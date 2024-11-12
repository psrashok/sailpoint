### Sailpoint
  -> SailPoint's Identity Security Cloud solution enables organizations to manage and secure real-time access to critical data and applications for every enterprise identity with an intelligent and unified approach.

 #### What is Identity Access Management?
  -> Manage the access of Identity \
  -> Identity management is a method of verifying the identities of network entities and the level of access for enterprise network resources. It helps keep IT systems, networks, and data secure.

#### What is Identity Security Breaches
   
   1. An identity security breach occurs when someone gains unauthorized access to a person's identity-related data.
   2. This can happen through a malicious attack or an accident, like leaving confidential data on an unsecured server.
   3. Identity security breaches can lead to identity theft, fraud, and other cybercrimes. Cybercriminals can use stolen information to steal money or classified information from the victim.   

#### Security Fundamentals of Sailpoint

  a. Identity landscape
    1. Identity Security Categories
    2. Identity Security Foundations

  b. Managing access
    1. Managing and Securing identities and their access
    2. Provisioning access through out the identity lifecycle

  c. Strengthen security
   1. Controls that tighten security in Identity and Access Management
   2. Managing risk in Identity Security

  d. Assess your maturity
   1. Assess your maturity

### Basics of Identity Access Management
  - Identity and access management is the framework and processes organizations use to manage and secure digital identities and control user access to critical information.
  -  Systems include user registration, identity authentication, role-based access control, and compliance auditing and reporting.
  - Identity and access management systems protect sensitive data and systems from unauthorized access and breaches while also streamlining and automating the management of users’ digital identities, access permissions, and security policies.

  ##### Core concepts related to identity and access management

      - Digital identities
      - Identity management
      - Access management
      - Identity governance
      - Multi-factor authentication (MFA)
      - Access Management
      - Authentication
      - Authorization
      - Password management
      - Provisioning
      - User Management

  ##### Introduction to IdentityIQ

    - SailPoint IdentityIQ is an identity and access management software platform custom-built for complex enterprises.
    - It delivers full lifecycle and compliance management for provisioning, access requests, access certifications, and separation of duties.
    - The platform integrates with SailPoint's extensive library of connectors to intelligently govern access to today's essential business applications.
    - Harnessing the power of AI and machine learning, SailPoint's AI Services seamlessly automate access, delivering only the required access to the right identities and technology at the right time.
    - SailPoint's comprehensive extension modules address the sophisticated needs of the large enterprise while delivering the flexibility and ease-of-deployment that customers demand.

    ##### IdentityIQ Components and Features

      - IdentityIQ Compliance Manager
      - IdentityIQ Lifecycle Manager
      - Artificial Intelligence and Machine Learning
      - Privileged Account Management Module
      - Connectors and Integration Modules
      - Cloud Access Management
      - Password Manager
      - Access Risk Management
      - SaaS Management
      - Identity Security Platform
      - Access History

  ##### Sailpoint LifeCycle Manager

      - SailPoint Lifecycle Manager (LCM) is a product that helps manage identity and access to improve security, compliance, and reduce risk
      - IdentityIQ Lifecycle Manager manages changes to user access and automates provisioning activities in your enterprise environment.\
      - The Lifecycle Manager maps directly to the lifecycle of a user in an organization and the core identity business processes associated with the user lifecycle activities.
         
         * User Lifecycle Activities – joining, moving, leaving
         * Core Identity Processes – provision, change, de-provision

  The Lifecycle Manager can be configured to enable users to make requests through IdentityIQ and control which requests they can make.

    a. Users
            Individual User – can make requests using the self-service feature
            Managers – can make requests for direct reports
            Help Desk Operators – can make requests for populations
            Other users – controls requests by all users not a part of the standard groups

    b. User Requests 
            New access – request entitlement and roles
            Account Management – create, manage, and delete accounts including enable, disable, and unlock, change and reset passwords, and track current requests
            Identity Management – create, edit, and view identities

    c. Automated Change Management Using Configurable Event Triggers
            Lifecycle Manager provides automated change management based on configurable identity lifecycle event triggers.\
            These triggers are mapped to different identity-related events in an authoritative source, typically an human resources system.\ 
            When a tracked event is detected, provisioning requests are generated.

             > For Example
              ''' When the status of an employee changes from active to terminated, this lifecycle event can be configured to trigger a deprovisioning request for all of the access associate with the employee.\ 

            If an employee's job title changes, a trigger can launch the assignment of a new business role to replace the employee's current business role.'''

    d. IdentityIQ Governance Platform
        Lifecycle Manager leverages the IdentityIQ Governance Platform to enhance compliance performance, improve security, and reduce risk.\

        SailPoint uses a combination of roles, policy, and risk to provide a framework for evaluating all requests for changes to access against predefined business policies.

            - IdentityIQ Role Model – simplifies administration of user access by providing a predefined and planned structure for requesting and validating user access based on business or IT roles.

            - IdentityIQ Policy Model – evaluates your corporate access policies during the access request and provisioning processes.

            - IdentityIQ Risk Model – reduces operational risk by using a risk-based approach to identity governance and provisioning by enabling organizations to modify change management processes.


    e. Identity Provisioning Broker
        Lifecycle Manager uses the IdentityIQ Provisioning Broker to manage the final change manage activities that are the result of self-service access requests or automated lifecycle event triggers.\
        The IdentityIQ Provisioning Broker is a key piece of the IdentityIQ architecture that enables organizations to coordinate changes to user access across different provisioning processes.\
        When a provisioning change is triggered, the provisioning broker separates each request into its component parts and determines the appropriate provisioning implementation process. Provisioning options include:

          - The SailPoint Automated Change Manager
          - 3rd-party user provisioning solutions, such as Oracle IdM
          - Service request systems, such as BMC Remedy
          - Email generated to a system administrator


