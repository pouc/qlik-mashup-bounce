# qlik-mashup-bounce

A small mashup that enables you to bounce back from Qlik Sense to another URL

This is particularly usefull when you need to authenticate using an unknown authentication module that opens a session, and that you then need to go back to another url that uses the Qlik Sense APIs

# how to use this

[deploy](http://help.qlik.com/sense/2.0/en-us/developer/#../Subsystems/Mashups/Content/Howtos/mashups-deploy-mashup.htm%3FTocPath%3DBuilding%2520mashups%7CGetting%2520started%2520building%2520mashups%7C_____3) as a standard mashup

redirect to bounce using ```<qlik sense host>/extensions/bounce/bounce.html?bounceUrl=<bounce URL>```

your user will be redirected to the bounce URL when authenticated!
