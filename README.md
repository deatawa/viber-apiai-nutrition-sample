# Viber chat bot sample using API.AI and Node.js

This is a simple chat bot, built using API.AI and Node.js, to generate a nutrition fact based on your input. The bot utilize data.gov API for [nutrition facts](https://ndb.nal.usda.gov/ndb/).

## Setup Instructions

### Pre-requisites
 1. [API.AI account](https://api.ai)
 2. [Viber Public Account](https://www.viber.com/en/public-accounts)
 3. [data.gov API key](https://api.data.gov/signup/)

See the developer guide at [developers.viber.com](https://developers.viber.com/public-accounts/index.html#access) for more details.

# Deploy to:
[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

### Steps
 1. Create a new agent in API.AI [api.ai](https://api.ai).
 1. Click on the project gear icon to see the project settings.
 1. Select "Export and Import".
 1. Select "Restore from zip". Follow the directions to restore.
 1. Select the `NutritionMaker.zip` file in this repository.
 1. Deploy this app to your preferred hosting environment.
 1. Set the "Fulfillment" webhook URL to the hosting URL.
 1. Make sure all domains are turned off.
 1. Enable Viber in the API.AI integrations panel.
 1. Provide an invocation name for the action.


## References and How to report bugs
* If you find any issues, please open a bug here on GitHub.

## License
See [License](LICENSE.md).

## Terms
Your use of this sample is subject to, and by using or downloading the sample files you agree to comply with, the [Viber API Terms of Service](https://developers.viber.com/general/api-terms-of-service/index.html/).

## Community
Viber/API.AI Developers community on [Gitter](https://gitter.im/viber/apiai-integration).