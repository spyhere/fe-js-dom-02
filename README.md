# Attraction Authorisation

Look, our layout developers have made the form, now it’s your turn to implement simple logic. Read value from the inputs
and display the authorisation verdict in corresponding fields. For example: when the user types 90 in `weight` input it
should display `Ok` in the `Weight` display.

## Acceptance criteria:
- `Height` verdict is displayed when the value is entered in the `height` input
- If `height` less than `150` display `Too short`, if more than `200` - `Too high`, otherwise - `Ok`
- `Weight` verdict is displayed when the value is entered in the `weight` input
- If `weight` less than `40` display `Too thin`, if more than `110` - `Overweight`, otherwise - `Ok`
- If the there is a negative or no value then it should display `Awaiting`. Applied for `height` and `weight` verdicts

## Example:
https://spyhere.github.io/fe-course/js-dom-02/public/

### Hints:
- Browser events
- addEventListener

### Resources:
- Events - https://learn.javascript.ru/introduction-browser-events

Also, You can check out `solution.zip` to see my solution. Maybe you will see something interesting there
