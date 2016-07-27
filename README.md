# Snippets for Wp

> Libraries for WP

#### Back-end
- [active-maintenace-mode.php](https://github.com/juniorbdb/snippetsWp/blob/master/Back-end/active-maintenace-mode.php)
- [customize-login-admin.php](https://github.com/juniorbdb/snippetsWp/blob/master/Back-end/customize-login-admin.php)
- [register-sidebar.php](https://github.com/juniorbdb/snippetsWp/blob/master/Back-end/register-sidebar.php)
- [resources-editor.php](https://github.com/juniorbdb/snippetsWp/blob/master/Back-end/resources-editor.php)

#### Comments
- [insert-mytheme-comment.php](https://github.com/juniorbdb/snippetsWp/blob/master/Comments/insert-mytheme-comment.php)

#### Front-end
- [function-ajax.php](https://github.com/juniorbdb/snippetsWp/blob/master/Front-end/function-ajax.php)
- [insert-googleanalytics.php](https://github.com/juniorbdb/snippetsWp/blob/master/Front-end/insert-googleanalytics.php)
- [insert-scripts-style.php](https://github.com/juniorbdb/snippetsWp/blob/master/Front-end/insert-scripts-style.php)
- [limit-numbers-character.php](https://github.com/juniorbdb/snippetsWp/blob/master/Front-end/limit-numbers-character.php)
- [remove-junk-header.php](https://github.com/juniorbdb/snippetsWp/blob/master/Front-end/remove-junk-header.php)

#### Images
- [post-thumbnails.php](https://github.com/juniorbdb/snippetsWp/blob/master/Images/post-thumbnails.php)

#### Menu
- [get-description-menu.php](https://github.com/juniorbdb/snippetsWp/blob/master/Menu/get-description-menu.php)

Coloque esta variável na função do menu
```php
$walker = new Menu_With_Description;
```

Em seguida coloque o código abaixo no array da função wp_nav_menu
```php
'walker' => $walker
```
- [register-nav-menu.php](https://github.com/juniorbdb/snippetsWp/blob/master/Menu/register-nav-menu.php)

#### Pages
- [add-tag-pages.php](https://github.com/juniorbdb/snippetsWp/blob/master/Pages/add-tag-pages.php)
- [nav-between-pages.php](https://github.com/juniorbdb/snippetsWp/blob/master/Pages/nav-between-pages.php)

#### Posts
- [count-show-access.php](https://github.com/juniorbdb/snippetsWp/blob/master/Posts/count-show-access.php)
- [pagination.php](https://github.com/juniorbdb/snippetsWp/blob/master/Posts/pagination.php)
- [register-post-types-taxonomies.php](https://github.com/juniorbdb/snippetsWp/blob/master/Posts/register-post-types-taxonomies.php)
