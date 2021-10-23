# NFTs Money Club Card Properties

Your NFTs Money Club Card has a lot of properties. Some properties are generated randomly when you mint a card while other will be collecting important data during the process of using a card.&#x20;

&#x20;Let’s look closer to what your NFTs Money Club Card consists of.

Properties that are randomly generated during the minting process:

|   Property  |    Value    | Description                                                                                                                                                                                                                                                                                                                                                                                                          |
| :---------: | :---------: | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|    ePower   |   100-1000  | <p>Earning Power.</p><p>Earning power defines your share in community or VIP pool depending on card type you have.</p><p>You can get +100 points to your ePower by inviting other projects/artist/collections to get promoted in NFTs Money Club;</p><p>ePower value of each standard card is randomly generated during the minting process. The range is 100-1000.</p><p>VIP card has ePower = 800.</p>             |
|    vPower   |   100-1000  | <p>Voting Power.</p><p>Voting power defines how much power your voice has during the DAO voting process. This property will be used once DAO is created.</p><p>vPower value of each standard card is randomly generated during the minting process. The range is 100-1000.</p><p>VIP card has vPower = 1000.</p>                                                                                                     |
| refBonus, % |    10-25    | <p>Referral Bonus lvl1.</p><p>It’s % you’ll be getting each time when someone mints a card using your referral link.</p><p>Each time a new member mints a card using your referral link you get +1 to your refBonus until it reaches maximum value of 25%.</p><p>refBonus value of each standard card is randomly generated during the minting process. The range is 10%-25%.</p><p>VIP card has refBonus = 25%.</p> |
| Discount, % |     5-20    | <p>Discount.</p><p>It’s discount you can get on minting 3rd party’s collection in case of integration of a few lines of code into the collection’s smart contract.</p><p>Discount value of each standard card is randomly generated during the minting process. The range is 5%-20%.</p><p>VIP card has discount = 20%.</p>                                                                                          |
|   xFactor   |     1-10    | <p>Secret ingredient.</p><p>Will be used later.</p><p>xFactor value of each standard card is randomly generated during the minting process. The range is 1-10.</p><p>VIP card has xFactor = 10.</p>                                                                                                                                                                                                                  |
|     VIP     | True, False | <p>The flag that shows the type of card – standard or VIP.</p><p>When you mint a standard card you have 1% chance to get a VIP card at a price of standard. Good Luck!</p>                                                                                                                                                                                                                                           |

&#x20;

&#x20;Properties that are used to collect data during the process of using a card:

|            Property            | Starting Value |                                                               Description                                                              |
| :----------------------------: | :------------: | :------------------------------------------------------------------------------------------------------------------------------------: |
|            refCount            |        0       | Amount of referrals that used your link to mint their own card. Once this value reaches 100 your card becomes a VIP one automatically. |
|              Rank              |        0       |             <p>User rank.</p><p>Further it will reflect the user’s twitter activity during promotions and integrations;</p>            |
|          ParentTokenID         |        x       |                                                      Token ID of the parent token                                                      |
|      directRefBonusBalance     |        0       |                                Amount of ETH distributed to a user as a direct referral bonus lvl1+lvl2.                               |
| directRefBonusBalanceWithdrawn |        0       |                                            How much ETH from the value above was withdrawn.                                            |
|          pendingReward         |        0       |                                   How many ETH from pool user was rewarded with, pending to withdraw.                                  |
|          totalRewarded         |        0       |                              Total amount of ETH rewarded to user from pool (community pool or VIP pool).                              |
|           rewardDebt           |        x       |    A part of pool user cannot pretend to due to the fact that this part has been formed before the moment user joined the community.   |
|            imageHash           |        -       |          imageHash in IPFS (avatar of your card). Yes, NFTs Money Club Card will contain a picture as many other collections))         |

&#x20;

&#x20;
