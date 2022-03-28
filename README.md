# ADAPunkz proposals storage + review Repo

This is a repository to store markdown-formatted proposal submissions for the ADAPunkz DAO. When a proposal is submitted via the ADAPunkz website, a bot will create a PR on this repo for review by the team. Once the team agrees that the proposal is of a high enough quality to go a voting stage, the PR should be merged into master where the site API will automatically fetch options for the current voting round.

Which round is currently active is manually configured by the team, and needs to be advanced from one stage to the next by editing the value in `.round`.
