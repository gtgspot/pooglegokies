build with [Next.js](https://nextjs.org). It requires Node.js v18.17+.

**1. Clone the repository**
```
git clone https://github.com/tgspot/spin-wallet.git
```

**2. Install dependencies**
```
npm install
```

**3. Run dev server**
```
npm run dev
```

**4. Edit config**
```
src/app/resources/config
```

**5. Edit content**
```
src/app/resources/content (or content-i18n for localization)
```

**6. Create blog posts / projects**
```
Add a new .mdx file to src/app/[locale]/blog/posts or src/app/[locale]/work/projects
```

# **Features**
```
- Automatic open-graph and X image generation with next/og
- Automatic schema and metadata generation based on the content file

## **Design**
- Responsive layout optimized for all screen sizes
- Timeless design without heavy animations and motion
- Endless customization options through [data attributes]

## **Content**
- Render sections conditionally based on the content file
- Enable or disable pages for blog, work, gallery and about / CV
- Generate and display social links automatically
- Set up password protection for URLs

## **Localization (NEW)**
- Magic Portfolio now supports localization with the next-intl library
- See more info in resources/config.js

# **Authors**

Connect with us on Threads or LinkedIn.

Lorant Toth: [Threads](https://www.threads.net/@lorant.one), [LinkedIn](https://www.linkedin.com/in/tothlorant/)  
Zsofia Komaromi: [Threads](https://www.threads.net/@zsofia_kom), [LinkedIn](https://www.linkedin.com/in/zsofiakomaromi/)

Localization added by [François Hernandez](https://github.com/francoishernandez)

# **Get involved**

- Report a [bug](https://github.com/gtgspot/apiagent/issues/new?labels=bug&template=bug_report.md).

# **License**

Distributed under the CC BY-NC 4.0 License.
- Commercial usage is not allowed.
- Attribution is required.

See `LICENSE.txt` for more information.

# **Deploy with Vercel**
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Ftgspot%2Fspin-wallet&project-name=spin-wallet&repository-name=spin-wallet&redirect-url=https%3A%2F%2Fgithub.com%2Ftgspot%2Fspin-wallet&demo-title=tgspot%20spin-wallet&demo-description=Showcase%20your%20designers%20or%20developer%20portfolio&demo-url=https%3A%2F%2Fpragmaticplay-casino.com&demo-image=https%3A%2F%2Fpragmaticplay-casino.com%2Fimages%2Ftemplates%2Fspin-wallet%2Fcover.jpg)