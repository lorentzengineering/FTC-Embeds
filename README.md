# FTC-Embeds

A IFrame library anyone can use to display FTC Stats for any team/competition

# IMPORTANT
This is still in beta, so the urls don't work yet. I will update this when they do.
U can still use the embeds, but you will have to use ``beta.lorentzengineering.nl`` instead of ``lorentzengineering.nl``
# Usage

To use it simply add the following to your HTML

```html
<iframe src="https://lorentzengineering.nl/iframes/<iframe>?option=value&secondOption=value"></iframe>
```
# Iframes

## Rankings

To display the rankings of a competition use the following

```html
<iframe src="https://lorentzengineering.nl/iframes/rankings"></iframe>
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
- [x] Rankings
- [ ] Matches
- [ ] Awards
- [ ] Team information
- [ ] Url Generator

# Generator

For a generator go to: https://lorentzengineering.nl/iframes/generator (comming soon)

