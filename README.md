```powershell
function Show-Introduction {
    $intro = @"
    Oi! 👋
    Name's Shabeer. I do things with computers
    and occasionally they work.

    📅 A TYPICAL DAY:
      06:00 — Wake up, check phone, regret it 📱
      09:00 — Open 47 browser tabs, read none 🗂️
      11:00 — Google autocompletes my problem 🔮
      14:00 — Stack Overflow saves me. Again. 🛟
      17:00 — 'It works on my machine' (lies) 🎭
      22:00 — Just one more YouTube video... 📺

    🎯 PROFESSIONAL SKILLS:
      • Nodding in meetings I joined late 🎩
      • Saying 'I'll get back to you' (I won't) 📝
      • Turn it off, turn it on. Magic. 🔌
      • Pretending I read the documentation 📖
      • Finding THE typo after 3 hours 🔍

    🗣️ LANGUAGES I SPEAK:
      • English (mostly)
      • Sarcasm (fluent)
      • Error messages (interpretive)
      • 'Hmm that's weird' (native level) 🤔

    🦆 Fun fact: My rubber duck has heard more
       confessions than a priest.

    ⚡ Powered by chai, chaos, and the unshakeable
       belief that Ctrl+Z works in real life. ⏪
"@
    Write-Host $intro
}

Show-Introduction
```
