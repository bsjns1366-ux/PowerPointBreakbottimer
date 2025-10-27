PowerPointBreak × MinexxProo — All-in-One Telegram Bot (ClawCloud-ready)

1) ClawCloud Deploy
-------------------
- Upload: bot.py, requirements.txt
- Set Environment Variable: BOT_TOKEN=YOUR_BOTFATHER_TOKEN
- (Optional) edit bot.py for OWNER_ID / CHANNEL_USERNAME / GROUP_USERNAME
- Start command: python bot.py

2) First Steps
--------------
- Add bot to @PowerPointBreak (channel) and @PowerPointBreakConversion (group) as admin
- Owner: /panel , /status
- Others: /start -> Join -> Send Access Request (Owner approves)
- New chat: /enable (Owner approves)

3) Main Commands
----------------
- /count <time>            (Owner/Admin)
- /pause /resume /stop /refresh
- /giveaway                (Owner/Admin)
- /giveaway2 <message>     (Owner/Admin/Approved)
- /settime <time>
- /chkparticipate          (Owner/Admin)
- /winner [n]              (Owner/Admin)
- /setpost <text> /showpost /resetpost
- /enable                  (chat admin)
- /panel                   (Owner)
- /botoff /boton           (Owner)

4) Notes
--------
- state.json stores approvals, chats, participants, and settings.
- Keep BOT_TOKEN secret (env var).
- Make sure Group Privacy is OFF in @BotFather.
