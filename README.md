Original App Design Project - README Template
===

# Grab-a-Goalie

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
An app that helps soccer players find goalies to play or practice with, and vice versa.

### App Evaluation
[Evaluation of your app across the following attributes]
- **Category:** Matching/Social
- **Mobile:** Easy to communicate with other users on the go, camera/maps sdk features for increased ease of use.
- **Story:** Allows soccer players to more efficiently meet up and practice together
- **Market:** Soccer players in general
- **Habit:** Users can chat with other users to make plans for future outings, users can create a network of players they've played with.
- **Scope:** The bare bones design of the app is a basic matching app with a messenger feature. Lots of additions can make the scope more complex, like adding a friends list feature or adding more advanced matching support, like for other positions, or even other sports.

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* Can sign up on the app as either a goalie or a player
* Users can add a short bio about themselves
* Can match with other users
* Users can view the profiles of other users
* User information is stored in a database
* Can use the camera to add a user profile photo
* Can access google maps from the app
* Can communicate with other users in some way


**Optional Nice-to-have Stories**

* App uses location data to match users who are close together
* Users can select more varied positions
* Users can friend one another
* The messaging system is complex, allows users to message their friends
* Users can add additional information to their bio that allows for advanced matching, such as playstyle and teammate playstyle preferences.
* Gale shapley for matching
* Can uses google maps sdk to share marker location with other users


### 2. Screen Archetypes

* Login/Signup Screen
   * User can login to their account or create a new account
* Profile Screen
   * User can add or update a short bio about themselves
   * Users can view match requests or messages
* Search screen
    * User can view the profiles of other users
* Detailed view
    * User can see more detailed info about a specific user
    * User can send match request or messages

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Login Screen
* Profile Screen
* Seach Screen

**Flow Navigation** (Screen to Screen)

* Login
   * Profile
* Profile
   * Search
 * Search
     * Detail view
     * back to profile
* Detail view
    * back to search

## Wireframes
[Add picture of your hand sketched wireframes in this section]
<img src="YOUR_WIREFRAME_IMAGE_URL" width=600>

### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype

## Schema 
[This section will be completed in Unit 9]
### Models
[Add table of models]
### Networking
- [Add list of network requests by screen ]
- [Create basic snippets for each Parse network request]
- [OPTIONAL: List endpoints if using existing API such as Yelp]
