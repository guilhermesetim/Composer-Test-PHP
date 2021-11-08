## Acrescentar no arquivo composer.json

```
"scripts": {
    "test_unit": "phpunit test[Arquivo que ocorrerá o teste].php",
    "cs": "phpcs --standard=PS12 src/",
    "phan": "phan --allow-polyfill-parser",

    "check": [
        "@phan",
        "@cs",
        "@test_unit"
    ]
}

```