writeCode

Write code to:-

- create a database named `sports`.
  // use sports

- list all databases present in local mongod server.
  // show dbs

- create 3 collections named `cricket`, `football`, `TT` in sports databse.
  // db.createCollection('football')...

- add multiple players in those collections which should have fields like `name`, `age` and `email` and `bid_price`.
  //db.TT.insert({name:"akshat",age:"21",email:"xyz@gmail.com",bid_price:"200k"}) ...

- list all collections in sports database.
  // show collections

- rename `TT` collection to `tennis`.
  //db.TT.renameCollection('tennis')

- create a capped collection called `khokho` which should have max 3 documents.
  //db.createCollection('Khokho',{capped:true,size:1024,max:3})

  Try inserting more than 3 and see what happens?
  // it will add the latest document but remove the first inseted one from the list.

- check whether a collection is capped or not?
  //db.Khokho.isCapped()

- drop all documents from `football` collection.
  //db.football.remove({})

- delete cricket collection completely.
  // db.football.drop()

- delete sports database.
  //db.dropDatabase()

- check which database you are connected to ?
  //db
- connect to test database
  //use test
