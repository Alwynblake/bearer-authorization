# bearer-authorization

Author: Alistair Blake

This code implements a Bearer Authentication system with optional token expiry, api keys, and single use tokens.

This demonstrates an improved core bearer authorization system…
* Altered the JWT to be time sensitive (valid for 15 minutes)
* Altered the JWT to be single-use:
 1. with every authenticated access, 
 2. re-sent a new JWT token as a cookie/ header
