# WP2-Social-Media-Presence
Development stage of application for WP2 purposes.<br/><br/>

The application is used to scrap all the links related to social media from websites that are put in:
url.txt
file that should have the list of URLs in the following format:<br/>
maslankowski.pl<br/>
http://stat.gov.pl<br/>
www.ug.edu.pl

The output of the application are two files:
<b>wp2_social.csv</b>
and
<b>wp2_social_YYYYMMDDHHMMSSnnnnnnn.json</b>

The file <b>wp2_social.csv</b> is updated with its content. 

The json file is created every time of the application running.

To start using the software, you should download Python source file and execute like this:
<b>python3 WP2_SocialMediaPresence_Dev.py</b>