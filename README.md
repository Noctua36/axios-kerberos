# axios-kerberos
wrapper over [axios](https://github.com/axios/axios) for kerberos authentication using [kerberos](https://github.com/mongodb-js/kerberos) module. 

This is only for server side axios. Client side kerberos auth is handled by the browser itself.

Adds a request intercepter which uses [kerberos](https://github.com/mongodb-js/kerberos) to generate a client token and sets it in authorization header.

