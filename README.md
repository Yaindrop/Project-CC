# Project CC
Inspired by [The Connectable Manifesto][tcm], Project CC defines an ecosystem of connectable services aimed at providing better user experiences for individual user. 

The ecosystem of Project CC is made up of the Connectable Center and a series of compatible connectable projects.

## Connectable Center
Connectable Center (CC) is a front-end container for connectable services powered by [React Native][rn], which hosts UI for different connected services and provides easy UI customization for user. 

Connectable Services that are compatible with the Project CC should provide specific APIs designed for CC, which include a listing of all available APIs, code for implementation of the default UI, and a function to upload customized UI. 

CC can be deployed as a mobile app or a website. Once a compatible service is connected, the stored UI design will be downloaded onto CC as ReactJS code, and then applied via hot-update.

User can interact with connected services inside CC and customize their UI as they wish. CC will provide a simple building-block style UI designer and a choice for source code editing as well. 

## First-Party Services
The Project CC comes along with several first-party services before more developers join this community.

### Organizer 
Organizer is a control panel for connectable services deployed on [Kubernetes][k8s]. 

Organizer helps individual user deploying and managing containerized connectable services on personal servers easily. 

### Connector
Connector is a router for connectable services. 

Connector saves user from connecting to all different servers directly from their CC. User can connects their CC only with Connector. and Connector will relay transmissions between the user and other connectable services. 

Connector also saves user's connection configurations. This is particularly helpful when the user wants to use CC on multiple devices and in different network environments. 

### Authenticator
Authenticator is a vault that keeps the credentials for other connectable services. 

With the credentials stored by Authenticator, user can use different connectable services directly without having to enter credentials individually. 

### Keeper
Keeper is a personal file storage service providing basic NAS functions. 

It is projected that Keeper will support multiple file transmission protocols including http, websocket, ftp, and nfs.

### Exchanger
Exchanger is an interpersonal information exchange service providing chatting and file sharing functions.

It is projected that Exchanger will also serve as a decentralized social network for multiple users. 

## Community Projects
UNDER CONSTRUCTION

## Quick Start Guide
UNDER CONSTRUCTION

## Document
UNDER CONSTRUCTION

[tcm]: <https://connectable.rarea.net/>
[rn]: <https://facebook.github.io/react-native/>
[k8s]: <https://kubernetes.io/>
