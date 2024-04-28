# Introduction to GraphQL

## Why GraphQL?
- Для нашего мобильного приложения требуется гибкий бекенд, фронтенд будет очень динамично расти в 
требованиях. Разработать для каждого случая REST-API будет не быстро, хлть и надежно. Поэтому, мы будем отдавать 
данные по необходимости клиента.

##  Why not NoSQL, MongoDB?
- У нас есть четкая структура данных, для метаданных можно создать колонку c JSONb
и получать данные по запросу. Postgres удовлетворяет требованиям модели данных.

## Problems
- Пока не понятно в каком лучше виде вести кодовую базу - или максимально разбивать функционал
дабы не допустить связанности компонентов или разбить на минимальные группы, например на модули, что гораздо удобнее

## Links
- Using GraphQL with Python – A Complete Guide - https://www.apollographql.com/blog/complete-api-guide
- Open source code, doc, examples - https://github.com/strawberry-graphql