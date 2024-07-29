# Azure Crash Course

In this crash course we will be creating a Resource group, storage account, and a container to upload and store files in Azure.

Firstly, we will create a Resource group.

After you’ve created a subscription to Azure and logged into your portal, on the home page select “Resource groups,” circled in red below.

![Screenshot 1 Azure](https://github.com/user-attachments/assets/6478e636-6842-4093-af7c-0c20af57ab50)

After selecting “Resource groups” you will see this creation page. Click on the blue “+ Create” button. 

![Screenshot 2 Azure](https://github.com/user-attachments/assets/fb598430-7e33-4516-b02b-8b53d21a17bc)

Once you’ve selected “create”, you’ll be taken to this page. You can select the subscription you would like this Resource group to be added to, create a unique name for your Resource group, and select the region it be located in. Select “Next : Tags” when you finish this step.

![Screenshot 3 Azure](https://github.com/user-attachments/assets/242762cb-396d-40a8-870c-ca68f96b2a40)

Here, you can create tags for your Resource group. Tags allow for better organizational features and consist of a name and corresponding value. Select “Next : Review + create >” to go to the next page.

![Screenshot 4 Azure](https://github.com/user-attachments/assets/8b2a5bc3-1888-4426-9750-33a733b7ede1)

You will be taken to the validation page to ensure all the information you entered was accurate. After the validation is passed, click the “create” button in the bottom left corner.

![Screenshot 5 Azure](https://github.com/user-attachments/assets/59a5e07c-5566-4aa1-95c7-fbe7652ea2a8)

Lastly, you will be taken to this page to view your Resource group inside of your subscription.

![Screenshot 6 Azure](https://github.com/user-attachments/assets/b007565e-974f-49d4-873d-60c3862381bf)

CONGRATS!! YOU JUST CREATED YOUR FIRST AZURE RESOURCE GROUP!!


Now, we will create a storage account. 

To create a storage account, type “storage account into the search bar and click on the first option, circled in red. 

![Screenshot 7 Azure](https://github.com/user-attachments/assets/6b7cd24a-2df9-462e-aa3e-84701a48e249)

You’re then taken to this page. Click “create storage account.”

![Screenshot 8 Azure](https://github.com/user-attachments/assets/f0cc1c74-fd13-469b-91e5-20607948e54a)

Here you can select the subscription, Resource group, region, and performance that you want the storage account to be in. The storage account name needs to be globally unique. 

![Screenshot 9 Azure ](https://github.com/user-attachments/assets/0c6fe9ab-28d1-46ea-9dcd-aa4d62ca880d)

Scroll all the way down to the bottom of the page to explore redundancy options. Once finished, click “review and create.”

![Screenshot 10 Azure](https://github.com/user-attachments/assets/d55c3b69-07ad-46e4-9ff0-06f3ede27d08)

Now you’ll be taken to the review/validation page. If everything looks good to you, click on create.

![Screenshot 11 Azure](https://github.com/user-attachments/assets/d1d6c9d1-9ab3-4b26-a21c-1d9231ac582b)

After clicking create, you will see this page. It may take a few minutes for your deployment to validate everything but once it is finished you should see this screen, indicating that the storage account is officially created. (Click Go to resource to see inside of your storage account)

![Screenshot 12 Azure](https://github.com/user-attachments/assets/14e7eb31-944d-4e16-b715-0886b74d078a)

CONGRATS!! YOU JUST CREATED YOUR FIRST AZURE STORAGE ACCOUNT.

Next, we will create containers.

Inside your storage account you will see this page. Click on the tab “Containers” on the left-hand side. 

![Screenshot 13 Azure](https://github.com/user-attachments/assets/90d296ef-ae56-4842-b70a-bc168d1a9f8a)

Click “+Container” to create a container.

![Screenshot 14 Azure](https://github.com/user-attachments/assets/fd1174a0-5b07-4b53-ada6-f87588e2520d)

This will pop up on the right hand side for you to name your container. After that, click create in the bottom left corner. 

![Screenshot 15 Azure](https://github.com/user-attachments/assets/9b5e67d1-4651-449e-bef1-9d6a636bfb31)

Now the container that you just created is in the “Container” tab in the storage account it was stored in. 

![Screenshot 16 Azure](https://github.com/user-attachments/assets/b9db8d65-6cf7-4936-bc45-6a2f7b64d4ae)

Lastly, we will create and upload a file to our container inside of our storage account. 

Open your desktop text editor. I am running on a Windows 10 operating system, so my desktop text editor is notepad.

Now type anything you want into the application and then save the file.

Go back to your open container and click on the “upload” button. 

![Screenshot 17 Azure](https://github.com/user-attachments/assets/e07e0cf4-76d1-4f4e-a403-8efcf560d24d)

You should see this page open on the right hand side. Click on “browse for files” and click on the file that you saved from your text editor to your computer. 

![Screenshot 18 Azure](https://github.com/user-attachments/assets/893fc7d4-91e0-4aa1-9569-0ef3febd4a0c)

Then click Upload!

The text file will now be stored in the container. To edit it click on the 3 dots next to the word “Available” on the right side.

![Screenshot 19 Azure](https://github.com/user-attachments/assets/41b7f487-7cf8-4fe7-99b2-7ff378440b1f)

Here you can add more to the text file. Once you finish click the save button and your changes will be saved to that file.
