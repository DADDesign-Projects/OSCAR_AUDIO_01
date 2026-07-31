# OSCAR Audio Board - OSCAR_AUDIO_01

![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)
![Hardware](https://img.shields.io/badge/hardware-PCB-green.svg)
![Audio](https://img.shields.io/badge/audio-DSP-orange.svg)
![KiCad](https://img.shields.io/badge/KiCad-9.0-blue.svg)

## 📋 Description

Dedicated electronic board implementing the audio section of the OSCAR effects pedal (https://github.com/DADDesign-Projects/OSCAR_P01A01). This board handles all digital and analog audio processing required for the pedal's operation.

## 🚀 Evolutions

### V2
- Modification of the output summing stage to restore phase alignment identical to the input signal

### V2.1 (PCB V2.2)
- Addition of a second relay to enable true hardware bypass

## 🛠️ Technical Specifications

### Audio Codec
- **PCM3060**: 24-bit stereo audio codec
- **ADC**: 2-channel, 24-bit resolution
- **DAC**: 2-channel, 24-bit resolution
- **Sampling Rate**: Up to 96 kHz

### Analog Dry Channel
- **PGA2310/PGA2311**: Stereo volume controller
- **Analog dry path** for unaffected signal
- **Independent wet/dry mix control**

### Power Supply
- **Isolated Power**: Separate analog and digital domains
- **Input Voltage**: 12V DC
- **Low Noise Regulation**: Multiple LDO regulators
- **Consumption**: < 150mA

## 🛠️ Design Tools
This project was entirely designed using **KiCad 10.0**, the open-source electronics design.

## 📜 License
This project is licensed under the **Apache License 2.0**.

# 📬 Contact
Feel free to contact me for any questions, feedback, improvement suggestions, or collaboration proposals related to the FORGE framework or the OSCAR hardware platform.
I am always open to discussion and community contributions (daddesign.projects@gmail.com).