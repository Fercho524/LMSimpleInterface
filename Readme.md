# AI LLM Loquendo

Using LLM Studio I made a test to create a simple chat interface with voice output using loquendo cli interface. I taste it with gemma because i need vram to put whisper and a tts model in future.


## Requirements

1. Install LM Studio https://lmstudio.ai/ download a model and load in your gpu.

2. Install conda, activate and create the enviroment

```sh
conda env create -f environment.yml
conda activate mltesting
```

3. Download loquendo and install in your machine, also you can install it on linux using wine, i did it. You can find tutorials on youtube, but ensure that you are downloading Loquendo TTS Director, this works for me.

4. Install balabolka cli, you can download it for free on the official website.https://www.cross-plus-a.com/es/bconsole.htm . Once it has been downloaded, unzip balcon.zip, and put into the project folder.

5. Run the jupyter notebook and enjoy :)

## Todo
- Add whisper, i need to buy a microphone, or make the lm studio global to use other devices.
- Make a better optimization to improve speed.