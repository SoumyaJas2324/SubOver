# SubOver


## https://github.com/Ice3man543/SubOver

***Subover is a Hostile Subdomain Takeover tool originally written in python but rewritten from scratch in Golang. Since it's redesign, it has been aimed with speed and efficiency in mind. Till date, SubOver detects 30+ services which is much more than any other tool out there. The tool uses Golang concurrency and hence is very fast. It can easily detect and report potential subdomain takeovers that exist. The list of potentially hijackable services is very comprehensive and it is what makes this tool so powerful.


### Installing

***You need to have Golang installed on your machine. There are no additional requirements for this tool.

 >> go get github.com/Ice3man543/SubOver

    NOTE - Do not change the location of providers.json file. Or the tool will not work.

### Usage

>> ./SubOver -l subdomains.txt

    -l List of Subdomains
    -a Check all hosts regardless of CNAME (Time Consuming and prone to fp's)
    -t Number of concurrent threads. (Default 10)
    -v Show verbose output (Default False)
    -https Force HTTPS Connection (Default HTTP)
    -timeout Set custom timeout (Default 10)
    -h Show help message

## Currently Checked Services

>> Github, Heroku, Unbounce, Tumblr, Shopify, Instapage, Desk, Tictail, Campaignmonitor, Cargocollective, Statuspage, Amazonaws, Cloudfront, Bitbucket, Smartling, Acquia, Fastly, Pantheon, Zendesk, Uservoice, Ghost, Freshdesk, Pingdom, Tilda, Wordpress, Teamwork, Helpjuice, Helpscout, Cargo, Feedpress, Surge, Surveygizmo, Mashery, Intercom, Webflow, Kajabi, Thinkific, Tave, Wishpond, Aftership, Aha, Brightcove, Bigcartel, Activecompaign, Compaignmonitor, Acquia, Proposify, Simplebooklet, Getresponse, Vend, Jetbrains, Azure..

### FAQ

***Q: What should my wordlist look like?

A: Your wordlist should include a list of subdomains you're checking and should look something like:

***backend.example.com
  something.someone.com
  apo-setup.fxc.something.com


### Credits
   
    ## https://0xpatrik.com ------Subdomain Takeover Blogs
    ## subjack : Hostile Subdomain Takeover Tool Written In GO
    ## Subdomain Takeover Scanner by 0x94
    ## Anshumanbh : tko-subs
    ## EdOverflow : can-i-take-over-xyz
    ## https://0xpatrik.com/subdomain-takeover-ns/
    ## https://0xpatrik.com/subdomain-takeover-basics/
    ## https://0xpatrik.com/takeover-proofs/
    ## https://blog.sweepatic.com/subdomain-takeover-principles/
    ## https://0xpatrik.com/subdomain-takeover/
    ## https://0xpatrik.com/subdomain-takeover-starbucks/
    ## https://medium.com/bugbountywriteup/how-i-bought-my-way-to-subdomain-takeover-on-tokopedia-8c6697c85b4d
    ## https://medium.com/@friendly_/subdomain-takeover-awarded-200-8296f4abe1b0
    ##https://medium.com/bugbountywriteup/how-i-started-a-chain-of-subdomain-takeovers-and-hacked-100s-of-companies-770d8f84885e
