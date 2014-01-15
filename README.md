Look back 2013
--------------

**hotel prototype**

 - Some would say p2 was a failure, but you only can learn from things failing in order to get better. I look at p2 as a learning success. We fail we try again. This is what technology is built on.
 - Like a famous quote I always refer to "Your most unhappy customers are your greatest source of learning"

**new stack**

 - Applied all the lessons learned from prototyping into architecting the new stack
 - Saved 3 days of developer time by automating the developer set up. New hired developers as well as any new machine set ups, now come in and can start working right away and adding contribution to the organization. 
 - By introducing technologies such as Git, Node.js, and grunt we are now able to get tech team to by pass most development challenges they would encounter on a daily basis.
 - Collaborated with Engineering to retool the deployment process to meet the needs of a modern web app
 

**fly**

 - Getting the product on the new stack gave us the ability to move through air under control.
 - Consulted with the fly team in choosing the tools used to forge the fly app such as Grunt and almond.
 - Developing features on the fly app gave me a chance to use the new stack end to end, thus staying motivated to keep it at a high quality.

**recruiting**

 - Screened and onboarded 10 successful engineers to the company for contribution to the Customer Conversion Team. The newly hired engineers are a part of desktop and  mobile teams.

**GeekTo5k**

 - Since we have open space and the flexibility to go to the NYC office, this has given me the ability to collaborate with the mobile team, in order for us to show off Google's new Chrome App technology which sparked a discussion about how this new platform could be used to benefit Priceline.com such has making dashboard available while offline

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
