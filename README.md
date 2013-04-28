# Chef Testing

## Setup
* vagrant destroy && vagrant up && vagrant ssh
* sudo su
* gem install chef
* mkdir /etc/chef
* cat > /etc/chef/solo.rb
```ruby
cookbook_path "/cookbooks"
```
* cd /cookbooks
* chef-solo -j node.json
