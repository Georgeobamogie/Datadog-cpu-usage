# Datadog-cpu-usage

firstly, the Datadog client will be initialized with the api_key and app_key obtained from your Datadog account. Then, the function get_cpu_usage retrieves the current system's CPU usage by reading the /proc/stat file. Finally, the CPU usage is sent to Datadog as a metric named system.cpu.usage at an interval of 60 seconds.
