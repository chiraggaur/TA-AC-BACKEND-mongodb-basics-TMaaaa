writeCode

Write command to

- List collections from a database.

// show Collection();

- create a new collection in your country database which you created recently.

-db India
-db.createCollection()

Write code to:-

- crate a database named `weather`
  //use weather
- create a capped collection named `temperature` with maximum of 3 documents and try inserting more than 3 to see the result.
  //db.createCollection("temperature", {capped:true, size:10000, max:3})
- create a simple collection named `humidity`
  //use weather
- check whether `temperature` collection is capped or not ?
  // no
- Delete `humidity` collection and then the entire database(weather).

// db.humidity.drop()
