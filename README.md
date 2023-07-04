
## Why use JBot?

* Provides you with __all the boilerplate code__ which handles underlying websocket connections and other complexities.
* Supports __extra events__ in addition to all the events supported by Slack/Facebook which makes your work a lot more easier.
* __Receiving & sending messages__ is as easy as defining a `@Controller` and calling `reply()`.
* __Conversation feature__ of JBot makes talking to your bot a breeze. This feature makes JBot different than rest of the Java frameworks out there.
* __Well tested__ with good coverage unit tests.
* And many other features which can't just be mentioned here.

**Not satisfied?** Read on...

* JBot got more than __400 stars__ in just 2 days after release.
* It is in the [Hacker News](https://news.ycombinator.com/item?id=12239667) 50 club.
* Chosen by [DZone daily picks](http://mailer.dzone.com/display.php?M=15184241&C=dcebb6887365120539df1fbf19a071ed&S=9043&L=658&N=4604).
* Last but not the least, it's listed on [Slack.com](https://api.slack.com/community)

**Still worried?** Open an [issue on Github](https://github.com/rampatra/jbot/issues) and we can discuss.

## JBot for Slack

**Running your SlackBot is just 4 easy steps:**
  
1. Clone this project `$ git clone https://github.com/rampatra/jbot.git`.  
2. [Create a slack bot](https://my.slack.com/services/new/bot) and get your slack token.  
3. Paste the token in [application.properties](/jbot-example/src/main/resources/application.properties) file.  
4. Run the example application by running `JBotApplication` in your IDE or via commandline: 
    ```bash
    $ cd jbot
    $ mvn clean install
    $ cd jbot-example
    $ mvn spring-boot:run
    ```

You can now start talking with your bot ;)

Read the detailed [Slack documentation](https://blog.rampatra.com/how-to-make-a-slack-bot-in-java) to learn more.