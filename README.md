[![Latest Stable Version](http://poser.pugx.org/nguyenanhung/validation/v)](https://packagist.org/packages/nguyenanhung/validation) [![Total Downloads](http://poser.pugx.org/nguyenanhung/validation/downloads)](https://packagist.org/packages/nguyenanhung/validation) [![Latest Unstable Version](http://poser.pugx.org/nguyenanhung/validation/v/unstable)](https://packagist.org/packages/nguyenanhung/validation) [![License](http://poser.pugx.org/nguyenanhung/validation/license)](https://packagist.org/packages/nguyenanhung/validation) [![PHP Version Require](http://poser.pugx.org/nguyenanhung/validation/require/php)](https://packagist.org/packages/nguyenanhung/validation)

# Template start helper, library

Template for repository helper, library - Basic, Simple and Lightweight

## Use this Template

First, you can `Use this template` for new project: [Use this template](https://github.com/nguyenanhung/validation/generate)

Second, clone your project to your to path in your machine

Finally, your edit file `composer.json` in root folder of project

```json
{
    "type": "library",
    "name": "nguyenanhung/validation",
    "description": "Template for repository helper, library - Basic, Simple and Lightweight",
    "keywords": [
        "template",
        "helper",
        "library",
        "php"
    ],
    "homepage": "https://github.com/nguyenanhung/validation",
    "license": "MIT",
    "minimum-stability": "stable",
    "authors": [
        {
            "name": "Nguyen An Hung",
            "email": "dev@nguyenanhung.com",
            "homepage": "https://nguyenanhung.com",
            "role": "Developer"
        }
    ],
    "require": {
        "php": ">=5.6"
    },
    "autoload": {
        "psr-4": {
            "nguyenanhung\\Libraries\\REPLACE_FOR_YOUR\\": "src/"
        },
        "files": [
            "helpers/helpers.php"
        ]
    }
}

```

Replace name space `REPLACE_FOR_YOUR` to Library space, example: `JSON`. After change namespace, project namespace same `"nguyenanhung\\Libraries\\JSON\\": "src/"`

Finished, your can writing new awesome helper and library now time.

## Contact & Support

If any question & request, please contact following information

| Name        | Email                | Skype            | Facebook      |
|-------------|----------------------|------------------|---------------|
| Hung Nguyen | dev@nguyenanhung.com | nguyenanhung5891 | @nguyenanhung |

From Vietnam with Love <3
