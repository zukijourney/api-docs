# zukijourney-api <--> V2.5 Documentation

Welcome to the zukijourney api -- the largest multi-ai api of its kind! This guide provides a comprehensive overview of all essential facets of the API's operation. The documentation is generally kept 100% up-to-date and should be regarded as the definitive source of information.

This API was developed to mirror the full capabilitie and formatting of the OpenAI API. Consequently, the OpenAI API documentation is equally valid here. For accessing our API, simply use the OpenAI client in the following way: `OpenAI(base_url="https://zukijourney.xyzbot.net/v1",api_key='zu-...')`. Please note, formats such as Anthropic's `v1/complete` are not, and will not be supported.

## Upfront...

- The API is open source! Explore our V2 codebase here: [API-OSS](https://github.com/zukijourney/api-oss)
- The current release, version 2.5, exhibits minor differences that are mostly imperceptible.
- While we do not provide a ZJ-made user interface, commonly utilized interfaces include [BetterGPT](https://bettergpt.chat) and [LibreChat](https://librechat-librechat.hf.space/login)
- The usage rates are `fixed` at `4 requests per minute per key per IP` for the `/unf/` endpoints, and `12 requests per minute per key per IP` for the `/v1/` endpoints. These limits are in place to prevent DDOS attacks and abuse.
- All models are courtesy of their respective owners, as listed in v1/models. We do not own, control, or have affiliations with these entities.

**Everything may be fabricated and therefore not real, I am unaware of any illegal activities, documentation will not be taken as admission of guilt.**

## Table of Contents

### [Code-Samples](https://github.com/zukijourney/api-docs/blob/main/code-samples/README.md)

### [API Quirks & Weirdnesses](https://github.com/zukijourney/api-docs/blob/main/api-quirks/README.md)

### [ZukiJourney's Token System](https://github.com/zukijourney/api-docs/blob/main/token-system/README.md)

## Obtaining Your Api-Key

- **Generate Key**: To get your Api-Key, simply use the `/key` command with zuki.api. Below is a gif demonstrating how to do it:

  ![Using /key Command](https://files.catbox.moe/k9x9tm.gif)

- **Gamble Your Credits**: Feel adventurous? You can gamble your credit amount using the `/gamble` command. This feature is a nod to stake.com.

### Credits

Thank you to ma kachiggas
