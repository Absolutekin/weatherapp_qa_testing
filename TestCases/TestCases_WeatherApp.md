# 🌦️ WeatherApp Test Cases

This file contains the list of manual test cases created for **WeatherApp**.

---

## 🧪 Functional Test Cases

| Test Case ID | Test Scenario | Test Steps | Expected Result | Actual Result | Status |
|---------------|---------------|-------------|-----------------|----------------|---------|
| TC001 | Verify app launches successfully | 1. Open WeatherApp | App launches without crashing | Works as expected | Pass |
| TC002 | Verify current weather data loads | 1. Open app <br> 2. Allow location access | App displays current temperature, location, and condition | Works as expected | Pass |
| TC003 | Verify location permission request | 1. Open app <br> 2. Deny location access | App should display “Location permission required” message | Works as expected | Pass |
| TC004 | Verify search functionality | 1. Tap on search icon <br> 2. Enter “London” | Weather details for London should appear | Works as expected | Pass |
| TC005 | Verify temperature unit change | 1. Go to Settings <br> 2. Switch from °C to °F | Temperature should update to Fahrenheit | Works as expected | Pass |
| TC006 | Verify offline mode | 1. Turn off internet connection <br> 2. Open app | App should show “No internet connection” alert | Works as expected | Pass |
| TC007 | Verify refresh button functionality | 1. Pull down or tap refresh | Weather data should reload and update | Works as expected | Pass |

---

## 📱 UI Test Cases

| Test Case ID | Test Scenario | Test Steps | Expected Result | Actual Result | Status |
|---------------|---------------|-------------|-----------------|----------------|---------|
| TC008 | Verify app icon and splash screen | 1. Open app | Splash screen and logo should display correctly | Works as expected | Pass |
| TC009 | Verify temperature font and alignment | 1. Open app | Temperature text should be clearly visible and centered | Works as expected | Pass |
| TC010 | Verify light/dark mode toggle | 1. Change device theme | App UI should adjust accordingly | Works as expected | Pass |

---

## 🧩 Notes
- Device used: Redmi 12 Android 15 (Physical Device)  
- App Version: 1.0.0  
- Testing Type: Manual Functional Testing  
- Tester: **Sergio (Damilola Oludayo)**

---

✅ **Status Legend:**  
- **Pass** → Works as expected  
- **Fail** → Bug encountered  
- **Blocked** → Test cannot proceed due to dependency
