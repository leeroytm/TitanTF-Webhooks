New: (Working - Finalized)
```
{
  "content": "<@&774248009813852180> — A new ticket report has appeared!",
  "embeds": [
    {
      "title": "{{EntryTitle}}",
      "url": "{{EntryUrl}}",
      "color": 16752128,
      "footer": {
        "text": "{{EntryPublished}} • React 📝- Reviewed︱✅- Closed "
      },
      "author": {
        "name": "Support Ticket Report",
        "url": "https://titan.tf/tickets",
        "icon_url": "https://media.discordapp.net/attachments/776599695786508328/790736454594461726/aot.png?width=475&height=475"
      }
    }
  ]
}
```

Compact for IFTTT:
```
{"content": "<@&774248009813852180> — A new ticket report has appeared!","embeds": [{"title": "{{EntryTitle}}","url": "{{EntryUrl}}","color": 16752128,"footer": {"text": "{{EntryPublished}} • React 📝- Reviewed︱✅- Closed "},"author": {"name": "Support Ticket Report","url": "https://titan.tf/tickets","icon_url": "https://media.discordapp.net/attachments/776599695786508328/790736454594461726/aot.png?width=475&height=475"}}]}
```

---

#### Tests
Embed mode: ON 
Results : **[ Failed ]** - Action failure message: Too many requests to this host.
```
{
  "content": "<@&774248009813852180> — A new ticket report has appeared!",
  "embeds": [
    {
      "title": "{{EntryTitle}}",
      "description": ":pencil: when you have reviewed this ticket. \n :white_check_mark: when the ticket is closed. ",
      "url": "{{EntryUrl}}",
      "color": 16752128,
      "footer": {
        "text": "{{EntryPublished}}"
      },
      "author": {
        "name": "Support Ticket Report",
        "url": "https://titan.tf/tickets",
        "icon_url": "https://media.discordapp.net/attachments/776599695786508328/790736454594461726/aot.png?width=475&height=475"
      }
    }
  ]
}
```
---

Old School (OG):
```
{ "username":"Titan.TF Support Tickets", "content":"@here — New Report! \n`[📩]` **[{{EntryTitle}}](<{{EntryUrl}}>)** \n • Issued on : {{EntryPublished}}" }
```

