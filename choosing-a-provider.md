---
layout: default
title: Choosing a provider
nav_order: 3
---

# Choosing a Music Provider

**Background Music Generator with any AI** uses a Music API Profile. You bring the account and API key from the provider you want to use, and BMG sends the brief and output settings directly to that profile.

---

## A practical place to start

If you want access to multiple music models through one account, start with **OpenRouter**. It is the simplest way to compare available music models without creating a separate BMG profile for every model host.

The best model depends on the track you need, your provider account, duration limits, and the provider's current availability. Use **Test connection** after changing any profile field.

---

## Provider choices in BMG

| Profile choice | What you enter |
|---|---|
| **OpenRouter** | Your OpenRouter API key and the music model you want to use |
| **Gemini (Lyria)** | Your Google AI API key and a Lyria music model |
| **Stable Audio** | Your Stability AI account details and audio model |
| **TemPolor** | Your TemPolor connection details and model |
| **SOUNDRAW** | The connection details provided for your SOUNDRAW access |
| **Custom** | A provider endpoint and model supplied by that provider |

Provider catalogues, model names, pricing, output length, and commercial-use terms are set by each provider. Check the provider's own documentation before using a track commercially.

---

## Profile fields

- **Profile** — a name you recognise later; it does not affect the generated music.
- **Provider** — chooses BMG's connection format and starter values.
- **Model** — the specific music model to request from that provider.
- **Base URL** — the provider API endpoint. Keep the preset unless the provider tells you to use another one.
- **API key** — your secret provider credential. Leave it empty while editing an existing profile to keep the saved key.

## Test before generating

Click **Test connection** after entering or changing a profile. A successful result confirms the key, endpoint, and model can be reached. It does not generate a track or charge for one.

If testing fails, check the API key, model spelling, Base URL, provider account permissions, and any provider-side credit or quota requirement.
