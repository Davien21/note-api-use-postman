## NOTES API  
### An API for a Notes APP  

This api gives access to the file system using the **fs** module of nodejs.
This API will allow you to:  

1. View a list of all existing note files. 
2. Read the content of note files.  
3. Create new note files.
4. Update existing note files.   
5. Delete a note file.   
6. Rename a note file.   

#### Things to consider:
1. Review the **NoteClass.js** file to see the Class described and how it's methods work.  
2. Adjust the directory of the notes you handle from the NoteClass file if you do not like the current structure

#### How to use:  
1. Open the **notes-api.js** file and enter the **node notes-api.js** command  
2. Open **Postman** and create any of the following requests to get responses from the API:  
> - GET or POST request to the **"/"** route to return a JSON containing data with the list of Note files  
  
#### The Following require you pass in the specified parameters using the x-www-form-urlencoded option:
> - POST request to the **"/create"** route by passing in the **name** and **content** of the new file.  
> - POST request to the **"/delete"** route by passing in the **name** of the file you wish to delete.    
> - POST request to the **"/update"** route by passing in the **name** and **content** of the file you wish to update.    
> - POST request to the **"/rename"** route by passing in the **name** and **new_name** of the file you wish to rename.   

#### There are no dependencies and testing can easily be done via **Postman**.

Made with love from an intern at **WeJapa**
