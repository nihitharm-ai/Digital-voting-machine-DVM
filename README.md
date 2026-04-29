# Digital-voting-machine-DVM
This project presents the design and construction of an Digital Voting Machine that prioritizes data integrity and security.  Our system utilizes an Arduino-based microcontroller integrated with lEEPROM. This integration ensures that every vote cast is recorded in a non-volatile format, making it resilient to power outages. 
1. ABSTRACT:
This project presents the design and construction of an Digital Voting Machine (DVM) that
prioritizes data integrity and security. Traditional voting methods often suffer from
logistical delays and potential data loss during power fluctuations. Our system utilizes an
Arduino-based micro-controller integrated with Electrically Erasable Programmable Read- Only Memory (EEPROM). This integration ensures that every vote cast is recorded in a non- volatile format, making it resilient to power outages. The system also incorporates digital
debouncing algorithms to prevent mechanical switch errors and provides a user-friendly
interface via an I2C Liquid Crystal Display (LCD). The core of the design focuses on three technical pillars:
 Data Persistence: By utilizing EEPROM, the system ensures that vote counts are saved
in real-time. This non-volatile storage prevents data loss during unexpected power
failures, as the memory retains information without a power source.  Input Accuracy: The inclusion of digital debouncing algorithms filters out "noise" from
mechanical switches, ensuring that each physical button press is registered as exactly
one vote, eliminating errors caused by contact bounce.  User Interface: An I2C LCD provides a streamlined interface for voters and officials, simplifying the hardware wiring while offering clear, real-time feedback on the voting
process. Essentially, the system transforms a manual logistical challenge into a precise, automated
process that prioritizes resilience and integrity.
