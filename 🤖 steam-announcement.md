Newer using MonitoRSS bot (1 Aug 2022)
```
TEXT: <@&776362265200033804> — A wild steam announcement has appeared!

EMBED:
Author:
> Text: Titan.TF Steam Alert!
> Icon: https://cdn.discordapp.com/emojis/775347648583696434.png?v=1
> URL: https://steamcommunity.com/groups/titantf

Title:
> Text: {title}
> URL: {link}

Description:
> {description}

Footer:
> Text: 🕒 Announced on {date} from {author} (Team Titan)

Color:
> 6750156
```


New:
```
{
  "content": "<@&776362265200033804> — A wild announcement has appeared! ",
  "embeds": [
    {
      "title": "{{EntryTitle}}",
      "url": "{{EntryUrl}}",
      "color": 5301186,
      "footer": {
        "text": "{{EntryPublished}} from {{EntryAuthor}} (Titan Team)"
      },
      "author": {
        "name": "Alert!",
        "url": "https://steamcommunity.com/groups/titantf",
        "icon_url": "https://cdn.discordapp.com/emojis/775347648583696434.png?v=1"
      }
    }
  ]
}
```

Compact for IFTTT:
```
{"content": "<@&776362265200033804> — A wild announcement has appeared! ","embeds": [{"title": "{{EntryTitle}}","url": "{{EntryUrl}}","color": 5301186,"footer": {"text": "{{EntryPublished}} from {{EntryAuthor}} (Titan Team)"},"author": {"name": "Alert!","url": "https://steamcommunity.com/groups/titantf","icon_url": "https://cdn.discordapp.com/emojis/775347648583696434.png?v=1"}}]}
```

---

Old School (OG):
```
{ "username":"Titan.TF Steam Group", "content":"<@&776362265200033804> — An announcement! \n`[📢]` **[{{EntryTitle}}](<{{EntryUrl}}>)** \n> Publish : {{EntryPublish}} by {{EntryAuthor}} - Team Titan" }
```

---

20 Apr 2021 Testing: **[Not Implimented!]**
```
{
  "content": "<@&776362265200033804> — A wild announcement has appeared! ",
  "embeds": [
    {
      "title": "{{EntryTitle}}",
      "url": "{{EntryUrl}}",
      "color": 5301186,
      "footer": {
        "text": "{{EntryPublished}} from {{EntryAuthor}} (Titan Team)"
      },
      "thumbnail" : {
      "url": "https://cdn.discordapp.com/emojis/775347648583696434.png?v=1"},
      
      "author": {
        "name": "Alert!",
        "url": "https://steamcommunity.com/groups/titantf",
        "icon_url": ""
         
      }
      
    }
  ]
}
```
```
RSS: https://steamcommunity.com/groups/titantf/rss/
```

