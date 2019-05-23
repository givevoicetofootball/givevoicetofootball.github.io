---
layout: page
title: APIs Documentation
permalink: /api/
nav_order: 3
---

## API Documentation

**FAPIs**: FIFA makes publicly available a set of APIs containing data from past competitions.
A detailed description of all the endpoints can be found at the following URL:  <https://givevoicetofootball.fifa.com/ApiFdcpSwagger/>

Below some example of calls for reference, where API_ROOT must be replaced with <https://givevoicetofootball.fifa.com/api/v1>

To get ALL seasons for a FIFA Tournament (for example FU20 Women's World Cup): <br/>
[API_ROOT/seasons/search?name=FIFA%20U-20%20Women%20World%20Cup](https://givevoicetofootball.fifa.com/api/v1/seasons/search?name=FIFA%20U-20%20Women%20World%20Cup)

To get the details of a specific season: <br/>
[API_ROOT/seasons/278491](https://givevoicetofootball.fifa.com/api/v1/seasons/278491)

To get ALL Stages of the season: <br/>
[API_ROOT/stages?idSeason=278491&idCompetition=108](https://givevoicetofootball.fifa.com/api/v1/stages?idSeason=278491&idCompetition=108)

To get all the Squad of the season: <br/>
[API_ROOT/teams/squads/all/108/278491](https://givevoicetofootball.fifa.com/api/v1/teams/squads/all/108/278491)

To retrieve all players: <br/>
[API_ROOT/players/seasons/278491?count=1000](https://givevoicetofootball.fifa.com/api/v1/players/seasons/278491?count=1000)

To retrieve all coaches: <br/>
[API_ROOT/coaches/season/278491](https://givevoicetofootball.fifa.com/api/v1/coaches/season/278491)

To get ALL matches: <br/>
[API_ROOT/calendar/matches?idSeason=278491&idCompetition=108&count=100](https://givevoicetofootball.fifa.com/api/v1/calendar/matches?idSeason=278491&idCompetition=108&count=100)

To get matches for a specific stage: <br/>
[API_ROOT/calendar/matches?idSeason=278491&idCompetition=108&idStage=278493](https://givevoicetofootball.fifa.com/api/v1/calendar/matches?idSeason=278491&idCompetition=108&idStage=278493)

To get the standings for a Stage: <br/>
[API_ROOT/calendar/108/278491/278493/Standing](https://givevoicetofootball.fifa.com/api/v1/calendar/108/278491/278493/Standing)

To get the standings for a specific Group: <br/>
[API_ROOT/calendar/108/278491/278493/Standing?idGroup=278497](https://givevoicetofootball.fifa.com/api/v1/calendar/108/278491/278493/Standing?idGroup=278497)

To get the line-ups of a Match: <br/>
[API_ROOT/live/football/108/278491/278493/300424860?language=en-GB](https://givevoicetofootball.fifa.com/api/v1/live/football/108/278491/278493/300424860?language=en-GB)

To get the timeline (live events) of a Match: <br/>
[API_ROOT/timelines/108/278491/278493/300424860?language=en-GB](https://givevoicetofootball.fifa.com/api/v1/timelines/108/278491/278493/300424860?language=en-GB)

To get the Season stats: <br/>
[API_ROOT/topseasonplayerstatistics/season/278491/topscorers](https://givevoicetofootball.fifa.com/api/v1/topseasonplayerstatistics/season/278491/topscorers)

[API_ROOT/topseasonteamstatistics/season/278491/topscorers](https://givevoicetofootball.fifa.com/api/v1/topseasonteamstatistics/season/278491/topscorers)

To get Team or Player stats: <br/>
[API_ROOT/seasonstatistics/season/278491/team/1888591](https://givevoicetofootball.fifa.com/api/v1/seasonstatistics/season/278491/team/1888591)

[API_ROOT/seasonstatistics/season/278491/team/1888591/players](https://givevoicetofootball.fifa.com/api/v1/seasonstatistics/season/278491/team/1888591/players)
