                                           ## Bookings-etl

We are using Databricks Community Edition for Execution.

### Steps to create Account:
1. Go to the [Databricks Community Edition sign-up page](https://databricks.com/try-databricks).
2. Fill in the required information, including your username, email, and password.
3. Click on the "Create Account" button to create your Databricks Community Edition account.


### Creating a cluster:
1. Login to your Databricks Community Edition account.
2. Click on the "Clusters" tab.
3. Click on the "Create Cluster" button.
4. Configure the cluster settings, such as name, instance type, and worker nodes.
5. Optionally, specify advanced options like libraries and environment variables.
6. Click on the "Create Cluster" button to create your cluster.

![this is a screenshot of the create cluster](../images/create_cluster.png)

### Cloning the Repository to local:
To clone a GitHub repository to your local machine, follow these steps:

1. Open your terminal or command prompt.
2. Change your current working directory to the location where you want to clone the repository.
3. Use the `git clone` command followed by the repository URL.

   ```shell
   git clone https://github.com/hemanth-hrs/bookings.git


### Uploading the data files:
To upload data from a local folder to the "/Filestore/Tables/" directory in the Databricks data section, follow these steps:

1. Navigate to the Databricks data section.
2. Create or select the target folder where you want to upload the data.
3. Click on the "Upload" button.
4. Choose the files or the entire local folder to upload.
5. Start the upload process by clicking "Upload" or "Open".
6. Wait for the upload to complete.
7. Once the upload finishes, the files will be available in the selected folder under "/Filestore/Tables/".

![this is a screenshot of the data upload](../images/data_upload.png)

### Uploading script file to Databricks:
To upload a .ipynb file to Databricks Workspace, follow these steps:

1. Navigate to the Databricks Workspace homepage.
2. Select the folder where you want to upload the .ipynb file or create a new folder.
3. Click on the "Upload" button.
4. Choose the .ipynb file from your local computer.
5. Wait for the upload to complete.
6. Once the upload is finished, you will see the .ipynb file in the selected folder within the Databricks Workspace.

![this is a screenshot of the uploading script](../images/notebook_upload.png)

### Run the Script:
To run a notebook in Databricks Community Edition, follow these steps:

1. Navigate to the Databricks Community Edition workspace homepage.
2. Select the notebook you want to run from the list of available notebooks.
3. Click on the notebook to open it.
4. In the notebook editor, click on the "Run All" button or use the shortcut "Ctrl + Enter" to run all cells in the notebook.
5. Wait for the notebook execution to complete.

![this is a screenshot of the run script](../images/run_notebook.png)













