# users

## Columns

| Name | Type | Default | NOT NULL | Comment |
| ---- | ---- | ------- | -------- | ------- |
| id | integer | nextval('users_id_seq'::regclass) | true |  |
| username | varchar(50) |  | true |  |
| password | varchar(50) |  | true |  |
| email | varchar(355) |  | true |  |
| created | timestamp without time zone |  | true |  |
| updated | timestamp without time zone |  | false |  |