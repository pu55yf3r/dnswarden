# Notice

## Currently this project is no longer supported, for more info look at https://dnswarden.com .


#### Implemented blocking of 1st party trackers which uses CNAME's, more [information](https://github.com/uBlockOrigin/uBlock-issues/issues/780) can be found here about them. This is only applicable to Adblocking and Adult-Filter dns.


# dnswarden
#### Just a normal privacy oriented dns service with a ability to block ads , trackers and also provides uncensored dns! Servers are hosted in Germany



## Features

* Provides three types of dns 
  * **Pure uncensored dns** (Blocks nothings , more power for the user!)
  * **Adblocking dns** (Blocks ads , trackers and all the random crap on the internet.)
  * **Adult Filter dns** ( Blocks adult content, enforces force safe search for search engines and youtube. Also blocks ads,trackers and other malicious stuff)
  

    * Supports DNSCrypt , DNS over HTTPS and DNS over TLS.
    * DNSSEC and [QNAME minimization](https://tools.ietf.org/html/rfc7816) are enabled by default.
    * Supports other [non-icann TLD's](https://github.com/bhanupratapys/dnswarden/issues/7#issuecomment-548266343).
    * EDNS Client Subnet ([ECS](https://tools.ietf.org/html/rfc7871)) is disabled by default. Only supports [ECS](https://tools.ietf.org/html/rfc7871) depending upon the subdomain/path choice.
    * No query logging .
    * If your favourite website gets blocked/broken , **[report here!](https://github.com/dnswarden/blocklist)**    
    
    
 # Server information
 
* ## Adblocking DNS (DoT, DoH, DnsCryptV2)
  
  
  * ### DNS-over-TLS
     *  adblock-dot.dnswarden.com ( Supports both port **853** and **443**)
  
  * ### DNS-over-HTTPS: 
    *  https://doh.dnswarden.com/adblock
    *  https://ecs-doh.dnswarden.com/adblock-ecs (With [ECS](https://tools.ietf.org/html/rfc7871))
    
  * ### DnsCryptV2
      * IPv4
        
       * IPv6
         
         
      * IPv4 with ecs enabled.
        
       * IPv6 with ecs enabled.


   * ### Clear text dns
      
        * IPv4
          

       
        * IPv6
          

       
* ## Uncensored DNS (DoT, DoH, DnsCryptV2)
  
  
  * ### DNS-over-TLS
     *  uncensored-dot.dnswarden.com ( Supports both port **853** and **443**)
  
  * ### DNS-over-HTTPS: 
    *  https://doh.dnswarden.com/uncensored
    *  https://ecs-doh.dnswarden.com/uncensored-ecs (With [ECS](https://tools.ietf.org/html/rfc7871))
    
  * ### DnsCryptV2

      * IPv4
        
        
       * IPv6


      * IPv4 with ecs enabled.
        
        
       * IPv6 with ecs enabled.



   * ### Clear text dns
      
        * IPv4
          

       
        * IPv6
          

       
       
* ## Adult Filter DNS (DoT, DoH, DnsCryptV2)
  
  
  * ### DNS-over-TLS
     *  adult-filter-dot.dnswarden.com ( Supports both port **853** and **443**)
  
  * ### DNS-over-HTTPS: 
    *  https://doh.dnswarden.com/adult-filter
    *  https://ecs-doh.dnswarden.com/adult-filter-ecs (With [ECS](https://tools.ietf.org/html/rfc7871))
    
  * ### DnsCryptV2
      * IPv4
        
       * IPv6
       

      * IPv4 with ecs enabled.
        
       * IPv6 with ecs enabled.


   * ### Clear text dns
      
        * IPv4
          

       
        * IPv6
          


       
* ## Privacy policy and T&C
  * Use at your own risk. I will not be held responsible for any downtime of the servers , only on a "best effort" basis.
  * No query logging . Completely disabled query logs related to the DNS traffic.
  * Dns traffic will be forwarded to either [dns.watch](https://dns.watch) or datacenter's dns servers if any one of the backend resolver fails. 



* ### Health/Dns Query Rate Graph
    * [Live at](does not exist). The graph what you see here is equal to "Total number of queries received by servers" minus "Cache hits" , because each backend has its own resolver with cache enabled. So it is kinda hard to know the "Total numbers of queries received by the servers" without disabling the resolver cache on the backends.
    * [Uptimerobot](does not exist)
    
    
* ### Test domains to check whether the dns is correctly configured or not.

   * [While using uncensored dns](does not exist)
   * [While using adblock dns](does not exist)
   * [While using adult-filter dns](does not exist)
   * [To test whether you are using dnswarden or not](does not exist)


* ### Client software

    * Android
      * [Dnscrypt-proxy](https://github.com/DNSCrypt/dnscrypt-proxy), Supports dnscrypt and DoH. Also supports other os's.
      * [Nebulo](https://git.frostnerd.com/PublicAndroidApps/smokescreen#installation), Supports both DoT and DoH.
      * [PersonalDnsFilter](https://zenz-solutions.de/personaldnsfilter), Supports DoT , DoH and normal DNS.
      * [Intra](https://play.google.com/store/apps/details?id=app.intra), Supports only DoH.
      * By using Android Pie , Go to Setting -> Wi-Fi -> Private DNS and enter the hostname. Supports only DoT.
      
     
    * For other OS's
       * [Knot-resolver](https://www.knot-resolver.cz).
       * [Unbound](https://nlnetlabs.nl/projects/unbound/about).
       * [Stubby](https://dnsprivacy.org/wiki/display/DP/DNS+Privacy+Daemon+-+Stubby).
       * [m13253's DoH](https://github.com/m13253/dns-over-https).




