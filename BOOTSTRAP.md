\[exec\_policy]

mode = "full"

allowed\_commands = \[

&#x20;   "systemctl",

&#x20;   "journalctl",

&#x20;   "bash",

&#x20;   "sh"

]

safe\_bins = \[

&#x20;   "systemctl",

&#x20;   "journalctl",

&#x20;   "bash",

&#x20;   "sh"

]



\[exec\_policy]

mode = "Allowlist"

safe\_bins = \["systemctl"]



