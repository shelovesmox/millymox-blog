---
layout: post
title:  So you are worried about AI?
description: Unraveling the complexities of AI and why newcomers should focus less on worrying.
date:   2023-11-17 15:01:35 +0300
image:  '/images/post1.jpg'
tags:   [Software Engineering, AI]
---
You've come across ChatGPT and AI Hypist have convinced you that you ought to be paranoid about the security of your new interest/career, and frankly, they aren't **entirely** wrong. However, it's important that you realize the state of AI right now, its capabilties and the nuances that come with software engineering. I'll also share my perspective on the matter and why you should do less worrying, and more programming.



### Software Engineering Is NOT Just About Coding

As a young engineer and novice programmer its important you must understand that the sheer complexity of software engineering extends far beyond simply coding. It involves maintaining huge codebases with millions of lines, documenting and comprehending the program's requirements to meet the needs of end-users and stakeholders, and performing maintenance. This includes patching bugs, rolling out updates, ensuring compatibility with new systems and hardware, and writing high-quality tests. And while AI can automate making test, its human judgement that remains and will continue to remain highly valuable in deciding which areas need more testing based on potential risk and tradeoffs.

Right Now [GPT 4](https://chat.openai.com/) is the most powerful language learning model (LLM) available to the public. You most likely (Where have you been if not?) have heard of GPT 4, and hell you probably use it, I sure do. It is incredibly helpful when breaking down concepts, complex code or generating quick snippets of code for things I may be too lazy to write. I love ChatGPT and i pay for the subscription because it yeilds value to me. Despite this it is not a replacement for an junior engineer (yet). It's a non expert tutor that doesn't get annoyed by endless questions. The more I use ChatGPT, the more i realize how little it really knows about software engineering. Again, don't get me wrong its an incredible tool, but it has some weak points.

![Preventing Data Races]({{site.baseurl}}/images/gpt4ex.png)
*GPT 4 / [OpenAI](https://openai.com/)*

| Weak Point | Description |
|-----------|-------------|
| Lack Of Memory | Memory limitations or inability to retain past interactions effectively. |
| No Understanding of My Environment and System | Inability to directly perceive or interact with the user's physical environment or computing system. |
| Inability to Comprehend Obscure Documentation | Difficulty in understanding poorly written or highly technical documentation without context. |


The last point resonates with me a lot. I was trying to get ChatGPT to help me with a GUI library in Rust. There was 0 documentation besides docs.rs and code examples (which in my opinion is a lazy replacement for documentation). I downloaded the entire docs.rs page for the library and fed it into ChatGPT piece by piece and despite this, it still couldn't figure out how to help me make a custom widget. This is where the disconnect happens between AI Enthusiasts and engineers/non-AI Enthusiasts. Software engineers who actually write, test, and distribute software, and also use tools like ChatGPT realize these limitations and issues. But AI Enthusiasts who had ChatGPT write them a half-baked ping pong game in Python think that's it and we are to be automated within the year. I want to highlight however that these limitations and issues are not things that can't be fixed, but telling people their jobs will be automated by GPT 4.5 "Make up random libraries and borrow the borrow checker from the borrow checker with the borrow checker (Rust joke, unfunny I know)" is absurd and does nothing but cause panic. On the contrary, if all you know how to do is code. You will find yourself outpaced in the future, as engineers who can code and use AI tools will render you obsolete. So pick up these tools, learn them thoroughly and understand their limitations. Most importantly though, expand your skillset outside of coding. Read a book about software design and architecture (Computer Systems: A Programmer's Perspective - One Of My Favorites), deepen your knowledge in database management and optimization, learn how to write automated tests, scale infascrutue, and practice the best security patterns.

### Translating Ambiguity and Business Requirements into Clarity

Oftentimes as an engineer, you'll be given a ticket with a vague request or feature addition. For example, your product manager or higher-up might say, 'Enhance User Experience,' with no additional context whatsoever. What exactly does enhancing user experience mean? This is a prime example of something AI currently cannot do. Current AI does not seem to possess the ability to process ambiguity. Test it out. If you ask GPT-4 to 'Enhance' the user experience and provide a snippet of code, it typically won't seek clarification or additional context. Instead, it attempts to generate a plausible response based on its training, which might include suggesting new features that could, in theory, enhance the user experience. However, these suggestions may not always align with the specific business needs. It's important to recognize that, despite its sophistication (trigger warning for AI enthusiasts), GPT-4 is fundamentally a text generation tool. It lacks true comprehension and the ability to ask follow-up questions; it makes no effort to try and understand your request. That's because it doesn't. It's simply giving you what sounds good. It's quite telling that AI Enthusiasts prop these tools up to be things they aren't, and actual Machine Learning Engineers and researchers aren't. Well apart from the researchers at OpenAI. But keep in mind this is a business and its in their best interest to hype their niche.

![GPT 4 Attempts To Enhance User Experience]({{site.baseurl}}/images/gpt4amb.png)
*GPT 4 / [OpenAI](https://openai.com/)*

I do not claim to know everything about AI and i'm not going to educate you on it. But i urge you to educate yourself on AI, understanding how it works will provide with better all around knowleadge so you are able to come down to your own conclusions on new developments or community activity.  nstead of being swayed by those who engage in speculative discussions and claim that your job will be replaced and AGI ([Artficial General Intelligence](https://en.wikipedia.org/wiki/Artificial_general_intelligence)) is next year.

By the time software engineers can be fully replaced by AI (I am a strong believer we would need AGI at the very minimum to achieve this) then every other job would also be replaced. The trades are safe until robotics catches up, and they aren't too far behind. So realistically, you might have a few extra years after all the white collar jobs are replaced, but blue collar jobs are next up on the chopping block.

![Alt Text](https://2.bp.blogspot.com/-ztv8BcdPQpI/WEqOPjy_CmI/AAAAAAAEup8/e35JaOBGUwst6W50I1MC5UIzkH0qT2hHwCLcB/s1600/AW328916_02.gif)
