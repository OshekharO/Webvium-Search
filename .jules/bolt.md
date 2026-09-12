## 2026-04-04 - Precise Timer Scheduling for Clocks
**Learning:** Clocks showing HH:MM do not need a 1000ms `setInterval`. Calculating the delay to the start of the next minute and scheduling via `setTimeout` reduces timer executions by 98.3% and prevents main thread wakeups when the tab is hidden via Page Visibility API.
**Action:** Replace fixed 1-second interval clocks with minute-aligned `setTimeout` and `visibilitychange` listeners in lightweight web pages.
