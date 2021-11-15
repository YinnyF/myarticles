# myarticles

Rails RESTful API practise

DB: MySQL
API Testing: Insomnia

`http://localhost:3000/api/v1/articles`

# Usage
Install dependencies:
`bundle install`

To start server:
`rails s`

Start MySQL server, then migrate the db:
`rails db:migrate`

Seed random data in the DB:
`rails db:seed`

## Actions on Article
1. index the article (GET all articles from db)
2. show an article (GET one article)
3. create an article (POST)
4. destroy an article (DELETE)
5. update an article (PUT)
