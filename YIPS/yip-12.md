---
yip: 12
title: Reducing the quorum for accepting proposal
status: Proposed
author: cp287 (@illlefr4u)
discussions-to: https://gov.yearn.finance/t/yip-12-reducing-the-quorum-for-accepting-proposal/578
created: 2020-07-24
---

## Simple Summary
<!--"If you can't explain it simply, you don't understand it well enough." Simply describe the outcome the proposed changes intends to achieve. This should be non-technical and accessible to a casual community member.-->
At the moment, it is difficult for the yEarn governance mechanism to achieve a quorum of 33%. For the control system to function, the threshold must be lowered so that at least some decisions can be made.

## Abstract
<!--A short (~200 word) description of the proposed change, the abstract should clearly describe the proposed change. This is what *will* be done if the YIP is implemented, not *why* it should be done or *how* it will be done. If the YIP proposes deploying a new contract, write, "we propose to deploy a new contract that will do x".-->
It is proposed to reduce the quorum threshold for accepting the proposal to 20%.
At the moment, no changes to the on-chain are necessary, since the quorum check is currently being carried out off-chain. Thus, it is enough to simply make a decision by onchain voting.

## Motivation
<!--This is the problem statement. This is the *why* of the YIP. It should clearly explain *why* the current state of the protocol is inadequate.  It is critical that you explain *why* the change is needed, if the YIP proposes changing how something is calculated, you must address *why* the current calculation is innaccurate or wrong. This is not the place to describe how the YIP will address the issue!-->
At the moment, it is difficult for the yEarn governance mechanism to achieve a quorum of 33%. We could observe this even with the important proposal 1, which could not reach the quorum.
This is due to both:

- general passivity and lack of motivation to participate in governance system;
- negative motivation to participate (lock of funds).

Thus, yEarn protocol is under the threat of forever remaining as it is, since all proposals may not reach the required quorum (with a high probability, the activity in voting will only decrease over time).

There are many different solutions, which I will describe below, and I propose to start discussing them in the topic, but it is critical now to make a simple decision that will allow the protocol to evolve, and the community to make decisions on the development of the protocol.
In my opinion, such a decision may be to reduce the quorum threshold to 20%, which I put up for voting.

Other ways to solve the quorum problem:

- you get rewards for staking only if you vote;
- delegation of votes (implementation will take some time);
- quorum should be not for ALL tokens, but for only those “escrowed” to be voting;
- should have a quorum schedule which after x amount of time with no proposal meeting quorum the threshold goes down 1%-2% for year1, 0.5%-1% for year 2, etc.

**FOR**: The threshold for accepting the proposal drops to 20%.

**AGAINST**: No change for threshold.

## Copyright
Copyright and related rights waived via [CC0](https://creativecommons.org/publicdomain/zero/1.0/).
