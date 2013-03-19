shiro-ad-ssl-example
====================

An example of using Shiro to perform Active Directory authentication over SSL.

This simple example illustrates how you can configure Shiro via the shiro.ini to do authentication and authorization using Active Directory over SSL. There are a few steps to be performed before you can run the LdapSslExample#main method.

**Prerequisites:**
- An Active Directory server with some users and groups, configured to accept SSL connections.

**Instructions:**
 1. Modify src/main/java/shiro.ini, following the instructions within that file.
 2. Modify the userName and password variables of com.jhegg.reference.shiro.ldapSslExample.LdapSslExample. Those credentials will be used to authenticate. Note: this handling of credentials is insecure and in plain-text.
 3. Run LdapSslExample#main.

The output will indicate whether the user is authenticated, and whether it is authorized.
