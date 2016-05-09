### TODO
- [ ] Generate an Elixir Project using `mix`
- [ ] Link Dependencies using `mix`
- [ ] Given a (link, text), method should output XML in atom format
- [ ] When a list is provided, it should output the complete XML in atom format
- [ ] Define Tweet Entity
- [ ] Given a list Fetch Twitter Feed (limit to last 25 entries)
- [ ] Given a user Fetch Twitter Feed (limit to last 25 entries)
- [ ] Limit entries based on last fetched item (Explore the twitter API)
- [ ] Link above two Modules
- [ ] Generate a Phoenix webserver to serve data
- [ ] OAuth Authentication through Twitter
- [ ] UI to allow to create a list to user and get a link to private RSS feed
- [ ] Cache data for 15 minutes. Skip cache via "?cache=false"
- [ ] Persist Tweet Entity
- [ ] Store feed data as history for 48 hours per feed
- [ ] Extend to send email at a specific time in a day (which takes in data till 24 hours or limit to 100)
- [ ] Integrate with Amazon SES w/ above HTML Template via SMTP [https://github.com/swoosh/swoosh/tree/master/lib/swoosh/adapters](swoosh) adapter

### Future Plans
- [ ] Redirect links through the server (to track opens per user). [http://www.reganmian.net/blog/2015/09/03/sending-and-receiving-email-with-elixir/](See Example)
- [ ] Provide Analytics based on email opens and links clicked per user

### API Info
- Twitter Lists API - https://dev.twitter.com/rest/reference/get/lists/statuses
- Max Page size is 800 for lists - https://dev.twitter.com/overview/general/things-every-developer-should-know
- 3200 for user timeline
