# Privacy Policy

**Last updated:** 29 August 2026

Hooked ("the Bot") is operated by Phish Net ("we", "us"), the data controller for the purposes of
this policy. You can reach us in our [Discord support server](https://discord.gg/d9WK5BeyaR).

**We do not store your messages.** Messages are read in memory to check for phishing and spam, then
discarded. No message content is written to any database and we keep no message history.

### What we collect

We store the following, and nothing else:

- **Your Discord user ID** — only once you trigger something, such as sending a flagged link,
  receiving a timed role, or being timed out by a rule. If you never trigger a moderation rule, we
  hold no record of you.
- **A count of flagged links you have sent in a server, and the time of the most recent one** —
  recorded on each detection, because escalating punishment rules depend on the running count.
- **Timed roles and timeouts currently in effect** — so they can be removed automatically when they
  expire.
- **Server IDs and the settings a server's administrators configure** — to apply that server's
  chosen behaviour.
- **Webhook credentials for servers using audit logging** — created when an administrator selects a
  log channel, so logs can be delivered without consuming the Bot's rate limit.

### What we do not collect

- We do not collect email addresses, IP addresses, real names, or payment details. We never receive
  them.
- We do not build profiles, use your data for advertising, or sell it.

### How messages are processed

To detect phishing, the Bot reads message content as it arrives and extracts any links. Those links —
**and only the links, never the message text or the identity of the sender** — are sent to the Phish
Net API for classification. That service checks them against our own blocklist and against the
third-party feed **Sinking Yachts** (`phish.sinking.yachts`).

Message content is never retained at any stage of this process.

### Audit logs

Servers may enable audit logging, which posts records of moderation events into a channel that server
controls. Those messages may include your user ID, the channel involved, and the content of a message
that was removed for phishing or spam.

**Those messages belong to that server, not to us.** We cannot delete them on your behalf. Contact
that server's administrators for removal.

### Sharing

We do not sell or share your data. It is disclosed only:

- to Discord, Inc., inherently, as the platform the Bot operates on;
- to Sinking Yachts, limited to link classification as described above;
- where required by law.

### Retention

- Timed roles and timeouts are deleted as soon as they expire.
- Flagged-link counts are kept until a server administrator resets them, or you ask us to erase them.
- Webhook credentials are deleted when a server stops using that log channel.
- If the Bot is removed from a server, ask and we will erase that server's data.

We do not otherwise impose a fixed retention period, because the data is retained only while it is
serving the moderation purpose it was collected for.

### Your rights

You may ask us to tell you what we hold about you, to correct it, or to erase it. If you are in the
UK or EEA, you also have the right to object to processing, to request portability, and to complain
to your local supervisory authority.

**To make a request:** open a ticket in our
[Discord support server](https://discord.gg/d9WK5BeyaR) and include your Discord user ID. Requests
must come from the account they concern — we will not act on a request naming a different account,
since that would let anyone erase someone else's moderation history.

We aim to acknowledge requests within **14 days**, and will respond within **one month**. If a
request is complex, or you have made several, we may extend that by up to two further months — we
will tell you within the first month if we need to, and why.

**Erasure is queued, not immediate.** Once we accept an erasure request it is scheduled to run
**7 days later**, and you may withdraw it at any point before then by telling us in the same ticket.
The delay exists because erasure cannot be undone — there is no copy to restore from — so a request
made in haste stays reversible for a week. Your data is destroyed at the end of that period without
any further action needed from you.

The one limit we cannot work around: audit-log messages already delivered into a server's own channel
are that server's messages. We will erase our records; only that server can delete theirs.

### Children

The Bot is not directed at anyone under the minimum age required by Discord's Terms of Service in
their country.

### Changes

We may update this policy at any time, and a change takes effect as soon as it is published here.
We will not always announce updates, so the version on this page is the one that applies — the date
at the top tells you when it last changed.

Where a change materially affects how your data is handled, we will make a reasonable effort to
announce it in the support server. That is an intention rather than a guarantee, and it does not
replace checking this page.
