# json-server-local-api
This is to create some api in the local server



1. DownLoad node.js
link : https://nodejs.org/en/download/
2. Open cmd and run below command
-->> npm install -g json-server
3. Again run below command
-->>json-server --watch db.json
4. Now go to the file location where you have ran the step 3 command and search for db.json file
5. Right click on the db.json file and choose option "Edit with Nodepad++"
6. Clear all the data of the file and copy+paste the below content
-->>
{
  "users": [
    {
      "firstName": "tamanna",
      "lastName": "tuly",
      "subjectId": "1",
	  "id": "1"
    },
	{
      "firstName": "ria",
      "lastName": "khan",
      "subjectId": "2",
	  "id": "2"
    },
	{
      "firstName": "morium",
      "lastName": "meher",
      "subjectId": "1",
	  "id": "3"
    }
  ],
  "subjects": [
    {
      "id": 1,
      "name": "Automation"
    },
	{
      "id": 2,
      "name": "Manual"
    }
  ]
}

7. save the file and go to http://localhost:3000/ from your browser
