## AWS Identity and Access Management

* Login as root user
 * Create policies first
    * Click policy - select a service (EC2) - Manual action (tick all EC2 box) as shown below 
 ![alt text](images/Capture1.PNG)
 
    * Resources (click all) as shown below 
    ![alt text](images/Capture2.PNG)

    * click next to go to next page - input policy name (Developers) - give description (This allows developers access EC2 instance) as shown below
    ![alt text](images/Capture3.PNG)

    * Click create policy.
    ![alt text](images/Capture4.PNG)

* Create group for the developers
    * Click user groups - create group - Enter user group name (Dev-team) - add users (Rokeeb) to the group
    ![alt text](images/Capture9.PNG)

    * Add a policy for this user group. Add Devs policy that was just created, policy-for-devs
    ![alt text](images/Capture10.PNG)

    * Click create user group
    ![alt text](images/Capture11.PNG)

* Creating Iam User for Rokeeb
    * Select users - click create user - type in the username (Rokeeb) - tick the box, provide user access to AWS management console - tick the box, I want to create an Iam user - console password
    ![alt text](images/Capture5.PNG)

    * After setting up password, click next. Then select attach policy directly - filter by type, chosose customer managed. Then search for your policy created earlier (policy-for-devs) and select. 
    ![alt text](images/Capture6.PNG)

    * Then click next to review and create
    ![alt text](images/Capture7.PNG)

    * Then create user
    ![alt text](images/Capture8.PNG)

* Created another user, Abbey and added to the Dev-team group
![alt text](images/Capture12.PNG)
![alt text](images/Capture13.PNG)


     