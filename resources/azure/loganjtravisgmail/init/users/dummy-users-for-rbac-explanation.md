# Dummy Users for Role-Based Access Test

2020-03-27
loganjtravis@gmail.com (Logan J Travis)

### Purpose

To create intial Azure Active Directory usres for role-based access testing. Mimics ideal organization.

### Users

* Name: Solutions Architect
    * Username, etc. (imported): *[See .\dummy-users-for-rbac-import.csv](.\dummy-users-for-rbac-import.csv)*
    * Azure AD Roles (manual):
        * TODO
    * Asure AD Groups (manual):
        * dept-it
    * Subscription Roles (manul):
        * Pay-As-You-Go (default Subscription):
            * Co-Administrator
            * Owner
            * Reader (via dept-it)
* Name: Billing Administrator
    * Username, etc. (imported): *[See .\dummy-users-for-rbac-import.csv](.\dummy-users-for-rbac-import.csv)*
    * Azure AD Roles (manual):
        * TODO
    * Azure AD Groups (manual):
        * dept-it
    * Subscription Roles (manual):
        * Pay-As-You-Go (default subscription):
            * Reader (via dept-it)
* Name: Support Specialist
    * Username, etc. (imported): *[See .\dummy-users-for-rbac-import.csv](.\dummy-users-for-rbac-import.csv)*
    * Azure AD Roles (manual):
        * TODO
    * Azure AD Groups (manual):
        * dept-it
    * Subscription Roles (manual):
        * Pay-As-You-Go (default subscription):
            * Reader (via dept-it)