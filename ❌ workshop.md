### Alert!
- This applet uses {{EntryContent}} module in the IFTTT
- The applet may or may not work because of too many requests to this host.

New:
```
{
  "embeds": [
    {
      "title": "{{EntryTitle}}",
      "url": "{{EntryUrl}}",
      "description": "{{EntryContent}}",
      "color": 4886754,
      "footer": {
        "text": "Submit : {{EntryPublished}} by {{EntryAuthor}} "
      },
      "author": {
        "name": "Titan.TF Workshop",
        "url": "https://workshop.titan.tf/",
        "icon_url": "https://media.discordapp.net/attachments/776599695786508328/792389296584785921/tf2_logo.png?width=473&height=473"
      }
    }
  ]
}
```

Compact for IFTTT:
```
{"embeds": [{"title": "{{EntryTitle}}","url": "{{EntryUrl}}","description": "{{EntryContent}}","color": 4886754,"footer": {"text": "Submit : {{EntryPublished}} by {{EntryAuthor}} "},"author": {"name": "Titan.TF Workshop","url": "https://workshop.titan.tf/","icon_url": "https://media.discordapp.net/attachments/776599695786508328/792389296584785921/tf2_logo.png?width=473&height=473"}}]}
```

---
Old School (OG):
```
{ "username":"New Workshop Submission", "content":"`[⚙️]` **[{{EntryTitle}}]({{EntryUrl}})** \n • Submitted on {{EntryPublish}} by {{EntryAuthor}}" }
```

---
RSS: https://workshop.titan.tf/atom