b. Benefits of Sailpoint?

1.  Easy Installaiton
2.  Simple On-boarding
3.  Sailpoint provide 57+ out of the box connector (OOTB) Application/Connector
4.  Sailpoint also provides 1-Webservices connector
    <strong>Note:- 1-WebServies Connector any custom application which support/provides rest API to explore/Consume</strong>
5.  Provides lots of feature in Certification.
6.  Automatic Provisioning :- All the Identity Access management will provide the Automatic Provisioning but Sailpoint provide some additional features when compares to others which makes the Sailpoint different.
7.  Customization :- This is the very importent in Sailpoint - Sailpoint says these are my exposed API you can use this API and do whatever you want to do, our product will support what ever the customization you can do.

### Sailpoint Profiles

Sailpoint provides 3 profiles

1. Implementation :- Development - Configure custom workflows, configure Life cycle Events, Custom Rules, Customization
2. Administration :- Application OnBoarding, Configuration Certification, Policy violation, Installation, Patching
3. Support :- troubleshooting, reporting, Advance Analytics and handling incident which required whole product knowledge.

## Life Cycle Manager :-

- It includes Provisioning, Manage password and configuring events.

## Complience Manager (Governece) :-

- It's for auditng purpose, certification + policy violation + risk score

# Target System :-

- Any end system -> AD/LDAP/Azure

# Application :-

- AD target system in IIQ - I need to configure these target system in IIQ under Application
- Sailpoint provides 57+ OOTB application

# Connector :-

- bridge between IIQ(Application) and target System. Most of the coding in Sailpoint/Connector is in Java. Every application would be having atleast one connector.

- IQ Service :-

# Aggrigation :-

- Fetching the data from Target system to IIQ ->
  a. Account Aggrigation :- Fetching the accounts/users information from the target system to IIQ -> User Information includes -> attributes of the user and groups/permission/members of details.

  b. Account Group Aggegation :- Fetching group information from target system to IIQ.

- AD Read Only -> Updating the group

# Identity :-

- Users in Identity IQ
- One Identity have a multiple accounts Ex:- Ashok (AD)+LDAP+Peoplesoft+Salesforce.
  One ashok Identity is created -> All the account will be mapped to Identity.

# Account :-

- User's in Target System.

# Authoritative Application :-

    - Data from HR feed file/source application/Spource of truth.

# Non-Authoritative Application :-

    -

# Identity Cube :-
