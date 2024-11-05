# audio-arabic-review
<!-- <table>
  <tr>
    <th>Model Name</th>
    <th>Small Text</th>
    <th>Small Text with English Terms</th>
    <th>Large Text</th>
    <th>Large Text with English Terms</th>
    <th>Text with Tashkeel (تشكيل)</th>
    <th>Text without Tashkeel</th>
    <th>Upvote Score</th>
  </tr>
  <tr>
    <td>Fish-Speech-1</td>
    <td><audio controls><source src="audio-link-a-small.mp3" type="audio/mpeg"></audio></td>
    <td><audio controls><source src="audio-link-a-small-eng.mp3" type="audio/mpeg"></audio></td>
    <td><audio controls><source src="audio-link-a-large.mp3" type="audio/mpeg"></audio></td>
    <td><audio controls><source src="assets/fish1-speech/fish-speech1-total.wav" type="audio/wav"></audio></td>
    <td><audio controls><source src="audio-link-a-tashkeel.mp3" type="audio/mpeg"></audio></td>
    <td><audio controls><source src="audio-link-a-no-tashkeel.mp3" type="audio/mpeg"></audio></td>
    <td>
      <span id="score-a">0</span>
      <button onclick="upvote('score-a')">Upvote</button>
    </td>
  </tr>
 -->





<!-- # Project Documentation -->

## Datasets

| Dataset Name                                      | Description                                                                               | Link                                                                                                     |
|---------------------------------------------------|-------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------|
| ClArTTS                                           | Arabic Text-To-Speech (TTS) dataset, designed for expressive speech synthesis.            | [ClArTTS on Hugging Face](https://huggingface.co/datasets/MBZUAI/ClArTTS)                                |
| Shaip Arabic Speech Dataset                       | Arabic speech data collection for various speech recognition and synthesis applications.   | [Shaip Arabic Dataset](https://fi.shaip.com/offerings/speech-data-catalog/arabic-dataset/)               |
| European Language Grid Arabic TTS Dataset         | Dataset for Arabic Text-To-Speech synthesis, enabling high-quality audio generation.       | [European Language Grid Arabic Dataset](https://live.european-language-grid.eu/catalogue/tool-service/9390/download%2Frun/) |

## Models

| Model Name                        | Purpose                                 | Description                                                                                              |
|-----------------------------------|-----------------------------------------|----------------------------------------------------------------------------------------------------------|
| AutoPeftModelForCausalLM          | Text Generation                         | Pre-trained Llama-based model fine-tuned for Arabic sentiment analysis, stored in `./trained_weights/`.  |
| Sentiment Analysis Model          | Sentiment Classification                | Model trained to classify text sentiment using `label` and `text` columns in a Hugging Face dataset.      |
| Multimodal Text and Image Model   | Text and Image Processing Integration   | A model for integrating both text and image inputs, supporting the PALIGEMA project.                     |
| Anomaly Detection Model           | Security Monitoring                     | Identifies anomalies using continuous features such as login counts and device usage metrics.             |
| Activity Classification Model     | Office Activity Recognition             | Classifies activities like sitting, walking, and working based on vision inputs.                          |
| Object Detection Model            | Identity and Object Tracking            | Detects faces and associated objects from live camera feeds, designed for real-time monitoring.           |
| Computer Vision Pipeline          | End-to-End Vision Tasks                 | Comprehensive computer vision pipeline built to support various task-specific models.                     |
| React Countdown Game              | Interactive Game                        | Game model with three rounds (Letters, Numbers, Conundrum) and a scoring system, created for React.       |
| TTS Model for Arabic              | Text-To-Speech Generation               | Generates Arabic TTS audio, including handling of diacritics and English terms within Arabic sentences.   |


