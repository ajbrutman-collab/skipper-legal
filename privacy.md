---
title: Skipper Privacy Policy
permalink: /privacy/
---

# Skipper Privacy Policy

**Effective:** October 25, 2026
**Contact:** SkipperFirstMate@gmail.com

Skipper ("we") is an iOS app that helps you own and run a boat: profiles, maintenance, a logbook, charts, safety gear, first aid guides and an AI assistant called First Mate. This policy explains what data the app uses, where it goes, and the choices you have.

## The short version

- Most of what you put in Skipper — boats, maintenance, trips, tracks, catches, markers, safety gear — **stays on your iPhone**.
- Some features need our server: signing in, First Mate's online answers, fish identification, fishing regulations, species photos, AIS traffic and the optional boat registry. Those features send only what they need.
- We **don't sell your data, show ads, or track you** across other apps or websites.
- You can **delete your account in the app** (More → Account → Delete account).

## Data that stays on your phone

Your boat profiles, engines, maintenance tasks and records, service documents, trips and GPS tracks, sea time, catches and photos, markers and routes, safety gear and settings are stored on your device. They aren't uploaded unless you use one of the features below. Deleting the app deletes this data.

## Data that leaves your phone, and why

| What | When | Sent to | Why |
|---|---|---|---|
| Email address or phone number | You sign in | Supabase (our sign-in provider) | To create your account and send sign-in codes |
| Your messages to First Mate, plus app context (selected boat, its maintenance and logs as needed, your current position, what screen you're on) | You use First Mate's online answers | Our server, then Anthropic (Claude) | To answer your question and take actions in the app |
| Catch and problem photos, approximate position | You tap Identify | Our server, then Anthropic | To identify the fish or diagnose a problem |
| State, species, nearby town | You check fishing regulations | Our server, then Anthropic (which searches official agency websites) | To find current rules |
| Species names | Regulations show photos | Our server, then Wikimedia | To fetch reference photos (no personal data) |
| The map area you're viewing | AIS layer is on | Our server, then aisstream.io | To show nearby vessel traffic |
| The map area you're viewing | You view the chart and weather | NOAA, Open-Meteo, OpenSeaMap, Apple Maps (directly from your phone) | Charts, wind, forecasts, seamarks, places |
| Boat details and, if you choose, maintenance and issue history | You turn on "List in registry" / "Share history" for a boat | Our server | So crew can find the boat, and to improve maintenance predictions |
| How much you use First Mate each day (number of requests and their cost to us) | You use Claude-backed features | Our server | To keep costs fair (a daily allowance per account) |

With Sign in with Apple or Google, we receive the email address (or Apple's private relay address) and an account identifier from them.

**Location.** Skipper uses your location to show you on the chart, record trips, and (if you allow "Always") log trips automatically when you leave the dock. Tracks are stored on your phone. Your position is sent to our server only with a First Mate request, fish identification, regulations lookup or AIS request that uses it.

**AI processing.** First Mate and identification use Anthropic's Claude. Anthropic processes these requests to return answers; under its commercial terms it doesn't use them to train its models.

## How long we keep it

- Account: until you delete it.
- First Mate messages and photos: not stored on our server after the answer is returned; the conversation stays on your phone until you clear it.
- Server access logs: our host keeps standard request logs (time, address requested — which for AIS includes the map area you were viewing — and IP address) for up to 30 days to keep the service running and secure.
- Daily usage records: about 2 months, then deleted automatically.
- Regulations and species photo results: cached up to 3 and 30 days, not linked to you.
- Registry data you chose to share: until you turn sharing off or delete your account.

## Your choices

- Use Skipper without an account: everything on-device keeps working; online features ask you to sign in.
- Turn off location, camera, photos or Bluetooth in iOS Settings at any time.
- Turn registry sharing on or off per boat.
- Delete your account in the app; this removes your account and anything you shared to the registry.
- Contact us at SkipperFirstMate@gmail.com to ask what we hold about you or to request deletion.

## Children

Skipper isn't directed to children under 13, and we don't knowingly collect their data.

## Security

Data sent to our server travels over HTTPS. Sign-in tokens are stored in the iOS Keychain. No system is perfectly secure; tell us at SkipperFirstMate@gmail.com if you find a problem.

## Changes

We'll update this page and change the date above when this policy changes, and tell you in the app for significant changes.
