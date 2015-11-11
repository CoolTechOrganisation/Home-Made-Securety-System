# Home-Made-Securety-System

Pleas Install ssmtp and mailutils on your raspberrypi to .
Just type" sudo apt-get install ssmtp mailutils" and hit Enter.
After the Installation pleas go in the root direction and the do "cd /ect/ssmt/"
After taht do nano ssmtp.conf after nano opens go to mailhub= and replace mail with  the smtp
for your email address . After the Server (ex.smtp.gmail.com)type : and the Port of the 
smtp Server .
After Doing that add the Line AuthUser=Youremailadress under hostname.
Under taht do AuthPass=Your Password . 
Unser that to UseSTARTTLS=YES.
Under that do UseTLS=YES
ssmt.conf is Not Incriptid ! 
