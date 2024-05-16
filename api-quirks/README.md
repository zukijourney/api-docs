# Zukijourney Quirks: Important Considerations

### Request Handling

- **Request Reuse**: (_Currently disabled_) Requests that are 99% similar to previous ones, such as repeating the same request multiple times, will receive the same response to conserve usage.
- **Handling Simple Requests**: If the most recent message to the API is deemed too short, too simple, or unnecessary, it will be handled by Mixtral (Mistral-Small). This prevents wasting GPT resources. Note that subscribers and enterprise-tier users are exempt from this rule.

### Api-Key Management

- **IP-Locked Keys**: The Api-Key provided is IP-LOCKED, meaning it can only be used from one IP address at a time. To change the IP, use the `/resetip` command `on the zuki.api Discord Bot`. Automating this command is prohibited and will result in a ban of your key. Subscribers and enterprise-tier users are not subject to IP-Lock restrictions.
- **Key Suspension**: Leaving the ZukiJourney server will result in suspension of your Api-Key. Rejoining does not automatically restore access unless the situation is directly communicated and resolved.
- **Account and API Usage**: Each person is limited to one account. Misuse, such as using alt accounts or DDOS attacks on the API, will trigger automatic punitive measures.

### Caramelldansen-1
- **Caramelldansen-1** and its **-plus** version are our own in-house developed LLM models! Fine-Tuned on Mixtral-8x22b with special datasets, the model achieves a performance that sits right well with its other similar models, such as dbrx-instruct.
- The model is available @ **0.5x cost for all users**, with **-plus** being donator+.


### Administrative Rights

- **Access Regulation**: I reserve the right to grant or revoke access, premium features, or any benefits related to this API for any reason at my discretion.
