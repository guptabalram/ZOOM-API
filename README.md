# ZOOM-API
Creating a Meeting on Zoom using Zoom API and PHP


composer require guzzlehttp/guzzle




 *store the access token in the database*
 
CREATE TABLE `token` (
 `id` int(11) NOT NULL AUTO_INCREMENT,
 `access_token` text NOT NULL,
 PRIMARY KEY (`id`)
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4;
