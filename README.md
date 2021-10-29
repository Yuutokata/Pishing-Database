# Pishing Database

Hello and welcome to this Database. This Pishing Database has over **75k** Pishing Domains and it gets updated every Sunday. 

## How to use the Database?

You could download the domains.json but you should rather call 

    https://raw.githubusercontent.com/Yuutokata/Pishing-Database/main/database/domains.json

and get it as a json and loop through it.

## How do we detect Pishing Links/Domains?

We detecting the Pishing Domains through other Api's and more. 

## Why we doing this?

Yea you could use the Api instead of this Database, but this Database has no Rate Limit and more Domains than a normal Api.

## My Domain is there how can i remove it?

You "can't" pls contact me so i can  remove you Domain from the Database. 

## Python Example

	
    import requests
    
	r = requests.get("https://raw.githubusercontent.com/Yuutokata/Pishing-Database/main/database/domains.json")
	
	for domain in r.json():
	
		if "https://google.com" == domain:
			print("Pishing Domain")
			
		else:
			pass
