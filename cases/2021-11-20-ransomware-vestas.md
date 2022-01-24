# 2021-11-19 - Ransomware - Vestas hit by cyber attack 
Company: Vestas A/S   
Type: Ransomware   
Sector: Energy  
Actor: Lockbit 2.0 

## Description  
Vestas was hit by ransomware on the 19th of November 2021 by the threat actor 

**Communication**   
Vestas has sent out four press releases first with sparingly information on the incident but on the 28th of November they confirmed to "Danmarks Radio" that they were in fact hit by a ransomware attack. On the 6th of December 2021 it was confirmed by Vestas that they were in fact hit by the Lockbit 2.0 ransomware. A 200GB leak that included pictures passports (also of top management and the security department), salery information, copies written signatures, technical data and very recent strategy documentation [according](https://www.version2.dk/artikel/vestas-hacket-vokser-topledelse-produkt-data-kompromitteret-kaempe-laek-1094059) to an article published in January 2022 from the danish news site Version2.   

Vestas have been critised in the media for keeping to much information about the incident to themselves. Vestas do not think that is the case.

**Economical Impact**   
Vestas shares closed on Monday the 22th of November 2021 with a loss of 2,5%, corresponding to a plunge in the wind turbine giant's market value of DKK 5.8 billion.

## Timeline
### November 19 
Vestas releases the following [press statement](https://www.vestas.com/en/media/company-news/2021/vestas-impacted-by-cyber-security-incident-c3457473):  
"Vestas has on 19 November 2021 been impacted by a cyber security incident. To contain the issue, IT systems are shut down across multiple business units and locations.
As part of our crisis management setup for cyber security, we are working together with our internal and external partners to contain the issue fully and recover our systems.
Customers, employees and other stakeholders may be affected by the shutdown of several of our IT-systems."

Backup [PDF](images/vestas-press-statement.pdf)    

### November 22 
Vestas releases an [updated statement](https://www.vestas.com/en/media/company-news/2021/update-on-cyber-security-incident-c3457795):   
"The company’s preliminary findings indicate that the incident has impacted parts of Vestas’ internal IT 
infrastructure and that data has been compromised. At this stage, the work and investigation are still 
ongoing. However, there is no indication that the incident has impacted third party operations, including customer 
and supply chain operations. Vestas’ manufacturing, construction and service teams have been able to 
continue operations, although several operational IT systems have been shut down as a precaution. 
Vestas has already initiated a gradual and controlled reopening of all IT systems."

Backup [PDF](images/vestas-press-update1.pdf)    

### November 26
Vestas Vice President, Head of Communications Anders Riis confirms to MarketWire and in an [article](https://finans.dk/erhverv/ECE13505712/vestas-med-itstatus-det-gaar-fint-fremad/) to Finans, that most systems are up and running again. They are generally seeing good progess but some systems are purposingly still shutdown.
He also states that they have not seen any substantial impact on production or operations due to the incident. They have also not seen any impact on the windfarms/mills, supply-chain or customers.

### November 28
Vestas confirms in an [article](https://www.dr.dk/nyheder/penge/cyberkriminelle-afpresser-dansk-vindmoellegigant/) on Danmarks Radio website that Vestas were in fact hit by ransomware.

### November 29
Vestas confirms in it's [second updated statement](https://www.vestas.com/en/media/company-news/2021/second-update-on-cyber-incident-c3462120) that Vestas were in fact hit by ransomware.

Backup [PDF](images/vestas-press-update2.pdf)    

### December 6
Vestas confirms in it's [third updated statement](https://www.vestas.com/en/media/company-news/2021/third-update-on-cyber-incident-c3466518) that data has been stolen and extortion of Vestas has been attempted by leaking data. Vestas also [confirms](https://www.dr.dk/nyheder/seneste/data-stjaalet-fra-vestas) to "Danmarks Radio" that they have indeed been hit by Lockbit 2.0. This is also confirmed on the onion leak site ([image from leaksite](images/vestas-screenshot-lockbit-leaksite-2021-12-06%2020-22.png)).

They also continue to state that "The work and investigations are still ongoing, and Vestas still has no indication that the event has impacted customer and supply chain operations, a view which is supported by third-party experts."

Backup [PDF](images/vestas-press-update3.pdf)    

## Security Advisor
CSIS ([unconfirmed by Vestas/CSIS](
https://finans.dk/erhverv/ECE13489688/cyberangreb-sender-vestas-i-armene-paa-csis-sikkerhedseksperter/)) 

## Related Indicators

## Related Detection rules (Yara/Sigma)

## References   

### 19.11.2021  
https://www.vestas.com/en/media/company-news/2021/vestas-impacted-by-cyber-security-incident-c3457473   

### 20.11.2021  
https://www.reuters.com/markets/europe/vestas-hit-by-cyber-security-incident-shuts-some-it-systems-2021-11-20/   
https://www.bloomberg.com/news/articles/2021-11-20/vestas-shuts-down-some-it-systems-after-cyber-security-incident  
https://www.berlingske.dk/business/vestas-ramt-af-cyberangreb-it-systemer-lukkes-ned   
https://nyheder.tv2.dk/samfund/2021-11-20-vestas-ramt-af-cyberangreb-it-systemer-lukkes-ned   
https://borsen.dk/nyheder/virksomheder/vestas-lukker-it-systemer-ned-efter-cyberangreb

### 22.11.2021  
https://www.vestas.com/en/media/company-news/2021/update-on-cyber-security-incident-c3457795   
https://finans.dk/erhverv/ECE13489688/cyberangreb-sender-vestas-i-armene-paa-csis-sikkerhedseksperter/   
https://borsen.dk/nyheder/generelt/vi-maa-udfordre-os-selv-som-samfund-undervurderer-vi-cyberkriminalitet   
https://finans.dk/erhverv/ECE13487221/cyberangreb-kan-goere-vestasaktien-til-en-oplagt-investering/  
https://www.dr.dk/nyheder/penge/i-oktober-advarede-efterretningstjenesten-energisektoren-om-angreb-nu-har-vestas-haft   
https://www.bleepingcomputer.com/news/security/wind-turbine-giant-vestas-data-compromised-in-cyberattack/
https://www.computerworld.dk/art/258705/hackerangreb-af-vestas-paavirker-stadig-centrale-it-systemer-data-er-blevet-kompromitteret   
https://www.version2.dk/artikel/vestas-ramt-hackerangreb-1093673  
https://finans.dk/erhverv/ECE13487092/vestas-om-hackerangreb-data-er-blevet-kompromitteret/   
https://energiwatch.dk/article13490178.ece

### 24.11.2021  
https://www.version2.dk/artikel/status-paa-vestas-angrebet-interne-systemer-paavirket-data-kompromitteret-1093691   

### 26.11.2021  
https://finans.dk/erhverv/ECE13505712/vestas-med-itstatus-det-gaar-fint-fremad/   

### 28.11.2021  
https://www.dr.dk/nyheder/penge/cyberkriminelle-afpresser-dansk-vindmoellegigant  

### 29.11.2021
https://www.vestas.com/en/media/company-news/2021/second-update-on-cyber-incident-c3462120  

### 06.12.2021
https://www.vestas.com/en/media/company-news/2021/third-update-on-cyber-incident-c3466518   
https://www.dr.dk/nyheder/seneste/data-stjaalet-fra-vestas

### 08.12.2021
https://www.version2.dk/artikel/sidste-gang-roeg-accentures-filer-online-ransomware-hackere-udskyder-vestas-laek-1093796   
https://www.version2.dk/artikel/hackere-har-offentliggjort-vestas-data-paa-nettet-tusindvis-kunders-finansielle-oplysninger  
https://www.computerworld.dk/art/258941/her-er-hackergruppen-der-har-faaet-ram-paa-vestas  

### 24.12.2022
https://www.version2.dk/artikel/vestas-hacket-vokser-topledelse-produkt-data-kompromitteret-kaempe-laek-1094059   

### Other
https://twitter.com/KraftCERT/status/1462157010506588169?s=20 (Reply to a Danish tweet about the incident from Norwegian KraftCERT stating that they cannot contact Vestas and that they are affected)   
https://www.wired.com/story/wind-turbine-hack/ (not directly related, old article from 2017)   
