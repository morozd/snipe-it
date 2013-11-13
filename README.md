## Snipe-IT - Asset Management For the Rest of Us

This is a FOSS project for asset management in IT Operations. Knowing who has which laptop, when it was purchased in order to depreciate it correctly, etc.

It is built on [Laravel 4](http://laravel.com) and uses the [Sentry 2](https://github.com/cartalyst/sentry) package. I chose Laravel because it's no better or worse than any other PHP framework out there, and not really for any other reason.

Many thanks to the [Laravel 4 starter site](https://github.com/brunogaspar/laravel4-starter-kit) for a quick start. 

This isn't actually ready for anyone to use yet, as I'm still working out some of the basic functionality in the develop branch. You're welcome to fork it and submit pull requests if there;s something you'd like to see there. 

### Features Currently in Development
- asset models (example: Macbook Pro 13-inch, late 2013)
- assets belonging to asset models (example: Serial # 1234567890)
- categories (example: laptops, desktops, monitors, etc)
- basic depreciation reports (add purchase date, cost and invoice number to pull quick year-end reports on straight-line depreciation)
- multiple location support (if a laptop started in NY and ended up in the SF office, you can see the progressoon and depreciate from there)
- lookup by asset or by person (if you want to know who has a laptop with a specific serial, you can do that - or if you want to look up all assets belonging to one person, you can do that too)