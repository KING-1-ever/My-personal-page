# Cyberpunk Personal Business Card

This is the first project I made during my Vibe Coding course — a personal business card webpage that works fully offline. I basically squeezed the phrase "I'm a low-key nerdy guy who loves life and nature" into a cyberpunk city where it's raining data. The whole page lives in a single index.html file. Every visual, animation, and effect is hand-built with CSS and Canvas — no external images or fonts anywhere.

## How to run

Just download index.html and double-click it in your browser. No environment setup, no server needed — it works fully offline. The only parts that need a connection are the contact form and the Gmail / Outlook buttons if you actually want to email me.

## What's already done

These are the things I really built and that actually exist on the page:

- Five screens: Home, About, Interests, Skills, and Contact. You switch between them through the navigation without reloading the page.
- Three cyberpunk themes you can flip between with the three color dots at the top right: Classic Neon, Glitch, and Vaporwave.
- A day/night mode toggle. The button icon and its label change together, and your choice is saved locally, so it's still there after you refresh the page.
- A boot-up animation: a progress bar, a typewriter effect, and content that fades in piece by piece, to make it feel like the system is starting up.
- Some 3D stuff: a spinning cube on the home page, interest cards that tilt to follow your mouse, and a perspective grid floor.
- A dynamic background: rain drawn on Canvas, floating glowing particles, neon glows, scanlines, and chromatic-aberration effects for that cyberpunk vibe.
- Day mode switches to a Chinese classical-fantasy style. The three themes map to Ink-wash Xianxia(in Chinese it writes as "仙侠" ), Blue-and-white Porcelain, and Dunhuang Guochao（in Chinese it writes as "国潮"）, with distant mountains, mist, and a cinnabar seal as decoration.
- About page: three personality cards (cheerful, helpful, loves life) with energy bars, plus a personal motto.
- Interests page: high-quality games (GTA V, COD, Minecraft, Dead Cells), natural scenery, and my love for One Piece.
- Skills page: four progress bars — web scraping and data collection, getting to know the Unity engine, Vibe Coding, and ball sports.
- Contact page: shows my email address plus a contact form. The form validates the email format, and clicking send opens your default email client, or you can compose via Gmail or Outlook webmail instead.
- Responsive: it works from phones up to desktops, has a hamburger menu on mobile, and the page never gets a horizontal scrollbar.
- Accessibility: you can switch pages with the keyboard (arrow keys, Esc to close the menu), key elements have labels, and buttons show a visible focus highlight.

## What I explored

For the creation of this webpage, I used Trae, an agent, to handle the production, as well as to process and optimize the corresponding prompts. I was responsible for filling in the content and designing the page layout, while Trae took care of processing and refining the prompts to ensure that the webpage's functionality and effects met the requirements. I had multiple rounds of dialogue with Trae, continuously iterating on the project, and finally completed this webpage.

## Problems I ran into

The initial issue I encountered was that the webpage's dark and light modes could not be switched properly—both displayed the same interface. I identified the problem, described the expected outcome to Trae, and ultimately made changes to the project. 

Second, I ran into layout issues. On the Interests and Skills pages, I noticed that the page layout was problematic, with low space utilization that caused content to display incompletely. I proposed optimization suggestions to Trae and then adjusted the project accordingly.

Finally, on the email page, after users submitted their personal information, the page initially failed to redirect to their personal email client. In addition, the webpage originally offered Gmail and QQ Mail as options. However, I found that QQ Mail could not redirect properly. I tried multiple iterations, but the improvements were minimal, so I eventually dropped QQ Mail and switched to Outlook instead. (Note: Gmail requires a VPN/proxy to redirect successfully.)
## Show time
<img width="2522" height="1351" alt="屏幕截图 2026-08-14 164411" src="https://github.com/user-attachments/assets/f1574cbf-2b43-484e-bd9a-5b39dec9de7f" />
<img width="2525" height="1352" alt="屏幕截图 2026-08-14 164208" src="https://github.com/user-attachments/assets/c267f9f1-1da4-4c5b-a92c-d423dda99fbd" />
<img width="2532" height="1348" alt="屏幕截图 2026-08-14 164232" src="https://github.com/user-attachments/assets/ec611afe-2664-4c95-a416-29c121d336d1" />


