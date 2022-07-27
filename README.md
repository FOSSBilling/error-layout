# error-layout
The source files for FOSSBilling's error page.
![Preview screenshot](https://user-images.githubusercontent.com/35808275/181360799-6bcfe059-9742-45d1-9061-eeeac7044e43.png)

# How to implement it to FOSSBilling
Currently, the part that handles the error and renders the error page is a little messy.
1. Build the stylesheets: `npx tailwindcss -i ./assets/css/src/style.css -o ./assets/css/dist/style.css --watch`
2. Place the assets accordingly into `/bb-library/Error/assets/`
3. Edit `/bb-load.php` accordingly. This is the messy part.

In the future, we should implement some kind of template system instead.
