# activitypub
The Reference ActivityPub Implementation based on Web 4.0 


# The new Unified activitypub protocol version 1.2.1

sends ECMASCript Module specifiers array. and ECMAScript export object array , entrypoint all in a array
```js
[
 [], // importSpecifier Array
 [], // exportSpecifier Array matching the import array in order
 [importSpecifierIdx, 'exportProperty'], // suggest entrypoint
];
```

this allows us to send whole applications as also news and any other information in one or multiple formats fully auditable so that it is secure.


unlike the old spec we use webrtc so this works out of the box with the Web 4.0 Project and builds the main bridge for the activity pub protocol that is adaptable so you can consume anything from anywhere this even disables cross origin checks without a extension or anything to give you the best expirence. 

hope you enjoy it as this is the result of over 20 years of research from me full time! none paid only because i want it to happen.
