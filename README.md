# If-custom-post-type-post-not-open-in-single


/* Flush rewrite rules for custom post types. */
add_action( 'after_switch_theme', 'jeba_flush_rewrite_rules' );
 
/* Flush your rewrite rules */
function jeba_flush_rewrite_rules() {
     flush_rewrite_rules();
}
