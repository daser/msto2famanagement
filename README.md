# msto2famanagement

This project serves to expose a lot of 2FA functionlities to the User management. It is a link between the user management and the 2FABackend Microservice.

WHY: The user management would require 2FA verificaton and 2FA token generation for mobile access. During signup process on the user management microservice for mobile access, users would be enrolled into the 2FA authentication in which case a base32 key would be generated and stored against the user ID in the 2FABackend MS. This key would be used to verify sign in performed by the user subsequently.

## Requirements
* NodeJS


## Setup
It can installed into the usermanagement from npm.
The next stage would be to add TOTPMICROSERVICE to .ENV of user management or any microservice that would require 2FA. TOTPMICROSERVICE would be the url of the 2FABackend microservice and this module would expose all 2FA services to the the requiring microservice.


## Contributors
[Daser David](https://github.com/daser)



