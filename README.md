zandimna-polytime

Usage:
python polytime <interval name 1> <starting time 1> [interval name 2] [starting time 2] ...

All times should be expressed in terms of minutes past midnight UTC.
Example:
Local time in Japan is UTC+9
Wake time 1 is 04:50 local time, which is 19:50 UTC, which is 19*60+50=1190 minutes past 
midnight UTC.
Wake time 2 is 08:40 LT, 23:40 UTC, 1420 minutes past midnight UTC
The period following wake time 1 is Alpha and the period following wake time 2 is Beta

The example command will be:
python polytime Alpha 1190 Beta 1420

The numbers following names does not have to be in ascending order
