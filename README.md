# I wrote code in [this website](https://markdown-editor.github.io/) 
## Output of the code:
<img width="839" alt="Screen Shot 2022-06-17 at 13 57 56" src="https://user-images.githubusercontent.com/93094921/174285870-329342d7-6b94-4640-b44e-934887ea1985.png">

Code:
<pre>
>Header

<button type="button"> +New User</button> &nbsp;&nbsp;&nbsp; <input type="checkbox"> Hide Disabled User &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <button type="button" color=red> Save User</button>

>Header
-“NewUser” button with a plus sign (where you can add new user to the database)
-“Hide Disabled User” checkbox button (where you can hide or unhide disabled user)
-“Save User” button on the far right of the page (Allows the save user to a system when the new user form is filled. Only usable when the form is filled)

>Section
-User table with 4 columns which contains “ID”, “User Name”, “Email”, “Enabled”. Each columns should be filtered and sorted in itself. (Shows users registered to the system)

| ID          | User Name       | Email                    | Enabled |
| :---:       |    :----:      |          :---:            | :---:   |
| 1           | AdminUser       | admin@piworks.net        |true     |
| 2           | Test User       | tesuser@piworks.net      |true     |

>Section cont.
New User Form ( Placed next to User Table)
This is new user form where the user can fill the above information and the system will save the user.
Username: type: text fields
Display name: type: text fields
Phone: type: text field but only accept integer values
Email: type: text fields
User Roles: Dropdown list box (options: Guest, Admin, SuperAdmin)
Enabled: check box (If it is selected, take the value of “true” in the user table “enabled” column.


**Username:**&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <input type="text" size="50">

**Displayname:**&nbsp;&nbsp;&nbsp;&nbsp; <input type="text" size="50">

**Phone:**&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <input type="text" size="50">

**Email:**&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<input type="text" size="50">

**User Roles:**&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <input type="text" size="50"> 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<select name="" size="3">
  <option value="Guest">Guest</option>
  <option value="Admin">Admin</option>
  <option value="SuperAdmin">SuperAdmin</option>
</select>

You can find screenshots of the code below:
<img width="1493" alt="Screen Shot 2022-06-17 at 13 59 40" src="https://user-images.githubusercontent.com/93094921/174285930-80458ea9-2cea-4f29-bb77-82128526bfe3.png">

<img width="1434" alt="Screen Shot 2022-06-17 at 13 59 51" src="https://user-images.githubusercontent.com/93094921/174285953-54cd4c0f-c118-4f93-8daf-16e5bd6553d2.png">
