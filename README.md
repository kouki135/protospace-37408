# ProtoSpaceのER図

|users テーブル                            |
|                                         |
|email (string型, NOT NULL, ユニーク制約)   |
|encrypted_password (string型, NOT NULL)
|name (string型, NOT NULL)
|profile (text型, NOT NULL)
|occupation (text型, NOT NULL)
|position (text型, NOT NULL)



# テーブル設計

## users テーブル

| Column             | Type   | Options     |
| ------------------ | ------ | ----------- |
| name               | string | null: false |
| email              | string | null: false |
| encrypted_password | string | null: false |


* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
