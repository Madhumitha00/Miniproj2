# Miniproj2
<table><tr><td> <em>Assignment: </em> IS601 Mini Project 2  Business Management</td></tr>
<tr><td> <em>Student: </em> Madhumitha Srinivasan (ms2992)</td></tr>
<tr><td> <em>Generated: </em> 12/15/2022 9:53:52 PM</td></tr>
<tr><td> <em>Grading Link: </em> <a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IS601-005-F22/is601-mini-project-2-business-management/grade/ms2992" target="_blank">Grading</a></td></tr></table>
<table><tr><td> <em>Instructions: </em> <ol><li>checkout dev and pull any latest changes</li><li>Create a branch called MiniProject-2</li><li>Add all the baseline files first under a folder called BusinessManagement (included below)</li><li>Don't forget to copy your .env file from flask_sample into BusinessManagement</li><li>source the venv and pip install the requirements.txt</li><li>Run the BusinessManagement/sql/init_db.py script</li><li>Immediate add/commit/push to github</li><li>Open a pull request and keep it open until you're done adding the submission file</li><li>&nbsp;(optional) updated the deploy dev yml file and add MiniProject-2 so you can deploy to dev without needing to merge into dev</li><li>Make your code changes per the following requirements</li><ol><li>Important: run the test files indiviudally as you're working/testing to save on query quota usage</li></ol><li>Add/commit periodically (recommended after you implement a TODO item or checlist item)<br></li><li>Anywhere relevant add your ucid and the date you added the code (best to do this as you go)</li><li>You'll be capturing website screenshots from dev and code snippet screenshots (ensure you upload these properly as pull request comments to the pull request from step 5</li><ol><li>Note: You don't need separate screenshots for each checklist item, when possible it's recommended to try to capture multiple items together</li><li>Ensure all screenshots are properly captioned in the deliverable section</li></ol><li>You may save your progress when filling out this submission as often as you want</li><li>Once done, copy the markdown or download the md file and save it under the BusinessManagement folder</li><li>Do a final add/commit/push</li><li>Verify everything looks ok in the pull request</li><li>Merge the pull request</li><li>Make a new pull request from dev to prod and merge it</li><li>Navigate to the submission file under the BusinessManagement folder</li><li>Copy the github url to the exact file and submit it to Canvas</li></ol><div>You'll be implementing a basic Business Management site.</div><div>There will be some provided files fully working as-is and some skeleton files you'll need to fill in.</div><div>The files you need to fill in will have TODO items or comments mentioning what's expected.</div><div>There are provided test case files too that all must be passing for full credit. Do not edit these test case files.</div><div>The site will handle CRUD operations for Companies and Employees as well as allowing import of Company/Employee data via a csv file.</div><div><br></div><div>Baseline files:&nbsp;<a href="https://github.com/MattToegel/IS601/tree/F22-MiniProject-2">https://github.com/MattToegel/IS601/tree/F22-MiniProject-2</a></div><div>May want to download branch as a zip, then copy/paste the files into your repo</div><div><br></div><div>Provided files you don't need to edit:</div><div><ul><li>000_create_table_companies.sql</li><li>001_create_table_employees.sql</li><li>db.py</li><li>init_db.py</li><li>flash.html</li><li>company_dropdown.html</li><li>country_state_selector.html</li><li>upload.html</li><li>sort_filter.html</li><li>all test files</li><li>geography.py</li><li>__init__.py (remains empty)</li><li>Dockerfile</li><li>main.py</li><li>index.py</li></ul><div>All other files likely have requirements to fill in.</div></div><div><br></div></td></tr></table>
<table><tr><td> <em>Deliverable 1: </em> Identity Edits and Setup </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add screenshot of the index page being displayed (from dev)</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113865901/207225415-100c4250-bc25-4b46-82bf-5652f9d59265.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>In this we need change add DIAR with our UCID in the layout<br>of html and then the url should be visible in tyhe heroku dev<br>and in that page there should be brought to you by your name<br>and ucid.<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add screenshot from the DB extension of vs code / IDE</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113865901/207508921-35c13d90-0fe3-44f9-a480-68ab5f58c76e.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>In this we need to show that companies and employees table should be<br>visible whether empty or not and we need to show ucid and database<br>name should be visible .<br></p>
</td></tr>
</table></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 2: </em> Upload / Import CSV File (provided data.csv) </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add screenshot of /import route</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113865901/208006561-2818bd49-c1e7-4576-b304-25175cd82018.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>The code should check if the file is a .csv file otherwise reject<br>with a flash and 	CSV file should be read from the provided stream<br>as a dictionary and then	Extracted employee data should be append as a dictionary<br>to the employee list  Extracted company data should be to the company<br>list  and After each query a flash message should be generated many<br>records were processed If a particular list  list wasn&#39;t loaded or was<br>empty in the flask.<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Screenshots of the website when uploading the data.csv file</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113865901/208008256-591c3de8-6002-4c60-9c3a-542a853e4296.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>In this we are uploading the update date from csv file.<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Screenshots of DB data (basic summary/view)</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113865901/207512317-3d907ea9-bed7-41d3-ae96-e0ee94cbc0de.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Uploading the screenshot of employee and company data<br></p>
</td></tr>
</table></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 3: </em> Add Employee </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Screenshot of code for /add route of employee</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113865901/207510621-65ec0b80-9373-4384-9476-d1aad5bbff1f.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>In this code retrieve first name, last name, company id and email <br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Screenshots of website for add employee</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113865901/207513275-acc6919e-8a20-4349-aa60-2e9fc509e380.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>adding employees name and email <br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Screenshot of new employee DB record from VS Code / IDE</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113865901/207513275-acc6919e-8a20-4349-aa60-2e9fc509e380.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>In this adding the new employee database record from visual studio vode<br></p>
</td></tr>
</table></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 4: </em> List/search Employees </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Screenshots of code for /search route of employee</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113865901/207519063-9c6d9fae-cadf-46c7-85ab-4f819e144ff1.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>The code from the route of employees<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Screenshots of website for search employee</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113865901/207522441-277612b2-ed84-4b7a-a018-631bca7b5254.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Searching for the website employees<br></p>
</td></tr>
</table></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 5: </em> Edit Employee </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Screenshots of code for /edit route of employee</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113865901/207514035-78afe105-5dcf-47d7-9ecd-d08bf7c05103.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Editing the employee details like names, email and data<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Screenshots of website for edit employee</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113865901/207514386-8d2462b7-c84a-4044-a3a3-c30e99760b3e.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>The data before and after an edit<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Screenshots of DB data before and after of employee data edit from VS Code / IDE</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113865901/207521812-dce3f9ae-b451-489e-ab7a-22ced93b6ed1.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>the data should be clearly visible and should be data changed<br></p>
</td></tr>
</table></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 6: </em> Add company </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Screenshot of code for /add route of company</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113865901/207520794-1a27eecc-91cc-4ced-9545-5d376ef74aef.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>The code should retrieve form data for name, address, city, state, country, zip,<br>website<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Screenshots of website for add company</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113865901/207521530-c99f1fce-9f8f-4eda-9d77-a04bf780cc3a.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>the filled valid data prior and submission<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Screenshot of new company DB record from VS Code / IDE</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113865901/207520794-1a27eecc-91cc-4ced-9545-5d376ef74aef.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>the valid company data as been shown<br></p>
</td></tr>
</table></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 7: </em> List/Search Comapny </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Screenshots of code for /search route of company</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113865901/207516323-4527df6e-5f3d-4d98-b5e0-819a115b5459.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>In this searching of company fetch id, name, address, city, country, state, zip,<br>website, employee count for the company like name country and order <br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Screenshots of website for search company</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113865901/207516751-810240ab-ff29-46cb-b2ef-cd77185d488f.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>The search company name are filtered and result applied<br></p>
</td></tr>
</table></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 8: </em> Edit Company </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Screenshots of code for /edit route of company</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113865901/207512615-e6a6a331-a465-416e-9435-756dd368ea02.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>In this we are adding first and last name, city ,state and country<br>and except blocks <br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Screenshots of website for edit company</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113865901/207520243-530544ab-6a22-49ac-816c-e9e71ed70f27.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>This show data before and after the edit<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Screenshots of DB data before and after of company  data edit from VS Code / IDE</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113865901/207520510-bbb398e1-3fa0-4804-ac90-daa9b16c10e0.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>The data should be clearly visible<br></p>
</td></tr>
</table></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 9: </em> Delete Employee and Delete Company </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Screenshot of code for /delete route of employee</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113865901/207517130-37adc92a-2fe6-441e-a3fb-2e7dd639e413.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Deleting employee id and we can redirect employee data<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add a before and after website screenshot of deleting an employee</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113865901/207517507-7fdf0dba-2bc9-4274-8ae7-356f5f677b92.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>the before and after employee <br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Screenshot of code for /delete route of company</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113865901/207517677-7f47b048-cee5-4421-979d-8fb0afd5a55a.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>The code for delete route of company<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 4: </em> Add a before and after website screenshot of deleting a company</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113865901/207517927-a18aad6f-01c9-4f23-8662-7e618f386ac2.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Deleting the company before and after <br></p>
</td></tr>
</table></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 10: </em> Test Cases and Misc </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Screenshot Test case Results</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/113865901/207510011-8fe59490-3cae-4120-9eee-682bc5a90ba7.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Test cases are pass<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Issues / Learnings / Interesting things to note</td></tr>
<tr><td> <em>Response:</em> <p>Yes some issues are there and learning is interesting.<br></p><br></td></tr>
</table></td></tr>
<table><tr><td><em>Grading Link: </em><a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IS601-005-F22/is601-mini-project-2-business-management/grade/ms2992" target="_blank">Grading</a></td></tr></table>
