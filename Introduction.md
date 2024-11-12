a. What is Identity Access Management?
-> Manage the access of Identity

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
