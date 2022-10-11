# AUX PROJECT 1: SHELL SCRIPTING

- Write a shell script named Onboard.sh to onboarding 20 users. The script must meet the following conditions:

- Create the project folder called Shell

- Create a csv file named names.csv inside the Shell directory

- Open the names.csv by running this command below:
   
   `cat names.csv`
   
   -A list of created names(Users) will appear as seen in the screenshot below: 
   
   ![List of the created Users](https://user-images.githubusercontent.com/65022146/195077835-97688028-7964-422d-ab26-61f35bcb08db.png)

- The script you created should read the CSV file, create each user on the server, and add to an existing group called developers (You will need to manually create this    group ahead).

- Ensure that your script will first check for the existence of the user on the system, before it will attempt to create that it.

- The Sript Implementation is shown on the two screenshots below:

   ![new sript 1](https://user-images.githubusercontent.com/65022146/195084063-ce37588f-f2c5-4c18-a453-dae3c9e6ce68.png)

   ![script 2](https://user-images.githubusercontent.com/65022146/195084119-d46840b6-5650-4d47-ba6f-78801efa6703.png)

- Ensure that the user that is being created also has a default home folder such as the screenshot below:

   ![Accesss to Ifeanyi](https://user-images.githubusercontent.com/65022146/195085775-e92360de-87ab-4a61-bf7f-0ffac6af8d34.png)

- Ensure that each user has a .ssh folder within its HOME folder. If it does not exist, then create it.

- For each user’s SSH configuration, create an authorized_keys file and add ensure it has the public key of your current user.

- Login or connect one of the users by using the newly created authorized_keys and the public IP address of the Instance

- When login is successful, you should be able to see an output as seen in the screenshots below:

![Logged in as Ifeanyi](https://user-images.githubusercontent.com/65022146/195081160-59ce7046-450f-4e08-9546-7088a6b4607c.png)

![Logged in as Ifeanyi 2](https://user-images.githubusercontent.com/65022146/195084647-5b056526-5011-4d33-b7ba-4e1100e67dad.png)

- And this is where Aux Project-1 successfully comes to an end.
