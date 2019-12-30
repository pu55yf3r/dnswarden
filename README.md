# Notice



## Implemented blocking of 1st party trackers which uses CNAME's, more [information](https://github.com/uBlockOrigin/uBlock-issues/issues/780) can be found here about them. This is only applicable to Adblocking and Adult-Filter dns.


# dnswarden
### Just a normal privacy oriented dns service with a ability to block ads , trackers and also provides uncensored dns! Servers are hosted in Germany



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
        * sdns://AQMAAAAAAAAAEzExNi4yMDMuNzAuMTU2OjQ0NDMgenKjVeH-LU7Opsyq1ljKZz14fHsngOK8OOeQ-cR2mAsjMi5kbnNjcnlwdC1jZXJ0LmRuc3dhcmRlbi0xLWFkYmxvY2s
        
        * sdns://AQMAAAAAAAAAEzExNi4yMDMuMzUuMjU1OjQ0NDMg-IlTTFFgMuUntnNV78COzbhJN9_OEOVWNgHhdg4BNXwjMi5kbnNjcnlwdC1jZXJ0LmRuc3dhcmRlbi0yLWFkYmxvY2s
        
        * sdns://AQMAAAAAAAAAETg4LjE5OC4xNjEuODo0NDQzIBc_e3j6AbaHocJHqJVzfpZ7xi2puAm6tL5xZTRrMTPbIzIuZG5zY3J5cHQtY2VydC5kbnN3YXJkZW4tMy1hZGJsb2Nr
        
       * IPv6
         * sdns://AQMAAAAAAAAAHFsyYTAxOjRmODoxYzFjOjc1YjQ6OjFdOjQ0NDMgenKjVeH-LU7Opsyq1ljKZz14fHsngOK8OOeQ-cR2mAsjMi5kbnNjcnlwdC1jZXJ0LmRuc3dhcmRlbi0xLWFkYmxvY2s
         
         * sdns://AQMAAAAAAAAAHFsyYTAxOjRmODoxYzFjOjVlNzc6OjFdOjQ0NDMg-IlTTFFgMuUntnNV78COzbhJN9_OEOVWNgHhdg4BNXwjMi5kbnNjcnlwdC1jZXJ0LmRuc3dhcmRlbi0yLWFkYmxvY2s
         
         * sdns://AQMAAAAAAAAAG1syYTAxOjRmODpjMGM6NjJhNzo6MV06NDQ0MyAXP3t4-gG2h6HCR6iVc36We8YtqbgJurS-cWU0azEz2yMyLmRuc2NyeXB0LWNlcnQuZG5zd2FyZGVuLTMtYWRibG9jaw
         
   * ### Clear text dns
      
        * IPv4
          
          * 116.203.70.156
       
        * IPv6
          
          * 2a01:4f8:1c1c:75b4::1
       
* ## Uncensored DNS (DoT, DoH, DnsCryptV2)
  
  
  * ### DNS-over-TLS
     *  uncensored-dot.dnswarden.com ( Supports both port **853** and **443**)
  
  * ### DNS-over-HTTPS: 
    *  https://doh.dnswarden.com/uncensored
    *  https://ecs-doh.dnswarden.com/uncensored-ecs (With [ECS](https://tools.ietf.org/html/rfc7871))
    
  * ### DnsCryptV2

      * IPv4
        * sdns://AQcAAAAAAAAAEzExNi4yMDMuNzAuMTU2Ojg0NDMgenKjVeH-LU7Opsyq1ljKZz14fHsngOK8OOeQ-cR2mAskMi5kbnNjcnlwdC1jZXJ0LmRuc3dhcmRlbi0xLXVuY2Vuc29y
        
        * sdns://AQcAAAAAAAAAEzExNi4yMDMuMzUuMjU1Ojg0NDMg-IlTTFFgMuUntnNV78COzbhJN9_OEOVWNgHhdg4BNXwkMi5kbnNjcnlwdC1jZXJ0LmRuc3dhcmRlbi0yLXVuY2Vuc29y
        
        * sdns://AQcAAAAAAAAAETg4LjE5OC4xNjEuODo4NDQzIBc_e3j6AbaHocJHqJVzfpZ7xi2puAm6tL5xZTRrMTPbJDIuZG5zY3J5cHQtY2VydC5kbnN3YXJkZW4tMy11bmNlbnNvcg
        
        
       * IPv6
         * sdns://AQcAAAAAAAAAHFsyYTAxOjRmODoxYzFjOjc1YjQ6OjFdOjg0NDMgenKjVeH-LU7Opsyq1ljKZz14fHsngOK8OOeQ-cR2mAskMi5kbnNjcnlwdC1jZXJ0LmRuc3dhcmRlbi0xLXVuY2Vuc29y
         
         * sdns://AQcAAAAAAAAAHFsyYTAxOjRmODoxYzFjOjVlNzc6OjFdOjg0NDMg-IlTTFFgMuUntnNV78COzbhJN9_OEOVWNgHhdg4BNXwkMi5kbnNjcnlwdC1jZXJ0LmRuc3dhcmRlbi0yLXVuY2Vuc29y
         
         * sdns://AQcAAAAAAAAAG1syYTAxOjRmODpjMGM6NjJhNzo6MV06ODQ0MyAXP3t4-gG2h6HCR6iVc36We8YtqbgJurS-cWU0azEz2yQyLmRuc2NyeXB0LWNlcnQuZG5zd2FyZGVuLTMtdW5jZW5zb3I
       
   * ### Clear text dns
      
        * IPv4
          
          * 116.203.35.255
       
        * IPv6
          
          * 2a01:4f8:1c1c:5e77::1
       
       
