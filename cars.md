# CARS

| Column      | Type        | Attributes                 |
| ----------- | ----------- | -------------------------- |
| id          | BIGINT      | PRIMARY_KEY AUTO_INCREMENT |
| plate       | CHAR(7)     | NOT_NULL UNIQUE            |
| model       | VARCHAR(20) | NOT_NULL                   |
| kilometers  | MEDIUMINT   | NOT_NULL                   |
| color       | VARCHAR(20) | NULL                       |
| supply      | CHAR(1)     | NULL                       |
| spare_wheel | TINYINT(1)  | NULL                       |
| seats       | TINYINT     | NULL                       |
| doors       | TINYINT     | NULL                       |
| weight      | SMALLINT    | NULL                       |
| height      | FLOAT(3, 2) | NULL                       |
| length      | FLOAT(3, 2) | NULL                       |
| width       | FLOAT(3, 2) | NULL                       |

<br>

Scaletta supply:

- B: benzina
- D: diesel
- E: elettrica
- I: ibrida

(Poi non so se ne esistono altri tipi)
