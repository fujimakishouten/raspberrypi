# fujimakishouten/raspberrypi

## Generate OpenVPN client certificate

```shell
easyrsa gen-req <clientName> nopass
easyrsa sign-req client <clientName>
```
