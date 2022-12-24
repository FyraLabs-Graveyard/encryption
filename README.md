# Notice

This is an archive of a library from another organization, used in the now defunct chat-app Octii. The code here hasn't been audited and shouldn't be used in a production enviroment or where security matters, as it is no-longer being worked on or maintained. **Please don't use this.**

Notably, the amount of PBKDF2 iterations used for deriving a key from a user's password is 100,000, which isn't secure in 2022, ~~even though [some other apps](https://bitwarden.com/help/what-encryption-is-used/#pbkdf2) still use that amount at the time being.~~

If you have any questions, please contact a staff member on Discord.

-L

# Installation

```sh
yarn add @fyralabs/inncryption
```

# License

[MIT](https://github.com/fyralabs/encryption/blob/master/LICENSE)
