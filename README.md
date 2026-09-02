# bayda-legal

Hosting only. This repo exists so that **https://baydalabs.github.io/bayda-legal/** resolves —
that URL is registered in App Store Connect as Bayda's privacy policy, and TestFlight beta
review checks it.

## ⚠️ This is not the source of truth

`index.html` is a **copy**. The original is `legal/privacy-policy.html` in the Bayda app repo,
where it sits beside the schema it describes and is reviewed with it. Edit it there, then copy
it here. Editing this copy directly is how the two drift, and the one that is wrong is the one
the public reads.

There is a Markdown twin (`legal/privacy-policy.md`) in that repo too; it is the readable
source the HTML is kept in step with.

## When this must be updated

The policy is deliberately **not** revised feature by feature — its current inaccuracies all
*over*-describe data sharing (a social feed that is not built, notifications nothing can
generate), and over-disclosure harms nobody.

**The exception, which must not be missed:** the day the social feed ships, those same
sentences stop being over-cautious and start *under*-describing real sharing. The policy has to
be updated in the same change as the feed — never after it.
