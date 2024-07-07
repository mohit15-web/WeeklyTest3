1. find all the products available in db
  db.product.find()
 
2. find all the products whose price is greater than 50
    db.product.find({ price : {$gt : 50}})
