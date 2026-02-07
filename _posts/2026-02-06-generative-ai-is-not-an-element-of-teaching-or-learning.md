---
layout: post
title: Generative AI ∉ (Teaching ∪ Learning)
subtitle: There are no ethical use cases for generative AI in higher education
thumbnail-img: /assets/img/posts/datacenter-energyusage.png
share-img: /assets/img/posts/datacenter-energyusage.png
tags: [AI]
author: Peter Keep
mathjax: no
---

My college hosts a professional development day every semester for faculty and staff, and this semester's is...interesting. There's a theme for the day, normally something connected loosely with a recent college goal or broad focus. This semester, it's "Approaching AI with Teamwork and Heart."

I got this theme in an email along with a call for presentation proposals, so you can bet that I shot a message to a friend on campus, asking if they wanted to co-present something with the following description:

> "There are no ethical use cases for generative AI in higher education. In this presentation, we'll discuss a host of ethical reasons why generative AI tools are not elements of teaching or learning and how the use of generative AI is fundamentally at odds with our students' agency as well as their humanity."

I'm going to use this post to collect some notes and references as I prepare for this session (if it gets accepted).

# Data Security and Privacy

* Legal experts warn that user-facing generative AI tools should be considered insecure, and that even with confidentiality agreements there is little guarantee that inputted data will remain private.[^privacy]
* Ed tech companies have failed to keep students' data secure[^FTC] and have been alleged to have harvested and monetized student data without permission.[^IXL]
* The health care industry, which has been quick to adopt generative AI tools, has seen increased data policy violations directly due to the use of generative AI tools.[^healthcare]
* Generative AI tools collect huge amounts of data on users, and data leaks in generative AI models are typically used to train the model itself, meaning identifying information can be retrieved long after the leaked data is "removed."[^surveillance]

# Training Data and Models

* Training data sets are built from anything searchable on the Internet, including huge amounts of personal information, unverified claims, and intentional misinformation.[^personal]
* Because training data includes copyright material, output from generative AI tools can and does include plagiarized material.[^examples]
* Institutions are encouraged to develop clear policies about intellectual property,[^IP] and using generative AI tools on any student could violate these policies.
* Bias in generative AI models comes from a mixture of human decisions as well as systemic issues in the data or models themselves, and efforts to "debias" these models are often costly, ineffective, and can even compound the biases.[^bias]
* Biases are based on racism,[^racism] gender bias,[^gender] ableism,[^ableism] fatphobia,[^fatphobia] anti-Queer bias,[^queer] and political/religious bias.[^religion]
* Generative AI models are "black box" models--opaque and uninterpretable--making compliance with privacy policies, protection against biases, and general accountability difficult or impossible.[^blackbox]
* Models rely heavily on human classification for training, leading to workers required to watch abusive content in order to classify violent and abusive outputs.[^abuse]

# Environmental Impact and Energy Use

* Data centers have a high ratio of physical footprint to employment. Large data centers do not scale the number of jobs they create with the space they take.[^RPA]
* Data centers can use the same amount of water (mostly used for cooling hardware) as a town of 50,000 people and contribute to air quality degradation and public health costs.[^NWF] 
* Electricity usage by data centers is increasing rapidly, putting stress on the energy infrastructure. Updates are now required more often, resulting in outages and increased billing for the general population in those areas.[^usage]

{: .caption}
![A line chart showing energy usage increasing from around 60 TWh in 2014 to 175 TWh in 2023. After this, there is a widening range of predicted values that keep increasing, ending with a predicted range of 325TWh to 580TWh in 2028. The plot has three annotations, showing that in 2018, data centers accounted for 1.9% of the US Total electricity consumption. This number is 4.4% in 2023, and the range in 2028 is 6.7%-12%.]({{ '/assets/img/posts/datacenter-energyusage.png' | relative_url }})
*Total U.S. data center electricity use from 2014 to 2028.[^usage]*

* Previous clean or renewable energy usage requirements for data centers have been dismantled, allowing for the increased energy usage to come from energy sources that we know are not sustainable or environmentally friendly.[^EO]
* Black Americans are disproportionately harmed by air pollution already,[^pollution] and are expected to have an even larger increase in health risks due to the increased demand for data centers.[^healthrisk]


# User Safety

