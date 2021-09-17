## Dictionnaire de données :

### User (user)
| Champ | Type | Spécificités | Description |
|-----------|-----------|-----------|-----------|
| id | INT | PRIMARY KEY, NOT NULL, UNSIGNED, AUTO_INCREMENT | The user's id |
| username | VARCHAR(180) | NOT NULL | The user's username |
| password | VARCHAR(255) | NOT NULL | The user's password |
| roles | longtext | NOT NULL | The user's role (by default, user has a role_user) |

## Liste de routes :

| Endpoints | Route names | Description |
|-----------|-----------|-----------|
| /login | app_login | Allows to log in | 
| /logout | app_logout | Allows to log out | 
| / | home_main | Returns home page | 
| /register | user_add | Returns page with form to create a new user | 
