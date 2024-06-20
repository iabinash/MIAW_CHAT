<html>
<body>
   
    <script type='text/javascript'>
        function initEmbeddedMessaging() {
            console.log('initEmbeddedMessaging clicked')
            
            try {
                embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US' add -pt_BR
    
                embeddedservice_bootstrap.init(
                    '00D8B0000004cZ5',
                    'MIAWPOC',
                    'https://dellservices--ge4.sandbox.my.site.com/ESWMIAWPOC1715760511897',
                    {
                        scrt2URL: 'https://dellservices--ge4.sandbox.my.salesforce-scrt.com'
                    }
                );
            } catch (err) {
                console.error('Error loading Embedded Messaging: ', err);
            }
        };
             var sIssue = "Account_Access";
             var sServiceTag = "DLPV0F3";
              var sQueueNameFromeSupport = "00G2R0000048staUAA";
        window.addEventListener("onEmbeddedMessagingReady", e => {
            console.log("onEmbeddedMessagingReady event triggered");
    
            embeddedservice_bootstrap.prechatAPI.setHiddenPrechatFields({
                "IssueType" : sIssue,
                "Service_Tag" : sServiceTag,
                "QueueNameFromeSupport" : sQueueNameFromeSupport
                
            });
        });
    
    </script>
</body>
</html>

