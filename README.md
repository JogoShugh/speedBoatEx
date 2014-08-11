# Clarity PPM Speed Boat Exercise

# Agenda

* First half-hour is for individuals to consider the ClarityOne project. The metaphor: If ClarityOne were a speedboat on the ocean of Agile, heading to the island of “agile en el paraíso”, what were the anchors that slowed us down. The “anchors” that slow the speedboat down can be practices, tools, or technology, so try to cover all of these. I will have the GTM open so people can ask questions
* Second hour. Play the on-line Speedboat game together. People will place their anchors on the board and use the Innovation Games System to discuss and consider. Ian will have the GTM open, just as a back-up in case of communication issues but please expect to use the “chat” built into the game.

# Josh

## Anchors

* Nearly constant churn of Dave passing along *`a few tweaks`*, resulting in needing to rebaseline testing images
* Lack of *`Clarity`* as to when is appropriate to be experimental with using new languages, such as Scala. However, while this did slow things down a bit, it also didn't get out of hand, because after the experimentation, we realized it was not the best approach for the near-term.
 * On balance, I'd rather "fail fast" through experiments like that, than feel like we should never try new languages.
* Delaying the `Get stuff installed; Snapshot the image; Use it as the baseline` environment automation sweet spot for too long. We spent too long wishing and praying for the perfect world of downloading VersionOne and automating its installation from step 0, that every environment build took 30 to 45 minutes, even when failing, which was the worst.
 *  Instead, when we decided to be pragmatic about automation, we achieved 95% of the benefits with very little down side. As a side-benefit, we worked with Dan Gilkerson and Tom Hall about longer-term solutions for cloud V1 automation, [documented here](https://github.com/versionone/VersionOne.ChocolateyPackage/blob/master/DanGNotes.md#devops-notes).
 
## Winds and motors

Is this just about anchors? What about the winds in our sails and gas in our engine?

* Amitai and Valentin working on automation, from integration tests, to smoke tests -- bringing both the practical approach, and experience in tools we don't normally use
* Having someone as Feature Lead on the project, Acey, who brought both deep VersionOne integration project background (both technically and managerially)
* Mariano figuring out awesome Powershell remoting and other techniques that I was able to build upon to eliminate Bash scripts entirely
* Python SDK's simplicity and power for creating test data and outputting data to flow into XOG


