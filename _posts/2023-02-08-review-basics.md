---
title: "ACL'23 Peer Review Process"
author: program-chairs
author_profile: true
tags:
  announcement
  peer-review
categories:
  blog
---


<p style="text-align: center;font-style: italic">based on <a href="https://aclrollingreview.org/reviewertutorial">"How to review for ARR"</a> by Anna Rogers, Isabelle Augenstein <br/>
modified by Anna Rogers, Jordan Boyd-Graber, Naoaki Okazaki </p>

You may have heard of the NeurIPS experiments ([2014](https://arxiv.org/abs/2109.09774), [2021](https://blog.neurips.cc/2021/12/08/the-neurips-2021-consistency-experiment/)) with assigning the same papers to two sets of reviewers. Their results suggest that about 50% of the accepted NeurIPS papers would have been rejected, had they simply been assigned to different reviewers. This is obviously a frustrating situation for the authors, going through rounds of arbitrary rejections. 

Why does this happen? Here are a few possible culprits:

* Variance in the **experience of reviewers**. Some reviews are by experienced reviewers and some are by novices; yet, to date there has been little effort to provide systematic training. 
* Differences in understanding the **key evaluation criteria**. What counts as a "weakness" - a fundamental flaw or a lack of clarification experiment? What exactly does "overall recommendation" mean - the personal interest in the topic or how solid the research is? Just how much should different weaknesses "cost" the authors?
* Implicit **biases** that we all have due to our social and academic backgrounds. The same approach may receive different evaluation if it is tested on a popular or a niche task, on English or any other language, with focus on engineering or linguistic aspects, and if it had been preprinted by a well-known lab and received much attention.

This tutorial is part of an effort to improve the overall quality of reviews at ACL'23 conferences, aiming to address the above issues. Part I provides a general overview of the typical peer review process for the novice reviewers and authors; if you are familiar with this, feel free to skip this part. **We are asking all reviewers and authors to read [Part II](2023-02-09-review-acl23.md)**, since it outlines the policies and review forms specific to ACL23. The reviewers need to adhere to the conference policies. The authors will be able to point to violations thereof in the author response, and the meta-reviewers will take that into account.

In this tutorial:

1. [Before the paper assignment](#1-before-the-paper-assignment)
2. [Check that you can/should perform the assignment](#2-check-that-you-can-should-perform-the-assignment)
   - [Am I qualified to review this?](#am-i-qualified-to-review-this)
   - [Do I have a conflict of interest with this submission?](#do-i-have-a-conflict-of-interest-with-this-submission)
3. [Plan your time](#3-plan-your-time)
4. [How to read for review](#4-how-to-read-for-review)
5. [Who are you writing to?](#5-who-are-you-writing-to)
6. [Author response](#6-author-response)
7. [Discussion period](#7-discussion-period)<br/>
[Resources](#resources)

## 1. Before the paper assignment 

All the information about submissions and reviews that you receive as part of your assignment is **confidential**. If you participate in discussions of peer review on social media, please make sure that your comments/examples are general enough that no submissions can be identified, and the authors cannot identify you. Do not refer to individual papers.

Check that you have provided all the information about you, which the venue asked for - any sign-up forms, reviewer profiles etc. This is used for computing conflicts of interest and paper-reviewer assignments. 

When you accept an invitation to review for ACL conferences or ARR, please make sure that your Semantic Scholar profile is accurate and up-to-date, and provided in the relevant forms. For ACL 2023, the semantic scholar field is set through softconf global profile (log in to the ACL site, in the top left corner find User > Account Information > Go to the global profile). This information is used in the automatic paper-reviewer matching process, so the more accurate it is - the more likely you are to get papers in your area at *ACL venues.


## 2. Check that you can/should perform the assignment 


### Am I qualified to review this? 

As soon as you get an assignment, skim the paper to check whether this is **something that you are qualified to review**. The assignments are made based on a semi-automatic process, and, even with careful checks by the area chair / action editor, you may feel like you are not qualified to review a given submission.  

Yet, even in the best-case scenario the matches will not always be perfect. For very novel work or atypical papers, it is inherently difficult to find available qualified reviewers. The possibility of a close match also depends on the set of people in the reviewing pool: a submission in a large and popular subfield is more likely to find the right reviewers. And even large subfields may experience a lack of well-matching reviewers when they are still actively growing. Moreover, sometimes a less obvious match may also be a conscious decision on the part of the chair/editor, e.g., to collect reviewers from different perspectives when the paper is interdisciplinary, or when it focuses on less popular topics and languages. 

So, the bad news is that realistically, you will sometimes be asked to review papers that are a bit outside of your own subfield. That is ok and to be expected, as long as you are sufficiently familiar with the core methodology. If your expertise does not cover certain aspects of the submission, your review should specify that, and most NLP venues let you indicate your confidence score in the review form. 

The good news is that the less-than-perfect matches also have upsides: you get to expand your repertoire, the authors get feedback on what needs more clarification/explanation, and NLP in general gets more intellectual exchange between subfields. 


### Do I have a conflict of interest with this submission? 

If the venue implements a fully or partially anonymous review process (*ACL conferences do), the second thing to check is whether **you know or can guess who the authors are.** The problem with implicit social biases is that they are unconscious; we may be 100% sure that we do not think worse of a paper just because it is written by someone from a group minoritized in computing research, and that we are not pre-disposed to like papers coming from famous labs, but we cannot really trust our conscious selves.

Thus, when you get the assignment, do check that [anonymity is preserved](https://www.aclweb.org/adminwiki/index.php?title=ACL_Policies_for_Submission,_Review_and_Citation). If it is not, the paper should be **desk-rejected**: contact your chair or action editor about this. You can also indicate that the paper should be desk-rejected if it does not follow the style guides or goes over the page limit (which does _not_ include the ethical considerations section). 

If anonymity is preserved, but you happen to know who the authors are from personal communication, social media or talks, ask for re-assignment if possible, especially if you have a conflict of interest (because you know the authors personally, have or will work with them etc.). For the papers where it is impossible to maintain anonymity (e.g., because they are [too famous](https://medium.com/@ryancotterell/we-should-anonymize-model-names-during-peer-review-bcab0cc78946), or the authors are easy to guess for anyone who works in the same narrow subfield), the ACL policy is to indicate your awareness of the authors' identity in the review form (more on that later).

The third check is on **academic conflicts of interest**. If the submission looks like something that is very close to your own work about to be submitted, it is best to recuse yourself. You can contact your senior area chair this way.


## 3. Plan your time

When you accept an assignment, please **block the time in your calendar for working on that review and submitting it on time**, preferably at least a few days before the deadline - to give yourself some buffer in case of unexpected life events. If you are a novice reviewer, submitting your review early also gives your area chair / action editor the time to catch any grave issues.

How much time will you need? That varies by reviewer, paper, and experience. A way of estimating it would be to calculate what your average time for (a) an in-depth reading of a paper is that is as close to your area as the submission, (b) writing and editing about half a page of an article. You may also need to participate in the forum discussion with other reviewers before the reviews are sent to the authors.

If at all possible, reviewing should _not _be done in a single session. When you first read a paper, you may have a knee-jerk reaction to it that would make it harder to write a useful review. For example, you may fundamentally dislike the topic, or the method that was chosen, or [the conclusions are at odds with what you already believe](https://www.acpjournals.org/doi/abs/10.7326/0003-4819-116-11-958_2). It is best to read the paper and let it sink in for a few days, and then work on the review. If you write a first-impression draft at once, make sure to revisit it later.


## 4. How to read for review 

Everybody's process is different, but one strategy that seems to be often used, but **not** very well suited for peer review is commenting _during_ the very first read. You do need to first at least skim the paper and understand the overall type of contribution and the framework in which the authors are working. If you do not do that, you are likely to start critiquing the paper from the perspective of a “prototypical” NLP paper in your area (e.g., an experimental paper proposing a SOTA system for English). That mental model might bias you against other types of contributions (e.g., resource papers, model or linguistic analysis, data processing/annotation strategies, reproduction studies, surveys, position pieces, negative results). Any study should be judged for what it is, and not for what you think it should be.

For experimental papers, a useful trick is to avoid looking at the results when first skimming the paper. When you start actually reading, carefully read the introduction and the methodology sections. After that, pause and ask yourself: is it clear what the research question is and what was done? Do you believe this would answer that question? Do you want to know the answer? Will the answer advance the field? Only then you should look at the results. This way you will be better able to focus on the _knowledge_ gained in the paper: the result may be negative, but if you believe that the experiments are sound and the question worth asking, something that could save time to many others - this is also a valid contribution, as per the ACL [call for papers](https://2023.aclweb.org/calls/main_conference/).

Note whether the paper is long or short, and adjust your expectations accordingly. Long papers are supposed to describe completed work, with thorough evaluation and analysis. A short paper may present proof of concept, an interesting finding, a convincing point, but it is **not** expected to have extensive evaluation and analysis: only the minimal (but sufficiently convincing) evidence for the claim.

While you read, you may want to look up some references or concurrent work. This should be done cautiously: many papers have non-anonymous preprints, and you may accidentally discover the identity of authors, which would open you up to social biases.

## 5. Who are you writing to? 

A review is a document, and in writing a document, it is useful to think about who is going to read the document. Let's quickly go through them:

* **The authors:** This is probably the reader that you'll think about the most, and that's good (you want to be respectful and thorough ... they are your colleagues, so you should give the review you would like to receive). One thing to check is whether, after reading the review, the authors have a clear path forward on how to improve the paper: "not enough experiments" is far less actionable than "the results would be stronger with validation on the LDC NYT dataset". Unlike all of the other readers we mention here, the authors will not see the discussion that happens on the review platform. While not everything from the discussion period should go into the review, the authors will see nothing of what happens in the discussion period, so if something new comes to light, make sure to modify your review so that the authors have all of the relevant information to revise their paper.
* **Other reviewers:** You'll be able to read, compare, and contrast the reviews from the 3-4 other reviewers of the paper. One of the goals of your review is to spark discussion with the other reviewers, so it is okay to open a door for conversation on a particular topic either directly in your review or in the discussion period. Not all of the reviews need to be consistent, but they can and should interact. After reading other reviews, you can edit yours to say things specifically like “unlike Reviewer 2, I …” (remembering to be professional and constructive).
* **The area chair (AC):** The area chair is going to have to write a metareview of this paper. They won't have time to read the paper as carefully as the reviewers will. So to make their life easier, make your review as specific and self-contained as possible. (We expand on this with examples below.)
* **The senior area chair (SAC):** Will have to calibrate the metareview of the AC against all the other papers in the area. They may not have read the paper, so the reviews need to be self-contained to know how this paper fits into the rest of the pool.


## 6. Author response 

After all reviews are in, the authors will have a chance to respond to them. Here is [a great guide on responding to reviewers](https://deviparikh.medium.com/how-we-write-rebuttals-dc84742fece1) that we highly recommend. Remember, the response is addressed not only by the reviewers but also to the chair.

The primary purpose of the author response period is to make sure that the reviewers understand the paper correctly. If the reviewer misunderstood the claims/contributions or is asking about something that is in fact stated in the paper, please state where. 

If the reviewers ask to reframe the research questions or claims, or make some other changes that would be easy to do in the camera-ready version, please state how you will address that. Unfortunately, conferences are not well equipped to handle revisions, and it is up to the reviewers and chairs to be convinced or not.

If the reviewers are asking for experimental results that were not a part of the original submission, but that have been performed since the submission - you may report these, but the submission will be evaluated for acceptance in its submission version. In your response, consider whether these results are necessary to back up the claims of your paper, or this is something nice to have but not a part of the central claim. In the former case such missing results are a weakness, in the latter - a suggestion/recommendation.

We highly encourage you to read part 2 of this review tutorial, especially the conference policy part. If you received a review that violates these policies, please flag this in the rebuttal form. 

Finally - **please, do respond to the reviews even if they are very negative**. This should be done at least to thank the reviewers: they are volunteers who donated their time to read your work. If they were able to find serious issues with your work, this means that they really helped you to improve it and grow as a researcher. If there were issues with the review that fall under conference policy violations - by pointing it out you help to strengthen the peer review norms in the field, so that it happens less often in the future. And even if they simply misunderstood it, the process is mutually beneficial: you learned that the paper needs to be clearer to reach a broader audience, and if you clarify the misunderstanding, you'll help the reviewers to grow. 


## 7. Discussion period 

After the author responses are in, the area chair may invite the reviewers to discuss the paper, especially when there is much variation in the scores. Please participate in that. A major goal here is to catch any mistakes, misunderstandings, or violations of the reviewer guidelines. It is also a good chance to just exchange opinions with peers on something that you all read, and learn more about how reviewers think in the process. This is very handy as an author!  


# Resources  

**General peer review process**

EACL 2021 tutorial on peer review, pt. II - The Actual Review (Karën Fort): [slideslive](https://slideslive.com/38955744), [slides](https://github.com/reviewingNLP/EACL2021T5/blob/main/EACL_2021_pt2_theActualReview.pdf)

**General advice and reviewing philosophy**

* Advice on peer review from Mirella Lapata, Marco Baroni, Yoav Artzi, Emily M.Bender, Joel Tetreault, Ani Nenkova, Tim Baldwin: [https://acl2017.wordpress.com/2017/02/23/last-minute-reviewing-advice/ ](https://acl2017.wordpress.com/2017/02/23/last-minute-reviewing-advice/)
* A podcast interview with Noah Smith: [https://soundcloud.com/nlp-highlights/77-on-writing-quality-peer-reviews-with-noah-a-smith](https://soundcloud.com/nlp-highlights/77-on-writing-quality-peer-reviews-with-noah-a-smith)
* Rebekah Baglini and Christine Parsons on how to avoid harsh language in peer review: [https://www.nature.com/articles/d41586-020-03394-y](https://www.nature.com/articles/d41586-020-03394-y) 

**Examples of good reviews**

* Two examples of peer review from NAACL 2018: [https://naacl2018.wordpress.com/2018/01/20/a-review-form-faq/](https://naacl2018.wordpress.com/2018/01/20/a-review-form-faq/)

**Reviewing specific aspects of papers**

* Jesse Dodge and Noah Smith on the reproducibility checklist: [https://2020.emnlp.org/blog/2020-05-20-reproducibility/](https://2020.emnlp.org/blog/2020-05-20-reproducibility/) 
* EACL 2021 tutorial on peer review, pt. III - Reviewing Results Section (Kevin Cohen): [slideslive](https://slideslive.com/38955745), [slides](https://github.com/reviewingNLP/EACL2021T5/blob/main/EACL_2021_pt3_resultsSection.pdf)
* EACL 2021 tutorial on peer review, pt. IV - Reviewing Conclusion Section (Kevin Cohen): [slideslive](https://slideslive.com/38955752/), [slides](https://github.com/reviewingNLP/EACL2021T5/blob/main/EACL_2021_pt4_conclusionSection.pdf)

**Reviewing different types of papers**

* COLING 2018 review form for different paper types has great questions to ask yourself when reviewing engineering, resource, reproduction, survey and computational linguistics papers: [http://coling2018.org/paper-types/](http://coling2018.org/paper-types/) 
* Anna Rogers. Peer review in NLP: reject-if-not-SOTA [https://hackingsemantics.xyz/2020/reviewing-models/](https://hackingsemantics.xyz/2020/reviewing-models/)
* Anna Rogers. Peer review in NLP: resource papers [https://hackingsemantics.xyz/2020/reviewing-data/](https://hackingsemantics.xyz/2020/reviewing-data/) 

**Cognitive and social biases in peer review**

* Anna Rogers, Isabelle Augenstein. What can we do to improve peer review in NLP? [https://aclanthology.org/2020.findings-emnlp.112/](https://aclanthology.org/2020.findings-emnlp.112/) 
* EACL 2021 tutorial on peer review, pt. V: Reviewer Biases (Anna Rogers): [slideslive](https://slideslive.com/38955745), [slides](https://github.com/reviewingNLP/EACL2021T5/blob/main/EACL_2021_pt5_biases.pdf)
* EACL 2021 tutorial on peer review, pt. VI:  Anonymity in Peer Review (Anna Rogers): [slideslive](https://slideslive.com/38955746), [slides](https://github.com/reviewingNLP/EACL2021T5/blob/main/EACL_2021_pt6_anonymity.pdf)

**Ethics **

* NAACL 2021 Ethics FAQ: [https://2021.naacl.org/ethics/faq/](https://2021.naacl.org/ethics/faq/) 
* EACL 2021 tutorial on peer review, pt. VII - Ethics and Reviewing (Aurélie Névéol): [slideslive](https://slideslive.com/38955747), [slides](https://github.com/reviewingNLP/EACL2021T5/blob/main/EACL_2021_pt7_ethics.pdf)
* Just what do you think you're doing, Dave? A checklist for responsible data use in NLP. [https://arxiv.org/abs/2109.06598](https://arxiv.org/abs/2109.06598) 