* ## Adult Filter DNS (DoT, DoH, DnsCryptV2)
  
  
  * ### DNS-over-TLS
     *  adult-filter-dot.dnswarden.com ( Supports both port **853** and **443**)
  
  * ### DNS-over-HTTPS: 
    *  https://doh.dnswarden.com/adult-filter
    *  https://ecs-doh.dnswarden.com/adult-filter-ecs (With [ECS](https://tools.ietf.org/html/rfc7871))
    
  * ### DnsCryptV2
      * IPv4
        * sdns://AQMAAAAAAAAAEzExNi4yMDMuNzAuMTU2OjE0NDMgenKjVeH-LU7Opsyq1ljKZz14fHsngOK8OOeQ-cR2mAsoMi5kbnNjcnlwdC1jZXJ0LmRuc3dhcmRlbi0xLWFkdWx0LWZpbHRlcg
        
        * sdns://AQMAAAAAAAAAEzExNi4yMDMuMzUuMjU1OjE0NDMg-IlTTFFgMuUntnNV78COzbhJN9_OEOVWNgHhdg4BNXwoMi5kbnNjcnlwdC1jZXJ0LmRuc3dhcmRlbi0yLWFkdWx0LWZpbHRlcg
        
        * sdns://AQMAAAAAAAAAETg4LjE5OC4xNjEuODoxNDQzIBc_e3j6AbaHocJHqJVzfpZ7xi2puAm6tL5xZTRrMTPbKDIuZG5zY3J5cHQtY2VydC5kbnN3YXJkZW4tMy1hZHVsdC1maWx0ZXI
        
       * IPv6
         * sdns://AQMAAAAAAAAAHFsyYTAxOjRmODoxYzFjOjc1YjQ6OjFdOjE0NDMgenKjVeH-LU7Opsyq1ljKZz14fHsngOK8OOeQ-cR2mAsoMi5kbnNjcnlwdC1jZXJ0LmRuc3dhcmRlbi0xLWFkdWx0LWZpbHRlcg
         
         * sdns://AQMAAAAAAAAAHFsyYTAxOjRmODoxYzFjOjVlNzc6OjFdOjE0NDMg-IlTTFFgMuUntnNV78COzbhJN9_OEOVWNgHhdg4BNXwoMi5kbnNjcnlwdC1jZXJ0LmRuc3dhcmRlbi0yLWFkdWx0LWZpbHRlcg
         
         * sdns://AQMAAAAAAAAAG1syYTAxOjRmODpjMGM6NjJhNzo6MV06MTQ0MyAXP3t4-gG2h6HCR6iVc36We8YtqbgJurS-cWU0azEz2ygyLmRuc2NyeXB0LWNlcnQuZG5zd2FyZGVuLTMtYWR1bHQtZmlsdGVy
       

   * ### Clear text dns
      
        * IPv4
          
          * 88.198.161.8
       
        * IPv6
          
          * 2a01:4f8:c0c:62a7::1

       
* ## Privacy policy and T&C
  * Use at your own risk. I will not be held responsible for any downtime of the servers , only on a "best effort" basis.
  * No query logging . Completely disabled query logs related to the DNS traffic.
  * Dns traffic will be forwarded to either [dns.watch](https://dns.watch) or datacenter's dns servers if any one of the backend resolver fails. 



* ### Health/Dns Query Rate Graph
    * [Live at](https://health.dnswarden.com/?server=dnsdist.dnswarden.main). The graph what you see here is equal to "Total number of queries received by servers" minus "Cache hits" , because each backend has its own resolver with cache enabled. So it is kinda hard to know the "Total numbers of queries received by the servers" without disabling the resolver cache on the backends.
    * [Uptimerobot](https://health-check.dnswarden.com)
    
    
* ### Test domains to check whether the dns is correctly configured or not.

   * [While using uncensored dns](https://test-uncensor.dnswarden.com)
   * [While using adblock dns](https://test-adblock.dnswarden.com)
   * [While using adult-filter dns](https://test-adult-filter.dnswarden.com)
   * [To test whether you are using dnswarden or not](https://test.dnswarden.com)


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



# Contributors
  * [Blaumaus](https://github.com/Blaumaus), for providing the initial working website.
