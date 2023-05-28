# Deepgram to JSON
Deepgram supports word-by-word timestamps, but doesn’t support exporting them in the [Podcast Namespace JSON structure](https://github.com/Podcastindex-org/podcast-namespace/blob/main/transcripts/transcripts.md#json). This is a quick guide on how to do that.

## Quick Start
1. Clone deepgramtoJSON:
   ```sh
   # Clone deepgramtoJSON and navigate into it’s directory:
   git clone https://github.com/stenofm/deepgramtoJSON.git && cd deepgramtoJSON/
   ```
1. [Create a Deepgram account](https://console.deepgram.com/signup) and get an API key.
1. Replace `YOUR_SECRET` in `file.py` with your own Deepgram API Key.
1. Run file.py replacing the file and mimetype (optional) arguments:
   ```sh
   python --file @youraudiofile --mimetype @youraudiomimetype
   ```
