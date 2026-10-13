# The story of Truth Date

I am Mouemen Akari, a junior student. Truth Date was my first real project, and this is how it went.

## The idea
You send someone special a themed link. They open it, press No, No, No, and then Yes. You get a phone notification at every step, and you can see how far they got.

## How I built it
- The idea, the screens and every rule came from me. I tested each step on my phone and said what to change.
- It is plain JavaScript on the front end, small serverless functions on the back end, and a Postgres database, so it is fast and free to run.
- I used AI tools as a coding helper, and I reviewed everything it produced.

## Problems I met and how I solved them
1. **I wanted to see what happens after the link is sent.** I added a journey: which screen was reached, and how many times No was pressed.
2. **I needed to know right away.** I added phone notifications for open, Yes and answer.
3. **Contacts.** The last page asks the person for a WhatsApp number or Instagram, and the owner dashboard lists them with a CSV export.
4. **Privacy.** Passwords are never stored in clear text, and the personal data stays in the database, not in this public repository.
5. **Splitting it from my bigger app, O HUB.** I moved Truth Date to its own repository and its own database, and fixed the hosting build so it deploys as a plain site with an API.

## Tools and services I used
- GitHub for the code
- Vercel for hosting
- Neon for the Postgres database
- Web Push for phone notifications

## AI
I used AI assistants to write and review code and to explain errors. I gave the direction and made the decisions.

## Skills I practised
- Turning an idea into screens and rules
- Database design
- Debugging a failed deployment
- Keeping private data private

## Links
- App: https://truthdate.vercel.app
- Code: https://github.com/Moemenakari/truthdate
- My other project, O HUB: https://github.com/Moemenakari/adate

## News
- Truth Date now lives in its own repository.
- The owner dashboard shows each invite and what the person did.
