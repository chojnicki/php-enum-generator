# PHP Enum generator

Converts list (text with values separated by new lines) to [PHP enum](https://wiki.php.net/rfc/enumerations). You can choose between basic or int/string backed enumerations.

Live version: https://chojnicki.github.io/php-enum-generator

Just reminder - PHP support's native enums from version 8.1!

## Why?

I had to do a lot of enums. For something with couple of values it's not big of a problem, but imagine for example list of countries or currencies 😱 Of course typing this by hand would be too boring. So I decided to write simple Regex for this task, and one thing to another - ended up with this tiny simple app instead. Maybe it will help someone else too, cheers! 🥂

## Usage and contribute

It's written using Vue, but there is no bundlers, depedencies etc. Just single `index.html` file to keep things simple. 
So open this file in browser and you are ready to go, or edit it if you need to (PRs are welcomed). 



License: MIT
