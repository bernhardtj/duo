Use duo with pyOTP.

Installation:

```sh
curl -O https://raw.githubusercontent.com/bernhardtj/duo/master/duo
pip3 install pyotp
```

Examples:

```sh
duo fetch duo://XXXXXXX-XXXXXXXXXXXXXXXXX > .duo
chmod 600 .duo
duo code < .duo
```
