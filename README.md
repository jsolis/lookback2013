Look back 2013
--------------

**hotel prototype**

 - Predicted the failure of the prototype based on the project management style being enforced

**new stack**

 - Applied all the lessons learned from prototyping into architecting the new stack
 - Automated developer setup
 - Overhauled and modernized developer workflow
 - Collaborated with Engineering to retool the deployment process to meet the needs of a modern web app
 - All these efforts contribute to a countless amount of time saved for developers, makes them more productive, and contributes to our recruiting efforts

**fly**

 - Worked with the fly team as a technology consultant helping to choose and tweak the tools used to forge the app such as Grunt and almond
 - Worked on the fly team as an app developer giving me the chance to eat my own cooking

**recruiting**

 - Interviewed a number of developers which were hired and started contributing meaningfully to our products

**GeekTo5k**

 - Collaborated with the mobile team to do a joint demonstration during GUTS which showed off Google's new Chrome App technology which sparked a discussion about how this new platform could be used to benefit Priceline.com such has making dashboard available while offline

        if (chrome.pushMessaging) {
        // Listens for push messages in the window
        chrome.pushMessaging.onMessage.addListener(function(message) {
                var payload = JSON.parse(message.payload);
                self.addNewStatus({activity:payload.activity});
        });
    
        // get last known activity for this user
        chrome.storage.sync.get('activity', function(items) {
                if (items.activity) {
                        self.addNewStatus({activity:items.activity});
                }
        });
    }

[GeekTo5K GitHub repo][1]

What were my competencies for 2012-2013?


  [1]: https://github.com/jsolis/GeekTo5K
