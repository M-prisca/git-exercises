## Round 1

1. Turn the project folder into a Git repository and record your first snapshot of the files. Then change your current branch's name to trunk, and afterwards back to main. Connect the project to a GitHub repository you create and publish your work to it.
2. Make a new branch called staging. From within staging, create another branch called preview. Return to staging and remove the preview branch.
3. Create menu.html, hours.html, and gallery.html one at a time, and after each one set its changes aside temporarily (without committing) so your working folder is clean again. Then bring back the hours.html changes, and afterwards bring back only the menu.html changes leaving gallery.html set aside.
4. Create a branch feat/reviews, add a reviews.html page, record the change, publish the branch, and open a request to merge it into main.
5. Create a branch feat/specials, add a specials.html page, and commit it. Then create a separate branch feat/promo (from main). Bring just that one commit from feat/specials onto feat/promo, without merging the whole branch.

## Round 2

1. Create a branch `feat/newsletter,` add a `newsletter.html` page, record it, publish it, and open a merge request into `main`. Have a review and merge it.
2. On a branch `feat/menu-update`, change a specific line in `menu.html`. Then, on `main`, change the **same line** in a different way. Publish both. Your merge request will now clash with `main`, inspect the differences between the two branches, then combine `main` into your feature branch and resolve the clash so both can live together.
3. Make a change to `gallery.html` and set it aside temporarily. Then discard that change entirely so your project returns to its last recorded state.
4. On main, make a change to `index.html` and commit it (e.g. an "opening hours" line). You then decide that commit was a mistake. Create a **new** commit that reverses that commit's changes (don't erase history), then publish and open a merge request. _(B3 – revert)_
5. Register a second publishing destination named `backup` (a different GitHub repo). Make a change to `index.html` and publish it to **both** destinations.
