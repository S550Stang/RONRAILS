# Jungle

A mini e-commerce application built with Rails 4.2 for purposes of teaching Rails by example.

## Dependencies

- Rails 4.2 [Rails Guide](http://guides.rubyonrails.org/v4.2/)
- PostgreSQL 9.x
- Stripe

## Tests
- Capybara
- RSpec

## Getting Started

1. Run `bundle install` to install dependencies
2. Create `config/database.yml` by copying `config/database.example.yml`
3. Create `config/secrets.yml` by copying `config/secrets.example.yml`
4. Run `bin/rake db:reset` to create, load and seed db
5. Create .env file based on .env.example
6. Sign up for a Stripe account
7. Put Stripe (test) keys into appropriate .env vars
8. Run `bin/rails s -b 0.0.0.0` to start the server

## Stripe Testing

Use Credit Card # 4111 1111 1111 1111 for testing success scenarios.

More information in their docs: <https://stripe.com/docs/testing#cards>

## Current Limitations/Bugs/Future Features

- TO-DO: Add validation on creation so only one sale can be active at a time.
- TO-DO: Change displayed prices when sales are active.
- TO-DO: Add rspec tests for sale creations.
- TO-DO: Validate a category has at least one product before adding to the menu.
- TO-DO: Add fake information to About Us page.
- TO-DO: Add sales to the dashboard.
- TO-DO: Order products and categories, on admin pages.
