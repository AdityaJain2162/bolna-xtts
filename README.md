Place XTTS models in the home directory ./XTTS/<model here>
https://huggingface.co/coqui/XTTS-v2/tree/main

Sample input for websocket request

{
    "text" : "Ensure the environment variables TTS_WS and TTS_API_URL are correctly set in your .env file or environment.",
    "language" : "en",
    "voice" : "rohan",
    "model" : "xtts"
}
