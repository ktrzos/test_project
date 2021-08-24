This repository was created as an example of an error mentioned in here:<br>
https://github.com/symplify/symplify/issues/3502

Instructions:

- `composer install`
- `vendor/bin/config-transformer switch-format -s 5.3 config/x`

Result:

> In XmlFileLoader.php line 624:

> There is no extension able to load the configuration for "doctrine:config" (in "/.../test_project/config/x2/doctrine.xml").
> Looked for namespace "http://symfony.com/schema/dic/doctrine", found "none".                                                                                                                                                
                                       