// Admin Favicon Function for functions.php
add_action('admin_head', 'show_favicon');
function show_favicon() {
echo '<link href="ADD YOUR FAVICON LINK HERE" rel="icon" type="image/x-icon">';}
