## This Java reference sample shows how to CosmosDB Pagination can be achieved with ContinuationToken

## Steps 
git clone https://github.com/jyotsnaravikumar/azure-cosmosdb-java-pagination </br>  
cd azure-cosmosdb-java-pagination </br>  
Update AccountSettings.java with cosmosdb hostname and key </br>  
Run Main.Java </br>  

### This method returns a map with nextContinuationtoken and prevContinuationToken with resultsets Which can be used in UI
   QueryPageByPage();

### This method shows how to querying a Document with a list saved in a Collection into Cache which can be used sliced in UI code for pagination
### This example shows EHCache, however for centralized management rediscache can also be used
   executeSimpleQueryWithList();
