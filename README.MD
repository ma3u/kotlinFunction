Create a Kotlin function in Azure Functions using Maven 
https://docs.microsoft.com/en-us/azure/azure-functions/functions-create-first-kotlin-maven?tabs=powershell


mvn archetype:generate ` "-DarchetypeGroupId=com.microsoft.azure" ` "-DarchetypeArtifactId=azure-functions-kotlin-archetype"

mvn clean package 
mvn azure-functions:run

localhost:7071/api/HttpTrigger-Java?name=Lori

mvn azure-functions:deploy
