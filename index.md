<html>
  <body>
     <script type='text/javascript'>
            function initEmbeddedMessaging() {
                           try {
                           embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'
    
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
    </script>
    <script type='text/javascript' src='https://dellservices--ge4.sandbox.my.site.com/ESWMIAWPOC1715760511897/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
    
  </body>
</html>
