**Project #6(A-O): Implementing Service Accounts**

- This project involved setting up a Service Account (i.e., a workstation dedicated to running a single application or program) that perpetually displays the Cybersecurity and Infrastructure Security Agency's (CISA) Cybersecurity Awareness page as part of a security awareness campaign conducted within the organization.
- A Service Account Organizational Unit and Service Account User was created within Active Directory, and then Sysinternals Suite was installed on a client virtual (VM) machine in order to configure the client VM to automatically log into the Service Account upon startup. 
- Additionally, Google Chrome was configured to automatically launch upon startup and to display the CISA's Cybersecurity Awareness page in full screen.
- The client VM was configured to never enter sleep mode, so as to perpetually display the CISA's Cybersecurity Awareness page.
- A Group Policy Object (GPO) was created which restricts regular enterprise network users from logging in to the Service Account workstation.
- Lastly, the new GPO was applied to the Service Account.
