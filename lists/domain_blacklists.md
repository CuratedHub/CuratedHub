A curated list of English blocklists (and some whitelists) for all your favorite adblockers and DNS tools.  
  

## Ad-Block Tests
https://canyoublockit.com/  
https://github.com/d3ward/toolz  
https://github.com/ymatuhin/adblock-tester  

### Convert
MANY OF THESE LISTS WILL BE SOMEWHAT INTERCHANGEABLE, SUCH AS THOSE FOR UBLOCK AND ADGUARD AND BRAVE SHIELDS  
---You can also easily change them with excel, such as adding 0.0.0.0 or removing it before the entire list. Seeing the different lists already will give you a template of how to format it or to create custom lists. Alternatively, write a script (even ai chats can do it for you now). Look at the ones below to get an idea. Most of the ones that say pi-hole are just a list of text domains.   
[Hosts-BL](https://github.com/ScriptTiger/Hosts-BL) (remove Duplicates and a few conversions)  
[Pi-Hole2Hosts](https://github.com/RPiList/specials/blob/master/Converter/pihole2hosts.py)  
[Hosts2Pi-Hole](https://github.com/RPiList/specials/blob/master/Converter/hosts2pihole.py)  
[Domains to Hosts](https://github.com/peter9811/ad_filter2hosts)  
[Hosts to AdGuard Home](https://github.com/henrikwidlund/hostsparser)  
[AdGuard to Hosts](https://github.com/b4skyx/adblock_hosts)  
[AdBlock Plus or Hosts to text-only Domain](https://github.com/justdomains/ci/blob/master/convertlists.py)  
[AdBlock Plus to Hosts](https://github.com/wwalexander/hostsblock)  
[AdBlock to domains](https://github.com/anthonytwh/pihole-blocklist-converter)  
[AdBlock to Unbound](https://github.com/imp1sh/adblock-converter)  
[AdBlock to uBlock](https://github.com/tnodet/morph-adblock)  
[Pi-Hole to AdGuard](https://github.com/headblockhead/piholeToAdguardConverter)  
[Hosts file to Unbound](https://github.com/a16bitsysop/blocklist2unbound)  
[Hosts file to Unbound](https://github.com/a16bitsysop/blocklist2unbound)  
[Hosts file to Unbound](https://github.com/Aracktus/DNS-Unbound-Blocklist-Downloader/blob/master/dns-unbound-blocklist-downloader.py)  
[Hosts file to Unbound](https://github.com/gbxyz/unbound-block-hosts)  
[AdBlock to Privoxy](https://github.com/Andrwe/privoxy-blocklist)  
[AdBlock Plus to Webkit](https://github.com/adblockplus/abp2blocklist)  
[IP (pg2) to ipset](https://github.com/ilikenwf/pg2ipset)  
[Disconnect.me json to domains/pi-hole](https://github.com/erkexzcx/disconnectme-pihole/blob/master/update.py)  
[Hosts to Little Snitch](https://github.com/NanoSector/bl-convert)  

### How-To Create Filters
[AdBlock Plus](https://help.adblockplus.org/hc/en-us/articles/360062733293-How-to-write-filters)  

If you see something like (uBlock/Adblock +) at the end of a link, it means it works with both and it is duplicated in the list with the other (so you know not to add twice).  

How to get AdBlock Plus lists to work in uBlock: https://github.com/bogachenko/fuckfuckadblock/issues/423   



## uBlock Origin
Most of these should work in AdGuard Browser extension.  
[urlHaus - malicious](https://malware-filter.gitlab.io/malware-filter/urlhaus-filter.txt)   
[urlHaus - Tracking Javascript](https://malware-filter.gitlab.io/malware-filter/tracking-filter.txt)  
[urlHaus - Phishing](https://malware-filter.gitlab.io/malware-filter/phishing-filter.txt)  
[Fanboy Annoyances](https://secure.fanboy.co.nz/fanboy-annoyance_ubo.txt) (includes Fanboy social list and cookie warning)  
[1Hosts lite](https://o0.pages.dev/Lite/adblock.txt)  
[1Hosts Pro](https://o0.pages.dev/Pro/adblock.txt)    
[uBlock Cookie Notices](https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/annoyances-cookies.txt)  
[uBlock Other Annoyances](https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/annoyances-others.txt)  
[uBlock Badware](https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/badware.txt)  
[uBlock Privacy](https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/privacy.txt)  
[uBlock Filters](https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/filters.txt)   
[uBlock Filters 2020](https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/filters-2020.txt)  
[uBlock Filters 2021](https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/filters-2021.txt)  
[uBlock Filters 2022](https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/filters-2022.txt)  
[uBlock Filters 2023](https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/filters-2023.txt)  
[uBlock Filters 2024](https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/filters-2024.txt)  
[uBlock Filters - Mobile](https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/filters-mobile.txt)  
[uBlock Lan Intrusion](https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/lan-block.txt) (Prevents public internet sites from digging into your local LAN files)  
[uBlock Resource Abuse](https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/resource-abuse.txt) (To foil sites potentially abusing CPU/bandwidth resources without informed consent)  
[uBlock Link Shorteners](https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/ubo-link-shorteners.txt)  
[uBlock unbreak](https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/unbreak.txt)  
[Fuckfuckadblock](https://raw.githubusercontent.com/bogachenko/fuckfuckadblock/master/fuckfuckadblock.txt?_=rawlist)   
---[Fuckfuckadblock CDN 1](https://fuckfuckadblock.pages.dev/fuckfuckadblock.txt?_=rawlist)  
---[Fuckfuckadblock CDN 2](https://raw.githack.com/bogachenko/fuckfuckadblock/master/fuckfuckadblock.txt?_=rawlist)  
---[Fuckfuckadblock CDN 3](https://cdn.statically.io/gh/bogachenko/fuckfuckadblock/master/fuckfuckadblock.txt?_=rawlist)   
[Fuckfuckadblock - Miners](https://raw.githubusercontent.com/bogachenko/fuckfuckadblock/master/fuckfuckadblock-mining.txt?_=rawlist)    
---[Fuckfuckadblock - Miners CDN 1](https://fuckfuckadblock.pages.dev/fuckfuckadblock-mining.txt?_=rawlist)  
---[Fuckfuckadblock - Miners CDN 2](https://raw.githack.com/bogachenko/fuckfuckadblock/master/fuckfuckadblock-mining.txt?_=rawlist)  
---[Fuckfuckadblock - Miners CDN 3](https://cdn.statically.io/gh/bogachenko/fuckfuckadblock/master/fuckfuckadblock-mining.txt?_=rawlist)    
[Bypass Paywalls Clean](https://raw.githubusercontent.com/bpc-clone/bypass-paywalls-clean-filters/main/bpc-paywall-filter.txt) (Same on AdGuard Home/uBlock)  
[EasyList uBO Cookie specific](https://github.com/easylist/easylist/raw/master/easylist_cookie/easylist_cookie_specific_uBO.txt)  
[EasyList uBO Privacy specific](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_specific_uBO.txt)  
[EasyList Adservers](https://github.com/easylist/easylist/raw/master/easylist/easylist_adservers.txt) (uBlock/AdBlock +)  
[EasyList Adservers Popup](https://github.com/easylist/easylist/raw/master/easylist/easylist_adservers_popup.txt) (uBlock/AdBlock +)  
[EasyList Allow List](https://github.com/easylist/easylist/raw/master/easylist/easylist_allowlist.txt) (uBlock/AdBlock +)  
[EasyList Allow List popup](https://github.com/easylist/easylist/raw/master/easylist/easylist_allowlist_popup.txt) (uBlock/AdBlock +)  
[EasyList Block](https://github.com/easylist/easylist/raw/master/easylist/easylist_general_block.txt) (uBlock/AdBlock +)  
[EasyList Block popup](https://github.com/easylist/easylist/raw/master/easylist/easylist_general_block_popup.txt) (uBlock/AdBlock +)  
[EasyList Hide](https://github.com/easylist/easylist/raw/master/easylist/easylist_general_hide.txt) (uBlock/AdBlock +)  
[EasyList Specific Block](https://github.com/easylist/easylist/raw/master/easylist/easylist_specific_block.txt) (uBlock/AdBlock +)  
[EasyList Specific Block popup](https://github.com/easylist/easylist/raw/master/easylist/easylist_specific_block_popup.txt) (uBlock/AdBlock +)  
[EasyList Specific Hide](https://github.com/easylist/easylist/raw/master/easylist/easylist_specific_hide.txt) (uBlock/AdBlock +)  
[EasyList Third Party](https://github.com/easylist/easylist/raw/master/easylist/easylist_thirdparty.txt) (uBlock/AdBlock +)  
[EasyList Third Party popup](https://github.com/easylist/easylist/raw/master/easylist/easylist_thirdparty_popup.txt) (uBlock/AdBlock +)   
[EasyList Cookie Allowlist](https://github.com/easylist/easylist/raw/master/easylist_cookie/easylist_cookie_allowlist.txt) (uBlock/AdBlock +)   
[EasyList Cookie Allowlist Hide](https://github.com/easylist/easylist/raw/master/easylist_cookie/easylist_cookie_allowlist_general_hide.txt) (uBlock/AdBlock +)  
[EasyList Cookie block](https://github.com/easylist/easylist/raw/master/easylist_cookie/easylist_cookie_general_block.txt) (uBlock/AdBlock +)   
[EasyList Cookie hide](https://github.com/easylist/easylist/raw/master/easylist_cookie/easylist_cookie_general_hide.txt) (uBlock/AdBlock +)  
[EasyList International cookie](https://github.com/easylist/easylist/raw/master/easylist_cookie/easylist_cookie_international_specific_block.txt) (uBlock/AdBlock +)  
[EasyList International cookie hide](https://github.com/easylist/easylist/raw/master/easylist_cookie/easylist_cookie_international_specific_hide.txt) (uBlock/AdBlock +)   
[EasyList Cookie specific block](https://github.com/easylist/easylist/raw/master/easylist_cookie/easylist_cookie_specific_block.txt) (uBlock/AdBlock +)   
[EasyList Cookie specific hide](https://github.com/easylist/easylist/raw/master/easylist_cookie/easylist_cookie_specific_hide.txt) (uBlock/AdBlock +)   
[EasyList Third-Party Cookie](https://github.com/easylist/easylist/raw/master/easylist_cookie/easylist_cookie_thirdparty.txt) (uBlock/AdBlock +)   
[EasyList Privacy Allow](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_allowlist.txt) (uBlock/AdBlock +)  
[EasyList International Privacy Allow](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_allowlist_international.txt) (uBlock/AdBlock +)  
[EasyList Privacy](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_general.txt) (uBlock/AdBlock +)  
[EasyList Privacy - Email Trackers](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_general_emailtrackers.txt) (uBlock/AdBlock +)   
[EasyList Privacy Specific](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_specific.txt) (uBlock/AdBlock +)  
[EasyList Privacy CNAME a8net](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_specific_cname_a8net.txt) (uBlock/AdBlock +)  
[EasyList Privacy CNAME acton](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_specific_cname_acton.txt) (uBlock/AdBlock +)  
[EasyList Privacy CNAME ad-ebis](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_specific_cname_ad-ebis.txt) (uBlock/AdBlock +)  
[EasyList Privacy CNAME adobe](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_specific_cname_adobe.txt) (uBlock/AdBlock +)  
[EasyList Privacy CNAME at-internet](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_specific_cname_at-internet.txt) (uBlock/AdBlock +)  
[EasyList Privacy CNAME branch](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_specific_cname_branch.txt) (uBlock/AdBlock +)  
[EasyList Privacy CNAME commanders-act](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_specific_cname_commanders-act.txt) (uBlock/AdBlock +)  
[EasyList Privacy CNAME criteo](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_specific_cname_criteo.txt) (uBlock/AdBlock +)  
[EasyList Privacy CNAME dataunlocker](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_specific_cname_dataunlocker.txt) (uBlock/AdBlock +)  
[EasyList Privacy CNAME eulerian](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_specific_cname_eulerian.txt) (uBlock/AdBlock +)  
[EasyList Privacy CNAME ingenious-technologies](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_specific_cname_ingenious-technologies.txt) (uBlock/AdBlock +)  
[EasyList Privacy CNAME keyade](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_specific_cname_keyade.txt) (uBlock/AdBlock +)  
[EasyList Privacy CNAME lead-forensics](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_specific_cname_lead-forensics.txt) (uBlock/AdBlock +)   
[EasyList Privacy CNAME np6](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_specific_cname_np6.txt) (uBlock/AdBlock +)  
[EasyList Privacy CNAME oracle](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_specific_cname_oracle.txt) (uBlock/AdBlock +)  
[EasyList Privacy CNAME otto](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_specific_cname_otto.txt) (uBlock/AdBlock +)  
[EasyList Privacy CNAME Plausible](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_specific_cname_plausible.txt) (uBlock/AdBlock +)  
[EasyList Privacy CNAME tracedock](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_specific_cname_tracedock.txt) (uBlock/AdBlock +)  
[EasyList Privacy CNAME webtrekk](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_specific_cname_webtrekk.txt) (uBlock/AdBlock +)  
[EasyList Privacy CNAME wizaly](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_specific_cname_wizaly.txt) (uBlock/AdBlock +)  
[EasyList International Specific](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_specific_international.txt) (uBlock/AdBlock +)  
[EasyList Privacy Specific Permiterx](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_specific_perimeterx.txt) (uBlock/AdBlock +)  
[EasyList Privacy Third-party](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_thirdparty.txt) (uBlock/AdBlock +)  
[EasyList Privacy Third-party International](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_thirdparty_international.txt) (uBlock/AdBlock +)   
[EasyList Privacy Tracking Servers](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_trackingservers.txt) (uBlock/AdBlock +)  
[EasyList Privacy Tracking Servers - Admiral](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_trackingservers_admiral.txt) (uBlock/AdBlock +)   
[EasyList Privacy Tracking Servers - general](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_trackingservers_general.txt) (uBlock/AdBlock +)   
[EasyList Privacy Tracking Servers - international](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_trackingservers_international.txt) (uBlock/AdBlock +)  
[EasyList Privacy Tracking Servers - mining](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_trackingservers_mining.txt) (uBlock/AdBlock +)  
[EasyList Privacy Tracking Servers - notifications](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_trackingservers_notifications.txt) (uBlock/AdBlock +)  
[EasyList Privacy Tracking Servers - Third-party](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_trackingservers_thirdparty.txt) (uBlock/AdBlock +)  
[ph00lt0 Blocklist](https://raw.githubusercontent.com/ph00lt0/blocklists/master/blocklist.txt) (uBO/AdGuard Home/Brave/Hosts)[
Dandelion uBlock](https://github.com/DandelionSprout/adfilt/raw/master/Dandelion%20Sprout's%20Anti-Malware%20List.txt)  
[Dandelion ClearURLs](https://github.com/DandelionSprout/adfilt/raw/master/ClearURLs%20for%20uBo/clear_urls_uboified.txt)  
[Dandelion Favicon](https://github.com/DandelionSprout/adfilt/raw/master/Special%20security%20lists/AntiFaviconList.txt)  
[Dandelion uBlock anti-logging extension](https://github.com/DandelionSprout/adfilt/raw/master/uBO%20list%20extensions/BrowseWebsitesWithoutLoggingIn-uBOExtension.txt)    
[Dandelion Annoyances](https://github.com/DandelionSprout/adfilt/raw/master/AnnoyancesList)  
[Dandelion Browse without logging in](https://github.com/DandelionSprout/adfilt/raw/master/BrowseWebsitesWithoutLoggingIn.txt)  
[LanikSJ Admiral Domains](https://raw.githubusercontent.com/LanikSJ/ubo-filters/main/filters/getadmiral-domains.txt)  
[Hagezi Blocklist - Normal](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/multi.txt) (uBo/Adblock+/AdGuard Home/Pi-hole/Brave)  
[Hagezi Blocklist - Pro++](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/pro.plus.txt)  (uBo/Adblock+/AdGuard Home/Pi-hole/Brave)  
[Hagezi Threat Intelligence](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/tif.txt) (uBo/Adblock+/AdGuard Home/Pi-hole/Brave)  
[Hagezi DNS-bypass Blocklist](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/doh-vpn-proxy-bypass.txt) (uBo/Adblock+/AdGuard Home/Pi-hole/Brave)  
[Hagezi Dynamic DNS blocking](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/dyndns.txt) (uBo/Adblock+/AdGuard Home/Pi-hole/Brave)  
[RpiList - Phishing](https://v.firebog.net/hosts/RPiList-Phishing.txt)  (uBo/Adblock+) 
[Yokoffing Privacy Essentials](https://github.com/yokoffing/filterlists/raw/main/privacy_essentials.txt)  (may cause some breakage)
[Yokoffing Block 3rd-party fonts](https://github.com/yokoffing/filterlists/raw/main/block_third_party_fonts.txt)  
[Yokoffing Anti-paywall](https://github.com/yokoffing/filterlists/raw/main/antipaywall_filters_without_element_hiding.txt)  
[Yokoffing Annoyance](https://github.com/yokoffing/filterlists/raw/main/annoyance_list.txt)  
[Dandelion Legitamate URL shortener](https://github.com/DandelionSprout/adfilt/raw/master/LegitimateURLShortener.txt)  
[Bypass Paywalls Clean](https://github.com/bpc-clone/bypass-paywalls-clean-filters/raw/main/bpc-paywall-filter.txt)  
[Antipaywall](https://github.com/liamengland1/miscfilters/raw/master/antipaywall.txt)  
[GoodbyeAds](https://raw.githubusercontent.com/jerryn70/GoodbyeAds/master/Formats/GoodbyeAds-AdBlock-Filter.txt) (uBo/Adblock Home/Adblock+/Brave)  
[NoAds X Files Blocklist](https://raw.githubusercontent.com/gioxx/xfiles/master/filtri.txt)  
[NoAds X Files Harmful sites](https://raw.githubusercontent.com/gioxx/xfiles/master/siteblock.txt)  
[Inversion Malicious Blocklist](https://github.com/elliotwutingfeng/Inversion-DNSBL-Blocklists/blob/main/Google_hostnames_UBO.txt?raw=true)  
[Global Anti-Scam](https://github.com/elliotwutingfeng/GlobalAntiScamOrg-blocklist/blob/main/global-anti-scam-org-scam-urls-UBO.txt?raw=true)  
 
 
## Host File
Note that 0.0.0.0 is faster than 127.0.0.1  
[CombinedPrivacy](https://raw.githubusercontent.com/bongochong/CombinedPrivacyBlockLists/master/newhosts-final.hosts)  (95% Toolz; 48% adblock-tester)  
[Ultimate Hosts Blacklist Hosts0](https://github.com/Ultimate-Hosts-Blacklist/Ultimate.Hosts.Blacklist/raw/master/hosts/hosts0) (5mb)  (when combined with Hosts 0-4: 80% Toolz; 48% adblock-tester)  
[Ultimate Hosts Blacklist Hosts1](https://github.com/Ultimate-Hosts-Blacklist/Ultimate.Hosts.Blacklist/raw/master/hosts/hosts1) (5mb)  
[Ultimate Hosts Blacklist Hosts2](https://github.com/Ultimate-Hosts-Blacklist/Ultimate.Hosts.Blacklist/raw/master/hosts/hosts2) (5mb)  
[Ultimate Hosts Blacklist Hosts3](https://github.com/Ultimate-Hosts-Blacklist/Ultimate.Hosts.Blacklist/raw/master/hosts/hosts3) (4mb)  
[Steven Black Hosts](https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts) (56% Toolz; 48% adblock-tester)  
---List of individual extra rules: https://github.com/FadeMind/hosts.extras  
---[adiq Nocoin Filter](https://raw.githubusercontent.com/hoshsadiq/adblock-nocoin-list/master/hosts.txt) (should already be in Ultimate Hosts Blacklist and Steven Blacks Hosts)  
[YoYo](https://pgl.yoyo.org/adservers/serverlist.php?hostformat=hosts)  (lets you change the IP)   
[urlHuas - Malicious](https://malware-filter.gitlab.io/malware-filter/urlhaus-filter-hosts.txt)   
[urlHaus - Phishing](https://malware-filter.gitlab.io/malware-filter/phishing-filter-hosts.txt)  
[Someonewhocares 127.0.0.1](https://someonewhocares.org/hosts/hosts)  
[Someonewhocares 0.0.0.0](https://someonewhocares.org/hosts/zero/hosts)  
[Adaway](https://raw.githubusercontent.com/AdAway/adaway.github.io/master/hosts.txt)  
[D3ward](https://raw.githubusercontent.com/d3ward/toolz/master/src/d3host.txt) (97% Toolz (but they make Toolz); 32% adblock-tester)    
[1Hosts lite](https://badmojr.gitlab.io/1hosts/Lite/hosts.txt)   
[1Hosts Pro](https://badmojr.gitlab.io/1hosts/Pro/hosts.txt) (84% Toolz, 32% adblock-tester)      
[Anudeep Blacklist](https://raw.githubusercontent.com/anudeepND/blacklist/master/adservers.txt) (hasn't been updated recently)  
[ph00lt0 Blocklist](https://raw.githubusercontent.com/ph00lt0/blocklists/master/blocklist.txt) (uBO/AdGuard Home/Brave/Hosts)  
[Dandelion Antimalware](https://github.com/DandelionSprout/adfilt/raw/master/Alternate%20versions%20Anti-Malware%20List/AntiMalwareHosts.txt)  
[MVPS Hosts](https://winhelp2002.mvps.org/hosts.txt) (2021 last update)  
[BarbBlock anti-DMCA](https://paulgb.github.io/BarbBlock/blacklists/hosts-file.txt) (BarbBlock was created in response to a troubling instance where a company used the DMCA takedown process to force a domain blacklist to remove its domain)  
[HostsVN Ads](https://raw.githubusercontent.com/bigdargon/hostsVN/master/hosts)  
[FadeMind Hosts.Extras](https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.2o7Net/hosts) (no updates in 2 years)  
[Frogeye First-party Trackers](https://hostfiles.frogeye.fr/firstparty-trackers-hosts.txt)  
[Frogeye Multi-party Trackers](https://hostfiles.frogeye.fr/multiparty-trackers-hosts.txt)  
[NoTrack Malware](https://gitlab.com/quidsup/notrack-blocklists/-/raw/master/malware.hosts?ref_type=heads)  
[NoTrack Tracker](https://gitlab.com/quidsup/notrack-blocklists/-/raw/master/trackers.hosts?ref_type=heads)  
[NoTrack Annoyances](https://gitlab.com/quidsup/notrack-annoyance-blocklist/-/raw/master/annoyance.hosts?ref_type=heads)  
[ThreatIntel Malware](https://osint.digitalside.it/Threat-Intel/lists/latestdomains.piHole.txt)   
[Hagezi Blocklist - Normal](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/hosts/multi.txt)  
[Hagezi Blocklist - Pro++](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/domains/pro.plus.txt) (97% Toolz; 41% adblock-tester)    
[Hagezi Threat Intelligence](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/hosts/tif.txt)  
[Zerodo1 Coinblocker](https://zerodot1.gitlab.io/CoinBlockerLists/hosts_browser)  
[Anudeep Facebook Blacklist](https://raw.githubusercontent.com/anudeepND/blacklist/master/facebook.txt)  
[Spotify Blocklist](https://github.com/x0uid/SpotifyAdBlock/raw/master/hosts)  
[KAD Hosts](https://raw.githubusercontent.com/FiltersHeroes/KADhosts/master/KADhosts.txt)  
[BlahDNS Blacklist](https://oooo.b-cdn.net/blahdns/blahdns_hosts.txt)  
[WindowsSpyBlocker Spy Blocklist](https://github.com/crazy-max/WindowsSpyBlocker/raw/master/data/hosts/spy.txt) (not updated for a while)  
[WindowsSpyBlocker extras](https://github.com/crazy-max/WindowsSpyBlocker/raw/master/data/hosts/extra.txt) (not updated for a while)  
[Adblock-nocoin-list](https://github.com/hoshsadiq/adblock-nocoin-list/raw/master/hosts.txt) (not updated for a while)  
[GoodbyeAds](https://raw.githubusercontent.com/jerryn70/GoodbyeAds/master/Hosts/GoodbyeAds.txt)  
[GoodbyeAds - Spotify](https://raw.githubusercontent.com/jerryn70/GoodbyeAds/master/Extension/GoodbyeAds-Spotify-AdBlock.txt)  
[GoodbyeAds - YouTube](https://raw.githubusercontent.com/jerryn70/GoodbyeAds/master/Extension/GoodbyeAds-YouTube-AdBlock.txt)  
[r-a-y AdGuard Mobile](https://github.com/r-a-y/mobile-hosts/raw/master/AdguardMobileSpyware.txt)  
[r-a-y AdGuard combined CNAME](https://github.com/r-a-y/mobile-hosts/raw/master/AdguardCNAME.txt)  (2mb) 
[r-a-y AdGuard CNAME Microsites](https://github.com/r-a-y/mobile-hosts/raw/master/AdguardCNAMEMicrosites.txt)  
[r-a-y AdGuard CNAME Ads](https://github.com/r-a-y/mobile-hosts/raw/master/AdguardCNAMEAds.txt)  
[r-a-y AdGuard Tracking](https://github.com/r-a-y/mobile-hosts/raw/master/AdguardTracking.txt)  
[r-a-y AdGuard 3rd-Party](https://github.com/r-a-y/mobile-hosts/raw/master/EasyPrivacy3rdParty.txt)  
[Warui Blocklist](https://warui.intaa.net/adhosts/hosts.txt)  
[iVoid Hosts](https://gitlab.com/intr0/iVOID.GitLab.io/-/raw/master/iVOID.hosts?ref_type=heads)  
[BlockListProject Abuse](https://blocklistproject.github.io/Lists/abuse.txt) (deceptive sites)  
[BlockListProject Ads](https://blocklistproject.github.io/Lists/ads.txt)  
[BlockListProject Cryptojacking](https://blocklistproject.github.io/Lists/crypto.txt) (may break normal crypto sites)  
[BlockListProject Malware](https://blocklistproject.github.io/Lists/malware.txt) (site that host malware)  
[BlockListProject Phishing](https://blocklistproject.github.io/Lists/phishing.txt)  
[BlocklistProject Ransomeware](https://blocklistproject.github.io/Lists/ransomware.txt)  
[BlockListProject Tracking](https://blocklistproject.github.io/Lists/tracking.txt)  
[BlockListProject SmartTV](https://blocklistproject.github.io/Lists/smart-tv.txt)  
[BlockListProject Adobe Telemetry](https://blocklistproject.github.io/Lists/adobe.txt)  
[DurableNapkin Scam Blocklist](https://github.com/durablenapkin/scamblocklist/raw/master/hosts.txt)  
[ThreatFox Abuse](https://threatfox.abuse.ch/downloads/hostfile/)  
[Schakal Hosts](https://schakal.ru/hosts/alive_hosts.txt)  
[DeveloperDan Ads & Tracking](https://www.github.developerdan.com/hosts/lists/ads-and-tracking-extended.txt) (56% Toolz; 41% adblock-tester)  
[DeveloperDan Facebook](https://www.github.developerdan.com/hosts/lists/facebook-extended.txt)  
[DeveloperDan Amp](https://www.github.developerdan.com/hosts/lists/amp-hosts-extended.txt)  
[DeveloperDan Aggressive Tracking](https://www.github.developerdan.com/hosts/lists/tracking-aggressive-extended.txt)  


## Plain Text
These should work with many, including AdGuard Home and pi-hole  
Domains are generally better than IP lists, because they won't change names as often, an IP can have multiple domains (less false positives), blocks before HTTPS connection.   
[Ultimate Hosts Blacklist Domain-0](https://raw.githubusercontent.com/Ultimate-Hosts-Blacklist/Ultimate.Hosts.Blacklist/master/domains/domains0.list) (5 mb)  
[Ultimate Hosts Blacklist Domain-1](https://github.com/Ultimate-Hosts-Blacklist/Ultimate.Hosts.Blacklist/raw/master/domains/domains1.list) (5 mb)  
[Ultimate Hosts Blacklist Domain-2](https://github.com/Ultimate-Hosts-Blacklist/Ultimate.Hosts.Blacklist/raw/master/domains/domains2.list) (4 mb)  
[Ultimate Hosts Blacklist IP](https://github.com/Ultimate-Hosts-Blacklist/Ultimate.Hosts.Blacklist/raw/master/ips/ips0.list)  
---[Ultimate Hosts Blocklist - nocoin](https://github.com/Ultimate-Hosts-Blacklist/adblock-nocoin-list/raw/master/clean.list) (should already be in the above domains)  
---[Ultimate Hosts Blocklist - add.risk](https://github.com/Ultimate-Hosts-Blacklist/Add_Risk/raw/master/clean.list)  (should be on Ultimate Blacklist and StevenBlack)  
---[StevenBlack plain text mirror](https://raw.githubusercontent.com/hectorm/hmirror/master/data/stevenblack/list.txt) (may not be most recent, better off creating script to mirror yoursef)  
[1Hosts lite](https://o0.pages.dev/Lite/domains.txt)  
[1Hosts Pro](https://o0.pages.dev/Pro/domains.txt)  
[YoYo](https://pgl.yoyo.org/adservers/serverlist.php?hostformat=plain)  
[urlHaus - Tracking Javascript](https://malware-filter.gitlab.io/malware-filter/tracking-data.txt)  
[CombinedPrivacy](https://raw.githubusercontent.com/bongochong/CombinedPrivacyBlockLists/master/NoFormatting/cpbl-ctld.txt)  
[CombinedPrivacy - Wildcards](https://raw.githubusercontent.com/bongochong/CombinedPrivacyBlockLists/master/NoFormatting/cpbl-wildcard-blacklist.txt)  
[CombinedPrivacy - IP](https://raw.githubusercontent.com/bongochong/CombinedPrivacyBlockLists/master/combined-final.cidr)  
[The Block List - ads](https://blocklistproject.github.io/Lists/alt-version/ads-nl.txt)  
[The Block List - phishing](https://blocklistproject.github.io/Lists/alt-version/phishing-nl.txt)  
[The Block List - redirect](https://blocklistproject.github.io/Lists/alt-version/redirect-nl.txt) (block sites that redirect from intended site)  
[The Block list - tracking](https://blocklistproject.github.io/Lists/alt-version/tracking-nl.txt)  
[The Block List - Adobe telemetry](https://blocklistproject.github.io/Lists/alt-version/adobe-nl.txt)  
[Admiral List](https://raw.githubusercontent.com/jkrejcha/AdmiraList/master/AdmiraList.txt)  
[AdBlock-Dandelion IP](https://github.com/DandelionSprout/adfilt/raw/master/AdGuard%20Home%20Compilation%20List/AdGuardHomeCompilationListIPs.txt)  
[AdGuard-Dandelion Webpush](https://github.com/DandelionSprout/adfilt/raw/master/AdGuard%20Home%20Compilation%20List/TopDescription-Notifications.notlist)  
[Dandelion Antimalware](https://github.com/DandelionSprout/adfilt/raw/master/Alternate%20versions%20Anti-Malware%20List/AntiMalwareDomains.txt)  
[Dandelion IP](https://github.com/DandelionSprout/adfilt/raw/master/Alternate%20versions%20Anti-Malware%20List/Dandelion%20Sprout's%20and%20other%20adblocker%20lists'%20IPs.ipset)  
[Dandelion presumed hostile IP](https://github.com/DandelionSprout/adfilt/raw/master/AdGuardHomeDisallowedIPs.txt)  
[Matomo spam](https://github.com/matomo-org/referrer-spam-list/raw/master/spammers.txt)  
[NeoHosts Basic](https://v.firebog.net/hosts/neohostsbasic.txt)  
[Pi-hole Stuff](https://raw.githubusercontent.com/RooneyMcNibNug/pihole-stuff/master/SNAFU.txt)  
[Firebog - AdGuard DNS](https://v.firebog.net/hosts/AdguardDNS.txt)  
[Firebog - Admiral](https://v.firebog.net/hosts/Admiral.txt)  
[Firebox - Ad Easy List](https://v.firebog.net/hosts/Easylist.txt)  
[HostsVN Adservers](https://github.com/bigdargon/hostsVN/raw/master/source/adservers-all.txt)  
[Firebog - Easy Privacy](https://v.firebog.net/hosts/Easyprivacy.txt)  
[Firebog - UT Capitole](https://v.firebog.net/hosts/Prigent-Ads.txt)  
[Frogeye First-party Trackers](https://hostfiles.frogeye.fr/firstparty-trackers.txt)  
[Frogeye Multi-party Trackers](https://hostfiles.frogeye.fr/multiparty-trackers.txt)  
[Perflyst - Android Tracking](https://raw.githubusercontent.com/Perflyst/PiHoleBlocklist/master/android-tracking.txt) (No updates in 1 year)  
[NoTrack Malware](https://gitlab.com/quidsup/notrack-blocklists/-/raw/master/malware.list?ref_type=heads)  
[NoTrack Tracker](https://gitlab.com/quidsup/notrack-blocklists/-/raw/master/trackers.list?ref_type=heads)  
[NoTrack Annoyances](https://gitlab.com/quidsup/notrack-annoyance-blocklist/-/raw/master/annoyance.list?ref_type=heads)  
[ThreatIntel Malware - IP](https://osint.digitalside.it/Threat-Intel/lists/latestips.txt)  
[ThreatIntel Malware - Domain](https://osint.digitalside.it/Threat-Intel/lists/latestdomains.txt)  
[ThreatIntel Latest Tips - IP](https://osint.digitalside.it/Threat-Intel/lists/latestips.txt)  
[ThreatIntel latesturl](https://osint.digitalside.it/Threat-Intel/lists/latesturls.txt)  
[Firebog UT Capitole - Cryptojacking](https://v.firebog.net/hosts/Prigent-Crypto.txt)  
[Firebog UT Capitole - Malware](https://v.firebog.net/hosts/Prigent-Malware.txt)  
[Phishing Army](https://phishing.army/download/phishing_army_blocklist_extended.txt)  
[Rpilist Easylist](https://github.com/RPiList/specials/raw/master/DNSMASQ/easylist)  
[Rpilist Malware](https://raw.githubusercontent.com/RPiList/specials/master/DNSMASQ/malware)  
[Hagezi Blocklist - Normal](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/domains/multi.txt)  
[Hagezi Blocklist - Pro++](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/hosts/pro.plus.txt)  
[Hagezi Threat Intelligence](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/domains/tif.txt)  
[AssoEchap - Stalkerware](https://raw.githubusercontent.com/AssoEchap/stalkerware-indicators/master/generated/hosts)  
[urlHaus - Malicious - IP](https://malware-filter.gitlab.io/malware-filter/urlhaus-filter-domains-online.txt)  
[urlHaus - Phishing](https://malware-filter.gitlab.io/malware-filter/phishing-filter-domains.txt)  
[ph00lt0 Blocklist](https://raw.githubusercontent.com/ph00lt0/blocklists/master/pihole-blocklist.txt)  
[Spotify Blocklist](https://github.com/x0uid/SpotifyAdBlock/blob/master/SpotifyBlocklist.txt)  
[KAD Hosts](https://raw.githubusercontent.com/FiltersHeroes/KADhosts/master/KADomains.txt)  
[BlahDNS Blacklist](https://github.com/zoonderkins/blahdns/raw/master/hosts/blacklist.txt) 
[BlahDNS Blacklist 2](https://oooo.b-cdn.net/blahdns/blahdns_domains.txt)  
[AirVPN - Malware](https://airvpn.org/api/dns_lists/?code=air_malware&block=0.0.0.0&style=domains)  
[AirVPN - Cryptojacking](https://airvpn.org/api/dns_lists/?code=air_cryptojacking&block=0.0.0.0&style=domains)  
[AirVPN - Ads](https://airvpn.org/api/dns_lists/?code=air_ads&block=0.0.0.0&style=domains)  
[No-google Blocklist](https://github.com/nickspaargaren/no-google/raw/master/pihole-google.txt)  
[LoyalSoldier Blocklist](https://raw.githubusercontent.com/Loyalsoldier/v2ray-rules-dat/release/reject-list.txt)  
[LoyalSoldier Windows Spy](https://raw.githubusercontent.com/Loyalsoldier/v2ray-rules-dat/release/win-spy.txt)  
[LoyalSoldier Windows Extra](https://raw.githubusercontent.com/Loyalsoldier/v2ray-rules-dat/release/win-extra.txt)  
[Scafroglia93 Meta Blocklist](https://github.com/scafroglia93/blocklists/raw/master/blocklists-meta.txt) (Meta as in Facebook)  
[Rescure Malicious Domain](https://rescure.fruxlabs.com/rescure_domain_blacklist.txt)  
[Blackbook - Malware](https://github.com/stamparm/blackbook/raw/master/blackbook.txt)  
[Nginx Ultimate Bot Blocker - Bad Referrers](https://raw.githubusercontent.com/mitchellkrogza/nginx-ultimate-bad-bot-blocker/master/_generator_lists/bad-referrers.list)  
[Nginx Ultimate Bot Blocker - Fake Googlebot IP](https://raw.githubusercontent.com/mitchellkrogza/nginx-ultimate-bad-bot-blocker/master/_generator_lists/fake-googlebots.list)  
[Firehold IP Blocklist - Level 1](https://raw.githubusercontent.com/firehol/blocklist-ipsets/master/firehol_level1.netset) (low false positives)  
[BlockListProject Abuse](https://blocklistproject.github.io/Lists/alt-version/abuse-nl.txt) (sites meant to deceive)  
[BlockListProject Ads](https://blocklistproject.github.io/Lists/alt-version/ads-nl.txt)  
[BlockListProject Cryptojacking](https://blocklistproject.github.io/Lists/alt-version/crypto-nl.txt) (can break normal crypto sites)  
[BlockListProject Malware](https://blocklistproject.github.io/Lists/alt-version/malware-nl.txt) (sites that host malware)  
[BlockListProject Phishing](https://blocklistproject.github.io/Lists/alt-version/phishing-nl.txt)  
[BlockListProject Ransomeware](https://blocklistproject.github.io/Lists/alt-version/ransomware-nl.txt)  
[BlockListProject Redirect](https://blocklistproject.github.io/Lists/alt-version/redirect-nl.txt)  
[BlockListProject Tracking](https://blocklistproject.github.io/Lists/alt-version/tracking-nl.txt)  
[BlockListProject SmartTV](https://blocklistproject.github.io/Lists/alt-version/smart-tv-nl.txt)  
[BlockListProject Adobe Telemetry](https://blocklistproject.github.io/Lists/alt-version/adobe-nl.txt)  
[Amnesty International Spyware](https://raw.githubusercontent.com/AmnestyTech/investigations/master/2021-07-18_nso/domains.txt)  
[Techynoy Ads](https://www.technoy.de/lists/blocklist.txt)  
[Technoy Malware](https://www.technoy.de/lists/malware.txt)  
[Inversion Malicious Blocklist](https://github.com/elliotwutingfeng/Inversion-DNSBL-Blocklists/blob/main/Google_hostnames_light.txt?raw=true)  
[Inversion Malicious Blocklist - IP](https://github.com/elliotwutingfeng/Inversion-DNSBL-Blocklists/blob/main/Google_ipv4.txt?raw=true)  
[AZOrult Malware](https://azorult-tracker.net/api/list/domain?format=plain)  
[Global Anti-Scam](https://github.com/elliotwutingfeng/GlobalAntiScamOrg-blocklist/blob/main/global-anti-scam-org-scam-urls.txt?raw=true)  
[Global Anti-Scam - IP](https://github.com/elliotwutingfeng/GlobalAntiScamOrg-blocklist/blob/main/global-anti-scam-org-scam-ips.txt?raw=true)  
[Maltrail Malware](https://raw.githubusercontent.com/stamparm/aux/master/maltrail-malware-domains.txt)  
[StopForumSpam Toxic Domains](https://www.stopforumspam.com/downloads/toxic_domains_whole.txt)  
[Disconnect.me Simple Ads](https://s3.amazonaws.com/lists.disconnect.me/simple_ad.txt) (not sure how well it is updated)  
[disconnectme-pihole - entities](https://raw.githubusercontent.com/erkexzcx/disconnectme-pihole/master/entities.txt)  
[disconnectme-pihole - servers](https://raw.githubusercontent.com/erkexzcx/disconnectme-pihole/master/services.txt)  




## Unbound
[YoYo](https://pgl.yoyo.org/adservers/serverlist.php?hostformat=unbound)   
[1Hosts lite](https://o0.pages.dev/Lite/unbound.conf)  
[1Hosts Pro](https://badmojr.gitlab.io/1hosts/Pro/unbound.conf)  
[ph00lt0 Blocklist](https://raw.githubusercontent.com/ph00lt0/blocklists/master/unbound-blocklist.txt)  
[Hagezi Blocklist - Normal](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/unbound/multi.blacklist.conf)  
[Hagezi Blocklist - Pro++](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/unbound/pro.plus.blacklist.conf)  
[Hagezi Threat Intelligence](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/unbound/tif.blacklist.conf)  
[Hagezi DNS-bypass Blocklist](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/unbound/doh-vpn-proxy-bypass.blacklist.conf)  
[Hagezi Dynamic DNS blocking](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/unbound/dyndns.blacklist.conf)  
[BlahDNS Blacklist](https://oooo.b-cdn.net/blahdns/blahdns_unbound.conf) (download)  
[No-google Blocklist](https://github.com/nickspaargaren/no-google/raw/master/pihole-google-unbound.conf)  

## Pi-hole  
Most should work with browser extensions adblockers as well. 
[Hagezi Blocklist - Normal](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/multi.txt) (uBo/Adblock+/AdGuard Home/Pi-hole/Brave)  
[Hagezi Blocklist - Pro++](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/pro.plus.txt)  (uBo/Adblock+/AdGuard Home/Pi-hole/Brave)  
[Hagezi Threat Intelligence](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/tif.txt) (uBo/Adblock+/AdGuard Home/Pi-hole/Brave)  
[Hagezi DNS-bypass Blocklist](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/doh-vpn-proxy-bypass.txt) (uBo/Adblock+/AdGuard Home/Pi-hole/Brave)  
[Hagezi Dynamic DNS blocking](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/dyndns.txt) (uBo/Adblock+/AdGuard Home/Pi-hole/Brave)  
[RpiList - Crypto](https://raw.githubusercontent.com/RPiList/specials/master/Blocklisten/crypto)  
[RpiList - Malware](https://raw.githubusercontent.com/RPiList/specials/master/Blocklisten/malware)  
[RpiList - MSOffice Telemetry](https://raw.githubusercontent.com/RPiList/specials/master/Blocklisten/MS-Office-Telemetry)  
[RpiList - Phishing-Angriffe](https://raw.githubusercontent.com/RPiList/specials/master/Blocklisten/Phishing-Angriffe )  
[RpiList - Windows 10 Telemetry](https://raw.githubusercontent.com/RPiList/specials/master/Blocklisten/Win10Telemetry )  


## DNSCrypt-Proxy
Or wildcard domains
[urlHaus - Domains - Malicious](https://malware-filter.gitlab.io/malware-filter/urlhaus-filter-dnscrypt-blocked-names.txt)   
[urlHaus - IP - Malicious](https://malware-filter.gitlab.io/malware-filter/urlhaus-filter-dnscrypt-blocked-ips.txt)  
[urlHaus - Phishing - Domains](https://malware-filter.gitlab.io/malware-filter/phishing-filter-dnscrypt-blocked-names.txt)   
[urlHaus - Phishing - IP](https://malware-filter.gitlab.io/malware-filter/phishing-filter-dnscrypt-blocked-ips.txt)   
[1Hosts lite](https://badmojr.gitlab.io/1hosts/Lite/domains.wildcards)   
[1Hosts Pro](https://badmojr.gitlab.io/1hosts/Pro/domains.wildcards)   
[Hagezi Blocklist Pro++](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/pro.plus-onlydomains.txt)  
[Hagezi Threat Intelligence](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/tif-onlydomains.txt)  
[Hagezi DNS-bypass Blocklist](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/doh-vpn-proxy-bypass-onlydomains.txt)  
[Hagezi Dynamic DNS blocking](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/dyndns-onlydomains.txt)  


## AdGuard Home
Should work with pi-hole also 
[urlHaus - Malicious](https://malware-filter.gitlab.io/malware-filter/urlhaus-filter-agh.txt)   
[urlHaus - Phishing](https://malware-filter.gitlab.io/malware-filter/phishing-filter-agh.txt)  
[AdGuard Base](https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_2_Base/filter.txt)  
[AdGuard Tracking Protection](https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_3_Spyware/filter.txt)  
[AdGuard Social Media](https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_4_Social/filter.txt) (removes "likes" "tweets" and integrations)  
[AdGuard Annoyances](https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_14_Annoyances/filter.txt) (includes cookie notices, popups, mobile app banners, and widgets)  
[AdGuard Annoyances - other](https://github.com/AdguardTeam/AdguardFilters/raw/master/AnnoyancesFilter/Other/sections/annoyances.txt)  
[1Hosts lite](https://o0.pages.dev/Lite/adblock.txt)  
[1Hosts Pro](https://o0.pages.dev/Pro/adblock.txt)     
[Bypass Paywalls Clean](https://raw.githubusercontent.com/bpc-clone/bypass-paywalls-clean-filters/main/bpc-paywall-filter.txt) (Same on AdGuard Home/uBlock) 
[ph00lt0 Blocklist](https://raw.githubusercontent.com/ph00lt0/blocklists/master/blocklist.txt) (uBO/AdGuard Home/Brave/Hosts)  
[AdGuard cookies](https://github.com/AdguardTeam/AdguardFilters/raw/master/AnnoyancesFilter/Cookies/sections/cookies_general.txt)    
[AdGuard cookies specific](https://github.com/AdguardTeam/AdguardFilters/raw/master/AnnoyancesFilter/Cookies/sections/cookies_specific.txt)  
[AdGuard self-promo](https://github.com/AdguardTeam/AdguardFilters/raw/master/AnnoyancesFilter/Other/sections/self-promo.txt) (blocks websites own banners)  
[AdGuard Tweaks](https://github.com/AdguardTeam/AdguardFilters/raw/master/AnnoyancesFilter/Other/sections/tweaks.txt) (changing ui, such as allowing right click on websites or unblocking a banner)  
[AdGuard anti-adblock detection - annoyances](https://github.com/AdguardTeam/AdguardFilters/raw/master/AnnoyancesFilter/Popups/sections/antiadblock.txt)    
[AdGuard anti-adblock detection](https://github.com/AdguardTeam/AdguardFilters/raw/master/BaseFilter/sections/antiadblock.txt)  
[AdGuard popups allow list](https://github.com/AdguardTeam/AdguardFilters/raw/master/AnnoyancesFilter/Popups/sections/popups_allowlist.txt)  
[AdGuard popups](https://github.com/AdguardTeam/AdguardFilters/raw/master/AnnoyancesFilter/Popups/sections/popups_general.txt)  
[AdGuard popups specific](https://github.com/AdguardTeam/AdguardFilters/raw/master/AnnoyancesFilter/Popups/sections/popups_specific.txt)  
[Adguard Widgets](https://github.com/AdguardTeam/AdguardFilters/raw/master/AnnoyancesFilter/Widgets/sections/widgets.txt)  
[AdGuard Adservers](https://github.com/AdguardTeam/AdguardFilters/raw/master/BaseFilter/sections/adservers.txt)  
[AdGuard Adservers - First Domain](https://github.com/AdguardTeam/AdguardFilters/raw/master/BaseFilter/sections/adservers_firstparty.txt)  
[AdGuard Allowlist](https://github.com/AdguardTeam/AdguardFilters/raw/master/BaseFilter/sections/allowlist.txt)  
[AdGuard Content Blocker](https://github.com/AdguardTeam/AdguardFilters/raw/master/BaseFilter/sections/content_blocker.txt)  
[AdGuard Crypto-Miners](https://github.com/AdguardTeam/AdguardFilters/raw/master/BaseFilter/sections/cryptominers.txt)  
[AdGuard Foreign](https://github.com/AdguardTeam/AdguardFilters/raw/master/BaseFilter/sections/foreign.txt)  
[AdGuard Element hider](https://github.com/AdguardTeam/AdguardFilters/raw/master/BaseFilter/sections/general_elemhide.txt)  
[AdGuard Advanced extensions](https://github.com/AdguardTeam/AdguardFilters/raw/master/BaseFilter/sections/general_extensions.txt) (css, scriplets, html filtering, etc.)  
[Adguard Blocking Rules](https://github.com/AdguardTeam/AdguardFilters/raw/master/BaseFilter/sections/general_url.txt)   
[AdGuard Content Replacement](https://github.com/AdguardTeam/AdguardFilters/raw/master/BaseFilter/sections/replace.txt)   
[AdGuard ad specific](https://github.com/AdguardTeam/AdguardFilters/raw/master/BaseFilter/sections/specific.txt)   
[Adguard Social Allowlist](https://github.com/AdguardTeam/AdguardFilters/raw/master/SocialFilter/sections/allowlist.txt)  
[AdGuard Social blocking](https://github.com/AdguardTeam/AdguardFilters/raw/master/SocialFilter/sections/general_url.txt)   
[AdGuard Social popups](https://github.com/AdguardTeam/AdguardFilters/raw/master/SocialFilter/sections/popups.txt)  
[AdGuard Social trackers](https://github.com/AdguardTeam/AdguardFilters/raw/master/SocialFilter/sections/social_trackers.txt)  
[AdGuard social specific widgets](https://github.com/AdguardTeam/AdguardFilters/raw/master/SocialFilter/sections/specific.txt)   
[AdGuard unblock search engine ads](https://github.com/AdguardTeam/AdguardFilters/raw/master/UsefulAdsFilter/sections/usefulads.txt)  
[Hagezi Blocklist - Normal](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/multi.txt) (uBo/Adblock+/AdGuard Home/Pi-hole/Brave)  
[Hagezi Blocklist - Pro++](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/pro.plus.txt)  (uBo/Adblock+/AdGuard Home/Pi-hole/Brave)  
[Hagezi Threat Intelligence](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/tif.txt) (uBo/Adblock+/AdGuard Home/Pi-hole/Brave)  
[Hagezi DNS-bypass Blocklist](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/doh-vpn-proxy-bypass.txt) (uBo/Adblock+/AdGuard Home/Pi-hole/Brave)  
[Hagezi Dynamic DNS blocking](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/dyndns.txt) (uBo/Adblock+/AdGuard Home/Pi-hole/Brave)  
[BlahDNS Blacklist](https://oooo.b-cdn.net/blahdns/blahdns_adguardhome.txt)  
[No-google blocklist](https://github.com/nickspaargaren/no-google/raw/master/pihole-google-adguard.txt)  
[GoodbyeAds](https://raw.githubusercontent.com/jerryn70/GoodbyeAds/master/Formats/GoodbyeAds-AdBlock-Filter.txt) (uBo/Adblock Home/Adblock+/Brave)  
[BlockListProject Abuse](https://blocklistproject.github.io/Lists/adguard/abuse-ags.txt) (sites meant to decieve)  
[BlockListProject Ads](https://blocklistproject.github.io/Lists/adguard/ads-ags.txt)  
[BlockListProject Cryptojacking](https://blocklistproject.github.io/Lists/adguard/crypto-ags.txt) (may break normal crypto sites)  
[BlockListProject Malware](https://blocklistproject.github.io/Lists/adguard/malware-ags.txt) (sites that host malware)  
[BlockListProject Phishing](https://blocklistproject.github.io/Lists/adguard/phishing-ags.txt)  
[BlockListProject Ransomeware](https://blocklistproject.github.io/Lists/adguard/ransomware-ags.txt)  
[BlockListProject Redirect](https://blocklistproject.github.io/Lists/adguard/redirect-ags.txt)  
[BlockListProject Scam](https://blocklistproject.github.io/Lists/adguard/scam-ags.txt)  
[BlockListProject Tracking](https://blocklistproject.github.io/Lists/adguard/tracking-ags.txt)  
[DurableNapkin Scam Blocklist](https://github.com/durablenapkin/scamblocklist/raw/master/adguard.txt)  


## Little Snitch
[YoYo](https://pgl.yoyo.org/adservers/serverlist.php?hostformat=littlesnitch)   
[1Hosts lite](https://badmojr.gitlab.io/1hosts/Lite/snitch.rules)  
[1Hosts Pro](https://badmojr.gitlab.io/1hosts/Pro/snitch.rules)  

## AdBlock Plus
[YoYo](https://pgl.yoyo.org/adservers/serverlist.php?hostformat=adblockplus)   
[Fanboy Complete](https://secure.fanboy.co.nz/r/fanboy-complete.txt) (Easylist, Easyprivacy, and Enhanced Trackers)   
[Fanboy Ultimate](https://secure.fanboy.co.nz/r/fanboy-ultimate.txt) (Easylist, Easyprivacy, Enhanced Trackers List and Annoyances)  
[Fanboy Enhanced Tracking](https://secure.fanboy.co.nz/enhancedstats.txt)  
[Fanboy Annoyances](https://secure.fanboy.co.nz/fanboy-annoyance.txt) (includes Fanboy social list and cookie warnings)  
[Fanboy anti-Facebook](https://secure.fanboy.co.nz/fanboy-antifacebook.txt)  
[Fanboy 3rd Party Fonts](https://secure.fanboy.co.nz/fanboy-antifonts.txt)  
[Eyeo Adblock Warning](https://gitlab.com/eyeo/filterlists/antiadblockfilters/-/raw/master/antiadblockfilters/antiadblock_english.txt) (removes adblock warnings)  
[Easylist - Adblock Warning](https://easylist-downloads.adblockplus.org/antiadblockfilters.txt)  
[Eyeo Circumvention](https://easylist-downloads.adblockplus.org/abp-filters-anti-cv.txt) (blocking newer anti-adblock ads)  
[Spam 404](https://raw.githubusercontent.com/Spam404/lists/master/adblock-list.txt) (blocks scam sites)  
[CombinedPrivacy](https://raw.githubusercontent.com/bongochong/CombinedPrivacyBlockLists/master/cpbl-abp-list.txt)   
[I don't care about cookies](https://www.i-dont-care-about-cookies.eu/abp/)   
[D3ward](https://raw.githubusercontent.com/d3ward/toolz/master/src/d3host.adblock)  
[EasyList ABP Hide](https://github.com/easylist/easylist/raw/master/easylist/easylist_specific_hide_abp.txt)  
[EasyList ABP Cookie](https://github.com/easylist/easylist/raw/master/easylist_cookie/easylist_cookie_specific_ABP.txt)  
[EasyList ABP Privacy Specific](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_specific_abp.txt)  
[EasyList Adservers](https://github.com/easylist/easylist/raw/master/easylist/easylist_adservers.txt) (uBlock/AdBlock +)  
[EasyList Adservers Popup](https://github.com/easylist/easylist/raw/master/easylist/easylist_adservers_popup.txt) (uBlock/AdBlock +)  
[EasyList Allow List](https://github.com/easylist/easylist/raw/master/easylist/easylist_allowlist.txt) (uBlock/AdBlock +)  
[EasyList Allow List popup](https://github.com/easylist/easylist/raw/master/easylist/easylist_allowlist_popup.txt) (uBlock/AdBlock +)   
[EasyList Block](https://github.com/easylist/easylist/raw/master/easylist/easylist_general_block.txt) (uBlock/AdBlock +)  
[EasyList Block popup](https://github.com/easylist/easylist/raw/master/easylist/easylist_general_block_popup.txt) (uBlock/AdBlock +)  
[EasyList Hide](https://github.com/easylist/easylist/raw/master/easylist/easylist_general_hide.txt) (uBlock/AdBlock +)  
[EasyList Specific Block](https://github.com/easylist/easylist/raw/master/easylist/easylist_specific_block.txt) (uBlock/AdBlock +)  
[EasyList Specific Block popup](https://github.com/easylist/easylist/raw/master/easylist/easylist_specific_block_popup.txt) (uBlock/AdBlock +)  
[EasyList Specific Hide](https://github.com/easylist/easylist/raw/master/easylist/easylist_specific_hide.txt) (uBlock/AdBlock +)  
[EasyList Third Party](https://github.com/easylist/easylist/raw/master/easylist/easylist_thirdparty.txt)  (uBlock/AdBlock +)  
[EasyList Third Party popup](https://github.com/easylist/easylist/raw/master/easylist/easylist_thirdparty_popup.txt) (uBlock/AdBlock +)   
[EasyList Cookie Allowlist](https://github.com/easylist/easylist/raw/master/easylist_cookie/easylist_cookie_allowlist.txt) (uBlock/AdBlock +)   
[EasyList Cookie Allowlist Hide](https://github.com/easylist/easylist/raw/master/easylist_cookie/easylist_cookie_allowlist_general_hide.txt) (uBlock/AdBlock +)   
[EasyList Cookie block](https://github.com/easylist/easylist/raw/master/easylist_cookie/easylist_cookie_general_block.txt) (uBlock/AdBlock +)   
[EasyList Cookie hide](https://github.com/easylist/easylist/raw/master/easylist_cookie/easylist_cookie_general_hide.txt) (uBlock/AdBlock +)  
[EasyList International cookie](https://github.com/easylist/easylist/raw/master/easylist_cookie/easylist_cookie_international_specific_block.txt) (uBlock/AdBlock +)   
[EasyList International cookie hide](https://github.com/easylist/easylist/raw/master/easylist_cookie/easylist_cookie_international_specific_hide.txt) (uBlock/AdBlock +)   
[EasyList Cookie specific block](https://github.com/easylist/easylist/raw/master/easylist_cookie/easylist_cookie_specific_block.txt) (uBlock/AdBlock +)   
[EasyList Cookie specific hide](https://github.com/easylist/easylist/raw/master/easylist_cookie/easylist_cookie_specific_hide.txt) (uBlock/AdBlock +)   
[EasyList Third-Party Cookie](https://github.com/easylist/easylist/raw/master/easylist_cookie/easylist_cookie_thirdparty.txt) (uBlock/AdBlock +)   
[EasyList Privacy Allow](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_allowlist.txt) (uBlock/AdBlock +)  
[EasyList International Privacy Allow](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_allowlist_international.txt) (uBlock/AdBlock +)  
[EasyList Privacy](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_general.txt) (uBlock/AdBlock +)  
[EasyList Privacy - Email Trackers](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_general_emailtrackers.txt) (uBlock/AdBlock +)   
[EasyList Privacy Specific](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_specific.txt) (uBlock/AdBlock +)  
[EasyList Privacy CNAME a8net](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_specific_cname_a8net.txt) (uBlock/AdBlock +)  
[EasyList Privacy CNAME acton](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_specific_cname_acton.txt) (uBlock/AdBlock +)  
[EasyList Privacy CNAME ad-ebis](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_specific_cname_ad-ebis.txt) (uBlock/AdBlock +)  
[EasyList Privacy CNAME adobe](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_specific_cname_adobe.txt) (uBlock/AdBlock +)  
[EasyList Privacy CNAME at-internet](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_specific_cname_at-internet.txt) (uBlock/AdBlock +)  
[EasyList Privacy CNAME branch](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_specific_cname_branch.txt) (uBlock/AdBlock +)  
[EasyList Privacy CNAME commanders-act](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_specific_cname_commanders-act.txt) (uBlock/AdBlock +)  
[EasyList Privacy CNAME criteo](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_specific_cname_criteo.txt) (uBlock/AdBlock +)  
[EasyList Privacy CNAME dataunlocker](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_specific_cname_dataunlocker.txt) (uBlock/AdBlock +)  
[EasyList Privacy CNAME eulerian](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_specific_cname_eulerian.txt) (uBlock/AdBlock +)  
[EasyList Privacy CNAME ingenious-technologies](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_specific_cname_ingenious-technologies.txt) (uBlock/AdBlock +)  
[EasyList Privacy CNAME keyade](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_specific_cname_keyade.txt) (uBlock/AdBlock +)   
[EasyList Privacy CNAME lead-forensics](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_specific_cname_lead-forensics.txt) (uBlock/AdBlock +)  
[EasyList Privacy CNAME np6](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_specific_cname_np6.txt) (uBlock/AdBlock +)  
[EasyList Privacy CNAME oracle](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_specific_cname_oracle.txt) (uBlock/AdBlock +)  
[EasyList Privacy CNAME otto](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_specific_cname_otto.txt) (uBlock/AdBlock +)  
[EasyList Privacy CNAME Plausible](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_specific_cname_plausible.txt) (uBlock/AdBlock +)  
[EasyList Privacy CNAME tracedock](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_specific_cname_tracedock.txt) (uBlock/AdBlock +)  
[EasyList Privacy CNAME webtrekk](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_specific_cname_webtrekk.txt) (uBlock/AdBlock +)  
[EasyList Privacy CNAME wizaly](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_specific_cname_wizaly.txt) (uBlock/AdBlock +)  
[EasyList International Specific](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_specific_international.txt) (uBlock/AdBlock +)  
[EasyList Privacy Specific Permiterx](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_specific_perimeterx.txt) (uBlock/AdBlock +)  
[EasyList Privacy Third-party](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_thirdparty.txt) (uBlock/AdBlock +)  
[EasyList Privacy Third-party International](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_thirdparty_international.txt) (uBlock/AdBlock +)  
[EasyList Privacy Tracking Servers](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_trackingservers.txt) (uBlock/AdBlock +)  
[EasyList Privacy Tracking Servers - Admiral](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_trackingservers_admiral.txt) (uBlock/AdBlock +)  
[EasyList Privacy Tracking Servers - general](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_trackingservers_general.txt) (uBlock/AdBlock +)  
[EasyList Privacy Tracking Servers - international](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_trackingservers_international.txt) (uBlock/AdBlock +)  
[EasyList Privacy Tracking Servers - mining](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_trackingservers_mining.txt) (uBlock/AdBlock +)   
[EasyList Privacy Tracking Servers - notifications](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_trackingservers_notifications.txt) (uBlock/AdBlock +)  
[EasyList Privacy Tracking Servers - Third-party](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_trackingservers_thirdparty.txt) (uBlock/AdBlock +)  
[Dandelion Anti-malware](https://github.com/DandelionSprout/adfilt/raw/master/Dandelion%20Sprout's%20Anti-Malware%20List.txt)  
[Hagezi Blocklist - Normal](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/multi.txt) (uBo/Adblock+/AdGuard Home/Pi-hole/Brave)  
[Hagezi Blocklist - Pro++](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/pro.plus.txt)  (uBo/Adblock+/AdGuard Home/Pi-hole/Brave)  
[Hagezi Threat Intelligence](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/tif.txt) (uBo/Adblock+/AdGuard Home/Pi-hole/Brave)  
[Hagezi DNS-bypass Blocklist](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/doh-vpn-proxy-bypass.txt) (uBo/Adblock+/AdGuard Home/Pi-hole/Brave)  
[Hagezi Dynamic DNS blocking](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/dyndns.txt) (uBo/Adblock+/AdGuard Home/Pi-hole/Brave)  
[RpiList - Phishing](https://v.firebog.net/hosts/RPiList-Phishing.txt)  (uBo/Adblock+)  
[adblock-nocoin-list](https://github.com/hoshsadiq/adblock-nocoin-list/raw/master/nocoin.txt) (not updated for a while)  
[GoodbyeAds](https://raw.githubusercontent.com/jerryn70/GoodbyeAds/master/Formats/GoodbyeAds-AdBlock-Filter.txt) (uBo/Adblock Home/Adblock+/Brave)  
[Inversion Malicious Blocklist](https://github.com/elliotwutingfeng/Inversion-DNSBL-Blocklists/blob/main/Google_hostnames_ABP.txt?raw=true)  
[Global Anti-Scam](https://github.com/elliotwutingfeng/GlobalAntiScamOrg-blocklist/blob/main/global-anti-scam-org-scam-urls-ABP.txt?raw=true)  


## DNSMasq
[YoYo](https://pgl.yoyo.org/adservers/serverlist.php?hostformat=dnsmasq)   
[urlHaus - Malicious](https://gitlab.com/malware-filter/urlhaus-filter#dnsmasq)  
[urlHaus - Phishing](https://malware-filter.gitlab.io/malware-filter/phishing-filter-dnsmasq.conf)  
[CombinedPrivacy](https://raw.githubusercontent.com/bongochong/CombinedPrivacyBlockLists/master/NoFormatting/cpbl-dnsmasq.txt)  
[1Hosts lite](https://badmojr.gitlab.io/1hosts/Lite/dnsmasq.conf)  
[1Hosts Pro](https://badmojr.gitlab.io/1hosts/Pro/dnsmasq.conf)  
[The Block List - ads](https://blocklistproject.github.io/Lists/dnsmasq-version/ads-dnsmasq.txt)  
[The Block List - phishing](https://blocklistproject.github.io/Lists/dnsmasq-version/phishing-dnsmasq.txt)  
[The Block List - redirect](https://blocklistproject.github.io/Lists/dnsmasq-version/redirect-dnsmasq.txt) (block sites that redirect from intended site)  
[The Block list - tracking](https://blocklistproject.github.io/Lists/dnsmasq-version/tracking-dnsmasq.txt)  
[The Block List - Adobe telemetry](https://blocklistproject.github.io/Lists/dnsmasq-version/adobe-dnsmasq.txt)  
[Hagezi Blocklist - Normal](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/dnsmasq/multi.txt)  
[Hagezi Blocklist - Pro++](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/dnsmasq/pro.plus.txt)  
[Hagezi Threat Intelligence](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/dnsmasq/tif.txt)  
[Hagezi DNS-bypass blocklist](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/dnsmasq/doh-vpn-proxy-bypass.txt)  
[Hagezi Dynamic DNS blocking](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/dnsmasq/dyndns.txt)  
[KAD Hosts](https://raw.githubusercontent.com/FiltersHeroes/KADhosts/master/KADdnsmasq.txt)  
[BlahDNS Blacklist](https://oooo.b-cdn.net/blahdns/blahdns_dnsmasq.conf) (download)  
[BlockListProject Abuse](https://blocklistproject.github.io/Lists/dnsmasq-version/abuse-dnsmasq.txt) (sites meant to deceive)  
[BlockListProject Ads](https://blocklistproject.github.io/Lists/dnsmasq-version/ads-dnsmasq.txt)  
[BlockListProject Cryptojacking](https://blocklistproject.github.io/Lists/dnsmasq-version/crypto-dnsmasq.txt) (may break normal crypto sites)  
[BlockListProject Malware](https://blocklistproject.github.io/Lists/dnsmasq-version/malware-dnsmasq.txt) (sites that host malware)  
[BlockListProject Phishing](https://blocklistproject.github.io/Lists/dnsmasq-version/phishing-dnsmasq.txt)  
[BlockListProject Ransomeware](https://blocklistproject.github.io/Lists/dnsmasq-version/ransomware-dnsmasq.txt)  
[BlockListProject Redirect](https://blocklistproject.github.io/Lists/dnsmasq-version/redirect-dnsmasq.txt) (block sites that redirect from intended site)  
[BlockListProject Scam](https://blocklistproject.github.io/Lists/dnsmasq-version/scam-dnsmasq.txt)  
[BlockListProject Tracking](https://blocklistproject.github.io/Lists/dnsmasq-version/tracking-dnsmasq.txt)  
[BlockListProject SmartTV](https://blocklistproject.github.io/Lists/dnsmasq-version/smart-tv-dnsmasq.txt)  
[BlockListProject Adobe Telemetry](https://blocklistproject.github.io/Lists/dnsmasq-version/adobe-dnsmasq.txt)  


## Brave Shields
Should have compatability with other browser extension lists like uBo or adguard browser.  
[Brave Experimental](https://raw.githubusercontent.com/brave/adblock-lists/master/brave-lists/experimental.txt) (may break some websites)  
[Brave First Party](https://github.com/brave/adblock-lists/raw/master/brave-lists/brave-firstparty.txt)  
[ph00lt0 Blocklist](https://raw.githubusercontent.com/ph00lt0/blocklists/master/blocklist.txt) (uBO/AdGuard Home/Brave/Hosts)  
[Hagezi Blocklist - Normal](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/multi.txt) (uBo/Adblock+/AdGuard Home/Pi-hole/Brave)  
[Hagezi Blocklist - Pro++](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/pro.plus.txt)  (uBo/Adblock+/AdGuard Home/Pi-hole/Brave)  
[Hagezi Threat Intelligence](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/tif.txt) (uBo/Adblock+/AdGuard Home/Pi-hole/Brave)  
[Hagezi DNS-bypass Blocklist](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/doh-vpn-proxy-bypass.txt) (uBo/Adblock+/AdGuard Home/Pi-hole/Brave)  
[Hagezi Dynamic DNS blocking](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/dyndns.txt) (uBo/Adblock+/AdGuard Home/Pi-hole/Brave)  
[GoodbyeAds](https://raw.githubusercontent.com/jerryn70/GoodbyeAds/master/Formats/GoodbyeAds-AdBlock-Filter.txt) (uBo/Adblock Home/Adblock+/Brave)  


## Wildcard Asterisk 
For use with software like OPNSense and YogaDNS
[Hagezi Blocklist - Normal](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/multi.txt)  
[Hagezi Threat Intelligence](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/tif.txt)  
[Hagezi DNS-bypass blocklist](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/doh-vpn-proxy-bypass.txt)  
[Hagezi Dynamic DNS blocking](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/dyndns.txt)  

## Suricata
[urlHaus - Malicious](https://malware-filter.gitlab.io/malware-filter/urlhaus-filter-suricata-online.rules)  
[urlHaus - Phishing](https://malware-filter.gitlab.io/malware-filter/phishing-filter-suricata.rules)  
[ThreatFox Abuse](https://threatfox.abuse.ch/downloads/threatfox_suricata.rules)  

## RethinkDNS
Hagezi normal DNS-over-HTTPS: https://sky.rethinkdns.com/1:AAkACAgA   
Hagezi normal DNS-overTLS/QUIC: 1-aaeqacaiaa.max.rethinkdns.com   
Hagezi Pro++ DNS-over-HTTPS: https://sky.rethinkdns.com/1:AAoACAgA	   
Hagezi Pro++ DNS-over-TLS/QUIC:	1-aafaacaiaa.max.rethinkdns.com   


## Whitelists
https://raw.githubusercontent.com/anudeepND/whitelist/master/domains/whitelist.txt  
https://raw.githubusercontent.com/anudeepND/whitelist/master/domains/optional-list.txt  
[AdBlock unblocking search and self-promotions](https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_10_Useful/filter.txt)  
https://discourse.pi-hole.net/t/commonly-whitelisted-domains/212    
[uBlock unbreak](https://raw.githubusercontent.com/uBlockOrigin/uAssets/master/filters/unbreak.txt)  
[Slickdeals Allow List](https://slickdeals.net/attachment/extension/allowlist.txt)  
[Acceptable Ads](https://easylist-downloads.adblockplus.org/exceptionrules.txt)  
[Brave Unbreak](https://raw.githubusercontent.com/brave/adblock-lists/master/brave-unbreak.txt)  
[EasyList Allow List](https://github.com/easylist/easylist/raw/master/easylist/easylist_allowlist.txt) (uBlock/AdBlock +)  
[EasyList Allow List popup](https://github.com/easylist/easylist/raw/master/easylist/easylist_allowlist_popup.txt) (uBlock/AdBlock +)  
[EasyList Cookie Allowlist](https://github.com/easylist/easylist/raw/master/easylist_cookie/easylist_cookie_allowlist.txt) (uBlock/AdBlock +)  
[EasyList Privacy Allow](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_allowlist.txt) (uBlock/AdBlock +)
[EasyList International Privacy Allow](https://github.com/easylist/easylist/raw/master/easyprivacy/easyprivacy_allowlist_international.txt) (uBlock/AdBlock +)  
[Dandelion allow URL-shortener-affiliate tag](https://github.com/DandelionSprout/adfilt/raw/master/LegitimateURLShortener-AffiliateTagAllowlist.txt)  
[Dandelion allow URL-shortner](https://github.com/DandelionSprout/adfilt/raw/master/LegitimateURLShortener.txt)  
[AdGuard popups allow list](https://github.com/AdguardTeam/AdguardFilters/raw/master/AnnoyancesFilter/Popups/sections/popups_allowlist.txt)  
[AdGuard Allowlist](https://github.com/AdguardTeam/AdguardFilters/raw/master/BaseFilter/sections/allowlist.txt)  
[Adguard Social Allowlist](https://github.com/AdguardTeam/AdguardFilters/raw/master/SocialFilter/sections/allowlist.txt)  
[AdGuard unblock search engine ads](https://github.com/AdguardTeam/AdguardFilters/raw/master/UsefulAdsFilter/sections/usefulads.txt)  
[HG1978 - AdGuard Home Whitelist](https://github.com/hg1978/AdGuard-Home-Whitelist/raw/master/whitelist.txt)  
[Spotify Whitelist](https://gist.github.com/captainhook/9eb4132d6e58888e37c6bc6c73dd4e60)  
[Ultimate Hosts Whitelist](https://github.com/Ultimate-Hosts-Blacklist/whitelist/raw/master/domains.list) (For Steven Blacks consolidated host file)
[Anudeep false positives](https://github.com/anudeepND/blacklist/raw/master/miscellaneous/false-positives.txt)  
[Hagezi Whitelist URL Shortener](https://github.com/hagezi/dns-blocklists/raw/main/adblock/whitelist-urlshortener.txt)  
[OISD Whitelist](https://oisd.nl/excludes.php) 
[AdGuard Exclusions](https://github.com/liamengland1/miscfilters/raw/master/antipaywall.txt) (sites with personal info like privacy tools) 
[AdGuard DNS Exclusions](https://raw.githubusercontent.com/AdguardTeam/AdGuardSDNSFilter/master/Filters/exclusions.txt)  
[AdGuard Home Whitelist](https://raw.githubusercontent.com/DandelionSprout/AdGuard-Home-Whitelist/master/whitelist.txt)  
[Hagezi affiliate & Tracking referral unblock](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/whitelist-referral.txt)  
[Boutetnico - URL Shorteners](https://raw.githubusercontent.com/boutetnico/url-shorteners/master/list.txt)  
[Anudeep Whitelist](https://github.com/anudeepND/whitelist/blob/master/domains/whitelist.txt)  (hasn't been updated in a while)  
[SM443 Torrent trackers](https://github.com/SM443/Pi-hole-Torrent-Blocklist/raw/main/all-torrent-trackres.txt) (created as a blocklist, but I use as a whitelist...)  
[SM443 Torrent websites](https://github.com/SM443/Pi-hole-Torrent-Blocklist/raw/main/all-torrent-websites.txt) (created as blocklist, but I use as a whitelist...)
[BlahDNS Whitelist](https://raw.githubusercontent.com/ookangzheng/blahdns/master/hosts/whitelist.txt)  
[BlahDNS Whitelist2](https://github.com/zoonderkins/blahdns/raw/master/hosts/whitelist2.txt)  
[No-google](https://github.com/nickspaargaren/no-google)  
[AdGuard Banks & Financial](https://raw.githubusercontent.com/AdguardTeam/HttpsExclusions/master/exclusions/banks.txt)  
[Technoy Whitelist](https://www.technoy.de/lists/whitelist.txt)  


# Filter Lists
There may be some above not listed here if they only had one filter. 
https://gitlab.com/malware-filter/urlhaus-filter  
https://gitlab.com/malware-filter/phishing-filter  
https://gitlab.com/malware-filter/tracking-filter  
https://pgl.yoyo.org/adservers/  
https://malwarediscoverer.com/intelligence.html  
https://adguard.com/kb/general/ad-filtering/adguard-filters/  
https://gitlab.com/eyeo/filterlists/antiadblockfilters  
https://gitlab.com/eyeo/anti-cv/abp-filters-anti-cv  
https://adblockplus.org/subscriptions  
https://github.com/bongochong/CombinedPrivacyBlockLists/  
https://someonewhocares.org/  
https://github.com/AdAway/adaway.github.io/  
https://firebog.net/  
https://github.com/badmojr/1Hosts  
https://publicsuffix.org/list/index.html  
https://github.com/uBlockOrigin/uAssets/tree/master/filters  
https://bogachenko.github.io/fuckfuckadblock/  
https://acceptableads.com/ (The reason why everyone hates AdBlock Plus and other similar ad-blockers)  
https://github.com/brave/adblock-lists/tree/master/brave-lists  
https://github.com/bpc-clone/bypass-paywalls-clean-filters   
https://github.com/jkrejcha/AdmiraList/tree/master  
https://easylist.to/  
https://firebog.net/  
https://winhelp2002.mvps.org/  
https://github.com/DandelionSprout/adfilt (some reports about blocking domains of non malware/ad content that owner politically disagrees with)  
https://github.com/ph00lt0/blocklist  
https://github.com/AdguardTeam/AdguardFilters/tree/master  
https://dsi.ut-capitole.fr/blacklists/  
https://hostfiles.frogeye.fr/  
https://gitlab.com/quidsup/notrack-blocklists  (now in maintenance mode only)
https://osint.digitalside.it/  
https://phishing.army/  
https://github.com/hagezi/dns-blocklists  
https://github.com/RPiList/specials  
https://github.com/StevenBlack/hosts  
---https://github.com/FadeMind/hosts.extras (extra rules for StevenBlack's host, all are also ported over to Ultimate Hosts Blacklist)  
https://kadantiscam.netlify.app/#hosts  
https://github.com/yokoffing/filterlists/tree/main  
https://github.com/SM443/Pi-hole-Torrent-Blocklist  
https://github.com/zoonderkins/blahdns/tree/master/hosts  
https://github.com/Loyalsoldier/v2ray-rules-dat  
https://github.com/ultimate-hosts-blacklist/ultimate.hosts.blacklist  
---https://github.com/Ultimate-Hosts-Blacklist (Check all the repositories here for the sources to Ultimate Hosts. They are plain text domains. Many are sourced from others such as StevenBlack's sources, converted from hosts (0.0.0.0), which you can find in repositories such as FadeMinds host.extras)  
---https://github.com/Ultimate-Hosts-Blacklist/adblock-nocoin-list  
---https://github.com/Ultimate-Hosts-Blacklist/Add_Risk  
https://github.com/scafroglia93/blocklists  
https://github.com/jerryn70/GoodbyeAds  
https://github.com/r-a-y/mobile-hosts  
https://github.com/Cats-Team/AdRules?tab=readme-ov-file (Chinese)  
https://rescure.fruxlabs.com/  
https://warui.intaa.net/  
https://github.com/stamparm/blackbook  
https://xfiles.noads.it/  
https://gitlab.com/intr0/iVOID.GitLab.io/  
https://github.com/mitchellkrogza/nginx-ultimate-bad-bot-blocker?tab=readme-ov-file  
https://github.com/mitchellkrogza/Phishing.Database  
https://iplists.firehol.org/    
---Consolidates large list of IP Blocklists. See website or: https://github.com/firehol/blocklist-ipsets  
https://blocklistproject.github.io/Lists/  
https://github.com/AmnestyTech/investigations  
https://cybertalk.io/de/blocklists-fuer-pihole/  
https://github.com/elliotwutingfeng/Inversion-DNSBL-Blocklists  
---https://tranco-list.eu/ (In Inversion Blocklist)  
https://github.com/elliotwutingfeng/GlobalAntiScamOrg-blocklist  
https://azorult-tracker.net/  
https://github.com/MetaMask/eth-phishing-detect/ (phishing targeting Ethereum/web3)  
https://cert.pl/en/posts/2020/03/malicious_domains/ (mostly Polish, but also international)  
https://openphish.com/  
https://gitlab.com/malware-filter/phishing-filter    
https://github.com/durablenapkin/scamblocklist  
https://threatfox.abuse.ch/export/  
https://www.stopforumspam.com/downloads  
https://github.com/hectorm/hblock  
https://github.com/disconnectme/disconnect-tracking-protection  
https://github.com/erkexzcx/disconnectme-pihole  
https://github.com/LanikSJ/ubo-filters/tree/main/filters  
https://www.github.developerdan.com/hosts/  
  

### Currently Deprecated Lists (only listing ones that could possibly be revived)
https://github.com/lightswitch05/hosts  
https://github.com/ph00lt0/blocklist  
https://github.com/anudeepND/blacklist  
https://gitlab.com/malware-filter/pup-filter  
https://winhelp2002.mvps.org/  
https://github.com/Perflyst/PiHoleBlocklist  
https://github.com/AssoEchap/stalkerware-indicators  
https://www.hostsfile.org/hosts.html  
https://github.com/mitchellkrogza/Badd-Boyz-Hosts  
https://github.com/mitchellkrogza/The-Big-List-of-Hacked-Malware-Web-Sites  
https://github.com/mitchellkrogza/Phishing.Database  
https://github.com/tiuxo/hosts  
https://github.com/zoonderkins/blahdns   
https://github.com/crazy-max/WindowsSpyBlocker/tree/master/data/hosts   
https://github.com/stamparm/maltrail/  
https://github.com/justdomains/blocklists  



### Abandoned (but possibly useful)
https://sysctl.org/cameleon/  
https://github.com/mitchellkrogza/Stop.Google.Analytics.Ghost.Spam.HOWTO   

### International
Not a comprehensive list
[CERT Polska Malicious](https://hole.cert.pl/domains/domains.txt) (Polish)  
[Tcert  Malicious](https://www.usom.gov.tr/url-list.txt) (Turkish/Russian)  
[Takeaway Phishing](https://github.com/SoftCreatR/fakerando-domains) (archived)  

=== Ultimate Hosts DNS Servers
IPV4:   
safedns.allover.co.za 88.198.70.38	  
safedns2.allover.co.za 88.198.70.39	53, 5353  
Ports: 53, 5353


==== Pi-hole and unbound on Windows
Script: https://github.com/DesktopECHO/Pi-Hole-for-WSL1 



https://github.com/dnscrypt/dnscrypt-resolvers

Anonymized relays supported by:  
[dnscrypt-proxy](https://github.com/DNSCrypt/dnscrypt-proxy)   
[SecureDNS](https://github.com/Texnomic/SecureDNS)    
[Simple DNSCrypt](https://github.com/bitbeans/SimpleDnsCrypt) [(Instantsc Fork)](https://github.com/instantsc/SimpleDnsCrypt)  
[encrypted-dns-server](https://github.com/DNSCrypt/encrypted-dns-server)  
[YogaDNS](https://yogadns.com/ )   


Resolvers: https://github.com/dnscrypt/dnscrypt-resolvers



- [ ] To do: sort these better 
