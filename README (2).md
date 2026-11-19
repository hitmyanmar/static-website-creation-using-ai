# Build a Website with AI

## Participant Prompt Pack

**SME Hub Asia · 21 November 2026 · Trainer Ye Myint Soe**

Create a business landing page or personal portfolio, update its content and design, and ask AI to fix problems. This pack uses `index.html`, an editable `content.js` file, and an `images` folder.

## How to use this pack

1. Read the instructions above the prompt you need.
2. Copy the complete text inside that prompt’s block using its copy button in GitHub’s rendered view, when available.
3. Replace any **[placeholders]** with your own information.
4. Paste it into a normal ChatGPT or Gemini conversation and send it.
5. For website updates, attach your **latest** website files before sending the prompt.

**Normal text is guidance for you. Text inside the fenced blocks is the material to copy.** The worksheet block is for preparing your information; the other blocks are prompts to send to AI.

You can describe changes in Burmese or English. You do not need programming terms to explain what you want.

## Contents

- [Website information worksheet](#website-information-worksheet)
- [Create your website](#prompt-1-create-your-website)
- [Complete bakery example](#complete-bakery-example)
- [Complete portfolio example](#complete-portfolio-example)
- [Add a portfolio project](#add-a-portfolio-project)
- [Change a price](#prompt-2-change-a-price)
- [Add a product](#prompt-3-add-a-product)
- [Improve product cards](#prompt-4-improve-product-cards)
- [Change colors](#prompt-5-change-colors)
- [Burmese design change example](#burmese-design-change-example)
- [Add frequently asked questions](#prompt-6-add-frequently-asked-questions)
- [Add product search](#prompt-7-add-product-search)
- [Fix a problem](#prompt-8-fix-a-problem)
- [Fix a missing photo](#prompt-9-fix-a-missing-photo)
- [Save changes and check the result](#save-changes-and-check-the-result)

## Website information worksheet

Copy this worksheet into your notes and fill it in. Replace every [placeholder]. Use “Not provided” for missing contact details. You will paste the completed information into Prompt 1.

```text
What this website is for: [Describe it in your own words]
Name to display: [Name, brand, or title]
Who should visit: [Who you want to reach]
What visitors should know or see: [Write a few notes in your own words]
What visitors should do next: [Optional]
Anything to include or leave out: [Optional. Add any links or media you want to use.]
Website language: [Burmese / English / Both]
Colors and style: [Your preference, or ask AI to suggest]
```

## Prompt 1 Create your website

Copy the entire prompt below. Before sending it, replace [Paste your completed website information here.] with your worksheet. Leave the prepared technical instructions as written; you do not need to learn those terms.

```text
You are a web designer helping a beginner create their first website.

Create an attractive, mobile-friendly, one-page website for the website type I choose using my information below.

MY WEBSITE INFORMATION
[Paste your completed website information here.]

GOAL AND CONTENT
Use my audience and main visitor action to decide what to highlight. Use navigation only if it helps visitors move between sections. Include public contact links only when supplied.

Choose the sections and their names based on what I want visitors to know, see, or do. Use sections I explicitly request. If I leave the structure open, suggest a simple layout that fits my material. A short introduction can be enough for a first version.

Skip sections marked Skip or left empty, including their navigation links. Do not invent facts or fill empty sections with sample material.

Use my chosen language. If I choose Burmese, write natural, concise Burmese with readable line spacing. Keep business and product names as supplied. Use a clean layout with readable text, generous spacing, and suitable colors. Make navigation work on phones.

PHOTOS AND CONTACT
Use photos from an images folder. Give me simple filenames such as images/hero.jpg and images/product-1.jpg, and tell me which photo belongs to each filename.

When an image path is empty or a photo cannot load, show an attractive labeled placeholder. Keep its dimensions consistent and do not use external placeholder services.

Use only my real contact details for working links. Omit missing contact methods. If I supply details marked as samples or placeholders, display them as examples without clickable links. If no usable contact details are provided, show a short message saying contact details will be added later.

FILES AND EDITING
Give me exactly two complete code files plus an image filename list:

1. index.html: The website layout, styling instructions, and the code that makes the page work.
2. content.js: All editable website information, including page headings, text, button labels, image paths, and links.

Keep items that share the same layout in easy-to-edit lists inside content.js. Adding or removing an item must automatically update the page. Add short comments explaining how to change text, prices, images, and contact details. Keep the field names straightforward.

PREPARED TECHNICAL INSTRUCTIONS
Use plain HTML and JavaScript. Store editable content in window.siteContent in content.js and load it using a normal script tag before rendering. Use Tailwind CSS v4 through this exact script in the HTML head:
<script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>

Do not require npm, frameworks, builds, JavaScript modules, fetch(), or a local server. The page must open by double-clicking index.html when internet is available for Tailwind. Use complete literal Tailwind class names. Insert content text safely with textContent or equivalent safe DOM methods. Keep image paths relative and handle missing photos without broken-image icons. Include meaningful image descriptions, keyboard-friendly controls, and visible keyboard focus. Avoid horizontal scrolling on small screens.

Do not add login, checkout, payments, booking systems, or forms that need a server. Do not add login, checkout, payments, booking systems, or forms that need a server. Use Google Fonts to match the site's style. Choose fonts that support the website's language. For Burmese text, use Noto Sans Myanmar or another font with Myanmar Unicode support. Load only the font weights you use and include a system font fallback. Use Lucide icons if necessary via its CDN where they help visitors understand an action or find information. Keep text labels for important actions, or give icon-only buttons accessible names. If the icon script fails to load, the page should still be usable.

Keep the code simple and animations minimal. The website must open directly from index.html without npm or a build step. Mention in the setup instructions that internet access is needed to load Tailwind, Google Fonts, and Lucide from their CDNs.

WHAT TO RETURN
Return the complete index.html and content.js in separate labeled code blocks. Do not omit code or give partial snippets. If you can also provide downloadable files, include them with the exact filenames.

Then list the required image filenames and briefly explain how to save both files together, add the images folder, open the website, and change a piece of text.

In the setup explanation, note that internet is needed for Tailwind CDN. Explain that Tailwind Play CDN is intended for development prototypes; a production release should use compiled CSS. Keep this explanation outside the customer-facing website.
```

## Complete bakery example

This is the complete Shwe Eain Bakery & Snack example, ready to copy as one message. Use it for practice, or adapt the reusable prompt above for your own business. The sample has no working contact details.

```text
You are a web designer helping a Myanmar small-business owner create their first website.

Create an attractive, mobile-friendly, one-page business website using my information below.

MY BUSINESS INFORMATION
Business name: Shwe Eain Bakery & Snack
What we do: A small Yangon bakery offering cakes, cookies, and snacks for everyday treats, gifts, and special occasions.
Main visitor action: Explore products and find contact information.
Products:
- Butter Cookies: Cookies for everyday treats and gifts. 8,000 MMK per box. Image: images/butter-cookies.jpg
- Banana Cake: Banana cake to enjoy with tea or share with family. 6,000 MMK per loaf. Image: images/banana-cake.jpg
- Brownies: Chocolate brownies for sharing and celebrations. 12,000 MMK per box. Image: images/brownies.jpg
Services:
- Custom birthday cakes: Enquire about a cake for your celebration.
- Event snack boxes: Enquire about snack boxes for meetings and events.
- Bulk orders: Contact us to discuss quantities and requirements.
About us: A small bakery in Yangon offering cakes, cookies, and snacks, with enquiries welcome for custom cakes, event snack boxes, and bulk orders.
Location: Yangon, Myanmar
Full address: Not provided
Opening hours: Daily, 9 AM–6 PM
Phone: Not provided
Facebook: Not provided
Email: Not provided
Website language: Natural Burmese descriptions and labels; English business and product names.
Colors and style: Warm cream, golden brown, and dark brown. Welcoming, clean, and easy to read.
Hero photo: images/hero.jpg
Footer: Business name and a simple copyright notice.

GOAL AND CONTENT
Help visitors understand my business, explore my products or services, and contact me through the details I provide.

Include a header and navigation, a welcoming introduction at the top, products and/or services, an About section, contact information, and a footer with my business name and copyright notice.

Only include sections relevant to my business. If I have no products or no services, omit that section and its navigation link. Ask me if essential information is missing. Do not invent reviews, awards, discounts, policies, certifications, or contact details.

Use my chosen language. If I choose Burmese, write natural, concise Burmese with readable line spacing. Keep business and product names as supplied. Use a clean layout with readable text, generous spacing, and suitable colors. Make navigation work on phones.

PHOTOS AND CONTACT
Use photos from an images folder. Give me simple filenames such as images/hero.jpg and images/product-1.jpg, and tell me which photo belongs to each filename.

When an image path is empty or a photo cannot load, show an attractive labeled placeholder. Keep its dimensions consistent and do not use external placeholder services.

Use only my real contact details for working links. Omit missing contact methods. If I supply details marked as samples or placeholders, display them as examples without clickable links. If no usable contact details are provided, show a short message saying contact details will be added later.

FILES AND EDITING
Give me exactly two complete code files plus an image filename list:

1. index.html: The website layout, styling instructions, and the code that makes the page work.
2. content.js: All editable business information, page headings, button labels, image paths, products, services, and footer text.

Keep products and services in easy-to-edit lists inside content.js. Adding or removing an item must automatically update the page. Add short comments explaining how to change text, prices, images, and contact details. Keep the field names straightforward.

PREPARED TECHNICAL INSTRUCTIONS
Use plain HTML and JavaScript. Store editable content in window.siteContent in content.js and load it using a normal script tag before rendering. Use Tailwind CSS v4 through this exact script in the HTML head:
<script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>

Do not require npm, frameworks, builds, JavaScript modules, fetch(), or a local server. The page must open by double-clicking index.html when internet is available for Tailwind. Use complete literal Tailwind class names. Insert content text safely with textContent or equivalent safe DOM methods. Keep image paths relative and handle missing photos without broken-image icons. Include meaningful image descriptions, keyboard-friendly controls, and visible keyboard focus. Avoid horizontal scrolling on small screens.

Do not add login, checkout, payments, booking systems, or forms that need a server. Do not require external fonts or icon libraries. Keep code simple and animations minimal.

WHAT TO RETURN
Return the complete index.html and content.js in separate labeled code blocks. Do not omit code or give partial snippets. If you can also provide downloadable files, include them with the exact filenames.

Then list the required image filenames and briefly explain how to save both files together, add the images folder, open the website, and change one price.

In the setup explanation, note that internet is needed for Tailwind CDN. Explain that Tailwind Play CDN is intended for development prototypes; a production release should use compiled CSS. Keep this explanation outside the customer-facing website.
```

## Complete portfolio example

Copy this full example to try a portfolio for someone who does not own a business yet.

```text
You are a web designer helping a beginner create their first website.

Create an attractive, mobile-friendly, one-page website for the website type I choose using my information below.

MY WEBSITE INFORMATION
Website type: Personal portfolio
Name to display: Thiri Aung
Short introduction: A student learning visual design
Who should visit: Internship recruiters and potential collaborators
Main visitor action: View my work
Projects: Tea Shop Poster — a practice poster exploring typography and color; Campus Event Graphics — a class project where I designed two social posts
Skills: Layout, typography, and basic photo editing
About: I am building a portfolio through class and practice projects.
Public contact details: Skip
Website language: Burmese descriptions with English project titles
Colors and style: Cream and navy with a simple layout

GOAL AND CONTENT
Use my audience and main visitor action to decide what to highlight. Use navigation only if it helps visitors move between sections. Include public contact links only when supplied.

Choose the sections and their names based on what I want visitors to know, see, or do. Use sections I explicitly request. If I leave the structure open, suggest a simple layout that fits my material. A short introduction can be enough for a first version.

Skip sections marked Skip or left empty, including their navigation links. Do not invent facts or fill empty sections with sample material.

Use my chosen language. If I choose Burmese, write natural, concise Burmese with readable line spacing. Keep business and product names as supplied. Use a clean layout with readable text, generous spacing, and suitable colors. Make navigation work on phones.

PHOTOS AND CONTACT
Use photos from an images folder. Give me simple filenames such as images/hero.jpg and images/product-1.jpg, and tell me which photo belongs to each filename.

When an image path is empty or a photo cannot load, show an attractive labeled placeholder. Keep its dimensions consistent and do not use external placeholder services.

Use only my real contact details for working links. Omit missing contact methods. If I supply details marked as samples or placeholders, display them as examples without clickable links. If no usable contact details are provided, show a short message saying contact details will be added later.

FILES AND EDITING
Give me exactly two complete code files plus an image filename list:

1. index.html: The website layout, styling instructions, and the code that makes the page work.
2. content.js: All editable website information, including page headings, text, button labels, image paths, and links.

Keep items that share the same layout in easy-to-edit lists inside content.js. Adding or removing an item must automatically update the page. Add short comments explaining how to change text, prices, images, and contact details. Keep the field names straightforward.

PREPARED TECHNICAL INSTRUCTIONS
Use plain HTML and JavaScript. Store editable content in window.siteContent in content.js and load it using a normal script tag before rendering. Use Tailwind CSS v4 through this exact script in the HTML head:
<script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>

Do not require npm, frameworks, builds, JavaScript modules, fetch(), or a local server. The page must open by double-clicking index.html when internet is available for Tailwind. Use complete literal Tailwind class names. Insert content text safely with textContent or equivalent safe DOM methods. Keep image paths relative and handle missing photos without broken-image icons. Include meaningful image descriptions, keyboard-friendly controls, and visible keyboard focus. Avoid horizontal scrolling on small screens.

Do not add login, checkout, payments, booking systems, or forms that need a server. Do not require external fonts or icon libraries. Keep code simple and animations minimal.

WHAT TO RETURN
Return the complete index.html and content.js in separate labeled code blocks. Do not omit code or give partial snippets. If you can also provide downloadable files, include them with the exact filenames.

Then list the required image filenames and briefly explain how to save both files together, add the images folder, open the website, and change a piece of text.

In the setup explanation, note that internet is needed for Tailwind CDN. Explain that Tailwind Play CDN is intended for development prototypes; a production release should use compiled CSS. Keep this explanation outside the customer-facing website.
```

## Add a portfolio project

Attach your latest `index.html` and `content.js` and fill in the project details.

```text
Add a project to my portfolio. Create a Projects section if I do not have one yet.
Title: [Project name]
What I did: [Your role and what you made]
Photo or link: [Optional]

Match my current design. Keep the project details editable in content.js. Give me each complete updated file and tell me which files to replace.
```

## Prompt 2 Change a price

Back up your website folder and attach the latest index.html and content.js. The example changes Butter Cookies from 8,000 to 10,000 MMK; replace the name and prices for your own business.

```text
I have attached the latest index.html and content.js for my website.

Change the Butter Cookies price from 8,000 MMK per box to 10,000 MMK per box.

Keep the existing design and all other business information unchanged. Keep the price editable in my content file.

Give me the complete updated files that changed, with their exact filenames. Do not send partial snippets. Tell me which files to replace and what to check after refreshing the browser.
```

## Prompt 3 Add a product

Attach both current website files. Replace the sample product information if needed. After saving the updated files, add the matching photo to your images folder.

```text
I have attached the latest index.html and content.js for my website.

Add this product to my existing Products section:
Name: Chocolate Muffin
Description: A chocolate muffin to enjoy as a snack.
Price: 4,000 MMK per piece
Photo: images/chocolate-muffin.jpg

Use the same card design as my other products. Show a labeled placeholder if the photo is missing. Keep this product in my content file so I can edit or remove it later.

Give me the complete updated files that changed, with their exact filenames. Do not send partial snippets. Tell me which files to replace and what to check after refreshing the browser.
```

## Prompt 4 Improve product cards

Attach both current website files. This example changes the product layout and photo sizes. Describe what you want visitors to see using everyday language.

```text
I have attached the latest index.html and content.js for my website.

Improve the Products section:
- Show three products in a row on large screens, two on tablets, and one on phones.
- Make product photos taller without stretching them.
- Make prices easier to notice and Burmese descriptions comfortable to read.

Keep the existing products, prices, colors, other sections, and mobile menu. Keep content editable through content.js.

Give me the complete updated files that changed, with their exact filenames. Do not send partial snippets. Tell me which files to replace and what to check after refreshing the browser.
```

## Prompt 5 Change colors

Attach both current website files. Replace cream and deep green with your chosen colors before sending.

```text
I have attached the latest index.html and content.js for my website.

Change the website colors to cream backgrounds, deep green buttons and headings, and dark readable body text. Make sure buttons and links are easy to see.

Keep the current layout, photos, business details, and features.

Give me the complete updated files that changed, with their exact filenames. Do not send partial snippets. Tell me which files to replace and what to check after refreshing the browser.
```

## Burmese design change example

မြန်မာလိုလည်း ပြင်ချင်တဲ့အချက်တွေကို ရေးပြောနိုင်ပါတယ်။ လက်ရှိ index.html နဲ့ content.js ဖိုင်နှစ်ဖိုင်ကို ပူးတွဲပြီး အောက်က prompt ကို အသုံးပြုပါ။

```text
လက်ရှိ website ရဲ့ index.html နဲ့ content.js ဖိုင်တွေကို ပူးတွဲပေးထားပါတယ်။

Products အပိုင်းမှာ စျေးနှုန်းစာသားကို ပိုထင်ရှားအောင် ပြင်ပေးပါ။ ဖုန်းနဲ့ကြည့်တဲ့အခါ မြန်မာစာတွေကို ဖတ်ရလွယ်အောင်လည်း ပြင်ပေးပါ။ လက်ရှိ ပစ္စည်းအချက်အလက်နဲ့ စျေးနှုန်းတွေကို မပြောင်းပါနဲ့။

ပြင်ထားတဲ့ဖိုင်ကို အစအဆုံးပြန်ပေးပြီး ဘယ်ဖိုင်ကို အစားထိုးရမလဲ၊ ဘယ်လိုစစ်ကြည့်ရမလဲ ဆိုတာ ရိုးရိုးရှင်းရှင်း ရှင်းပြပေးပါ။
```

## Prompt 6 Add frequently asked questions

Attach both current files. Replace the placeholder with your real questions and answers. If your site has no Services section, change the requested position to a section that exists.

```text
I have attached the latest index.html and content.js for my website.

Add a Frequently Asked Questions section below Services and a link to it in the top menu. Use these questions and answers:

[Paste your actual questions and answers here.]

If I have not supplied the answers, ask me for them before writing the updated files. Do not invent business policies.

Let visitors click a question to show or hide the answer. Make this work with a keyboard too. Match the existing design. Keep all questions and answers in content.js so I can easily add, edit, or remove them later. If I remove all questions, hide the section and its menu link.

Keep the other content and features working.

Give me the complete updated files that changed, with their exact filenames. Do not send partial snippets. Tell me which files to replace and what to check after refreshing the browser.
```

## Prompt 7 Add product search

Optional exercise for a website with a Products section. Attach both current files. The search will filter the products already on the page.

```text
I have attached the latest index.html and content.js for my website.

Add a search box above the products. Visitors should be able to type a product name or words from its description to find matching products. Search should ignore differences between uppercase and lowercase English letters.

Show a friendly message when nothing matches. Clearing the search should show all products again. Use wording in my website language and match the existing design.

Keep products editable in content.js. Do not add a login, database, or paid service.

Give me the complete updated files that changed, with their exact filenames. Do not send partial snippets. Tell me which files to replace and what to check after refreshing the browser.
```

## Prompt 8 Fix a problem

Attach both current files, fill in all three descriptions, and include a screenshot if it helps show the problem. Keep your working backup.

```text
I have attached the latest index.html and content.js for my website.

After my last update, this problem appeared:
[Describe what you see.]

I expected:
[Describe what should happen.]

It happens when:
[For example: opening the page, clicking the mobile menu, or searching.]

I have also attached a screenshot if available. Find and fix the cause using these current files. Ask me for missing information if necessary. Preserve the existing content and design except where a correction is needed. Explain the cause in simple language.

Give me the complete updated files that changed, with their exact filenames. Do not send partial snippets. Tell me which files to replace and what to check after refreshing the browser.
```

## Prompt 9 Fix a missing photo

Attach both current files and enter the exact photo filename and folder. Include the extension, such as .jpg or .png.

```text
I have attached the latest index.html and content.js for my website.

This photo is not appearing:
[Product name or hero section]

My photo filename is: [Exact name including .jpg, .jpeg, .png, or .webp]
It is saved inside: [Folder name]

Check the image path and missing-photo handling. Tell me whether I need to rename or move the photo. Do not replace it with a random online image.

Give me the complete updated files that changed, with their exact filenames. Do not send partial snippets. Tell me which files to replace and what to check after refreshing the browser.
```

## Save changes and check the result

### Repeat this routine for each update

1. Back up your working website folder.
2. Attach the latest `index.html` and `content.js` to AI.
3. Describe one change and review its answer.
4. Replace only the files AI changed, keeping the exact filenames.
5. Save, refresh your browser, and check the result.
6. To update the live website, upload the updated website folder to the **same hosting project**.

### Keep matching files together

Your website folder contains:

- `index.html` — the page structure, appearance, and behavior.
- `content.js` — editable business text, products, services, and image paths.
- `images/` — the photo files referenced by the website.

Keep photo filenames and paths consistent. Do not mix files from different generated website versions.

Check that your files are named `index.html` and `content.js`, without an extra `.txt` extension. If downloads have names such as `index(1).html` or `content(1).js`, rename the matching pair to `index.html` and `content.js`.

### Check your changes

- Is the requested change visible?
- Are the product names, prices, and Burmese wording correct?
- Do photos or labeled placeholders appear?
- Does the page work at a phone-sized window width?
- Do navigation links and the mobile menu work?
- Does the FAQ or search work if you added it?
- Do contact links go to the correct destination?

If something breaks, keep your working backup and use Prompt 8 with the updated files. Do not overwrite your only working copy.

### If AI returns incomplete code

Send this follow-up:

```text
Please return the complete updated file from beginning to end, with no omitted sections. Provide one file per response if needed. Tell me the exact filename to save.
```

### Before publishing your website

Replace sample details with your own, check that your contact and project links work, and use photos you have permission to use. Files uploaded as part of a static website are public, so do not put passwords or private customer information in `content.js`.

This workshop uses Tailwind Play CDN for the prototype and requires internet to load its styles. Tailwind recommends compiled CSS for production. Arrange that conversion before treating the prototype as the final production website; it is outside this prompt pack.

Reference: [Tailwind Play CDN documentation](https://tailwindcss.com/docs/installation/play-cdn).
