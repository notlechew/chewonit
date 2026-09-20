# chewonit

## Athens flight finder (`athens-flight-finder.html`)

A standalone HTML tool for finding cheap weekend-to-weekend airfare to Athens.

It has no live pricing feed, so instead of guessing at exact fares it:

- Generates every Friday-night / Saturday-out date for the next 12 months, each paired
  with a return exactly two weeks (configurable) later.
- Tags each week Low season / Shoulder / Peak using typical Athens demand seasonality
  (cheaper Feb–Mar and Nov, pricier Jul–Aug and the New Year week).
- Builds a one-click Google Flights and Skyscanner search link for every date pair, so
  you can pull real live prices instead of a stale snapshot.
- Surfaces the 10 weeks worth checking first, ranked by that seasonality heuristic.

Open the file directly in a browser, or publish it wherever you host static pages. The
departure airport, trip length, and Friday/Saturday preference are all editable in the
page itself.
