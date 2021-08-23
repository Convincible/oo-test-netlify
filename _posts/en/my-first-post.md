---
title: My first post
date: 2021-08-23T12:07:41.581Z
lang: en
---
## Commit

Implementation begins with making a specific, public commitment to creating a BO register and beginning to draw up initial plans as to how this may be achieved. At this stage, it is important to consider how to: identify which agencies will be involved in and leading implementation; outline programmes for involving stakeholders and data users in policy design; and decide how to sequence reforms and introduce future improvements.

> ### The economic value of beneficial ownership data in the UK
>
> In the UK, a 2019 Companies House (CH) study estimates the value of UK company data to be an average of GBP 1,100 per reuser, with an estimated total benefit between GBP 1 billion and GBP 3 billion per year3 – of which BO data constituted between GBP 40 million and GBP 120 million4 – for Companies House Service (CHS) users alone. The study explains that “more than half of the smaller intermediaries that access CH bulk data products have only been accessing these products since they became available free of charge. This suggests that access to free data has stimulated the development of new business opportunities”.
> {: .resource }

Here is a BOVS worksheet.

![]()

Here is an example of a BOVS diagram:

```json
[
  {
    "statementID": "1dc0e987-5c57-4a1c-b3ad-61353b66a9b7",
    "statementType": "entityStatement",
    "isComponent": false,
    "statementDate": "2017-11-18",
    "entityType": "registeredEntity",
    "name": "CHRINON LTD",
    "foundingDate": "2010-11-18",
    "identifiers": [
      {
        "scheme": "GB-COH",
        "id": "07444723"
      }
    ],
    "publicationDetails": {
      "publicationDate": "2018-02-13",
      "bodsVersion": "0.2",
      "publisher": {
        "name": "CHRINON LTD"
      }
    }
  },
  {
    "statementID": "019a93f1-e470-42e9-957b-03559861b2e2",
    "statementType": "personStatement",
    "isComponent": false,
    "statementDate": "2017-11-18",
    "personType": "knownPerson",
    "nationalities": [
      {
        "code": "GB"
      }
    ],
    "names": [
      {
        "type": "individual",
        "fullName": "Christopher Taggart",
        "givenName": "Christopher",
        "familyName": "Taggart"
      },
      {
        "type": "alternative",
        "fullName": "Chris Taggart"
      }
    ],
    "birthDate": "1964-04",
    "addresses": [
      {
        "type": "service",
        "address": "Aston House, Cornwall Avenue, London",
        "country": "GB",
        "postCode": "N3 1LF"
      }
    ],
    "publicationDetails": {
      "publicationDate": "2018-02-13",
      "bodsVersion": "0.2",
      "publisher": {
        "name": "CHRINON LTD"
      }
    }
  },
  {
    "statementID": "fbfd0547-d0c6-4a00-b559-5c5e91c34f5c",
    "statementType": "ownershipOrControlStatement",
    "isComponent": false,
    "statementDate": "2017-11-18",
    "subject": {
      "describedByEntityStatement": "1dc0e987-5c57-4a1c-b3ad-61353b66a9b7"
    },
    "interestedParty": {
      "describedByPersonStatement": "019a93f1-e470-42e9-957b-03559861b2e2"
    },
    "interests": [
      {
        "type": "shareholding",
        "interestLevel": "direct",
        "beneficialOwnershipOrControl": true,
        "startDate": "2016-04-06",
        "share": {
          "exact": 100,
          "minimum": 100,
          "maximum": 100
        }
      }
    ],
    "publicationDetails": {
      "publicationDate": "2018-02-13",
      "bodsVersion": "0.2",
      "publisher": {
        "name": "CHRINON LTD"
      }
    }
  }
]
```