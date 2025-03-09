# Text_to_Speech
Building Text to Speech pipeline using pre-trained Tacotron2 in torchaudio.
1. Text preprocessing.
- The input text is encoded into a list of symbols. We will use Enhlish characters and phenomes as the symbols.

2. Spectrogram generation.
- From the encoded text, a spetrogram is generated.

3. Time-domain conversion.
- The last step is the spectrogram into the waveform. The process to generate speech from spectrogram is also called a Vocoder. There are three different vocoders: WaveRNN, GriffinLim and Nvidia's WaveGlow
