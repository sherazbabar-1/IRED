# IRED: A Indoor Risk Recognition Dataset

## Dataset and Code will be Available Soon.

## Overview

IRED is an indoor risk recognition dataset created for detecting safety-related indoor events and abnormal patterns from sensor data. It is designed to support researchers and developers working on indoor monitoring, anomaly detection, hazard recognition, and smart home safety systems.

The dataset contains sensor-driven event descriptions collected from indoor environments, annotated into risk categories such as unauthorized entry, fire or smoke events, gas leakage, falls, suspicious activity, and sensor faults.

---

## Sample Entries

| Sample ID | Event Description | Label ID | Class |
|---|---|---:|---|
| Sample_001 | midnight sensor readings from the main entrance over 5 minutes; door contact was closed; humidity was near 42.1%; PIR motion appeared for about 24 seconds; light level stayed close to 48.0 lux; gas reading was near 0.2. | 5 | Suspicious Activity/Noise |
| Sample_002 | dining area sensor stream during the afternoon for about 1 minute; gas reading was near 0.1; door contact was closed; vibration was around 0.2 g; PIR motion was detected for about 66 seconds; occupancy status was registered occupant present; one background reading shifted slightly; door contact was closed. | 0 | Normal Activity |
| Sample_003 | partially stable sensor record from the basement during the evening; gas reading was near 0.6; humidity was near 39.1%; sound level was near 53.0 dB; smoke reading was close to 0.2; CO was about 36.6 ppm; one background reading shifted slightly; vibration was around 0.0 g. | 3 | Gas Leakage |
| Sample_004 | during the midnight, the kitchen was monitored for nearly 1 minute; CO was about 69.3 ppm; gas reading was near 0.7; the pattern was not continuous; occupancy status was no occupant confirmed; smoke reading was close to 0.1; sound level was near 46.4 dB; light level stayed close to 159.7 lux. | 3 | Gas Leakage |
| Sample_005 | monitoring note from the staircase during the afternoon; PIR motion was not detected after event for about 3 seconds; door contact was open; sound level was near 60.0 dB; occupancy status was registered occupant present; light level stayed close to 0.0 lux; gas reading was near 0.1; a weak conflict appeared between nearby readings. | 4 | Fall/Impact Event |
| Sample_006 | the living room was observed during the morning for nearly 1 minute; sound level was near 39 dB; the pattern was not continuous; air-quality measurements stayed within a routine range; temperature was around 24 degrees Celsius; vibration was around 0 g; one sensor update was delayed; gas reading was near 0; PIR motion was intermittent for about 3 seconds. | 0 | Normal Activity |
| Sample_007 | noisy indoor sensor note from the main entrance over 1 minute; a weak conflict appeared between nearby measurements; PIR motion appeared for about 47 seconds; temperature remained around 25.7 degrees Celsius; CO was about 12.7 ppm; light level stayed close to 175.6 lux; occupancy status was no registered occupant; sound level was near 47.3 dB; occupancy status was no registered occupant. | 1 | Unauthorized Entry |
| Sample_008 | the storage room appeared observed during the evening for nearly 30 seconds; light level stayed close to 173.46 lux; PIR motion appeared for about 3 seconds; light level stayed close to 173.46 lux; door contact was open; temperature was around 24.67 degrees Celsius; gas reading was near 0.0. | 5 | Suspicious Activity/Noise |
| Sample_009 | noisy indoor sensor note from the hallway over 6 minutes; sound level was near 48.3 dB; temperature was around 20.4 degrees Celsius; occupancy status was no registered occupant; smoke reading was close to 0.1; PIR motion appeared for about 36 seconds; door contact was open; occupancy status was no registered occupant. | 1 | Unauthorized Entry |
| Sample_010 | IoT monitoring summary from the basement during a 2 minutes morning interval; temperature was around 65.2 degrees Celsius; vibration was around 0.1 g; a partial reading was unavailable; CO was about 26.6 ppm; occupancy status was registered occupant present; PIR motion was intermittent for about 26 seconds; smoke reading was close to 0.8. | 2 | Fire/Smoke Event |
| Sample_011 | during the afternoon, the staircase was monitored for nearly 3 minutes; temperature was around 18 degrees Celsius; the readings were not perfectly stable; CO was about 6 ppm; vibration was around 0 g; door contact was unchanged; occupancy status was unknown; the context was not fully clear from the available readings; sensor health was reported as stuck reading. | 6 | Sensor Fault/Anomaly |

---

## Label Taxonomy

| Label ID | Class Name |
|---|---|
| 0 | Normal Activity |
| 1 | Unauthorized Entry |
| 2 | Fire/Smoke Event |
| 3 | Gas Leakage |
| 4 | Fall/Impact Event |
| 5 | Suspicious Activity/Noise |
| 6 | Sensor Fault/Anomaly |

---

## Coming Soon

The full dataset, benchmark scripts, and documentation will be released in a future update.
