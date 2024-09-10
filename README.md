# NEAR DAO Ecosystem

This repo is for understanding the DAO (Decentralized Autonomous Organization) Ecosystem on [NEAR Protocol](https://near.org).

For a [history of DAOs on NEAR](https://nearbuilders.com/dao-map)

[NEAR DAO Builders Group Telegram link](https://nearbuilders.com/tg-dao)

## Live DAO Tooling

### Frontends

- AstraPlus Components built by [NDC](https://neardc.org) last year. Uses [Pikespeak API](https://docs.pikespeak.ai) (needed because it's hard to index proposals, comments, and all DAOs). Available on [near.social](https://near.social/astraplusplus.ndctools.near/widget/home?tab=funds&daoId=build.sputnik-dao.near&page=dao) and [dev.near.org](https://dev.near.org/astraplusplus.ndctools.near/widget/home?tab=funds&daoId=build.sputnik-dao.near&page=dao) gateway (each gateway needs to be CORS whitelisted by the team at Pikespeak). Has global DAO, DAO Feed, flow of funds, vote on multiple proposals at once. [GitHub Repo](https://github.com/near-ndc/AstraPlusPlus). Easily switch props on DAO address in URL: `/astraplusplus.ndctools.near/widget/home?tab=funds&daoId={YOURDAONAME}.sputnik-dao.near&page=dao`
- Other BOS-based components that use NEAR Social built-in NEAR API JS. I like this as I can access through different gateways, and it's easiest to fork and customize.
- [DAOs on BOS - No Middleware](https://near.social/builddao.near/widget/page.proposals.Index?daoId=impact.sputnik-dao.near) For Full Sputnik Frontend Functionality mixed with Social Profile (Proposal Creation, Adding/Removing Members) by [Build DAO](https://nearbuilders.org) - `/builddao.near/widget/page.proposals.Index?daoId={YOURDAO}.sputnik-dao.near` (works on any gateway)
- BOS-based DAO Voting only component by Evgeny of FastNEAR/NEAR Social  : https://near.social/mob.near/widget/DAO.Main
- Other BOS apps like [Mintbos](https://mintbos.vercel.app/) + [Potlock](https://bos.potlock.org/) have "act as DAO" functionality that enables you to use any button as a function call proposal (mint, list, buy NFT, deploy storefront) + (create Potlock / NEAR social profile, donate as DAO). Also adding to Potlock NextJS app ([Code Snippet](https://github.com/PotLock/potlock-nextjs-app/blob/main/src/app/_components/ActAsDao.tsx)). Tutorials coming soon.
- Multicall App https://www.multicall.app/#/app

### Tooling

- Keypom DAO Bot: https://docs.keypom.xyz/docs/next/Tutorials/Advanced/daos/introduction 
- DAO Analytics by Pikespeak.ai: https://pikespeak.ai/daos/overview
- DAO Notifications on Telegram with [LNC Watch Bot](https://t.me/lncwatchbot) (by [Learn NEAR Club](https://learnnear.club) team) to not only keep track of DAO Addresses but also all our contracts on staging + prod and wallets for Telegram notification. Here is the [tutorial](https://youtu.be/TCEcZSaCHeo?si=rgK1ylwGJ6J-jtup)

### Figma
- astra++ designs https://www.figma.com/file/oA41se1TnBuFe2AC71jguw/Astra%2B%2B-%7C-NEAR?type=design&node-id=3-3&mode=design&t=prDSAHP59ZBgp6MU-0

## Contracts

- Sputnik v2: https://github.com/near-daos/sputnik-dao-contract (Deployed Address: sputnik-dao.near https://nearblocks.io/address/sputnik-dao.near?tab=contract)
- Metapool Voting Contracts: https://github.com/Meta-Pool/meta-vote-contracts
- NDC Voting Contracts: https://github.com/near-ndc/voting-v2
- NEAR Multicall Contracts: https://github.com/near-multicall/contracts 

## Tutorials

- Creating a DAO on NEAR: https://www.youtube.com/watch?v=FzUATFR8ky4&t=1243s

## Upcoming DAO Initiatives

- DevHub in the upcoming quarter is coming with a treasury management app that simplifies payments off of SputnikDAO. [Repo](https://github.com/NEAR-DevHub/neardevhub-treasury-dashboard) 
- DAO smart actions within [Bitte Wallet](https://wallet.bitte.ai). [Repo](https://github.com/jaswinder6991/dao-agent-next) - [Recent Code Review](https://www.youtube.com/watch?v=mbECFe2txd0&t=2151s)

### House of Stake

- House of Stake is being built by some NEAR OGs and should be ready in a few months for contracts with audit [Governance Proposal](https://gov.near.org/t/near-governance-house-of-stake-proposal-by-gauntlet/39768) by Gauntlet

## Deprecated

### Frontend

- AstroDAO.com  Front End Repo https://github.com/near-daos/astro-ui
- Sputnik-fund - also a frontend maintained by LNC Club

### Contracts

- Goblin Contracts by Tonic: https://github.com/tonic-foundation/goblin-contracts
- Vostok DAO by Robert Z: https://github.com/robert-zaremba/vostok-dao

## History

- Sputnik DAO Initial Commit by Illia: https://github.com/near-daos/sputnik-dao-contract/commit/01ffd34b52d73c48e7dd397d94ad944ab2a167e9
- Start of Guilds Program (2021): https://medium.com/nearprotocol/welcome-to-the-guilded-age-of-near-protocol-4a46136c67d3
- Start of Daocubator (2022): https://x.com/DAOcubator/status/1501451457413152770
- Formation of DAO Builder Calls (late 2022)
- AstroDAO Transition RFPs: https://near.social/devhub.near/widget/app?page=post&id=2375

Other Resources
- https://github.com/near-daos
