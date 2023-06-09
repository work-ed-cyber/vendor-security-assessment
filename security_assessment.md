# VENDOR SECURITY ASSESSMENT

Learn how to research by using various open-source tools and content that was provided on the vendor’s website to determine the quality of a vendor’s security program.


## Researching the Company
- **Task 1**: Identify the product/service to be purchased/used, bold one and italicize the other:

  - **Blackboard**
  - *Canvas*

- **Task 2**: Search for any Privacy Link or Risk and Compliance Link (if available). The Privacy Link should state how and what type of information is being collected and what is shared to third-parties if any. Based on the information provided, determine what you are comfortable in sharing with the company and if your information stays within the United States or not. If it is outside the United States, the security posture of another foreign country is very different in how security protections are put in place.

- **Task 3**: Determine if there is a Search Button on the website and type “security” or “compliance” (if available). You are trying to determine if the company discloses any of their security programs. Look for any verbiages on the following security categories and bold/italicize the ones you find: 
  - Security and Awareness Program 
  - Access Control 
  - Audit and Accountability
  - Assessment, Authorization and Monitoring
  - Configuration Management
  - Contingency Planning
  - Identification and Authentication
  - Incident Response
  - Maintenance
  - Media Protection
  - Physical and Environmental Protection
  - Planning
  - Program Management
  - PII Processing and Transparency
  - Risk Assessment
  - System and Services Acquisition
  - System and Communications Protection
  - System and Information Integrity
  - Supply Chain Risk Management
  - Any verbiages or descriptions on the above topics shows us that the Company has some form of security program in place.
  - Look for any policies that are published for Security/Security Whitepaper

- **Task 4**: Look for any 3rd Party Audit Certifications that the vendor has claimed to have received and mark them in **bold**/*italics* 
  - SOC 2 Type 2
  - PCI – DSS: Ability to process credit card information securely 
  - ISO 27001

- **Task 5**: Look for a Customer List on the vendor’s website and **report your findings**. Look for well established companies that are utilising the vendor’s product or service. Usually, if a well-known company is using the product or service it means that the vendor has been vetted. An example is if the product/service will be used by a local government company, I would look at the vendor to determine if there was any local, state, or federal government that is already utilising the product or service.

**Open-Source Checks**
Utilize open-source intelligence (OSINT) to determine what we can find out about the vendor 

## Vulnerability Database Checks

- **Task 6**: Determine if there is any vulnerability that exists within the product or service by looking at various vulnerability databases. Look at the National Institute of Standards and Technology (NIST) Vulnerability Database and CVEdetails which is a free security vulnerability database.
  - [https://nvd.nist.gov/vuln/search](https://nvd.nist.gov/vuln/search)
      - Type the name of the vendor, product, or service on the search feature. We  are usually concerned if there is a vulnerability that is 1-2 years old and has a Medium/High/Critical Vulnerability that can be exploited by attackers.	

  - [https://www.cvedetails.com/](https://www.cvedetails.com/)
      - Type the name of the vendor, product, or service on the search feature. We are usually concerned if there is a vulnerability that is 1-2 years old and has a Medium/High/Critical Vulnerability that can be exploited by attackers.

**Were there any vulnerabilities?**

## Certificate Checks (Encryption)

- **Task 7**: Determine if the vendor utilises outdated encryption algorithms. If the encryption algorithm is outdated, it means that an attacker can possibly decrypt information that could be sensitive. Certificate checks scans a company’s public infrastructure to determine if data in transit is encrypted.
  - [https://www.ssllabs.com/ssltest/](https://www.ssllabs.com/ssltest/)
     - Type the Vendor URL on to the Qualys Scanner to determine if encryption is updated
     - You can also check if the protocol is unencrypted (http) or encrypted (https)

**Were there any certificates? **


## FedRAMP Checks (Been vetted for use for Government Agencies)

- **Task 8**: The Federal Risk and Authorization Management Program (FedRAMP) was established to provide a cost-effective, risk-based approach for the adoption and use of cloud services by the federal government. FedRAMP is a rigorous process to check if a vendor’s security posture meets the certain compliance requirements. Search for the Vendor’s name to determine if the vendor has gone through a FedRAMP certification [https://marketplace.fedramp.gov/#!/products?sort=productName](https://marketplace.fedramp.gov/#!/products?sort=productName)

**Have they been vetted? **

## Google News Search

- **Task 9**: Determine if the vendor has been in the news for any security breaches. For this course we will utilise the OSINT Framework which has other tools that can be utilised to verify and identify information about a company. The tool that we will focus on is the Google News Search.
  - [https://osintframework.com/](https://osintframework.com/)
      - Follow the directory path below:
          - Search Engines > News Search > Google News Search
      - Type in the Google New Search function the company name

**Were there any breaches or potential issues? **

## Final Recommendation

- **Task 10**: Articulate why the vendor should be chosen or not or if an alternative vendor should be utilised.


