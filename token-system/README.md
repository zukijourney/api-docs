# Token System Overview

#### Daily Token Grant

- Every 24 hours, you are eligible for a token grant, which is available if your current token balance is below 6969 tokens. You can apply for this grant using the `/daily` command.

#### Token Equivalence

- Tokens are equivalent to OpenAI tokens: 1 OpenAI token equals 1 ZukiJourney token.
- Usage example: if a system prompt uses 200 OpenAI tokens and your request uses 20 tokens with a response of 180 tokens, you will be charged 400 ZukiJourney tokens (exactly the total OpenAI tokens used).
- Special note: Certain 'very short' requests incur an additional cost. Specific details on penalizations are undisclosed to prevent abuse such as spamming the input with nonsense.

#### Cost Multipliers by Model

- Different models affect the token cost by certain multipliers:
  | Multiplier | Models/Categories |
  | --- | --- |
  | 1.5x | all multimodal/tools requests, claude-3-opus, gpt-4-1106-preview and later |
  | 1.25x | gpt-4-32k and later, claude-3-sonnet/haiku, gemini-1.5 |
  | 1x | all models with provider=perplexity or deepinfra, gpt-3.5, claude-2, mistrals, gemini-pro |
  | 0.75x | all models by replicate |
  | 0.5x | all models by cloudflare |

#### Specific Costs for Various Endpoints

- Images: Midjourney: 42k, SD3/DALLE-3: 2500, replicate: 250, prodia: 100
- Embeddings, moderations, upscale, text translations, all audio: static cost of 100 tokens per request

### Token Allocation Based on Roles

#### Daily Token Allowances

- **@Member**: 22,500/day | ~100 msg/day | Everyone in the ZukiJourney Server | IP-Locked Key | Low Priority Support
- **@Booster**: 200,000/day | ~300 msg/day | Boosters of the ZukiJourney Server | IP-Locked Key | Medium Priority Support
- **@Donator**: 200,000/day | ~300 msg/day | One-Time Donators to ZukiJourney Executives @ >$5 value | IP-Locked Key | Medium Priority Support
- **@Early Supporter/Contributor**: 225,000/day | ~350 msg/day | Early One-Time Donators to ZukiJourney Executives (Unavailable for Purchase) | IP-Locked Key | Medium Priority Support
- **@Subscriber**: 450,000/day | ~800 msg/day | Subscribers to the KoFi of @zukixa @ ~$10/mo value. | IP-Free Key | High Priority Support
- **@Enterprise**: 2,500,000/day | ~5000 msg/day | Subscribers to the KoFi of @zukixa @ $100/mo value. | IP-Free Key | Highest Priority Support

#### Additional Payment Information

- KoFi Link is available [right here](https://ko-fi.com/zukixa)
- Crypto-equivalent payments are accepted; any Coinbase-supported cryptocurrency is supported. Contact ZukiJourney executives via the #tickets channel for further details. Go via [ZukiJourney's Discords Tickets](https://discord.com/channels/1090022628946886726/1099424338287014029/1099426357219438612)
- Enterprise-level donors can request specific arrangements or benefits by opening a ticket, in the [same place](https://discord.com/channels/1090022628946886726/1099424338287014029/1099426357219438612)
- All donations & boosts include additional perks with the @zuki.gm bot. Further information can be found in the [ZukiJourney server](https://discord.com/channels/1090022628946886726/1147595903537000539/1147600594316578926)
