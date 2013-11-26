AngularJS_Schema
================

AngularJS Schema files of Microsoft IDEs (enable the intellisense feature for AngularJS)

# Install and how to use
  + WebMatrix 3
    1. Copy AngularJS.xsd, angularjs.png, SchemaCatalog.xml(overwrite) in {WebMatrix Install Dir}\Schemas\1033\Html)
       Most of time the path should be "C:\Program Files (x86)\Microsoft WebMatrix\Schemas\1033\Html"
    2. Start WebMatrix, create a html5 file. 
    3. In the code view use the right mouse click to popup the context menu. Check "IntelliSense" -> "AngularJS".
    4. In the code view type something to create a dom node and add some attributes.
       When you trigger the IntelliSense dropdown, Select "data-..." and click the [Tab] key, the AngularJS attributes will be shown. Enjoy it.

  - Visual Studio 2013
    working on it...

# Known issure
  - in Web Matrix 3, the AngularJS attributes list can not be triggered by just typing "ng-" attribute perfix. (even changed both vs:customattrprefix in html_5.xsd and AngularJS.xsd)
  - in Web Matrix 3, the AngularJS attributes are still "Unknow attribute", and be listed in "Error List" view.

