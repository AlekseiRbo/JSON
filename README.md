# GIT Homework 1 "JSON"

4. Create an external repository named JSON.  
```   
Go to the "Repositories" tab, then ckick "New", in the "Repository name *" enter repository name and click "Create repository".   
```

5. Clone JSON repository to local machine.  
`git clone git@github.com:AlekseiRbo/JSON.git` 

6. Inside the local JSON create a “new.json” file.  
`touch new.json`

7. Add file under git.  
`git add .`

8. Commit file.  
`git commit -m "Add new.json"`

9. Push file to external GitHub repository.  
`git push`  

10. Edit the content of the “new.json” file - write information about yourself (full name, age, number of pets, future desired salary). Write everything in JSON format.  
`vim json`  
```
{
	"user_name": "Riaboshapko Aleksei",
	"user_age": 28,
	"user_animal": 0,
	"user_salary": 1000
} 
```
11. Push changes to an external repository.  
`git commit -am "Add diff new.json`  
`git push`  

12. Create preferences.json file  
`touch preferences.json`  

13. In the preferences.json file, add information about your preferences (Favorite movie, favorite series, favorite food, favorite season, side you would like to visit) in JSON format.  
`vim preferences.json`  
```
{
	"user_favorite_movie": "John Wick",
	"user_favorite_soap_opera": "The Walking Dead",
	"user_favorite_food": "French_meat", "Pork_skewers0",
	"user_favorite_season": "I like all seasons",
	"user_country_to_travel": "Germany"
}
```  

14. Create a sklls.json file to add information about the skills that will be studied in the course in JSON format.  
`vim sklls.json`  
```
{
	"user_soft_skills": [
		"attentiveness", 
		"multitasking", 
		"perseverance", 
		"skill to work in team",
		"and etc"
		]
	"user_hard_skills": [
		"Git", 
		"GitHub", 
		"Postman_API", 
		"SQL", 
		"SOAP_API", 
		"and etc"
		]
}
```  

15.  Send 2 files at once to an external repository.  
`git commit -am "Add diff 'preferences.json' and 'sklls.json'"`  
`git push`  

16. On the web interface, create a bug_report.json file.  
Click in the repository `Add file` then `Create new file` in field "Name your file..." enter "bug_report.json"  

17. Make Commit changes (save) changes on the web interface.  
In field "Update README.md" enter ***changes*** then click `Commit changes`  

18. On the web interface, modify the bug_report.json file, add a bug report in JSON format.  
Go to file "bug_report.json" click `Edit this file`, insert json file:  
```
{
  "ID": "001",
  "Severity": "Medium",
  "Environment": "Devices",
  "Title": "What?Where?When?",
  "Steps": "Steps to reproduce",
  "ER": "Expected Result",
  "AR": "Actual Result",
  "Link": "link",
  "License": "license",
  "Role": "Unregistered, Unauthorized, Authorized, All",
  "Telegram @nick. Bug started": "@_",
  "Telegram @nick. Bug reproduced": "@_",
  "Telegram @nick. Bug didn't reproduce": "@_",
  "Bug didn't reproduce (environment)": "Devices"
}
```

19. Make Commit changes (save) changes on the web interface.  
In field "Update README.md" enter ***changes*** then click `Commit changes`  

20. Synchronize external and local JSON repository.  
`git pull`  
