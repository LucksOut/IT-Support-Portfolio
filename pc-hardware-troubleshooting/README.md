# PC Hardware Troubleshooting & System Diagnostics

## Project Overview

This project documents my hands-on experience assembling desktop computers, replacing hardware components, and troubleshooting system instability.

My goal was to identify potential hardware and software issues using a structured troubleshooting process.

## Technical Skills Demonstrated

- Desktop PC assembly and component installation
- Hardware replacement and compatibility checks
- Windows operating system troubleshooting
- Graphics driver installation and troubleshooting
- Windows Event Viewer analysis
- System stability testing
- Troubleshooting documentation

## System Configuration

One of the systems I worked on included:

| Component | Hardware |
|---|---|
| Processor | AMD Ryzen 5 7500F |
| Motherboard | ASRock A620I Lightning WiFi |
| Memory | 32GB DDR5 RAM |
| Graphics Card | Intel Arc B580 (original configuration) |
| Power Supply | Cooler Master V750 SFX Gold (original configuration) |
| Operating System | Windows |

## Troubleshooting Case Study: System Instability

### Problem

The computer experienced unexpected black screens and restarts during gaming and GPU stress testing.

### Troubleshooting Steps

1. Reviewed Windows Event Viewer and identified Kernel-Power Event ID 41.
2. Used GPU stress testing to investigate system instability.
3. Removed and reinstalled graphics drivers using Display Driver Uninstaller (DDU).
4. Tested different graphics cards to investigate potential GPU-related problems.
5. Replaced the power supply to investigate a possible power delivery issue.
6. Replaced the motherboard during the troubleshooting process.
7. Adjusted DDR5 memory speed to 5600 MT/s to improve stability.

### Findings

The troubleshooting process involved investigating several possible causes, including graphics drivers, power delivery, motherboard functionality, and memory stability.

Kernel-Power Event ID 41 indicated that Windows detected an unexpected shutdown or restart, but did not independently identify the root cause.

A definitive root cause was not established in this case study.

## Lessons Learned

- Follow a structured troubleshooting process instead of assuming the first suspected component is defective.
- Review system logs to gather evidence.
- Test one variable at a time whenever possible.
- Record hardware changes and testing results.
- Verify system stability before considering a problem resolved.

## Future Improvements

- Document benchmark and stress-test results.
- Capture Windows Event Viewer screenshots.
- Record before-and-after system configurations.
- Add confirmed resolutions for future troubleshooting cases.
