#  Music streaming service API

## Summary 
* This is the README file for the Music Streaming Service API. The API allows two types of users, Normal and Admin, to interact with the system. The Admin user has the ability to perform CRUD (Create, Read, Update, Delete) operations on songs, while the Normal user can add songs to their playlist and perform CRUD operations on their playlist.

## Feature
* Two types of users: Normal and Admin
* CRUD operations for Admin user on songs
* Playlist management for Normal user (addition, retrieval, update, and deletion)
* Validation for input data
* Controller, service, and repository layers for proper organization and separation of concerns

## FrameWork and Language Used
* SpringBoot 
* Java

## DataBase Used
MySql

## Controller
* UserController 
* StatusController 
* SongController

## Service
* UserService 
* StatusService 
* SongService

## Model
* User 
* Status 
* Song

## Repository
* UserRepository 
* StatusRepository 
* SongRepository
