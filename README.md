# AD_Batch_Demo

1. Started working on the LWC code + custom metadata types, but DML operations aren’t allowed on custom metadata in the Partner or Enterprise APIs. Each change triggering a record creation is treated as a deployment. MDT not showing in the flow as well. 
https://www.apexhours.com/difference-between-custom-setting-and-custom-metadata-salesforce/

2. Started with custom setting, faced the issue - Number of DML statements: 1 out of 0 ******* CLOSE TO LIMIT. As the imperative apex method has the    @AuraEnabled(cacheable=true)

3. Faced the issue - SetupOwnerId duplicates value on record with id: 00D5j00000DqR1NEAV, as the custom setting is Hierarhy. List custom setting is greyed out.

4. ![image](https://github.com/alekhSharma/AD_Batch_Demo/assets/28496671/9a2b81a9-02c5-4ac1-8773-3d1fc0a8922e)


  
