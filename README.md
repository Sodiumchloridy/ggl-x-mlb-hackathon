<div align="center">
  <div>
    <h1 style="display: inline-block;">Melby-sama</h1>
  </div>
  <p align='center'>
  Melby-sama (MLB... Melby... get it?), an AI MLB VTuber and streamer powered by Google's Multimodal AI — the segue to our sponsor: the Google Cloud x MLB Hackathon, powered by Gemini!
</p>

[![forthebadge](https://forthebadge.com/images/featured/featured-built-with-love.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/featured/featured-powered-by-electricity.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/featured/featured-gluten-free.svg)](https://forthebadge.com)

[![forthebadge](https://forthebadge.com/images/badges/ctrl-c-ctrl-v.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/works-on-my-machine.svg)](https://forthebadge.com)

</div>

## 1. Install Dependencies

### 1. Install Poetry

You can install Poetry by following the official [installation guide](https://python-poetry.org/docs/#installation).

```bash
pip install poetry
poetry config virtualenvs.in-project true # to create the virtual environment in the project directory
```

### 2. Setup the environment variables

Create a `.env` file at the root of the project with the following variables:

```env
GEMINI_API_KEY=
SPEECH_KEY=
SPEECH_REGION=
```

You can get your own `GEMINI_API_KEY` at [Google AI Studio](https://aistudio.google.com/app/apikey).

You can get the `SPEECH_KEY` and `SPEECH_REGION` by following the steps below:

1. Sign up for an Azure free account at [https://azure.microsoft.com/free/cognitive-services](https://azure.microsoft.com/free/cognitive-services).
2. [Create a Speech Services resource](https://portal.azure.com/#create/Microsoft.CognitiveServicesSpeechServices) in the Azure Portal.
3. Get the `SPEECH_KEY` and `SPEECH_REGION` from the resource.

### 3. Run the project

At the root of the project, run:

```bash
poetry run python src/main.py
```
