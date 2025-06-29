# 🎧 Voice & Music Separation in MATLAB

**Separate vocals and instrumentals from any audio file using classic digital signal processing techniques in MATLAB.**

This project applies IIR filter-based frequency isolation to cleanly separate human voice from musical background in a mono-converted audio stream. Featuring a user-friendly GUI for visualization and playback, it offers an accessible foundation for audio engineering tasks such as karaoke track generation, remixing, or speech preprocessing.

---

## 🚀 Key Features

✅ Vocal and instrumental separation using bandpass and bandstop IIR filters
✅ Time-domain waveform visualization
✅ Frequency spectrum (FFT) analysis
✅ Spectrograms for time-frequency representation
✅ Interactive GUI with Play, Pause, Resume controls
✅ Filtered audio automatically saved to `.wav` files

---

## 📌 Processing Flow

  ![Flow](https://github.com/user-attachments/assets/e3fac5fe-a50b-4054-bd6f-1b4de759c73c)

---

## 🛠️ Tools & Dependencies

* MATLAB Online
* MATLAB Signal Processing Toolbox

---

## 📂 Project Directory

```plaintext
voice-music-separation/
│
├── README.md
├── Flow.png
├── project.m
├── vocals_extracted.wav
└── instrumental_extracted.wav

```

## 💻 How it Works

1. **Audio Input**: Load a user-specified `.wav` file
2. **Mono Conversion**: Converts stereo signals to mono for simplified filtering
3. **Filter Design**:

   * Bandpass IIR filter for voice (300–3400 Hz)
   * Bandstop IIR filter for music background
4. **Zero-Phase Filtering**: Uses `filtfilt()` to preserve signal phase
5. **Visualization**:

   * Waveform plots
   * FFT frequency spectra
   * Spectrogram views
   * Filter frequency responses
6. **GUI**: Enables interactive playback with status indicators
7. **Output**: Saves separated vocals and instrumentals to `.wav` files

---

## 📊 Visual Results

✅ Clear waveform separation of vocal vs. instrumental components
✅ Spectrograms highlighting time-varying frequency content
✅ GUI-controlled playback for user interaction
✅ Filter response plots confirming effective frequency isolation

---

## 📝 Conclusion

This project demonstrates the power of classical DSP methods for practical source separation. It serves as a solid platform for exploring more advanced solutions, including adaptive filtering or machine learning-based enhancement, which can benefit applications such as speech recognition, karaoke generation, and audio restoration.

---

## 📎 Getting Started

1. Clone or download this repository
2. Open `project.m` in MATLAB Online
3. Run the script
4. Use the provided GUI to play, pause, or save the outputs

---

## 💻 Screen Recorder

  [Uploading Voice and Music Separation using MATLAB.mp4…](https://github.com/user-attachments/assets/ec194405-a764-4f7f-8467-64864a7af43c)

---
## 🤝 Contributing

Interested in expanding this project with modern source separation approaches, such as deep neural networks or adaptive filter banks? Contributions are highly welcome! Please open an issue or submit a pull request to collaborate.
