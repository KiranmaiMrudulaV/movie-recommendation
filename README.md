# movie-recommendation

# Run Python notebook 'Database Building.ipynb'
# Additional commands to run before running app.py.
mongosh
show dbs
use movrec
show collections
db.createCollection("Users")
db.Counts.insertOne({ "_id": 1, "users": 1 })
db.Movies.createIndex({ title: "text" })

