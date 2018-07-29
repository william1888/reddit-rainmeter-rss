# Rainmeter RSS monitor for Reddit

By default the RSS reader shows /r/anime episode discussion threads, you can click on the individual titles to take you to the reddit thread. It can also be modified for any other subreddit.

## Usage

1. Download the latest release zip file
2. Unzip the folder and place the folder into your rainmeter skins folder, usually at C:\Users\Username\Documents\Rainmeter\Skins
3. Open rainmeter and click refresh all, the skin should show up on the list, you can then select one of the 2 provided skins

## Screenshots

The first skin is a transparent skin based on the Multimeter RSS:

Note: My desktop background is dark

![transparent](https://camo.githubusercontent.com/7e4387d0bdd15d0394ac2152579bbbcacd4a9193/68747470733a2f2f692e696d6775722e636f6d2f5664577a4365332e706e67)

The second skin is a bigger skin that you can manually refresh and collapse, its based on the RSSFEEDpack

![big](https://camo.githubusercontent.com/6c19e3309df9caeacfddfac22e35329b81276658/68747470733a2f2f692e696d6775722e636f6d2f784e725574704e2e706e67)

## Editing the RSS feed

If you wish to edit what the RSS reader shows, open the skin .ini file and look for this line:

`https://www.reddit.com/r/anime/search.rss?q=discussion+NOT+rewatch+NOT+request&restrict_sr=on&sort=new&t=all`

This is based on the reddit search, currently its searching for any thread that has "discussion" in the name and it hides anything that has "rewatch" or "request", its sorted by new.

You can simply make your own search on reddit and just add .rss after search in the url and replace your url in the .ini file, then refresh the skin.
