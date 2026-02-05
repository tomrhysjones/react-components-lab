# React Components Lab – Weather Forecast

## Overview
In this lab, you build a weather forecast page that **re-uses a single React component** to display multiple days’ worth of weather forecasts. The goal is to practice component reuse, props, and dynamically generating content in React.

Only two components are required:
- `src/App.jsx`
- `src/components/WeatherForecast/WeatherForecast.jsx`

`App` acts as the root component, while `WeatherForecast` is used inside `App` to generate a list of forecasts.

---

## Component Hierarchy



---

## Weather Data
Weather data is defined in `App.jsx` as an array of objects. Each object contains:
- `day`
- `img`
- `imgAlt`
- `conditions`
- `time`

The data is mapped over to render multiple `WeatherForecast` components.

---

## JSX Structure
Each `WeatherForecast` component renders the JSX equivalent of the following structure:

## Screenshots

Screenshot 2026-02-05 at 06.46.22