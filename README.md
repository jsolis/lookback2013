Look back 2013
--------------

**hotel prototype**

 - Predicted the failure of the prototype based on the project management style being enforced

**new stack**

 - Applied all the lessons learned from prototyping into architecting 
 - List item
 - Automated developer setup
 - Overhauled and modernized developer workflow
 - Collaborated with Engineering to retool the deployment process to meet the needs of a modern web app
 - All these contribute to a countless amount of time saved for developers which will help put features out quicker which makes the company more money

**fly**

 - Worked with the fly team both as a technology consultant and later as an app developer using the tools from both the new stack and the fly app as an end user

**hiring help**

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
