
CONFIGURATION AT JEKINS SIDE 
                        ....
                         1.  Create a Free Style Project .
                         2.  selet Project and Confure >>>  Source Code Management >>>> git>>>>> paste github Repo url 
                          .....if repo is public no need to add Credention 
                          3. In Build Triggers >>> GitHub hook trigger for GITScm polling
                          4. apply and save 
 
 
 CONFIGURATION AT GITHUB SIDE                         
                          
                          1. SELETC REPO >>>> SETTING >>>>>WEBHOOK>>>>>> Add web hook
                          2. Payload URL ( https://300f-103-47-44-2.in.ngrok.io/github-webhook/) >>>>>Content type ( appliaction/json )>>>>Secret (blank )>>>Which events would you like to trigger this webhook?
                             ( push ebent )>>> than Add webhook 


