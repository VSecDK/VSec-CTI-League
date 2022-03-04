# 2021-02-29 - Ransomware - Lifa
Company: Lifa   
Type: Ransomware   
Sector: Production / Land surveying  
Actor: Conti   

## Description  
The land surveyor company Lifa was hit by Conti ransomware in the weekend between friday the 29th of February to the 1st of March 2022. Homepage and it-systems are affected.
According to Computerworld on the 3rd of March, Director Thomas Boding denies to pay ransom.

## Timeline
### 29/02 to 01/03 2022
Hit by ransomware

## Security Advisor
Truesec  

## Related Indicators of compromise
150.129.234[.]203:82 Download IP for Chimaera cryptojacking malware  
51.222.121[.]180:82 Download IP for Chimaera cryptojacking malware  
103.142.218[.]18:18 Download IP for Chimaera cryptojacking malware  
45.32.120[.]201 C2 IP for persistence on VMware Horizon VM  
176.113.115[.]107 Download IP for Atera Remote access used by Conti  
193.27.228[.]127 Download IP for Atera Remote access used by Conti  

According to Truesec Denmark CEO and VSec Member the above IOC's are related to the incident.  
Entrypoint was a vulnerability that an external vulnerability scanner had missed.

Source: https://www.truesec.com/hub/blog/teamtnt-gang-is-part-of-fin12-conti-syndicate-a-truesec-investigation

## Related Detection rules (Yara/Sigma)
Unknown

## References   

### 01.03.2022
https://www.computerworld.dk/art/259616/den-danske-million-virksomhed-lifa-ramt-af-russisk-hackerangreb-gennemfoerer-kontrolleret-nedlukning  

### 02.03.2022
https://fyens.dk/artikel/stor-fynsk-virksomhed-ramt-af-russisk-hackerangreb-jeg-tror-de-vil-ramme-infrastrukturen-i-danmark  
https://nyheder.tv2.dk/samfund/2022-03-02-dansk-firma-lagt-ned-af-russiske-hackere-er-gaaet-i-hoejeste-kriseberedskab  

### 02.03.2022
https://nyheder.tv2.dk/samfund/2022-03-02-dansk-firma-lagt-ned-af-russiske-hackere-er-gaaet-i-hoejeste-kriseberedskab

### 03.03.2022
https://finans.dk/tech/ECE13793541/angrebet-virksomhed-det-ville-vaere-en-meget-soegt-forklaring-hvis-man-undlod-at-betale-paa-grund-af-krigsklausul/  
https://www.computerworld.dk/art/259931/saadan-kan-russiske-hackere-vaere-kommet-ind-i-danske-lifas-it-systemer-direktoer-thomas-boding-naegter-at-betale-loesepenge

### 04.03.2022
https://jyllands-posten.dk/jplokal/jpranders/ECE13792059/hvorfor-skulle-et-russisk-cyberangreb-blive-rettet-mod-en-dansk-by-ifoelge-professor-er-der-to-grunde/

### Other
https://www.linkedin.com/feed/update/urn:li:activity:6905133322784034817/
