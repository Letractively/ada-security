Ada Security provides a security framework which allows applications to define
and enforce security policies.  This framework allows users to authenticate by using
[OpenID Authentication 2.0](http://openid.net/specs/openid-authentication-2_0.html)
as well as [OAuth 2.0](http://oauth.net/2/) protocol.

  * A security policy manager defines and implements the set of security rules that specify how to protect the system or the resources.
  * A user is authenticated in the application.  Authentication can be based on OpenID, OAuth or another system.
  * A security context holds the contextual information that allows the security policy manager to verify that the user is allowed to access the protected resource according to the policy rules.

![http://ada-security.googlecode.com/svn/wiki/AdaSecurity.jpg](http://ada-security.googlecode.com/svn/wiki/AdaSecurity.jpg)


## This project was moved to `GitHub`. ##

The new location is: https://github.com/stcarrez/ada-security/wiki

The Git repository is: https://github.com/stcarrez/ada-security.git

## NEWS ##

### Version 1.1.1   - Jul 2014 ###
  * Fix minor configuration issue with GNAT 2014

### Version 1.1     - Mar 2014 ###
  * New authentication framework that supports OpenID, OpenID Connect, OAuth, Facebook login
  * AWS demo for a Google, Yahoo!, Facebook, Google+ authentication
  * Support to extract JSON Web Token (JWT)
  * Support for the creation of Debian packages

### Version 1.0     - Jan 2013 ###
  * OpenID implementation based on Ada Server Faces
  * OAuth 2.0 client implementation
  * Security policy core implementation
