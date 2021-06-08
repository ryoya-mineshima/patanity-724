# README

# 機能

投稿機能
ユーザー管理機能
検索機能
コメント機能

# テーブル設計

## usersテーブル
| Column             | Type    | Options     |
| ------------------ | ------- | ----------- |
| nickname           | string  | null: false |
| email              | string  | null: false |
| encrypted_password | string  | null: false |
| first_name         | string  | null: false |
| last_name          | string  | null: false |
| first_name_kana    | string  | null: false |
| last_name_kana     | string  | null: false |
| gender             | integer | null: false |
| birth_day          | date    | null: false |


## postsテーブル

## ｃommentsテーブル

| Column  | Type       | Options                        |
| ------- | ---------- | ------------------------------ |
|  | string     | null: false                    |
|  | text       | null: false                    |
|  | text       | null: false                    |
|  | references | null: false, foreign_key: true |