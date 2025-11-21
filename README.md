<strong> Video Summarizer using Agentic AI with Phidata & Google Gemini </strong>

<strong>Features:</strong>

<ul>
  
<li>Transcript extraction: Using APIs like YouTubeTranscriptApi to pull subtitles or speech-to-text from YouTube videos. </li>
<li>Preprocessing: Clean up the transcript — remove noise, format text, handle long lengths. </li>
<li>Summarization prompt and model: Define a prompt template for the LLM to generate summaries (core theme, key points, tips, suggestions)</li>
<li>Chunking / handling long videos: If the transcript is very long, break into chunks before feeding into the LLM. (mentioned as a future enhancement) </li>
<li>Environment / API Key Management:Uses .env file / environment variables to store the Gemini API key securely. Dependencies / libraries managed via requirements.txt.</li>
<li>Scalability / Extensibility: Because it's modular: transcript extraction, chunking, summarization, UI are separate  you can swap LLM, or change summarization prompt.
Could be extended to support other LLMs (not just Gemini), or other front-ends (instead of Streamlit).</li>
</ul>
