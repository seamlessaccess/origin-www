---
layout: page
title: FAQ
---

### What is SeamlessAccess.org?

SeamlessAccess.org is a service, based on the findings of the Resource Access for the 21st Century ([RA21](https://ra21org)) initiative, designed to help foster a more streamlined online access experience when using scholarly collaboration tools, information resources, and shared research infrastructure. The service promotes digital authentication leveraging an existing single-sign-on infrastructure through one’s home institution, while maintaining an environment that protects personal data and privacy.


### How is SeamlessAccess.org governed?

SeamlessAccess.org is committed to ensuring all stakeholders are represented in governance of the service. Current coalition members include representatives from [GÉANT](https://geant.org), [Internet2](https://internet2.edu), the National Information Standards Organization ([NISO](https://niso.org)), [ORCID](https://orcid.org), and the International Association of STM Publishers ([STM](https://stm-assoc.org)). Technical Steering includes individuals from GEANT, Internet2, OARnet, Stanford University, and Duke University 


### How does SeamlessAccess.org take into account user privacy?

User privacy is one of the guiding principles of the SeamlessAccess.org service. The General Data Protection Regulation and the e-privacy regulation proposal arising from the EU provide a set of legal requirements that inform the configuration and use of the service. 

SeamlessAccess.org uses SAML federated authentication technology, which has in-built mechanisms for preserving privacy. No information can be shared about the user without action on the part of the user's institution. Typically, academic SAML Identity Providers provide unique, persistent, but opaque identifiers, which provides a way for service providers (SPs) to personalize services for users without knowing the actual identity of the individual. Optionally, SPs may then ask for additional personal information from users via their normal registration processes, disclosing their privacy policies, in order to provide services which require the publisher to know the identity of the user, such as email alerts.

### How is federated access relevant in the world of open access publishing?

Librarians are responsible for providing access to a vast array of information sources, not just journals. Access to books, databases and other online resources and services will also be improved.

The use of the SeamlessAccess.org service can also be implemented in manuscript submission systems, editorial review tools, pre-print servers, etc, easing the difficulties users have today in managing multiple accounts and passwords for these tools, and potentially allowing usage reporting on the institutional level, supporting the reporting and compliance requirements of institutions.

At present, libraries have no way of measuring usage of freely available information resources by their patrons. Depending on the access mechanism selected, it may be possible for librarians to better understand the patterns of usage of their patrons /across all information resources.
    

### How will federated access to library material work for the walk-in user at a library?

This is definitely an area which will need special attention. Using federated access does not imply using only login credentials. Institutions will be free to use different authentication methods for different classes of users. They could, for example, use smart cards, one-time access codes, certificates installed on library workstations, or even  continue to use the IP address authorization for on-site usage, or may transition to a guest account service. It is up to the library and its associated institution to make these decisions.


### Does SeamlessAccess.org replace IP-based access (e.g., EZProxy)? 

SeamlessAccess.org, alongside federated authentication, could eventually replace traditional IP-based access methods (e.g., EZProxy). SeamlessAccess.Org is a solution for licensed resource access that utilizes existing SAML federated authentication technology. Users may be familiar with federated authentication through using “institutional login” options on library vendor websites.

### Why should my library consider federated authentication instead of relying on traditional IP-based access? 

Libraries have long relied on IP-based methods to provide access to licensed electronic resources. However, in today’s world of networked mobile devices and increasingly sophisticated security threats, IP-based access may not be the best choice for libraries. Some considerations for libraries include: 

* Security 
  * IP-based access may pose a security threat to your institution, because legitimate credentials are not required to obtain access to resources. IP addresses can be emulated, and access could be provided for non-authorized use. Libraries should discuss these concerns with their IT department’s security professionals. 

* User expectations
  * Most non-library campus systems require authentication regardless of a user’s IP address, as IP addresses no longer accurately represent either a user’s location or legitimacy. Users may not understand why library access works differently from other campus systems.
  * IP access requires that a user begin with a “proxied” link if they are off-network. Users may not understand why (unlike other campus systems) they can’t go directly to the site they wish to access. 

* Reliability
  * IP access requires that the library maintain accurate lists of of both IP ranges and vendor URLs (proxy configuration files). Proxy configurations can easily break due to unexpected changes in vendor websites, resulting in loss of access and user frustration. Federated access, by contrast, does not require as much individual maintenance by libraries, as the federation serves as a single point of access for all vendors. This simplification can improve the reliability of library resource access. 

### Does SeamlessAccess.org require my organization already have federated authentication technology? (e.g., Shibboleth, OpenAthens, InCommon?) 

Your organization may already participate in a SAML-based identity federation such as InCommon or OpenAthens, and may utilize software tools such as Shibboleth to participate in that federation. Participation in a federation is required to implement SeamlessAccess.org. SeamlessAccess.org streamlines your organization’s existing federated identity environment by making it possible for users to stay logged in across different resource providers (single sign-on). Libraries should talk to their organization’s identity and access management professionals (often this will be the IT department) to learn whether or not their institution already participates in an identity federation. 

### Is federated access more secure than IP-based access (e.g., EZProxy)? 

Federated access requires every user, regardless of IP address, to authenticate using their institutional credentials. Federated access can be hacked by obtaining a legitimate user’s credentials. IP-based access, in contrast, can be hacked without obtaining credentials. IP addresses can be emulated by bad actors. Libraries should discuss these concerns with their IT department’s security professionals. 

### My organization has two-factor authentication implemented for our EZProxy sign on. Isn’t that secure? 

Two-factor authentication greatly improves the security of IP-based access methods. However, many libraries have implemented their IP access only for off-network (often called “off-campus”) users. This represents a security threat, as IP addresses can be emulated and are no longer an accurate representation of legitimate use. 

### Can libraries provide access to vendors who don’t yet participate in federated authentication?

Some e-resource vendors do not yet participate in federated authentication. Libraries will likely continue to utilize whatever access models required by those vendors for some resources until all vendors have adopted federated authentication. Software solutions are becoming available that allow libraries to support and manage both IP and federated access without needing to run separate systems or maintain complex proxy configuration files. 

### Will users need to start on a publisher site to access resources if we switch to federated authentication? Or can they still start on the library’s website?

Users can still directly access resources from links on the library’s website, if the library uses federated access links provided by vendors. SeamlessAccess.org ensures a consistent user experience: whether a user starts on the library website or elsewhere (e.g., Google Scholar) they will only need to authenticate once per browser session across all participating resource providers. 

### Can libraries track usage of e-resources with SeamlessAccess.org?

Depending on how libraries have implemented their federated access, they may be able to better understand patterns of usage across all information resources. IP access often cannot capture information about on campus use, and also does not capture use of open access resources. Federated access, as implemented with SeamlessAccess.org, can begin to provide better solutions. As with IP access methods, libraries may choose to implement software tools designed to capture and display usage patterns. 


### How can my library get started with SeamlessAccess.org?

Here are three things libraries can do to get started with SeamlessAccess.org and federated authentication: 

1. Find out if your institution already participates in an identity federation such as InCommon, the Australian Access Federation, OpenAthens. This may involve reaching  out to your IT department, or whomever manages identity and access management (IAM) at your institution. If your institution doesn’t yet participate, begin to advocate for membership. 

2. If your institution already supports federated authentication, work with your identity and access management team (often your IT department) to set up SeamlessAccess for your identity provider (IdP). You can also check out our Getting Started guide. Ask your library’s e-resource vendors if they participate in SeamlessAccess. For those that don’t, encourage them to consider adoption in order to provide library users with a consistent experience across platforms. 
