NewsByte: Digital Archive and Debate Synthesis Hub

Hacktober Fest Open Source AI Hackathon | Qualifier Submission | Team BYTE_ME

---

1. Project Name

NewsByte is a local, open-source AI research desk that collects news articles, organizes them, and uses Gemma 4 E4B running on Ollama to synthesize them and to separate opposing viewpoints on any topic with the help of relevant articles.

---

2. Problem Statement

Understanding a news topic properly means reading many articles from different sources and different years. In practice this is slow and one-sided:

>Readers open articles one by one through a search engine and rarely compare them side by side.

>Articles end up scattered across browser tabs, with no single place to collect, annotate and revisit them.

>On controversial topics, people tend to read only the viewpoint they already agree with and never see the strongest opposing argument.

>General AI chatbots answer from memory, not from the articles the user is actually reading. They can make up facts and give no sources.

>Cloud AI services need accounts, API keys and per-request cost, and they send the user's research questions to third parties.

*There is no simple, open-source tool that gathers articles, keeps them as a searchable archive, and gives answers that are tied to those articles, along with a fair view of both sides of a motion.

--

3. Project Overview

NewsByte is a web application with four connected workspaces:

Workspace	Purpose

I. Global Wire:	Search a topic within a year range and fetch recent and historical news articles.

II. Editor's Desk:	Drag and drop articles into a working set, return them to the feed, and keep a Research Notebook.

III. Synthesis Engine:	Ask Gemma 4 E4B a question. It answers only from the clipped articles, or from the stored archive plus live news, and cites its sources.

IV. Debate and Perspective Room:	Enter a motion and a year range. The system shows articles For and Against the motion in two columns.

Privacy note: the language model and the embedding model both run on the user's own machine, so questions and article text are never sent to a cloud AI service. Only the search keywords go to the public news sources when articles are fetched.

---

4. Target Users / Use Case

User	                          Use case

1.Students and debaters:	       Prepare both sides of a motion with real news evidence.

2.Researchers and journalists:	 Collect and compare coverage of a topic over a period of years, with notes.

3.Curious readers:	             Understand a controversial issue without staying inside one viewpoint.

4.Privacy-conscious:             users	Use AI on their research without sending questions to a cloud AI service.

Example: a debate student enters the motion "Should social media be restricted for children?", sets the years 2023 to 2026, and gets supporting and opposing articles in two columns. She clips the best ones to the Editor's Desk, adds notes, and asks the Synthesis Engine to compare the strongest arguments, with sources.

--

5. Objectives
   
1.Build a source-grounded news research assistant using only open-source AI.

2.Let a user go from a topic to a collected, annotated set of articles in a few minutes.

3.Give answers that name their sources and stay inside the supplied articles.

4.Present both sides of a motion fairly, with the model verifying each article's stance.

5.Keep the AI neutral on disputed issues and clearly separate facts from opinions.

6.Run the language model locally on a single laptop with Gemma 4 E4B

7.Keep the architecture modular so sources, models and features can be swapped or extended.



