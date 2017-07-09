# enpsnippets README

VScode twig snippets extention.

## Features

Add some generic twig language snippets and some extra piece of code.

**Basic twig snippets:**

* dump - `{{dump(var)}}`
* set - `{% set var %}{% endset %}`
* set inline - `{% set var = value %}`
* block - `{% block name %}...{% endblock %}`
* extends - `{% extends 'template' %}`
* for - `{% for item in data %} ... {% endfor %}`
* if - `{% if condition %} ... {% endif %}`
* ife - `{% if condition %} ... {% else %} ... {% endif %}`
* else - `{% else %}`
* endif - `{% endif %}`
* endblock - `{% endblock %}`
* endfor - `{% endfor %}`
* endset - `{% endset %}`
* macro - `{% macro name(params) %} ... {% endmacro %}`
* verbatim - `{% verbatim %} ... {% endverbatim %}`
* spaceless - `{% spaceless %} ... {% endspaceless %}`
* include - `{% include 'template' %}`
* include with - `{% include 'template' with {params} %}`

**Custom twig/html snippets:**

* trans - `{{ 'name'|trans }}`
* icon - `<i class='icon-name'></i>`
* imageMacro - import image macro
* image - usage example with filter, path and sizes
* pageZone
* adZone
* postscript
* emblem
* productDescribe
* newsletter twig extension
* opinions twig extension
* javascripts - example with block and assets
* magnific macro
* adBlock
* controlPanelValue
* flashMessage
* contentLandingpages
* connectedPages
* systemAttributeValues
* offerLink


## Install

Manual install

* Download file enptwigsnippets-0.1.0.vsix
* Open VSCode extenstions
* Click Install from VSIX...

![Install from VSIX](https://github.com/enetproduction/vscode-extensions/blob/master/enpTwigSnippets/vsix.png)

## Using

Just start typing include... to insert include code.


## Release Notes

### 1.0.0

Initial release

