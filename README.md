# Raat Ki Kahani 🌙

A calm bedtime story maker for children. Enter the child's name, age, topic, lesson and language (Hindi, English or Hinglish) and get a gentle story, with a "Read aloud" button.

**Open-source AI at the core:** Google's open-weight **Gemma** model runs locally through **Ollama**. No internet, no account, no cost, and nothing about your child leaves your computer.

## Run it
1. Install Ollama: https://ollama.com/download
2. `ollama pull gemma3:1b`
3. Start Ollama with the page allowed:
   - Windows PowerShell: `Stop-Process -Name "ollama*" -Force; $env:OLLAMA_ORIGINS="*"; ollama serve`
   - Mac/Linux: `OLLAMA_ORIGINS="*" ollama serve`
4. Open `index.html` in Chrome (or the GitHub Pages link) and click **Tell me a story**.

Built for the Hacktoberfest Open-Source AI Challenge: Week 3 (theme: Slow and Steady), Oct 19-25, 2026. HTML, CSS, JavaScript, Gemma, Ollama.
