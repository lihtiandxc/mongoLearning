# Query on Embedded/Nested Documents
db.inventory.find( { size: { h: 14, w: 21, uom: "cm" } } )
https://docs.mongodb.com/manual/tutorial/query-embedded-documents/

# Query an Array
db.inventory.find( { tags: ["red", "blank"] } )
https://docs.mongodb.com/manual/tutorial/query-arrays/

# Query an Array of Embedded Documents
db.inventory.find( { "instock": { warehouse: "A", qty: 5 } } )
https://docs.mongodb.com/manual/tutorial/query-array-of-documents/
