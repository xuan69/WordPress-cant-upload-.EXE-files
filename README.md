# WordPress can't upload.EXE-files
WordPress only accepts general images, video and document formats, If you try to upload any other file type you will get security warning Sorry, this file type is not permitted for security reasons.

To quickly allow, add this to your **wp-config.php**

define(‘ALLOW_UNFILTERED_UPLOADS’, true);
