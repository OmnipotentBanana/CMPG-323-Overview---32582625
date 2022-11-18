## CMPG 323 Projects

- In the ReadME.md, address which 
repositories will be created and used 
for each project


## Branches that will be used for this project
- main
- dev

Working alone with these branches will allow for fluid and safe commits.

- In the ReadME.md, explain the 
branching strategy to be used within 
each project

> A user would commit to branch "dev". This will allow someone to make a pull request to check whether the code in the dev branch is up to standard. If it is, it is then integrated with the main branch where most of the functional code lies. 

- In the ReadME.md, explain the use 
of a .gitignore file within each project

> .gitignore allows for file exclusions when pushing to a branch. This will leave files out of commits which allows a developer to have full control of pushes. When working on certain files, a dev does not want to push some other files which are out of scope.


- In the ReadME.md, provide a 
diagram explaining project and 
repository context and how they are 
integrated

![alttext](https://github.com/OmnipotentBanana/CMPG-323-Overview---32582625/blob/main/Project%201%20Diagram.jpg)

1. git init
> Allows for a user to initiate a clean repository. In this case, I created a repository in GitHub and just cloned the repo.
2. git add <files>
> A user adds files to be committed to the local repository with git.
3. git commit
> A user then commits these changes to the local repository and the changes are made to ONLY the local repository.
4. git push
> A user then pushes the changes to the cloud repository hosted wherever.

> Different things could be used in different workflows. It just depends on the methodology used.

- In the ReadME.md, explain the 
storage of credentials and sensitive 
information

> When data breaches occur on massive companies and passwords are stored in plain text, this will allow any malicious party to do credential stuffing on any other website that the users of the breached company use. Many people don't use different passwords for different websites. This is why companies should encrypt passwords to make it harder for malicious parties to decrypt the passwords of the users. SHA-2 is a common encryption method used for passwords in databases, seen in past breaches.



## Project 2:

> This project handled output of IOT devices through a web interface. These devices can then be listed and tracked to see their status and locations. The device specifications are stored in an Azure database in the cloud, allowing for safe storage and accessibility.

## Project 3: 

> This project allows for the insertion, editing and deletion of IOT devices. The UI allows for easy manipulation of the data in the database and makes it easier for the stakeholder to have control of the data.

## Project 4:

> The IOT API has been automated. This allows for testing of data and see if all devices are correctly entered into the database. This removes the need for humans to test any sort of device entry.

## Project 5:

> This project handled the high-level reporting of data regarding the IOT devices. Graphs and charts are used to show stakeholders the most important data regarding the IOT devices and makes it much easier to read the data.