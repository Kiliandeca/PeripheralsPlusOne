# Time Sensor

The Time Sensor is a simple peripheral that returns the system time.

##Functions

Function | Returns | Description
-|-|-
getDate() | *table* date | Returns a table containing the year, month, day, hour, minute, second.
getTime() | *number* miliseconds | Return a Unix timestamp in milliseconds.
startTimer() | *nil* | Starts a time profiler that can then be stopped to get the elapsed time.
stopTimer() | *number* milliseconds | Returns the time elapsed since starting the timer.
