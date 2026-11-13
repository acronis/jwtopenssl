# jwtopenssl

[![Go Reference](https://pkg.go.dev/badge/github.com/acronis/jwtopenssl.svg)](https://pkg.go.dev/github.com/acronis/jwtopenssl)

OpenSSL-based signing methods (RS256/384/512, HS256/384/512) for [golang-jwt/jwt](https://github.com/golang-jwt/jwt) v4. Importing the package replaces the standard methods with the ones backed by [github.com/acronis/openssl](https://github.com/acronis/openssl).

Versions before v0.2.0 work with the abandoned `github.com/dgrijalva/jwt-go`.

The package links against Acronis' own OpenSSL 1.0 build, see [acronis/openssl](https://github.com/acronis/openssl#build-requirements).
