# data-on-daos 
or may we say regen-daos?

An open source repository to learn and gather data about regenerative Decentralized Autonomous Organizations (DAOs)

# What are Decentralized Autonomous Organizations?

They're **organizations** where coordination and collaboration between humans happen in order to fulfill some common goals.
They're **autonomous** because they are self governing, this is what makes them so special, because the organizations are built on top of a software (smart contract) that can be run in any computer without the presence of any government or controlling institution.
And they are **decentralized** because they are global and uncensorable. To explain this decentralization, it's important to understand 3 key points_
  1. One is _payments_ because DAOs are free to trade permissionlessly without any person or organization in the network
  2. Another one would be _workforce_ in which most daos are open to contributions from anyone willing to give their work in exchange for cryptocurrency
  3. How are decisions made in these organizations? With _open governance_: any member can propose an idea and all members can vote democratically on every decision

## What are regenerative DAOs?
(context)

# Why should we pay attention to them?

DAOs are new structures that are making human organization possible like never before and in order for them to thrive, I truly believe we need to lessen the learning curve and ease the onboarding process to Decentralized Autonomous Organizations.

Would it be of value to be able to find all DAOs that are working to regenerate our Earth, the projects that are working on solutions for a better future? In this case, this repo aims to take a closer look on the progress that each organization is making in their path. Aggregate information and make a place where the insights that people care about come together. The ultimate regen DAO mind map to understand this new paradigm of human organization. 

# The seed is planted

Different insights have been extracted and put together in the form of an analytical dashboard to understand how a DAO operates. For extended details, see file_descriptions

<details>
<summary>file_descriptions</summary>
<br>
1. datasets: folder containing all .csv files used in the notebooks
  - aragon: folder containing the .csv files from Aragon DAO
    - aragon_transhist.csv: data extracted from Etherscan (2020-10-23 to 2022-04-0)
  - bankless: folder containing the .csv files from Bankless DAO
    - bankles_gnosis_proxy.csv:
    - bankless_tokenholders.csv: 
    - bankless_transhist.csv:
    - bankless_treasury.csv:
  - gitcoin: folder containing the .csv files from Gitcoin DAO
    - gitcoin_tokenholders.csv:
  - lido: folder containing the .csv files from Lido Protocol
    - lido_transactionhist.csv:
    - lido_treasury.csv:
  - mstable: folder containing the .csv files from Mstable DAO
    - mstable_gnosis_wallet.csv: 
    - mstable_tokenholders.csv:
    - mstable_transhist.csv:
    - mstable_treasury.csv:
  - impactdaos_lang_processed.csv
2. notebooks:
  - gitcoin_votes_and_proposals.ipynb: notebook with Gitcoin's insights related to governance, topic modelling on Snapshot proposals
  - lido_transactions.ipynb:
  - mstable_contributors_index.ipynb: notebook with all classified contriburs transactions
  - mstable_votes_and_proposals.ipynb: notebook with Mstable's insights related to governance, topic modelling on Snapshot proposals
  - mstable_wallet_segmentation-4k.ipynb: notebook with supervised machine learning model of classification, segmentation of wallets in clusters to identify types of transactions related to contributors
  - mstable_wallet_segmentation_bmf.ipynb:
  - bankless_votes_and_proposals.ipynb:
  - impact_daos_topic_modelling.ipynb:
  - aragon_transactions.ipynb:
  - bankless_transactions.ipynb:
  
3. text_files: folder containing .json files extracted from snapshot with GraphQL
  - bankless_proposals.json
  - bankless_votes.json
  - cabindao_proposals.json
  - forefront_proposals.json
  - gitcoin_proposals.json
  - gitcoin_votes.json
  - giveth_proposals.json
  - goldfinch_proposals.json
  - moss_proposals.json
  - mstable_proposals.json
  - mstable_votes.json
  - oceanprotocol_proposals.json
  - poh_proposals.json
  - primedao_proposals.json
  - protein_proposals.json
  - thedreamdao_proposals.json
  - vitadao_proposals.json
  
</details>
