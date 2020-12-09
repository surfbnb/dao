# SURFBNB DAO [![Build Status](https://travis-ci.org/aragon/dao-templates.svg?branch=master)](https://travis-ci.org/aragon/dao-templates)

Instead of relying on anonymous TA or Yelp reviews, users can connect with a surf industry insider who shares your likes, interests, and preferences. The site serves up curated lists of available guides in each prime surf destination and facilitates one-on-one connections. The team is working on a compensation system for ambassadors, who currently work on a volunteer basis. They are our biggest assets and we hope they can be well compensated in the future.

# Crowdsourcing travel recommendations 🧭

> Ambassadors will give you the inside scoop and users can tap into a network of insiders that offer authentique surf travel experiences. Being featured on SurfBnB is a symbol of distinction and owners can claim SBNB tokens.

We can assign customers tokens for staying in a specific hotel and they get registered in the blockchain, never expiring and redeemable at any time? By tokenising reward programmes we can enhance the exchangeability of these SBNB rewards?

Together with a bunch of innovators we are currently exploring crypto-economic models and primitives. Distributing our token to users of our products, builders that create those products and other like minded community members helps ensure the right people are incentivized. In the coming weeks/months we will handpick more people that we feel have earned a reward for the content, design or code they open-sourced.

For now we are only distributing SBNB tokens specifically to high-trust individuals invested with time in the project. If you want something to change you can step up, and make it happen. We'll work on a community-audited, specific, and highly curated outline of future token issuance and supply. There is no “team” making the decisions alone. It’s all of us who earned tokens by contributing content, design and code.

What if companies pay us in fiat and we swap to buy back tokens on honeyswap? What if Surfbnb dao buys back sbnb tokens with 50% of revenue? Demand > Offer ?

# DAOfi the SurfBnB Community 💭

SurfBnB is a community owned and operated surf travel guide. How can we best DAOfi our project? How can we best onboard a community of 70K facebook fans without the web3 UX getting in the way? Which token mechanisms can capture value?

The most exciting contrast between DAOs and traditional companies, however, is the ability for DAOs to truly live the ethos of stakeholder capitalism by including the builders, funders, and users all in the governance of the product.

Conducting a fair launch is the most important piece to this whole puzzle. Distributing the SBNB token to users of our products, builders that create those products and other like minded community members helps ensure the right people are incentivized.

Thanks to the modularity of current DAO frameworks, the sky is the limit. The point is that the building blocks are now ready — now it’s just a matter of plumbing things together!

We should go where existing communities live and supercharge them. DAOs offer new tools to attract, incentivize and reward contributions that would be very useful if embedded into existing social platforms. Onboarding should be as easy as writing your phone number and credit card. Voting should be as easy as getting a push notification and clicking a button.

## What is a template

The best way to kickstart an Aragon organization is by using a template. Templates are a set of smart contracts that will create an organization from scratch and configure it according to some provided parameters.

Because they involve smart contract code, modifying a template, even though it's usually really easy, must be done with extreme care. It is always recommended to do a third party security audit to review the template code when modified.

## Mainnet-ready templates

Aragon creates and have put most of the templates in this repo through an external audit. Despite this, they come without any guarantees; a template we consider secure today may be vulnerable to an unknown security hole discovered down the road. Moreover, once a user has created their organization, they may grant or transfer permissions in a way that makes their organization insecure.

You can find more information about template deployments and their addresses in the [deployments repo](https://github.com/aragon/deployments/tree/master/environments/mainnet).

### Aragon 0.8

With Aragon 0.8, the client has switched to the following templates:

- [Company](https://github.com/aragon/dao-templates/tree/master/templates/company): `company-template.aragonpm.eth`
- [Company-Board](https://github.com/aragon/dao-templates/tree/master/templates/company-board): `company-board-template.aragonpm.eth`
- [Membership](https://github.com/aragon/dao-templates/tree/master/templates/membership): `membership-template.aragonpm.eth`
- [Reputation](https://github.com/aragon/dao-templates/tree/master/templates/reputation): `reputation-template.aragonpm.eth`

These templates were audited as part of the 0.8 release.

### Aragon 0.7

With Aragon 0.6 and 0.7, the following templates were used by the client to create organizations for users:

- [Democracy](https://github.com/aragon/dao-templates/tree/aragon-v0.7/kits/democracy): `democracy-kit.aragonpm.eth`
- [Multisig](https://github.com/aragon/dao-templates/tree/aragon-v0.7/kits/multisig): `multisig-kit.aragonpm.eth`

These templates were audited as part of the 0.6 and 0.7 releases by WHG and Consensys Diligence.

## Build your own template!

`@aragon/templates-shared` is published on npm and contains contract, deployment, and testing utilities to help you build your own template. All of the templates in this monorepo use `templates-shared` internally.

## Help

For help and support, feel free to contact us at any time on [Spectrum](https://spectrum.chat/aragon/app-development).
