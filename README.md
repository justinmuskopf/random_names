# random_names
All names were sourced from *names.mongabay.com*
## Contents
* `male_first_names.txt` - Contains over 1,200 typically Male first names
* `female_first_names.txt` - Contains over 4,000 typically Female first names
* `last_names.txt` - Contains over 18,000 last names
* `1000000_names.txt` - Contains 1,000,000 randomly generated names from the list above
* `customers.sql` - A Database that contains all 1,000,000 random names as "customers"
	- The `customer` table contains `customer` objects of schema:
		```json
		{
		    "id": "int",
		    "firstName": "string",
		    "lastName": "string"
		}
		```
