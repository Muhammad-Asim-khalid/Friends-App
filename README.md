# Friends App

This project is used to make list of your Friends.

##### Prerequisites

The setups steps expect following tools installed on the system.

- Github
- Ruby [2.4.0](https://github.com/organization/project-name/blob/master/.ruby-version#L1)
- Rails [5.0.2](https://github.com/organization/project-name/blob/master/Gemfile#L12)
- Add environment_variables.yml file in config directory:

     development:
      GMAIL_USERNAME: your_username
      GMAIL_PASSWORD: your_password
      
##### To run this project

- Run bundle install 
- Run rails g devise:install
- Run rails db:migrate
- Run rails server