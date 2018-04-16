# Tests

Tests for all clients.

## Format

Similar to [Ethereum tests](https://github.com/ethereum/tests).

```
{
  "pre": {
    "0x372a08b828598122fc64c4aa94735c770f25bbbc": {
      "storage": [
        "0x01"
      ],
      "code": "0x0061736d...",
      "nonce": 0
    }
  },
  "transaction": {
    "actorId": "0x372a08b828598122fc64c4aa94735c770f25bbbc",
    "nonce": 1,
    "ticks": 500000,
    "funcName": "0xd82b8482f46673746f72653280d82954372a08b828598122fc64c4aa94735c770f25bbbc00",
    "secretKey": "0x78d783b89b0de774b8fcf465d9644fb1f739875876ec3f9cad8f56947e27d141"
  },
  "post": {
    "0x372a08b828598122fc64c4aa94735c770f25bbbc": {
      "storage": [
        "0x02"
      ]
    }
  }
}
```
