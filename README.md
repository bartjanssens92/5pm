
  This script is used to calculate when it's "5pm".
  It calculates the time that the user can leave after working the defined workinghours.
  This is done by using the time that the user first logged in.

  Options:
    --more | -m      : Show some more output.
    --quiet | -q     : Don't show any output, for running on startup
    --workhours | -w : Set the workhours, defaults to '08:30'
    --debug | -d     : Enable debug mode, aka echo some params
    --start | -s     : Don't use last to get the login time but the current time
