### [Discuss]

**SELECTED**

### Pitch

Finally, an app for those of us who wish every night could be a book club night.

### Description

With Discuss, users can browse a list of books, find a good place in their neighborhood to chat, and share an invite with their social circles.

I'm planning on pulling in data from the NY Public Library Digital Collection API. Users can input a keyword and find books that match that keyword. This will spark some book ideas, as users will get a sense of what's out there to discuss. Next, users can use Google Maps to find areas of interest around them -- libraries, parks, restaurants, cafes, etc. Finally, they'll be able to take the name of the book and the name of the location they've selected, choose a date and time, and send a message to their friends inviting them to the discussion.

### Target Audience

Bookworms. Social butterflies. Single people. Etc.

### Integrations

* OAuth: Twitter
* Data: Google Maps API, New York Public Library Digital Collection API. -- was just granted access, wohoo!
* Other: Foursquare? Yelp?

### Iterations

By Tuesday, November 17 EOD: Wireframes.

By Thursday, November 20: VPS implemented. OAuth can log a user in and out. Once logged in, the user can browse and select a book based on a keyword. Book selection stays associated to the user through the database. Simple design.

By Tuesday, November 25: Integration of the location search. Users can now not only select a book but can also select a location in their area. Fancy simple design integrated.

By Sunday, November 30: When logged in, users can now browse their past book and location selections. Integration of background workers. Integration of Twitter. Majority of fancy design in place.

By Thursday, December 4: Ruby gem completed. Full functioning web app with added functionality of users sharing their selections on their social circles.

### Game plan

If things go ridiculously better than planned: Twitter bot it. Folks can tweet their zipcode and a genre to the bot, bot will tweet back location nearby and random book selection from that genre.

If things go as planned: YO, SARA. You just built a sweet app.

If NYPL API goes miserably: Scratch NYPL API integration and focus only on proximity-based searching and sharing. Include a simple text field for users to input what they're reading.

If proximity-based searching API goes miserably: I will feel very not smart.










### [Particle]

If this project gets selected, put **SELECTED** here

### Pitch

I'd like to build app that provides a book suggestion based on a user's local weather.

### Description

The plan would be for users to log in with Twitter (or Goodreads?), answer a few questions about their reading preferences and input their zip code, then the app would spit out a reading suggestion based on the weather results from their location, à la a quick Buzzfeed quiz.

### Target Audience

So many people! Bookworms would love it. Authors would love it. People stuck inside on cold, rainy days would love it. Investors would love the idea of it, as a quick quiz with one answer would prompt people to take it again and again, trying to see all the different results.

### Integrations

* OAuth: Twitter (and Goodreads?)
* Data: Weather Underground, Goodreads
* Other: Eventually, I'm thinking it'd be fun to turn this web app into a Twitter bot, where you just tweet your zip code to the bot and the bot tweets back the book suggestion.
