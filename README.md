Task 7 – Monitor System Resources Using Netdata
Objective

Install and run Netdata to visualize system and application performance metrics in real time.

Tools Used

Netdata – An open-source, real-time monitoring tool.

Docker – To run Netdata in a container without installing it directly on the host.

Steps Followed

Pulled and ran the Netdata container using Docker.

Mapped port 19999 so the Netdata web dashboard could be accessed from the browser.

Granted necessary permissions to allow Netdata to read system metrics from the host machine.

Opened a browser and visited http://localhost:19999 to access the dashboard.

Verified that live system metrics such as CPU, RAM, disk, and network usage were displayed.

Features Observed in Netdata Dashboard

CPU usage overall and per core.

Memory usage details.

Disk read/write statistics.

Network traffic in and out.

Docker container resource usage.

Alerts and notifications for unusual activity.

Deliverable

A screenshot of the Netdata dashboard showing real-time system metrics.

Why Use Netdata?

Netdata provides more detailed and historical system monitoring compared to built-in tools like Task Manager. It allows storing past performance data, viewing per-process and per-container statistics, and even setting up remote monitoring and alerts.
