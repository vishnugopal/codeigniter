This is a customised CodeIgniter deployment package. 

The only obvious differences are that the "application" folder has been moved from system/ to its own top-level and index.php has been moved to a new "public" folder inside application/. 

This is a la Rails, and allows for:
* clean separation of system and application code.
* easier upgrading.
* lots of connected applications for a single system/
* and only exposing application/public/ to a web server that leads to better security by default.