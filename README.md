# Assorted-fg-CustomScenery

The intention with this pack is to provide a fusion of various custom sceneries that many people would otherwise have a difficult time finding, since most of these were scattered all over the web and not provided in bulk by one author – as is the case with certain developers who have done scenery for FG such as [D-ECHO](https://github.com/D-ECHO?tab=repositories) and [legoboyvdlp](https://github.com/legoboyvdlp?tab=repositories), among several others.

Inside, you will find everything from airport layouts and objects (some even with custom models), to even [osm2city](https://osm2city.readthedocs.io/en/latest/index.html) structures and airport/navigation data!

-----

I have already installed the individual custom scenery packs in the proper way – all you'll need to do is download and add the folder into your FG launcher/arguments just as you would with any other custom scenery.

## Sources

I do not claim any of this great work as my own. It would be wrong to not give credit to the original authors and provide reference to where I found everything included in this pack, so here goes:

* The foundation for the entire pack was legoboyvdlp's [new VATSIM layouts](https://github.com/legoboyvdlp/VATSIM-new-layouts) repo – this is where it all started.
* SurferTim's [nav data update](https://github.com/SurferTim/navupdate) for certain airports
* Sydney osm2city+Australian airport package courtesy of [merspieler](https://github.com/merspieler?tab=repositories) and the [Australia scenery project](https://cdn.merspieler.tk/hosting/au-build/) – see [here](https://www.fgau.org/scenery-packages/australia) for more info.
* osm2city can be downloaded either through TerraSync or via [merspieler's server](https://cdn.merspieler.tk/osm2city/current/).

### Note on Australia

I have already accomplished the work of making the Sydney osm2city compatible with YSSY by deleting just the intruding+duplicate files – the only remaining loose end you should take into account is that although this repo will supply the latest version of the Australian airport package, which includes improved terminal models, it won't override the terminal objects that exist in Terrasync by default and will therefore appear duplicated unless you take care of it yourself. To do so, simply head into the proper directory (Objects/e150s40/e151s34), open up 5426688.stg in a text editor of your choice, and delete what should be the final 3 lines:
```
OBJECT_STATIC Terminal1-Main.ac 151.16661255 -33.93675475 53.41 150.5
OBJECT_STATIC Term1-PierC_02.ac 151.16515164 -33.93970065 17.97 104
OBJECT_STATIC Terminal1-Pier_B.ac 151.16891414 -33.93722588 10.55 127.3
```
Afterwards, it is also safe to delete the corresponding files.

* [Airport layout info](https://github.com/projectindia-FGFS/Airports) provided as part of Project India
* [Airbase model pack](https://github.com/JMaverick16/AirBase_models-pack) by JMaverick16
* SH-M's [VOTV](https://github.com/SH-M/VOTV-fg-CustomScenery), [VQPR](https://github.com/SH-M/VQPR-fg-CustomScenery), and [VOBL](https://github.com/SH-M/VOBL-fg-CustomScenery) sceneries
* Catalanoic's [WSSS](https://drive.google.com/file/d/1Kv5i3A8NV-kvFLiE7w8x_VYikKSqbtFs/view) scenery
* BAWV12's [LTAI](https://github.com/BAWV12/LTAI), [EGLL](https://github.com/BAWV12/EGLL), [NZCH](https://github.com/BAWV12/NZCH), [NZWN](https://github.com/BAWV12/NZWN), and [NZAA](https://github.com/BAWV12/NZAA) sceneries
* [ZSPD](https://github.com/20161229a/ZSPD) by 20161229a
