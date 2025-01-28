# Drep
Cardano Drep file
[Uploading Donny7Lewis.jsonld…](){
  "@context": {
    "@language": "en-us",
    "CIP100": "https://github.com/cardano-foundation/CIPs/blob/master/CIP-0100/README.md#",
    "CIP119": "https://github.com/cardano-foundation/CIPs/blob/master/CIP-0119/README.md#",
    "hashAlgorithm": "CIP100:hashAlgorithm",
    "body": {
      "@id": "CIP119:body",
      "@context": {
        "references": {
          "@id": "CIP119:references",
          "@container": "@set",
          "@context": {
            "GovernanceMetadata": "CIP100:GovernanceMetadataReference",
            "Identity": "CIP119:IdentityReference",
            "Link": "CIP119:LinkReference",
            "Other": "CIP100:OtherReference",
            "label": "CIP100:reference-label",
            "uri": "CIP100:reference-uri",
            "referenceHash": {
              "@id": "CIP119:referenceHash",
              "@context": {
                "hashDigest": "CIP119:hashDigest",
                "hashAlgorithm": "CIP100:hashAlgorithm"
              }
            }
          }
        },
        "paymentAddress": "CIP119:paymentAddress",
        "givenName": "CIP119:givenName",
        "image": "CIP119:image",
        "objectives": "CIP119:objectives",
        "motivations": "CIP119:motivations",
        "qualifications": "CIP119:qualifications",
        "doNotList": "CIP119:doNotList"
      }
    },
    "authors": {
      "@id": "CIP100:authors",
      "@container": "@set",
      "@context": {
        "name": "http://xmlns.com/foaf/0.1/name",
        "witness": {
          "@id": "CIP100:witness",
          "@context": {
            "witnessAlgorithm": "CIP100:witnessAlgorithm",
            "publicKey": "CIP100:publicKey",
            "signature": "CIP100:signature"
          }
        }
      }
    }
  },
  "hashAlgorithm": "blake2b-256",
  "body": {
    "givenName": "Donny7Lewis",
    "motivations": "I studied, history, political science and philosophy.  I have traveled the world and experienced 92 countries, cultures, and people.  This education, read and lived, allows for a diverse open perspective from which to evaluate possible solutions. ",
    "objectives": "I believe in self sovereign ownership, privacy, id, and governance.  I would like to see more circularity built into every transaction from every fee to every trade.  A portion goes to develop regenerative projects and practices for the environment, known as ReFi.  I believe we have to have DeFi to have ReFi and Cardano DeFi will help create a censorship resistant self sovereign regenerative financial to humanity and the world on which humanity resides.",
    "paymentAddress": "addr1qxlnyydl424cvelry4240l3ah2xpuj98f377my8l2qude2mfxrld35gyq803rl6r32nsj0m8w4xxxp2jfafzsadg27uqpa9ejx",
    "qualifications": "I have been involved in governance both as a citizen and through being a member of many DAO's.  The operations of governance and the long term strategic thinking are the hallmarks of my consultancy that helps transition companies into the blockchain world.  ",
    "references": [
      {
        "@type": "Link",
        "label": "DAO Governance builder and web3 consultant.",
        "uri": "https://www.linkedin.com/in/donny-lewis-77b71a13/"
      },
      {
        "@type": "Identity",
        "label": "Personal website, that shows my writing and how I traveled.",
        "uri": "https://www.donnylewis.com"
      },
      {
        "@type": "Identity",
        "label": "new github repo ",
        "uri": "https://github.com/DVSLewis"
      }
    ]
  }
}
