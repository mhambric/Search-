# Search
# (Front of index card) 
Search Items by keywords  

 As a developer, I want to call the search microservice so that I can find items in my dataset that match a given keyword. 

# (Back of index card) Acceptance criteria 

Given a request to add an item,  when the microservice receives the request, then it will append the notification to notifications.json and confirm success in response.json with message “Item_1 was Added!! ”. 

 Given invalid or missing data, When the request is processed, Then it will respond with "Status: Error Request Not Valid.” 

 # Quality attributes & Non-functional requirements 

Reliability: Must save notifications and confirm success within 3 seconds. 

Usability: Messages must be formatted as valid JSON that can be parsed by any main program. 

 # (Front of index card)
Seach Items by ID  

As a developer, I want to call the search microservice so that I can find a specific record by its unique ID. 

# (Back of index card) Acceptance criteria 

Given a search request containing an ID, when the microservice reads the data file, then it will return the exact record that matches the ID. 

Given an invalid or non-existent ID, when the microservice finishes searching, then it will respond with "Item not found" in JSON format. 

# Quality attributes & Non-functional requirements 

Reliability: Must always return the correct record that matches the ID. 

Efficiency: Should perform lookup operations within 3 seconds with minimal resource use. 

 

 


