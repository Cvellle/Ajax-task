# Instructions

## Download the folder

```
git clone https://github.com/Cvellle/Ajax-task.git

```

## Create table with in test database:

```
CREATE TABLE usersNikola ( user_id int(10) NOT NULL AUTO_INCREMENT,
                    first_name varchar(255) NOT NULL,
                    last_name varchar(255) NOT NULL,
                    gender varchar(255) NOT NULL,
                    birth_year varchar(255) NOT NULL,
                    address varchar(255) NOT NULL,
                    city varchar(255) NOT NULL,
                    status tinyint(2) NOT NULL,
                    PRIMARY KEY (user_id),
                    KEY first_name (first_name),
                    KEY last_name (last_name),
                    KEY gender (gender),
                    KEY birth_year (address),
                    KEY address (last_name),
                    KEY city (city)
                   ) ENGINE=InnoDB DEFAULT CHARSET=utf8;
```

## Open it with url:

```
http://localhost/Ajax-task/

```

### Ajax and fetch (comented) options