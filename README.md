# NyteByte

> Use our app to collaborate with your friends to help choose a place to eat by voting choices you and your friends picked!

## Team

  - __Product Owner__: Jonathon Lo
  - __Scrum Master__: Justin Bitely
  - __Development Team Members__: Noel Felix, Jisoo Yoon

## Table of Contents

1. [Usage](#Usage)
1. [Requirements](#requirements)
1. [Development](#development)
    1. [Installing Dependencies](#installing-dependencies)
    1. [Tasks](#tasks)
1. [Team](#team)
1. [Contributing](#contributing)

## Usage

The landing page allows creating a unique event by entering a name, location, search radius, and date/time. No account creation or signup is required. Upon creation users are redirected to a custom, human readable url where all additional event actions will take place. This url can be shared with others for collaboration.

On the event details page any user with access to the custom url can search for venues, save them as possible options, upvote existing options, and leave persistent comments on the event. The saved options are sorted by vote count and link to their Yelp page.

## Requirements

- Node 4.3.0
- Express 4.13.0 or greater
- Mongoose 4.4.4 or greater
- yelp 1.0.1 or greater
- socket.io 1.4.5 or greater

## Development

### Installing Dependencies

From within the root directory:

```sh
sudo npm install -g bower
npm install
bower install
```

### Roadmap

View the project roadmap [here](https://waffle.io/MajesticBrachiosaurus/MajesticBrachiosaurus)


## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for contribution guidelines.
See [STYLE-GUIDE.md](STYLE-GUIDE.md) for style guide.
