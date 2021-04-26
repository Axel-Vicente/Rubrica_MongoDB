# Rubrica_MongoDB
I leave a small configuration code to start a MongoDB docker 

# Some quick tips after logged-in MongoDB
### Show databases:

```
show dbs
```
### Create new non-existant database:

```
use mydatabase
```
### Show collections:

```
show collections
```
### Show contents of a collection:

```
db.your_collection_name.find()
```
### Save a data to a collection:

```
db.your_collection_name.save({"name":"Sony AK"})
```
### Show database version:

```
db.version()
```
