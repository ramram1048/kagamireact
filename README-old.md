# kagami

Tool for showing your FFXIV skill cycle in realtime.


#### Usages

- Makes you checking your dps cycle.
- On your skill cycle movie/raid PoV video or streaming, this makes truly easy to show your skill cycle to your viewers.

![preview](./mdimages/preview.gif)





## Prerequirements

- [ACT](http://advancedcombattracker.com/download.php)
- [FFXIV_ACT_Plugin](https://github.com/ravahn/FFXIV_ACT_Plugin/releases/latest)
- [OverlayPlugin(hibiyasleep version)](https://github.com/hibiyasleep/OverlayPlugin/releases/latest)

We will not cover the installation about ***ACT*** or ***OverlayPlugin***. 





## Download

- kagami overlay: <https://github.com/anoyetta-academy/kagami/releases/latest>

recent updated: 190710





## Installation

1. Setting latest version of ***ACT*** and ***OverlayPlugin***.



![install2.png](./mdimages/install2.png)

2. Download ***kagami plugin*** above, and extract it in your ***OverlayPlugin*** folder.



![install3.png](./mdimages/install3.png)

3. Open your ACT and go to ***Plugins*** tab > ***OverlayPlugin.dll*** tab and click "***Add***" button to add "***kagami***"(any name will be ok).



![install4.png](./mdimages/install4.png)

4. Go to the new tab and set ***URL*** to one ***Overlay URLs*** below.
5. Push ***Reload overlay*** and enjoy.



#### Overlay URLs

> `https://ramram1048.github.io/kagamireact/`
>
> `https://ramram1048.github.io/kagami-light/`
> (lightweight version, may contain beta features)





## Known Issues

- There is an issue on first runtime work weird now. 
  - This can be fixed pushing ***Reload overlay*** button once more.
- An issue wherein the 2+ skills on the timeline when the skills captured in a single timing.
- An issue with the same actions captured twice rarely.
  - Above the two issues may can be reduced by setting ***Parse log polling interval*** into low about to 10.
