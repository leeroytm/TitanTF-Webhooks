### Alert!
This applet uses {{EntryContent}} module in the IFTTT
The applet may or may not work because of too many requests to this host.

---

New:
```
{
  "embeds": [
    {
      "title": "{{EntryTitle}}",
      "url": "{{EntryUrl}}",
      "description": "{{EntryContent}}",
      "color": 59749,
      "footer": {
        "text": "Issued : {{EntryPublished}} "
      },
      "author": {
        "name": "Fix Titan.TF",
        "url": "https://fix.titan.tf/",
        "icon_url": "https://media.discordapp.net/attachments/776599695786508328/792384331423285278/Fix.png?width=473&height=473"
      }
    }
  ]
}
```

Compact for IFTTT:
```
{"embeds": [{"title": "{{EntryTitle}}","url": "{{EntryUrl}}","description": "{{EntryContent}}","color": 59749,"footer": {"text": "Issued : {{EntryPublished}} "},"author": {"name": "Fix Titan.TF","url": "https://fix.titan.tf/","icon_url": "https://media.discordapp.net/attachments/776599695786508328/792384331423285278/Fix.png?width=473&height=473"}}]}
```

---

Old School (OG):
```
{ "username":"Fix Titan.TF Report", "content":"`[🛠]` **[{{EntryTitle}}]({{EntryUrl}})** \n • Issued on {{EntryPublish}}" }
```

---
RSS: https://fix.titan.tf/atom
