# Flat Admin for SilverStripe
####Custom CSS for the SilverStripe CMS Admin Interface.

This module basic overrides some basic CSS that is found in the SilverStripe framework.

###Installation:
####Composer:
```json
require: "mediabeast/flat-admin": "3.2"
```
####Download:
Clone or download this repo, copy it into your website folder, rename the folder to `flat-admin` and then run `dev/build`.

### Configuration
If you have ModelAdmins with no icons then you'll want to replace the black SilverStripe icon as it's very hard to see with this theme installed. For a quick alternative use one of the icons located in the flat admin theme e.g.
```php
private static $menu_icon = 'flat-admin/images/db.png';
```

### Contribution
I'm a developer so I'd be keen for an actual designer to suggest some changes. I only want to change CSS and not the structure of the HTML as I think that will cause issues if SilverStripe update a template at their end and someone has this module installed. So I anyone has any suggestions on colors etc feel free to let me know of do a pull request.

###Screenshots:
![Flat Theme](http://i.imgur.com/QnN3wPz.png "Flat Theme")

![Flat Theme](http://i.imgur.com/anH4Uv6.png "Flat Theme")

###TODO:
- In Progress: customise GridField to suit the new colors .e.g. remove texture
- ~~change icons in menu to be white~~
- In Progress: change icons used in buttons, something a bit more moder and no drop shadow will be nice.
- In Progress: remove any textures and dropwshadows in other parts of the interface.
- Responsiveness? Could add some simple media queries to make it usable on modiles/tablets.
