# Flickerd ZenPhoto Theme 
####*(2016 Fork for Zenphoto version 1.4.11)*

**Note:** This is a Fork from [Amereservant git-repo](http://github.com/amereservant/FlickerdTheme) changing some piece of the code of the Flickered Theme to work with the new version of ZenPhoto version 1.4.11.

Flickerd is a [ZenPhoto](http://www.zenphoto.org) theme that is based off of the [Flickrish Theme](http://code.google.com/p/flickrish/) hosted on Google Code. It integrates a photo stream similar to Flickr.com and implements a similar design as well. It is still being developed and I hope to be able to add new features soon.

The *Flickerd Theme* is licensed under the [MIT License](http://opensource.org/licenses/mit-license.php).

# Usage

**PHP 5 Required!**

Refer to ZenPhoto's documentation on how to add and use themes. It works just like a normal theme does.

# Feedback

**Report An Issue/Bug/Suggestion** <br>
Please report issues on the project's "GitHub Issues" page of this Fork.

**Comments/Feedback** <br>
Not available for now on the [ZenPhoto's Forums](http://www.zenphoto.org/support/).

# Changelog

### Current Issues

- [Issue 1](https://github.com/Kant1-0/FlickerdTheme/issues/1): Warning: array_slice() expects parameter 1 to be array, null given in flickerd.class.php (line 193)
- [Issue 2](https://github.com/Kant1-0/FlickerdTheme/issues/2) *(Solved but still Open)*: Warning: printAdminToolbox (called from header.php line 43) is deprecated

#### Version 1.1 (currently in work in this fork)

- **Functions setThemeOption()** has been replaced by **setOptionDefault()**. The theme can now be activate in ZenPhoto without warning messages.
- **Function printAdminToolbox()** has been replaced by **zp_apply_filter('theme_body_close')**. The admin tool seems to work now. Better checking needed.

#### Version 1.0.2 (from [Amereservant git-repo](http://github.com/amereservant/FlickerdTheme))

- **GoogleMap Plugin Support** - Added support for the GoogleMap plugin as per request in [Issue 11](https://github.com/amereservant/FlickerdTheme/issues/11) and added the option *GoogleMap Width* to the *Theme Options* page.
- **Back-link Added to Sizes View** - As per request in [Issue 9](https://github.com/amereservant/FlickerdTheme/issues/9), a backlink has been added to the image *Sizes* page.
- **Password Page Design** - As mentioned in [Issue 4](https://github.com/amereservant/FlickerdTheme/issues/4), the page login form didn't have any formatting so it was formatted to match the ZenPhoto login page.
- **Larger Image Preview** - In [Issue 6](https://github.com/amereservant/FlickerdTheme/issues/6), a request for a large image layout was made. The way this was implemented was by adding a *hover* effect so when the mouse hovers over the thumbnail for at least the *Preview Image Delay* length, a larger image (size determined by the *options > theme > Standard options > Image size* value) is displayed.
- **CSS Modified** - The width of the content area in the theme was changed for better viewing.
- **Added better Page Titles** - In the head tags, better <title></title> values were added for better search engine ranking.
