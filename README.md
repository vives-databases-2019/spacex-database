# Gamereview database

## Import the Database


Go to the `/sql` directory and import the `spacex.sql` file in your database to get access to the tables for this exercise.

Execute the following command in this project directory with the `mysql` client:

```sql
source spacex.sql
```

Answer every question with:

1. The query that answers the question.
2. The results of that query.

Every query that returns more than 10 row must be reduced to the first 10 rows. (HINT you can do this in you query).

## Example

1. Give all product id's en product descriptions of all products.

```sql
SELECT prod_id, prod_desc FROM products;
```

```
+---------+----------------------------------------------------------------+
| prod_id | prod_desc                                                      |
+---------+----------------------------------------------------------------+
| ANV01   | .5 ton anvil, black, complete with handy hook                  |
| ANV02   | 1 ton anvil, black, complete with handy hook and carrying case |
| ANV03   | 2 ton anvil, black, complete with handy hook and carrying case |
| DTNTR   | Detonator (plunger powered), fuses not included                |
| FB      | Large bag (suitable for road runners)                          |
| FC      | Carrots (rabbit hunting season only)                           |
| FU1     | 1 dozen, extra long                                            |
| JP1000  | JetPack 1000, intended for single use                          |
| JP2000  | JetPack 2000, multi-use                                        |
| OL1     | Oil can, red                                                   |
| SAFE    | Safe with combination lock                                     |
| SLING   | Sling, one size fits all                                       |
| TNT1    | TNT, red, single stick                                         |
| TNT2    | TNT, red, pack of 10 sticks                                    |
+---------+----------------------------------------------------------------+
14 rows in set (0.00 sec)
```

### Get Exercise updates

Exercise instructions will be added. To get the latest instructions you need to pull them into your own project. This can be done with the following command:

```shell
git pull https://github.com/vives-databases-2019/spacex-database master
```

This will add or update the exercise.md file and its dependencies in your own project.

## Exercise

1. Amount of launches

´´´sql

´´´

```text

```

2. Amount of upcoming launches

´´´sql

´´´

```text

```

3. Amount of past launches

´´´sql

´´´

```text

```

4. Amount of successful launches

´´´sql

´´´

```text

```

5. Amount of successful past launches

´´´sql

´´´

```text

```

## Report

When you are ready and submitted the exercise, make sure to fill in the [report](./REPORT.md) file. Don't forget to commit it as well. Answer all questions and check the formatting by viewing the file on GitHub.