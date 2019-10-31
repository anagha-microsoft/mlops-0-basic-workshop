# mlops-0-basic-workshop

1.  Create an Azure resource group <br>
2.  Provision:<br>
a) A storage account version 1 in resource group from #1, create a blob container called training; We will store training data there.<br>
b) A devops project called mlops-0-basic in dev.azure.com<br>
c) An Azure ML workspace in the resource group from #1<br>
<br>
3.  Upload training dataset to storage account<br>
a) Change the permissions of the container to allow anonymous access<br>
b) Upload the CSV file within the training dataset directory to the container<br> 
