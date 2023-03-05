# ImeiService
Developed IMEI control system.

#### There are three users in the ImeiService system. AppUser user can register IMEI number in the system and view these numbers.
#### At the same time, with the "Forgot Password" option, the password reset token information automatically created in the database is sent to the e-mail of the data user, enabling the user to reset their password.
#### Admin user can view all registered IMEI numbers and block IMEI number.
#### The Hibernate Validator library was used to show that the values met certain constraints.
#### With the Spring Security integration, the user information logged in was checked and a role was assigned to the user.
