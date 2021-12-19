Instructions


Add the sample web log data to Kibana.


Answer the following questions:


In the last 7 days, how many unique visitors were located in India?
252

In the last 24 hours, of the visitors from China, how many were using Mac OSX?
19.05%

In the last 2 days, what percentage of visitors received 404 errors? How about 503 errors?
404 -  < 1%, 503 - < 1%

In the last 7 days, what country produced the majority of the traffic on the website?
US

Of the traffic that's coming from that country, what time of day had the highest amount of activity?
Between 10am and 12pm

List all the types of downloaded files that have been identified for the last 7 days, along with a short description of each file type (use Google if you aren't sure about a particular file type).

gz = A GZ file is an archive file compressed by the standard GNU zip (gzip) compression algorithm.
css = CSS (Cascading Style Sheets) are files that describe how HTML elements are displayed on the screen, paper, etc.
zip = .ZIP files are archives that store multiple files.
deb = A DEB file is a standard Unix archive that contains two bzipped or gzipped archives, one for the installer control information and another for the actual installable data.
rpm = An RPM file is an installation package originally developed for the Red Hat Linux operating system, but now used by many other Linux distributions as well. RPM files are commonly used for installing programs on Linux systems

Now that you have a feel for the data, Let's dive a bit deeper. Look at the chart that shows Unique Visitors Vs. Average Bytes.

Locate the time frame in the last 7 days with the most amount of bytes (activity).
2021-12-18 20:36 , 1 visitor and  bytes of 10.8KB


In your own words, is there anything that seems potentially strange about this activity?
1 visitor on 2021-12-18 downloaded a zip file of 10.8KB
The utilization by 1 user seems high compared to the other activities.

Filter the data by this event.

What is the timestamp for this event?
Dec 18, 2021 @ 19:00:00.000
What kind of file was downloaded?
zip
From what country did this activity originate?
Brazil
What HTTP response codes were encountered by this visitor?
200


Switch to the Kibana Discover page to see more details about this activity.

What is the source IP address of this activity?
17.111.163.53
What are the geo coordinates of this activity?
"lat": 42.59157139, "lon": -114.7967178 
What OS was the source machine running?
win 7
What is the full URL that was accessed?
GET /kibana/kibana-6.3.2-windows-x86_64.zip HTTP/1.1
From what website did the visitor's traffic originate?
http://twitter.com/success/mark-kelly


Finish your investigation with a short overview of your insights.

What do you think the user was doing?
Downloading kibana-6.3.2-windows-x86_64.zip
Was the file they downloaded malicious? If not, what is the file used for?
The file is not mailicious and it was used for installing kibana
Is there anything that seems suspicious about this activity?
It seems no suspicious activity was detected.
Is any of the traffic you inspected potentially outside of compliance guidlines?
I assume kibana does all the inspections inside of compliance guidelines.