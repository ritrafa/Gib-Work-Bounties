# Introduction
This technical review is performed as a response to [Dean's List Bounty #6 for TipLink](https://github.com/dean-s-list/Gib-Work-Bounties/issues/6). The review has been performed in the following stages:

1. [Initial Review](#o1) - meant to generate first-impressions, initial considerations, and highlight areas of further review.
2. [Implementation Test](#o2) - meant to generate understanding of any turtorial's ease-of-use, correctness of examples, and aesthetic value.
3. [Code Review](#o3) - meant to consider code quality, completeness, and documentation.
4. [Summary](#o4) - meant to offer suggestions and summarized feedback.

# <a id="o1"></a>Initial Review
## Docs Website
1. Website is clean and easy to understand, but the largest question that comes to mind is what audience is the documentation website aimed at? Potentially it may be worthwhile to consider a dual channel approach where the documentation website directly has a path for TipLink developers vs recipients (which goes to your excellent consumer-facing tutorials/site/faq), that way if a recipient finds themself on this site they have a clear path out.
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
1. [TipLink Pro](https://tiplink.io/pro/campaigns) sidebar has a small spelling error, should be statuses or status, not statues (See below)
    * ![alt text](image.png)
2. Feature request - it would be great if a ui-spawned campaign can request that a minter shares some details with the organizer, such as email, socials, or a custom field. Ideally it could be configured to be pre or post mint.
3. Feature request - that api emails could have customizable text, as the default message limits the flexibilty of how you can use it in a program.

# <a id="o2"></a>Implementation Test
## Quickstart
To run this test, I'm going to use the solana dapp scaffold template, and create a basic site to test out each of TipLink's features and implementation guides.

## Areas of Focus 
0. [Prior to testing out the dev functions, I am going to test out the ui methods of these functions.](#it0)
1. [Use the quickstart guide/basic examples for the bare minimum fuctionality.](#it1)
2. [Create a TipLink wallet transaction](#it2)
3. [Create a TipLink QR Code](#it3)
4. [Create a TipLink Mint](#it4)
5. [Create/initate an emailed TipLink](#it5)
6. [Create an escrowed wallet](#it6)

## <a id="it0"></a>0. UI Methods

## <a id="it1"></a>1. Basic Fuctionality

## <a id="it2"></a>2. Wallet Transaction

## <a id="it3"></a>3. QR Code

## <a id="it4"></a>4. Mint

## <a id="it5"></a>5. Emailed TipLink

## <a id="it6"></a>6. Escrow

# <a id="o3"></a>Code Review

# <a id="o4"></a>Summary