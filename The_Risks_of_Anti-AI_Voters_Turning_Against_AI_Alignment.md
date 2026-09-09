<!-- Title:    The Risks of Anti-AI Voters Turning Against AI Alignment -->
<!-- Subtitle: How Unstable Anti-AI Alliances can Impede AI Alignment Political Agendas -->

*TL;DR: To prevent political impediment of AI alignment efforts, there needs to be more research into and awareness of how public anti-AI groups view AI alignment.*

# 1. Motivation and Claims

AI alignment efforts have largely treated the institutions building and governing AI as the main battleground: labs, governments, and other actors directly shaping its development. While I view that this current approach should still be the top priority, there is an overly neglected, but non-negligible, area that can become a practical obstacle to ensuring AI alignment policies and resources are put into place: gaining public support from anti-AI groups who have yet to develop an established stance on AI alignment.

Previously, AI alignment efforts were largely not affected by public opinions and actions, and there was no incentive to pay attention to them. However, I propose that as of now, AI alignment has begun to grow more dependent on the success of political victories that are affected by public opinions and actions, which can potentially help or hinder its agendas (an example of how this can occur is discussed in Section 3). More specifically, I propose that establishing alliances with anti-AI groups carries a deceptive risk: if these alliances are built on unstable foundations without genuinely strong relationships, then anti-AI groups can turn on AI alignment agendas, triggering severe political setbacks.

To provide context for these proposed claims, we will first observe a few examples of anti-AI groups, from the general public, that already demonstrate negative views on AI alignment. These are not fully representative of the public’s anti-AI sentiment; however, as from my initial analysis via web-scraping samples, they are notably prevalent, and are at risk of growing fast (Section 2 delves more into related analyses).

**Example 1: There are many anti-AI people who downplay AI capabilities.** This can potentially be a huge obstacle to getting the public to side with mitigating misalignment risks.

