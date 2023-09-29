# *the* **hept** *manifesto*
an esoteric, explicit, efficient engine

## document contents
- [purpose](#purpose)
	- [clarity](#clarity)
	- [performance](#performance)
	- [architecture](#architecture)
- [goals](#goals)
- [support](#support)

# purpose
- traditional tools obscure core mechanics too much, spawning friction and restricting customisation and optimisation.
- conventions are accepted and not questioned, so there's need to dissolve these walls and reimagine game engine concepts.
- very few minimal game engines lean heavily into performance while also being clean and easy to use.

### clarity
- elimination of ambiguity, taking extreme care in the choice of words.
- every word in every name uses clearer terms that are more broadly understood.
- it must transform the complex into the effortlessly understandable.

### performance
- using raw C and the Vulkan API, minimal compromises.
- a single file will hold the entirety of the engine, improving compile times.
- extremely light-weight and only has the essentials, the engine must amplify your intent, not obstruct it.

### architecture
- built on a foundation of Vulkan, rather then bending a graphics API to the engine - the engine is shaped around the API.
- consistent forms, structures, and design across the entire tool.
- tailored for efficiency, the structure follows functional and procedural paradigms.

# goals
### *(complete)* v0.0 - announcement
- conceptualisation
- question-answering via convention breaking
### *(complete)* v0.1
- C layer: c7h16
- Vulkan layer: Hephaestus
- hept structure construction
- window creation
- Volk integration
### *(complete)* v0.2
- engine fundamentals
- shader processing
- basic rendering
### *(complete)* v0.3
- keyboard/mouse input
- default structures, shaders, objects
- event system
### *(in progress)* v0.4
- reconstruction via feedback
- multi-threading support
- auto buffer resizing/deleting
- examples construction
	- hept_tri
	- hept_pong
### v0.5 - public push
- png image loading
- basic audio/sfx system
- examples construction
	- hept_plat
	- hept_cube
	- hept_fps
### v0.6
### v0.7
### v0.8
### v0.9
### v1.0 - public release
- completely functional
- able to create games like NYKRA

# support
- open-source, open-community, open-future.
- examples created and maintained by passionate people.
- direct help and support to allow any game creation to come into existence with the least amount of stress.
