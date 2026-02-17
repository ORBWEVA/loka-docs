---
sidebar_position: 4
title: AI-Powered Features
description: "Use AI in Loka with your own API key. Get lesson preparation help, real-time suggestions, and automated session feedback."
---

# AI-Powered Features

Loka integrates AI to help you teach more effectively. From generating teaching suggestions to creating review materials automatically, these tools save time and improve the learning experience.

## Bring Your Own Key (BYOK)

Loka uses a **BYOK model** for AI features. This means you provide your own API key from a supported AI provider, and Loka uses it to power AI features in your account. You are billed directly by the AI provider based on your usage -- Loka does not mark up or resell AI access.

### Supported Providers

| Provider | Key Setting | Default Model |
|----------|-------------|---------------|
| **Anthropic Claude** | Profile > AI Integration | Claude Sonnet |
| **OpenAI** | Profile > AI Integration | GPT-4o Mini |
| **OpenRouter** | Profile > AI Integration | Configurable (includes free models) |

### Adding Your API Key

1. Go to your **Profile** page in the educator dashboard
2. Open the **AI Integration** section
3. Enter your API key for Anthropic, OpenAI, OpenRouter, or any combination
4. Select your **preferred provider** (the one Loka will try first)
5. Save your settings

Your keys are encrypted and stored securely. Loka never shares your keys with third parties.

:::tip
If you're unsure which provider to choose, Anthropic Claude generally produces more nuanced language feedback, while OpenAI GPT-4o Mini is faster and uses fewer tokens. You can add keys for both and let the fallback system handle the rest.
:::

## Provider Fallback

If you have keys for both providers, Loka uses an automatic fallback system:

1. Loka tries your **preferred provider** first
2. If that provider fails (rate limit, quota exceeded, temporary error), Loka automatically tries the **next available provider**
3. You get your result without interruption

This means you're never blocked by a single provider's downtime.

## AI Features

### AI-Assisted Progress Ratings

After a lesson, use AI to help generate progress assessments:

- Suggested criteria movements (whether each skill area should be rated up, down, or stay)
- Auto-generated comments for "Points to Improve" and "Strong Points"
- Based on session data including canvas notes and CIPs

Access this feature from the session review screen when wrapping up a lesson.

### ARP Generation

AI can automatically generate **Active Recall Pairs** from your lesson content:

1. Complete a session with notes on the [Living Canvas](/educators/canvas)
2. Click the **AI** button on the canvas toolbar
3. If you use Fathom AI, the system first fetches the meeting transcript for richer context
4. AI analyzes your session notes, keywords, and CIPs to generate question-answer pairs
5. Generated ARPs are inserted into your canvas and can be edited or removed with undo

### AI-Powered Session Feedback

After a lesson, AI can help generate structured progress assessments:

- Analysis of criteria movements across skill areas
- Points to improve with specific examples from the session
- Strong points demonstrated during the lesson

This feedback is based on your canvas notes and CIPs, so the more detailed your session records, the better the feedback.

## Fathom AI Integration

If you use **Fathom AI** for meeting transcription, you can connect it to Loka:

1. Go to **Settings > AI Integration**
2. Enter your Fathom API key
3. After a lesson conducted via video call, Fathom's transcription can feed into Loka's ARP generation and feedback tools

This is especially powerful for conversation-heavy lessons where you may not have time to type detailed notes on the canvas. The transcription fills in the gaps.

## Usage and Costs

Since you own your API keys, AI costs depend on your usage:

| Feature | Typical Cost |
|---------|-------------|
| AI Suggest | A few cents per request |
| ARP Generation | A few cents per session |
| Session Feedback | A few cents per session |

Costs are billed directly by your AI provider (Anthropic, OpenAI, or OpenRouter). Check your provider's dashboard for detailed usage tracking.

:::note
AI features are optional. Loka works fully without them -- you can always create ARPs, write feedback, and plan lessons manually. AI simply speeds up the process.
:::
