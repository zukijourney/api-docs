# Token System Overview

### Daily Token Grant

- Every 24 hours, you are eligible for a token grant, which is available if your current token balance is below 6969 tokens. You can apply for this grant using the `/daily` command.

### Token Equivalence

- Tokens are equivalent to OpenAI tokens: 1 OpenAI token equals 1 ZukiJourney token.
- Usage example: if a system prompt uses 200 OpenAI tokens and your request uses 20 tokens with a response of 180 tokens, you will be charged 400 ZukiJourney tokens (exactly the total OpenAI tokens used).
- Special note: Certain 'very short' requests incur an additional cost. Specific details on penalizations are undisclosed to prevent abuse such as spamming the input with nonsense.

### Cost Multipliers by Model

- Different chat models affect the token cost by certain multipliers:
  | Multiplier | Models/Categories |
  | --- | --- |
  | 1.5x | gpt-4-1106-preview and later, claude-3-opus and later, gpt-4-vision-preview |
  | 1.25x | gpt-4 and later, claude-3-sonnet |
  | 1x | gpt-4o-mini + all non-4 gpt models, claude-3-haiku and before, All Gemini/Mistral-Series models |
  | 0.5x | all other models not developed by zukijourney |
  | 0.25x | our own models: caramelldansen-1 & caramelldansen-1-plus |

- Similar scenario applies for image models.
  | Cost per Request | Models |
  | --- | --- |
  | 42,000 | Midjourney |
  | 2500 | DALLE-2 and later + Stable-Diffusion-3-large + Stable-Image-Ultra/Core and later |
  | 250 | Stable-Diffusion-3-Medium & the Flux model series. |
  | 100 | All models provided by Prodia. |

### Specific Costs for the Other Endpoints

- All Audio, Embeddings, Image-Upscaling @ 100 tokens per request
- Moderations, Text-Translations @ 10 tokens per request

### **Daily Token Allowances**

**Roles and Privileges in the ZukiJourney Server:**

- **@Member**
  - **Tokens**: 22,500 per day
  - **Messages**: Approximately 126 messages per day
  - **Access Level**: Available to everyone in the ZukiJourney Server
  - **Key**: IP-Locked Key
  - **Support Priority**: Low

- **@Booster**
  - **Tokens**: 200,000 per day
  - **Messages**: Approximately 400 messages per day
  - **Access Level**: Boosters of the ZukiJourney Server
  - **Key**: IP-Locked Key
  - **Support Priority**: Medium

- **@Donator**
  - **Tokens**: 200,000 per day
  - **Messages**: Approximately 400 messages per day
  - **Access Level**: One-time donations to ZukiJourney Executives exceeding $5 value
  - **Key**: IP-Locked Key
  - **Support Priority**: Medium

- **@Early Supporter/Contributor**
  - **Tokens**: 225,000 per day
  - **Messages**: Approximately 450 messages per day
  - **Access Level**: Early one-time donors to ZukiJourney Executives (Unavailable for Purchase)
  - **Key**: IP-Locked Key
  - **Support Priority**: Medium

- **@Subscriber**
  - **Tokens**: 450,000 per day
  - **Messages**: Approximately 900 messages per day
  - **Access Level**: Subscribers to the KoFi of @zukixa with a monthly contribution of about $10
  - **Key**: IP-Free Key
  - **Support Priority**: High

- **@Enterprise**
  - **Tokens**: 4,000,000 per day
  - **Messages**: Approximately 10,000 messages per day
  - **Access Level**: Subscribers to the KoFi of @zukixa with a monthly contribution of $100
  - **Key**: IP-Free Key
  - **Support Priority**: Highest


#### Additional Payment Information

- KoFi Link is available [right here](https://ko-fi.com/zukixa)
- Crypto-equivalent payments are accepted; any Coinbase-supported cryptocurrency is supported. Contact ZukiJourney executives via the #tickets channel for further details. Go via [ZukiJourney's Discords Tickets](https://discord.com/channels/1090022628946886726/1099424338287014029/1099426357219438612)
- Enterprise-level donors can request specific arrangements or benefits by opening a ticket, in the [same place](https://discord.com/channels/1090022628946886726/1099424338287014029/1099426357219438612)
- All donations & boosts include additional perks with the @zuki.gm bot. Further information can be found in the [ZukiJourney server](https://discord.com/channels/1090022628946886726/1147595903537000539/1147600594316578926)
