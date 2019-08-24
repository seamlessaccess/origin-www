---
layout: page
title: Getting Started
---

SeamlessAccess.org supports a streamlined federated authentication experience when using scholarly collaboration tools, information resources, and shared research infrastructure. Building on the [recommendations from the RA21 project](https://ra21.org/index.php/results/), the service promotes digital authentication leveraging an existing single-sign-on infrastructure through one’s home institution, while maintaining an environment that protects personal data and privacy. The service aims to enable simple, trusted use of scholarly resources and services anytime, anywhere, and on any device.

# Using SeamlessAccess

There are four basic steps for implementing the SeamlessAccess service:

![Four steps: 1 Gather information, 2. Connect Seamless Access Service, 3. Add Seamless Access button, 4. Tell your users](/assets/img/gettingStartedSteps.png)

## 1. Gather information

> **Who does this work?** This information will be gathered from several different people and probably will be coordinated by a project manager. During this phase of the work, you will be working closely with the SeamlessAccess team who will help you interpret the information you have gathered and what it means to your organization. Based on this information, we will also be able to estimate time and resource requirements to make your site SeamlessAccess enabled.

### How does your system support federated sign in?

You may not know this! So, your task will be in determining who in your organization to ask. Often those who handle system security compliance will know, as will those who manage the access control to the resources that are secured by a sign in. 

**Someone else may handle this**
In some cases, a vendor or software provider may provide this support for you. If this is the case, you will need to work with this provider to use SeamlessAccess. We are working with several providers, and would like to work with you and your provider on a solution.

**We do this ourselves, but I don't know what tool we use**
A few examples of tools include:

* [Shibboleth SP](https://www.shibboleth.net/products/service-provider/) (Open source software)
* [simpleSAMLphp](http://simplesamlphp.org/)
* [Active Directory Federation Services (ADFS)](https://docs.microsoft.com/en-us/windows-server/identity/active-directory-federation-services) (Microsoft)
* [Layer7 SiteMinder](https://www.ca.com/us/products/ca-single-sign-on.html) (formerly CA Single Sign-On)
* [ForgeRock Identity platform](https://www.forgerock.com/platform)
* [Oracle Access Management platform](https://www.oracle.com/middleware/identity-management/access-management/)

**Or, maybe you don’t yet enable federated single sign-on…**
Maybe you are just getting started with federated sign on! We’re excited that you are trying it out with SeamlessAccess so that your end users get the best possible user experience. For you, we suggest using Shibboleth SP, and we include in this guide details on how to get it up and running. Instead of continuing here, check out the Implementation Guide for Those New to Federated SSO.

### Choose a SeamlessAccess "flavor"

SeamlessAccess.org provides services and software, enabling three different "flavors" of implementation:

* **Limited** - lets you use the SeamlessAccess discovery service for users to find and sign into their preferred Identity Provider, but doesn’t integrate this service into your site
* **Full** - lets you use the SeamlessAccess service to display the button on your site, and use the SeamlessAccess discovery and persistence services as integrated components on your site
* **Advanced** - provides you with the SeamlessAccess persistence service while giving you greater control over the appearance of the service on your site, and what Identity Providers (IdPs) you include in your discovery service

## 2. Connect to SeamlessAccess

> **Who does this work?** This work is done by someone who configures your access systems for your site and the person/team that modifies the pages where sign in happens will make this change. This may be a system administrator, a software interface designer, or it could be a software developer. In some cases this work may be done by a vendor or consultant. The SeamlessAccess team will help you to identify the right person.

To implement the SeamlessAccess **Limited** or **Standard** 'flavors', you will be using the SeamlessAccess service which is a hosted instance of the thiss software. This service provides the core benefits of SeamlessAccess with minimal work. Most Service Providers (SPs) will prefer this option.

To implement the **Advanced** features, you will need to use the thiss software to run your own instance of the service.

### Connecting - "Limited" Flavor

For the the "Limited" flavor, you will implement:

* Discovery Service Integration - _Integrate the SeamlessAccess service to use it as your Discovery Service._

See the [Integration Guide](https://thiss.io/integration/) to learn how to configure your Service Provider (SP) software stack.

### Connecting - "Full" Flavor

For the "Full" flavor, you will implement:

* Discovery Service Integration - _Integrate the SeamlessAccess service to use it as your Discovery Service._
* Display of SeamlessAccess Login Button - _Use the SeamlessAccess service to display the login button component on your SP login page._
* Integration of Login Button with your SAML SP - _Integrate the SeamlessAccess service to use it as your Discovery Service._

See the [Integration Guide](https://thiss.io/integration/) for details on how to implement.

### Connecting - "Advanced" Flavor

For the "Advanced" flavor, you will implement:

* A discovery service - _either set up your own, or integrate the one provided by SeamlessAccess_
* A metadata query service - _either set up your own, or integrate the one provided by SeamlessAccess_
* The SeamlessAccess Button - _use the provided versions of the button, or work with our design team to adapt the style for your needs._
* The SeamlessAccess Persistence Service API - _Use the Persistence Service API to retrieve or store the user's cross-site preferred identity provider._

See the [Software Documentation](https://thiss.io/documentation.html) for details and examples, as well as API documentation.

## 3. Spread the word!

> **Who does this work?** This work is likely done by your communication or marketing team. It’s a great idea to get this group involved early in the project so they are ready to talk about the connection when it is ready to launch!

Once you have connected to the SeamlessAccess service, you are going to want to let others know about it. We have provided you with a suite of communication resources that you can use to help spread the word.

### Get listed on the SeamlessAccess site
Please let us know when you have implemented SeamlessAccess so that we can include you in the list of SeamlessAccess-enabled sites. This list will help other service providers and end users know who is using the service.

### Showcase your use case on the SeamlessAccess site
We also will be highlighting several SeamlessAccess-enabled sites. Your inclusion will help others to envision what they can do with the SeamlessAccess service, and also provide more exposure for the work that you put in to enable SeamlessAccess.

### Include a SeamlessAccess-enabled logo on your site
You’ve done the work; why not flaunt it! When you inform us that you have implemented SeamlessAccess, we will reply with a copy of our SeamlessAccess-enabled logo that you can add to your site. Maybe you’ll included in a blog post or tweet, or add it to your documentation about accessing your service or resources!

### Share the good news with your end users
We’ve prepared some boilerplate text that you can use when communicating with your end users. We’ve also included some suggestions on how to spread the word, and how we can help amplify your message.
