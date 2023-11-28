---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

# The Workshop on Heterogeneous Trust in Distributed Systems

Many permissionless systems are based on a global, collective assumption about
adversarial behavior -- e.g. that less than 50% of hashing power or staked
tokens are adversarial, as in Bitcoin and Ethereum.

However, other systems, like the XRP ledger, MobileCoin, the Stellar network,
and the Anoma protocol, allow each participant to flexibly make its own
assumptions about failures and adversaries. This flexibility is useful, for
example:

- As a more egalitarian approach than proof-of-work and proof-of-stake for
  building permissionless systems, e.g. using asymmetric, trust-based quorum
  systems.
- Allowing each validator to choose its own tradeoff between performance and
  security by adjusting its quorums.
- For Oracle networks, where users may have different degrees of trust in
  different signers.
- As a more inclusive system that allows participants to coexist
  constructively, with different (or even incompatible) beliefs and
  assumptions.

The design space for heterogeneous-trust systems has attracted the attention of
several research groups, leading to disparate models and algorithms.

We would like to encourage this work to consolidate and thus move forward this
mathematically interesting and practically important field.  The workshop will
bring together researchers interested in distributed systems based on
heterogeneous trust, and help coalesce a new and active community on topic.

# Location and dates

The workshop co-located with [AFT 2023](https://aftconf.github.io/aft23/index.html)
and will take place on October 26th, 2023 in Princeton, New Jersey, at the [Friend Center](https://www.google.com/maps/place/Friend+Center+for+Engineering+Education,+7799+William+St,+Princeton,+NJ+08540/@40.3503606,-74.6534157,19.09z/data=!4m6!3m5!1s0x89c3e6c2c6e8d9f9:0x997e4572848080d8!8m2!3d40.3503041!4d-74.6526987!16s%2Fg%2F12hrg1gp3?entry=ttu) Convocation Room (Room 113; same room as AFT).

# Schedule (Eastern Daylight Time)

8:30am-9am: light breakfast

- 9am-9:30am: [David Mazières](https://www.scs.stanford.edu/~dm/), Stanford University, USA  
"Stake Reputation, Not Cryptocurrency" ([recording](https://youtu.be/5sMtaifisZA?si=3O6Z91Mb4OUikaeH))
- 9:30am-10am:[Isaac C. Sheff](https://isaacsheff.com/), Heliax  
"Chimera Chains: Cross-Domain Atomic Commits Using Heterogeneous Paxos" ([recording](https://youtu.be/LHCUR13ifSA?si=yIpQ69Wc9BwCRqVy))
- 10am-10:30am: [Mohsen Lesani](https://www.cs.ucr.edu/~lesani/), University of California, Riverside, USA  
"Open Heterogeneous Quorum Systems" ([recording](https://youtu.be/hdqfoeMmjOE?si=16FZt9c9F38Wvmny))

10:30am-11am: coffee break

- 11am-11:30am: [Orestis Alpos](https://crypto.unibe.ch/oa/), University of Bern, Switzerland  
"Bringing classical distributed protocols into the heterogeneous setting with Asymmetric Byzantine Quorum Systems"
- 11:30am-12am: [Jamie Gabbay](https://gabbay.org.uk/), Heriott-Watt University, UK  
"The semi-topology of heterogeneous consensus" ([recording](https://youtu.be/ZYk4phq3Xdo?si=7kdqZ03Y-K5QO6tn) and [slides](./gabbay.pdf))
- 12pm-12:30pm: [Kartik Nayak](https://users.cs.duke.edu/~kartik/), Duke University, USA  
"Order policy enforcement in the presence of rational parties" ([recording](https://youtu.be/5uCA6_VHnnU?si=qfrCZpm4lc3-PAMw))

12:30pm-1:30pm: lunch

- 1:30pm-2pm: [Ling Ren](https://sites.google.com/view/renling), University of Illinois at Urbana-Champaign, USA  
"Dynamic quorums in sleepy BFT" ([recording](https://youtu.be/rJkKPQrlSFg?si=2jkAX6CTQnBxn9OV))
- 2pm:2:30pm: [Srivatsan Sridhar](https://ssrivatsan97.github.io/), Stanford University, USA  
"Optimal Flexible Consensus and its Application to Ethereum" ([recording](https://youtu.be/qCZZ7SLL93s?si=gvFeBS89DRdljzYZ))
- 2:30pm-3pm: Yifan Mao, Ohio State University, USA:  
"Efficient and resilient peer-to-peer overlays for federated Byzantine agreement systems" ([recording](https://youtu.be/cvQd8cE_Fa8?si=xqfHu0T2dc42_OMC))

3pm-3:30pm: coffee break

- 3:30pm-4pm: Liron Schiff, Akamai Technologies:  
"Heterogeneous Trust with Probabilistic Witnesses" ([recording](https://youtu.be/WhS_cXo2pvM?si=fNP516gZ-rMeFaDU) and [slides](./schiff.pdf))
- 4pm-4:30pm: [Goeff Ramseyer](https://www.scs.stanford.edu/~geoff/), Stanford University, USA  
"Sisyphus: Heterogeneous and Efficient Partial Auditing of Replicated State Machines" ([recording](https://youtu.be/oByTWr7afOk?si=orDasNEGdzMi2qhy) and [slides](./ramseyer.pdf))

# Remote participation

If you would like to participate remotely, please email both organizers to get a zoom link.

# Travel grants

The [Stellar Development Foundation](https://www.stellar.org) offers a limited
number of travel grants for graduate students, with priority given to speakers
at the workshop. Please fill out the [application
form](https://forms.gle/HbzyJpzS7mKsAHjq8) to apply, indicating in the last
question in the form that you are applying for support to attend this workshop.

# Call for abstracts

We solicit submissions of talk abstracts and full papers on topics related to heterogeneous
trust in distributed systems, including but not limited to:
- Mathematical models of heterogeneous trust
- Distributed algorithms under heterogeneous-trust models, including consensus
  algorithms
- Descriptions of system designs or implementations based on heterogeneous
  trust
- Sybil resilience based on heterogeneous trust
- Peer-to-peer networking based on heterogeneous trust
- Cryptography and multi-party computation under heterogeneous trust
  assumptions
- Heterogeneous trust in reconfigurable and dynamic systems
- Social dynamics in heterogeneous trust systems

Talks will be 30 minutes + questions. Submissions can be extended abstracts
(from a few paragraphs to maximum 5 pages) or full papers (maximum 15 pages) in
a format of the author's choosing. Please send you submissions to the
organizers by email before September 22nd.

There will not be any workshop proceedings, but authors of selected submissions
will be invited to submit a paper to a journal special issue.

# Organizers

* [Christian Cachin](https://crypto.unibe.ch/cc/), University of Bern [(email)](mailto:christian.cachin@unibe.ch)
* [Giuliano Losa](https://www.losa.fr/), Stellar Development Foundation [(email)](mailto:giuliano@stellar.org)
