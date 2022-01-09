---
name: Anwar
about: I'm using ESP 32 DevKit, Mini OBD-II as shown in this link (https://www.tokopedia.com/tokodibandung/super-mini-elm327-bluetooth-obd2-v2-1-automotive-test-tool-blue?whid =0), For the code I only use example ESP32_bluetoothserial and ESP32_test, Actually I use OBD-II to the DLC socket (Data Link Connector) of a motorcycle that already uses OBD-II. The motorcycle I use is Honda Vario (2021). The Mini OBD-II I'm using works fine if I plug it into the "Torque" app. But when I try to connect to the ESP 32 it can't connect. I see on serial monitor it only says "Couldn't connect to OBD scanner - Phase 1". I tried to change the baudrate from 115200 to 38400 also the same. I've also uncommented //SerialBT.setPin, nothing has changed. Can you provide a solution for my problem?

title: 'ELM327 not Connect to ESP32'
labels: question
assignees: PowerBroker2

---


