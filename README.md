# Ramadan 2026 Tracker Dashboard

This Power BI dashboard tracks prayers, Quran reading, Athkar, tasks, work hours, holidays, and employee performance during Ramadan 2026.

## Features

- **Prayer & Fasting Tracker**: Shows next prayer, remaining time, and fasting hours.
- **Quran Reading Progress**: Displays total pages, daily target, actual pages, and reading trends over time.
- **Athkar**: Daily spiritual reminders.
- **Work & Task Management**: Monitors tasks, work hours, and performance.
- **Holidays & Ramadan Calendar**: Gantt chart of holidays, Ramadan workdays, and durations.
- **Mosque Map**: Displays nearest mosques with popularity & expected crowding based on reviews.

## Preview

![Ramadan Dashboard](./RamadanD.png)

## Tech Stack

- Power BI Desktop
- SharePoint / API Integration (Athkar, Mosques)
- DAX Measures & Power Query Transformations

## Sources
All data used is public and integrated using APIs:

[AlAdhan Prayer Times API](https://aladhan.com/prayer-times-api#get-/calendar/from/-start-/to/-end-)

[Azkar API](https://github.com/wdalgrb/azkar-api/blob/main/azkar.json)

[Google Maps API via SerpApi](https://serpapi.com/google-maps-api)

[AlQuran Cloud API](https://alquran.cloud/api)