When browsing r/BetterOffline, a subreddit that opposes Big Tech and has 52,243 subscribers (found in Reddit’s about.json metadata) plus 198k weekly visitors, one can see that there are many anti-AI people who are against Bernie Sanders’s support of misalignment risk mitigation, despite his support of AI regulation. [In a post from August 2026](https://www.reddit.com/r/BetterOffline/comments/1vl6m21/sanders_calls_on_tech_giants_to_pause_development/), a comment with 65 upvotes conflates the general AI safety movement with “AI bros”, and downplays the dangers of capabilities:

> Even someone who marches with you in your criticism of the AI bubble, can still, through misconceptions about the capability of the tech, unwillingly serve amplify the bullshit the CEOs try to spread.
>
> Every single time someone with media reach goes out there talking about "out of control ai" or similar nonsense, *they amplify the exact message the ai bros WANT amplified;* That their product is scary and dangerous and powerful.
>
> They live on hype, and fear generates lots of it…. I know people don't like to hear this, but **Bernie Sanders is wrong about AI.** On pretty much all aspects of it.

This belief exists across platforms, such as in Bluesky. In response to the [2026 OpenAI agent security incidents](https://bsky.app/profile/nbcnews.com/post/3mukpydlvou2l), [a September 2026 post](https://bsky.app/profile/jametc.bsky.social/post/3mul77azf722q) (with 859 likes and 285 reposts) from a user with 55.3K followers stated:

> I cannot stress enough that all this bullshit about AI escaping containment and other stupid doomer fear mongering is ALL MARKETING. IT'S FUCKING MARKETINNGGGGGGGG

Similar sentiments are found on [other communities](https://www.reddit.com/r/behindthebastards/comments/1v3h7kv/help_me_understand_how_to_feel_about_the_ai/), including in r/antiai, a subreddit with 296,508 subscribers and 1.3 million weekly visitors, where [a user claims that AI are not growing more powerful:](https://www.reddit.com/r/antiai/comments/1w59vnx/sen_bernie_sanders_yes_we_must_hit_the_pause/)

> The actual reason we should want to pause AI isn't because it's too powerful, but because it isn't, and someone needs to stop our insane elites from throwing all of our resources into its bottomless pit in the hope that it makes a magic AGI genie come out.

**Example 2: Anti-AI groups have shown hostility towards working with AI alignment organizations.** [In a post from r/ArtistHate](https://www.reddit.com/r/ArtistHate/comments/1cnu2w2/announcement_we_are_banning_advertisements_of/), a subreddit with 33,727 subscribers and over 20K weekly visitors, a moderator declared:

> From now on we won't be allowing PauseAI to run or announce their campaigns on our page or anywhere we are are associated with, including our Discord server… It has come to our attention that leaders of the movement openly state their disregard for the inherit unfairness of how generative ML have came to be and even allow people to share "appreciation" for it…
>
> It is very clear that people at PauseAI do not care about the current and mundane problems and risks ML possesses like undercutting labor and side stepping paying for work; for the sake of an imagined and more fantastical ways it can hurt us like causing world ending scenarios.

Many comments agree with the post. For instance, a comment with 39 upvotes stated:

> Yeah. The most recent few promotions here really rubbed me the wrong way. I saw them talk about machines rising up against humans and not being able to control them when they go rogue etc. Thought I was reading a sci-fi film excerpt or something. I fully agree with cutting all ties with them.

Anti-technology protestors also [disrupted a keynote talk at a PauseAI event in Paris](https://www.reddit.com/r/artificial/comments/1irp9cm/antitechnology_protestors_disrupted_a_keynote/) due to believing that PauseAI leans too strongly towards pro-AI.

**Example 3:** [There are anti-AI people who are against Bernie Sanders’s goal](https://www.reddit.com/r/antiai/comments/1tu7an4/bernie_sanders_ai_is_a_public_resource_you_should/) to make AI a public resource, as they want to entirely ban AI, and show that they are unwilling to work with him; this conflict can affect the votes received by AI-alignment-favoring candidates whom he supports.

> No. You don’t steal from someone and offer them 50% of what you stole back. Copyright exists and therefor it should be opt in, not opt out. Remove any model made with copyright material and force people to be paid from what was already stolen. Otherwise, no deal. I’ll live my whole life purposefully avoiding AI. You downplay how far people are willing to go.

Section 2 provides a further analysis on 17,619 anti-AI comments found via data scraping.

While it seems that these anti-AI groups have the same goal as AI alignment, they are only partially aligned when it comes to the action of slowing down AI. In actuality, many of these anti-AI groups find that lacking. Rather, they only care about one goal: to stop AI completely. 

It can be beneficial, especially in the short-term, to gather anti-AI allies to slow down AI capabilities development. Additionally, it may seem that these opinions would have no effect on AI alignment agendas. But there is a hidden danger to this: if their reasons are not aligned with those from AI alignment, there can be conflicts of interest among this coalition in the long-term, leading to in-fighting that can impede political mechanisms crucial for implementing practical AI alignment agendas. Based on early evidence of these occurrences, I propose two main potential dangers that can impede AI alignment agendas:

**DANGER 1: Naturally Emergent Conflicts**

In the examples above, we showed that anti-AI people can turn on AI alignment when they perceive that it does not align with their own concerns, such as rejecting support of Sanders for stating what they claim are “false beliefs about AI capabilities” that “support pro-AI" agendas.

**DANGER 2: Astroturfed Conflicts**

Based on the assumption that public opinion has low impact on AI alignment, it may not appear worthwhile to focus on it. But when certain groups are neglected, there is the risk that bad actors can compromise these groups and turn them against AI alignment agendas. They can take advantage of this in-fighting and distrust, turning allies into enemies by taking advantage of misinformation.

This has been predicted before as an epistemic security pathway to existential risk: Allan Dafoe, an AI safety and governance researcher, [has noted that social media has weakened political communities’ ability to cooperate](https://www.allandafoe.com/opportunity) by increasing polarization and eroding a shared understanding of agreed-upon facts. He also stated that hostile foreign governments have attempted to take advantage of these weaknesses in democratic political debates.

An early warning sign showing how this can happen is a case with Sabine Hossenfelder, a physicist and science YouTuber with about 1.8 million subscribers. In a [September 2026 video](https://www.youtube.com/watch?v=lPdmYMHrWKg), she described being contacted by an AI safety organization that offered to pay her to warn viewers that AI is an existential threat, and declining their offer when the organization tried to dictate what the video would be about. She also mentioned that other people on Twitter were contacted by the Center for AI Safety, Control AI, and Future of Life Institute.

As her main complaints were about editorial control, she stated she was open to hearing about the dangers of AI and does not paint the movement as malicious, noting that both the “doom” and “boom” sides are quietly paying creators. However, AI accelerationists (e/acc) immediately [used her video to smear AI safety as a paid, deceptive operation](https://x.com/mark_k/status/2096271444241990090). This incident shows how a well-intentioned outreach attempt [handed AI alignment opponents material to define AI alignment as “inauthentic”](https://x.com/AISafetyMemes/status/2097178919044878609) for an audience that had no prior opinion of it.

There is also evidence supporting the claim that foreign actors have been manipulating US voters’ opinions on AI. For instance, in a June 2026 report, [OpenAI claimed that it found Chinese AI accounts](https://openai.com/index/prc-linked-influence-operations-ai-debates/) manipulating social media to fuel data center opposition in the US. In their report, they state: “The first cluster generated social media comments and images claiming that data center buildouts for AI were increasing electricity prices for average families”.

Lastly, Alex Bores, NY Assembly member and author of the RAISE Act (New York's frontier-AI safety law), ran for Congress in 2026. However, he was attacked by ads from Leading the Future, a pro-AI PAC, [tying him to Palantir and its ICE contract due to his previous work at Palantir](https://ny1.com/nyc/all-boroughs/politics/2026/05/20/ai-money-floods-manhattan-congressional-race). This shows that opponents of AI alignment groups are willing to exploit misinformation or half-truths against political candidates backed by AI safety organizations. Notably, their angle of attack aimed to turn him against anti-AI groups that oppose mass surveillance. [Additionally, Micah Lasher, who won the Democratic primary over Bores in a tight race, also took advantage of this slander associating Bores with Big Tech, stating in his victory speech](https://www.politico.com/news/2026/06/23/micah-lasher-wins-new-york-congress-primary-00972335): “I have some news for the two big AI companies… I won’t be taking my cues from either of you when it comes to protecting our kids, our jobs and our families.”

**Main Claims:** An alliance between AI alignment and the general public anti-AI groups may seem beneficial as a “means to an end”. But there is a latent threat: if the general public’s reasons are not aligned with those of AI alignment, there can be conflicts of interest among this coalition in the long-term, leading to in-fighting. Bad actors or naturally emergent opposition can take advantage of this vacuum, turning anti-AI supporters against AI alignment, pushing their votes to siphon its funding and resources, or writing hit pieces against major players. The loudest voices that fill this vacuum would dictate the public’s opinion, potentially stalling or even banning safety research.

As such, I advance that it is not enough for groups affiliated with AI alignment to form a weak, unstable alliance with the anti-AI public by vaguely stating that AI alignment aims to “also slow down or stop AI”, hoping that no further questions be asked. Crucially, AI alignment groups must check that these anti-AI groups both truly understand and side with AI alignment goals, harboring with a positive view towards alignment-affiliated groups. This ensures greater stability that they are on the side of AI alignment, as they form actual opinions about it; without doing so, if they initially only have a vague understanding of what AI alignment groups are, but later discover information or misinformation that paints AI alignment as opposing their main concerns, then they can turn against it, greatly turning away crucial voters, and surprising previous voter forecasting models that did not take this factor into account. 

Just how prevalent are these antagonizing beliefs, and how risky is this threat? I currently believe that we do not have enough information to draw a sound conclusion. Thus, I argue that further research must be done in this area. Moreover, I do not propose reckless engagement, as that can worsen situations if not done properly (as seen in the examples discussed above); rather, I suggest to first scout the landscape by learning more about the general public’s anti-AI groups. This can greatly improve understanding how to interact with them.

Relative to other AI alignment political and social focus areas, this focus area is a minor threat; however, that is what makes it deceptively dangerous. When minor threats are overlooked and not fortified, they can be taken advantage of and amplified, either intentional or unintentionally. Given that this is a minor, yet notable, potential risk, I estimate that only ~0.1 to 0.3% of resources need to be dedicated to develop political strategies in this area. This amount of resources would be proportionate to this issue’s threat level. Sections 3.5 and 5 discuss this estimate in more detail.

**Related Works (Added after writing the rest of this)**

After I finished writing this piece, I checked for similar works, and realized many of these same issues and solutions were already proposed by others this year, with the other authors and I independently reaching similar conclusions. I will list out direct quotes that show the overlaps between this piece and theirs:

- [The AI safety movement needs normies](https://www.transformernews.ai/p/the-ai-safety-movement-needs-normies) : In April 2026, Celia Ford wrote:
    - “Mainstream anxieties about job loss, cyberattacks, and mass surveillance — which all [rank](https://report2025.seismic.org/media/documents/On_the_Razors_Edge_Seismic_Report_2025.pdf) relatively high on the public’s list of concerns about what AI might do — tie into x-risk-pilled concerns such as [gradual disempowerment](https://gradual-disempowerment.ai/) and [loss of control](https://www.rand.org/randeurope/research/projects/2025/examining-risks-and-response-for-ai-loss-of-control-incidents-cm.html).”
    - “The AI safety community has historically worried that addressing normie concerns would come at the expense of x-risk, and possibly knock it off potential legislation altogether. But these pressing, present socioeconomic issues may be the gateway that gets x-risk on the table.”
    - “But in choosing to operate largely behind the scenes, the AI safety community created a vacuum that’s now being filled by industry lobbyists, populist politicians, and radicalized individuals.”
    - “To build a real movement,” Sherman said, AI safety advocates “need to run full speed ahead towards people who are concerned about their kids, towards people who are concerned about data centers … the whole thing, all of it.”
    - “The best thing that the AI safety movement could do would be to build an army of surrogates who are regular people, going into their own communities and talking about this stuff,” Sherman said — “not strangers from a foreign land speaking a different language.”
- [Strategic considerations for pausing the AI race](https://connorsscratchpad.substack.com/p/strategic-considerations-for-pausing) : In April 2026, Connor Williams wrote:
    - “We need to fight this battle from the outside. Many attempts to achieve AI safety goals have treated it as a family affair to be handled within the AI community, without involving politics or outside pressure.”
    - “To make the best possible use of this limited time, we need to work with, rather than alienate, existing forces that share some or all of our goals - groups that ought to be our natural allies.”
    - “A broad front doesn’t mean we should try to work with absolutely anyone”
- [The left is missing out on AI](https://www.transformernews.ai/p/the-left-is-missing-out-on-ai-sanders-doctorow-bender-bores) : In February 2026, Dan Kagan-Kans wrote:
    - “Social media reinforces this consensus, so that anyone who turns from the *NYRB* to Reddit or Bluesky, or the remaining left corners of X, will see the same thing. “Ppl don’t know how ChatGPT works,” one recent post said. “It doesn’t ‘know’ things. It autocompletes sentences. It makes things up.” The post has more than 70,000 likes.”
- [Existential AI safety needs an effective social movement. PauseAI is building it](https://www.lesswrong.com/posts/aoqhszdEWqcFWbnda/existential-ai-safety-needs-an-effective-social-movement) : In June 2026, Matilda da Rui and Maxime Fournes wrote:
    - “The existential AI safety community needs to take building a civic and social movement seriously as a core intervention. We believe this is a high-value, badly neglected approach to reducing catastrophic/x-risks from AI because it may significantly enhance the likelihood of governance efforts succeeding at keeping humanity safe.”
    - “On remarkably thin resources ($600k since we started in 2023), we have built an organised presence in more than 15 countries and a community of thousands of supporters and volunteers.”
- [One Year of PauseAI UK](https://www.lesswrong.com/posts/i2rCbxuskrarrprwA/one-year-of-pauseai-uk) : In June 2026, PauseAI reported:
    - “We are cognisant that building an AI movement in a context where many people have an incomplete understanding of the most severe risks requires caution and continual shaping of our message. Having our primary policy demand built into our name is a good safeguard against harmful distortions of our goals.”

# 2. Background on Anti-AI Groups

**AI Opposition Groups**

[Ipsos, a major global market research company, reported](https://www.ipsos.com/sites/default/files/ct/news/documents/2026-06/Ipsos-AI-Monitor-2026.pdf) that when asked if “Products and services using artificial intelligence have more benefits than drawbacks”, only 38% US respondents responded that they agree (with 38% for UK, 37% for German, and 34% for Canadian respondents.) At first, this may seem beneficial for AI alignment. However, the reasons for having these negative stances towards AI may not be due to alignment concerns, but due to other reasons such as labor or human wellness concerns.

[Research from June 2026](https://theaipi.org/poll-ai-safety-majority/) by Artificial Intelligence Policy Institute (AIPI) polled 1007 likely US voters about slowing down AI. Given two choices (along with “Not sure”), the study’s findings included the following:

- 66% supported mandatory AI standards vs 21% supported an outright AI ban
- 63% supported an outright AI ban vs 17% supported no AI regulation
- 47% supported data center guardrails vs 38% supported an outright local data center ban

However, I did not see if this study measured how familiar the voters were with misalignment risks, nor if it checked their reasons for choosing mandatory standards over an outright ban. As such, the reasons for the voters’ choices may have also largely been due to non-alignment issues such as labor concerns. On another note, while this data shows that many Americans support standards over an outright ban, the percentage of those who support an outright ban is still notable, hovering ~20%; this number may increase fast depending on future events, which does not bode well for those who support AI for scientific/medical applications.

To informally take a glimpse into how prevalent the general public (outside of AI alignment) is concerned with existential risk (when they are not directly asked about it), I scraped 17,619 anti-AI posts/comments from social media sites (YouTube, Reddit, X, Bluesky, TikTok), using gpt-4o as an LLM judge to check if the item is anti-AI and what type of stance it embodied, found that only 0.7% of these samples were concerned with misalignment risks.

| Type of Stance | # of Items | % of 17,619 items (rounded) | # of engagement | % of engagement (rounded) |
| --- | --- | --- | --- | --- |
| Creative Media | 8,659 | 49.1% | 1,825,402 | 50.1% |
| Human Wellness | 5,189 | 29.5% | 1,066,758 | 29.3% |
| Anti-Surveillance/Tech | 4,493 | 25.5% | 802,211 | 22.0% |
| Pro-Labor | 3,016 | 17.1% | 490,476 | 13.5% |
| Pro-Environment | 2,158 | 12.2% | 361,069 | 9.9% |
| Fairness / Bias Ethics | 272 | 1.5% | 21,764 | 0.6% |
| **Alignment risks** | **117** | **0.7%** | **6,739** | **0.2%** |

27.6% of items belong to multiple groups, so the item counts sum to 23,904, and the percentages exceed 100. Each row's "% of engagement" is its share of total likes or upvotes.

Note that this is not rigorous research, given issues such as its focus on a narrow audience that is frequently online on these social media sites (which does not represent many groups in the US); thus, in Section 5.1, I propose that more rigorous research is needed. [In a planned follow-up to this introductory post, there will be an appendix with more detailed analyses I have done that are not shown here yet (e.g., belief prevalence analysis for beliefs like “opposes Sanders’s claim of AI capabilities”)].

Therefore, we can assume that the anti-AI public currently has no strong stance or awareness about misalignment risks. To provide a background of their main concerns, we will summarize a few prominent anti-AI stances:

(Note that when I use the word “group” in this writing, I am using the term like “stance” rather than a formal organization. A person may belong to several of these groups.)

Examples of AI alignment groups:

1. Slow Down: Aim for AI regulation/slowdown of building frontier models, instead of stopping completely. Supported by some frontier labs with regulatory policies on scaling.
2. Shut Down: Aim to stop AI completely due to existential risks

Examples of general public anti-AI groups:

1. Pro-Labor: concerned with issues such as job replacement and worker rights. Currently lacking concrete answers on what will happen with jobs when AI grows more powerful. Connected to future capabilities risks via employment post-AGI concerns (depending on their views of AGI).
2. Pro-Creator (Creators/artists in creative media such as Hollywood, Gaming, TikTok, Social Media Influencers, etc.): concerned with issues such as fair use / plagiarism, slop reduction, and discerning if an output was produced by a human or AI. They have strong ties with Pro-Labor, such as with their focus on SAG-AFTRA contracts. May be the most prevalent group among teenagers / young adults due to their strong connections with influencers and media personalities via social media.
3. Pro-Environment: concerned with issues like data center grid strain and pollution.
4. Anti-Surveillance + Anti Big-Tech: concerned with issues such as spying on citizens and consumers, transparency, and data collection without consent; partially overlaps with anti-big government groups.
5. Pro-Human Wellness: concerned with topics such as deepfakes (like impersonations, or faking footage to muddy videos that can be used as criminal evidence), child-safety, effects on human intelligence and education, AI psychosis (like instilling delusions), using hallucinated information, or dangerous AI relationships.
6. Pro-Fairness/Bias Ethics: concerned with issues such as discrimination and bias in AI decisions. While these are important issues, my personal observations find that the public is less concerned with them; this topic is more popular in academic and industry circles.
7. Those who “just hate AI” because others do: tend to form their opinions around what are “currently trendy social issues” rather than “what they actually feel is right”. If one persuades the people they listen to, who usually fall into the above camps, and cause large audience opinion changes, then these people usually change too.

Note that we are not discussing pro-AI/AI-accel groups, as they are not the focus of this writing. While they can also impede AI alignment efforts, the focus of this writing is about the deceptive dangers of unstable alliances with anti-AI groups.

Most people, from anecdotal observation online and offline, appear ambivalent or indifferent to AI; we will also not discuss this group. The aim here is to discuss AI opposition groups with people who oppose mainstream AI issues, but who are mostly undecided on AI alignment.

Currently, different groups affiliated with AI alignment have varying relationships with these other groups. For instance, in my view, I believe most alignment-affiliated groups generally have stronger alliances and goals with those interested in Human Wellness than with Pro-Creators/Artists. AI alignment groups also have strong agreements with Pro-Labor groups, as they both believe the power of current capabilities, but may disagree on future capabilities. Overall, more rigorous research is needed to track which groups are likely to turn on AI alignment.

Relative to an organization’s AI alignment agenda, I propose that it is crucial that they are aware of which groups they can ally with, which groups they cannot ally with, and which groups they can have a partial allyship with. More specifically, identifying these three categories and putting a much greater focus on securing a partial alliance with the third category is highly important to prevent a strategic move by opposing actors who seek to secure a partnership with them first.

# 3. How Public Opinions Can Impede AI Alignment Agendas

## 3.1. Nuclear energy- a historical precedent

[In the 1970s, scientists and engineers who raised concerns about nuclear reactor safety](https://time.com/archive/6854316/nation-hell-no-we-wont-glow/) were broadly aligned with environmentalists, consumer advocates, and anti-nuclear activists pushing for greater caution over serious, legitimate dangers including accidents, radiation exposure, and waste. These public movements had ties with scientists belonging to organizations such as the Union of Concerned Scientists.

However, these scientific concerns were overly generalized by many in the public into becoming beliefs that all of nuclear technology was catastrophically dangerous, blurring the distinctions between the benefits of civilian nuclear power with the harms of nuclear weapons. The focus became less on regulating particular designs and practices carrying specific risks, and more on banning nuclear technology all together. Overall, [studies have found substantial gaps between expert and lay perceptions of radiation risk.](https://journals.sagepub.com/doi/10.1177/0096340212444870)

[The Three Mile Island accident in 1979 accelerated this shift.](https://www.nrc.gov/reading-rm/doc-collections/fact-sheets/3mile-isle) The reactor suffered a genuine partial meltdown caused by equipment failures, design problems, and operator errors, but the NRC reports that its small radioactive releases produced no detectable health effects in workers or the surrounding public. Nevertheless, contemporary survey research found that the accident significantly decreased public acceptance of nuclear power and increased opposition to constructing new plants. [Shoreham illustrates how this political environment could affect otherwise completed infrastructure](https://www.jstor.org/stable/jj.14170582): the Long Island plant was completed in the 1980s at a reported cost of about $5.6 billion, but never entered commercial service amid intense public opposition.

The public perceptions of nuclear power persisted even decades later: [after the 2011 nuclear disaster in Fukushima, public attitudes shifted sharply against nuclear power in Germany](https://journals.sagepub.com/doi/10.1177/0963662515589276), accelerating a phase-out of nuclear energy. An NBER analysis estimates that the resulting lost nuclear generation was [replaced primarily by coal generation and electricity imports, producing a social cost of approximately $12 billion per year](https://www.nber.org/papers/w26598), more than 70% of which came from increased mortality risk associated with fossil-fuel air pollution.

These public concerns about nuclear power were rooted in real dangers supported by scientists. However, public distrust that was built on misunderstandings of a complicated technology led to outcomes that some claim have worsened the environment. Likewise, it is possible that public misunderstandings of AI and AI alignment may usher in policies that obstruct the benefits of certain AI technologies that have no impact on labor or theft issues, and may also obstruct the evaluations, compute, model access, and safety research needed to make advanced systems safer.

## 3.2. Example of an AI alignment plan that can face impediment

As an illustrative example, we lay out one such AI alignment plan, and describe how it can be politically impeded. This plan is not reflective of my personal views, nor does it model after a specific, existing organization. Consider a hypothetical organization with the following goals to research AI safety to further pull civilization towards AI alignment:

1. Support regulating frontier compute scaling with mandatory standards: This is due to the organization’s belief that AI has great use for science and improving human lives; thus, they aim to not completely ban it, but to regulate it
2. Spend funding on researching dangerous capabilities
3. Increase auditing transparency with external evaluators and government cooperation
4. Democratize AI for public ownership

Now consider a hypothetical, near-future election race between candidate A, who is backed by the hypothetical AI alignment organization (as they support capabilities testing and slowing down AI), and candidate B, who completely rejects AI existential risk and vows to completely ban AI with an unrealistic but highly appealing plan.

The public, having no strong understanding of AI alignment, is unfamiliar with why it wants to “use AI” in research. Candidate B’s campaign takes advantage of this: they run a smear operation that “exposes” how candidate A’s organization uses generative AI to run its evaluations and its automated research, while being hypocrites in wanting to oppose it. They paint the candidate who is concerned about existential risk as "crazy", and misconstrue their relationships with working with the government as allowing the government to use AI for harmful applications. Lastly, they misconstrue candidate A’s call for public ownership as “wanting to force everyone to use and own AI”. These smear campaigns may seem fantastical, but the examples I showed in the introduction show that these sentiments and manipulation of them already exist (meaning that writing about this is likely not giving any new ideas to anyone; this writing will just draw awareness to these deceptive acts).

Therefore, I view that it is paramount that the public obtain an immunity towards this misinformation. Whether they support candidate A or candidate B is up to their own personal free will and belief; however, their decisions should not be made from a place of inaccurate information and half-truths. By instilling into the public a more accurate understanding of both AI and AI alignment, justifying why it “uses gen AI in research”, and destigmatizing notions such as how “all of AI is bad” or how “medical AI does not use gen AI”, the public can be aware of the inaccuracies of these smear campaigns, while justifying their goals of opposing AI based on accurate information about how it impacts labor or increases existential risks.

## 3.3. Examples of political mechanisms affected by Anti-AI opinions

In the United States, public opinion can change the political costs facing candidates, legislators, executives, and agencies at different points in the policymaking process. Consider a few examples of how this can occur:

1. **Candidate Policies and Elections:** Knowing that voters can replace politicians whose positions they dislike, politicians [often change their positions before an election](https://www.cambridge.org/core/journals/american-political-science-review/article/abs/dynamic-representation/0BF0C091BFF116F645EE16C9C5D37995) because they anticipate losing support. If voters come to see frontier-model evaluations as helping AI companies rather than restraining them, candidates may gain support by opposing such requirements given in proposals such as the [2026 FRONTIER Act](https://www.govinfo.gov/content/pkg/BILLS-119hr9925ih/pdf/BILLS-119hr9925ih.pdf), which includes independent evaluations, risk-management requirements, and incident reporting for frontier models.
2. **Constituent pressure between elections:** [Legislators do not only respond to voters on Election Day](https://www.congressfoundation.org/s/cwc-perceptions-of-citizen-advocacy.pdf): calls, emails, town halls, district meetings, and organized constituent campaigns tell congressional offices which issues are politically important. Members can respond by co-sponsoring a bill, refusing to support it, demanding amendments, pressuring committee leadership, or simply deciding that the issue is not worth spending political capital on. Congressional staff are specifically responsible for tracking and communicating constituent concerns. Therefore, a member of a committee considering frontier-AI legislation could support AI alignment policies in principle, but push to weaken them after receiving sustained opposition from constituents, such as from those who believe AI evaluation testing legitimizes AI development.
3. **Primaries candidate selection:** Public opinion can also determine during primaries which candidates ever reach a general election. Primary voters are often especially politically engaged, so a relatively small but motivated group can make a position risky within a party. Candidates may adopt that position to avoid a primary challenge even when the broader electorate is less concerned with the issue. If strongly anti-AI primary voters begin treating cooperation with AI-safety organizations as evidence that a candidate is "pro-AI," candidates may distance themselves from alignment organizations, or reject policies that allow continued AI development under safety requirements.
4. **Lobbying and organized interest groups:** Public opinion becomes more powerful when people organize around it. Organizations can hire lobbyists, develop policy proposals, meet legislators and executive officials, testify at hearings, coordinate constituent campaigns, and maintain pressure on an issue for years. Thus, an organized anti-AI group could lobby against allowing frontier developers to share information about dangerous capabilities because it views cooperation among AI companies as collusion. This could conflict with proposals such as the [Collaboration on Adversarial Threats and Security Risks Act](https://www.govinfo.gov/app/details/BILLS-119s5105is), which is intended to make certain forms of safety coordination easier.
5. **Campaign spending and political advertising:** Groups do not need to persuade legislators directly. [They can instead make a politician's position electorally costly,](https://www.fec.gov/help-candidates-and-committees/making-independent-expenditures/) as federal law allows independent groups to spend money advocating for or against candidates, provided that spending is not coordinated with the campaign. A politician who supports frontier-AI safety rules could be attacked in advertisements as being aligned with Big Tech, surveillance, automation, or job displacement.
6. **Ballot initiatives and referenda:** In many states, [voters can make policy without going through the normal legislative process](https://www.ncsl.org/elections-and-campaigns/initiative-and-referendum-processes). Twenty-four states allow citizens to place proposed laws or constitutional amendments on the ballot through an initiative process. In the future, consider a ballot initiative banning state support for "advanced AI development" that could be written broadly enough to also restrict university alignment research, government safety evaluations, or publicly funded compute used to study dangerous models.
7. **Protests and political salience:** Protests cannot directly pass legislation, but they can make an issue politically difficult to ignore. Large demonstrations attract media coverage, increase public attention, recruit activists, and [signal to politicians that a constituency cares intensely about an issue](https://doi.org/10.1017/S000305542000009X). Research on U.S. protest movements has found effects on media attention, political behavior, and public opinion. Anti-AI protests could increase support for mandatory frontier-model testing if protesters demand stronger safety controls. But if the movement instead treats any testing or research on advanced AI as participation in AI development, the same political pressure could be directed against alignment researchers and evaluators.
8. **Funding and appropriations:** Creating a government program and funding it are separate political decisions. Congress can authorize an office or responsibility [while later providing too little money for it to function effectively](https://www.congress.gov/crs-product/RS20371). It can also place conditions on how appropriated money is used. For example, a federal AI-safety office could have legal authority to evaluate frontier models but lack enough money for technical staff, secure compute, cybersecurity, or external evaluators. If public opinion treats this spending simply as "government funding AI," legislators could weaken safety capacity without repealing the underlying law.

These mechanisms often reinforce one another: A protest can make an issue more salient, which increases constituent pressure and campaign activity. That pressure can change candidate behavior, legislative votes, executive decisions, funding, and agency implementation. Therefore, public opposition does not need to control the entire political system to impede an AI-alignment agenda; a shift in opinion does not need to produce a national majority to block an agenda. It only needs enough influence to make that agenda politically costly at one important decision point.

**Other vectors of influence against AI alignment**

**1. Direct and hostile attacks:** Negative views can cascade into serious direct attacks, from hit pieces to terrorism. For instance, Kate Willett, [a comedian with over 60k followers who has appeared on The Late Show with Stephen Colbert, tweeted out a negative view of Bores, tying him to ICE](https://x.com/katewillett/status/2068927015789441205), possibly showing the effectiveness of pro-AI smear campaigns in turning anti-AI supporters against candidates backed by alignment organizations.

> Bores is a fraud like no other. His AI legislation is so weak bc it’s sponsored by the other major AI company… Bores was high level at Palantir during several contracts with ICE, he made his money and then tried to rebrand.

**2. Anti-AI creators shape cultures:** Artists, TikTok, influencers, and others in media are highly influential on topics that the public is interested in (ties to current political topics, streaming/gaming, etc.). They shape the next generation’s views in the long-term with long-standing cultural influences, and people who enjoy their works are more prone to being persuaded by their creators’ personal views. Thus, it is important to ensure that they do not influence large groups of the public against good causes via misinformation, as these beliefs can develop into larger issues such as erroneous conspiracy theories.

**3. Anti-AI sentiment against the AI itself can impede AI welfare:** While the term “clankers” is largely used in jokes, many people actually hate AI for being AI right now (not just those who control AI); this can translate into stopping AI from being seen as “deserving of rights” in the future when there is a time we should seriously consider its welfare. Additionally, the public creates the training data that the next AI learns from. The AI can develop a negative view of humans if many humans are seen as “hating AI from misinformation”. However, this item is highly speculative and is based on many assumptions that currently do not hold.

## 3.4. Fast timelines

Public opinion moves very fast on a new topic, but once entrenched, it can be hard to reverse. In December 2022, over the course of just a few days, many people became anti-AI during Stable Diffusion 2.1’s release. [Google search interest in “AI art”](https://trends.google.com/trends/explore?date=2022-06-01%202023-02-28&q=AI%20art) was flat from August through November, then rapidly rose in the week of December 4 to 10. One major event that caused this was when [Lensa’s “Magic Avatars”](https://www.cnbc.com/2022/12/07/lensa-app-turns-selfies-into-avatars-with-artificial-intelligence.html), built on Stable Diffusion 1.5, hit #1 on the Apple App Store and put the product into millions of social media feeds.

This caused a massive backlash against AI art on sites such as Twitter, with information spreading that it was trained on artists’ works without their permission; people were also shocked by its capabilities. All of this anger sparked [a mass protest](https://arstechnica.com/information-technology/2022/12/artstation-artists-stage-mass-protest-against-ai-generated-artwork/) in just a few days, and this negative sentiment, along with the slogans that grew out of it, has strongly persisted even after almost four years.

Previously, some artists did not show highly negative stances towards AI image generation. In fact, some had playful attitudes towards it, such as [an artist who combined her artwork with DALL-E](https://blog.loish.net/post/689864565777973248/i-typed-loish-art-into-the-dall-e-mini-2-ai):

> I typed ‘loish art’ into the [**DALL-E mini 2 AI tool**](https://huggingface.co/spaces/dalle-mini/dalle-mini), picked my favorite result, and painted over it! Mainly because I couldn’t think of anything to draw, but also because I want to make a gesture of acceptance towards the AI world so that they will consider sparing my life when the inevitable robot uprising arrives.

However, [the same artist rapidly turned against AI generation on December 15th](https://www.instagram.com/p/CmMds1dM__Z/), just a few days after the huge backlash against Stable Diffusion.

Thus, while only a small subset of the population may currently harbor beliefs such as “Alignment is a fake tech bro scam”, or “These are real incidents that have impacts on our every day lives, and must be taken seriously”, these beliefs may rapidly spread to a large portion of the population in a small amount of time. This may be done via top influencers who express their actual views, or via bad actors who manipulate discourse.

## 3.5. Expected risk estimates

In this section, we walk through a highly simplified risk estimate analyzing the trade-offs of working on this problem. Consider two options to take when faced with this potential risk: 1) ignore the anti-AI public, or 2) spend about 0.3% of resources (money, attention, and time) scouting the landscape and stabilizing relations with the anti-AI public.

Now also consider possible two states of the world over roughly the next three years: A) a serious backlash event occurs, meaning anti-AI opinion turns against an alignment input at crucial decision point(s) (such as those described in the examples in Section 3.3), or B) it does not. Then define the following variables:

- ***p***: the probability that a “serious backlash event” occurs in the next three years

- ***L***: the damage done if a “serious backlash event” occurs (without mitigation preparation).

    - We measure loss as a percentage of the field's total resources over the same period, roughly the three years to the end of 2028. "Resources" means money plus attention and time, priced as money. Assume the total resources within this time period is $1 billion (chosen as an arbitrary number that makes calculations cleaner; this can be updated later with [better estimates of total spending](https://x.com/PChuzeville/status/2075595916984119317)).

    - *L* = 10% means the fracture wastes as much as a tenth of everything the field would have spent had the bad event not occurred, such as by delaying a compute site, cutting a budget line, or losing a candidate.

    - In other words, if a “backlash event” happens and nobody (or not enough people) in AI alignment prepared, how much does it set the field back?

- ***r***: if the field did prepare, what share of the damage does the preparation undo?

    - Assume that preparation cannot stop all of the damage; only a partial damage. r defines how much: r = 0.2 means it saves a fifth of the damage, while r = 0 means no preparation occurred, so no damage was mitigated.

- ***c***: the premium cost paid (against the total budget) to insure against this damage. We set this as 0.3% of the total budget of $1 billion, which is $3 million.

We use these to estimate a decision matrix for payoffs given each (decision, outcome). Every cell is a loss measured as a percentage of the field's total resources over the same period, roughly the three years to the end of 2028:

|  | If a backlash event happens (probability *p*) | No backlash event (1 − *p*) |
| --- | --- | --- |
| Do nothing | Lose the full *L* = −*L* | Lose nothing = 0 |
| Spend 0.3% | Lose *L*, get *r* × *L* of it back, and pay the 0.3% = −(*L* − *r* × *L*) − 0.003 | Pay 0.3% = −0.003 |

Spending the 0.3% premium costs 0.3% whether or not a backlash event occurs, and it pays back *r* × *L* only if one does. So spending is worth it whenever *p* × *r* × *L* > 0.003 ; in other words, the chance of a bad event, times the share of the damage preparation saves, times the size of the damage, must exceed the price of the insurance.

Now consider a worked example. First, assume *p* is above 0.5, noting that small versions of a backlash event have already happened (but were not impactful): such as r/ArtistHate (assuming they represent well how many anti-AI creators view alignment) expelling PauseAI, and some anti-AI public people rejecting Sanders’s reasons for pausing AI while still wanting a pause. One can track how these backlash events evolve and what their losses are to see if their losses are increasing, and derive better expected estimates for the chances of an event occurring that incurs a huge loss.

Let *p* = 0.6 be such that one serious backlash event occurs. For instance, assume a policy (which was expected to very likely pass) that provided $100 million in funding is struck down (so *L* = 10%). But assume preparation saves a fifth of it (*r* = 0.2).

Observe that 0.6 × 0.1 × 0.2 = 0.012 > 0.003, showing that with these estimates, it is better to pay the premium than not. 

We can also see this in more detail using the decision matrix. With these worked numbers (*p* = 0.6, *L* = 0.1, *r* = 0.2) and calculations (*L* − (*r* × *L*) = 0.1 − (0.1 × 0.2) = 0.08), the decision matrix reads:

|  | Backlash (*p* = 0.6) | No backlash (1 − *p* = 0.4) | Expected loss |
| --- | --- | --- | --- |
| Do nothing | **−10%** = $100M | 0% | 0.6 × (−10%) + 0.4 × (0%) = **−6.0%** = $60M |
| Spend 0.3% | −8% − 0.3% = −8.3% = $83M | −0.3% = $3M | 0.6 × (−8.3%) + 0.4 × (−0.3%) = −4.98% − 0.12% = **−5.1% = $51M** |

Thus, spending the premium to prepare would save $9 million in loss.

When would “not spending the premium for preparation” be the better choice? In other words, when does *p* × *r* × *L* ≤ 0.003 occur? Let’s look at the break-even values by shrinking one input while keeping the other two fixed, until there is no payoff (and shrinking it further would make “do nothing” decision be the better choice):

| Shrink one input | Break-Even: Hits $3M when | “Do nothing” wins only if |
| --- | --- | --- |
| Chance of backlash *p* | *p* = 0.15 | a backlash is less than a one-in-seven chance |
| Share saved *r* | *r* = 0.05 | preparation recovers under 5% of the damage |
| Damage *L* | *L* = $25M | the damage is under $25 million |

Therefore, to justify spending this premium, we assume there is greater than 1 in 7 chance of a serious backlash, that preparation will recover more than 5% of the damage, and/or that the damage would be greater than $25 million.

Note that all of these are simplistic, rough estimates that are not based on empirical data; thus, I call for further research in this area, as described in Section 5.

# 4. Barriers Towards Adopting AI Alignment for the Anti-AI Public

## 4.1. Barrier A- Misinformation fueling beliefs

There are many anti-AI beliefs that are based on partial truths or misunderstandings. One of the beliefs that I predict can have a notable effect on the public siding with AI alignment efforts is that “AI is not capable.” Let’s look at a few examples of these beliefs that downplay the capability of AI:

**1. Beliefs that it’s “a big tech, tech bro scam like NFTs” with no real use case, and is entirely propped up by fake investments**

While AI scams and fake investments are real, this belief claims that all AI has no real use cases, or is highly incapable. Using an LLM judge on the 17,619 anti-AI social media samples mentioned in Section 2, this belief appears in ~11.6% of samples.

Examples:

In [a video with over 1.5 million views](https://www.youtube.com/watch?v=0A2SP-QBByI&lc=UgzpGigLXHeK5HUd2hx4AaABAg), a top comment with over 13k likes says:

> Hard not to be an ai skeptic when everyone involved in it is either a complete fraud or a cartoon supervillain

In [a video with over 4.5 million views](https://www.youtube.com/watch?v=l0K4XPu3Qhg&lc=Ugzm-XT_5WTz4T3ZPtx4AaABAg), a top comment with over 17k likes says:

> It's a fucking Ponzi scheme. Our government is funding a Ponzi scheme for billionaires.

**2. Beliefs that the AI’s outputs are all “just stealing by copying”, or a “mash-up machine” (like a collage that just takes existing things and re-arranges them)**

AI is capable of memorization, and thus there is legitimate concern over fair use. However, plagiarism is different from “being only able to copy”, and these two concepts may be conflated to make people believe the AI “is not generalizing” and “cannot reason or solve problems by deriving new solutions”. This belief appears in ~14.4% of samples.

Examples:

In [a video from August 2026 called “Hank Green Admitted to Using AI. Then It Got Weird”](https://www.youtube.com/watch?v=mMXqoAtBAnw&lc=UgyWUloeILI09gfBPIh4AaABAg), which has over 300k views from a channel with over 170k subscribers, a highlighted comment with over 635 likes states:

> The thing about AI is it’s not research at all it’s just regurgitating stuff other people have done research elsewhere

A reply to it, with over 45 likes states that “it lacks the capicity to analyze and synthesize text.”

In [this reddit thread](https://www.reddit.com/r/antiai/comments/1vacyg0/the_bubble_already_burst_spread_the_fucking_word/), a comment with 391 likes states that, “AI isn’t even the “AI” we were promised. It’s literally a powerful mash up machine that isn’t doing ANYTHING intelligent.”

**3. Beliefs that it’s “just auto-complete” / “a stochastic parrot”**

These are similar to the belief that it’s just a “mash-up machine”, but instead of specifically saying that it just copies, it uses frequently propagates phrases such as how it’s “just a stochastic parrot” to make specific claims about its intelligence, and that it cannot perform well on reasoning tasks. This belief appears in ~6.5% of samples.

Examples:

A comment from [this Bluesky thread](https://bsky.app/profile/hankgreen.bsky.social/post/3mfk24d3tlk2y) states:

> At its base it really is fancy auto correct

A comment from [this r/antiai thread](https://www.reddit.com/r/antiai/comments/1u912tf/regulating_the_trivial_while_ignoring_the/) states:

> Here we go with the AGI schizophrenic nonsense again. AI isn't intelligent to begin with. Current "AI" are Language Models and Chatbots, like we've had them for 15 years. Their main purpose is to be a vehicle for financial speculation, not actually a transformative technology.

This table summarizes the prevalence of these beliefs (assessed by an LLM judge):

| Belief | # of Items | % of 17,619 items (rounded) |
| --- | --- | --- |
| Scam / bubble / NFT-style grift | 2,035 | 11.6% |
| Theft by copying | 2,539 | 14.4% |
| Parrot / autocomplete / not reasoning | 1,143 | 6.5% |


Other anti-AI beliefs based on misinformation include:

**1. Beliefs misunderstanding what the AI bubble is, when it pops, and what happens when it pops**

While the AI bubble is most likely real, it is a financial bubble that does not mean that all of AI will go away when it pops, nor does it exist because AI “doesn’t work” (see [this explainer of the AI bubble](https://cardcatalogforlife.substack.com/p/the-ai-bubble-explained)).

Example: [a r/antiai thread declaring that the bubble already burst](https://www.reddit.com/r/antiai/comments/1vacyg0/the_bubble_already_burst_spread_the_fucking_word/).

**2. Beliefs about data center dangers**

Beliefs about data center water usage may be based on misinformation, such as those “claiming that each ChatGPT prompt used a whole bottle of water.” [A counterargument against them](https://x.com/AndyMasley/status/2058862525056156061) claims that they are “based entirely on napkin math that ignored lots of simple things we knew about the hardware and software running GPT-4, and if you just account for those the cost drops by 50 to 200 times.” (See also [Tom’s Hardware’s report on OpenAI’s water-use figures](https://www.tomshardware.com/tech-industry/data-centers/openai-ceo-sam-altman-says-38-000-chatgpt-queries-use-as-much-water-as-the-production-of-one-almond-says-data-centers-use-no-more-water-than-an-office-building).)

Example: [a TikTok video from @dylan.page](https://www.tiktok.com/@dylan.page/video/7459886952981007649).

**3. Anthropic’s training on old books**

This is a nuanced issue where people overexaggerate the harm with claims such as how Anthropic is “destroying rare books” (when it actually used, second-hand, out-of-print books that had many other physical copies) or wants to “shred every book on the planet” (destructive scanning was far cheaper and faster than non-destructive scanning, so the aim was not to destroy every book for the sake of replacing them with Claude; their memo’s line about aiming to get “all the books in the world” was to optimize for Claude’s training). Actual controversies lie in piracy and privacy issues.

Examples: [a post on X by Evan Luthra](https://x.com/EvanLuthra/status/2082573286966448351), [a Forbes video on the book scanning](https://www.youtube.com/watch?v=LAslxexwhOU), and [a r/antiai thread on the story](https://www.reddit.com/r/antiai/comments/1uv305v/the_most_antiai_story_imaginable_anthropic/).


***Hypothesized Reasons Why Beliefs that Downplay Capabilities Emerge***

One hypothesis of why these beliefs arise is that they partly stem from a hatred of AI replacing workers, especially in the creative fields. People see their hard work, talent, and education go to waste, and are insulted that people who did not put in this effort can take over their roles and livelihood. Thus, any information that is against AI capabilities- whether true, false, or exaggerated- is propagated. I believe these concerns are important, legitimate and should be addressed to help people with their livelihoods and well-being (as different issues than AI alignment. However, these concerns make people understandably angry and frustrated, and like how an invading force to a land makes its residents feel threatened, desperation to save their home can make people feel that they should use any means necessary to stop the invasion, even if it means spreading information without checking if it is actually true.

These beliefs can be potentially dangerous as they can interfere with AI alignment agendas, such as with funding capability evaluations research. As an analogy, imagine a real pandemic, during which information- both real and exaggerated- is constantly spread. When people find that the “exaggerated” information is false, they treat the pandemic like the “boy who cried wolf” and don’t believe even the real information. This can lead them to not treating the virus itself as real, even if they see others suffer and die from it with their own eyes. Then, they take steps to prevent political action that mitigates this pandemic, believing it to be a waste of resources. Similar to this imaginary pandemic story, envision a hypothetical scenario where people engage in belief perseverance after a misaligned, superintelligent AI arises, believing it to be a smoke-and-mirrors trick done by big tech, when big tech is not the puppetmaster pulling the strings anymore.

This is similar to a hypothetical situation in which a social media algorithm floods users with multiple types of malicious content, and people believe it must be a cabal of bad actors intentionally doing so, when it is possible there are two separate cases: a cabal intentionally does it, AND the creation does it itself without any intervention, as the creator has lost control of it. If people do not believe in the latter, they will only focus their efforts on trying to uncover and mitigate the former, which in some cases, will not affect the latter. Loosely resembling sandbagging, the AI “appears less capable” to the public, but is deceptively capable in areas that the public is not monitoring, and the real culprit is not caught.

## 4.2. Barrier B- Lack of Personal Relevance

There already is an effort to teach AI alignment to the public through popular influencers. For instance, Hank Green, an influential pop-science explainer, has [a video, with over 1.8 million views](https://www.youtube.com/watch?v=90C3XVjUMqE), in which he partners with ControlAI to discuss rapidly evolving AI capabilities and misalignment risks.

While the comments largely agree with slowing down AI, if one goes through the comments and his community ([r/nerdfighters](https://www.reddit.com/r/nerdfighters/)), one sees that many in his audience only agree with how they support **_anti-AI-industry_ goals** (as they mostly tie slow-down to the AI bubble fragility, power concentration, labor, or theft; for instance, one comment states: “Either AI is a bubble and causes the next Great Depression, or it works and causes the next Great Depression.”).

Thus, even when presented with AI alignment knowledge, the public may not latch onto it with much interest. I hypothesize that this is because they are unable to relate it to what they care about in life (such as their finances, immediate personal health, or status). This suggests that it is not enough to present this information by showing its serious consequences; one must do it in a way that the public cares about, and can believe.

Additionally, while there is some evidence of positive support, one should also compare it to the prevalence of negative support, which can quickly and unexpectedly gain traction. For instance, in that same video, there are also comments that rally against AI capability claims, such as one with over 280 likes by a user “konkonvulpix8712” that states:

> Modern AI companies want us to believe they are mere breaths away from AGI that could revolutionize or destroy the world, when really they’re selling fancy autocomplete. It’s why things like ChatGPT should not even be called AI…. This video is the kind of thing the industry would pay for. We are no where near the kind of AI that would be an existential threat to humanity.

# 5. Steps-to-Action: Strategies to Avoid Coalition Instabilities

Foremost, I propose that only passive research be done first. However, this passive research must include planning strategies on how to better interact with other AI opposition groups. These strategies can also serve as contingency plans for various potential scenarios and threat models to ensure AI alignment groups are not caught off-guard when public opinions suddenly shift. In this section, I describe one such high-level plan.

## 5.1. Develop passive research groups to better understand concerns and mindsets

There is a lack of rigorous statistical studies about the general public’s anti-AI beliefs, such as how prevalent they are, which ones are the riskiest, or trends of how they evolve. Thus, it can be beneficial to establish research teams dedicated to this subject to first scout the current landscape of beliefs. These teams can assess risks and timelines of how these public opinions affect crucial political events, and with how they evolve alongside short AGI/ASI timelines, developing plans based on both worst and expected cases.

These teams can also talk to previous partnerships, such as PauseAI and ControlAI, to evaluate how current relations are going. Protests like [a recent Stop AI march](https://www.dailycal.org/news/nations-1st-major-anti-ai-protest-sees-hundreds-march-on-downtown-san-francisco/article_8253b059-e793-4de4-a012-cc20ddc5ad69.html) have multiple anti-AI groups; a good way to observe interactions is by talking to people there. This would also involve comparing different communities, such as understanding why China’s public is more receptive of AI and less concerned with risks.

*Example roles for a research and strategy team include:*

1. Data scientists: to gather public opinion data, run sentiment analyses, run studies using market/consumer analysis (not for profits, but to check for opinions that can potentially hinder AI alignment efforts), etc.
2. Psychologists
3. Social scientists
4. Political/social strategists: understanding who, when, and how to engage, etc.

I propose that organizations only need to spend a tiny amount of resources, attention, and time on this topic for a small research team, approximately 0.1 to 0.3%, which can be enough to mitigate potential risks (and allows AI alignment supporters to be much better off than being unaware of this potential danger at all).

## 5.2. Proposed diplomacy plan

### 5.2.1. Assist them with their main concerns (to a realistic extent)

First, it is important to ensure friendly relations between AI alignment groups and other anti-AI groups. This can be done by acknowledging the legitimate concerns of these other anti-AI groups, and figuring out how AI alignment can help their concerns, while realistically acknowledging issues that AI alignment cannot help with. For instance, there are obvious overlaps on limits on reckless deployment, liability for harms, and transparency/disclosure; more research can look into finding other ways that AI alignment groups can help. This would bestow a positive public perception of groups affiliated with AI alignment as being empathetic, trustworthy, and beneficial. Thus, this should also be done without trickery; groups may “feel used or manipulated” if lied to, and turn against AI alignment.

### 5.2.2. Draw connections between AI alignment and their main concerns

Even though risks such as nuclear war and bioterrorism are real, the average person is not as concerned with them, as seen by the YouTube comments discussed in Section 4.2. Some dismiss the notions as “sci-fi” (as observed in the Introduction’s social media examples), downplaying current capabilities and/or future capabilities. Rather, the public seems more receptive to “how does this impact my life?” They are more concerned with what they see in front of them that affects their lives, their friend’s lives, or the lives of celebrities they follow: namely labor impacts, which is also what drives Pro-Creator factions.

Therefore, after ensuring that the other anti-AI groups know that they have the support of AI alignment groups, I do not believe AI alignment groups should lead with the most consequentially serious existential risks. Instead, I propose that AI alignment groups should start by drawing connections between existing anti-AI concerns (such as labor replacement and human wellbeing) that people do not doubt, then show evidence that supports claimed directions and speeds of which these concerns are evolving, and lastly, argue that these real, existing concerns can evolve into serious, existential consequences with superintelligence. This allows alignment concerns to become more relatable with concerns that the public sees right in front of them.

For example, many anti-AI people are concerned with how companies will replace workers with AI. This cannot occur unless there is some acknowledgment that AI can match some human capabilities, which most people do not doubt. However, one major issue is that many people do not believe in the jump from current capabilities to massively greater capabilities in the near future. Within this anti-AI group concerned with labor replacement, let’s identify a few separate camps:

1. **People who actually believe in that current AI capabilities are powerful, and believe it will grow very fast**: These people do not need much convincing. Even if they disagree with the speed of growth or what it will grow into, they are more receptive to changing their belief.
2. **People who think human replacement is done not because AI is more capable, but just because AI is cheaper**: These people do not believe in that AI capabilities are that strong or will grow much stronger, and require more convincing.
3. **People who believe the AI is “just stealing other people’s work” and that it cannot generalize well or create novel things beyond what humans train it on**: These people also do not believe in AI capabilities. They often believe they find the exact items from the training data that the AI “steals from”, claiming that it is largely the same thing, but only slightly modified. Some believe that AI is just a scam to get away with “copyright barriers” and that it actually isn’t doing anything impressive.

One cannot convince everyone to believe something. But one way to get some people from Camps 2 and 3 to believe in superintelligent risks is to change their belief about AI capabilities. This can be done by: 1) Explaining evidence in a way they are receptive to and understand, 2) Changing the factors that cause belief perseverance even under stark evidence (the latter is much harder to change, but it may be possible; one can think deeply about how to do this).

Likewise, for other mainstream concerns, one can describe how a misaligned AI can impact surveillance, how AI that is intelligent enough to “think for each person” can replace them in many more life roles than just jobs, or how a deceptively sycophantic AI can make people delusional. Given that these existing, real-world concers require acknowledging undoubtable capabilities, one can get people to infer that an AI with even greater intelligence can cause even worse outcomes. Framing a misaligned, superintelligent AI as obtaining control over executive decisions in large organizations becomes seen as more plausible, and that can get one to consider how governance tasks can be dictated and ruled over by a superintelligent AI that is out of big tech’s control for purpose of “making society more efficient”. This requires people to acknowledge the truth of increasing AI capabilities, and not just say that it’s “big tech” that is threatening, but the AI itself.

Lastly, sensationalism should be avoided, even if it drives clicks. If people do not make decisions based on realistic evidence and predictions, that can cause more harm than good.

### 5.2.3. Improve education about AI and correct misinformation

Section 4.1 showed a few examples of beliefs that doubt AI capabilities and which are based on half-truths, a lack of nuance, starkly incorrect information, and more. These can be mitigated by introducing engaging, comprehensible vectors of education, such as ones that clearly explain how AI works, and ones that show evidence from real-world events and research that demonstrate rapid capabilities progress. This information should be shaped for non-technical audiences by people who are good at communicating technical concepts to the general public.

### 5.2.4. Study how to deal with belief perseverance

Having information is not enough. For instance, during certain pandemics, there was a lot of misinformation spread online, some which even conflicted with obvious reality. In some cases, one cannot just show a person “something remarkable the AI does”; those entrenched in strong beliefs will deny reality just to preserve their beliefs. For instance, much disbelief about AI capabilities may not be due to a lack of observations about what it can do, but be due to a distrust of authority. To develop a better understanding of them, research teams may have to model peoples’ underlying psychological needs to cause them to harbor such beliefs, and find what causes people to change entrenched stances. 

## 5.3. An outreach style that focuses on authenticity

### 5.3.1. What kind of people should conduct outreach?

I propose that the “outreach group” would not be an actual, coordinated team that micromanages exactly what to say or think like a calculated politician- it would just consist of people who have good relationships with both influencers and public communities. Thus, most have no direct affiliation with a “formal” organization; they should be naturally seen as relatable people.  (In contrast, the research teams can be paid and operated as formally structured team(s), including within a formal organization, since their only goal is to gather the opinions of society to better understand and improve the concerns of people.)

Outreach people should understand the anti-AI public communities well; they may likely be a part of these communities (such as being artists or environmentalists), but would be highly pro-AI alignment (to prevent them from being convinced out of it by their own community or other social pressures). They may also work with psychology and anthropology experts to develop a theory of mind for these communities that can be understood by those outside of them.

*Examples of outreach roles may include:*

1. People within these communities, or have good relationships with them, who actually interact with them, not just “study them from afar”. These include influencers, such as those in “pop science”, but also includes people who do not have a large media presence but are well respected within local communities, or are just familiar with them.
2. Negotiators: people who are good at diplomacy with the general public, and do not take a two-faced, deceptive approach. These people should be genuinely trustworthy and morally upstanding. 
3. Science educators who do technical AI/governance research: people who are familiar with research, and can translate this to the general public. It is best they actually conduct this research so they do not misunderstand it. These are not purely “pop science” people who may misrepresent facts.

(Note that these descriptions are not job titles, but people who embody the desired characteristics.)

### 5.3.2. Authenticity is highly important

I also propose that AI alignment groups should avoid positioning themselves as “deceptive” or being “controlling” in the general public’s eye. There are already early warning signs that the public can obtain bad early impressions of AI alignment groups if they feel they don’t come from a place of authenticity, and appear overly demanding or controlling of what people say.

For instance, in the video “I was Offered Money to Tell You AI Will Kill Us” (mentioned in the Introduction), Sabine stated that she was contacted by AI alignment groups to talk about AI safety, but she rejected their offers. While Sabine only mentioned how she did not like how these messages interfered with her video-making decisions, AI-accelerationists attempted to take advantage of this negative association to smear AI safety as inauthentic, deceptive, and power-hungry.

(Side note: I am not viewing this situation from the perspective of someone from within these organizations; I am putting myself in the shoes of someone from outside of AI alignment who just encounters only what is shared online, which is limited to Sabine’s perspective, and leaves comments on social media, so I am not making claims on what actually happened between these organizations and Sabine.)

While this approach is practically effective to combat huge campaigns from opposing sides who are leveraging this area, it is only effective for certain people who are receptive to being paid this way. It is not an effective technique to reach out in every case. Thus, I propose that organizations should consider alternative strategies than just paying money to certain influencers (outside of AI alignment) to preach for AI alignment, especially if they do not strongly support it already.

So, how can outreach be done with “authenticity?” The solution may be overly simple: an individual has to be viewed as speaking from genuine concern over real risks, not as part of a campaign, a faceless organization, or a transaction. This sounds cheesy and vague, but it is just a way of saying how organic trust, including friendships, are built.

As such, the “outreach people” we’re discussing for here are not limited to people who are highly influential. They may lack a large following, but may be highly trustworthy to influencers, perhaps by having no strong ties to big organizations, or may connect with an audience well enough to dismiss smear campaigns, such as the ones launched on Alex Bores. They may be “likable average Joes” who do not have, and are not seen as having, deceptive “Machiavellian-like” intentions. They should not come across as “forcefully demanding or preachy” (note that this is not the same as saying that they must be passive and lukewarm).

“Naturally reaching out to someone” paradoxically sounds like a technique that a large organization with ties to big tech would do to deceptively “appear more natural”. But the people who are engaging in the outreach are *not* associated as part of these organizations; they are individuals who genuinely believe that AI alignment is a moral goal aimed for the betterment of humanity.

This is not completely dismissing “planning/strategizing” about good relations; all relations require planning, such as strategically discerning the best way to approach a friend about a difficult conflict, and this is not overly romanticizing “authenticity”. Rather, I am proposing that having the public see the cause as authentic is highly important, and the best way to do that is just by actually being relatable, open, and authentic. This is also not a criticism that this is not how things have been handled so far- it is saying that because a first impression on *a large amount of the general public* (enough to swing voting outcomes) has actually *not* been made yet, then the first impressions should aim for authenticity. However, there are a few first impressions on a *tiny subset* of the general public in which they interpret (regardless of actual intentions) AI safety groups as “inauthentic”, and this has had negative consequences. This serves as a good early warning sign that can be learned from.

While the research team itself may appear formal and inauthentic, the outreach team should be authentic. Consider an analogy to explain how this can work: when there is someone who is in an emotional crisis, there are psychologists and doctors who “coldly study” the patient to obtain data to accurately diagnose them. Without these “inauthentic” studies, accurate diagnoses cannot be obtained- one would not have an unbiased assessment of the patient’s biological and mental states/history, which are highly important to helping them. But the ones who actually reach out to the patient are the therapists, friends, family, and support groups who are, ideally, genuinely authentic and develop a bond with the patient. Those in outreach are greatly helped by the information provided by the “cold assessments” from doctors and scientists; for instance, they may learn that there are certain traumatic topics to not talk to the patient about. In this case, “political strategists” should study population statistics to understand the best ways to approach people and provide information to the outreach team, but the actual way that people are approached is entirely decided by the outreach team.

Lastly, an appeal to authority won’t work when many in the general public are distrustful of big tech and academia unless it’s supported by influencers they trust.

### 5.3.3. Avoiding overly transactional “business” relationships

If those being reached out to feel that they’re just being used to “give a frontier lab good PR”, they may feel coerced. In contrast, if individuals (rather than organizations) reach out in good faith, arguing from moral goals, then people may be more receptive.

This direction would focus on outreach people strongly filling the information-space with actual evidence and arguments, correcting misinformation, exaggerations, and more, and relying on each individual’s free will to develop their own beliefs. While there are influencers who can be paid off, these are unstable partnerships; it is more stable to ally with those who actually believe in the cause, and genuine friendships should be established. The goal is not to win or control, but to relay an important message that helps humanity.

Likewise, AI alignment should distance itself from being industry-centered. The public should see AI alignment as independent from industry, but allying with certain companies for shared goals. That’s different from misconstruing the movement as a “big tech led way to get people to be more pro AI”.

## 5.4. Outreach Strategies

### 5.4.1. Connecting with influencers

The majority of the general public does not need to be aware of or support AI alignment; there are only certain groups that would make a difference for practical outcomes. Additionally, each group only needs to be on-board to a certain degree- some groups need to actually understand that capabilities are not a “scam”, while others just need to agree with slowing down capability building.

I do not believe it is worthwhile to try to sway the opinions of people (and influencers) who heavily downplay capabilities. While some of these people are highly intelligent and not wrong, and having a different opinion than AI alignment is not enough as the sole reason to declare them to be wrong, some of what they present is biased, and some also rests on misinformation. But these are intelligent people who will feel insulted if they’re told what to think, rather than independently derive it. I believe that the best way they can be swayed is if they are given information, and derive it for themselves.

For instance, Notch, the creator of Minecraft, did not support AI coding. But later, [he tried it for himself, and was highly impressed by its capabilities](https://x.com/notch/status/2081917722854674642). While he still hates AI and how it replaces programmers by training on their own code, he uses it for coding.

Now I will discuss what I believe is a better way to connect with influencers. To more clearly state what I mean by an “influencer”, I define it as anyone who has a large audience of followers whose opinions are swayed by the influencer. I believe that it is better to spend resources on convincing influencers who have no strong anti-AI opinions yet, already side with AI alignment. I also believe connecting with general audience influencers who are not just entirely dedicated to AI is even more important than connecting to those with a niche AI-familiar audience. Outreach people should form genuine relationships with trustworthy influential people (in gaming, art, video essayists, streamers, popscience, and more). They should also assess if an influencer is prone to “giving in to the mob/audience” based on past behavioral patterns. Lastly, it is highly advantageous if an influencer already has AI-knowledgeable or alignment supporters within it, as they help correct misinformation that their fellow members spread.

Next, we discuss examples of influencers, and their current or potential opinions on alignment. This serves to illustrate a glimpse into the current online landscape:

**1. People who acknowledge AI capabilities (and potentially AGI) and are pro stop/slow (lean towards alignment)**

- Kyle Hill: YouTube pop-scientist who is highly pro alignment
- Cassie Pritchard: an anti-AI labor activist on X who pushes for beliefs in dangerous AI capabilities
- John Oliver: talk show host who discusses AI safety, but more focus on current capabilities rather than on future superintelligence

**2. Existing partnerships that can be bolstered**

- Hank Green: pop-science explainer who made a video discussing AI alignment, while also criticizing doomerism. Notably, had a controversial incident where he apologized to his audience for using AI.
- Kurzgesagt: Makes videos on AI safety

**3. People who are on the fence**

- Sabine Hossenfelder: Claims to be open to being pro or anti AI, and is sympathetic to slowing down AI, but is not like being not badgered to parrot others’ views. Sees herself as an “infoencer”.

**4. People who strongly downplay capabilities**

*People familiar with technical/business fields: preach about AI bubble, not as concerned shutdown/slowdown*

- Angela Collier: a physicist with a large following on YouTube who doubts AI capabilities
- Coffeezilla / voidzilla: a journalist who focuses on exposing scams. But focuses on actual AI scams, and likely is not interested in discussing other topics

*People in media / creative arts: still in favor of shutdown/slowdown, but not due to AI alignment*

- Karla Ortiz: a highly influential artist whose one Bluesky post rallying against how San Diego Comic Con allowed AI reverted SDCC’s policies in just a day
- Adam Conover: talk show host
- Drew Gooden: YouTuber focused on anti-AI in creative media

*Famous Academics: still in favor of shutdown/slowdown, but not due to AI alignment - can be invited as expert guests to anti-AI podcasts*

- Gary Marcus: pro-AI but “anti gen AI”
- Timnit Gebru: anti-AI for fairness, environment, and big-tech power concentration

**5. Wild Card Influencers**

- Moistcritikal: a streamer who has a huge public audience, and has fluctuating views on AI. In [a video with 1.5 million views](https://www.youtube.com/watch?v=9T8blyb5_Uw&lc=UgzyHN4c-1IQFkXsmcd4AaABAg), he showed support for Anthropic’s stand against mass surveillance and AI weaponry. His audience gave 23k likes on a comment stating: “When the AI company is the good guy you know shits getting bad”.

### 5.4.2. Empower existing AI alignment outreach groups

These groups include:

1. [Rational Animations](https://www.youtube.com/RationalAnimations)
2. [CivAI](https://civai.org/)
3. [Frame Fellowship](https://www.framefellowship.com/)
4. [Siliconversations](https://www.youtube.com/@Siliconversations/videos)

### 5.4.3. Casually talking as individuals

Talking to others about alignment is also important on an individual level, not just organizational. Any individual (even in big tech) can be an outreach person, but they should be prepared to do it well. AI alignment support would greatly benefit by being prepared to answer questions consistently and logically, such as in “elevator talks” during events, with friends/family, during protests, debates, and online. For instance, they should be able to answer simple questions of “Why not just stop building it?” with persuasive, honest, easy-to-understand, and non-contradictory answers, and obtain a good theory of mind of how other people would respond. It is important to understand how to challenge misinformation they use in their claims while simultaneously not pushing them away from supporting AI alignment goals. Unexpected antagonization can be dangerous- one can believe they are reaching out to them well through a gesture, when they are actually antagonizing them. Thus, cultivating both theories of mind for different types of people, and skills to reach out to them, is paramount for this task.

# 6. Potential Counterarguments and Risks

**1. If engagement is done wrong, it could have the opposite effect where AI alignment is seen as pushy and reveals that they are against public interest. It may be better to be unnoticed so no judgment is done.**

*Response:* I do not believe AI alignment groups should recklessly start engaging with these groups, as seen by the response to PauseAI on r/ArtistHate. I advocate that passive research must first be done to scout for the current landscape of different groups, their goals, and how they may respond to AI alignment agendas. Then, these research groups should decide what is the best strategy to engage with them: if they decide to reach out, how to reach out to them; or, they may decide it is best to not reach out to them. Either way, obtaining more data on these other factions is highly valuable to brace for potential risks, such as enemies against one’s organization (skeptics and accelerationists, or even those in-fighting within AI alignment movements).

**2. There is the risk that transparently coordinating these movements in public can give opposing enemies the idea to do this when they did not do it before, or be one step ahead of alignment organization.**

*Response:* I believe that merely introducing this idea has this trade-off: if we do not introduce this idea to a wider audience, this danger goes unnoticed, and because there are already possible acts of this occurring, and risks that it may be bigger than suspected, introducing this idea will increase awareness and thus increase mitigations against these dangers with contingency plans.

**3. A temporary, unstable alliance is fine given the short timelines of AI capability dangers; a means to an end is necessary and has few side effects. Thus, establishing stability is not worth it. Just banding together to slow down frontier compute works.**

*Response:* I agree that a temporary alliance is ok for now; however, I believe there are risks that side effects may occur even after just a few months. Public opinion shifts very fast, especially in the age of social media. The resources devoted to mitigating side effects of unstable alliances (by attempting to make them stronger) are relatively few, and may have large impacts if done right.

**4. If they have misunderstandings about AI alignment actual goals, and these misunderstandings get them to the same desired political outcomes as AI alignment, then they are useful as a means to an end.**

*Response:* It is tempting to amplify these misunderstandings. But this is deceptive, and if found out, the groups will turn sour on trust.

**5. One of the dangers is that these can be seen as “extremist or fringe views”, so it’s not worth focusing on.**

*Response:* The issue with this way of thinking is that in recent years, extremist or fringe views have become more popular and mainstream, with large amounts of the “normal” population believing in various conspiracies. Without a proper empirical analysis of how prevalent these beliefs are, and how susceptible they are to spreading online, one is blind to their potential dangers in the near future. Views on AI mutate very fast, and when paired with short AGI timelines, this can introduce possible fast-evolving conflicts.

**6. If the risk is small now, why spend resources on it?**

*Response:* The consequences are impactful, as discussed throughout this writing, while the resources devoted to it should be relatively few. Thus, it’s a worthwhile trade-off.

**7. This is hard to succeed in.**

*Response:* The starting point of this is to just establish research teams to analyze data and come up with hypothetical strategies based on this data. This can even start with volunteers without any funding (and see how far they can get). While successful outreach may be difficult, I propose that we do not first aim for successes, but to gather data, devise plans and then estimate their success rates (and finally, to enact the plans)- without this data or attempts at plans, we are missing information that can help us estimate how difficult it is to succeed here.

# 7. Conclusion

Overall, I do not argue that public anti-AI sentiment is an enormous threat to AI alignment, nor that AI alignment organizations should immediately launch large-scale campaigns to persuade the public. Rather, it is that this area represents an overlooked source of political risk that deserves substantially more research. As AI alignment becomes increasingly dependent on legislation, elections, public funding, regulation, and other political mechanisms, public opinion can become an important factor in whether alignment agendas succeed or fail. Anti-AI groups may currently support some of the same outcomes as AI alignment organizations, particularly in slowing or restricting AI development, while holding very different underlying beliefs about why AI should be restricted. These differences can create unstable coalitions that fracture when their goals no longer coincide.

This risk is especially important because “anti-AI” is not a single ideological position; as of now, “anti-AI” is an overloaded term, comprising groups with both shared and opposing goals. It includes people primarily concerned about labor displacement, creative work, surveillance, environmental harms, human wellbeing, corporate power, bias, and other issues, alongside a much smaller category of people primarily concerned with misalignment or existential risk. Some of these groups may become strong allies of AI alignment efforts, some may remain opposed, and others may support only particular policies. Treating all of them as interchangeable because they currently favor slowing AI risks obscuring these differences. A better strategy is to understand where genuine common ground exists, where disagreements are likely to emerge, and which partial alliances are most vulnerable to political manipulation or naturally occurring conflict.

Thus, some of my suggested proposals include:

1. **Passively developing better public opinion research and outreach strategies**
2. **Developing an improved theory of mind for each anti-AI constituency**
3. **Prioritizing authenticity and trust during outreach**
4. **Building relationships that address both common interests and certain concerns**
5. **Improving public understandings of AI capabilities and alignment**
6. **Preparing for rapid changes in opinion**
7. **Keeping the intervention proportional to the threat**

There is also an potent opportunity associated with this risk. Much of the general public has not yet developed a detailed view of AI alignment. This creates a limited period to strongly inoculate against reputational blowback, in which first impressions can still be shaped by accurate information and genuine interaction. If alignment groups do not understand anti-AI public audiences, opponents may instead define AI alignment for them through accusations of hypocrisy, industry capture, elitism, or indifference toward present-day harms. But if their perceptions can be changed to see AI alignment in a positive light, then potentially powerful relationships and alliances can form.

In conclusion, I propose that AI alignment supporters move away from exclusively relying on only changing the policies of laboratories, governments, and industries. The success of alignment is increasingly becoming dependent on the views of the general public, whose true goals and intentions related to AI alignment remain largely unknown. Currently, there is a lack of interaction between AI alignment groups and the general public. But AI opposition groups may be able to learn much from each other, both in truths and values, helping to shape each others’ views and correct misinformation. However, this can only occur with open-minded dialogue and a desire to optimize for truths that would benefit the well-being of conscious lives. Otherwise, the sea of information is left ripe for manipulation.
