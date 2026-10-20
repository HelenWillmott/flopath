# FloPath

Live at https://flopath.co.uk. Helps students pick post-GCSE subjects and see which UK degree courses they unlock.

## Hosting
GitHub Pages, deployed from the `main` branch (root). `CNAME` sets the custom domain; don't delete it.

## Releasing
1. Changes go on a branch and open as a pull request against `main`.
2. Check the page in the PR (open `index.html` locally).
3. Merge the PR. Pages publishes `main` to flopath.co.uk within a few minutes.

Rollback: revert the merge commit on `main`.

Note: the page saves progress in the browser under the localStorage key `flopath` and migrates the old `uni-route-finder` key on load. Keep that migration.
