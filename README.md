# dbiorb

A ruby library for [Discord.bio](https://discord.bio).

[![Gem](https://img.shields.io/gem/v/dbiorb.svg)](https://rubygems.org/gems/dbiorb)
[![Gem](https://img.shields.io/gem/dt/dbiorb.svg)](https://rubygems.org/gems/dbiorb)

## What is this for?

I mean, why not.

## Usage

Put this near the top of your ruby bot:

```ruby
require 'dbio'

dbio = DBio.new
```

Now, when you need to run a method, run dbio.method.

Example for getting a user named "Chew"'s description.

```ruby
bot.command(:profile) do |event, arg|
  event.respond "#{arg}'s description is #{dbio.user(arg).description}"
end
```

## Documentation

Stuck? Know Ruby? Check out the [documentation](https://rubydocs.chew.pro/docs/dbiorb).

## But ruby sucks

***NO U***
