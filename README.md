**Text in json format**

```
{
"version": {
"id": "v3.4",
"links": [
{
"href": "http://localhost:35357/v3/",
"rel": "self"
}
],
"media-types": [
{
"base": "application/json",
"type": "application/vnd.openstack.identity-v3+json"
}
],
"status": "stable",
"updated": "2015-03-30T00:00:00Z"
}
}
```


API Reference   
-------------------------------------------------------------------------
-------------------------------------------------------------------------


|Method      | URI                             |Description                                          |
|------------|---------------------------------|---------------------------------------------------  |
|GET         | /                               |Lists information about all Identity API versions.   |
|GET         | /v3                             |Shows details for the Identity API v3.               |
|POST        |  /v3/auth/tokens                | Authenticates and generates a token.                |
|GET         |  /v3/auth/tokens                |Validates a specified token.                         |
| HEAD       |  /v3/auth/tokens                |  Validates a specified token.                       |
|DELETE      |/v3/auth/tokens                  |Revokes a specified token.                           |
                                                                                     
                                                                                     

# Table Of Contents

1. Identity API v3
 
    1.1 API Versions

        1.1.1 List versions
        
        1.1.2 Show API version details
        
    1.2 Tokens
        
        1.2.1 Authenticate
        
        1.2.2 Validate token
        
        1.2.3 Check token
        
        1.2.4 Revoke token
        
2. Identity API v3 extensions

    2.1 OS-INHERIT extension (OS-INHERIT)
    
        2.1.1. List role assignments
        
        2.1.2. List roles for user
        
        2.1.3. Assign role to user
        
        2.1.4. Check role for user
        
    2.2. Key Distribution Server (KDS) extension (OS-KDS)
    
        2.2.1. Create key
        
        2.2.2. Delete key
        
        2.2.3. Generate ticket
        
        2.2.4. Get group key
        
        2.2.5. Create group
        
        2.2.6. Delete group
        
# 1. Identity API v3 (CURRENT)
**Gets an authentication token that permits access to the OpenStack services REST API.**

**Like most OpenStack projects, OpenStack Identity protects its APIs by defining policy rules based on a role-based access control (RBAC) approach. These rules are stored in a JSON policy file. The Identity service configuration file, keystone.conf, sets the name and location of this policy file. For information about Identity API protection, see Identity API protection with role-based access control (RBAC) in the OpenStack Cloud Administrator Guide.**


`[TOC]`:

 1.[Table with different attributes](https://github.com/Randive/Test/edit/master/README.md)

 2.[Image Of Lord Ganesha](https://github.com/Randive/Test/edit/master/README.md)
 
 #
 
 <html>
 <body>
 <table>
 <tr><td>Method</td><td>URI</td><td>Description</td></tr>
 <tr></tr>
 <tr><td>GET</td><td>/</td><td>Lists information about all Identity API versions.</td></tr>
 <tr><td>GET</td><td>/v3</td><td>Shows details for the Identity API v3..</td></tr>
 <tr><td>POST</td><td>/v3/auth/tokens</td><td>Authenticates and generates a token.</td></tr>
 </table>
 </body>
 </html>
 

                        
