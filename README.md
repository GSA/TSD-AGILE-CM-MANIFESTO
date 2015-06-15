# TSD Agile CM Manifesto
Before the Technology Solution Division, inside of GSA IT, develops formal policy and guidance for Configuration Managenet of agile projects, we will first document our core principles of configuration management. These principles serve as a high level list of do's and do not's for configuration management. These are the established principles where all teams stand equal in supporting and upholding said principles.

### Principle 1: Share First (Public Vs GSA Vs Private)
> All developers have an obligation to consider how code can be shared or otherwise leveraged by external enteties (Either Agency-wide or Government-wide).

### Principle 2: Decentralizatin of Repositories (Forking)
> All developers shall first "Fork" a central repository to their personal Github account. All commits during the process of development should be made to the "Fork". Only once code has met Acceptance Criteria can it be pulled to central repository.

### Principle 3: No Passwords in Code Repositories (Separate Config Repositories)
> All developers shall to the extent possible, develop code in a manner such that passwords or other sensitive information (IP Addresses, Server Names) is not stored in the same central repository as the code that requires said information. It is however acceptible to store sensitive information (not paswords) in a separate, private, repoository that has more stringent security controls applied to it.

### Principle 4: Ignore configuration files (.gitignore)
> All developers shall ignore configuration files from their code repositories by leveraging the [GitIgnore](http://git-scm.com/docs/gitignore) capability. See Principle 3 for more information.

### Principle 5: Commit Messages (Always)
> All developers shall input commit messages on all commits. Additionally, commit messages shall relate to the requirement/defect/issue that was being addressed.

### Principle 6: Code Documentation (Github Pages)
> All developers shall use a consistant, accessible, mechanism for writing and revisioning documention on code. The use of [Github Pages](https://pages.github.com/) shall be said standard mechanism.
