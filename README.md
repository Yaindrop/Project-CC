# Project CC
Inspired by [The Connectable Manifesto][tcm], Project CC is an ecosystem of connectable services aiming at providing better user experiences for individual users. 

Project CC consists of the Connectable Center and a series of compatible connectable projects.

## Connectable Center
Connectable Center (CC) is a front-end container for connectable services powered by [React Native][rn]. It hosts the UI for all connected services and provides easy UI customization for user. 

Connectable Service that is compatible with the Project CC should provide specific APIs designed for CC, which include a list of all available APIs, an implementation of the default UI, and the ability to upload customized UI. 

CC can be deployed as a mobile app or a website. User can interact with their connectable services inside CC and customize their UI as they wish. CC will provide a simple building-block-style UI designer and also a choice for source code editing. 

## First-Party Projects
The project CC comes along with several first-party projects before more developers join this community.
### Connector
Connector is a router for connectable projects. It saves user from connecting to all different servers directly from their CC, and it helps monitoring the services' status.

Connector needs to be deployed on an public server. It connects with other connectable services and the Connectable Center, relaying transmissions between them. 

CC users can connects only with the Connector and save all their connections on it. This is particularly helpful when the user wants to use CC from multiple devices and in different network environments. 
### Keeper
Keeper is a basic personal file storage service. It is projected that Keeper will support multiple file transmission protocols including http, websocket, ftp, and nfs.
### Exchanger
Exchanger is an interpersonal information exchange service. It provides secure chatting and file sharing functions and can also serve as a decentralized social network.
## Start Guide
UNDER CONSTRUCTION

## Document
UNDER CONSTRUCTION

[tcm]: <https://connectable.rarea.net/>
[rn]: <https://facebook.github.io/react-native/>
