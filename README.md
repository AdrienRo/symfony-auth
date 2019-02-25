# Symfony Authentification

## How to use ?

### Backend

#### 1. Install dependencies

First things to do is installing needed dependencies. If you start from nothing, you can initialize a new symfony project by running  ``` php composer create-project symfony/website-skeleton ```

For authentififate users, we simply need few dependecies :
  - orm
  - annotations
  - validator
  - security
  
In dev mode, also intall :
  - debug
  - maker
  - orm-fixtures


  
#### 2. Create User entity and fixture

Run ```shell php bin/console make:user``` to create a user model.
Add user fixtures
