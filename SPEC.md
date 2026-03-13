# Pomodoro Timer CLI Tool

### Goal
Create an easy to use, cross-platform CLI Pomodoro timer in Rust to help improve productivity while also learning the basics of CLI too 

---

### Commands Supported
- `pomodoro start` -> Starts a 25-minute focus session with sound notification upon completion
- `pomodoro break` -> Starts a 5-minute short break with sound notification
- `pomodoro long-break` -> Starts a 30-minute long break with sound notification
- `pomodoro status` -> Displays the amount of time remaining in the current session

---

### Timing
- Focus Session: 25 minutes (default)
- Short Break: 5 minutes
- Long Break: 30 minutes

---

### Notifications
- Terminal bell (`\x07`) at the end of each session

---

### Future Enhancements
- Persist session history
- Pause/resume functionality
- Configurable Pomodoro/break lengths
- Custom notification sounds
- Desktop notification pop ups
- More CLI Options:
  - `--minutes <n>` : Override default timer duration
  - `--sound <file>` : Play a custom sound file
  - `--silent` : Disable notifications
