# serverless-hello-aws-nodejs 
Simple script to test serverless with aws and nodejs

## changelog

### Create it
```
>  sls create --template aws-nodejs --path serverless-hello-aws-nodejs
Serverless: Generating boilerplate...
Serverless: Generating boilerplate in "/Users/sblack/Git/sblack4/serverless-hello-aws-nodejs"
 _______                             __
|   _   .-----.----.--.--.-----.----|  .-----.-----.-----.
|   |___|  -__|   _|  |  |  -__|   _|  |  -__|__ --|__ --|
|____   |_____|__|  \___/|_____|__| |__|_____|_____|_____|
|   |   |             The Serverless Application Framework
|       |                           serverless.com, v1.73.1
 -------'

Serverless: Successfully generated boilerplate for template: "aws-nodejs"
>  cd serverless-hello-aws-nodejs
>  ls
README.md      handler.js     serverless.yml
```

### Commands

```
>  sls -h

Commands
* You can run commands with "serverless" or the shortcut "sls"
* Pass "--verbose" to this command to get in-depth plugin info
* Pass "--no-color" to disable CLI colors
* Pass "--help" after any <command> for contextual help

Interactive Quickstart
* Run serverless (or shortcut sls) without any arguments to initialize an interactive setup
  of functionalities related to given service or current environment
* Pass "--help-interactive" for contextual help on interactive CLI options

Framework
* Documentation: http://slss.io/docs

Environment Variables
* Set SLS_DEBUG=* to see debugging logs
* Set SLS_WARNING_DISABLE=* to hide warnings from the output
* Set SLS_MAX_CONCURRENT_ARTIFACTS_UPLOADS to control the maximum S3 upload SDK requests that are sent in parallel during the deployment of the service's artifacts. The default is 3. Note: increasing this too high might, actually, downgrade the overall upload speed

config ........................ Configure Serverless
config credentials ............ Configures a new provider profile for the Serverless Framework
config tabcompletion install .. Install a <tab> completion for chosen shell
config tabcompletion uninstall  Uninstall a <tab> completion for chosen shell
create ........................ Create new Serverless service
install ....................... Install a Serverless service from GitHub or a plugin from the Serverless registry
package ....................... Packages a Serverless service
deploy ........................ Deploy a Serverless service
deploy function ............... Deploy a single function from the service
deploy list ................... List deployed version of your Serverless Service
deploy list functions ......... List all the deployed functions and their versions
invoke ........................ Invoke a deployed function
invoke local .................. Invoke function locally
info .......................... Display information about the service
logs .......................... Output the logs of a deployed function
metrics ....................... Show metrics for a specific function
print ......................... Print your compiled and resolved config file
remove ........................ Remove Serverless service and all resources
rollback ...................... Rollback the Serverless service to a specific deployment
rollback function ............. Rollback the function to a specific version
slstats ....................... Enable or disable stats
plugin ........................ Plugin management for Serverless
plugin install ................ Install and add a plugin to your service
plugin uninstall .............. Uninstall and remove a plugin from your service
plugin list ................... Lists all available plugins
plugin search ................. Search for plugins
login ......................... Login or sign up for Serverless
logout ........................ Logout from Serverless
generate-event ................ Generate event
test .......................... Run HTTP tests
dashboard ..................... Open the Serverless dashboard
output ........................ 
output get .................... Get value of dashboard deployment profile parameter
output list ................... List all dashboard deployment profile parameters
param ......................... 
param get ..................... Get value of dashboard service output
param list .................... List all dashboard service outputs
studio ........................ Develop a Serverless application in the cloud.
dev ........................... undefined

Plugins
AwsCommon, AwsCompileAlbEvents, AwsCompileAlexaSkillEvents, AwsCompileAlexaSmartHomeEvents, AwsCompileApigEvents, AwsCompileCloudFrontEvents, AwsCompileCloudWatchEventEvents, AwsCompileCloudWatchLogEvents, AwsCompileCognitoUserPoolEvents, AwsCompileEventBridgeEvents, AwsCompileFunctions, AwsCompileIoTEvents, AwsCompileLayers, AwsCompileS3Events, AwsCompileSNSEvents, AwsCompileSQSEvents, AwsCompileScheduledEvents, AwsCompileStreamEvents, AwsCompileWebsockets, AwsConfigCredentials, AwsDeploy, AwsDeployFunction, AwsDeployList, AwsInfo, AwsInvoke, AwsInvokeLocal, AwsLogs, AwsMetrics, AwsPackage, AwsProvider, AwsRemove, AwsRollback, AwsRollbackFunction, Config, Create, Deploy, Executable, HttpApiEvents, Info, Install, InteractiveCli, Invoke, Logs, Metrics, Package, Plugin, PluginInstall, PluginList, PluginSearch, PluginUninstall, Print, Remove, Rollback, ServerlessEnterprisePlugin, SlStats
```

### Test Locally

```

```