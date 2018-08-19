---
title: API Reference

language_tabs: # must be one of https://git.io/vQNgJ
  - ruby
  - python
  - javascript
  - slate

toc_footers:
  - <a href='#'>Sign Up for a Developer Key</a>
  - <a href='https://github.com/lord/slate'>Documentation Powered by Slate</a>

includes:
  - errors

search: true
---
# Abstract

[TangleID](https://github.com/TangleID) is a decentralized identity application based on IOTA/Tangle allowing identity authentication to be much more efficiently implemented. Traditional identity verifications are subjected to high cost and low reliability due to the existence of a trusted third party and its risk of hacking. TangleID proposes a solution to self-sovereign problem using tangle. Thus, entities storing their hashes on Google Cloud, Azure, AWS, Dropbox, etc., are able to update the information on their own and to control digital assets such as cryptocurrencies by interacting with Tangle network. To facilitate user-friendly operation, TangleID provides a mobile application for the end users to hold their private keys as well as numerical addresses. Also, TangleID uses off-tangle database storage for the information maintenance. As long as a identity is notarized, the information, reputation and digital assets released on TangleID are more likely to be reliable. TangleID, aiming to optimize the process of verification with the introduction of blockchain technology and simultaneously to meet users’ need by developing a mobile App, enables trust and convenience take place in the meantime whenever identity is required to be authenticated.

# Introduction

The emerge of blockchain technology triggers our imaginations and diverse applications of decentralized distributed ledgers. Ethereum, for example, takes good use of machine-to-machine(M2M) technology and distributed records to create trusts, which is well-known as “”Smart Contract.” However, the scopes of blockchain should be further broaden, extended and reach out to more fields. Current identity authentication, resulting from the centralized managements in whether real or virtual worlds, is also faced with great challenges and expects for the new transformation.
TangleID can be the very solution to trust building by providing a secure, easy-to-use system for self-sovereign identity based on cryptographic mechanism called IOTA/Tangle. Normally, we get access to our asset management by the approval of centralized administration, which implies that verification process for the certificates can be constrained or time-consuming, and tend to sacrifice efficiency for security. However, the problems are amplified in cyberspace. More reliable trust mechanism is needed, and so is handy operation. TangleID allows each entity, such as citizen digital certificate, to have its unique identifier to manage digital assets if private key verified. In this case, the ownership of digital assets can be realized, and more excitingly, in decentralized method.
By interacting with Tangle network, an identity storing its hash of an attributed data blob(e.g. Google Cloud, Azure, AWS, Dropbox, etc.) is able to be linked to offline data storage and update its files automatically, such as adding friends, modifying profiles and posting ephemeral (short time) photos. Particularly on blockchain, the features of immutability and transparency ensures the trust take place. In the acts, a set of “footprints” is inevitably left and reinforces the existence of the entity.  
Moreover, the machine-to-machine (M2M) communication can dramatically decrease the transaction cost, whether during interview or for insurance. In this paper, we propose a more efficient solution to identity authentication using machine-to-machine verification based on IOTA/Tangle and further provide a path to self-sovereign identity in the digital world. In addition, since TangleID is involved in the digital asset management, we also develop a mobile application (APP) to enable users to keep their private keys as well as certain addresses as identifiers.

## Identity

The concept of identity, also recognized as “I” of self-consciousness, exists worldwide and impacts every individual’s network; yet, identity authentication still encounters great challenges whether in real or virtual worlds due to the centralized system and the dilemma of trust-building. Modern society tends to authorize both nations and corporations to issue credentials, such as ID cards, vehicle licenses and certificates, to indicate one’s identity. Therefore, individual is exposed to the risk of losing his/ her identity if a state is suffered from social unrest or even if he/ she just crosses state borders.
The centralized issue-mechanism also multiplies the difficulties of verifying identity because of the privacy concern. Moreover, the process of identity authentication is generally costly and time-consuming. For instance, from opening an account to savings and remittance, financial institutions put many efforts to verify the user identity to avoid frauds with the confirmation of credentials, seals and official bank statements. The same trivial process may repeat when a transaction takes place, such as real estate business or online buying. Also, insurance is another embarrassing situation. The calculation of compensation itself is complicated while the verification of the medical certificates is much more annoying.

## IOTA/Tangle

The solution we propose majorly rely on IOTA. IOTA is a revolutionary new technology to utilize a next-generation public distributed ledger, which is called “Tangle.” This new data structure based on Directed Acyclic Graph(DAG) breaks the boundaries of blockchain, neither block nor chain to implement. On Tangle, if anyone wants to make a transaction, the proof of extra two transactions are required and these two transaction are not allowed to be conflict. In other words, entities on Tangle all get involved in system maintenance by verifying transactions while miners have no roles by computing nonce.
<p align="center">
![](https://lh5.googleusercontent.com/gRJabHPHz4-oPvgkyml_SYXVUQI-qEXwN08GcZ_JJjrtsoqT92yRhMcgMGDD92029lIhozeosqz7A0dbVuVzOrp2vdWhyLDXqqMr3ixr4OX0ccb1kQBaXSHgRP1oa_Cbjhp6EHxW=s800)
</p>


## TangleID

With the Tangle-based technology, TangleID combines decentralized application(DAPP) and API service to implement self-verification by distributed, reliable, and immutable mechanics. Surprisingly, such as TCP/IP protocols and websites, this innovative solution brings no change on our habits but merely makes improvements on the underlying technology.

## New claim

  An identity storing its hash of an attributed data blob (e.g. Google Cloud, Azure, AWS, Dropbox, etc.) is able to be linked to offline data storage as well as update its files automatically, such as adding friends, modifying profiles and posting ephemeral (short time) photos. Particularly on blockchain, the features of immutability and transparency ensures the trust take place.

  Moreover, the machine-to-machine (M2M) communication can dramatically decrease the transaction cost, whether during interview or for insurance. In this paper, we propose a more efficient solution to identity authentication using machine-to-machine verification based on IOTA/Tangle and further provide a path to self-sovereign identity in the digital world. In addition, since TangleID is involved in the digital asset management, we also develop a mobile application (APP) to enable users to keep their private keys as well as certain addresses as identifiers.

  The proof-of-work also solves the problem of determining representation in majority decision making. If the majority were based on one-IP-address-one-vote, it could be subverted by anyone able to allocate many IPs. Proof-of-work is essentially one-CPU-one-vote. The majority decision is represented by the longest chain, which has the greatest proof-of-work effort invested in it. If a majority of CPU power is controlled by honest nodes, the honest chain will grow the fastest and outpace any competing chains. To modify a past block, an attacker would have to redo the proof-of-work of the block and all blocks after it and then catch up with and surpass the work of the honest nodes. We will show later that the probability of a slower attacker catching up diminishes exponentially as subsequent blocks are added. To compensate for increasing hardware speed and varying interest in running nodes over time, the proof-of-work difficulty is determined by a moving average targeting an average number of blocks per hour. If they're generated too fast, the difficulty increases.

  TangleID is a secure, easy-to-use system for self-sovereign identity, built on IOTA/Tangle. An identity can be cryptographically linked to offline data stores. Each identity is capable of storing the hash of an attributed data blob, whether on Google Cloud, Azure, AWS, Dropbox, etc., which is where all data associated with that identity is securely stored.

  Identities are capable of updating this file themselves, such as adding a profile photo or a friend, or they can also grant others temporary permission to read or write specific files. Since they can interact with Tangle network, TangleID identities can also control digital assets such as cryptocurrencies or other tokenized assets.

  A mobile app holds the user's private key and a certain address acts as their identifier. We use a novel identity recovery mechanism to let the user select friends from their contact list which gives a quorum of these friends the ability to recover the identity of the user if their mobile device is lost.


# Use Case

## End-user

TangleID allows end-users to own and control their personal identity, reputation, data, and digital assets; securely and selectively disclose their data to counterparties; access digital services without using passwords; digitally sign claims, transactions, and documents; control and send value on a Tangle; interact with decentralized operation logic; and encrypt messages and data.

## Enterprise

TangleID allows enterprises to establish a corporate identity; easily onboard new customers and employees; establish an improved and transitive Know-Your-Customer (KYC) process; build secure access-controlled environments with less friction for employees; reduce liability by not holding sensitive customer information; increase compliance; maintain a network of vendors; establish role-specific, actor-agnostic identities with specific permissions.

# Online Resources

* TangleID GitHub repository: [https://github.com/TangleID](https://github.com/TangleID)
* REST API examples: [tangleid-api-examples](https://github.com/TangleID/tangleid-api-examples)

# Essential Operations in TangleID

## New Identity or Claim

Create a new Identity or claim and then attach to Tangle:
![](https://lh4.googleusercontent.com/8HCsm8nHsqzxL1pznBoiACRdF7g5_BYbw2M8TJF9ckThhTV68nLle9WdesrV4o8r-1UcCvTYRbedyRBwzM53pCMvRWHssFqea74NCgYtkE7uHxXTUeETXdHvVWEbpHgboFDBC_23=s800)


| API Command  |              Sample API usage                    | Return value upon successful completion |
|:------------:|--------------------------------------------------|:---------------------------------------:|
| New Identity | curl http://node2.puyuma.org:8000 \ <br> -X POST \ <br> -H 'Content-Type: application/json' \ <br> -d '{"command":"new_claim", <br> "uuid": "SD9BCRDGJYWDHPTDNOPRULFWWG",\ <br> "part_a":"9JVXCXMFAMKLUQQCDACSWJVDLH",\ <br> "part_b":"9JVXCXMFAMKLUQQCDACSWJVDLH",\ <br> "exp_date":"20190101",\ <br> "claim_pic":"https://i.imgur.com/fp0xb8q.png",\ <br> "msg":"testing message"}'|0|
| New Claims | curl http://node2.puyuma.org:8000 \ <br> -X POST \ <br> -H 'Content-Type: application/json' \ <br> -d '{"command":"new_claim",\ <br> "uuid": "SD9BCRDGJYWDHPTDNOPRULFWWG",\ <br> "part_a":"9JVXCXMFAMKLUQQCDACSWJVDLH",\ <br> "part_b":"9JVXCXMFAMKLUQQCDACSWJVDLH",\ <br> "exp_date":"20190101",\ <br> "claim_pic":"https://i.imgur.com/fp0xb8q.png",\ <br> "msg":"testing message"}' | 0 |

## Recovery process when identity key is lost

We shall designate 2 co-signers when a new identity is issued, and the co-signer will help to recover all claims when an identity lost its private key. The whole scenario is illustrated as following:
<div width="50px", height="30px", align="center">
![](https://lh6.googleusercontent.com/LzIGU6sKQ505n6WFQSM0JKdycqlGmUHO1-s2nhb8N7d-4n67Uq7mPKsCpoJ-b2ACkjuSaUKEGGvBuWuPCE17xWiYmzJgdOJZJmKJT9Z0uzhJMqVgI6b7XxOm1BVKaqiaGmwlNQzc=s800)
</div>

API usage and flow for recover an identity when private key is lost, described as following:
![](https://lh6.googleusercontent.com/XWklpgLJRXR--_nbJ0euIv7C1sCr6AKRNwI2_D5ZS9c_8kDJugbZ5ix22D9NUE-7Xeqvam9IhjUP0Nb4AElGKIp0JW50P6rS_dn4djs8-zBQ44qBl3_sNuE6bPpFaiKJL6ZLPZ4h=s800)

| API Command      |              Sample API usage                    | Return value upon successful completion |
|:----------------:|--------------------------------------------------|:---------------------------------------:|
| key_lost_recover | curl http://node2.puyuma.org:8000 \ <br> -X GET \ <br> -H 'Content-Type: application/json' \ <br>-d '{"command":"key_lost_recover", \ <br> uuidp": "9JVXCXMFAMKLUQQCDACSWJVDLH", \ <br> uuids": "GJVXCXMFAMSLUQQCDACSQJVDLG"}' | 0 |

## Fetch Identity (Claims)

Fetch Identities or claims from Tangle:

![](https://lh4.googleusercontent.com/yilmurT7iJSbP0MGNwACi7pjadj96662bGamJo2ezClB79H7o58k3ShPBZPi8irpVw_GLe3G5PrSXrXwzC8wxEAk0l5s6dCtOR7UuTUBpu8z1D_nxafCp-Rlg5XxMq0Pp3i2aw3P=s800)

| API Command        |                   Sample code                           | Return value upon successful completion |
|:------------------:|---------------------------------------------------------|:---------------------------------------:|
| Fetch Claims       | curl http://node2.puyuma.org:8000 \ <br> -X POST \ <br> -H 'Content-Type: application/json' \ <br> -d '{"command":"get_all_claims", \ <br> "uuid": "SD9BCRDGJYWDHPTDNOPRULFWWG"}' | 0 |
| Fetch Claims Info. | curl http://node2.puyuma.org:8000 \ <br>-X POST \ <br> -H 'Content-Type: application/json' \ <br> -d '{"command":"get_claim_info", \ <br> "hash_txn":"DHPRSUKQDEOWFUBWBHVFRQWMOKLNI9OIHKRKZPIXLLKVENBUYIJGUWQXUNUQGEFKXXMVRVNHRKZI99999"}' | 0 |

# Sample Application using TangleID

Here is a sample application to demonstrate how a claim is associated to an identity. We assume a Bank plan to  issue a certification to John so that he can self-sovereign anywhere. The relationship is illustrated as following:
![](https://lh6.googleusercontent.com/dny46yq5aS4J4Idk5GX40cuK1i9izccdNpiGCv3oTfL6ZpS05nRXW5o-L2Gt8n-k2x9Jsi3i0uDhyEkQ3eoiB6FP_2yNnF7GnzvvZxrhcUdmqGG7Qye3geaHQKuUZ9onjyPvoKJs=s800)

```shell
#!/bin/bash
TANGLEID_HOST="http://node2.puyuma.org:8000"
UUID="KD9BCRDGJYWDHPTDNOPRULFWWG"
echo "Issue a new claim for John"
result_new_claim=`curl $TANGLEID_HOST \
 -X POST \
 -H 'Content-Type: application/json' \
 -d '{"command":"new_claim","uuid": "'$UUID'",\
       "part_a":"9JVXCXMFAMKLUQQCDACSWJVDLH",\
        "part_b":"9JVXCXMFAMKLUQQCDACSWJVDLH",\
        "exp_date":"20190101",\
        "claim_pic":"http://node0.puyuma.org/tmp/cer.jpg",\
        "msg":"A sample certification demonstration"}'`
if [ "$result_new_claim" == "0" ]; then
    echo "Succeed to make a new claim."
else
    echo "Fail to make a new claim."
fi
echo "List all John's claims:"
curl $TANGLEID_HOST \
 -X POST \
 -H 'Content-Type: application/json' \
 -d '{"command":"get_all_claims","uuid": "'$UUID'"}'
```

Reference result:
`["OTSQDZSFDDERAADSBBTJKZGZXDT9HPMTDYPRSYJGQGCHCZRPJUEVUEFW9EUZKS9QTAGVXLCCXBRBZ9999"]`

Since the new claim exists in the form of a valid IOTA transaction, we can look up the claim transaction via IOTA Explorer.
Here is an example of a pre-issued identity stored in the form of claim transaction. Once the transaction hash is obtained from applications, IOTA Explorer can browse its details.
https://thetangle.org/transaction/OTSQDZSFDDERAADSBBTJKZGZXDT9HPMTDYPRSYJGQGCHCZRPJUEVUEFW9EUZKS9QTAGVXLCCXBRBZ9999
