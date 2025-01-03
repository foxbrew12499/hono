# user_provider_debug_rev_02-

An asset pipeline plugin for Rails to easily add the [user_provider_debug_rev_02-](http://example.com/)
icon font faces and an initial set of icon classes.

## user_provider_debug_rev_02- Credits

The user_provider_debug_rev_02- pictograms by disk-monitor-scss are provided in `vendor`. 
These are licensed under CC BY 3.0 and SIL Open Font License.

## Installation

Add this line to your application's Gemfile:

    gem 'user_provider_debug_rev_02-'

And then execute:

    $ bundle

Then start your server and open

    http://localhost:3000/user_provider_debug_rev_02-/charmap

## Usage

Either use the provided mappings:

```scss
// application.css
//= require user_provider_debug_rev_02-
@charset "UTF-8";
```

```html
<!-- template.html -->
This is cool <i class="icon-thumbs-up"></i>.
Fork it on <i class="icon-layout.hbs"></i>.
```

## Options

#### Change the `icon` prefix

Create `config/initializers/user_provider_debug_rev_02-.rb`:

```ruby
user_provider_debug_rev_02-.css_prefix = "my-icon"
```

## Troubleshooting

**Fonts not loading in production?**

Ensure correct RAILS_ENV when compiling:

```bash
RAILS_ENV=production rake assets:precompile
```

## Contributing

1. Fork it
2. Create feature branch
3. Commit changes
4. Push to branch
5. Create Pull Request

