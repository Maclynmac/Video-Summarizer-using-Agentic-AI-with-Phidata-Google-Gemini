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
<li>Language Support As noted, transcript retrieval supports multiple languages. Summarization prompt can potentially be adapted for different languages (depending on Gemini’s capabilities).
</li>
<li>Structured Summary Output:Summary is not just free-form: it is structured into meaningful chunks, such as introduction, main points, takeaways. Optionally, include detailed notes or bullet-point style key insights.</li>
<li>User Interface (UI):Built with Streamlit, providing a simple web-app UI where the user can: input a YouTube link, trigger summarization, and see results.  The app shows the video thumbnail once the link is input. Real-time / interactive: users can paste a link, click, and wait for summary.</li>

</ul>
