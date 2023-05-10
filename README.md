# RubyOnRails

# Install Ruby 
sudo gem install rails

# Create New App
sudo rails new app

# Generate a route 
sudo rails generate controller Examples index

# Generate a Crud route with database 
sudo rails g scaffold friends name:string email:string 

sudo rails db:migrate