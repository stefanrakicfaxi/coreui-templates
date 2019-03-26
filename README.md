# coreui-templates
Core UI templates for InfyOm Laravel Generator

To use coreui templates, add following to your composer.json if you haven't.

```
"require": {
    "infyomlabs/coreui-templates": "dev-master"
}
```

##### Run Composer update
Run `composer update` command.

##### Add Service Provider
Update `config/infyom/laravel_generator.php` to use Coreui templates.

Update `templates => 'coreui-templates'`

##### Publish Layout
`php artisan infyom.publish:layout`

##

Infyom laravel Generator Installation steps are located [here](http://labs.infyom.com/laravelgenerator/docs/master/installation)
More about CoreUi [here](https://coreui.io/docs/getting-started/introduction)