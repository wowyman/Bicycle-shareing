How to install project:
1. Run apache jena fuseki:
     cd <path-to-apache-jena-fuseki> 
     fuseki-server --update --mem /ds
2. Open the page of Apache jena server : localhost:3030 and add create database named "TestTripleStore", then add file "Project_data2.ttl" to the database.
3. Open root file of project.
    Install packages need to run:
        cd client
        npm install
        cd server
        npm install
4. Run the project:
    Open root file of project in File Explorer, and excute file both.bat
5. Open localhost:8080 to see app
