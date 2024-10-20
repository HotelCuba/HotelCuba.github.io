---
layout: post
title:  "Unreal Engine Theory"
published: true
categories: [unreal]
---

# Unreal Engine Theory

Game Instance: there is one per game, valid though levels, to store player's health etc.
Game Mode: there is one per level and valid only for a level. Only the server can access to game mode in multi player game. If there is no override game mode, the default game mode set on project settings will be adapted.
Game State: similar with Game Mode, but server and client both can access to game state.
Player State: like Game State, but there is one per player per level. to store player name, high score, etc.
Controller: like brain that drives player character or pawn, vpossess or unpossess different characters or pawns
