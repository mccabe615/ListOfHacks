# ListOfHacks
List of web app based hacks

#### Apache Bugzilla Hack
##### XSS & Credential brute force
##### Description

On April 5th, the attackers via a compromised Slicehost server opened a new issue, INFRA-2591. This issue contained the following text:

ive got this error while browsing some projects in jira http://tinyurl.com/XXXXXXXXX [obscured]
Tinyurl is a URL redirection and shortening tool. This specific URL redirected back to the Apache instance of JIRA, at a special URL containing a cross site scripting (XSS) attack. The attack was crafted to steal the session cookie from the user logged-in to JIRA. When this issue was opened against the Infrastructure team, several of our administators clicked on the link. This compromised their sessions, including their JIRA administrator rights.

##### More Info
https://blogs.apache.org/infra/entry/apache_org_04_09_2010

#### Imgur 8Chan DDoS
##### Malicious file upload
##### Description:

Imgur, the photo-sharing website best known for adorable cat GIFs and newly minted memes, has been exploited in a traffic-based attack on the popular imageboards 4chan and 8chan.

The distributed denial-of-service (DDoS) attack, first publicized by an Imgur employee on Reddit, used Imgur links to send huge amounts of traffic to 4chan and 8chan. Whenever a user on Reddit's 4chan subreddit clicked on an Imgur link, the link opened a hidden window off of the user’s screen and loads hundreds of image files located on the 4chan/8chan servers, effectively destabilizing the sites and slowing down legitimate traffic to them.

##### More Info
http://www.dailydot.com/technology/imgur-4chan-8chan-exploit/
