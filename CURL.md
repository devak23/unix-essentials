## CURL

|	COMMAND										|	Comments										|
|-----------------------------------------------|--------------------------------------------------	|
|	curl https://jsonplaceholder.typicode.com/	|	Generates and prints the HTML page for the site	|
|	curl -i https://jsonplaceholder.typicode.com/users/10	|	Gives back the JSON response with headers	|
|	OR curl --include https://jsonplaceholder.typicode.com/users/10	|	|
|	curl -d "userId=100&title=Get Milk&completed=false" https://jsonplaceholder.typicode.com/users/	|	Creating a POST request	|
