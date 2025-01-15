# My lovely Rails templates ;)


## Usage

```
rails new  --database=postgresql
./bin/rails app:template \
  LOCATION=https://raw.githubusercontent.com/dapi/rails_templates/main/default.rb
```

Local run:

```
APP=vilna; rm -fr ${APP}; rails new ${APP} --database=postgresql; cd ${APP}; ./bin/rails app:template LOCATION=~/code/rails_templates/default.rb
```
