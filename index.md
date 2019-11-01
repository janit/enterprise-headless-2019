## Headless Content Management in the Enterprise

- Jani Tarvainen, eZ Systems - Boye Aarhus 19 conference

--

## Agenda

- Let's discuss a how headless CMS<br>fits in a large enterprise setting
- An interactive session, ask and comment!
- Everyone's opinions and experiences valuable
- We are all here to learn!

---

## Reality check

--

### Who is using a headless CMS at scale?

- What are they using it for?
- To replace a web publishing platform?
- A mobile or web app that has some content?
- Consolidating or using for individual projects?

--

### Have you gone (or plan to go) headless?

- Do you think a headless approach would be right for you?
- What benefits and disadvantages do you see?
- What features are most important to your team?

--

### What does a "classic CMS" do for you today?
- Do you use it for site management?
- Is it your integration platform?
- A facade for exposing custom apps to public?

--

### What kind of Content API are you looking at?
- Content as a Service offering?
- A classic CMS with a REST/GraphQL/??? API
- Roll your own (really?)

--

### What approach for the front end
- Static HTML generation
- Dynamic server (custom, Next.js, Nuxt.js, etc.)
- FaaS (AWS Lambda or similar)

---

## Day to day tasks

--

## Day to day tasks

- Imagine a comples public facing multilingual site
- What do your editors work with every day?
- Consider those tasks with a headless system

--

### Content creation and previews

- Does they need workflows? Using CaaS or CMS API?
- How do you preview? Using a custom front end?
- Do they use a custom or extended admin UI?

--

### Site management

- How to modify visual appearance, content of landing pages?
- Which tool would you use for it? Custom, 3rd party?
- What if it was developer task like in 1999?

--

## Managing menus

- How do your users manage a menu?
- Some parts automatic, some static? How to configure?
- Which tool would you use for this? CMS or site head?

--

## Creating forms, etc.
- How do you create, manage form creation and data collection?
- Can you place forms flexibly to pages, within content etc?
- How integrated is this (logins, etc.) for the editor?

--

## Adding tracking scripts
- How do you add 3rd party tracking scripts?
- Do the standard scripts work, or do you need extra effort?
- What if your tracking script has broken markup or JS?

--

## SEO
- Can you manage metadata in a smart way?
- How do you handle redirects?
- What about Canonical URLs, sitemaps, etc.?

---

## Implementation complexity

--

### Changes in thinking
- The front end becomes a strategic choice?
- What is the lifespan of your front end package?
- Is it like moving to a microservices?<br>Benefits, challenges of this from app world?

--

### Implementation options

- Do you plan on going fully static?
  - Cheap, secure, limited (see JAM stack)
- Running a server (Node, etc.)?
  - Some extra complexity, very flexible
- Serverless (AWS Lambda, etc.)?
  - Pay as you go, flexible, how is the

--

### Ongoing maintentance

- Will you need to think of future of two systems?
- Are there grey areas possible in feature responsibility?
- Changes in the one product can break things surprisingly<br>(CaaS deprecates feature, etc.)


---

## Implementation and maintenance cost

--

### Development cost
- Is initial development cheaper, more costly or the same?
- How much experience does your implement partner have?
- Do the features you need require significant custom dev?
- What about integrations (authentication, etc.)?


--

### Project and program management cost?

- You will have more vendors, how will this affect cost?
- What about complexity over years, who knows the system from A to Z in five years?
- If you're not going with CaaS, then you'll need to maintain two systems - Content API and head?

--

### Hosting cost
- Hosting prices for head can vary (static, dynamic, faas)
- When using a CaaS, how will the pricing of it scale?
- What if CaaS prices change, can you switch backends feasibly?


---

## Product capability

--

## Features out of the box

- Compared to a CMS / DXP product how much<br>do you need to build for your project as custom work?
- Does your backend provide all required capabilities<br>(granular permissions, workflows, media management, etc.)
- What about integrations? Are there ready made ones,<br>or everything needs to be tailored?

--

## Back end choice considerations

- Traditional CMS
  - Throwing out a lot of standard features out the door?
  - Are paying for features you don't use?
  - Is the admin interface customization needed?
- CaaS
  - You get a full service for a specific task
  - Do you need to add more services (for forms, layouts management, etc)
  - Is switching vendors feasible if you want to do so?

---

## Wrapping up
- Maybe a hybrid solution is more realistic for large operations?
- Are we still lacking best practises?
- Did you learn something new
- Discussions