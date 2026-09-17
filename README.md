# JWT Authentication Bypass via Unverified Signature

Educational demonstration of a JWT vulnerability where the server fails to verify the token signature, allowing an attacker to modify claims (e.g. `sub`, `role`) without invalidating the token.

⚠️ **For authorized testing and educational purposes only.**

## How it works
1. Capture a valid JWT
2. Modify the payload (e.g. change `sub` to an admin identifier)
3. Since the signature isn't verified server-side, the tampered token is accepted

## Usage
[installation/usage steps]
