# Rails Starter Template

**Note:** Requires Rails 5.2

## Getting Started

Starter template to get you going quick

#### Requirements

You'll need the following installed to run the template successfully:

* Ruby 2.5+
* bundler - `gem install bundler`
* rails - `gem install rails`
* Yarn - `brew install yarn` or [Install Yarn](https://yarnpkg.com/en/docs/install)

#### Creating a new app

```bash
rails new <app name> -d postgresql -m https://raw.githubusercontent.com/josephhyatt/rails-template/master/template.rb
```

Or if you have downloaded this repo, you can reference template.rb locally:

```bash
rails new <app name> -d postgresql -m template.rb
```

#### Cleaning up

```bash
rails db:drop
spring stop
cd ..
rm -rf myapp
```

