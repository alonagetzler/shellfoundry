=======
History
=======

1.0.4 (2017-08-28)
------------------

* Fixed some inconsistencies between update and add shell specifically around the shell name

1.0.3 (2017-06-28)
------------------

* list command aborts if there is a new major version on pypi
* old shellfoundry versions are NOT supported anymore.
  Please use `pip install shellfoundry -U` in order to upgrade to the newest version

1.0.2 (2017-06-27)
------------------

* new command aborts if there is a new major version on pypi

1.0.1 (2017-06-26)
------------------

* new command now conforms to CloudShell naming rules

1.0.0 (2017-06-19)
------------------

* Please upgrade to this version as from now on, older versions will be obsolete
* list command will now show templates that are installable on your cloudshell
* new command will now create the latest version of the template that match the standards installed on your cloudshell
* When invoking new or list commands, there will be a notification in the case of a new shellfoundry version

0.2.7 (2017-05-16)
------------------

* Shellfoundry will now pack categories.xml if exists

0.2.6 (2017-03-14)
------------------

* Fixed some minor bugs

0.2.2 (2017-01-22)
------------------

* gen2/resource is the now the default template for new command instead of gen1/resource

0.2.0 (2017-01-17)
------------------

* List command filtering parameters have changed (legacy => gen1, tosca => gen2)
* Added another filtering parameter --layer1
* Minimum CloudShell version column appears on list command output table
* gen2 is now the default view for list command

0.1.3 (2016-12-27)
------------------

* shellfoundry config will now echo all default configuration if not override by user

0.1.2 (2016-12-26)
------------------

* Config command will now encrypt password field

0.1.0 (2016-12-14)
------------------

* Show command was added to view all available versions of a template
* A new option was added to the 'new' command. Please welcome --version. It enables template versioning on shellfoundry.

0.0.44 (2016-12-12)
-------------------

* Fixed a bug in config command which caused shellfoundry to crash when config file has not existed

0.0.43 (2016-12-11)
-------------------

* List command is now able to filter results based on shell type (--tosca, --legacy, --all)

0.0.41 (2016-12-08)
-------------------

* Config command was added to allow setting configuration once for all shells in addition to local configuration

0.0.39 (2016-10-09)
-------------------

* Pack Shell icon if specified in shell-definition.yml file under metadata\template_icon for TOSCA based shells

0.0.38 (2016-09-28)
-------------------

* Update reference to cloudshell-rest-api 7.2.0.7 to use PUT method in update shell

0.0.35 (2016-09-15)
-------------------

* TOSCA support was added to pack and install commands
* Generate command was added that generates driver data model in Python

0.0.32 (2016-08-10)
-------------------

* Pack command downloads dependencies into dist directory
* Dependency for git was removed
* Local shell templates are supported
* Proxy support was added for access to github

0.0.31 (2016-08-04)
-------------------

* git prerequisite was removed. shellfoundry works without git being preinstalled

0.0.28 (2016-07-07)
-------------------

* Installation of package into CloudShell was fixed


0.0.26 (2016-06-23)
-------------------

* Images copied to the DataModel folder (Issue #21)

0.0.17 (2016-05-25)
-------------------

* Proper error message when install command fails in logging in into CloudShell

0.0.1 (2016-05-02)
------------------

* First release on PyPI.
