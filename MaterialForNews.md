### Community

#### Seaside 3.5.0
[https://github.com/SeasideSt/Seaside/releases/tag/v3.5.0]()


#### New version of Pillar 
We are happy to announce a new release of pillar that supports the use of microdown as format.
Check [http://github.com/pillar-markup/pillar](http://github.com/pillar-markup/pillar)


#### DiscOrDance
DiscOrDance and Vizor are now publicly available under MIT License!
They support the analysis of discord forum.

You can find them on GitHub under USIREVEAL 
- [https://github.com/USIREVEAL/DiscOrDance]() and 
- [https://github.com/USIREVEAL/Vizor]().


#### Nova Stelo
NovaStelo is a block-style programming environment for multi agent system
[https://github.com/EiichiroIto/NovaStelo]()

#### Gratch
Block-style programming environment for tackling graph structure and algorithm
[https://github.com/EiichiroIto/Gratch]()

#### Cormas: 
A simple Telegram bot that allows users to control Cormas simulation with their phones
[https://www.youtube.com/watch?v=DRIRMZyDGSE]()

#### Pharo from Emacs
[https://revival.sh/shampoo/]()

#### Bell: An observability library written in Smalltalk 
[https://t.co/0lt1lwRUod]()


#### Gameye for Pharo
GAMEYE.app collection mobile App model and tools for Pharo.
[https://github.com/labordep/PharoGameye]()

#### Pharo Netatmo API implementation for Legrand Netatmo products.
Supported products : Weather station products / Healthy HomeCoach / Aircare product
[https://github.com/labordep/PharoNetatmoAPI]()

#### - Bytepair encoding 
Just to announce a first implementation of BytePairEncoding (a king of subword identification and text compression for Pharo). More precisely: it is a Subword-based tokenization algorithm.
[https://github.com/Ducasse/BytePairEncoder/]()

#### Memory Profiler
[https://github.com/jordanmontt/illimani-memory-profiler]()

#### Neo Networking 
This package contains a small framework to set up TCP or UDP network servers/services. By subclassing and overwriting just a couple of methods you get a working server for a specific protocol.
[https://github.com/svenvc/NeoNetworking]()

#### Accent transformers
[https://github.com/JanBliznicenko/accent-transformer]()

#### SnapDump 
is a software for pharo to create and manage runtime snapshots. 
[https://github.com/zweidenker/SnapDump]()

#### Pharo tiny images

I added a ‘dynamic’ image to the TinyBootstrap repo. It is a tiny image containing a pre-installed code loader. This code loader allows you to load additional classes and methods and (optionally) save this in the image. Code (in the form of a class method) can be executed from the command line. Once the image has the required content and functions as expected, it can be ‘fused’ in which case the code loader is removed from the image and only the defined functionality remains. To allow code to be installed from a regular Pharo 10 image, a small TinyTools repo is available which allows generation of code files. It also contains a small ‘Inspector’ class which simply prints out all classes (and optionally methods) which are present in the image. Installing this class is explained in the TinyTools readme.

The encoder/decoder combi used is an adapted version of the encoder/decoder in CodeParadise which are used to send code and objects between browser and application server. 

Have fun Smalltalking to tiny images! 

- [https://github.com/ErikOnBike/TinyTools]()
- [https://github.com/ErikOnBike/TinyBootstrap/blob/main/README.md#dynamic-image]()

#### CODEPARADISE ON PHARO11

Hi all. A small holiday present for anyone interested: https://github.com/ErikOnBike/CodeParadise now runs on P10 (and P11 with some care)! If you are using it on P8, please unload the CP-ClientEnvironment and reload it using the “pharo8” branch: 

Metacello new
  repository: 'github://ErikOnBike/CP-ClientEnvironment:pharo8';
  baseline: 'CodeParadise';
  load.
P11 seems to have some issues sometimes with restarting the image. Have not found the exact cause. Will look into this.

#### Ethnologue access from Pharo
- https://github.com/hernanmd/ethnologue

####
Molecule is a component oriented framework developed by Thalese
https://t.co/U9fBKhnlaV


#### Shield io from Pharo

I’d like to share a new Spec app for building badges made with Pharo 10. It is based on the Shields.io badge service provider. Select the badges you want, complete the required variables, and get your badge(s). You can also save and load commonly used variables, so it may help a bit to automate presenting your project’s README. 

https://github.com/hernanmd/shield-badges

#### PHARORAYLIB A BINDING FOR RAYLIB GAME LIBRARY
	- https://github.com/Zenchess/pharoRaylib

#### FIRMATA EXTENSION FOR PHARO
Adding support for i2c-enabled LCD panels.
- https://github.com/joao-pedro-braz/Firmata-LiquidCrystalI2C

#### P3 P3 is a modern, lean and mean PostgreSQL client for Pharo.
Release Version 1.4 · svenvc/P3

https://github.com/svenvc/P3

https://github.com/svenvc/P3/releases/tag/v1.4

Add SCRAM-SHA-256 authentication method (sponsored by Schmidt GmbH) Improve parsing speed for DateAndTime and Date based on the ISO PSQL 8601 format (as suggested by Esteban Maringolo) Extend P3Con…

Tx sven and your sponsor!

#### FFI analysis
-  FFICallBrowser - a tool to query FFI calls
[https://t.co/Zd3jshlJKA]()

####
PatternBuffer is a @pharoproject@twitter.com client for querying RDF databases:
[https://t.co/TBoybnuNqY]()

### Bloc updates
	- https://sympa.inria.fr/sympa/info/lse-openbloc
	add youtube ESUG presentation
	- https://pharoweekly.wordpress.com/2022/11/14/bloc-update/
	https://pharoweekly.wordpress.com/2022/10/25/bloc-update-harfbuzz/


### Blog Posts
- [https://medium.com/@dkgoutham1806/graph-algorithms-in-pharo-7d12af0be060]()
- [https://chinmaya.hashnode.dev/my-pharo-journey-making-a-simple-to-do-list-with-spec2]()
- [https://blog.sebastiansastre.co/article/how-to-create-a-pharo-smalltalk-plugin}()
- Roassal show: [https://pharoweekly.wordpress.com/2022/08/25/building-analyses-with-roassal-a-football-example/]()

	
### Pharo 

#### Social

- [https://mastodon.social/@pharoproject]()
- Google summer of code selected Pharo [https://gsoc.pharo.org]()
	
#### Pharo improvements
- Phep [https://github.com/pharo-project/pheps/pull/9]()

#### Released
Pharo VM 10.0.0 release logs
[https://pharoweekly.wordpress.com/2023/03/01/ann-pharo-vm-release-v10-0-0/]()

### Documentation


#### Mooc 

- [http://advanced-design-mooc.pharo.org]()
	
	
#### Blog post
- [thepharo.dev/2023/04/03/undeclared-variable-reparation-an-epic-journey-in-a-compiler-partiii/]()
- [thepharo.dev/2023/03/20/undeclared-variable-reparation-an-epic-journey-in-a-compiler/]()
- [thepharo.dev/2023/03/27/undeclared-variable-reparation-an-epic-journey-in-a-compiler-part-ii/]()
- [https://thepharo.dev/2021/04/28/advanced-stepping-and-custom-debugging-actions-in-the-new-pharo-debugger/]()
- [https://thepharo.dev/2021/04/02/debugger-extensions-in-pharo-9-0/]()
	
#### Pharo by example 9
The new version of Pharo by Example is now available for print.
- [https://www.bod.fr/librairie/pharo-9-by-example-stephane-ducasse-9782322394104]()
- [https://www.decitre.fr/livre-pod/pharo-9-by-example-9782322394104.html]()

#### Pharo with Style (new version) is now available as physical book. 
For example

- [https://www.decitre.fr/livre-pod/pharo-with-style-9782322182015.html]()
- [https://www.bod.fr/librairie/pharo-with-style-stephane-ducasse-9782322182015]()

#### Exercism promoting Pharo

- Introducing Pharo: [https://t.co/kkWZ6dKnqD]()
- Unique features of Pharo: [https://t.co/D1mmJxEDDo]()
	

