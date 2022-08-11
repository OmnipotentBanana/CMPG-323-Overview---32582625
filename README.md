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