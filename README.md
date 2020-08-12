# kafka2slides
Have you ever wanted to build a slide deck but only have Kafka and a Google Slides account? Look no further! 

## Steps to reproduce:

First, get the bloody thing running:

* `git clone --depth=1 git@github.com:ebelliveau/kafka2slides.git`
* `cd /path/to/this\ dumpsterfire`
* Set your server info in `/path/to/this\ dumpsterfire/src/main/java/kafka2slides/App.java` at the top of the App class (it's the only classy thing in this piece of crap).
* `gradle run`

Next up, go download your credentials.json from the Google Slides API (I used "desktop app"): 

* https://developers.google.com/slides/quickstart/java

Don't even ask me for help setting up Kafka for you.

This trash heap will subscribe to the `"pitchdeck"` topic.  No, I won't change it for you.

Go publish some crap to the `pitchdeck` topic.  This dumpsterfire will magically litter your Slides account with new pitchdecks featuring whatever the hell you publish to the `pitchdeck` topic.

--
Built with 💩 in :canada: