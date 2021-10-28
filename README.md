# テーブル設計

  ## usersテーブル

| Column             | Type   | Options     |
| ------------------ | ------ | ----------- |
| email              | string | null: false |
| password           | string | null: false |
| name               | string | null: false |


  ### Association

- has_many :comics

  ## comicsテーブル

| Column             | Type       | Options     |
| ------------------ | ------     | ----------- |
| title              | string     | null: faise |
| catch_copy         | text       | null: faise |
| user               | references |             |
