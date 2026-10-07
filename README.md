# VoltSaver: Smart Home Energy Monitoring and Standby Power Reduction

A Grade 10 school project designed to monitor electricity usage in homes and detect unnecessary power consumption when appliances are left in standby mode.

## Project Overview
VoltSaver is a prototype system that helps reduce wasted electricity by tracking the power used by household appliances and identifying cases where appliances still consume electricity even when they appear to be switched off. The system can alert the user and disconnect power to avoid unnecessary energy loss.

This repository currently contains the project documentation and project overview. It does not yet include a completed ESP32 code file, dashboard implementation, or final hardware wiring files. Those parts are described in this report as a prototype plan and should be completed later with actual hardware testing.

## Project Goal
To create a simple, low-voltage prototype that demonstrates how smart monitoring can reduce standby power waste and help save energy.

## Key Idea
Many appliances such as TVs, set-top boxes, chargers, routers, and printers continue to consume a small amount of electricity even when they seem to be off. This is called standby power consumption. Although the amount is small for each device, it adds up over time and contributes to higher electricity bills and unnecessary pollution.

## Important Safety Note
This project is a low-voltage prototype only. It is not meant to be connected directly to household mains electricity (230V AC in many countries). Real mains wiring must only be handled by trained professionals using proper insulation, fuse protection, and safety-rated components.

## Report
- Project report: [PROJECT_REPORT.md](PROJECT_REPORT.md)

## Repository Contents
- `README.md` – project overview and summary
- `PROJECT_REPORT.md` – complete project report
- `.gitignore` – standard repository ignore rules
- `LICENSE` – repository license

## Suggested Future Work
- Add ESP32 firmware for sensor monitoring
- Connect to a dashboard or mobile app
- Use real current sensors and relay modules
- Test the prototype on a low-voltage bench setup
- Create a final, school-ready presentation
