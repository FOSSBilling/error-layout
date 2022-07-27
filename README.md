# [WIP] error-layout
The source files for FOSSBilling's error page. Not implemented to the core software yet.
![Preview screenshot](https://user-images.githubusercontent.com/35808275/181360799-6bcfe059-9742-45d1-9061-eeeac7044e43.png)

# How to implement it to FOSSBilling
Currently, the part that handles the error and renders the error page is a little messy.
1. Build the stylesheets: `npx tailwindcss -i ./assets/css/src/style.css -o ./assets/css/dist/style.css --watch --minify`
2. Place the assets accordingly into `/bb-library/Error/assets/`
3. Edit `/bb-load.php` accordingly. This is the messy part.

In the future, we should implement some kind of template system instead.

# Acknowledgements
* Heavily inspired by https://bunny.net/blog/building-better-error-pages/.

## Licensing
This extension is released under the Apache v2.0 license. See [LICENSE](https://github.com/FOSSBilling/error-layout/blob/master/LICENSE) for the full license terms.
