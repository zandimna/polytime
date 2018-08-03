<h1>zandimna-polytime</h1>

Usage:
<code>python polytime <interval name 1> <starting time 1> [interval name 2] [starting time 2] ...</code>

All times should be expressed in terms of minutes past midnight UTC.
<br>
Example:
Local time in Japan is UTC+9
<br>
Wake time 1 is 04:50 local time, which is 19:50 UTC, which is 19\*60+50=1190 minutes past 
midnight UTC.
<br>
Wake time 2 is 08:40 LT, 23:40 UTC, 1420 minutes past midnight UTC
<br>
The period following wake time 1 is Alpha and the period following wake time 2 is Beta
<br>
The example command will be:
<code>./polytime Alpha 1190 Beta 1420</code>
<br>
The numbers following names does not have to be in ascending order
