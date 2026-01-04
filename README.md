# LLM-to-Digital-Human Pipeline

A modular pipeline that turns text conversations into lifelike digital human videos by integrating:

- **LLM API** for conversational language generation  
- **GPT-SoVITS** for high-quality text-to-speech (TTS)  
- **MuseTalk** for lip-syncing audio to a talking avatar  

This project demonstrates an end-to-end workflow from user input → dialogue → speech → animated digital human video.

> ⚠️ **Note**: This repository only contains integration logic and glue code. It does **not** include the models or services themselves. All third-party components must be set up separately in accordance with their respective licenses.

## 🔧 Features

- End-to-end text-to-digital-human video generation  
- Configurable API keys and model paths  
- Modular design: easy to swap in alternative LLMs, TTS, or avatar engines  
- Example scripts for quick testing

---

## 📦 Dependencies

You'll need to install the following components **manually**, as they are not included in this repo:

1. **[GPT-SoVITS](https://github.com/RVC-Boss/GPT-SoVITS)**  
   - License: MIT  
   - Follow their instructions to set up the TTS inference environment.

2. **[MuseTalk](https://github.com/TMElyralab/MuseTalk)**  
   - License: Apache 2.0  
   - Clone and install per their official guide.

3. **DeepSeek API access**  
   - Sign up at [DeepSeek](https://platform.deepseek.com/) to get your API key.  
   - This project only calls the API via HTTP; no model weights are distributed.
