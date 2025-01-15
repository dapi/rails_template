# My lovely Rails templates ;)

# Usage

```bash
rails new  --database=postgresql
./bin/rails app:template \
  LOCATION=https://raw.githubusercontent.com/dapi/rails_templates/main/default.rb
```

Local run:

```bash
APP=vilna; rm -fr ${APP}; rails new ${APP} --database=postgresql; cd ${APP}; ./bin/rails app:template LOCATION=~/code/rails_templates/default.rb
```

## Add dockerization from Evil Martians

Source: https://evilmartians.com/chronicles/ruby-on-whales-docker-for-ruby-rails-development

```ruby
rails app:template LOCATION='https://railsbytes.com/script/z5OsoB'
```
