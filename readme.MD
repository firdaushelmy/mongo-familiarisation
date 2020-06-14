This is my list of notes for MongoDB

```
### 14 June 2020

mongo
show dbs
use shopDB
db.products.insertOne({_id: 1, name: "Pen", price: 1.20})
show collections
db.products.find()
db.products.find({name: "Pencil})
db.products.find({price: {$gt: 1}})
db.products.deleteOne({_id: 2})

db.products.insert({_id: 3, name: "pew"})



```

```
db.products.insertMany([{
  _id: 2,
  name: "pencil",
  price: 0.80,
  stock: 12,
  reviews:[
    {
      authorName: "Mickey",
      rating: 3,
      review: "product is half the size"
    },
    {
      authorName: "Jackson",
      rating: 5,
      review: "great stuff! very durable"
      }
      ]
},
{
  _id: 3,
  name: "rubber",
  price: 1.20,
  reviews:[
    {
      authorName: "Sally",
      rating: 5,
      review: "NOICE"
      },
      {
        authorName: "Jack",
        rating: 4,
        review: "its okay i guess"
        }
]
}])

```
