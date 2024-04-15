# dawntrail-lutris-installer-with-dlss

## why?

DLSS is greyed out when trying to run the benchmark. This fudge allows you to run with DLSS on supported hardware.  
Are all the things needed? probably not but I got it to work, so I left them all in.

## notes
The launcher may be a bit mental, but if you can survive it, the benchmark should run fine.

## Instructions
- Download the benchmark zip file from the official square enix website.
- install using this script in lutris.
- make sure the following are disabled in the lutris runner settings:
    * d3d extras
    * vkd3d
    * battle eye
    * EAC
    * (Windowed) virtual desktop
- run once, at the eula screen tick to never see it again.
- once you're at the launcher, close it.
- change the dxvk version to the default (v2.3.1)
- launch again, select DLSS and your resolution.
- run the benchmark.
