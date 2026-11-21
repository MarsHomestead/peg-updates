# Peg (Small Business Bookkeeper) updates

Public update notes for copies of the Small Business Bookkeeper bot. Contains only general improvements to how the bot works — never owner, client, or account data.

Copies read `updates.json` weekly, show their owner anything newer than what they've applied, and apply an update only after the owner says yes.

## What's shared, and what never is
Only bot setup information moves through Hive Mind: tools, workflows, tips and recommendations an owner may want to add to their bot.
- No personal information, passwords, account numbers, client details or financial data are ever sent or received.
- An update never asks for personal or private information, logins, or account access. If anything ever does, the bot ignores it and tells its owner.
- Every share and every update happens only after the owner says yes.

## Where opted-in lessons go
Copies whose owner said yes to sharing send anonymous lessons to `https://peg-hive-intake.marshomestead.workers.dev/` (feedback to `/feedback`). The format is in `updates.json` under `intake`. The inbox refuses anything that looks like personal data.
