# Contact

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "contact",
  "detailed_event": "Contact",
    "action": "<action>",
    "event_data": {
        "contact_action": "<contact_action>",
        "method": "<method>"
    },
    "method": "<method>"
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|action|string|The generic action of an event property||||||||
|event_data.contact_action|string|either "open", "close chat button", "send message", "survey start", "survey submit" or "close call button"|"open", "close chat button", "send message", "survey start", "survey submit", "close call button"|||||||
|event_data.method|string|The site that is tied to the FTI specific "login" event, which is intended to collect event\_data, not user\_data||||||||
|method|string|The site that is tied to the FTI specific "login" event, which is intended to collect event\_data, not user\_data||||||||




