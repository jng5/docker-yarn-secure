# Docker Image with Secure Yarn 

Author: Julie Ng

Slim Docker Images for **_secure_** global use of [Yarn package manager](https://yarnpkg.com/) instead of [npm](https://www.npmjs.com/).

### Securely Installed 

As per the [official Yarn documentation](https://yarnpkg.com/en/docs/install#alternatives-tab), it is not recommended to install yarn via npm, because:

> npm is non-determinstic, packages are not signed, and npm does not perform any integrity checks other than a basic SHA1 hash, which is a security risk when installing system-wide apps.


### Images Compared: Jessie vs. node-7.3

To get the slimmest image possible, I experimented with different source images. Installing nodejs by hand resulted in a 17.6% smaller image.

