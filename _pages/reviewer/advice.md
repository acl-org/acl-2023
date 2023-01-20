---
title: Reviewing Advice forACL 2023
layout: single
permalink: /reviewer/advice/
sidebar: 
    nav: "reviewer"
toc: false
---

We are re-posting the [reviewing advice from EMNLP 2020](https://2020.emnlp.org/blog/2020-05-17-write-good-reviews) with slight modifications/additions. 

The intention for this page is to provide some advice to reviewers, such that we can identify the best research to be presented in the conference, and provide constructive feedback in order for authors to further improve their papers. We recognize and appreciate the amount of efforts reviewers have contributed, and hope to make that more beneficial. We want all the authors to feel the delight when they read the peer reviews for their papers.

Please take the time to look through these excellent resources.

We hope reiterating some dos and don'ts here can help reviewers as well as authors.

## Who Reads the Review?

A review is a document, and in writing a document, it is useful to think about who is going to read the document.  Let's quickly go through them: 
* The authors: This is probably the reader that you'll think about the most, and that's good (you want to be respectful and thorough ... they are your colleagues, so you should give the review you would like to receive).  One thing to check is whether, after reading the review, the authors have a clear path forward on how to improve the paper: "not enough experiments" is far less actionable than "the results would be stronger with validation on the LDC NYT dataset".  Unlike all of the other readers we mention here, the authors will not see the discussion that happens on Softconf.  While not everything from the discussion period should go into the review, but the authors will see nothing of what happens in the discussion period, so if something new comes to light, make sure to modify your review so that the authors have all of the relevant information.
* Other reviewers: You'll be able to read, compare, and contrast the reviews from the 3-4 other reviewers of the paper.  You will have all read the document closely.  One of the goals of your review is to spark discussion with the other reviewers, so it is okay to open a door for conversation on a particular topic either directly in your review or in the discussion period.  Not all of the reviews need to be consistent, but they can and should interact.  You can say things specifically like (unlike Reviewer 2, I ...).
* The area chair (AC): The area chair is going to have to write a metareview of this paper.  They won't have time to read the paper as carefully as you, the reviewer, will.  So to make their life easier, make your review as self-contained as possible.  If you can explain something very briefly (either with a standalone sentence or with a reference to the current literature ``decoding a la Smith and Eisner''), do that rather than just putting a line reference to the paper. 
* The senior area chair (SAC): Will have to calibrate the metareview of the AC against all the other papers in the area.  They may not have read the paper, so the reviews need to be self-contained to know how this paper fits into the rest of the pool.

## What goes into the Review?

**First, evaluate the paper’s contributions.** This is where you will use your NLP domain knowledge. We advise that you should not accept papers just because their reported results are better, or that they appear to be mathematically sophisticated. These are not sufficient or necessary to constitute contributions. And we advise that you should not reject papers just because their results are not better than state-of-the-art. In the previous \*ACL conferences, some reviewers placed too much emphasis on SOTA performance, giving low scores to any systems that failed to reach that. While we aim to publish the very best work, a more constructive question to ask is "**state of which art?**". As discussed in [this blog post](https://hackingsemantics.xyz/2020/reviewing-models/), a paper could offer a step forward in terms of efficiency, generalizability, interpretability, and many other criteria. A convincing contribution of any kind should not be rejected only for not topping the leaderboards.

Regarding different kinds of contributions, here’s what Prof. Philip Resnik at University of Maryland says:

> I think there would be significant value in encouraging reviewers to think explicitly about the nature of the contribution, and what questions then need to be asked. As a first pass for consideration/discussion:
>
> *   Is this research making a **_scientific_** contribution? If so:
>     *   What is the phenomenon in the world that the authors are seeking to improve our understanding of?
>     *   What do we now know about this phenomenon that we did not know before?
> *   Is this research making an **_engineering_** contribution? If so:
>     *   What is the real-world problem (or set of problems) that this work is making progress on solving?
>     *   Alternatively, if it's not targeting a current real-world problem, what real-world problem(s) will this work help _enable_ solutions of?
> *   Is this research making a **_theoretical_** (e.g. mathematical) contribution? If so:
>     *   What do we know now that we did not know before?
>     *   How does this theoretical or mathematical advance connect to either scientific or engineering goals? (See above.)
>
> Work in computational linguistics might include a mixture of scientific, engineering, and theoretical contributions, rather than just one. But, I am suggesting, if a paper does not make a contribution in _any_ of those three categories, with the sub-bullets having understandable answers, one should seriously consider whether it belongs at the conference.


**Second, consider these other important points** when reading the paper and writing your review:

*   Check what the paper’s claims are, and how the content of the paper supports that claim. If the paper claims X and there is a performance increase, is that really because of X?

*   Be specific in your comments. For example, if you think the authors have neglected to cite key papers, then provide these references in your review. It might be obvious to you, but it’s often less clear to the authors. Being specific will help the authors to formulate a cogent response to the review, and to fix these problems in their paper. However, authors are **not** obliged to cite or draw comparisons with contemporaneous work (i.e. appearing within 3 months of submission), especially if it is not published in a peer-reviewed venue.

*   Be constructive in your advice. Stating that some aspect of the paper is done badly can be helpful in the gatekeeping aspect of review (providing grounds for rejection), but it tends to be less helpful to the authors. Some suggestions of how the authors might improve these problematic aspects can allow them to develop the work into something considerably better.

*   Be kind in your language, even when being critical. It’s easy to get carried away, and write something nasty that you would never say to someone’s face. Try to be polite in your feedback.


**Finally,** it’s becoming more common for people to share reviews on social media, especially when the reviews reject the work on spurious grounds. **These lead us to advise that the following are often _invalid_ bases for rejecting a paper:**

*   The paper’s language or writing style. Please focus on the paper’s substance. We understand that there may be times when the language or writing style is so poor that reviewers can not understand the paper’s content and substance. In that case, it is fine to reject the paper, however you should only do so after making a concerted effort to understand the paper.

*   The paper’s work is on a language other than English. We care about NLP for any language.

*   The paper’s results are not better than SOTA. Please look at the paper’s contributions and findings, as discussed above and in [this blog post](https://hackingsemantics.xyz/2020/reviewing-models/).

*   The paper does not use a particular method (e.g., deep learning). No one particular method is a requirement for good work. Please justify why that method is needed. Think about what the paper’s contributions are, and bear in mind that having a diversity of methods used is not a bad thing.

*   The paper’s method is too simple. Our goal is not to design the most complex method. Again, think what the paper’s contributions and findings are. Often the papers with the simplest methods are the most cited. If a simple method outperforms more complex methods from prior work, then this is often an important finding.

*   The paper’s topic is narrow or outdated. Please be open minded. We do not want the whole community to chase a trendy topic. Look at the paper’s contributions and consider what impact it may have on our community.

*   The paper’s topic is completely new, such that there’s no prior art or all the prior art has been done in another field. We are interested in papers that tread new ground.

*   The paper is a resource paper. In a field that relies on supervised machine learning as much as NLP, development of datasets is as important as modeling work. This [blog post](https://hackingsemantics.xyz/2020/reviewing-data/) discusses what can and cannot be grounds for dismissing a resource paper.

Please refrain from using the reasons above as primary grounds for rejection when writing your reviews. We will ensure authors are aware of these guidelines and can reference them during the author rebuttal period. ACs will be checking reviews carefully based on the above criteria, and may ask that you revise your review, or that you provide objective reasons to justify your positions.

We hope these tips are helpful to reviewers, and hope there will be more authors that appreciate the insightful feedback they get from the reviews, and fewer frustrating authors that complain about review quality.

## Numbers

The most important part of the review is your thorough comments.  However, what many people focus on are numbers.  Thus, it would remis for advice to overlook this part of the process.  ACL 2023 is trying something new this year.  We are splitting this decision into two parts: how sound the paper is and how novel/exciting the paper is.

Soundness goes to how well the paper backs up its claims with evidence and argumentation.  We want all papers to clear a minimum bar for presenting solid, thorough, technically sound research where the claims are well supported by the evidence/arguments.  We suspect that this will have lower variance than novelty.

Novelty captures the more subjective evaluations of the novelty/significance of the contributions, and their potential einteresting-ness to the community. 

Because not everyone will calibrate their scores the same way (this certainly depends on the batch of papers you get too), make sure that your scores are justified in the text of the review.  The AC should be able to understand your justification of the scores to create a consensus score from all of the reviews.

## Best Paper

The review will also ask you to nominate papers for a best paper award.  Reviewers are often a little too conservative in their nominations.  After all, you just spent hours looking for all of the flaws in the paper.  And they think about all of the best papers they've seen in the past (after they've gone through the review process).  Rather than thinking about the question as "is this a best paper", consider the question more of "how could you argue that this will be best paper".  It is okay if this paper is unique in topic or technique, that could be what makes it a best paper.

## Additional Resources

Additional discussions of reviewing in the NLP context:
*   [Discursive advice](https://acl2017.wordpress.com/2017/02/23/last-minute-reviewing-advice/) in ACL 2017 from leading lights in the field: Mirella Lapata, Marco Baroni, Yoav Artzi, Emily Bender, Joel Tetreault, Ani Nenkova, and Tim Baldwin
*   [Two example good reviews](https://naacl2018.wordpress.com/2018/01/20/a-review-form-faq/) from NAACL 2018 presented in their reviewing form
*   [A podcast by Noah Smith](https://soundcloud.com/nlp-highlights/77-on-writing-quality-peer-reviews-with-noah-a-smith) about peer reviews


To read more about the general advice on reviewing, we recommend the following resources:

*   NeurIPS not only instructs reviewers as to what to include in their reviews, but also gives examples of useful reviewer comments in their [Reviewer Guidelines](https://nips.cc/Conferences/2019/PaperInformation/ReviewerGuidelines), organized by evaluation criterion, such as "_Contributions of the submission_", "_Quality of the submission_", "_Clarity_", "_Originality_", and "_Significance_". This will be particularly useful for new reviewers, and also for authors.

*   ICML gives some examples of good reviews. Please refer to the Part 2 of their [Reviewer Guidelines](https://icml.cc/Conferences/2020/ReviewerGuidelines).

*   A blog [article](https://patthomson.net/2019/10/14/reviewing-your-first-paper/) by Pat Thomson about journal review, which shares a broadly similar procedure to conference review. The article is split into three parts, covering how to read the paper critically, how to decide on revisions required and recommendations to the PC, and how to write constructive feedback.

*   Wiley Publishing has a cute video with [10 tips for first-time reviewers](https://players.brightcove.net/3806881048001/rFXiCa5uY_default/index.html?videoId=4518165477001). A list of those tips can be found in the [pdf document](https://authorservices.wiley.com/asset/photos/reviewers.html/journal-reviewers.html/Top_Tips_for_Peer_Review.pdf). One tip that is useful for EVERYONE is tip 8: “Look at the Conclusion First”. Wiley advocates doing so because the Conclusion will give you a good idea whether the research is an exciting development within its own field. But another reason for doing so is to see what the paper is claiming to have done: This often differs from the Abstract and Introduction, which may make more impressive claims than the work actually supports.

*   Elsevier's "Researcher Academy" has produced a video about "[How to write a helpful peer review report](https://researcheracademy.elsevier.com/navigating-peer-review/certified-peer-reviewer-course/31-write-helpful-peer-review-report)", presented by Zoë Mullan, Founding editor and Editor-in-chief of the open access journal "The Lancet Global Health". To watch the video, you have to sign in to join the academy (which is free).

*   Some interesting findings about paper reviews can be found in an early article published in the Journal of the American Medical Association (JAMA), “[What Makes a Good Reviewer and a Good Review for a General Medical Journal?](https://jamanetwork.com/journals/jama/fullarticle/187762)”.

What any of the articles and videos indicated above will give you is CONFIDENCE that you're doing the right thing. (Early Career reviewers will be happy to hear that one of the conclusions of the JAMA paper is that _"Younger age also was an independent predictor for editors' quality assessments_")

