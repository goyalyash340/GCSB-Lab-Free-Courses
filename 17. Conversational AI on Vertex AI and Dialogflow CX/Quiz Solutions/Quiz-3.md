>You can add a list of banned phrases for your Generative Fallback response. What happens if a banned phrase has been entered by a user as part of their response?
```
A prescribed answer defined in Agent Says will be used to respond.
```
>What is the correct definition of the $route-descriptions prompt placeholder?
```
The intent descriptions of the active intents.
```
>Which statement is true for Generative Fallback:
```
Aim to prevent no-match scenarios by providing good, varied training phrases to your intents.
```
>You have been asked to enable generative responses for no-match events for specific pages, by enabling it in the Agent response section of the event handler. Where would you provide the information for the LLM to reference to generate its response?
```
Intent description
```
>A Dialogflow CX flow has been designed for booking diving trips. A particular page in the flow is configured to assist users with group reservations or full charters, the intent description states: ‘Currently you can assist users who are looking for a group reservation or a full charter. Initially collect travel details including departure period, destination, number of guests (min 4 max 15 people), contact details. The destination must be one of the following in the Pacific: Costa Rica, Mexico, Galapagos Islands.’ Which Generative Fallback enablement levels would be triggered if the user tries to book a full charter for 18 people? (Select two options)
```
The parameter-level would be triggered as the minimum and maximum number of guests is defined as an entity parameter. The LLM uses the intent description to generate the response.
```
```
The page-level would be triggered as the minimum and maximum number of guests is specified in the intent description. The LLM also uses this description to generate the response.
```
>Generative Fallback is a mechanism for handling points in a conversation with a Dialogflow CX virtual agent, where the user moves away from the intended flow and doesn't trigger another action or flow, known as a No Match error. What kind of user response could invoke a No Match error? (Select two options)
```
Saying something unexpected
```
```
An invalid input while form filling
```