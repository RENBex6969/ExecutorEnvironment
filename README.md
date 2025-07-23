# Lua Virtual Machine (Sandbox)

A secure sandboxed environment for executing untrusted Lua/Luau code with controlled permissions.

## Features

- 🔒 **Restricted Environment**: Blocks dangerous functions (`os`, `io`, `loadstring`)
- 🛡️ **Safety Controls**: Prevents malicious code execution
- 🔧 **Custom APIs**: Modified standard libraries with extra utilities
- 📊 **Usage Tracking**: Monitors operations on undefined variables
- 🧪 **Executor Simulation**: Mock functions like `getgenv` (Roblox-style)

## Installation

```lua
-- Simply include the VM code in your project
local VM = require("lua_vm")
