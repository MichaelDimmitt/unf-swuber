![swuber_3](https://cloud.githubusercontent.com/assets/11463275/25136927/4fd60eea-2424-11e7-989d-d6630c5b0827.png)

## Why Swuber?
It started in parking lot 14; on the way to class I asked a friend if they could give me a ride. the friend was not leaving but also going to class. As a result we walked together and not alone. Later when leaving the library I was forced to walk alone by lack of communication and lack of traffic at that hour.  

I did not want to walk to my car. I waited outside the library for someone I knew. Eventually I gave up but the idea was born. Generosity(reputation) and the capital of my parking spot could be used to get me to my car without having to walk alone. 

For years people have tried to solve the problem of finding a parking spot at the University of North Florida.
#### *We solved "the parking problem" in order to solve a "walking problem"*
<hr>

# Implementation

On a mac: 
make sure postgress is installed via homebrew.
<pre>
brew install postgresql
brew services start postgresql
</pre>

Dather dependencies and start the server
<pre>
 mix deps.get
 npm install 
 
 mix phoenix.server
</pre>
### Agenda 

1.make new pheonix app.<br>
2.implement channels into the app in order to incorporate swuber implementation.<br>
3. <br>

http://slack.elixirhq.com/phoenix/2016-06-26/
# Done so far notes
1.) look at endpoint... but dont touch<br>
2.) change channels<br>
3.) change static javascript<br>
4.) change template web page<br>

# UnfSwuber

To start your Phoenix app:

  * Install dependencies with `mix deps.get`
  * Create and migrate your database with `mix ecto.create && mix ecto.migrate`
  * Install Node.js dependencies with `npm install`
  * Start Phoenix endpoint with `mix phoenix.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.

Ready to run in production? Please [check our deployment guides](http://www.phoenixframework.org/docs/deployment).

## Learn more

  * Official website: http://www.phoenixframework.org/
  * Guides: http://phoenixframework.org/docs/overview
  * Docs: https://hexdocs.pm/phoenix
  * Mailing list: http://groups.google.com/group/phoenix-talk
  * Source: https://github.com/phoenixframework/phoenix
