## Immaculate: Free Portfolio Website Template

Immaculate is a **modern,** **beautiful** and **Clean One Page
Portfolio Website Template** with a refreshing layout. It is also **fast
loading**, **cross browser compatible** and is built to suit all kinds
of businesses as well as personal needs. The template is made using
**HTML5**, **CSS3** and **jQuery** and has **web fonts**,
**shortcodes**, **Flickr Image Slider** along with **working Ajax
contact form** and a lot more. You are free to use it for your personal
as well as commercial projects. It is released under **New BSD
License**, read more about it at http://www.opensource.org/licenses/bsd-license.php.

**Release Page
at http://priteshgupta.com/templates/immaculate/.**

### Using Slider

Zurb’s Orbit slider is being used for the image slider, the images are fetched from a flickr username. To change the flickr id, open  `functions.php` and replace 33871992@NO7 with your desired username . You can do a lot more with the flickr plugin, read
about it here: http://www.gethifi.com/blog/a-iguery-flickr-feed-plugin.

### Using Shortcodes

#### Boxes

Using a shortcode is really easy, just use the HTML code where ever you want to use them, customize it, and it's done.

The HTML shortcode for a normal box is 

```
<div class="box normal rounded full">
```

You can remove the `rounded` if you prefer square boxes. Similarly, you can remove the `full` if you don't want full border. 

For different box types, replace `normal` with your desired type, possible choices are `normal`, `info`, `tick`,
`note`, `download`, `alert`.

#### Colored Buttons

For using buttons, use the HTML syntax 

```
<a href="#" class="-button red"><span class="-">Button<span><a>
```

Where "Button" is the button text which you will like to display, and replace `red` with your desired button color type, possible options are `silver`, `red`, `orange`, `green`, `aqua`, `teal`, `purple`, `pink`. If you don't specify any color, then default blue button will be displayed.

#### Icons Buttons

Using Icons Buttons is very much same as using colored buttons, use the HTML syntax 

```
<a href="#" class="-button silver" ><span class="-
search">Button</span></a>
```

and specify the button color like above, and change the `search` with desired button icon, possible choices are `search`,
`stats`, `alert`, `tick`, `info`, `note`, `author`, `mail`, `notice`, `paper`, `people`, `download`.

#### Customizing Gallery

Fancybox has been used for galleries, for help with it, head over to http://fancybox.net/howto.

#### Customizing Contact

A working PHP Ajax Contact Form is already in place, just replace your email id with `you@email.com` and `Your Name` with your name in process.php.

#### Typography

The template uses the font ”Open Sans” by Steve Matteson and ”Bebas Neue” by Dharma Type.