# TSD Agile CM Manifesto
Before the Technology Solution Division, inside of GSA IT, develops formal policy and guidance for Configuration Managenet of agile projects, we will first document our core principles of configuration management. These principles serve as a high level list of do's and do not's for configuration management. These are untailorable principles where all teams stand equal in supportig and upholding said principles.

### Principle 1: Share First (Public Vs GSA Vs Private)
> It is a developers obligation to consider how code can be shared or otherwise leveraged by external enteties (Either Agency-wide or Government-wide).


### Principle 2: Decentralizatin of Repositories (Forking)
> All developers should first "Fork" a central repository to their personal Github account. All commits during the process of development should be made to the "Fork". Only once code has met Acceptance Criteria can it be pulled to central repository.

### Principle 3: No Passwords in Code Repositories (Separate Config Repositories)
> All developers shall to the extent possible, develop code in a manner such that passwords or other sensitive information (IP Addresses, Server Names) is not stored in the same central repository as the code that requires said information. It is however acceptible to store sensitive information (not paswords) in a separate, private, repoository that has more stringent security controls applied to it.

