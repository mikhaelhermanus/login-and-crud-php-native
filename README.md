"# login-and-crud-php-native" 

use db name = "crud_db"

CREATE TABLE `users` (
  `id` int(11) NOT NULL auto_increment,
  `name` varchar(100),
  `email` varchar(100),
  `mobile` varchar(15),
  PRIMARY KEY  (`id`)
);

This project was made when I was in semester 3 when I was in college, and now crud + login is often a test requirement for entering a company
