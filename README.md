# BWPaginationCSS
This consists of few lines to add in the CSS stylesheet (style.css) in Wordpress in order to have a similar pagination look to the paginations in Bootstrap 4 despite the lack of flexibility on styling the pagination using Wordpress function the_posts_pagination().

A sample code on how to use this inside index.php:

    the_posts_pagination(
      array( 'mid_size' 	=> 		  2,
      'prev_text' 		    => 		  '&lsaquo; '. __( 'Previous Page', 'jazz' ),
      'next_text'		      => 		  __( 'Next Page', 'jazz' ) . ' &rsaquo;',
    ));
