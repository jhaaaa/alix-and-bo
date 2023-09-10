# A cross-cultural cast of characters for cryptography

Based on [this proposal](#toward-a-cross-cultural-cast-of-characters-for-cryptography) that is open to community feedback, this is a list of updated character names for use in cryptography. Descriptions are derived from [Alice and Bob](https://en.wikipedia.org/wiki/Alice_and_Bob), as documented on Wikipedia.

| Updated name | Original name | Description |
| --- | --- | --- |
| Alix | Alice | Generic character who generally wants to exchange a message or cryptographic key with Bodhi. |
| Bodhi | Bob | Generic character who generally wants to exchange a message or cryptographic key with Alix. |
| Caro | Carol, Carlos, or Charlie | A generic third participant. |
| Chung | Chuck or Chad | A third participant, usually of malicious intent. |
| Cray | Craig | A password cracker, often encountered in situations with stored passwords. |
| Davon | Dan, Dave, or David | A generic fourth participant. |
| Eri | Erin | A generic fifth participant, but rarely used, as "E" is usually reserved for Evan. |
| Evan | Eve or Yves | An eavesdropper, who is usually a passive attacker. While they can listen in on messages between Alix and Bodhi, they cannot modify them. In quantum cryptography, Evan may also represent the environment. |
| Fayzi | Faythe | A trusted advisor, courier, or intermediary. Fayzi is used infrequently, and is associated with faith and faithfulness. Fayzi may be a repository of key service or courier of shared secrets. |
| Frankie | Frank | A generic sixth participant. |
| Gracen | Grace | A government representative.For example, Gracen may try to force Alix or Bodhi to implement backdoors in their protocols. Gracen may also deliberately weaken standards. |
| Heike | Heidi | A mischievous designer for cryptographic standards, but rarely used. |
| Iva | Ivan | An issuer, mentioned first by Ian Grigg in the context of Ricardian contracts. |
| Jude | Judy | A judge who may be called upon to resolve a potential dispute between participants. |
| Malet | Mallory, Mallet, or Darth | A malicious attacker. Associated with Truva, an intruder. Unlike the passive Evan, Malet is an active attacker (often used in man-in-the-middle attacks), who can modify messages, substitute messages, or replay old messages. The difficulty of securing a system against a Malet is much greater than against an Evan. |
| Mico | Michael or Mike | Used as an alternative to the eavesdropper Evan, from microphone. |
| Niaj | Niaj | An alternative to the eavesdropper Evan in several South Asian nations. |
| Oli | Olivia | An oracle, who responds to queries from other participants. Oli often acts as a "black box" with some concealed state or information, or as a random oracle. |
| Osher | Oscar | An opponent, similar to Malet, but not necessarily malicious. |
| Pema | Peggy or Pat | A prover, who interacts with the verifier to show that the intended transaction has actually taken place. Pema is often found in zero-knowledge proofs. |
| Rudo | Rupert | A repudiator, who appears for interactions that desire non-repudiation. |
| Syd | Sybil | A pseudonymous attacker, who usually uses a large number of identities. For example, Syd may attempt to subvert a reputation system. |
| Tran | Trent or Ted | A trusted arbitrator, who acts as a neutral third party. |
| Truva | Trudy | An intruder. |
| Vero | Victor or Vanna | A verifier, who requires proof from the prover. |
| Wael | Walter | A warden, who may guard Alix and Bodhi. |
| Wen | Wendy | A whistleblower with privileged access capable of divulging information. |

For interactive proof systems, there are other characters:

| Updated name | Original names | Description |
| --- | --- | --- |
| Artha and Merle | Arthur and Merlin | Merle provides answers, and Artha asks questions. Merle has unbounded computational ability (like the wizard Merlin). In interactive proof systems, Merle claims the truth of a statement, and Artha (like King Arthur), questions them to verify the claim. |
| Pau and Ora | Paul (standing in for Paul Erdős) and Carole (an anagram of oracle) | Pau asks questions, and Ora provides answers. In the solution of the Twenty Questions problem, Pau asked questions (standing in for Paul Erdős) and Ora answered them (as an abbreviation for "oracle"). Pau and Ora were also used in combinatorial games, in the roles of pusher and chooser. |
| Artha and Beza | Arthur and Bertha | Artha is the "left", "black", or "vertical" player, and Beza is the "right", "white", or "horizontal" player in a combinatorial game. Additionally, Artha, given the same outcome, prefers a game to take the fewest moves. Contrarily, Beza prefers a game to take the most moves. |

## Proposal: Toward a cross-cultural cast of characters for cryptography

### The history of Alice and Bob

Who are Alice and Bob? They are the first two of what would eventually grow to become a comprehensive cast of characters used to illustrate cryptography concepts. Specifically, these characters are used in discussions about people trying to communicate securely using cryptographic systems and protocols.  

With the advent of this cast of characters, instead of saying “Person A sends a message to Person B,” we were now able to say “Alice sends a message to Bob,” humanizing and concretizing the scenario.

The original Alice and Bob characters were invented by Ron Rivest, Adi Shamir, and Leonard Adleman in their 1978 paper, "[A Method for Obtaining Digital Signatures and Public-key Cryptosystems](https://web.williams.edu/Mathematics/lg5/302/RSA.pdf)." The fuller cast of characters was fleshed out by Bob Schneier in his 1994 book  "[Applied Cryptography: Protocols, Algorithms, and Source Code in C](https://www.wiley.com/en-us/Applied+Cryptography%3A+Protocols%2C+Algorithms+and+Source+Code+in+C%2C+20th+Anniversary+Edition-p-9781119096726)".

### Imagining the future of communication

In 1978, there was no internet. Digital communication was a concept of science fiction. Business was done in person or over the phone.

However, there were cryptographers of the time who conceived of a future in which remote digital communication would be possible.

> I certainly imagined purely electronic offices. Or buying and selling from a home terminal. 
I rather imagined we were moving forward, technically, into a future in which either technology could be used to protect the individual, or technology could be used to assault the individual.

—Whitfield Diffie, co-inventor of [Diffie-Hellman key exchange](https://en.wikipedia.org/wiki/Diffie%E2%80%93Hellman_key_exchange), a cryptographic method for securely exchanging encryption keys over a public network

> I could foresee a world in which buying a loaf of bread would involve an electronic funds transfer.

—Martin Hellman, co-inventor of Diffie-Hellman key exchange

> But they [Diffie and Hellman] also had the genius of knowing what might be done to protect our privacy, to protect commerce in such a future.

—Leonard Adleman, co-inventor of the [RSA](https://en.wikipedia.org/wiki/RSA_(cryptosystem)) algorithm

### The vision becomes reality

As just one example, in 2023, the Transport Layer Security (TLS) protocol is used to encrypt communications between clients and servers. TLS supports a range of key exchange mechanisms, including Elliptic Curve Diffie-Hellman (ECDHE) and Ephemeral Diffie-Hellman (DHE), both even more secure variants of the original Diffie-Hellman key exchange.

When billions of people around the world use apps like Facebook and Gmail to communicate, the apps use TLS as a part of making these digital connections.

Not only are we buying bread and working from home, but secure digital communication has enabled cross-cultural connection at a scale the creators of Alice and Bob might only have dreamed of 45 years ago.

### Honoring Alice and Bob with a cross-cultural update

The original cast of Alice and Bob characters has served cryptography incredibly well and played a huge role in bringing the world closer together through secure digital communication.

This post proposes that we honor the success of Alice and Bob by updating character names to reflect the global community they nurtured. People can choose to use these updated character names in place of the original character names.

> These updated names are meant to continue to foster cross-cultural exchanges, enabling more people to feel welcome when learning about, creating, and using cryptographic solutions.

These updated names are also meant to lend themselves to gender neutrality, enabling people to use the pronouns ”they,” ”their,” and ”theirs” whenever possible. This removes the burden of specifying gender in discussons unless it is integral. This can lead to simplified communication.

Updated names were selected based on the ability to retain use of the first two letters of the original name or actor to aid in recall when transitioning to using updated names.

> **Get the list**  
> For the list of ***proposed*** updated names, see [A cross-cultural cast of characters for cryptography](#a-cross-cultural-cast-of-characters-for-cryptography). 

### Origins and meanings of updated names

Here is the list of ***proposed*** updated names along with their origins and meanings. I compiled names, origins, and meanings based on internet research. I am certain this work must contain flaws.

For these flaw, I sincerely apologize in advance. I humbly request the community's feedback to improve upon this list and help rectify errors.

| Updated name | Origin and meaning |
| --- | --- |
| Alix | Origin: French <br/> Meaning: Noble |
| Artha | Origin: Sanskrit<br/> Meaning: Riches, wealth |
| Beza | Origin: Ethiopian/Amharic<br/> Meaning: Payment, redemption |
| Bodhi | Origin: Sanskrit<br/> Meaning: Awakening, enlightenment |
| Caro | Origin: Italian<br/> Meaning: Dear, precious |
| Chung | Origin: Korean<br/> Meaning: Gentle, still |
| Cray | Origin: Gaelic<br/> Meaning: Curly, prolific |
| Davon | Origin: English<br/> Meaning: Form of David, meaning beloved, friend |
| Eri | Origin: Japanese<br/> Meaning: Blessed prize or reason |
| Evan | Origin: Welsh<br/> Meaning: Gift, graciousness |
| Fayzi | Origin: Arabic<br/> Meaning: Abundance |
| Frankie | Origin: English<br/> Meaning: Free |
| Gracen | Origin: English<br/> Meaning: Steward |
| Heike | Origin: German<br/> Meaning: Estate rule |
| Iva | Origin: Slavic<br/> Meaning: Willow |
| Jude | Origin: English, Hebrew<br/> Meaning: Praised |
| Malet | Origin: Old Norman<br/> Meaning: Bad, unpleasant |
| Merle | Origin: Estonian<br/> Meaning: Sea |
| Mico | Origin: Native American (Choctaw)<br/> Meaning: Chief, leader |
| Niaj | Origin: Sanskrit<br/> Meaning: Knowledge, leadership, fairness |
| Oli | Origin: Hawaiian<br/> Meaning: Song |
| Ora | Origin: Hebrew / Latin<br/> Meaning: Light / Pray |
| Osher | Origin: Hebrew<br/> Meaning: Happiness |
| Pau | Origin: Chinese<br/> Meaning: Treasure, jewel |
| Pema | Origin: Tibetan<br/> Meaning: Lotus |
| Rudo | Origin: Zimbabwe Shona<br/> Meaning: Love |
| Syd | Origin: English<br/> Meaning: Short for Sydney |
| Tran | Origin: Vietnamese<br/> Meaning: Peace, calm |
| Truva | Origin: Turkish<br/> Meaning: Referring to the ancient city of Troy |
| Vero | Origin: Malagasy<br/> Meaning: A tall grass |
| Wael | Origin: Arabic<br/> Meaning: Refuge, shelter |
| Wen | Origin: Chinese<br/> Meaning: Literature, culture, writing |

> **🌐 Gratitude**  
> Thank you to Sonnet Phelps for opening my eyes to the need for cross-cultural representation in example person names used in technical documentation.
>
>Thank you also to the “Google developer documentation style guide” for providing their list of [Example person names](https://developers.google.com/style/examples#example-person-names), which served as a model for this list.