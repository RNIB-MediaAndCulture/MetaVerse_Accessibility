# Metaverse use cases
This document aims to encompass the ways in which the metaverse is or may be used in order to identify accessibility barriers and offer suggested solutions. It is broadly inspired by object based programming where something can 'inherit' properties from parents. In this way it offers 'aspects of experience' which will embody aspects of a metaverse use case. A guided tour of a museum will inherit from [Exhibition](#exhibition) and [Presentation](#presentation--demonstration--concert) whereas a guided tour of the White House will inherit from [Virtual Space](#virtual-space) and [Presentation](#presentation--demonstration--concert) and a virtual representation of Pompei may inherit from [Exhibition](#exhibition) and [Virtual Space](#virtual-space).
The document then lists relevant mechanics for each aspect of experience. These are actions you might expect to perform as part of this experience or ways in which you might expect to interact with it. These describe potential accessibility barriers and ways in which you might overcome those barriers. The suggestions of ways to overcome the barriers may point to accessibility design patterns.

## Aspects of Experience 

### Chatroom
A virtual space where two or more users can converse. Users will typically use avatars (representations of themselves) which may be fully virtual or could be a combination of virtual reality and input from a camera.
#### Relevant Mechanics
[Create Avatar](#create-avatar), [Customise Avatar](#customise-avatar), [Chat](#chat)

### Collaboration
Two or more users can work together on a collaborative project. This could be a document, picture, whiteboard etc.
#### Relevant Mechanics
[Add text](#add-text), [Annotate](#annotate), [Draw](#draw), [Pin note](#pin-note), [Update in realtime](#update-in-realtime) 

### Exhibition
A collection of objects of interest such as a museum or art gallery. 
#### Relevant Mechanics
[Browse](#browse), [Signpost](#signpost), [Discuss](#discuss), [Search a collection](#Search-a-collection), [View](#view)

### Meeting
A managed discussion which may or may not have a set agenda. There will usually be a chairperson managing the discussion and the meeting may be recorded as an audiovisual file, written transcript, written notes or in some other fashion. A meeting may incorporate a 'speaker token' which mutes all users except for the chairperson and the person with the 'speaker token'. Meetings will commonly incorporate [presentations](#Presentation--demonstration--concert).
#### Relevant mechanics
[Chat](#chat), [Discuss](#discuss), [Mute](#mute), [Speaker token](#speaker-token)

### Presentation / demonstration / concert
A gathering of multiple participants with presenters and an audience. Most of the communication will be one way (from the presenters to the audience) but it may flow the other way to allow reactions, comments and questions. There may be a separate chat function available to audience members (and additionally the presenters).
#### Relevant mechanics
[Chat](#chat), [Mute](#mute), [Present](#present), [Show reaction](#show-reaction), [Spectate](#spectate)  

### Payment
Perform a financial transaction. This will need to cover the exchange of funds and secure record of the transaction. Some use cases will also require a proof or purchase mechanism for pre-orders, purchased services etc.
#### Relevant mechanics
[Authenticate](#authenticate), [Invoice](#invoice), [Pay](#pay), [Receive receipt](#receive-receipt), [Request quote](#request-quote), [Proof-of-purchase](#proof-of-purchase), [Quote](#Quote)

### Scheduling
Manage time allocations for a service or virtual object or timed events. 
#### Relevant mechanics
[Authenticate](#authenticate), [Book](#book), [Release booking](#release-booking), [Read schedule](#read-schedule)

### Virtual space
A virtual representation of a physical location (real or imaginary) which can be navigated by the user often using an avatar. The virtual space may contain interactable objects, decorative objects, avatars or doors (or links) to other virtual spaces. Other types of experience will often happen in a virtual space.
#### Relevant Mechanics
[Browse](#browse), [Copy Object](#copy-object), [Create Avatar](#create-avatar), [Customise Avatar](#customise-avatar), [Drop](#drop),  [Interact](#interact), [move](#move), [Navigate](#navigate), [Orient](#orient), [Pick-up](#pick-up) [Search a collection](#Search-a-collection), [Signpost](#signpost), 

## Mechanics

### Add text
Add text to an existing document or object
#### Potential accessibility barriers
##### Text entry may not be accessible to print disabled people (people with sight loss, dyslexia or other conditions preventing them from easily accessing text)
- Ensure text is high contrast, of a good size and avoid novelty fonts
- Consider enabling text customisation to allow colours, fonts and text size to be changed by the user
- Avoid transparent or translucent backgrounds and enable single block coloured backgrounds
- Allow voice input and text-to-speech

### Annotate
Attach an auxhillary note to a document or object. 
#### Potential accessibility barriers
##### Blind and partially sighted users may struggle to attach an annotation to the document or object
- Consider providing a spoken interface that can cycle through objects by their descriptions in metadata 
- consider [Computer Vision](link) or [Human Assistance](link)
##### Text entry may not be accessible to print disabled people (people with sight loss, dyslexia or other conditions preventing them from easily accessing text)
- Ensure text is high contrast, of a good size and avoid novelty fonts
- Consider enabling text customisation to allow colours, fonts and text size to be changed by the user
- Avoid transparent or translucent backgrounds and enable single block coloured backgrounds
- Allow voice input and text-to-speech
- Consider emojis (with TTS support) to reduce the need for words

### Authenticate
A mechanism to prove a user's ID.   
#### Potential accessibility barriers



### Book
To reserve an object, virtual space or event. This may be an exclusive reservation or may enable the user to be one of many who reserve the object, virtual space or event. The reservation may be time-based.
#### Potential accessibility barriers


### Browse
Cycle through a collection of objects getting enough information about them to make a decision whether to find out more about them, interact with them, signpost or share them or perform some other action.  
#### Potential accessibility barriers

metadata
- consider [Computer Vision](link) or [Human Assistance](link)

### Chat
Communicate with other users or software agents through a range of possible communication channels including spoken language, sign language, text, drawings, facial expression, dance etc.
#### Potential accessibility barriers

### Copy object
Create a copy of an object from a virtual space or exhibition. This associates a copy with the user's avatar but leaves a copy in the virtual space or exhibition.
#### Potential accessibility barriers


### Create Avatar
Bring into existence an avatar (visual representative) of the user to be used in virtual spaces. The avatar may or may not resemble the user and could blend a picture or video of the user with a virtual object (as in use a texture map based on a picture of the user's face or appearence).
#### Potential accessibility barriers

- consider [Computer Vision](link) or [Human Assistance](link)
  
### Customise Avatar
Change the appearence of an existing avatar.
#### Potential accessibility barriers


- consider [Computer Vision](link) or [Human Assistance](link)

### Discuss
Communicate with one or more users or software agents about an object or subject. Communication can be through a range of possible communication channels including spoken language, sign language, text, drawings, facial expression, dance etc. The object or topic should be available as a reference.
#### Potential accessibility barriers

### Draw
Make marks on a document or virtual object.
#### Potential accessibility barriers
##### Blind users may not be aware of marks that are already made on the document or object. 
- Consider AI computer vision to describe existing marks
- Consider [Computer Vision](link) or [Human Assistance](link)
- Enable users who have made marks to add metadata describing what they've drawn 
##### Blind users may not be able to detect the marks they are making
- Consider AI powered mark making ("Draw a circle around the picture of a cat")
- Consider clip art or emojis that can be added and AI powered positioning
- Consider [Human Assistance](link) where the assistant can add marks according to a users instructions. 

### Drop
Place an object in a virtual space or exhibition. This disassociates it with the user's avatar and places it in the virtual space or exhibition.
#### Potential accessibility barriers
##### Blind users may not know where the object can be placed (obstacles in the way, restricted areas etc)



### Interact
Perform an action on an interactable object. The user will need to be able to understand what they can do with the object and how they do it.
#### Potential accessibility barriers
##### Visual intructions or clues to an object's use may not be accessible to blind and partially sighted people
- Ensure that all visual instructions or clues are communicated audibly or verbally
##### If an action cannot be performed and this is communicated visually then this may not be accessible to a blind or partially sighted user
- Ensure that all visual messages are communicated audibly or verbally

### Invoice
Formally send a request for payment.
#### Potential accessibility barriers

### Move
Reposition a users avatar from one place in a virtual space to another one. This may be via continuous user controlled movement, through a continuous computer controlled movement or instantaneous movement. If through continuous movement then users may benefit from finding out about objects and landmarks that become perceivable as they travel.  
#### Potential accessibility barriers

Continuous movement
- consider [Computer Vision](link) or [Human Assistance](link)

### Mute
To render something silent. This may be a user making something else silent or turning off their own microphone.
#### Potential accessibility barriers
##### Controls may not be accessible to blind and partially sighted people
- Consider keyboard shortcuts, gestures, voice commands as appropriate to the platform
##### Blind or partially sighted user may not be aware they are muted
- Ensure that mute icon is not just presented visually
- Consider speech detection so that if the user is talking and muted they are alerted that they are muted (potentially with a spoken message and voice interface"Unmute? Yes or No." or potentially with a sound that indicates they are muted)  

### Navigate
To understand how to get from where a user is in a [virtual space](#virtual-space) to another position in the virtual space that they want to get to. When a user navigates they become informed of where locations of interest are in releation to them so that they can then [move](#move) to them or towards them.
#### Potential accessibility barriers

 - consider [Computer Vision](link) or [Human Assistance](link)

### Orient
Where a user gains an understanding of the locations of objects that surround their avatar in a virtual space. This may include the whole virtual space or focus on a window. For instance in a first person view orienting may describe just the objects on the screen (requiring the user to turn their avatar to bring more objects into focus) or it may also communicate objects that are 'off camera' to the user.
#### Potential accessibility barriers
##### Visual information is not accessible to people with sight loss. 
- Provide an audio or verbal description of the scene or space. Consider [audio beacons](#audio-beacons), [audio description](#audio-description), [Text-to-Speech (TTS)](#Text-to-Speech) 
##### Audio information is not accessible to people with hearing loss

##### People with cognitive disabilities may be overwhelmed if given too much information
- In a first person view consider focusing on just the objects closest to the center of the view to allow the user to explore by turning their head.
- Allow the user to step through the objects one at a time so they get information about one object then trigger the interface moving on to describe the next one. 

> [!NOTE]
> Do we need Pay and Receive Payment as two seperate mechanisms? It may be important that users know they have received a payment...

### Pay
Transfer money to another person or account. 
#### Potential accessibility barriers

### Pick-up
Take an object from a virtual space or exhibition. This removes it from the virtual space or exhibition and associates it with the user's avatar.
#### Potential accessibility barriers

### Pin note
Place a short 'sticky note' style comment on a document or virtual object.
#### Potential accessibility barriers


- consider [Computer Vision](link) or [Human Assistance](link)

### Present
Deliver a presentation to 1 or more users. This is expected to be a one-way communication but could include showing pictures, playing videos, playing audio or using other media or props. 
#### Potential accessibility barriers

> [!NOTE]
> If Receive receipt provides a verifiable record of the amount paid and the reason for the payment then is a seperate "proof of purchase" mechanism required? Are there reasons to create a non-verifiable receipt? 

### Proof-of-purchase
A way to demonstrate that an object, asset or service has been paid for.
#### Potential accessibility barriers


### Quote
Present an estimate of the costs of a purchase. This is not expected to be legally binding but there should be an immutable record of the value quoted and the specifics of what the quote is for.
#### Potential accessibility barriers

### Read schedule
Obtain information from a schedule of events or timings.
#### Potential accessibility barriers

### Receive receipt
The user is provided a token that demonstrates they have paid for something. This may be a verifiable record of the amount paid and the reason for the payment.
#### Potential accessibility barriers

### Release booking
Cancelling a reservation to an object, virtual space or event.
#### Potential accessibility barriers

### Request quote
Formally request a financial quote. The request will need to contain details of the goods or services being quoted for.
#### Potential accessibility barriers
##### Any details of the quote communicated visually may not be accessible to blind and partially sighted users
- All information in a quote should be available visually and audibly 

### Search a collection
View a reduced selection of objects from a collection that meet a given set of search criteria.
#### Potential accessibility barriers


- consider [Computer Vision](link) or [Human Assistance](link)

### show reaction
A simple feedback mechanism where a 'reaction' picture is displayed to a presenter and other spectators. This is usually a simple emoji such as a heart, thumbs up, laughing emoji etc 
#### Potential accessibility barriers

### Signpost
Create a reference to something which can be shared with other users or software agents. 
#### Potential accessibility barriers


### speaker token
A token that specifies who is allowed to communicate to the group. 
#### Potential accessibility barriers


### Spectate
To observe a presentation or event without providing communication or feedback.
#### Potential accessibility barriers


### Update in realtime
To update the users view of a document or object as changes are being made.
#### Potential accessibility barriers

- consider [Computer Vision](link) or [Human Assistance](link)

### View 
Get information about an object. 
#### Potential accessibility barriers
##### Visual information is not accessible to people with sight loss. 
- Provide a verbal description of the object via embedded metadata. Consider [Text-to-Speech (TTS)](#text-to-Speech)
- If metadata not available consider [Computer Vision](link) or [Human Assistance](link)
##### Audio information is not accessible to people with hearing loss
- Provide visual equivalents for any sounds that are of interest or of importance. Consider [captions](#captions), [speech to text](#speech-to-text) 


## Accessible design patterns

### Audio beacons
Audio beacons are sounds 'placed around' the user using immersive audio. They can act as a way to locate objects in a virtual space, to annotate objects or to provide waypoints for navigation.

### Automated language translation
AI based software that can translate between two languages in realtime. Effectiveness may be hampered by strong accents or speech impediments, multiple voices talking at once or low bandwidth or unreliable internet connections. Accuracy is often higher between languages with more speakers or between languages in the same language families (ie French and Spanish, Turkish and Arabic, Dutch and German). Translation between written text may be more accurate.

### Captions
Captions are lines of text within a users view that correspond to audio information. They can translate between languages, provide a real-time transcript of speech for people who would struggle to hear or understand spoken language or describe sounds for people with hearing loss. They may also encourage language learning or reduce cognitive load by providing multi-channel communication. 

### Clear Language
Using simplified language. << There are many reasons for doing this and different ways to simplify the language. Using language that corresponds to a reduced reading age, avoiding colloquialisms, shorter sentences, unambiguous language etc. Is this one design pattern or several? 

### Computer Vision
AI that takes an image as input and attempts to describe the image in text. This is a difficult task for AI to perform and can be improved if the context is narrowed. AI is expected to improve in performing this task but currently may focus on the wrong visual elements to describe, use strange or out of place language or hallucinate visual elements that are not present in the picture.

### High Contrast
Parts of a visual are made to 'stand out' by using contrasting colours. This is often used for text but could also be used for symbols, the outlines of objects etc. WCAG contains a formula for determining the contrast ratio between two colours.

### Human assistance
By using telecommunication links a human assistant can be brought in to aid a blind user. This could be to select items based on criteria ("Which of these pens is red?"), describe a document ("What is this letter about?") or to orient a user ("Which way is the seminar area? Can you tell me when I am facing towards it?"). The human assistant could be a paid employee of the platform, a support worker who is paid for by a person's work or government assistance scheme or an unpaid volunteer. Professional support workers are often bound by confidentiality agreements in their contracts.

### Magnification
Part of the visuals are enlarged making them easier to see. 

### Mono audio
People who have hearing loss in one ear can benefit from stereo audio being flattened to mono audio so that no audio information is going just to the ear with hearing loss. 

### Remote spoken language interpreter
An interpreter who translates between two spoken languages via a telecommunications link. They may be funded by a user's workplace, by a service provider through a paid service covering multiple languages or may be funded by the user themselves.

### Respeaking
Users with speech impediments may use a respeaker to repeat their words after them. Respeakers are often familiar with the user and train on their voice so they can understand what they are saying. AI based automated respeakers may exist.

### Speech to text
Audio speech is converted into a stream of text 

### Tasklist
A list of actions which may help someone with cognitive disabilities keep track of actions they need to do or plan to do.

### Text to speech
Written text is synthesised into speech and played audibly to the user

### Video Sign Language Interpreter
A sign language interpreter who is visible to a Deaf sign language user and can hear the room and speak to it. They will translate speech into sign language for a user and translate the users sign language back into speech for other users. This can be tiring to do so sign language interpreters often work in pairs, switching over regularly.

### Visual sound effects
In a virtual space objects that make sounds can have captions or speech bubbles placed on them to make them accessible for people with hearing loss. 



