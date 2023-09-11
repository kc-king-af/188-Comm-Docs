 # Authentication Methods

## Username and Password

#### Use-Case
* The most common form of authentication.
* Users provide a username and a secret password.
* Often used for web applications, email accounts, and operating system logins.

#### Vulnerabilities 
* Password crackers
* Spyware such as keyboard loggers
* Intelligence gathering and guessing 

#### Best practices for strengthening
* Complex (alpha-numeric-symbolic) pass-phrases
* Best used in combination with MFA
* Passphrase rotation

## Multi-Factor Authentication (MFA)

#### Use-Case
* Combines multiple authentication methods for increased security.
* Typically involves something the user knows (e.g., password) and something the user has (e.g., a device's security application or hardware token).
* Can include biometrics as well (e.g., fingerprint scan).

#### Vulnerabilities 

#### Best Practices

## Certificate Based Authentication

#### Use-Case
* Uses digital certificates issued by a trusted certificate authority (CA) to authenticate users or devices.
* Commonly used in secure web browsing (HTTPS) and enterprise environments.

#### Vulnerabilities 

#### Best practices for strengthening

## Single Sign-On (SSO)

#### Use-Cases
* Allows users to authenticate once and gain access to multiple applications or systems without re-entering credentials
* Commonly used in organizations with third-party applications to improve user convenience
* Often implemented with OpenID Connect (OIDC), OAuth and secured APIs

#### Vulnerabilities 

#### Best Practices



## API Tokens

#### Use-Case
* Used for programmatic authentication and authorization.
* Applications or services generate tokens that users or other applications can use to access resources via APIs.
* Common in web services and RESTful APIs.

#### Vulnerabilities 

#### Best Practices

## SSH Keys

#### Use-Case
* Commonly used for secure remote shell access (SSH) to servers and devices.
* Based on public-private key pairs (PKI).
* The user's public key is stored on the server, and the private key is kept secret by the user.

#### Vulnerabilities 

#### Best practices for strengthening

## Directory Services Authentication 

#### Use-Case

* Enabling Authentication, Authorization and Accounting for networks such as VPNs.
* Commonly implemented with Kerberos or Remote Authentication Dial-In User Service(RADIUS)
* Supported by Lightweight Directory Access Protocol (LDAP)
* Radius was an early form of PKI with SSO functionality for <u>intra</u>net services

#### Vulnerabilities 

#### Best practices for strengthening



