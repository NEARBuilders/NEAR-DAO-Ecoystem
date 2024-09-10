# NEAR-DAO-Ecoystem
This repo is for understanding the DAO (Decentralized Autonomous Organization) Ecosystem on NEAR Protocol.

For a [history of DAOs on NEAR](nearbuilders.com/dao-map)
[NEAR DAO Builders Group tg link](nearbuilders.com/tg-dao) 


# Live DAO Tooling
## FrontEnds
- AstraPlus Components built by [NDC](https://neardc.org) last year. uses [Pikespeak API](docs.pikespeak.ai) (needed because hard to index proposals, commnets, and all DAOs), available on [near.social](https://near.social/astraplusplus.ndctools.near/widget/home?tab=funds&daoId=build.sputnik-dao.near&page=dao) and [dev.near.org](https://dev.near.org/astraplusplus.ndctools.near/widget/home?tab=funds&daoId=build.sputnik-dao.near&page=dao) gateway (each gateway needs to be CORS whitelisted by team at Pikespeak) - has global DAO, DAO Feed, flow of funds, vote on multiple proposals at once; [Github Repo](https://github.com/near-ndc/AstraPlusPlus) .easily switch props on DAO address in URL - /astraplusplus.ndctools.near/widget/home?tab=funds&daoId={YOURDAONAME}.sputnik-dao.near&page=dao
- Other BOS Based components that use NEAR Social built in NEAR API JS. I like this as i can access through different gateways and easiest to fork and customize
- [DAOs on BOS - No Middleware](https://near.social/builddao.near/widget/page.proposals.Index?daoId=impact.sputnik-dao.near) For Full Sputnik FrontEnd Functionality mixed with Social Profile (Proposal Creation, Adding / Removing Members) by [Build DAO](https://nearbuilders.org) - /builddao.near/widget/page.proposals.Index?daoId={YOURDAO}.sputnik-dao.near (works on any gateway)
- Evegeny of FastNEAR/NEAR Social made this BOS based DAO Voting only component https://near.social/mob.near/widget/DAO.Main
- Other BOS apps like [Mintbos](https://mintbos.vercel.app/) + [Potlock](https://bos.potlock.org/) have act as DAO functionality that enable you to use any button as a function call proposal (mint, list, buy NFT, deploy storefront) + (create potlock / near social profile, donate as DAO), also adding to Potlock NextJS app ([Code Snippet](https://github.com/PotLock/potlock-nextjs-app/blob/main/src/app/_components/ActAsDao.tsx)). Tutorials soon.


## Tooling
- Keypom DAO Bot https://docs.keypom.xyz/docs/next/Tutorials/Advanced/daos/introduction 
- DAO Anlaytics by Pikespeak.ai https://pikespeak.ai/daos/overview
- DAO Notifications on Telegram with [LNC Watch Bot](https://t.me/lncwatchbot) (by [Learn NEAR Club](https://learnnear.club) team) to not only keep track of DAO Adresses but also all our contracts on staging + prod and wallets for telegram notification. Here is the [tutorial](https://youtu.be/TCEcZSaCHeo?si=rgK1ylwGJ6J-jtup)

## Figma


# Contracts
- Sputnik v2 https://github.com/near-daos/sputnik-dao-contract :Deployed Address sputnik-dao.near https://nearblocks.io/address/sputnik-dao.near?tab=contract
- Metapool Voting Contracts https://github.com/Meta-Pool/meta-vote-contracts
- NDC Voting Contracts https://github.com/near-ndc/voting-v2
- NEAR Multicall Contracts https://github.com/near-multicall/contracts 

# Tutorials
- Creating a DAO on NEAR https://www.youtube.com/watch?v=FzUATFR8ky4&t=1243s



# Upcoming DAO Initaitives
- - DevHub in upcoming quarter is coming also with a treasurey management app that simplifies payments off of SputnIkDAO. [Repo](https://github.com/NEAR-DevHub/neardevhub-treasury-dashboard) 
- DAO smart actions within [Bitte Wallet](https://wallet.bitte.ai).  [Repo](https://github.com/jaswinder6991/dao-agent-next) - [Recent Code Review](https://www.youtube.com/watch?v=mbECFe2txd0&t=2151s)

### House of Stake
- House of Stake is being built by some NEAR OGs and should be a few months for contracts w audit
- House of Stake Governance Proposal by Gauntlet https://gov.near.org/t/near-governance-house-of-stake-proposal-by-gauntlet/39768

# Deprecated

## Frontend
- AstroDAO.com
- Sptunik-fund - also a front end mantained by LNC Club

## Contracts
- Goblin Contracts by Tonic https://github.com/tonic-foundation/goblin-contracts
- Vostok DAO by Robert Z https://github.com/robert-zaremba/vostok-dao

# History
- Sputnik DAO Initial Commit by Illia https://github.com/near-daos/sputnik-dao-contract/commit/01ffd34b52d73c48e7dd397d94ad944ab2a167e9
- Start of Guilds Program (2021) https://medium.com/nearprotocol/welcome-to-the-guilded-age-of-near-protocol-4a46136c67d3
- Start of Daocubator (2022) https://x.com/DAOcubator/status/1501451457413152770
- Formation of DAO Builder Calls (late 2022)
- - AstroDAO Transition RFPs https://near.social/devhub.near/widget/app?page=post&id=2375

