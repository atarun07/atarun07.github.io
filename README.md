{
  "@context": [
    "https://www.w3.org/ns/did/v1",
    "https://w3id.org/security/suites/jws-2020/v1"
  ],
  "id": "did:web:atarun07.github.io",
  "verificationMethod": [
    {
      "id": "did:web:atarun07.github.io#owner",
      "type": "JsonWebKey2020",
      "controller": "did:web:atarun07.github.io",
      "publicKeyJwk": {
        "kty": "EC",
        "crv": "secp256k1",
        "x": "dbMgLG0UlrsgeFjB+HY7kxqhC3p6wiS7xUoyaXFZHws=",
        "y": "OWsu4cFqmdX4L4C9NW0hgjCb3qR9HjgyfrsJU6GzpY4="
      }
    }
  ],
  "authentication": [
    "did:web:atarun07.github.io#owner"
  ],
  "assertionMethod": [
    "did:web:atarun07.github.io#owner"
  ]
}
