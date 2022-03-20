# karmabot
```mermaid
flowchart TD
team-member--makes-command-->shibe-points--allocated-to-community-member-->community-member
community-member-->banks-points
community-member-->spends-points
community-member-->gambles-points
gambles-points-->wins
wins-->banks-points
gambles-points-->loses-->points-deducted
spends-points-->points-deducted
community-member-->enters-raffle-->wins
community-member-->enters-raffle-->loses-->no-point-loss
community-member-->donates-points-->points-deducted
spends-points------>nfts/whatever-else
nfts/whatever-else-->can-be-burnt/traded-in
can-be-burnt/traded-in--deflationary-->2-traded-for-one-better-one
nfts/whatever-else-->traded-on-opensea/in-game?
banks-points--->shows-up-on-lb
points-deducted-->shows-up-on-lb
```
