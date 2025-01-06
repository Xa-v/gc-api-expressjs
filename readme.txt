SQL query for admin account

INSERT INTO `accounts`(`id`, `username`, `passwordHash`, `firstName`, `lastName`, `role`, `resetToken`, `resetTokenExpires`, `passwordReset`, `created`, `updated`, `dateDeleted`, `isActive`, `isDeleted`, `dateReactivated`) VALUES (1, 'XavAdmin', '$2a$10$t9sqf1p.xYijXtel8uLqperPOPy0YsJcSUB2gbp8PMrhdKkNHGDQK', 'Marc', 'Xavier', 'Admin', NULL, NULL, NULL, '2024-08-23 02:54:06', '2024-08-24 17:00:59', '2024-08-24 16:29:09', 1, 0, '2024-08-24 17:00:59');


change Database NAME in config.json file