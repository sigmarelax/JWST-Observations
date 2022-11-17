# James Webb Space Telescope Observation Tracker

This is a tracking tool for the James Webb Space Telescope. Using [observation schedules published by the Space Telescope Science Institute](https://www.stsci.edu/jwst/science-execution/observing-schedules), it will query for new observation events and create mastodon posts when one is occurring.

this is a port of the twitter bot below:
https://github.com/lauzadis/JWST-Observations
https://twitter.com/JWSTObservation

## Usage

0. Clone the repository to your machine.
1. Install the necessary dependencies with `pip install .`
2. Set up your .env file with mastodon access token
3. Run the tool using `python3 src/main.py`