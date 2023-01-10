# day-37
db.task37.insertMany()



1)db.task37.find({})

2)db.collection.find({
    product_price: {
      "$lt": 800,
      "$gt": 400
    }
  })
  
  3) db.collection.find({
    product_price: {
      "$not": {
        "$lt": 600,
        "$gt": 400
      }
    }
  })
  
  4.db.collection.find({
    product_price: {
      "$gt": 500
    }
  })
  
  5.db.collection.find({},
    {
      _id: 0,
      product_name: 1,
      product_material: 1
    })
    
    6.db.collection.find({
        id: "10"
      })
      
      7.db.collection.find({},
        {
          _id: 0,
          product_name: 1,
          product_material: 1
        })
        
        8.db.collection.find({
            product_material: "Soft"
          })
          
          9.db.collection.find({
            product_color: "indigo",
            product_price: 492.00
          })
          
         
