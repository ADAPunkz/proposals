# ADAPunkz proposals storage + review repo

This is a repository to store markdown-formatted proposal submissions for the ADAPunkz DAO. 

When a proposal is submitted via the ADAPunkz website, a bot will create a PR on this repo for review by the team. 

Once the team agrees that the proposal is of a high enough quality to go a voting stage, the PR should be merged into `master`, from which the site's API will automatically fetch options for the current voting round.

Rounds are manually advanced by the team, by editing the values in `round.yaml`. This allows the API to match location of current submissions and location of current active votes, to the correct folder within the `/rounds` directory.
