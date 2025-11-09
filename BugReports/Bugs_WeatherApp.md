# 🐞 WeatherApp Bug Reports

This document contains the list of bugs found during manual testing of **WeatherApp**.

---

## ⚠️ Report Summary

| Bug ID | Title | Description | Steps to Reproduce | Expected Result | Actual Result | Severity | Status |
|--------|--------|--------------|-------------------|----------------|----------------|-----------|---------|
| BUG001 | Search not returning results | When searching for a city, no result is displayed even when the city exists | 1. Launch app <br> 2. Tap search icon <br> 3. Type “London” <br> 4. Tap enter | Weather details for “London” should display | No result found | High | Open |
| BUG002 | Incorrect temperature unit conversion | Changing temperature unit from °C to °F displays wrong values | 1. Go to settings <br> 2. Change °C → °F | Values should convert correctly | Displays inconsistent readings | Medium | Open |
| BUG003 | App crashes on refresh | App crashes when user taps refresh button multiple times | 1. Open app <br> 2. Rapidly tap refresh | App should refresh normally | App closes unexpectedly | Critical | Fixed |
| BUG004 | Dark mode text visibility issue | Text becomes invisible in dark mode | 1. Switch device to dark theme <br> 2. Open app | Text should adapt to dark background | Text not visible | Low | Open |
| BUG005 | “No Internet” alert not dismissing | Alert stays on screen even after reconnection | 1. Turn off internet <br> 2. Turn back on <br> 3. Open app | Alert should disappear once internet is back | Alert remains stuck | Medium | Open |

---

## 🧩 Bug Details
- **Test Environment:** Android 13 (Real Device)  
- **App Version:** 1.0.0  
- **Test Type:** Functional & UI Testing  
- **Tester:** Sergio (Damilola Oludayo)

---

✅ **Severity Legend:**  
- **Critical:** App crash or major feature broken  
- **High:** Major functionality issue  
- **Medium:** Moderate issue affecting usability  
- **Low:** Minor UI or text issue