* Several lawsuits have been filed against OpenAI, alleging that their ChatGPT product has been partially responsible for wrongful death, assisted suicide, manslaughter, and other consumer risks due to negligence.[^suits] These have been so frequent and high-profile, that OpenAI has a public statement on their website detailing their approach to mental-health litigation.[^OpenAI]
* Elon Musk's xAI is under investigation[^investigation] due to the amount of non-consensual and sexually explicit images created to harass women on Twitter/X, as well as child sexual abuse material created using the generative AI tool, Grok.[^xAI]
* Psychologists are concerned about the increase in psychosis connected with generative AI usage.[^psychosis]
* While tech companies claim to have implemented safety features and guard rails for their generative AI tools, there is little certainty that they are actually effective or cannot be circumvented.[^NYT]

# Academic Malpractice

* Use of generative AI tools for assistance in tasks do not lead to statistically significant advantages in completing the tasks, but do lead to statistically significant reductions in retention or understanding of the task.[^Anthropic]
* Humans that engage with generative AI tools in their work become less engaged, less motivated, and any efficiency advantages do not remain in longer term contexts.[^Nature]
* When people use generative AI tools for assistance in tasks, they reduce the effort that they put into the task and do not think critically.[^Microsoft]
* In educational settings, generative AI usage leads to short-term gains in lower-cognitive tasks, with decreases in the higher-order cognitive tasks like retention.[^retention]
* Ed tech products, while claiming to provide highly tailored assistance for each individual student, is largely useless and has no positive impact on learning. If anything, it has a negative impact on learning.[^Economist]

# Conclusion

Even with this extremely incomplete list, I think it suffices to say that, if this presentation proposal gets accepted, we'll have enough content to fill the hour.

It is shameful for any academic institution to embrace generative AI tools in any way.

# References


