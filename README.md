# Laboratory work #5
## Topic: Enforcing a Policy (cont'd)
Author: Cipciu Lina, FAF-193
-----
## Task:
* Select the settings to be enforced (a subset of "Failed", or all of them);
* Enforce the policy on at least 20 settings (edit the selected settings in your system);
* Rollback to the system's initial settings.

## Implementation:
1. Download Audit Policies for Windows from: www.tenable.com;
2. Import the manually downloaded policies;
3. Parse the data within the imported policy;
4. Save locally the set of policies in a json file;
5. Search by name for an option (via search bar);
6. Select/Deselect all options in one click;
7. Create and save a policy that contains only the selected options under the same name or a different one;
8. Perform an audit of the worstation, using the options that were selected;
9. Output the result of the ausit on screen;
10. Select the settings to be enforced;
11. Enforce the policy on the 20 settings;
12. Rollback to the system's initial settings.

## Used Technologies:
* PyCharm
* Tkinter for GUI
* Python 3.8