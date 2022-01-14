# 2021-06-04 - Kompan hit by ransomware (Conti)
Company: Kompan A/S  
Type: Ransomware  
Actor: Conti   

## Description   
The danish company Kompan A/S that sells equipment for playgrounds (turnover of 877 million DKK in 2020) was hit by ransomware in beginning of July 2021 but the attack was first discovered in the morning of the 19th of July 2021.
When the attack was discovered Kompan shut down all servers within 30 minuttes, but by then 562GB of data mainly personal information on employees, financial information, partner information and internal confidential data was already exfiltrated.
CSIS advised them that all exfiltrated data seemed to be deleted but the data (internal data, employee copies of passports, health information etc.) was later found on the dark web. According to the danish newssite [Version2](https://www.version2.dk/artikel/medarbejder-data-laekket-kompan-9-aar-efter-opsigelse-jeg-rystet-vred-1093999), the leak contained information about at least one former employee that had been with the company 9 years prior and should therefor not have existed in the leak due to [GDPR](https://ec.europa.eu/info/law/law-topic/data-protection/reform/rules-business-and-organisations/principles-gdpr/how-long-can-data-be-kept-and-it-necessary-update-it_en). 

## Security Advisors
CSIS

## Realated Indicators
None

## Related Detection rules (Yara/Sigma)
None

## References/links:  
https://www.version2.dk/artikel/stor-dansk-virksomhed-hacket-strategi-sundhedsdata-medarbejderes-finansielle-oplysninger   
https://www.version2.dk/artikel/kompan-fik-at-vide-datalaek-var-usandsynligt-vurdering-vil-jeg-gerne-snakke-med-csis-1093367   
https://www.version2.dk/artikel/mere-end-hundrede-pas-dansk-virksomhed-svoemmer-rundt-paa-dark-web-jeg-skraemt-uhyggeligt   
https://www.bt.dk/krimi/odense-virksomhed-hacket-og-afpresset-utrolig-ubehageligt    
https://www.bt.dk/samfund/gittes-pasoplysninger-ligger-formentlig-pa-det-morke-net-efter-hackerangreb-det-er   
https://www.computerworld.dk/art/257851/sundhedsoplysninger-kreditkort-og-billeder-af-boern-dansk-virksomhed-ramt-af-ransomware-angreb-har-faaet-laekket-store-maengder-data  
https://www.version2.dk/artikel/medarbejder-data-laekket-kompan-9-aar-efter-opsigelse-jeg-rystet-vred-1093999
