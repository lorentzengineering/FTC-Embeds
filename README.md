# FTC-Embeds

A IFrame library anyone can use to display FTC Stats for any team/competition

# !! Beta !!
Some features are in beta, to use beta features, use ``beta.lorentzengineering.nl`` instead of ``lorentzengineering.nl``
# Usage

To use it simply add the following to your HTML

```html
<iframe src="https://lorentzengineering.nl/iframes/<iframe>?option=value&secondOption=value"></iframe>
```
# Iframes

## Rankings (beta)
The rankings ellement will show a list of all teams in a event and the current ranking, when a team has driven more matches thant the average a warning sign will apear in front of it. <br>
To display the rankings of a competition use the following:

```html
<iframe src="https://beta.lorentzengineering.nl/iframes/rankings"></iframe>
```
### Options

| Option                | Description                                       | Default       |
|-----------------------|---------------------------------------------------|---------------|
| event                 | The event to display                              | 2223-NLD-NLMD |
| highlightTeam         | The team to highlight                             | 19444         |
| highlightColor        | The background color for the highlighted team     | 4c51bf        |
| backgroundColorEven   | The background color when the row is even         | 1a202c        |
| backgroundColorOdd    | The background color when the row is odd          | 1f2937        |
| textColor             | The text color                                    | ffffff        |
| headerColor           | The header color                                  | 111827        |
| autoScrollToTeam      | If the page should scroll to the highlighted team | true          |
| autoScrollTeamsAmount | The amount of teams above the highlighted team    | 4             |
## More comming soon
Features planned (not in order):
- [x] Rankings (beta)
- [x] Url Generator (beta)
- [ ] Matches
- [ ] Awards
- [ ] Team information


# Generator

For a generator go to: https://beta.lorentzengineering.nl/iframes/generator (beta)

