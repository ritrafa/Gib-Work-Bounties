# Statement
This technical review is performed as a response to [Dean's List Bounty #6 for TipLink](https://github.com/dean-s-list/Gib-Work-Bounties/issues/6). The review has been performed in the following stages:

1. Initial Review - meant to generate first-impressions, initial considerations, and highlight areas of further review.
2. Implementation Test - meant to generate understanding of any turtorial's ease-of-use, correctness of examples, and aesthetic value.
3. Code Review - meant to consider code quality, completeness, and documentation.
4. Summary - meant to offer suggestions and summarized feedback.

# Initial Review
## Docs Website
1. Website is clean and easy to understand, but the largest question that comes to mind is what audience is the documentation website aimed at? Potentially it may be worthwhile to consider a dual channel approach where the documentation website directly has a path for TipLink developers vs recipients (which goes to your excellent consumer-facing tutorials/site), that way if a recipient finds themself on this site they have a clear path out.
2. The first CTA on the site is directing what appears to be offering a 20-minute tutorial *video*, based on their being a time mentioned. Since the tutorial is not recorded and instead is linking to relatively standard documentation, it may be worthwhile to change the icon to an open book or remove the '20 mins' and stopwatch entirely.
3. The bottom simple explanation is great, perhaps arrows showing it is a procedure between the steps is warranted, 
4. The link out the NPM on the navbar that persists on the entire docs site feels excessive, especially considering the quick start guide covers its use well. Perhaps it would be better suited in the footer.
5. [Getting Started](https://docs.tiplink.io/docs/category/getting-started) section is clear.
6. [Api Reference > TipLinkClient](https://docs.tiplink.io/docs/api-reference/client) (Pro) should use h4 headers for each individual class definition to allow deep linking and to give them more separation. It also would be valuable to have a 1-2 sentence description of what each class is, the most notable example is that a 'Campaign' has never been described or referenced in the docs until you first see it as a class. 'Dispenser' suffers the same problem, but is a more clear term, so the lack of explanation is less problematic.
7. [Extended Examples](https://docs.tiplink.io/docs/category/extended-examples) are excellent, and I look forward to using them during testing. The warning on 'Transactions Guide' is duplicated, but I recognize that may have been intentional.

## Github
1. It would be nice to have a public member or members listed on the organization, expecially since the team is not private.
2. Ditto to have the most critical repo pinned.

## Various Other Items
1. [TipLink Pro](https://tiplink.io/pro/campaigns) has a small spelling error, should be statuses or status, not statues.