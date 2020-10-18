The file queries.py contains the following:

The database used for this project is Luis Rocha’s Chinook Database(https://github.com/lerocha/chinook-database), modified for use with Python.

Implemented the following functions in Python:
	select(relation, predicate)
		The predicate for select() is a function that takes a single namedtuple as an argument and returns True or False.

	project(relation, columns)

	rename(relation, new_columns=None, new_relation=None)
		The new_columns and new_relation parameters to rename() are optional. if neither argument is provided, return the original relation.

	cross(relation1, relation2)

	theta_join(relation1, relation2, predicate)
		The predicate for theta_join() takes two namedtuples and return a bool.

	natural_join(relation1, relation2).



The file queries.py also contains four variations of the query - Albums by the artist “Red Hot Chili Peppers.” :
	Combining 𝜎 and ⨯ to implement 𝜃-join
	Performing 𝜎 after 𝜃-join
	Performing 𝜎 before 𝜃-join
	Natural join

All of the queries above return the following set:
{Result(Title='Blood Sugar Sex Magik'),
 Result(Title='By The Way'),
 Result(Title='Californication')}
