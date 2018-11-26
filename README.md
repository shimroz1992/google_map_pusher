Build a realtime location sharing app with Ruby on Rails and Pusher Channels

Getting Started
------

#### Clone The Repository
`$ git clone https://github.com/shimroz1992/google_map_pusher.git`


#### Change directory
`$ cd google_map_pusher`

#### Install dependencies
`$ bundle install`

#### Setup up database
`$ rails db:setup`
`$ rails db:migrate`

#### Setup up Figaro and Env variables
- Run `$ figaro install` to automatically generate `application.yml` file.
- Open `config/application.yml` and replace the content (if any) with the following:
```
PUSHER_APP_ID: 'your Pusher app ID'
PUSHER_KEY: 'your pusher kep'
PUSHER_SECRET: 'your pusher secret'
PUSHER_CLUSTER: 'your pusher cluster'
```


Prerequisites
------
A basic knowledge of Ruby and CoffeeScript


Built With
------
- [Pusher](https://pusher.com) - A Ruby gem to interact with the Pusher REST API
