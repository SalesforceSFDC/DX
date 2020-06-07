# DX
* [Salesforce CLI Command Reference](https://developer.salesforce.com/docs/atlas.en-us.220.0.sfdx_cli_reference.meta/sfdx_cli_reference/cli_reference.htm)
* [Salesforce DX Developer Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/sfdx_dev_intro.htm)
* [Create a new branch with git and manage branches](https://github.com/Kunena/Kunena-Forum/wiki/Create-a-new-branch-with-git-and-manage-branches)

## SFDX Commands

### Sandbox login
* sfdx force:auth:web:login -r https://test.salesforce.com


* 	force:alias:list
* 	`force:alias:set ai=vuk+ai@anablock.com`
* 	force:apex:class:create
* 	force:apex:execute
* 	force:apex:log:get
* 	force:apex:log:list
* 	force:apex:log:tail
* 	force:apex:test:report
* 	force:apex:test:run
* 	force:apex:trigger:create
* 	force:auth:jwt:grant
* 	force:auth:list
* 	force:auth:logout
* 	force:auth:sfdxurl:store
* 	force:auth:web:login
* 	force:config:get
* 	force:config:list
* 	force:config:set
* 	force:data:bulk:delete
* 	force:data:bulk:status
* 	force:data:bulk:upsert
* 	force:data:record:create
* 	force:data:record:delete
* 	force:data:record:get
* 	force:data:record:update
* 	force:data:soql:query
* 	force:data:tree:export
* 	force:data:tree:import
* 	force:doc:commands:display
* 	force:doc:commands:list
* 	force:lightning:app:create
* 	force:lightning:component:create
* 	force:lightning:event:create
* 	force:lightning:interface:create
* 	force:lightning:lint
* 	force:lightning:test:create
* 	force:lightning:test:install
* 	force:lightning:test:run
* 	force:limits:api:display
* 	force:mdapi:convert
* 	force:mdapi:deploy
* 	force:mdapi:deploy:cancel
* 	force:mdapi:deploy:report
* 	force:mdapi:describemetadata
* 	force:mdapi:listmetadata
* 	force:mdapi:retrieve
* 	force:mdapi:retrieve:report
* 	force:org:create
* 	force:org:delete
* 	force:org:display
* 	force:org:list
* 	force:org:open
* 	force:org:shape:create
* 	force:org:shape:delete
* 	force:org:shape:list
* 	force:org:snapshot:create
* 	force:org:snapshot:delete
* 	force:org:snapshot:get
* 	force:org:snapshot:list
* 	force:package1:version:create
* 	force:package1:version:create:get
* 	force:package1:version:display
* 	force:package1:version:list
* 	force:package:create
* 	force:package:install
* 	force:package:install:report
* 	force:package:installed:list
* 	force:package:list
* 	force:package:uninstall
* 	force:package:uninstall:report
* 	force:package:update
* 	force:package:version:create
* 	force:package:version:create:list
* 	force:package:version:create:report
* 	force:package:version:list
* 	force:package:version:promote
* 	force:package:version:report
* 	force:package:version:update
* 	force:project:create
* 	force:project:upgrade
* 	force:schema:sobject:describe
* 	force:schema:sobject:list
* 	force:source:convert
* 	force:source:delete
* 	force:source:deploy
* 	force:source:open
* 	force:source:pull
* 	force:source:push
* 	force:source:retrieve
* 	force:source:status
* 	force:user:create
* 	force:user:display
* 	force:user:list
* 	force:user:password:generate
* 	force:user:permset:assign
* 	force:visualforce:component:create
* 	force:visualforce:page:create
* 	help
* 	plugins
* 	plugins:generate
* 	plugins:install
* 	plugins:link
* 	plugins:trust:sign
* 	plugins:trust:verify
* 	plugins:uninstall
* 	plugins:update
* 	update
* 	which
* sfdx force:org:display
##
* sfdx force:alias:set MyDevSandbox=username@company.com.dev1
* sfdx force:alias:set VukSandbox=vuk.djukic_external.k2@coinbase.com.vuk
* sfdx force:config:set defaultusername=vuk.djukic_external.k2@coinbase.com
* `sfdx force:user:password:reset` - generate a password for your scratch org user
* `sfdx force:org:display` - to obtain the current scratch org's aauth token
