# Build a Website with AI

**Participant Prompt Pack · SME Hub Asia · 21 November 2026**  
**Trainer · Ye Myint Soe**

Use ChatGPT or Gemini to create a one-page website, open it on your laptop, and update it in your own words. You decide what visitors should see. The same prompt works for a shop, a personal introduction, a portfolio, or another idea you want to share.

## How to use this pack

1. For **your own website**, fill in the [website information worksheet](#website-information-worksheet). Paste your answers into [Prompt 1](#prompt-1-create-your-website).
2. To **practise with a ready-made example**, copy the [bakery example](#complete-bakery-example) or the [portfolio example](#complete-portfolio-example). Each is a complete version of Prompt 1 with the worksheet already filled in.
3. Paste your chosen prompt into a normal ChatGPT or Gemini chat. You can describe your website in Burmese, English, or both.
4. Save the two files the AI gives you and open `index.html` in your browser.
5. When you want a change, choose one of the update prompts below and attach your latest website files.

**On GitHub, use the copy button in the top-right corner of a prompt block.** The instructions outside each block are for you. The first block is a worksheet to fill in. The remaining blocks are prompts you can send to AI.

## Contents

- [Website information worksheet](#website-information-worksheet)
- [Prompt 1 — Create your website](#prompt-1-create-your-website)
- [Complete bakery example](#complete-bakery-example)
- [Complete portfolio example](#complete-portfolio-example)
- [Open your website on your laptop](#open-your-website-on-your-laptop)
- [Prompt 2 — Change one detail](#prompt-2-change-one-detail)
- [Prompt 3 — Add or remove an item](#prompt-3-add-or-remove-an-item)
- [Prompt 4 — Improve a section’s layout](#prompt-4-improve-a-sections-layout)
- [Prompt 5 — Change the visual style](#prompt-5-change-the-visual-style)
- [Burmese design change example](#burmese-design-change-example)
- [Prompt 6 — Add a new section](#prompt-6-add-a-new-section)
- [Prompt 7 — Add a feature](#prompt-7-add-a-feature)
- [Prompt 8 — Fix a problem](#prompt-8-fix-a-problem)
- [Prompt 9 — Fix a missing photo](#prompt-9-fix-a-missing-photo)
- [Save and check your changes](#save-and-check-your-changes)
- [Share your website](#share-your-website)

## Website information worksheet

Answer these questions as if you were explaining your idea to a designer. A few lines are enough to start. Under **What visitors should know or see**, you can write a paragraph or add as many lines as you need. If you already have wording, photo filenames, or public links you want to use, include them in your answers.

For optional questions, you can write **Skip**. If you have no design preference, write **Please suggest a style**.

```text
What this website is for: [What would you like to use this page for?]
Name to display: [What name or title should appear on the page?]
Who should visit: [Who are you making this for?]
What visitors should know or see: [What would you like to share? Add your details here.]
What visitors should do next: [Optional. What would you like someone to do after reading?]
Anything to include or leave out: [Optional. Mention any requests, photos, public links, or details to leave out.]
Website language: [Burmese, English, both, or another preference]
Colors and style: [Describe the look you like, or ask AI to suggest one.]
```

## Prompt 1 Create your website

Replace the single line `[Paste your completed worksheet here.]` with your answers. Copy the whole prompt into ChatGPT or Gemini. The technical instructions are already written for you.

```text
You are a web designer helping me create my first website. Build a mobile-friendly, one-page website using my information below.

MY WEBSITE INFORMATION
[Paste your completed worksheet here.]

PAGE CONTENT AND DESIGN
Choose the sections, their names, and their order based on my answers. Include the sections I request. If I leave the layout open, choose one that suits my content. A short introduction can be enough. Use navigation only when it helps visitors. If I give a main visitor action, make it easy to find and make sure it works.

Use only the facts I supply. Omit anything I mark Skip or leave empty, along with its menu link. Use public contact details only if I supply them for publication. If I mark a detail as a sample, keep it clearly labeled and unlinked. If I give no contact details, leave out contact buttons and messages about adding details later.

Use my chosen language and keep names and titles as supplied. For Burmese, use natural wording, comfortable line spacing, and buttons tall enough to show the full text. Make the page easy to read and use on a phone.

PHOTOS
Use local photos from an images folder where they suit my content. Respect any filenames I provide. If a photo is expected but its path is empty or the file cannot load, show a labeled placeholder that fits the layout. If a section needs no photo, use a text layout. Give meaningful descriptions to informative images.

FILES AND EDITING
Give me two complete files:
1. index.html — the page layout, styling, and code that makes the page work.
2. content.js — the editable wording, headings, button labels, image paths, links, and other website details.

Keep similar items together in easy-to-edit lists in content.js. Adding or removing an item there should update the page automatically. If a list becomes empty, hide its section and menu link. Add short comments showing how to edit the content.

TECHNICAL SETUP
Use plain HTML and JavaScript. Store the editable information in window.siteContent in content.js. Load content.js with a normal script tag before the code that displays the page. The website must open by double-clicking index.html. Use relative file paths. Do not require npm, a build step, JavaScript modules, fetch(), or a local server.

Use Tailwind CSS v4 through this exact script in the HTML head:
<script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>

Use complete Tailwind class names. Load a suitable Google Font with a system font fallback. For Burmese text, use Noto Sans Myanmar or another font that supports Myanmar Unicode. Load only the font weights used. Use Lucide icons through a CDN if they help visitors. Keep important actions understandable if the icons fail to load.

Use safe DOM methods such as textContent for editable text. Make controls keyboard-friendly, show visible keyboard focus, and avoid sideways scrolling on phones. Keep animations minimal. Keep the website frontend-only. Do not add login, checkout, payments, booking systems, or forms that need a server.

WHAT TO RETURN
Return the full index.html and content.js in separate code blocks labeled with their filenames. If you can provide downloadable files, use those exact names. List the photo filenames used and explain where each photo appears.

Give brief instructions for saving the files together, opening the website, and changing one real detail from my content. Explain that the CDN styles, fonts, and any icons need internet access. Mention the Tailwind Play CDN prototype limitation in the setup notes only.
```

## Complete bakery example

Copy this whole block to practise with **Shwe Eain Bakery & Snack**. Notice where the owner puts the menu, prices, and opening hours. They are all answers to **What visitors should know or see**.

```text
You are a web designer helping me create my first website. Build a mobile-friendly, one-page website using my information below.

MY WEBSITE INFORMATION
What this website is for: Introduce Shwe Eain Bakery & Snack and give people one page where they can browse what we make before visiting.
Name to display: Shwe Eain Bakery & Snack
Who should visit: People in Yangon looking for everyday treats, gifts, or snacks to share at a gathering.
What visitors should know or see:
- We are a small Yangon bakery offering cakes, cookies, and snacks.
- Butter Cookies — Butter cookies for everyday treats and gifts. 8,000 MMK per box. Photo: images/butter-cookies.jpg
- Banana Cake — A banana cake to enjoy with tea or share with family. 6,000 MMK per loaf. Photo: images/banana-cake.jpg
- Brownies — Chocolate brownies for sharing and celebrations. 12,000 MMK per box. Photo: images/brownies.jpg
- We also make custom birthday cakes, event snack boxes, and bulk orders for offices and celebrations.
- Location: Yangon, Myanmar. Opening hours: Daily, 9 AM–6 PM.
What visitors should do next: Tap a button near the top to see our baked items and prices on this page.
Anything to include or leave out: Use images/hero.jpg for the main bakery photo. Show our opening hours where they are easy to find. Leave out phone, email, Facebook, and street address. We have no public contact links to share yet.
Website language: Natural Burmese for descriptions, headings, and buttons. Keep the bakery name and the three product names in English.
Colors and style: Warm cream, golden brown, and dark brown. I want the page to feel welcoming, like a neighborhood bakery.

PAGE CONTENT AND DESIGN
Choose the sections, their names, and their order based on my answers. Include the sections I request. If I leave the layout open, choose one that suits my content. A short introduction can be enough. Use navigation only when it helps visitors. If I give a main visitor action, make it easy to find and make sure it works.

Use only the facts I supply. Omit anything I mark Skip or leave empty, along with its menu link. Use public contact details only if I supply them for publication. If I mark a detail as a sample, keep it clearly labeled and unlinked. If I give no contact details, leave out contact buttons and messages about adding details later.

Use my chosen language and keep names and titles as supplied. For Burmese, use natural wording, comfortable line spacing, and buttons tall enough to show the full text. Make the page easy to read and use on a phone.

PHOTOS
Use local photos from an images folder where they suit my content. Respect any filenames I provide. If a photo is expected but its path is empty or the file cannot load, show a labeled placeholder that fits the layout. If a section needs no photo, use a text layout. Give meaningful descriptions to informative images.

FILES AND EDITING
Give me two complete files:
1. index.html — the page layout, styling, and code that makes the page work.
2. content.js — the editable wording, headings, button labels, image paths, links, and other website details.

Keep similar items together in easy-to-edit lists in content.js. Adding or removing an item there should update the page automatically. If a list becomes empty, hide its section and menu link. Add short comments showing how to edit the content.

TECHNICAL SETUP
Use plain HTML and JavaScript. Store the editable information in window.siteContent in content.js. Load content.js with a normal script tag before the code that displays the page. The website must open by double-clicking index.html. Use relative file paths. Do not require npm, a build step, JavaScript modules, fetch(), or a local server.

Use Tailwind CSS v4 through this exact script in the HTML head:
<script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>

Use complete Tailwind class names. Load a suitable Google Font with a system font fallback. For Burmese text, use Noto Sans Myanmar or another font that supports Myanmar Unicode. Load only the font weights used. Use Lucide icons through a CDN if they help visitors. Keep important actions understandable if the icons fail to load.

Use safe DOM methods such as textContent for editable text. Make controls keyboard-friendly, show visible keyboard focus, and avoid sideways scrolling on phones. Keep animations minimal. Keep the website frontend-only. Do not add login, checkout, payments, booking systems, or forms that need a server.

WHAT TO RETURN
Return the full index.html and content.js in separate code blocks labeled with their filenames. If you can provide downloadable files, use those exact names. List the photo filenames used and explain where each photo appears.

Give brief instructions for saving the files together, opening the website, and changing one real detail from my content. Explain that the CDN styles, fonts, and any icons need internet access. Mention the Tailwind Play CDN prototype limitation in the setup notes only.
```

## Complete portfolio example

Copy this whole block to practise with **Thiri Aung**, a student who wants to share two pieces of design work. She answers the same eight questions as the bakery owner. Someone introducing themselves as an actor, teacher, founder, or student can use those questions to tell a different story.

```text
You are a web designer helping me create my first website. Build a mobile-friendly, one-page website using my information below.

MY WEBSITE INFORMATION
What this website is for: Give me a personal page I can share when applying for a design internship.
Name to display: Thiri Aung
Who should visit: Internship recruiters and people who might like to collaborate with me.
What visitors should know or see:
- I am a student learning visual design through class assignments and practice.
- Tea Shop Poster — I made this practice poster to explore how typography and color can give a tea shop its own look. Photo: images/tea-shop-poster.jpg
- Campus Event Graphics — For a class assignment, I designed two social posts for a campus event. Photo: images/campus-event-graphics.jpg
- I enjoy working with layout, typography, and basic photo editing.
What visitors should do next: Tap “View my work” to jump to the two pieces on this page.
Anything to include or leave out: Start with a short text introduction. Let the two designs be the main images. Leave out a profile photo and contact section.
Website language: Burmese for the introduction and descriptions. Keep my name, the two project titles, and the “View my work” button in English.
Colors and style: Cream and navy. Use a simple layout with enough space to see each design clearly.

PAGE CONTENT AND DESIGN
Choose the sections, their names, and their order based on my answers. Include the sections I request. If I leave the layout open, choose one that suits my content. A short introduction can be enough. Use navigation only when it helps visitors. If I give a main visitor action, make it easy to find and make sure it works.

Use only the facts I supply. Omit anything I mark Skip or leave empty, along with its menu link. Use public contact details only if I supply them for publication. If I mark a detail as a sample, keep it clearly labeled and unlinked. If I give no contact details, leave out contact buttons and messages about adding details later.

Use my chosen language and keep names and titles as supplied. For Burmese, use natural wording, comfortable line spacing, and buttons tall enough to show the full text. Make the page easy to read and use on a phone.

PHOTOS
Use local photos from an images folder where they suit my content. Respect any filenames I provide. If a photo is expected but its path is empty or the file cannot load, show a labeled placeholder that fits the layout. If a section needs no photo, use a text layout. Give meaningful descriptions to informative images.

FILES AND EDITING
Give me two complete files:
1. index.html — the page layout, styling, and code that makes the page work.
2. content.js — the editable wording, headings, button labels, image paths, links, and other website details.

Keep similar items together in easy-to-edit lists in content.js. Adding or removing an item there should update the page automatically. If a list becomes empty, hide its section and menu link. Add short comments showing how to edit the content.

TECHNICAL SETUP
Use plain HTML and JavaScript. Store the editable information in window.siteContent in content.js. Load content.js with a normal script tag before the code that displays the page. The website must open by double-clicking index.html. Use relative file paths. Do not require npm, a build step, JavaScript modules, fetch(), or a local server.

Use Tailwind CSS v4 through this exact script in the HTML head:
<script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>

Use complete Tailwind class names. Load a suitable Google Font with a system font fallback. For Burmese text, use Noto Sans Myanmar or another font that supports Myanmar Unicode. Load only the font weights used. Use Lucide icons through a CDN if they help visitors. Keep important actions understandable if the icons fail to load.

Use safe DOM methods such as textContent for editable text. Make controls keyboard-friendly, show visible keyboard focus, and avoid sideways scrolling on phones. Keep animations minimal. Keep the website frontend-only. Do not add login, checkout, payments, booking systems, or forms that need a server.

WHAT TO RETURN
Return the full index.html and content.js in separate code blocks labeled with their filenames. If you can provide downloadable files, use those exact names. List the photo filenames used and explain where each photo appears.

Give brief instructions for saving the files together, opening the website, and changing one real detail from my content. Explain that the CDN styles, fonts, and any icons need internet access. Mention the Tailwind Play CDN prototype limitation in the setup notes only.
```

## Open your website on your laptop

1. Create a folder for your website, such as `my-website`.
2. Save `index.html` and `content.js` directly inside that folder. If the AI gives you code blocks, copy each into a separate plain-text file. Copy only the code inside the block.
3. Check the filenames. On Windows, if Notepad offers **Save as type**, choose **All files** and use **UTF-8** encoding so Burmese text saves correctly. The filenames should end in `.html` and `.js`.
4. If your page uses photos, create an `images` folder inside `my-website`. Add the photos using the filenames in your AI response. You can try the page before adding the photos.
5. Connect to the internet and double-click `index.html`. Your browser will open the page. The internet connection loads Tailwind styles, Google Fonts, and any Lucide icons used.

| File or folder | What it does |
|---|---|
| `index.html` | Controls how the page looks and how buttons, menus, and other features work. |
| `content.js` | Holds the words, image filenames, links, and details you can edit. |
| `images/` | Holds the actual photo files. |

**Try one small edit yourself.** Open `content.js` in a text editor and search for a phrase you recognize from the page. Change just that phrase, keeping the quotation marks and commas around it. Save and refresh your browser. For the bakery, try changing `8,000 MMK` to `10,000 MMK`. For Thiri’s page, try changing a sentence in her introduction.

## How to ask for changes

Start with a copy of your working website folder as a backup. Attach your latest `index.html` and `content.js` to the chat and describe one change. Attaching the files saves you from pasting the entire page into your message.

A good change request answers three questions: **Where on the page? What should change? What should a visitor see or be able to do afterward?**

## Prompt 2 Change one detail

Use this for a price, a sentence, a name, a button label, or another piece of text. Copy the current wording from your page so the AI can find it.

```text
I have attached my latest index.html and content.js.

On my page, change this detail:
Where it appears: [Section or item name]
Current wording: [Copy the exact wording]
New wording: [Write the replacement]

Make this edit in content.js if the detail is already stored there. Keep the rest of the page as it is.

Return the complete file or files you changed, with the exact filenames. Tell me which file to replace and what I should see after I save and refresh.
```

## Prompt 3 Add or remove an item

Use this when your page already has a group of similar items. For example, the bakery could add a Chocolate Muffin, or Thiri could add a third design. For removal, give the exact name of the item.

```text
I have attached my latest index.html and content.js.

Section to update: [Use the heading shown on my page]
What I want to do: [Add an item or remove an item]
Item name: [Exact name]
Details to include if adding: [Wording, image filename, link, or other details I want to show]

Use the same layout as the other items in that section. Keep the items editable in content.js so I can add, change, or remove one later. If I remove the last item, hide the empty section and its menu link.

Return the complete file or files you changed, with the exact filenames. Tell me which files to replace, where to put any new photo, and what to check after refreshing.
```

## Prompt 4 Improve a section’s layout

Describe the part that feels awkward when you use the page. For the bakery, you might want prices closer to the item names. For Thiri’s page, you might want visitors to see a whole poster without cropping its edges.

```text
I have attached my latest index.html and content.js.

Improve this part of my page:
Section or heading: [Where the change belongs]
What feels awkward now: [What you notice when looking at or using the page]
What I would like instead: [Describe the result]
On a phone, I want: [Describe how this section should look or behave]

Use the existing wording and photos. Apply the layout change to this section and keep its content editable in content.js.

Return the complete file or files you changed, with the exact filenames. Tell me what to check on a laptop and at phone width.
```

## Prompt 5 Change the visual style

You can ask for everyday changes such as “make the Burmese text easier to read,” “give the photos more space,” or “use our dark green for the main button.”

```text
I have attached my latest index.html and content.js.

Please update the visual style of my website.
The look I want: [Describe it in your own words]
The changes I care about most: [Colors, text size, spacing, buttons, icons, or another detail]
Apply this to: [The whole website or a specific section]

Keep the current wording, images, links, and features. Make text readable and buttons easy to recognize on a phone. Use the existing Google Fonts and Lucide CDN setup where appropriate.

Return the complete file or files you changed, with the exact filenames. Tell me which files to replace and what visible differences to check.
```

## Burmese design change example

ပြင်ချင်တဲ့အချက်ကို မြန်မာလို ရေးလို့လည်း ရပါတယ်။ ဥပမာ မုန့်ဈေးနှုန်းတွေကို ဖုန်းပေါ်မှာ ရှာဖတ်ရတာ ခက်နေတယ်ဆိုရင် လက်ရှိဖိုင်နှစ်ဖိုင်ကို ပူးတွဲပြီး ဒီလိုတောင်းဆိုနိုင်ပါတယ်။

```text
လက်ရှိ website ရဲ့ index.html နဲ့ content.js ဖိုင်နှစ်ဖိုင်ကို ပူးတွဲပေးထားပါတယ်။

မုန့်တစ်မျိုးချင်းစီရဲ့ ဈေးနှုန်းကို ဖုန်းနဲ့ကြည့်တဲ့အခါ ရှာရလွယ်အောင် ပြင်ပေးပါ။ မုန့်နာမည်အောက်မှာ ဈေးနှုန်းကို ထားပြီး စာလုံးနည်းနည်းပိုကြီးပေးပါ။ မြန်မာစာကြောင်းတွေ ဖတ်ရလွယ်အောင် စာကြောင်းကြား အကွာအဝေးကိုလည်း နည်းနည်းချဲ့ပေးပါ။

လက်ရှိ မုန့်နာမည်၊ ဈေးနှုန်းနဲ့ ဓာတ်ပုံတွေကို ဒီအတိုင်းထားပေးပါ။ ပြင်ထားတဲ့ဖိုင်တိုင်းကို ဖိုင်နာမည်နဲ့အတူ အစအဆုံး ပြန်ပေးပါ။ ဘယ်ဖိုင်ကို အစားထိုးရမယ်၊ ပြီးရင် browser မှာ ဘာကို စစ်ကြည့်ရမယ်ဆိုတာ တိုတိုရှင်းရှင်း ပြောပြပေးပါ။
```

## Prompt 6 Add a new section

Use this when the information you want to share has no place on the current page. For example, you might add **Frequently Asked Questions**, **Upcoming Appearances**, or **A Note From Me**. Choose a heading that makes sense for your audience.

```text
I have attached my latest index.html and content.js.

Add a new section to my website.
Section heading: [What visitors should see as the title]
Put it here: [For example, below a heading already on my page]
What to show: [Paste the actual information]
How visitors should use it: [Read it, open a link, click a question to see the answer, or another action]

Match the existing design. Keep the section's wording and details in content.js. If it contains several entries, make it easy for me to add or remove one. Use only the information I give you. If an essential detail is missing, ask me for it.

If my page has a navigation menu and this section belongs in it, add a working link. If I later remove all the section's content, hide both the section and its menu link.

Return the complete file or files you changed, with the exact filenames. Tell me which files to replace and how to try the new section.
```

## Prompt 7 Add a feature

A feature gives visitors something to **do**. For example, if a page has many entries, a search box can help people find one. Use a section that already exists on your website.

```text
I have attached my latest index.html and content.js.

Add a search box to this section: [Exact heading on my page]

Visitors should be able to type a word and see matching entries from that section. Search the names and descriptions already on the page. For English words, match uppercase and lowercase letters equally. When there are no matches, show a short message in my website language. When visitors clear the box, show every entry again.

Match the website's design and make the search usable on a phone and with a keyboard. Keep the entries editable in content.js. The feature must work when I open index.html directly.

Return the complete file or files you changed, with the exact filenames. Tell me how to test a matching word, a word with no results, and an empty search box.
```

## Prompt 8 Fix a problem

Tell the AI what you did, what you expected, and what actually happened. A screenshot helps with visual problems. Attach the current files even if an earlier version is already in the chat.

```text
I have attached my latest index.html and content.js. Please help me fix this problem.

What I did: [What I clicked, changed, or opened]
What I expected: [What should have happened]
What actually happened: [What I saw]
Where it happens: [Laptop, phone, local file, or live website]
Last change I remember: [Optional]
Screenshot or error message: [Attach or paste it if available]

Use the attached files to find the cause. If you need a detail to identify the problem, ask me. Explain the fix in simple language and keep the existing content and design wherever possible.

If code needs to change, return each complete changed file with its exact filename. If I only need to rename, move, or replace a file, tell me exactly what to do. Give me a short way to test the fix.
```

## Prompt 9 Fix a missing photo

First, check the **actual filename**, including its extension. `brownies.jpg` and `brownies.png` are different names. Match uppercase and lowercase letters too, especially when a photo works on your laptop but disappears on the live site.

```text
I have attached my latest index.html and content.js.

A photo is missing from my website.
Where it should appear: [Section, item, or heading]
Actual photo filename: [Exact filename including .jpg, .png, .webp, or another extension]
Folder where I saved it: [For example, images]
What I see: [A labeled placeholder, blank space, or something else]
Where the problem happens: [On my laptop, on the live website, or both]

Compare my filename and folder with the path used by the website. Tell me the simplest fix. Use my own photo and keep the labeled placeholder for times when the image cannot load.

If code needs to change, return the complete changed file with its exact filename. If the fix is to rename, move, or upload the photo, give me those steps.
```

## Save and check your changes

1. Keep a backup of the version that works.
2. Replace only the files the AI changed. Keep the exact names `index.html` and `content.js`, even if your browser adds `(1)` to a download.
3. Put new photos in the matching folder. Save, then refresh the browser.
4. Try the change as a visitor. Click the button, read the new wording, open the new section, or search for an item.
5. Make the browser window narrow. Check that the text fits, the menu is usable, and Burmese letters display fully.
6. Before publishing an update, check names, numbers, links, and photos against your original information.

**If the AI reply stops halfway through a file**, use this follow-up.

```text
Please send the complete [index.html or content.js] from beginning to end in one code block. Include all the code I need to save this file. Send only this file in your next reply.
```

## Share your website

**For the workshop preview**, use the website folder you tested on your laptop. Keep `index.html` at the top level with `content.js` beside it, and include `images/` if your page uses photos. Follow the trainer’s Netlify or Vercel publishing demonstration. When the live link is ready, open it on your phone and try the main visitor action. For future updates, publish to the same hosting project so the link stays familiar to visitors.

**Before making the page public**, replace practice content with information you want to share, use photos you have permission to publish, and remove private details from the entire folder. Visitors can access the files you upload, including `content.js`.

**A custom domain** is an optional address for the same website. You can use the hosting link during class. If you later register a domain, add it to your hosting project, follow the DNS instructions provided by the host, and test the new address.

**For a production website**, replace the workshop’s Tailwind Play CDN setup with compiled CSS. The workshop version uses the CDN so you can build and preview the page without installing development tools. [Tailwind Play CDN documentation](https://tailwindcss.com/docs/installation/play-cdn)
