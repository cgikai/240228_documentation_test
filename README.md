# How to create a Joint
This tool works by placing a joint at the center of a vertex selection.

![alt text](https://github.com/cgikai/240228_documentation_test/blob/main/Rigging%20Tool_autoJoint.gif?raw=true)

To create a joint, follow these steps:
1. Create a vertex selection of your mesh
2. Click the corresponding Joint button

### Example: Creating the Pelvis

Create a selection around the pelvis area.

![alt text](https://github.com/cgikai/240228_documentation_test/blob/main/Rigging-Tool_Set-Up_Create-Selection_600.gif?raw=true)

Broad selections work if you're tight on time; however, the more precise your selection, the more accurate the joint placement will be, the better your rig will be. 

Next, click on the **Pelvis** button to create the joint. You'll see the indicator light turn green to show that the joint was successfully created. 

![alt text](https://github.com/cgikai/240228_documentation_test/blob/main/Rigging%20Tool_Pelvis%20Create%20-%20UI%20Close%20Up.gif?raw=true)

![alt text](https://github.com/cgikai/240228_documentation_test/blob/main/Rigging-Tool_Pelvis-Create_720.gif?raw=true)

Repeat this process for each Joint to create a full rig.

Use the indicator lights to see if you're missing joints.

# How to delete a Joint

Each joint has its own delete button. 

To delete a joint, click on the trash can icon to the right of the corresponding joint.

![alt text](https://github.com/cgikai/240228_documentation_test/blob/main/Rigging%20Tool_Pelvis%20Delete%20-%20UI%20Close%20Up.gif?raw=true)

![alt text](https://github.com/cgikai/240228_documentation_test/blob/main/Rigging-Tool_Pelvis-Delete_720.gif?raw=true)

# Creating the spine

To create the spine, follow these steps:
1. Create the Pelvis Joint
2. Create the Neck Joint
3. Click "Create Spine"

You cannot create the Spine without creating the Pelvis and Neck joints first.

Under the "Adjust Spine Joints" dropdown menu click "Create Spine". This will automatically place three evenly distributed Spine joints between the Pelvis and Neck.

![alt text](https://github.com/cgikai/240228_documentation_test/blob/main/Rigging-Tool_Spine_Create_720.gif?raw=true)

# Adding or Removing Spine Joints

To increase or decrease the amount of Spine joints, use the "Add Joint" and "Remove Joint" buttons. This will automatically redistribute the Spine joints to compensate for the change.

![alt text](https://github.com/cgikai/240228_documentation_test/blob/main/Rigging-Tool_Spine_Add-Remove_720.gif?raw=true)

If you've added or removed too many Spine joints, you can click "Reset Spine Joint Quantity" to reset the number of Spine joints to 3.

![alt text](https://github.com/cgikai/240228_documentation_test/blob/main/Rigging-Tool_Spine_Reset_720.gif?raw=true)
