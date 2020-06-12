
## Jacoco
mvn clean org.jacoco:jacoco-maven-plugin:prepare-agent package

\target\site\jacoco\`index.html

##  Test  REST API
POST: Servistate HTTP
Header : Content-Type :application/json
{
  "firstName": "Souleymane",
  "lastName": "SANOGO",
  "emailId": "test@gmail.com",
  "createdBy":"admin",
   "updatedby": "admin"
}