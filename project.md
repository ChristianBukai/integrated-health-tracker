# Integrated Health and Lifestyle Tracker

## Problem

People who track glucose, nutrition, exercise, and daily habits often use separate applications, making it difficult to review these activities together and understand their daily patterns.

## Target Users

The primary user is an individual who wants to combine historical glucose records with nutrition, exercise, hydration, sleep, and other daily health habits in one mobile application.

## MVP (Minimum Viable Product)

The MVP is a mobile application that combines historical glucose data with manually logged health and lifestyle information in a unified daily timeline.

The initial version will include:

- **Daily dashboard:** A chronological view of glucose readings, meals, insulin events, exercise, and other logged activities.
- **Glucose history:** A graph of imported historical glucose readings, with timestamps and data freshness clearly indicated.
- **Nutrition tracking:** Manual meal entry, macronutrient tracking, selected micronutrients, saved food presets, and configurable daily targets.
- **Lifestyle tracking:** Logging of insulin events, exercise, water intake, sleep duration, body weight, and supplements.
- **Daily review:** Progress toward personal targets and daily, weekly, and monthly summaries.
- **Reminders:** Simple configurable reminders for water intake and meal logging.

Automatic glucose data import through Apple Health (HealthKit) will be investigated early in development. Its feasibility must be verified before it is treated as a completed feature.

## Non-Goals

The first version will not:

- Replace the Dexcom G6 application or provide real-time glucose monitoring and alerts.
- Recommend insulin doses or make treatment decisions.
- Predict glucose levels or provide automated medical advice.
- Include AI-based food recognition, barcode scanning, or a comprehensive food database.
- Integrate automatically with every fitness, sleep, or health platform.
- Support multiple user accounts or social features.
- Include advanced AI-generated health recommendations.

These exclusions keep the MVP focused on reliable logging, data integration, visualization, and personal review.

## Technologies

The technology stack will be finalized after a technical feasibility check.

- **Target platform:** iOS mobile application.
- **Mobile development:** FlutterFlow is the initial candidate, subject to validating the required iOS capabilities.
- **Health data integration:** Apple HealthKit, subject to verifying access to the required glucose records.
- **Data storage:** A suitable local or cloud-based storage solution for logged activities, nutrition, and historical records.
- **AI-assisted development:** AI tools for planning, generating, modifying, and debugging the application.
- **Version control:** Git and GitHub for source control, documentation, and project history.

The selected technologies should keep development manageable, minimize initial costs, and support the MVP requirements.

## Success Criteria

The MVP will be considered successful when:

1. The main dashboard displays a chronological daily timeline.
2. Meals, insulin events, and lifestyle activities can be logged and reviewed.
3. Nutrition totals and progress toward personal targets are calculated correctly.
4. Historical glucose readings can be imported and displayed, provided the HealthKit feasibility check confirms access.
5. Historical records remain available after closing and reopening the application.
6. Basic reminders work as configured.
7. The application can be demonstrated on an iPhone.

## Future Extensions

Potential extensions include food database integration, automatic activity and sleep imports, data export, and more advanced historical analysis. These features are outside the initial MVP.
