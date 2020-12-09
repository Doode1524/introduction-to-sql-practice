# Introduction To SQL Practice

Your challenges!

1. Create a database called pet_shop.db
2. Create two tables pet and owner

- pet attributes should include: (don't forget it's primary key!)

  - name Text
  - age INTEGER
  - breed species
  - owner_id INTEGER (belongs to owner)

- owner attributes should include: (don't forget it's primary key!)

  - name
  - age

  has many pets

3. Create 3 owners.
4. Create 3 pets for owner with the id of 1, create 2 pets for the owner with id of 2, create 1 pet for the owner with id of 3. Randomize the species, but have at least 2 of 1 species.

# Query Challenges!

Enter the database and test queries to make sure they work. If they are successful, copy your query into the README.

### Query Challenge 1

Select all the names of the pet that belong to Owner 2.

:Copy Correct Query Here:

### Query Challenge 2

Select the name and age of the oldest pet.

:Copy Correct Query Here:

### Query Challenge 3

Select the most common species of pet.

:Copy Correct Query Here:

### Query Challenge 4

List the names of owners and how many pets they have in descending order by the count of pets.

:Copy Correct Query Here:

### Bonus Challenge

If you have finished. And if time, try to alter the tables and the insertions to work with a many to many relationship. (This is completely open ended)

A pet has many owners
An owner has many pets

Query the pets and their owners in any format you choose.

:Copy Correct Query Here:
