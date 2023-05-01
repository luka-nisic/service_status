# service_status

This is a repository for checking the status of microservices

## How it works

Github action should trigger on a 5 minute interval, using "on schedule" event, and it's checking the state of all microservices.

After checking, the script sends an action via webhook to Discord, where the messages of the final status are showed in their respectable channel.
