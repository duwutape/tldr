# top

> Display dynamic real-time information about running processes.
> More information: <https://manned.org/top>.

- Start `top`:

`top`

- Do not show any idle or zombie processes:

`top -i`

- Show only processes owned by given user:

`top -u {{username}}`

- Sort processes by a field:

`top -o {{field_name}}`

- Show the individual threads of a given process:

`top -Hp {{process_id}}`

- Show only the processes with the given PID(s), passed as a comma-separated list. (Normally you wouldn't know PIDs off hand. This example picks the PIDs from the process name):

`top -p $(pgrep -d ',' {{process_name}})`

- Display help about interactive commands:

`<?>`
