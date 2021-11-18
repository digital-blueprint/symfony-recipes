DBP Symfony Recipes
===================

This is the [Symfony Flex](https://symfony.com/doc/current/quick_tour/flex_recipes.html)
Repository of the Digital Blueprint.

It will be used by the [Relay Server Template](https://gitlab.tugraz.at/dbp/relay/dbp-relay-server-template)
as additional Symfony Flex Repository.

The original Symfony Flex Repository of Symfony is located here:
https://github.com/symfony/recipes/

To use these recipes add the following snipped into the composer.json of your Symfony app:

```json
{
    "extra": {
        "symfony": {
            "endpoint": [
                "flex://defaults",
                "https://api.github.com/repos/digital-blueprint/symfony-recipes/contents/index.json?ref=flex/main"
            ]
        }
    }
}
```