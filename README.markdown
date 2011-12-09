# Heroku status

DEPRECATED: This functionality has been merged directly into the heroku gem, see https://github.com/heroku/heroku/blob/master/lib/heroku/command/status.rb

Displays current status of the Heroku platform.

## Installation

    $ heroku plugins:install git://github.com/geemus/heroku-status.git

## Usage

To use simply call:

    $ heroku status

If everything is currently working you should see:

    All Systems Go: No known issues at this time.

If something is wrong you will instead see something like this:

    App Operations: yellow
    Tools: green

    Elevated Error Rates
    ISSUE: At this time git push, dyno scaling, and unidling are having intermittent problems. We are investigating the problem and will post additional information as it becomes available.
