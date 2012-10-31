# pysmime

pysmime is a python high level library build on top of M2Crypto to work with
*Secure/Multipurpose Internet Mail Extensions (S/MIME, RFC 3851)* as M2Crypto
case study for italian digital signature.

M2Crypto is a python library wrapper built on top of OpenSSL by SWIG.

pysmime includes basic functions to sign, verify, encrypt and decrypt
files or mail messagges in PEM ASCII or DER format with very basic support to
PKCS11 smart cards by OpenSC OpenSSL pkcs11 engine (pkcs11 module).

## Documentation and examples
Documentation generated by Epydoc can be found in `docs` folder.
Some basic test cases are present in `pysmime/test/PySmimeTest.py`.

## Status
* PKCS11 support is minimal.
* The code has very little comments, the documentation is quite good.
* The tests suite is very basic and not include PKCS11 tests.
* Verify function doesn't return the original data.

## References
* [Secure/Multipurpose Internet Mail Extensions](https://www.ietf.org/rfc/rfc3851.txt)
* [OpenSSL S/MIME](https://www.openssl.org/docs/apps/smime.html)
* [M2Crypto](http://chandlerproject.org/bin/view/Projects/MeTooCrypto)
* [Programming S/MIME in Python with M2Crypto](http://svn.osafoundation.org/m2crypto/trunk/doc/howto.smime.html)
* [M2Crypto API](http://www.heikkitoivonen.net/m2crypto/api/)
* [OpenSC PKCS11 engine](https://www.opensc-project.org/opensc/wiki/engine_pkcs11)

## License
[GNU GENERAL PUBLIC LICENSE, Version 3](https://www.gnu.org/licenses/gpl.html).
