<h3>1. Run collection</h3>

      newman run API Booker Data Driven.postman_collection.json -e Production.postman_environment.json -d data.csv
  
<h3>2. Install HTML report</h3>

     npm install -g newman-reporter-html

<h3>3. Run collection and export HTML report</h3>
   
     newman run API Booker Data Driven.postman_collection.json -e Production.postman_environment.json -d data.csv -r html
     
<h3>4. Install HTML report-extra</h3>

     npm install -g newman-reporter-htmlextra

<h3>5. Run collection and export HTML report-extra</h3>

     newman run API Booker Data Driven.postman_collection.json -e Production.postman_environment.json -d data.csv -r htmlextra



**Docs:** https://www.npmjs.com/package/newman-reporter-htmlextra
