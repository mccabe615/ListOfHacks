# ListOfHacks
List of web app based hacks


#### Name
##### Type
##### Description
##### Technique Details

#### Apache Bugzilla Hack
##### XSS & Credential brute force
##### Description

On April 5th, the attackers via a compromised Slicehost server opened a new issue, INFRA-2591. This issue contained the following text:

ive got this error while browsing some projects in jira http://tinyurl.com/XXXXXXXXX [obscured]
Tinyurl is a URL redirection and shortening tool. This specific URL redirected back to the Apache instance of JIRA, at a special URL containing a cross site scripting (XSS) attack. The attack was crafted to steal the session cookie from the user logged-in to JIRA. When this issue was opened against the Infrastructure team, several of our administators clicked on the link. This compromised their sessions, including their JIRA administrator rights.

##### More Info
https://blogs.apache.org/infra/entry/apache_org_04_09_2010

