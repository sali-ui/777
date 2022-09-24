
<?php
define('_MN_USER', 'f6e1ad2d926133444774024ca9ff6783d86b6983');
require_once($_SERVER['DOCUMENT_ROOT'].'/'._MN_USER.'/magenet.php');
$magenet = new Magenet();
echo $magenet->getLinks();
?>
