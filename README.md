# service_status

This is a repository for checking the status of microservices

## How it works

The process is simple:

* A GitHub action should be triggered on every 15th minute of every hour.

* After checking, the script sends an action via webhook to Discord, where the messages of the final status are shown in their respectable channel.

***Updated 16/8/2023***
