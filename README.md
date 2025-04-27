a command that can exute a command in a specific time with config
Config: 

# Interval in minutes between automatic executions. Set to 0 to disable.
intervalMinutes: 10

# List of specific times (24h format HH:mm) at which to run the command daily. Empty list to disable.
specificTimes:
  - "12:00"
  - "18:30"

# The command to execute (without leading slash)
command: "say Hello, Minecraft world!"

