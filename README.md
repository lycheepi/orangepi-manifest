# orangepi-manifest

Orange Pi Repo Manifest README.md

This repo is used to download manifests for Orange Pi BSP

To use this manifest repo, the 'repo tool must be installed first.

$: mkdir ~/bin
$: curl http://commondatastorage.googleapis.com/git-repo-downloads/repo  > ~/bin/repo
$: chmod a+x ~/bin/repo
$: PATH=${PATH}:~/bin

To excute 
$: mkdir <release>
$: cd <release>
$: repo init -u https://github.com/lycheepi/orangepi-manifest -b <branch name> [ -m <release manifest>]
  
Each branch will have detailed READMEs describing exact syntax.

Examples  

To download the orangepi-3-3.10.65-1.0.0_ga.xml release

repo init -u https://github.com/lycheepi/orangepi-manifest -m orangepi-3-3.10.65-1.0.0_ga.xml -b orangepi-linux-rocko
