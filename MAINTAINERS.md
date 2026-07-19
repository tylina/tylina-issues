# Maintainer setup

After creating `github.com/tylina/tylina-issues`:

1. Keep the repository public and enable Issues.
2. Enable **Settings → Security → Private vulnerability reporting**.
3. Add repository topics such as `tylina`, `typst`, `feedback`, and `desktop-editor`.
4. Create `bug`, `enhancement`, `question`, `needs-info`, and `confirmed` labels if those workflow states are useful.
5. Before pushing a release tag, run the private source repository's non-publishing Release workflow
   and check every installer plus `SHA256SUMS.txt`. A verified tag build mirrors those assets to this
   repository automatically; do not upload a separate set by hand.

Release notes should state:

- version and preview/stable status;
- supported operating systems and architectures;
- signing and notarization status;
- known installation issues;
- a link to the Tylina website and feedback forms.

GitHub automatically displays “Source code” archives for this repository. Those archives contain only this public feedback repository; they are not the source code of the proprietary Tylina desktop application. State this explicitly in each release note to avoid confusion.
