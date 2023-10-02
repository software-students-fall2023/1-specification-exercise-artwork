# Specification Phase Exercise

A little exercise to get started with the specification phase of the software development lifecycle. See the [instructions](instructions.md) for more detail.

## Clickable Prototype

[ARtwork Clickable Prototype](https://www.figma.com/proto/Zl5MFy7CDjFsLBtVzCIJcU/ARtwork?page-id=0%3A1&type=design&node-id=1-2&viewport=128%2C447%2C0.16&t=g78e8q0ZKunUMIPV-1&scaling=scale-down&starting-point-node-id=1%3A2&mode=design)


## Team members

- Aditya Pandhare: https://github.com/awesomeadi00
- Anzhelika Nastashchuk: https://github.com/annsts
- Baani Pasrija: https://github.com/zeepxnflrp
- Zander Chen: https://github.com/ccczy-czy

## Stakeholders
**Stakeholders Frustrations and Pain Points**: 
- **Digital Artists**: They mentioned, “I used to do paintings and have moved more towards digital art now, where there isn’t as much interaction.” It can be observed that there is a lack of community and connection in the digital art world, compared to more traditional forms of art.
- **City Explorers**: They mentioned that he would prefer if exploration applications had more access to less touristy areas to really explore the in-depths of the city rather than just the face of the city.  
- **Photographers**: They also mentioned that as a photographer and artist, he would find it more motivating to be able to capture unique sights of the city through art. 
- **Graphic Design students**: They mentioned that although museums offer a good amount of exhibitions of artworks, they are still missing the part of interaction, for example, the openings of the galleries and a space solely for the artist she is interested in. Galleries sometimes fail to provide enough artworks for her to view.

**Stakeholders Goals**: 
1. Create an application with a social aspect that can bring artists together and re-instill a sense of community within the digital art world. A way to do this is to allow users to make and share art. 
2. Create an application to encourage exploration of the city in general and to find new unique and interesting spots throughout the city. 
3. To create a platform to introduce and teach the use of AR technology to people who may not be aware/familiar with its capabilities. 
4. Create an application that encourages non-artists to explore art shared by communities of artists in a non-traditional way - that is, making the city a gallery. 
5. Create an application that makes art more accessible to everyone, disregarding economical, physical, geographical limitations.


## Product Vision Statement
ARtwork is a groundbreaking mobile application that transforms cities into vibrant canvases of creativity and exploration through the magic of augmented reality. Our vision is to empower teenagers and young adults to treat their city as a canvas to design, rediscover their urban environments, fostering a deep connection to their communities and city while unlocking their inner artists.  


## User Requirements

|  | User Stories | Estimation of Effort | Acceptance Criteria | 
| - | ----- | :-----: | ----- | 
| 1. | As a digital artist, I want to display my art so I can get some recognition or viewership. | Medium | <ul><li>There is a "Profile" tab on the app where users can have their username, profile picture and relevant website links associated with them.</li><li>Users can create their artwork all around the city through the “Capture” tab and switch the toggle to “create”. This will allow them to access a palette of tools where they can begin drawing on their screen which would appear to be drawn on the city through AR.</li><li>When another user taps on their art, the artist’s profile and art description is shown.</li><li>Other users can upvote artists' works and even share them with other users.</li></ul> | 
| 2. | As a local of NYC with no art experience, I want to look at and understand AR art while walking around so I can feel more connected to my community in a virtual world. | Hard | <ul><li>Users can view the artworks all over the city using their camera through the “Capture” tab by switching the toggle to ‘view’ mode. This will allow users to simply view the art and not draw anything on the screen.</li><li>When clicked on artworks, it will be followed by a description and profile of the artist to understand more about the art piece.</li><li>The app provides an intuitive and user-friendly interface for navigating and viewing AR art while walking around the city.</li><li>Users can view any artist's work by saving and viewing their artwork in the “Gallery” tab; they can see more of these artists’ works and get notified when they publish new art.</li><li>Users can share art on different social media platforms to further have discussions with their friends, and develop better connections to the community.</li></ul> |
| 3. | As a college student in NYC, I want to save the artworks I see and share them with my friends so that I can have interesting conversations with them. | Medium | <ul><li>Users should be able to save the art to their personal “Gallery” tab.</li><li>The app allows users to easily share specific pieces or their entire gallery on various social media platforms.</li><li>Users can also share profiles of their favorite artists with friends.</li></ul> | 
| 4. | As a user of the AR app, I expect to receive the location information for artworks for me to go and explore the artworks throughout the city. | Medium | <ul><li>The app offers the “Explore” tab, the user can see all artworks/events nearby them.</li><li>They can also use a filter to explore specific searches for pieces of artwork or events hosted by users or the company.</li><li>When selecting an artwork/event, they are provided with a description and details, the artist/owners and the art’s location (maps link included).</li></ul> | 
| 5. | As a user interested in adding variety to my daily routine, I want the app to send me notifications encouraging me to step outside and search for artworks. | Medium | <ul><li>The app sends notifications to users of certain places to visit throughout the city.</li><li>This will open the “Explore” tab where users can look through artworks/events nearby to their location.</li></ul> |
| 6. | As a user, I want the ability to replace artworks created by other artists within the app. I expect the app to track these replacements, allowing me to view past artworks that have been swapped. | Very Hard | <ul><li>Users who are artists can simply draw over the artwork on the "Capture" tab.</li><li>They can also choose to upload artwork if they have an AR file (GLB or gITF) within the "View" tab by pressing 'Upload' when the ‘Create’ toggle is on.</li><li>The app maintains a tracking system to record these replacements.</li><li>Users can access a history of past artworks that have been swapped.</li></ul> | 
| 7. | As a user, I want the ability to create my own personal artwork of the city just for my own view so no one can edit or draw over my work. | Medium | <ul><li>In the “Profile” tab under settings, users can set their artworks as private under ‘user privacy’. This way no one can see/edit their artworks except them.</li></ul> | 
| 8. | As a user, I want the ability to restrict myself from viewing certain pieces of artwork, for censorship reasons etc. | Very Hard | <ul><li>The app has to decide how to detect what certain pieces of art look like (perhaps through the incorporation of AI/Machine Learning).</li><li>Based on what the app detects, it will label certain artworks and filter what can be seen and what can’t be seen depending on the user’s needs.</li></ul> | 
| 9. | As a photographer, I want to be able to take photographs of the city through the app in order to capture everyone’s artwork at once. | Medium | <ul><li>The "Capture" tab will have a photo-capture feature.</li><li>The photos will be automatically saved onto their gallery.</li></ul> | 
| 10. | As a user, I wish for the app to include possible art events throughout the city to encourage community building, enhance exploration further and view even more artworks. | Hard | <ul><li>In the “Explore” tab, users can filter for events.</li><li>Users will be able to scroll through events throughout the city that are nearby to their location and can attend them in person.</li></ul> | 


## Activity Diagrams

**Activity Diagram 1 - Focus is on User Stories 1, 2, 3**
![Activity Diagram 1](https://github.com/software-students-fall2023/1-specification-exercise-artwork/assets/32769394/a5609bd8-3e3d-4621-aed5-f9c87bde8819)


**Activity Diagram 2 - Focus is on User Stories 4, 5**
![Activity Diagram 2](https://github.com/software-students-fall2023/1-specification-exercise-artwork/assets/32769394/2145ff7a-d78e-48d3-a2b2-efbf2afa75a5)


**Activity Diagram 3 - Focus is on User Stories 1, 6**
![Activity Diagram 3](https://github.com/software-students-fall2023/1-specification-exercise-artwork/assets/32769394/cf44d0c4-f061-4bdf-a916-42953ecfe651)



## Wireframe Diagrams 

**Login Screen Wireframe:**


![Login_Wireframe](https://github.com/software-students-fall2023/1-specification-exercise-artwork/assets/32769394/3472e83f-cc3b-4e2d-9e00-190e14104c29)


**Explore Screen Wireframe:**


![Explore_Wireframe](https://github.com/software-students-fall2023/1-specification-exercise-artwork/assets/32769394/9d327ecc-b1f3-4d7d-85a5-7ef6f9ddd112)
![Filter_Dropdown_Wireframe](https://github.com/software-students-fall2023/1-specification-exercise-artwork/assets/32769394/b871bef4-c5a9-4cad-baa8-312601cc1c13)


**Capture Screen Wireframe with Create Mode On:**


![Capture_Artist_Wireframe](https://github.com/software-students-fall2023/1-specification-exercise-artwork/assets/32769394/521fd973-7937-48f2-874c-511e357bef6f)


**Capture Screen Wireframe with User Mode On:**


![Capture_User_Wireframe](https://github.com/software-students-fall2023/1-specification-exercise-artwork/assets/32769394/62f28f4b-6c4f-49bf-bcf6-36d5db409947)
![Artoverlay_Wireframe](https://github.com/software-students-fall2023/1-specification-exercise-artwork/assets/32769394/8357a805-0c36-4f69-ac61-186e5ed7ba13)


**Profile Screen Wireframe:**


![Profile_Wireframe](https://github.com/software-students-fall2023/1-specification-exercise-artwork/assets/32769394/de588ac7-c822-438a-a845-73225033427e)


**Gallery Screen Wireframe:**


![Gallery_Wireframe](https://github.com/software-students-fall2023/1-specification-exercise-artwork/assets/32769394/ddd34682-b013-4adb-95d3-091e0114944a)


**Artist Profile Screen Wireframe:**


![ArtistProfile_Wireframe](https://github.com/software-students-fall2023/1-specification-exercise-artwork/assets/32769394/cc2bc51f-ef07-4d9b-965b-59f1af55e933)


**Settings Screen Wireframe:**

![Settings_Wireframe](https://github.com/software-students-fall2023/1-specification-exercise-artwork/assets/32769394/ff911c8e-8fa4-4535-b4d0-4ab0cfe97be3)
