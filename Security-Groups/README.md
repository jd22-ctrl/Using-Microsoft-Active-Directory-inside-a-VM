# Create Security Groups

## Objective

Create security groups to simplify permission management.

## Actions Performed

- Opened Active Directory Users and Computers.
- Created new Global Security Groups.
- Assigned descriptive names.
- Verified successful creation.

## Process:

Go into the **Organizational Unit** you want the certain security permission assigned to. For me it was the IT Department.
In the empty spot, right click and select `New`, then `Group`

![Creating Security Permissions](creating-groups-1.png)

Now you would put the correct name for the group ie: Managers, Interns, HelpDesk.  

Now the Group Scope can be set as requested. 

`Domain Local`:Its gives the group or users that are assigned to it certain permissions.

`Global`:Gives the users within this group a name to organize them within that domain.We well be using Global for this example.

`Universal`:Combines users/groups across different domains.
![Creating User Groups](group-scopes-2.png)


Now you can double click the `Group` you just made to pull up this menu.


Now click on `Members`, this is where you can add the members you want in said group.
![Selecting members for the group](making-groups-3.png)



Click `Add`.
![Adding members](making-groups-4.png)

Now in the box below, type the users **First** and **Last** name with the correct pronunciation.
Then click `Check Names` to find the user within the domain.
![Adding members](making-groups-5.png)


After the correct name is shown, click on `Ok`
![Finishing the member act](making-groups-6.png)

A box will show showing the users name, if its correct then click `Apply`
![Confirming the addiction of the user](making-groups-7.png)
