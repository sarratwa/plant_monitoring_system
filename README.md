# Plant Monitoring System

## Proof of Concept
The first prototype focuses on detecting dry soil and alerting the user with a blinking blue LED. This confirms that the Arduino can read sensor values and react to threshold-based conditions.

## Requirements

### Functional Requirements
- The system will read soil moisture values.
- The system will alert the user when the soil is too dry.
- The system will show sensor status using LEDs.
- The system will display sensor data on a small display.
- The system will support a reset button.

## Hardware Overview
- Arduino UNO mit Kabel
- Soil moisture sensor
- small display
- 3 color leds
- resistors
- connecting cables
- temperature and humidity sensor
- reset button

## Pin Mapping

## Testing
| Test Case | Input/Condition | Expected Result |
|---|---|---|
| Dry soil detected | Low moisture reading | Blue LED blinks |
| Normal soil detected | Moisture within range | Green LED turns on |
| Critical dry soil | Very low moisture | Red LED turns on |
| Reset button pressed | Button input detected | System resets status |
| Sensor disconnected | Invalid reading | Error state is shown |

## Future Improvements
- Replace LED-only alerts with Wi-Fi-based notifications.
- Add log history for sensor readings.
- Make thresholds configurable depending on plant type.