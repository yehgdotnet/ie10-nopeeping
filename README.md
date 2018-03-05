# ie10-nopeeping

Approach to prevent Microsoft Internet Explorer 10 password reveal button (aka eye symbol icon) from revealing clear-text password.

There has been a privacy concern on Microsoft Internet Explorer 10 - Reveal Password button feature (aka eye symbol icon). IE users can disable this feature via group policy. Web developers can disable it via IE browser specific "::-ms-reveal" pseudo element.

From developer's perspective, the first solution is out of reach as user's group policy settings cannot be controlled. Unfortunately, the second option works only in IE 10 document mode. It will not work if a web site is rendered as a lower version of IE for compatibility reason (i.e. 7, 8 , 9).

With this in mind, we developed a simple JavaScript solution that can seamlessly mask user password characters in password input field. This solution allows developer to retrieve the password via a JavaScript variable call.

Demos:
http://yehg.net/lab/pr0js/training/view/misc/IE-10_NoPeeping/

Try yourself: 
http://yehg.net/lab/pr0js/misc/ie10-nopeeping/CSS/IE-10/

http://yehg.net/lab/pr0js/misc/ie10-nopeeping/JavaScript/IE-10/