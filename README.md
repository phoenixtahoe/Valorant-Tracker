# Valorant Stat Tracker

# App Features
> *The goal of this app is to give simple analytics based on the game Valorant, aswell as presenting it on a simple and clean interface, while also letting a game enthusiast's choose a variety of ways to check certian statistics*

# The API

	The base url is https://api.henrikdev.xyz
	
	The documention for the API is available under 
	
	https://docs.henrikdev.xyz/valorant.html

## The Data

Using a Third-Party API I can get data based on user, match, etc...

	  "puuid": "322751e8-0008-52e2-8afe-025ae2ec5dff",
	  "name": "stole",
	  "tag": "1v9",
	  "team": "Red",
	  "level": 95,
	  "character": "Yoru",
	  "currenttier": 0,
	  "currenttier_patched": "Unrated",
	  "player_card": "fc209787-414b-10d0dcac-04832fc2c654",
	  "player_title": "2111510b-4dbfe9b6-9959-60b8fbce5b2",
	  "assets": {
	    "card": {
	      "small": "",
	      "large": "",
	      "wide": ""
	    },
	    "agent": {
	      "small": "",
	      "bust": "",
	      "full": "",
	      "killfeed": ""
	    }
	  },
	  "stats": {
	    "score": 2716,
	    "kills": 8,
	    "deaths": 16,
	    "assists": 4
	  },
	  "ability_casts": {
	    "c_cast": 4,
	    "q_cast": 28,
	    "e_cast": 17,
	    "x_cast": 4
	  },
	  "damage_made": 1975,
	  "damage_received": 0
    

## **Schema Design**

`2 Tables`

`Users, Watchlist `

`User stores id, username, password, email`

`Watchlist reference a User and an array of Valorant User id's`

## User flow

> User's will land at the homepage with options to either check the new's or patch notes, or check the leaderboard based on region, aswell as giving user the ablitly to directly search for a player to check stats like rank, match history, etc...

> User's will be able to add their Valorant players to a watch list
