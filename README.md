# ACE3 Nightly Build
## What is this
This repository hosts nightly builds of the [ACE3](https://github.com/acemod/ACE3) mod for Arma 3. The source code for two branches (the `master` branch and the `medical-rewrite` branch) are pulled every night and get compiled. The resulting artefacts - but more important the full build logs - are hosted at this repository. 

__Please note that this project is total unofficial and is not affiliated with the ACE project team in any manner!__

## Risks
Be aware that those builds may be very unstable or feature incomplete and - under extreme conditions - may crash your game or corrupt your userprofile and savegames. 

__Only use these builds if you know what you are doing! There is NO support for any crash or data loss while using these builds.__ 

These builds are __ONLY__ for debugging and testing purpose and __SHOULD NOT__ be used in a productive enviroment.

## Where do I find the builds and logs
The logs can be found in the main repository ([master](https://github.com/Zakant/ACE3_Nightly/tree/master/Logs/master), [medical-rewrite](https://github.com/Zakant/ACE3_Nightly/tree/master/Logs/medical-rewrite)). The `.log` file contains the build log, while the `.zip` contains the zipped up logs from Mikero's build tools. If the files have the `.FAILED` file extension, that build was not successful. There aren't any artefacts uploaded for those builds, however the logs are still provided for error seeking.
The build artefacts can be found [here](https://github.com/Zakant/ACE3_Nightly/releases).

There are also steam workshop uploads for [master](https://steamcommunity.com/sharedfiles/filedetails/?id=1461430193) and [medical-rewrite](https://steamcommunity.com/sharedfiles/filedetails/?id=1460588026) that are automatically kept up to date.


## Need help
If you encounter any bugs with these builds make sure they do not result from incomplete features. If they do not, feel free to open an [issue](https://github.com/acemod/ACE3/issues). Make sure you follow the [contribution guidelines](https://github.com/acemod/ACE3/blob/master/.github/CONTRIBUTING.md) from ACE and fill out the issue template carefully. Especially make sure to provide the __correct commit hash and branch__. If you need further help please see [get in touch](https://github.com/acemod/ACE3#get-in-touch).
