# Azure AD B2C and HYPR True Passwordless Strong Customer Authentication Sample

This repository shows users how to configure HYPR with Azure B2C so they can have true passwordless security into their Azure AD B2C applications.

With Azure AD B2C you can integreate HYPR to provide true passwordless authentication into any of your consumer applications. 

## About HYPR

Backed by Comcast, Mastercard and Samsung, the HYPR cloud platform is designed to eliminate passwords and shared secrets across the enterprise. By replacing passwords with Public Key Encryption, HYPR removes the hackers’ primary target - forcing them to attack each device individually. With HYPR, businesses are finally able to deploy Desktop MFA and Strong Customer Authentication to millions of users worldwide.

HYPR is a cloud-first authentication platform designed to eliminate passwords and shared secrets across the enterprise. HYPR is powered by advanced Public-Key Cryptography deployed at scale across millions of users. This approach removes the hackers’ primary target – forcing them to attack each device individually while drastically increasing security.
With True Passwordless Security, businesses can finally eliminate password reuse, fraud and phishing – all while providing a lightning-fast user experience that’s easy to use and easy to deploy.

## Tools Used In Sample

1. Azure AD B2C - This is the authorization server which is also the Identity Provider for your consumer application. B2C grants access to your application after successfully verifying the user on their device with HYPR. 

2. Web and Mobile Applications - These are your mobile or web applications that you choose to protect with HYPR and Azure B2C. HYPR provides a robust mobile SDK as well as a mobile app that you can use on iOS and Android platforms to do true passwordless authentication. 

3. The HYPR Mobile App - The HYPR mobile app can be used to execute this sample if you would prefer to not use the mobile SDKs in your own mobile applications. 

4. HYPR REST APIs - You can use the HYPR APIs to do both user device registration as well as authentication. These APIs can be found here - https://apidocs.hypr.com

## Prerequisites

1. You have access to a HYPR Cloud Tenant. If you don't have access to a tenant, please go to https://get.hypr.com/free-trial

2. You have followed all of the steps in Getting Started With Custom Policies in Azure AD B2C: https://docs.microsoft.com/en-us/azure/active-directory-b2c/custom-policy-get-started?tabs=applications 

3. You have followed all of the steps in Enable Custom Policies in Custom Profile Policy in Azure AD B2C: https://docs.microsoft.com/en-us/azure/active-directory-b2c/custom-policy-custom-attributes

4. You have registered a users mobile using the HYPR REST APIs or the HYPR Device Manager in your HYPR tenant. For example, you can use the HYPR Java SDK to accomplish this task: https://docs.hypr.com/integratinghypr/docs/hypr-java-web-sdk

## Import the 


