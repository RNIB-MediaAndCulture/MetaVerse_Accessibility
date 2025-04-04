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
A managed discussion which may or may not have a set agenda. There will usually be a chairperson managing the discussion and the meeting may be recorded as an audio visual file, written transcript, written notes or in some other fasion. A meeting may incorporate a 'speaker token' which mutes all users except for the chairperson and the person with the 'speaker token'. Meetings will commonly incorporate [presentations](#Presentation--demonstration--concert).
#### Relevant mechanics
chat, discuss, mute, speaker token, 

### Presentation / demonstration / concert
A meeting of multiple participants with presenters and an audience. Most of the communication will be one way (from the presenters to the audience) but it may flow the other way to allow reactions, comments and questions. There may be a separate chat function available to audience members (and additionally the presenters).
#### Relevant mechanics
Communicate, mute, present, show reaction,  

### Virtual space
A virtual representation of a physical location (real or imaginary) which can be navigated by the user often using an avatar. The virtual space may contain interactable objects, decorative objects, avatars or doors (or links) to other virtual spaces. Other types of experience will often happen in a virtual space.
#### Relevant Mechanics
Movement, wayfinding,  

## Mechanics

### Browse
Cycle through a collection of objects getting enough information about them to make a decision whether to find out more about them, interact with them, signpost or share them or perform some other action.  
#### Potential accessibility barriers

### Chat
Communicate with other users or software agents through a range of possible communication channels including spoken language, sign language, text, drawings, facial expression, dance etc.
#### Potential accessibility barriers

### Create Avatar

#### Potential accessibility barriers

### Discuss
Communicate with one or more users or software agents about an object or subject. Communication can be through a range of possible communication channels including spoken language, sign language, text, drawings, facial expression, dance etc. The object or topic should be available as a reference.
#### Potential accessibility barriers

### Search a collection

#### Potential accessibility barriers


### Signpost
Create a reference to something which can be shared with other users or software agents. 
#### Potential accessibility barriers



### View 
Get information about an object 
#### Potential accessibility barriers
##### Visual information is not accessible to people with sight loss. 
Provide a verbal description of the object. Consider [TTS](#TTS) 
##### Audio information is not accessible to people with hearing loss

## Accessible design patterns
#### TTS
Written text is synthesised into speech and played audibly to the user

