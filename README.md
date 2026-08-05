## Description 
SingleSelectDropdown control "converts" a text field into a dropdown populated from values 
stored in a Dataverse table. 
Simply select a source table and the field whose value should be stored in the text field. 
Optionally, you can specify a description field to provide additional context and a filter to limit 
the available options. 
https://youtu.be/XbAVxAQVH4Y
## Common scenarios 
- A field was originally created as text but later needs to be extended with a dropdown 
(e.g. adding a country dropdown to the standard Country/Region field on Account to 
simplify user input).  
- You want Choice-like functionality where available values can be managed through a 
Dataverse table/App. 
- You want a lookup-like experience without being tied to an actual relationship (e.g. 
referring to a table with temporary data that is constantly recreated).  
- You want to build a Business Rule with a condition based on a lookup value without 
being tied to a specific GUID.  
## Notes 
This control is intended to simulate a Choice field. Therefore: 
- It is not intended for very large lists and does not support pagination.  
- It does not provide lookup-style search. However, values are sorted alphabetically, and 
typing automatically jumps to the first matching value. 
