# Soccer_Database.sql
Soccer Database SQL Scripts:
This repository contains SQL scripts to create and query a comprehensive soccer database. The database includes tables for countries, cities, venues, teams, players, referees, matches, and various match-related details.



**Schema Overview:**
soccer_country: Stores country details.


soccer_city: Stores city details linked to countries.
soccer_venue: Stores venue details linked to cities.
soccer_team: Stores team details linked to countries.
playing_position: Stores player positions.
player_mast: Stores player details linked to teams and positions.
referee_mast: Stores referee details linked to countries.
match_mast: Stores match details linked to venues, referees, and players.
coach_mast: Stores coach details.
asst_referee_mast: Stores assistant referee details linked to countries.
match_details: Stores details of matches played by each team.
goal_details: Stores details of goals scored in matches.
penalty_shootout: Stores penalty shootout details.
player_booked: Stores details of players booked during matches.
player_in_out: Stores details of player substitutions during matches.
match_captain: Stores details of match captains.
team_coaches: Stores details of team coaches.
penalty_gk: Stores details of goalkeepers during penalty shootouts.
