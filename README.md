# qlik-bounce

A small mashup that enables you to bounce back from Qlik Sense to another URL

This is particularly usefull when you need to authenticate using an unknown authentication module that opens a session, and that you then need to go back to another url that uses the Qlik Sense APIs

# how to use this

deploy as a standard mashup

redirect to bounce using ```<qlik sense host>/extensions/bounce/bounce.html?bounceUrl=<bounce URL>```

your user will be redirected to the bounce URL when authenticated!
