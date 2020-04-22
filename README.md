# b - sessions

'b - sessions' is a mock-up session management platform.
Simple CRUD app built by @ruivitorbaltazar with:

* Ruby 2.6.5

* Ruby on Rails 5.2.4.2

* PostgreSQL 12.2


## Features

It allows for:

* Sign up/Log in/Log out as User
![Landing](../app/assets/images/landing.png?raw=true)

* Create/Edit/Delete Sessions
![New Session](../app/assets/images/new_session.png?raw=true)

* See list of Sessions you are hosting or just attending
![Sessions](../app/assets/images/sessions.png?raw=true)

* Check individual Session
![Show Session](../app/assets/images/show_session.png?raw=true)

* Add/Remove Trainees to Sessions
![Edit Session](../app/assets/images/edit_session.png?raw=true)


## Local Setup

You can clone this app to your machine to test it locally.
Just follow these steps, using the command line:

1. Make sure Ruby is installed on your system:
```ruby -v```
*If you don't see version of Ruby, check [how to install Ruby](https://guides.rubyonrails.org/v5.0/getting_started.html)*

2. Make sure Rails is also installed:
```rails -v```
*If you don't see version of Rails, check [how to install Rails](https://www.ruby-lang.org/en/documentation/installation/)*

3. Clone this repository into a folder of your choosing:
```git clone git@github.com:ruivitorbaltazar/b-sessions.git```

4. Install all dependencies:
```bundle install```

5. Create database:
```rails db:create```

6. Do all necessary database migrations:
```rails db:migrate```

7. Populate database:
```rails db:seed```

8. Run the application:
```rails s```

