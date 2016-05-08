## README

Write in Elixir

## Design

### Input
1. Twitter List
2. Twitter Profile
3. Twitter Search

### Output
1. RSS

### URL Format
1. List - `https://domain.com/t/l/sairam/rails.rss`
1. Public User - `https://domain.com/t/pu/sairam.rss` # (Public timeline)
1. Private User - `https://domain.com/t/pr/sairam.rss` # (Changes based on user querying)
1. Search - `https://domain.com/t/s/google.rss`

### Usage Limits
1. Cache response for 5-10 minutes for signed in users
1. Cache response for 1 hour for anonymous users
1. Remember history to avoid re-querying (Optimization) - Requires DataStore

### Private Links
1. Generate and store a link to associate with an Input
1. Any of the above links get associated as `https://domain.com/t/p/192kdassf9sdf23ldsa-238fda.rss`
1. The private link is different per user for the same list
