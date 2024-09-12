# heartbreaker-codechallenge
Naomi the Technomancer — Today at 8:11 AM
@Code Challenge I'm a bit of a heartbreaker, and thus have a few ex partners. Whenever I run an event, they show up to try to win me back and it's very dispruptive. Now, I've hired a private security firm for all of my future events, but I'm not made of money and need to keep this as affordable as possible. Thankfully, all of my events require a guest list so I know who will be there.

Guest lists are represented as strings of single characters. An x in the string is a former partner. An o in the string is one of my bodyguards. An event is safe to attend if there is at least one body guard for every ex-partner, and cost effective if there is most one body guard for every ex-partner. So an ideal event should have the same number of Xs and Os on the guest list (case insensitive!).

Here is your challenge: Given a string, return true if the event will be both safe to attend AND cost effective.

Test cases:
With input xo, return true
WIth input xxOo, return true
WIth input xxxm, return false
With input Oo, return false
With input ooom, return false
With input abcdef, return true (no ex partners are attending, so I need no protection)

You may use any language you'd like to solve this challenge. Have fun!
