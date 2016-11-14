# paaaarty
Create the ultimate playlist for your paaaarty by fetching your friends top tracks (Spotify only)

--------------

## Specs

### Algorithm

#### "Party admin view"

- FB connect, retrieve event members
- configure "party type"
  - "chill", "dance", "custom"
- configure "party progression"
  - editor to describe party time slots + music type/intensity

- "send mail to event members" or "post comment to event"

#### "party guest view"

- FB connect or token based authorization
- Spotify connect
- retrieve User favorite tracks

#### Player view

- create a party playlist, etc..
  - https://developer.spotify.com/technologies/widgets/spotify-play-button/


### Technical

- TypeScript
- Node 6 (ES6)
- Express + Passeport + GraphQL
- React (Flux)
- Postgres
