New Module
___

Whenever a new module is created, it must first be "standardized" before it is "customized" for the site. Use boostrap as a styling guide. Greys, and neutrals. If you have questions or need quidence see Joey. These default files should be complete, so that if used on a new site it will make sense and work.


* Modules and files now follow a BEM naming structure
* All should include a README.md describing functionality and changelog.
* All functionality must be included README.me
* All dependencies must be documented in the README.md
* All new functionality must be added as options on the controller file.
* All ACF fields must follow a BEM naimg structure.
* All files must contain clear comments that are easy to follow


Folder structure:
___


modules/<br/>
&nbsp;&nbsp;newModule/<br/>
&nbsp;&nbsp;css/<br/>
&nbsp;&nbsp;&nbsp;&nbsp;newModule--custom.scss<br/>
&nbsp;&nbsp;&nbsp;&nbsp;newModule--default.scss<br/>
&nbsp;&nbsp;js/<br/>
&nbsp;&nbsp;&nbsp;&nbsp;newModule--custom.js<br/>
&nbsp;&nbsp;&nbsp;&nbsp;newModule--default.js<br/>
&nbsp;&nbsp;tpl<br/>
&nbsp;&nbsp;&nbsp;&nbsp;newModule--default.tpl.php<br/>
&nbsp;&nbsp;&nbsp;&nbsp;newModule--custom.tpl.php<br/>
&nbsp;&nbsp;newModule.php<br/>
&nbsp;&nbsp;README.md<br/>






README.md SAMPLE Table of Contents
___

1. Breif Description
2. Dependencies
3. Change Log ( See Example below )



Chaneglog
___

* YYYY-MM-DD Sample Customized Feature A for siteName.org -- yourName
* 2015-12-04 Initialized -- Joey

