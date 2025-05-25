🧭 PhilosophyMap

PhilosophyMap is a data-driven exploration of how philosophical discourse plays out across Reddit. By pulling live data from several philosophy-adjacent subreddits, the project analyzes language, sentiment, cited thinkers, and concept networks to visualize the emotional and intellectual contours of modern discourse.

📊 Subreddits Analyzed
	•	r/philosophy
	•	r/askphilosophy
	•	r/stoicism
	•	r/sociology
	•	r/TrueAskReddit

🔍 Key Objectives
	•	Measure and compare keyword prominence using TF-IDF
	•	Detect discourse structure through concept co-occurrence graphs
	•	Analyze emotional tone using the NRC Emotion Lexicon
	•	Track citations of philosophical figures and compare emotional distance
	•	Synthesize everything into a Discourse Compass mega-visual that captures the personality of each subreddit

🧠 Methodology
	•	Data Collection: Reddit API via praw
	•	Preprocessing: Tokenization, lemmatization (SpaCy), stopword removal
	•	Keyword Analysis: TF-IDF matrix per subreddit
	•	Emotion Scoring: NRC Emotion Lexicon, aggregated by subreddit
	•	Network Graphing: Co-occurrence of noun phrases, visualized with NetworkX
	•	Citation Detection: Named entity matching of philosophical figures
	•	Discourse Compass: A unified radar-style visual summarizing each subreddit’s communication style

🖼️ Visual Highlights
	•	TF-IDF heatmaps of distinctive terms
	•	Concept network graphs
	•	Emotion heatmaps
	•	Cited thinker emotional distance bar charts
	•	Subreddit radar plots
	•	Final Discourse Compass visualization

🚧 Limitations
	•	Results are time-bound to the scraped sample
	•	Citation detection relies on exact matching
	•	Emotional scoring is lexicon-based and may miss nuance

🧠 Final Insight

Reddit’s philosophy discourse is emotionally and intellectually fragmented in fascinating ways. Stoicism leans stoic (naturally), AskPhilosophy is curious and reflective, and TrueAskReddit is emotionally volatile and existential. Who subreddits cite, and how those figures emotionally align with the subreddit’s own tone, reveals a surprisingly rich map of the modern philosophical mind.
