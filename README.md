# togeojson-cli-latin

**Note**: this is a fork of [tmcw/togeojson-cli](https://github.com/tmcw/togeojson-cli) that just changes the encoding to use, `latin1` instead of `utf8`. An idea may be to proposed to [tmcw](https://github.com/tmcw) a way to select the encoding easily. Any idea is more than welcome!

Converts KML and GPX to GeoJSON on the command line. You can provide a stream
of data from stdin, or a list of filenames. Auto-detects file types, and
if provided multiple files, concatenates them automatically.

## Instructions for this fork

Run it just once with npx:

     npx github:Coruja-Digital/togeojson-cli-latin file.kml

## Instructions for [`tmcw/togeojson-cli`](https://github.com/tmcw/togeojson-cli]

Install with yarn:

    yarn global add @tmcw/togeojson-cli

With npm:

    npm install -g @tmcw/togeojson-cli

Run it just once with npx:

    npx @tmcw/togeojson-cli file.kml
