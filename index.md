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
    
    <!-- Optional JavaScript; choose one of the two! -->
    <script type='text/javascript' src='https://dellservices--ge4.sandbox.my.site.com/ESWMIAWPOC1715760511897/assets/js/bootstrap.min.js' ></script>
    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>

    <!-- Option 2: Separate Popper and Bootstrap JS -->
    <!--
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js" integrity="sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.min.js" integrity="sha384-cVKIPhGWiC2Al4u+LWgxfKTRIcfu0JTxR+EQDz/bgldoEyl4H0zUF0QKbrJ0EcQF" crossorigin="anonymous"></script>
    -->

    
  </body>
</html>
