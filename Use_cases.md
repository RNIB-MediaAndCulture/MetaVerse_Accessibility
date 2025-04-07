# Metaverse use cases
This document aims to encompass the ways in which the metaverse is or may be used in order to identify accessibility barriers and offer suggested solutions. It is broadly inspired by object based programming where something can 'inherit' properties from parents. In this way it offers 'types of experience' which will embody aspects of a metaverse use case. A guided tour of a museum will inherit from [Exhibition](#exhibition) and [Presentation](#presentation--demonstration--concert) whereas a guided tour of the White House will inherit from [Virtual Space](#virtual-space) and [Presentation](#presentation--demonstration--concert) and a virtual representation of Pompei may inherit from [Exhibition](#exhibition) and [Virtual Space](#virtual-space).
The document then lists relevant mechanics for each type of experience. These are actions you might expect to perform as part of this experience or ways in which you might expect to interact with it. These describe potential accessibility barriers and ways in which you might overcome those barriers. The suggestions of ways to overcome the barriers may point to accessibility design patterns.

## Types of Experience 

### Chatroom
A virtual space where two or more users can converse. Users will typically use avatars (representations of themselves) which may be fully virtual or could be a combination of virtual reality and input from a camera.
#### Relevant Mechanics
Create Avatar, customise Avatar, chat

### Exhibition
A collection of objects of interest such as a museum or art gallery. 
#### Relevant Mechanics
[View](#view), signpost, discuss, search a collection, browse

### Meeting
A managed discussion which may or may not have a set agenda. There will usually be a chairperson managing the discussion and the meeting may be recorded as an audiovisual file, written transcript, written notes or in some other fashion. A meeting may incorporate a 'speaker token' which mutes all users except for the chairperson and the person with the 'speaker token'. Meetings will commonly incorporate [presentations](#Presentation--demonstration--concert).
#### Relevant mechanics
chat, discuss, mute, speaker token, 

### Presentation / demonstration / concert
A gathering of multiple participants with presenters and an audience. Most of the communication will be one way (from the presenters to the audience) but it may flow the other way to allow reactions, comments and questions. There may be a separate chat function available to audience members (and additionally the presenters).
#### Relevant mechanics
Communicate, mute, present, show reaction,  

### Virtual space
A virtual representation of a physical location (real or imaginary) which can be navigated by the user often using an avatar. The virtual space may contain interactable objects, decorative objects, avatars or doors (or links) to other virtual spaces. Other types of experience will often happen in a virtual space.
#### Relevant Mechanics
[Browse](#browse), [Copy Object](#copy-object), [Drop](#drop),  [interact](#interact), [move]#(move), [Pick-up](#pick-up) [Search a collection](#Search-a-collection), [Signpost](#signpost), [Navigate](#Wayfind)

## Mechanics

### Browse
Cycle through a collection of objects getting enough information about them to make a decision whether to find out more about them, interact with them, signpost or share them or perform some other action.  
#### Potential accessibility barriers

### Chat
Communicate with other users or software agents through a range of possible communication channels including spoken language, sign language, text, drawings, facial expression, dance etc.
#### Potential accessibility barriers


### Create Avatar

#### Potential accessibility barriers

### Copy object
Create a copy of an object from a virtual space or exhibition. This associates a copy with the user's avatar but leaves a copy in the virtual space or exhibition.
####

### Discuss
Communicate with one or more users or software agents about an object or subject. Communication can be through a range of possible communication channels including spoken language, sign language, text, drawings, facial expression, dance etc. The object or topic should be available as a reference.
#### Potential accessibility barriers

### Drop
Place an object in a virtual space or exhibition. This disassociates it with the user's avatar and places it in the virtual space or exhibition.
#### Potential accessibility barriers


### Interact
Perform an action on an interactable object. The user will need to be able to understand what they can do with the object and how they do it.
#### Potential accessibility barriers

### Orient
Where a user gains an understanding of the locations of objects that surround their avatar in a virtual space. This may include the whole virtual space or focus on a window. For instance in a first person view orienting may describe just the objects on the screen (requiring the user to turn their avatar to bring more objects into focus) or it may also communicate objects that are 'off camera' to the user.
#### Potential accessibility barriers
##### Visual information is not accessible to people with sight loss. 
- Provide an audio or verbal description of the scene or space. Consider [audio beacons](#audio-beacons), [audio description](#audio-description), [Text-to-Speech (TTS)](#Text-to-Speech) 
##### Audio information is not accessible to people with hearing loss

##### People with cognitive disabilities may be overwhelmed if given too much information
- In a first person view consider focusing on just the objects closest to the center of the view to allow the user to explore by turning their head.
- Allow the user to step through the objects one at a time so they get information about one object then trigger the interface moving on to describe the next one. 

### Pick-up
Take an object from a virtual space or exhibition. This removes it from the virtual space or exhibition and associates it with the user's avatar.
#### Potential accessibility barriers


### Search a collection

#### Potential accessibility barriers


### Signpost
Create a reference to something which can be shared with other users or software agents. 
#### Potential accessibility barriers





### Move
Reposition a users avatar from one place in a virtual space to another one. This may be via continuous user controlled movement, through a continuous computer controlled movement or instantaneous movement. If through continuous movement then users may benefit from finding out about objects and landmarks that become perceivable as they travel.  
#### Potential accessibility barriers



### Navigate
To understand how to get from where a user is in a [virtual space](#virtual-space) to another position in the virtual space that they want to get to. When a user navigates they become informed of where locations of interest are in releation to them so that they can then [move](#move) to them or towards them.
#### Potential accessibility barriers


### View 
Get information about an object. 
#### Potential accessibility barriers
##### Visual information is not accessible to people with sight loss. 
- Provide a verbal description of the object. Consider [Text-to-Speech (TTS)](#Text-to-Speech) 
##### Audio information is not accessible to people with hearing loss
- Provide visual equivalents for any sounds that are of interest or of importance. Consider [captions](#captions), [speech to text](#speech-to-text) 


## Accessible design patterns

### Audio beacons
Audio beacons are sounds 'placed around' the user using immersive audio. They can act as a way to locate objects in a virtual space, to annotate objects or to provide waypoints for navigation.

### Captions
Captions are lines of text within a users view that correspond to audio information. They can translate between languages, provide a real-time transcript of speech for people who would struggle to hear or understand spoken language or describe sounds for people with hearing loss. They may also encourage language learning or reduce cognitive load by providing multi-channel communication. 

### Clear Language
Using simplified language. << There are many reasons for doing this and different ways to simplify the language. Using language that corresponds to a reduced reading age, avoiding colloquialisms, shorter sentences, unambiguous language etc. Is this one design pattern or several? 

### High Contrast
Parts of a visual are made to 'stand out' by using contrasting colours. This is often used for text but could also be used for symbols, the outlines of objects etc. WCAG contains a formula for determining the contrast ratio between two colours.

### Magnification
Part of the visuals are enlarged making it easier to see. 

### Mono audio
People who have hearing loss in one ear can benefit from stereo audio being flattened to mono audio so that no audio information is going just to the ear with hearing loss. 



### Speech to text
Audio speech is converted into a stream of text 

### Text to speech
Written text is synthesised into speech and played audibly to the user

### Visual sound effects
In a virtual space objects that make sounds can have captions or speech bubbles placed on them to make them accessible for people with hearing loss. 



