# chrome-extension-blocker
Chrome extension to block some annoying things

### To block something just create a new rule in the rule1.json file

```  {
    "id" : *Insert new number*,
    "priority": 1,
    "action" : { "type" : "block" },
    "condition" : {
      "urlFilter" :  *Insert here the new url under ""*
    }
  }
```

