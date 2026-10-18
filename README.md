# Yosh blogerlar akademiyasi — Telegram Mini App

The public site hosts the parent-approved introduction flow for the Fergana children's blogging academy. Parents open it from a personalized Telegram bot link after the team leader approves their request.

## Introduction flow

- Uzbek Latin interface for ages 7–14, with age-appropriate examples for 7–10 and 11–14.
- Parent consent is requested before the child enters a name or profile details.
- The child introduces themselves with a first name or nickname, chooses interests and blogging styles, then visits three instructor-led academy rooms.
- Progress is saved to the CRM after each completed room. Child data is sent through the `yba-parent-api` Edge Function; no database secret is included in this public repository.
- Access requires a personal approved Telegram session link. Opening the public home URL alone does not load a child's profile or write CRM data.

## Assets

- `assets/room-idea.png`
- `assets/room-studio.png`
- `assets/room-project.png`

GitHub Pages URL: <https://platform770uz-dev.github.io/yosh-blogerlar-miniapp/>.