[^privacy]: [Concerns and legal issues surrounding AI](https://legal.thomsonreuters.com/blog/the-key-legal-issues-with-gen-ai/)
[^personal]: [Your Personal Information Is Probably Being Used to Train Generative AI Models](https://www.scientificamerican.com/article/your-personal-information-is-probably-being-used-to-train-generative-ai-models/)
[^FTC]: [FTC Takes Action Against Education Technology Provider for Failing to Secure Students’ Personal Data](https://www.ftc.gov/news-events/news/press-releases/2025/12/ftc-takes-action-against-education-technology-provider-failing-secure-students-personal-data)
[^IXL]: [IXL class-action suit advances amid student data harvesting claims](https://www.k12dive.com/news/ixl-learning-class-action-lawsuit-student-data-privacy/733335/)
[^healthcare]: [Threat Labs Report: Healthcare 2025](https://www.netskope.com/resources/threat-labs-reports/threat-labs-report-healthcare-2025#genai-usage)
[^surveillance]: [Unmasking EdTech's Surveillance Infrastructure in the Age of AI](https://www.techpolicy.press/unmasking-edtechs-surveillance-infrastructure-in-the-age-of-ai/)
[^RPA]: [The Rise of Data Centers in the Grid ](https://rpa.org/news/lab/the-rise-of-data-centers)
[^usage]: [2024 United States Data Center Energy Usage Report](https://escholarship.org/uc/item/32d6m0d1)
[^examples]: [Theft is not fair use](https://jskfellows.stanford.edu/theft-is-not-fair-use-474e11f0d063)
[^IP]: [IP Policies for Universities and Research Institutions](https://www.wipo.int/technology-transfer/en/ip-policies.html)
[^bias]: [Addressing Bias in Generative AI: Challenges and Research Opportunities in Information Management](https://arxiv.org/pdf/2502.10407)
[^racism]: [Covert Racism in AI: How Language Models Are Reinforcing Outdated Stereotypes](https://hai.stanford.edu/news/covert-racism-ai-how-language-models-are-reinforcing-outdated-stereotypes)
[^gender]: [How AI reinforces gender bias—and what we can do about it](https://www.unwomen.org/en/news-stories/interview/2025/02/how-ai-reinforces-gender-bias-and-what-we-can-do-about-it)
[^ableism]: [Trained AI models exhibit learned disability bias, IST researchers say](https://www.psu.edu/news/information-sciences-and-technology/story/trained-ai-models-exhibit-learned-disability-bias-ist)
[^fatphobia]: [Fatphobia Is Fueled by AI-Created Images, Study Finds](https://now.fordham.edu/science-and-technology/fatphobia-is-fueled-by-ai-created-images-study-finds/)
[^queer]: [Busting Anti-Queer Bias in Text Prediction](https://viterbischool.usc.edu/news/2022/08/busting-anti-queer-bias-in-text-prediction/)
[^religion]: [AI is biased in favour of US evangelicalism. It doesn’t have the mind of Christ](https://www.premierchristianity.com/opinion/ai-is-biased-in-favour-of-us-evangelicalism-it-doesnt-have-the-mind-of-christ/20900.article)
[^blackbox]: [Generative AI and the imperative for transparent monitoring](https://www.o3world.com/perspectives/navigating-generative-ai-black-box-transparency-control/)
[^abuse]: [‘In the end, you feel blank’: India’s female workers watching hours of abusive content to train AI](https://www.theguardian.com/global-development/2026/feb/05/in-the-end-you-feel-blank-indias-female-workers-watching-hours-of-abusive-content-to-train-ai)
[^EO]: [Executive Order: Accelerating Federal Permitting of Data Center Infrastructure](https://www.whitehouse.gov/presidential-actions/2025/07/accelerating-federal-permitting-of-data-center-infrastructure/)
[^bill]: [Data Center Growth Could Increase Electricity Bills 8% Nationally and as Much as 25% in Some Regional Markets](https://www.cmu.edu/work-that-matters/energy-innovation/data-center-growth-could-increase-electricity-bills)
[^NWF]: [More data centers, more environmental problems?](https://www.nwf.org/Magazines/National-Wildlife/2025/Fall/Conservation/AI-Data-Centers)
[^pollution]: [Fine Particulate Air Pollution from Electricity Generation in the US: Health Impacts by Race, Income, and Geography](https://pubs.acs.org/doi/10.1021/acs.est.9b02527)
[^healthrisk]: [Data Center Boom Risks Health of Already Vulnerable Communities](https://www.techpolicy.press/data-center-boom-risks-health-of-already-vulnerable-communities/)
[^suits]: [Seven more lawsuits filed against OpenAI for ChatGPT manipulation and ‘suicide coaching’](https://www.transparencycoalition.ai/news/seven-more-lawsuits-filed-against-openai-for-chatgpt-suicide-coaching)
[^OpenAI]: [Our approach to mental health-related litigation](https://openai.com/index/mental-health-litigation-approach/)
[^investigation]: [Attorney General Bonta Launches Investigation into xAI, Grok Over Undressed, Sexual AI Images of Women and Children](https://oag.ca.gov/news/press-releases/attorney-general-bonta-launches-investigation-xai-grok-over-undressed-sexual-ai)
[^xAI]: [Elon Musk's Grok AI floods X with sexualized photos of women and minors](https://www.reuters.com/legal/litigation/grok-says-safeguard-lapses-led-images-minors-minimal-clothing-x-2026-01-02/)
[^psychosis]: [The Emerging Problem of "AI Psychosis"](https://www.psychologytoday.com/us/blog/urban-survival/202507/the-emerging-problem-of-ai-psychosis)
[^NYT]: [Researchers Say Guardrails Built Around A.I. Systems Are Not So Sturdy](https://www.nytimes.com/2023/10/19/technology/guardrails-artificial-intelligence-open-source.html)
[^Anthropic]: [How AI assistance impacts the formation of coding skills](https://www.anthropic.com/research/AI-assistance-coding-skills)
[^Nature]: [Human-generative AI collaboration enhances task performance but undermines human’s intrinsic motivation](https://www.nature.com/articles/s41598-025-98385-2)
[^Microsoft]: [The Impact of Generative AI on Critical Thinking: Self-Reported Reductions in Cognitive Effort and Confidence Effects From a Survey of Knowledge Workers](https://www.microsoft.com/en-us/research/wp-content/uploads/2025/01/lee_2025_ai_critical_thinking_survey.pdf)
[^retention]: [Short-Term Gains, Long-Term Gaps: The Impact Of GenAI and Search Technologies On Retention](https://scale.stanford.edu/ai/repository/short-term-gains-long-term-gaps-impact-genai-and-search-technologies-retention)
[^Economist]: [Ed tech is profitable. It is also mostly useless](https://www.economist.com/united-states/2026/01/22/ed-tech-is-profitable-it-is-also-mostly-useless)