NFL Game Stats

Converts the NFL's XML game stats feed into a JSON data structure that is easy to work with.

How to use
Download and add nfl_game_stats-2.0.1.js and day_hours.js to your html.
 <script type="text/javascript" src="day_hours.js"></script>
 <script type="text/javascript" src="nfl_game_stats.js"></script>
Make a request* to http://www.nfl.com/liveupdate/scorestrip/ss.xml during the regular season or http://www.nfl.com/liveupdate/scorestrip/postseason/ss.xml during the post season.
Call getWeekGameStats.
 var weekGameStats = getWeekGameStats(this.responseText);
Use the returned JSON getWeekGameStats as you please.
*A cross-domain request must be made.
