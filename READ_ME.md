# Studio 7 Playbook

A single-page guide for starting and running Studio 7. It's one static file with no build step, no dependencies and no external assets.

The guide has three parts, in order:

1. Before you talk to anyone: define the business, packages and prices, how to get paid, business email, the pitch-to-delivery process, paperwork.
2. Set up your shop: build Studio 7's own site, three fictional demo sites, pick a URL, launch on GitHub Pages. It ends with a ready check.
3. Run the business: the eight steps for each customer, the pitch, build and handoff checklists, the owner's guide.

## Put it on GitHub Pages

1. Create a new GitHub repository (public is simplest for Pages on a free account).
2. Add `index.html` to the root of the repository. Commit to `main`.
3. In the repository, open Settings, then Pages.
4. Under "Build and deployment", set Source to "Deploy from a branch", pick `main` and the `/ (root)` folder, then save.
5. After a minute or two the site is live at `https://<your-username>.github.io/<repository-name>/`.

Part 2 of the guide covers adding a custom domain.

## Things to know

- The page follows the visitor's system theme (dark or light). The button in the top bar switches it, and the choice is remembered in that browser.
- The dark theme uses the Frontier Storyboard tokens as written. The light theme is derived from the system's print and strong-blue tokens, because the system doesn't define a production light theme. The token block at the top of the `<style>` tag and the theme layer under it are where to change colors.
- GitHub Pages sites are public. Anyone with the link can read the playbook. It contains no customer data, but it does describe the process and pricing. For a private copy, use a private repository on a plan that supports private Pages, or open the file locally.
- Checklist ticks are saved in each visitor's own browser. They don't sync between devices.
- Part 2 asks Finn to build three demo sites from prompts in the guide. The guide contains the prompts, not the demo sites themselves.
- Facts to recheck before relying on them: Square's and Stripe's current terms and fees, the GitHub Pages DNS addresses, and domain prices. These change.
- To change the text, edit `index.html`. The content is plain HTML, so searching for a phrase and editing it works fine.
