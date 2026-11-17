# Lens loader

Lens is a small bookmark that lets you highlight text (or a picture) on any web page and ask an AI about it. This repository holds the **loader**: the one line of text you save as a bookmark. The loader downloads the current Lens each time you click it, so you never have to replace your bookmark when Lens is updated.

> **You need a Lens account to use it.** Lens is not open to everyone. Accounts are created by the person who runs your Lens service. If you don't have a username and password yet, use **Sign up** on the card that appears after you click the bookmark, or email **lenssupportls@gmail.com**.

> **Important: AI is not perfect.** Lens gives you answers from an AI. It is a helper, not a source of truth. **The AI can and will get things wrong**, especially the cheaper, lighter models (the ones with a green dot), which are quicker and use fewer tokens but make more mistakes on maths, multi-step problems, facts, dates, names and anything that needs careful reasoning. Even the strongest model can be wrong or sound sure when it isn't. **Always check anything that matters** (homework, work, money, health, legal or safety questions) against a reliable source before you rely on it.

> **Please read the Terms and Conditions.** Everything you agree to when you sign up (what you pay, how your month works, what you may not do, what is stored about you, what happens if the rules are broken, and refunds) is in the Terms. Read them before you sign up and again if you are unsure about anything. See [Read the Terms and Conditions](#read-the-terms-and-conditions).

---

## Contents

- [Before you start: things to know](#before-you-start-things-to-know)
- [Read the Terms and Conditions](#read-the-terms-and-conditions)
- [Install](#install)
- [First sign-in](#first-sign-in)
- [Ask about text on a page](#ask-about-text-on-a-page)
- [Type a question instead](#type-a-question-instead)
- [Follow-ups](#follow-ups)
- [Pictures](#pictures)
- [Keyboard shortcuts](#keyboard-shortcuts)
- [Commands](#commands)
- [Choosing a model](#choosing-a-model)
- [Compact (Incognito) mode](#compact-incognito-mode)
- [Limits and account status](#limits-and-account-status)
- [Troubleshooting](#troubleshooting)
- [Please read: do not edit the loader](#please-read-do-not-edit-the-loader)
- [Privacy and security](#privacy-and-security)
- [Support](#support)

---

## Before you start: things to know

- **Answers can be wrong.** This is true of every AI. Cheaper models are wrong more often. If a question is important or tricky, pick a stronger model with `/model` (it costs more tokens), ask the question in a different way, and check the result yourself. See [Choosing a model](#choosing-a-model).
- **Don't copy answers blindly.** You are responsible for how you use what Lens gives you, including your own school's or workplace's rules about AI help. Lens can't be blamed for grades, work or decisions that rely on a wrong answer.
- **It is a paid service with limits.** Your plan sets your daily and monthly limits, your longest message, and which models you can use. Heavier models and pictures use far more of your tokens.
- **Lens is for personal use.** Use it for answers and help with your own work. Sharing your login, reselling access, or abusing the service can get your account shut down with no refund.
- **Be 13 or older.** If you are under 18, you need a parent or guardian's permission to sign up and pay.
- **The service can change or go offline.** Lens can be slow, change how it works, or be unavailable at times, and the bookmark updates itself from the service.
- **Never highlight or type secrets.** Don't send passwords, bank details, or other private information. What you highlight and type is sent to the AI service.

---

## Read the Terms and Conditions

When you sign up, you have to tick a box saying you've read and agree to the Terms and Conditions. **Please actually read them.** They are written in plain language, and they cover things that affect you and your money:

| Section | What it tells you |
|---|---|
| Plans and prices | What each plan costs per month and what it includes (limits, longest message, models). |
| Models | Which AI models each plan can use, how to choose one, and what happens if a model is shut down or replaced. |
| What the service is | That answers can be wrong, that Lens is for personal use, that the bookmark updates itself, and the age rule. |
| Your account | How signing up works (a sign-up is a request, and access turns on only when it is accepted and paid). One account is for one person: no sharing, selling or extra accounts. |
| The code | That you may not copy, share, edit, take apart, or try to find the hidden parts of the bookmark or service. |
| Abuse | What counts as misuse, such as automation, getting around limits, or overloading the service. |
| What we collect and why | What is stored about you (including your IP address, usage and what you send), how it is used, and how long it is kept. |
| What happens if you break the rules | Warnings are not guaranteed. Accounts can be signed out, blocked, timed out or shut down with no refund. |
| Payments and refunds | Plans are paid one month ahead and are generally not refundable once you have access. How your 30-day month starts, what happens if you don't renew, and when an unpaid account can be deleted. |
| Our responsibility, changes and contact | The service is provided "as is", the Terms can change, and how to reach us. |

A few points people often miss:

- Your month starts the **first time you use the AI after your account is turned on**, and lasts 30 days. Pay again before it ends to keep access.
- An **unpaid** account is locked. It can only sign out (plus use any free trial tokens left). If it stays unpaid for a week it may be deleted.
- Using Incognito mode only changes how Lens looks. It does **not** make your use private or invisible, and it doesn't excuse breaking your school's or workplace's rules.
- Your data, including your IP address, is kept while your subscription is active, and deleted within 30 days after it ends.

The Terms are shown in full during sign-up, and you can ask for a copy at any time at **lenssupportls@gmail.com**. If anything in them is unclear, ask **before** you pay.

---

## Install

You only do this once. It takes about a minute on a computer.

1. **Open the loader file** (`user-loader-v10.txt`) and **copy everything in it**. Select all (`Ctrl + A`, or `Cmd + A` on a Mac), then copy. It is one long line that starts with `javascript:`. Copy all of it, with nothing added or removed.
2. **Show your bookmarks bar** so you can see what you're doing.
   - Chrome / Edge: `Ctrl + Shift + B`
   - Firefox: `Ctrl + Shift + B`
   - Safari: View → Show Favorites Bar
3. **Create a new bookmark.**
   - Chrome / Edge: right-click the bookmarks bar → *Add page* (Chrome) or *Add favorite* (Edge).
   - Firefox: right-click the bookmarks bar → *Add Bookmark…*
   - Safari: bookmark any page, then edit the bookmark.
4. **Name it** whatever you like, for example `Lens`.
5. **Paste the loader into the address (URL) field** where the web address normally goes. Replace anything already there. Save.

That's it. To use it, open any normal web page and click the bookmark.

**Check that the paste worked.** The address field should start with `javascript:`. Some browsers remove that word when you paste into the address bar, but not when you paste into the bookmark's own URL field, which is why step 5 matters. If the bookmark does nothing when you click it, see [Troubleshooting](#troubleshooting).

**Phones and tablets.** Bookmarks that run code are awkward on mobile browsers, and some don't allow them at all. Lens is designed for a computer.

---

## First sign-in

1. Open any web page and click the Lens bookmark.
2. The first time, a card appears. Choose **Log in** if you already have an account, or **Sign up** to ask for one.
3. Enter your username and password and press **Sign in**. The eye button shows what you typed so you can check it.
4. A welcome card appears. It can include a message from staff, a personal note for you, and your plan, your AI model, your account status and how much you have left. Press **Got it** (or `Esc`) to close it.

Your login is saved in your browser, so you won't be asked again. The next time you click the bookmark you are already signed in.

### Signing up

1. Click the bookmark and choose **Sign up**.
2. Enter your email and pick a username. Usernames are unique. If yours is taken, pick another.
3. Enter your password twice. Lens tells you if they don't match.
4. Choose your plan and your AI model.
5. **Read the Terms and Conditions** (see [above](#read-the-terms-and-conditions)), then tick the box to agree. You can't continue without agreeing.
6. Choose how to pay, if payment options are shown.
7. Finish. A sign-up is a request, so it is reviewed first. Your account info and how to pay are emailed to you, and your account turns on once payment is confirmed. Use a real email address you can read, and only one account per person.

Until your account is turned on you can sign in, but it is locked. See [Limits and account status](#limits-and-account-status).

---

## Ask about text on a page

1. Click the Lens bookmark.
2. **Drag your mouse across** the text (or picture) you want to ask about. A small card shows what you picked.
3. Optional: type your own instruction in the box, for example *explain this simply* or *translate to Spanish*. What you type is used together with what you highlighted. If you leave the box empty, Lens asks about the highlighted text.
4. Press **Enter**. The answer appears on the page.

Good to know:

- You can **edit the highlighted text** before you send it.
- Long selections **scroll**, so you can check that Lens picked up the right text.
- The Lens window **can't be highlighted by accident**.
- The answer card shows how many tokens that question used, with a coloured dot for light, medium or heavy use.
- You can select the answer text or copy it with one click.
- Press `Esc` or click the **X** to close anything.

**Faster way:** hold `Alt` and drag. Lens asks right away, so you don't need to click the bookmark first.

---

## Type a question instead

Nothing to highlight? Click the bookmark, choose **or type a question**, type it, and press **Enter**.

---

## Follow-ups

Every answer has a box underneath for a follow-up. Lens remembers the last answer, so short messages work: *shorter*, *give me an example*, *why?*

---

## Pictures

If the area you highlight includes pictures, Lens tries to read them. Tick the box to send the picture, then ask.

- This is best effort. It doesn't always work.
- **Pictures use many more tokens than text**, so they use up your limits much faster.
- Maths, symbols and text inside frames are read as text, so they usually don't need a picture.
- If a picture belongs to another website that doesn't allow it to be read, type your question instead.

By default pictures are sent in a smaller, cheaper size. See `/pictures` below.

---

## Keyboard shortcuts

On a Mac, use `Control + Shift + Option` wherever this table says `Ctrl + Shift + Alt`.

| Keys | What it does |
|---|---|
| `Alt` + drag | Highlight and ask right away |
| `Enter` | Send your question |
| `Esc` | Close the card |
| `Ctrl + Shift + Alt + E` | Open the command box |
| `Ctrl + Shift + Alt + S` | Switch Incognito mode on or off |

---

## Commands

Press `Ctrl + Shift + Alt + E` to open the command box. Every command appears as a button. Tap one to fill it in, finish typing if it needs more, then press **Run** or **Enter**.

Many commands work like a switch: run one with nothing after it to turn it on, and run it again to turn it off.

| Command | What it does |
|---|---|
| `/model` | Shows the AI models your plan allows. Add a name to pick one, for example `/model terra`. See [Choosing a model](#choosing-a-model). |
| `/story` | Saves background text that is sent with every question, so the AI always knows your context. Run it alone to open a big box, or type it straight after: `/story (your text)`. Up to 20,000 characters. |
| `/clearstory` | Removes your story. |
| `/answer` | Sets how answers should look, for example `/answer (short, one sentence)` or `/answer (bullet points, simple words)`. |
| `/request` | Sets rules the AI follows on every answer, for example `/request (always answer in Spanish)`. |
| `/pictures` | Sets picture quality. `/pictures low` is smaller and cheaper (the default). `/pictures high` is sharper but costs far more tokens. Run it alone to switch between them. |
| `/instant` | Asks the moment you finish dragging, with no card to type in. `/instant on`, `/instant off`, or run it alone to switch. |
| `/incognito` | Turns Incognito mode on or off. |
| `/usage` | Shows what you've used and what you have left: requests and tokens for today and this month, your longest allowed message, when your daily limits reset, and your account status. |
| `/norm` | Puts your rules, answer style and modes back to normal. Your story is kept. |
| `/reset` | Clears everything you've saved, including your story. You start fresh. |
| `/signout` | Signs you out of Lens everywhere, on every website and every device. |

Your saved settings belong to your account, so they come with you to other websites and other computers.

---

## Choosing a model

Different AI models trade speed, quality and cost. Which ones you can use depends on your plan.

**The cheaper models are not the best.** A green-dot model is fast and uses very few tokens, which is great for simple questions like a definition or a quick rewrite. But it **will get more answers wrong**, especially on maths, step-by-step problems, facts and dates, and tricky wording. For anything that matters, use a stronger model (yellow or red dot) and still double-check the answer. A stronger model is more reliable, not perfect.

- Run `/model` by itself to see the models on your plan, with a short note on what each is good for.
- Each model has a coloured dot showing how much of your tokens and cost it uses: **green** is light, **yellow** is medium, **red** is heavy.
- Pick one by adding part of its name, for example `/model luna` or `/model terra`. If the name matches more than one model, Lens asks you to be more exact. If it matches none, run `/model` to see the choices.

Your choice is saved to your account and applies to your very next question. If your service owner has switched model choosing off, Lens tells you.

A heavier model uses more of your daily tokens, so a model that shows a red dot can use up your limit faster. It is a balance: light models stretch your tokens further, heavy models are more accurate.

---

## Compact (Incognito) mode

Incognito mode makes Lens as small and quiet as possible. Switch it on or off with `Ctrl + Shift + Alt + S` or the `/incognito` command.

- Everything is small and faded, with no icons, help text or animations.
- You still drag to select. A thin dotted outline shows the area.
- The card is just a small character count. Click it to see and edit the text.
- Answers appear as a small plain box. Double-click one to copy it and close it.
- After clicking the bookmark you can simply start typing a question.
- Welcome messages are turned off. Everything else still works.

If Lens suddenly looks tiny and faint, Incognito mode is on. Press `Ctrl + Shift + Alt + S` to switch it off.

Whatever mode you use, please follow the rules of your school or workplace about AI tools.

---

## Limits and account status

Your plan sets what you can use. Lens shows your limits on the welcome card and with `/usage`.

- **Message length.** There is a longest message your plan allows. Lens counts what you typed plus what you highlighted. If it is over the limit, Lens tells you how long your message is and what the limit is, and nothing is sent. Shorten it and try again.
- **Daily and monthly limits** on requests and tokens. When you reach one, Lens shows a clear message and locks until the limit resets.
- **Slow down.** If you ask too many times in a minute, Lens asks you to wait a moment.
- **Free trial.** Trial accounts show how many trial tokens are left.
- **Not paid, timed out, or blocked.** The account is locked. The only choice is to sign out, and Lens shows a message from staff.

If staff change your plan, your limits, or your status, it applies to your next question. You don't have to sign in again.

---

## Troubleshooting

**Nothing happens when I click the bookmark.**
- Make sure you are on a normal web page. Browsers don't allow bookmarks to run on their own pages (for example `chrome://` pages or extension stores) or on a blank new tab. Open any ordinary website and try again.
- Open the bookmark's settings and check that the address starts with `javascript:` and that you pasted the **whole** line.
- Some sites with very strict security settings can block bookmarks. Try another site to check that the bookmark itself works.

**"This Lens bookmark was changed."**
The loader checks itself. This means some part of it was changed, cut off, or re-typed. Delete the bookmark and install it again from the original file. See [the note below](#please-read-do-not-edit-the-loader).

**It says my username or password is wrong.**
Check for extra spaces, and use the eye button to see what you typed. Passwords are case-sensitive. After several wrong tries in a row, sign-in is paused for about 15 minutes. Wait, then try once more carefully.

**I'm locked and can only sign out.**
Your account is not paid, has timed out, or has been blocked, or you've hit a limit. The message on the screen says which. If it's a limit, it unlocks when the limit resets. For anything else, email **lenssupportls@gmail.com** with your username.

**"Message too long".**
Your highlight plus your question is over your plan's limit. Highlight less, or type a shorter question.

**Lens looks tiny and faint.**
Incognito mode is on. Press `Ctrl + Shift + Alt + S`.

**I'm signed in on a computer I don't use any more.**
Run `/signout` on any computer. It signs you out everywhere.

**Something went wrong.**
Try again in a moment. If it keeps happening, email **lenssupportls@gmail.com** and say what you were doing when it happened.

**The answer is wrong or doesn't make sense.**
This can happen, especially with the cheaper models. Ask again in different words, highlight a little more or less, or switch to a stronger model with `/model`. Always check important answers yourself.

---

## Please read: do not edit the loader

The loader protects itself. If **anyone** changes it in any way, even one letter, a number, a space, or cutting a piece off the end, it refuses to start and shows "This Lens bookmark was changed".

- Copy the **entire** file, exactly as it is.
- Don't retype it. Copy and paste.
- Don't open it in a program that rewrites text (for example a word processor), because it can change quotes or line endings. A plain text editor is fine.
- Don't pass the loader around. Under the Terms, the code is private and may not be shared, posted or copied. Someone who wants Lens should sign up or email **lenssupportls@gmail.com**.

You don't need to update the bookmark yourself. The loader gets the newest version of Lens from the service each time you click it.

---

## Privacy and security

- Lens sends your highlighted text, your question, and any picture you choose to send to the AI service so it can answer. Don't highlight anything you wouldn't want processed this way, such as passwords or private information.
- Your login is stored in your browser. Run `/signout` on shared computers.
- Your account, plan, usage and saved settings are kept by the service that runs Lens. They can see your usage.

---

## Support

Email **lenssupportls@gmail.com** for any kind of issue, including:

- problems signing up or signing in
- a locked, unpaid, timed-out or blocked account
- payments, renewals and refund questions
- changing your plan or your AI model
- a bug, an error message, or something that looks wrong
- questions about the Terms and Conditions
- asking for a copy of the loader or the Terms

**What to include so we can help quickly:** your username (never your password), what you were doing, what you expected, what happened instead, which website you were on, and which browser you use. A screenshot of the error helps.

Support is by email, so please allow some time for a reply.
