# Week 3 — Decentralized Authentication

## Setup Cognito User Pool
I was able to set up a user pool named crudder-user-pool by following the video.  Here is the snapshot of the created user pool.  
![cognito-user-pool](assets/Docker_update_Cognito.png)
![cognito-user-pool](assets/Cognito_user_pool_creation.png)

## Implement Custom Signin Page
Custom signin pages were added and tested to ensure accuracy.
![cognito-user-pool](assets/console_sign_in_update.png)
![cognito-user-pool](assets/successful_sign_in.png)

## Implement Custom Signup Page

## Implement Custom Confirmation Page
After successfully verifying our user we also showed up in AWS as verified.
![cognito-user-pool](assets/verified_in_cognito.png)
![cognito-user-pool](assets/verification_code.png)
![cognito-user-pool](assets/verification_code_screen.png)

After successfully performing sign up verification we were able to sign in and show our preferred user name
![cognito-user-pool](assets/successful_sign_in.png)
![cognito-user-pool](assets/user_preferred_update.png)
## Implement Custom Recovery Page
We also tested the portion of the site required if someone needed to recover/update their password due to forgetting it.  Here are the screenshots associated with that.
![cognito-user-pool](assets/recovery_code_email.png)
![cognito-user-pool](assets/recovery_code.png)

## Verify JWT Token Server Side
The last step was to implement JWT tokens and implement debugging pieces that allowed us to validate.  We also implemented secret crud that if we were authenticated correctly would show.  Issues were seen when logging out as the secret crud stayed.  We resolved that by implmenting a clear statment.

![jwt-user](assets/requirements_awscognito_update.png)
![jwt-user](assets/jwt_token_output.png)
![jwt-user](assets/jwt_docker_backend_error.png)
![jwt-user](assets/secret_crud.png)
![jwt-user](assets/remove_token_added.png)
![jwt-user](assets/crud_removed.png)

