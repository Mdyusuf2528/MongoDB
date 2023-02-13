# Prerequisite:

I have a satellite link.

It provides position information for each and every second.

I want to keep that data for 24 hours and add a 5-second delay after each data capture.

# Method:

1) I obtained the data from the satellite link by using urllib.request.
2) Since the data is provided in byte format, we must modify the datatype to dict format.
3) I used the json package to change the datatype into dict format.
4) I want to add a 5 second delay, therefore I utilised the time package to do that.
5) The while loop is used for additional stages.
