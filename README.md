# A global cast of characters for cryptography

Based on [this proposal](#proposal-toward-a-global-cast-of-characters-for-cryptography), here is a list of updated character names for cryptography discussions. See also: [Origins and meanings of updated names](#origins-and-meanings-of-updated-names).

| <div style="width:101px">Updated name</div> | Original name | Description (derived from [Alice and Bob](https://en.wikipedia.org/wiki/Alice_and_Bob)) |
| --- | --- | --- |
| Alix | Alice | Generic character who generally wants to exchange a message or cryptographic key with Bo. |
| Bo | Bob | Generic character who generally wants to exchange a message or cryptographic key with Alix. |
| Caro | Carol, Carlos, or Charlie | A generic third participant. |
| Chung | Chuck or Chad | A third participant, usually of malicious intent. |
| Cray | Craig | A password cracker, often encountered in situations with stored passwords. |
| Davon | Dan, Dave, or David | A generic fourth participant. |
| Eri | Erin | A generic fifth participant, but rarely used, as "E" is usually reserved for Evan. |
| Evan | Eve or Yves | An eavesdropper, who is usually a passive attacker. While they can listen in on messages between Alix and Bo, they cannot modify them. In quantum cryptography, Evan may also represent the environment. |
| Fayzi | Faythe | A trusted advisor, courier, or intermediary. Fayzi is used infrequently and is associated with faith and faithfulness. Fayzi may be a repository of key services or courier of shared secrets. |
| Frankie | Frank | A generic sixth participant. |
| Gracen | Grace | A government representative. For example, Gracen may try to force Alix or Bo to implement backdoors in their protocols. Gracen may also deliberately weaken standards. |
| Heike | Heidi | A mischievous designer for cryptographic standards, but rarely used. |
| Iva | Ivan | An issuer, mentioned first by Ian Grigg in the context of Ricardian contracts. |
| Jude | Judy | A judge who may be called upon to resolve a potential dispute between participants. |
| Malet | Mallory, Mallet, or Darth | A malicious attacker. Associated with Truva, an intruder. Unlike the passive Evan, Malet is an active attacker (often used in man-in-the-middle attacks) who can modify messages, substitute messages, or replay old messages. The difficulty of securing a system against a Malet is much greater than against an Evan. |
| Mico | Michael or Mike | Used as an alternative to the eavesdropper Evan, from microphone. |
| Niaj | Niaj | An alternative to the eavesdropper Evan in several South Asian nations. |
| Oli | Olivia | An oracle, who responds to queries from other participants. Oli often acts as a "black box" with some concealed state or information or as a random oracle. |
| Osher | Oscar | An opponent, similar to Malet, but not necessarily malicious. |
| Pema | Peggy or Pat | A prover, who interacts with the verifier to show that the intended transaction has actually taken place. Pema is often found in zero-knowledge proofs. |
| Rudo | Rupert | A repudiator, who appears for interactions that desire non-repudiation. |
| Syd | Sybil | A pseudonymous attacker, who usually uses a large number of identities. For example, Syd may attempt to subvert a reputation system. |
| Tran | Trent or Ted | A trusted arbitrator, who acts as a neutral third party. |
| Truva | Trudy | An intruder. |
| Vero | Victor or Vanna | A verifier, who requires proof from the prover. |
| Wael | Walter | A warden, who may guard Alix and Bo. |
| Wen | Wendy | A whistleblower with privileged access capable of divulging information. |

For interactive proof systems, there are other characters:

| <div style="width:110px">Updated name</div> | Original name | Description (derived from [Alice and Bob](https://en.wikipedia.org/wiki/Alice_and_Bob)) |
| --- | --- | --- |
| Artha and Merle | Arthur and Merlin | Merle provides answers, and Artha asks questions. Merle has unbounded computational ability (like the wizard Merlin). In interactive proof systems, Merle claims the truth of a statement, and Artha questions them to verify the claim. |
| Pau and Ora | Paul (after Paul Erdős) and Carole (anagram of oracle) | Pau asks questions, and Ora provides answers. In the solution of the Twenty Questions problem, Pau asked questions, and Ora answered them. Pau and Ora were also used in combinatorial games in the roles of pusher and chooser. |
| Artha and Beza | Arthur and Bertha | Artha is the left, black, or vertical player, and Beza is the right, white, or horizontal player in a combinatorial game. Additionally, Artha, given the same outcome, prefers a game to take the fewest moves. Contrarily, Beza prefers a game to take the most moves. |

### Optional citation

If you use these updated names in your work, until these names become the norm, your readers might benefit from some context. Here's a citation you can choose to include:

> This work uses [the global cast of characters for cryptography](https://github.com/jhaaaa/alix-and-bo).

## Proposal: Toward a global cast of characters for cryptography

### The history of Alice and Bob

Who are Alice and Bob? They are the first two of what would eventually grow to become a comprehensive cast of characters used to illustrate cryptographic concepts. Specifically, we use these characters in discussions about entities trying to communicate securely using cryptographic systems and protocols.  

For example, with the advent of this cast of characters, instead of saying, “Person A sends a message to Person B,” we could now say, “Alice sends a message to Bob,” humanizing and concretizing the scenario.

The original Alice and Bob characters were first documented by Ron Rivest, Adi Shamir, and Leonard Adleman in their 1978 paper, "[A Method for Obtaining Digital Signatures and Public-key Cryptosystems](https://web.williams.edu/Mathematics/lg5/302/RSA.pdf)." The fuller cast of characters was fleshed out by Bob Schneier in his 1994 book, "[Applied Cryptography: Protocols, Algorithms, and Source Code in C](https://www.wiley.com/en-us/Applied+Cryptography%3A+Protocols%2C+Algorithms+and+Source+Code+in+C%2C+20th+Anniversary+Edition-p-9781119096726)."

### Imagining the future of communication

In 1978, when Rivest, Shamir, and Adleman published their paper, there was no internet. Digital communication was a concept of science fiction. People did business in person or over the phone.

However, there were cryptographers of the time who conceived of a future in which remote digital communication would be possible—and they were planning for it.

<br/>

> I certainly imagined purely electronic offices. Or buying and selling from a home terminal. 
I rather imagined we were moving forward, technically, into a future in which either technology could be used to protect the individual, or technology could be used to assault the individual.

— Whitfield Diffie, co-inventor of [Diffie-Hellman-Merkle key exchange](https://en.wikipedia.org/wiki/Diffie%E2%80%93Hellman_key_exchange), a cryptographic method for securely exchanging encryption keys over a public network

<br/>

> I could foresee a world in which buying a loaf of bread would involve an electronic funds transfer.

— Martin Hellman, co-inventor of Diffie-Hellman-Merkle key exchange

<br/>

> But they [Diffie, Hellman, and Merkle] also had the genius of knowing what might be done to protect our privacy, to protect commerce in such a future.

— Leonard Adleman, co-inventor of the [RSA](https://en.wikipedia.org/wiki/RSA_(cryptosystem)) algorithm

### Vision becomes reality

As just one example, today, the [Transport Layer Security](https://en.wikipedia.org/wiki/Transport_Layer_Security) (TLS) protocol is used to encrypt data in transit between clients and servers. TLS supports a [range of key exchange mechanisms](https://en.wikipedia.org/wiki/Transport_Layer_Security#Key_exchange_or_key_agreement), including Elliptic Curve Diffie-Hellman (ECDHE) and Ephemeral Diffie-Hellman (DHE), both even more secure evolutions of the original Diffie-Hellman-Merkle key exchange.

When billions of people worldwide use web and mobile apps to connect and communicate, most apps use TLS to enable secure client-server communication.

Not only are we buying bread and working in "electronic offices," secure digital communication has enabled global connections at a scale that people might only have dreamt of 45 years ago.

### An update to reflect the global community

The original cast of Alice and Bob characters serves cryptography well and plays a role in helping people from around the world communicate about cryptographic topics.

**This proposal suggests updating character names to reflect the global impact of cryptography and the global community's contributions to this study and practice.**

**People can **_choose_** to use updated character names in place of original character names.**

> **Get the list**  
> See [A global cast of characters for cryptography](#a-global-cast-of-characters-for-cryptography). 

### How were the updated names selected?

Names were selected based on the following criteria:

- Enables a global community to see itself reflected in discussions when learning about, creating, and using cryptographic solutions

- Includes at least the first two letters of the original character or role name  

  This is meant to help people with recall when transitioning to using updated names.

- Lends itself to gender neutrality  

  This removes the need to specify gender unless it's integral to the topic. This can lead to simplified communication as people can use a single set of singular gender-neutral pronouns: they, their, and them and their forms.

  Use of singular gender-neutral pronouns is increasingly becoming the standard for technical documentation. See [Gender-neutral pronouns](https://developers.google.com/style/pronouns#gender-neutral-pronouns) in the "Google developer documentation style guide."

### Origins and meanings of updated names

Here's the list of updated names and their origins and meanings. I compiled names, origins, and meanings based on internet research.

I am certain this work contains flaws. For these unintentional flaws, I sincerely apologize in advance.

I humbly request the community's feedback to [help improve upon this list and correct errors](#provide-feedback).

| <div style="width:101px">Updated name</div> | Updated name origin and meaning | Original name |
| --- | --- | --- |
| Alix | Origin: French<br/>Meaning: Noble | Alice |
| Artha | Origin: Sanskrit<br/>Meaning: Riches, wealth | Arthur |
| Beza | Origin: Ethiopian/Amharic<br/>Meaning: Payment, redemption | Bertha |
| Bo | Origin: Chinese<br/>Meaning: Wave | Bob |
| Caro | Origin: Italian<br/>Meaning: Dear, precious | Carol, Carlos, or Charlie |
| Chung | Origin: Korean<br/>Meaning: Gentle, still | Chuck or Chad |
| Cray | Origin: Gaelic<br/>Meaning: Curly, prolific | Craig |
| Davon | Origin: English<br/>Meaning: Form of David, meaning beloved, friend | Dan, Dave, or David |
| Eri | Origin: Japanese<br/>Meaning: Blessed prize or reason | Erin |
| Evan | Origin: Welsh<br/>Meaning: Gift, graciousness | Eve or Yves |
| Fayzi | Origin: Arabic<br/>Meaning: Abundance | Faythe |
| Frankie | Origin: English<br/>Meaning: Free | Frank |
| Gracen | Origin: English<br/>Meaning: Steward | Grace |
| Heike | Origin: German<br/>Meaning: Estate rule | Heidi |
| Iva | Origin: Slavic<br/>Meaning: Willow | Ivan |
| Jude | Origin: English, Hebrew<br/>Meaning: Praised | Judy |
| Malet | Origin: Old Norman<br/>Meaning: Bad, unpleasant | Mallory, Mallet, or Darth |
| Merle | Origin: Estonian<br/>Meaning: Sea | Merlin |
| Mico | Origin: Native American (Choctaw)<br/>Meaning: Chief, leader | Michael or Mike |
| Niaj | Origin: Sanskrit<br/>Meaning: Knowledge, leadership, fairness | Niaj |
| Oli | Origin: Hawaiian<br/>Meaning: Song | Olivia |
| Ora | Origin: Hebrew / Latin<br/>Meaning: Light / Pray | Carole (anagram of oracle) |
| Osher | Origin: Hebrew<br/>Meaning: Happiness | Oscar |
| Pau | Origin: Chinese<br/>Meaning: Treasure, jewel | Paul |
| Pema | Origin: Tibetan<br/>Meaning: Lotus | Peggy or Pat |
| Rudo | Origin: Zimbabwe Shona<br/>Meaning: Love | Rupert |
| Syd | Origin: English<br/>Meaning: Short for Sydney | Sybil |
| Tran | Origin: Vietnamese<br/>Meaning: Peace, calm | Trent or Ted |
| Truva | Origin: Turkish<br/>Meaning: Referring to the ancient city of Troy | Trudy |
| Vero | Origin: Malagasy<br/>Meaning: A tall grass | Victor or Vanna |
| Wael | Origin: Arabic<br/>Meaning: Refuge, shelter | Walter |
| Wen | Origin: Chinese<br/>Meaning: Literature, culture, writing | Wendy |

## Provide feedback

The success of this proposal depends on constructive feedback and adoption by the 🌏🌍🌎 community.

To provide feedback on this proposal, please [open an issue](https://github.com/jhaaaa/alix-and-bo/issues).

If you support this proposal or use the updated cast of characters in your work, consider st⭐️rring this repo.

When contributing to this repo, please follow the [community code of conduct](https://github.com/jhaaaa/alix-and-bo/blob/main/CODE_OF_CONDUCT.md).

## Gratitude

- Thank you to P.S. for opening my eyes to the need for more global representation in example person names in technical documentation.

- Thank you to the "Google developer documentation style guide" for providing their list of [Example person names](https://developers.google.com/style/examples#example-person-names), which helped inspire this work.
