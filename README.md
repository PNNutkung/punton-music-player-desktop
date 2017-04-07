# Punton Music Player Desktop
[![CircleCI](https://circleci.com/gh/PNNutkung/punton-music-player-desktop.svg?style=svg)](https://circleci.com/gh/PNNutkung/punton-music-player-desktop)
[![license](https://img.shields.io/github/license/mashape/apistatus.svg)](https://opensource.org/licenses/MIT)

## Abstraction
Normally, songs are suggested based on information of previous songs such as genre of the songs,  and artists that users have listened to as well as their previous purchases. We have decided to try a new implementation of song suggestion which is by applying machine learning techniques on wave signal of songs which we believe to be the most relevant information of songs to be suggested. By doing so will allow us to form wave signal patterns that will be used to suggest songs that have similar patterns to user.

## Background and motivation
Nowadays, there are various genres of music and different people have their own taste of music. Music also has been used differently in order to create atmosphere for users while they are listening to songs. From many researches, music could be apply to many other things such as using it to abbreviate the disease or ease the pain or sorrow for any patiences. These prove the importance of the music in our life style. There is a quote from Plato state that “Music is a moral law. It gives soul to the universe, wings to the mind, flight to the imagination, and charm and gaiety to life and to everything. “ ㅡ Plato, 428 BC.
While there are many music classifiers that group music by the genre of the music or the category of music, these conditions might not be able to satisfy the user’s need in their daily lives. Rather than each individual person has to spend a lot of time each day surfing for songs they desire to listen to which wastes a lot of invaluable time. As a result, we have come up with the method of suggesting the music to users that don’t require them to surf which is by providing suggested lists of music that they prefer.

## Scope
The scope of this project is as follows:
1. Unsupervised prediction model is compared against the k-nearest neighbor algorithm.
2. Considered data source are sound wave of songs.
3. Application has user interface with good user experience which makes users do not have to learn how to use.
4. Cross-platform application serves different operating system users.
5. Machine learning technique separates group of song when users import new songs to application.
