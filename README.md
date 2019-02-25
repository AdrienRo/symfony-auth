# Symfony Authentification

## How to use ?

### Backend

#### 1. Install dependencies

First things to do is installing needed dependencies. If you start from nothing, you can initialize a new symfony project by running  ``` composer create-project symfony/website-skeleton ```

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

Create a new User model is very simple. Just run command ``` php bin/console make:user ```. Then, add ** uid ** property to your new entity, manualy or using the ``` php bin/console make:entity ``` command. Uid property allows us to retreive user by an other way to the common email/password.

To set uid, i create a doctrine event subscriber.
