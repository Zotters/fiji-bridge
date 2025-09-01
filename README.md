```lua     ▄▄▄▄▄▄▄▄▄▄▄  ▄▄▄▄▄▄▄▄▄▄▄  ▄▄▄▄▄▄▄▄▄▄▄  ▄▄▄▄▄▄▄▄▄▄▄                    
          ▐░░░░░░░░░░░▌▐░░░░░░░░░░░▌▐░░░░░░░░░░░▌▐░░░░░░░░░░░▌                   
          ▐░█▀▀▀▀▀▀▀▀▀  ▀▀▀▀█░█▀▀▀▀  ▀▀▀▀▀█░█▀▀▀  ▀▀▀▀█░█▀▀▀▀                    
          ▐░▌               ▐░▌           ▐░▌         ▐░▌                        
          ▐░█▄▄▄▄▄▄▄▄▄      ▐░▌           ▐░▌         ▐░▌                        
          ▐░░░░░░░░░░░▌     ▐░▌           ▐░▌         ▐░▌                        
          ▐░█▀▀▀▀▀▀▀▀▀      ▐░▌           ▐░▌         ▐░▌                        
          ▐░▌               ▐░▌           ▐░▌         ▐░▌                        
          ▐░▌           ▄▄▄▄█░█▄▄▄▄  ▄▄▄▄▄█░▌     ▄▄▄▄█░█▄▄▄▄                    
          ▐░▌          ▐░░░░░░░░░░░▌▐░░░░░░░▌    ▐░░░░░░░░░░░▌                   
           ▀            ▀▀▀▀▀▀▀▀▀▀▀  ▀▀▀▀▀▀▀      ▀▀▀▀▀▀▀▀▀▀▀                    
                                                                                 
 ▄▄▄▄▄▄▄▄▄▄   ▄▄▄▄▄▄▄▄▄▄▄  ▄▄▄▄▄▄▄▄▄▄▄  ▄▄▄▄▄▄▄▄▄▄   ▄▄▄▄▄▄▄▄▄▄▄  ▄▄▄▄▄▄▄▄▄▄▄    
▐░░░░░░░░░░▌ ▐░░░░░░░░░░░▌▐░░░░░░░░░░░▌▐░░░░░░░░░░▌ ▐░░░░░░░░░░░▌▐░░░░░░░░░░░▌   
▐░█▀▀▀▀▀▀▀█░▌▐░█▀▀▀▀▀▀▀█░▌ ▀▀▀▀█░█▀▀▀▀ ▐░█▀▀▀▀▀▀▀█░▌▐░█▀▀▀▀▀▀▀▀▀ ▐░█▀▀▀▀▀▀▀▀▀    
▐░▌       ▐░▌▐░▌       ▐░▌     ▐░▌     ▐░▌       ▐░▌▐░▌          ▐░▌             
▐░█▄▄▄▄▄▄▄█░▌▐░█▄▄▄▄▄▄▄█░▌     ▐░▌     ▐░▌       ▐░▌▐░▌ ▄▄▄▄▄▄▄▄ ▐░█▄▄▄▄▄▄▄▄▄    
▐░░░░░░░░░░▌ ▐░░░░░░░░░░░▌     ▐░▌     ▐░▌       ▐░▌▐░▌▐░░░░░░░░▌▐░░░░░░░░░░░▌   
▐░█▀▀▀▀▀▀▀█░▌▐░█▀▀▀▀█░█▀▀      ▐░▌     ▐░▌       ▐░▌▐░▌ ▀▀▀▀▀▀█░▌▐░█▀▀▀▀▀▀▀▀▀    
▐░▌       ▐░▌▐░▌     ▐░▌       ▐░▌     ▐░▌       ▐░▌▐░▌       ▐░▌▐░▌             
▐░█▄▄▄▄▄▄▄█░▌▐░▌      ▐░▌  ▄▄▄▄█░█▄▄▄▄ ▐░█▄▄▄▄▄▄▄█░▌▐░█▄▄▄▄▄▄▄█░▌▐░█▄▄▄▄▄▄▄▄▄    
▐░░░░░░░░░░▌ ▐░▌       ▐░▌▐░░░░░░░░░░░▌▐░░░░░░░░░░▌ ▐░░░░░░░░░░░▌▐░░░░░░░░░░░▌  
 ▀▀▀▀▀▀▀▀▀▀   ▀         ▀  ▀▀▀▀▀▀▀▀▀▀▀  ▀▀▀▀▀▀▀▀▀▀   ▀▀▀▀▀▀▀▀▀▀▀  ▀▀▀▀▀▀▀▀▀▀▀  
                                    **V1.0.5**
                               *Written by Zotters*
                       **CONFIGURATION FOUND IN SETTINGS.LUA**```   

A universal framework bridge for FiveM that provides a unified API for working with different frameworks (ESX, QBCore, QBX), inventory systems, and target systems.

## Overview

Fiji Bridge is designed to make your scripts framework-agnostic and easily portable across different server setups. It automatically detects and adapts to the framework and systems running on your server, providing a consistent API regardless of the underlying implementation.

## Compatibility
*Frameworks: ESX, QBCore, QBX, standalone
*Inventory Systems: ox_inventory, qb-inventory, qs-inventory, ESX inventory
*Target Systems: ox_target, qb-target, qtarget
*FiveM Artifacts: Compatible with latest artifacts
*OneSync: Fully compatible with OneSync

## Features

### Core Features
- **Framework Auto-Detection**: Automatically detects and adapts to ESX, QBCore, or QBX
- **Inventory System Integration**: Supports ox_inventory, qb-inventory, qs-inventory, and ESX inventory
- **Target System Integration**: Supports ox_target, qb-target, and qtarget
- **Performance Optimized**: Caching system for improved performance
- **Debug System**: Comprehensive debugging with different log levels
- **Callback System**: Framework-agnostic callback implementation

### Technical Features
- **Caching**: Intelligent caching with TTL and size limits
- **Error Handling**: Robust error handling and fallbacks
- **Performance Monitoring**: Track function performance and execution times
- **Lazy Loading**: Load framework objects only when needed
- **Resource State Caching**: Avoid repeated native calls               

## Installation

1. Drag `fiji_bridge` in your server's resources directory
2. Configure in `settings.lua`
3. Add `ensure fiji_bridge` to your server.cfg (make sure it loads before resources that depend on it)
4. In resources that need the bridge, add `fiji_bridge` as a dependency in their fxmanifest.lua
5. Use the export as shown in the examples to access the bridge functions

## API

### Initilization
```lua
-- Get the bridge in your resource
local Fiji = exports['fiji_bridge']:GetFiji()

-- Initialize the bridge (automatically called when the resource starts)
Fiji.Init()
```

### Framework Functions
```lua
-- Get the detected framework ('esx', 'qb', 'standalone')
local framework = Fiji.GetFramework()

-- Get player identifier
local identifier = Fiji.GetIdentifier(source)
```

### Money Functions
```lua
-- Check if player has enough money
local hasEnough = Fiji.HasMoney(source, amount, account)
-- source: player server ID
-- amount: amount to check
-- account: 'cash', 'bank', etc. (default: 'cash')

-- Get player money amount
local money = Fiji.GetMoney(source, account)
-- source: player server ID
-- account: 'cash', 'bank', etc. (default: 'cash')

-- Add money to player
local success = Fiji.AddMoney(source, account, amount, reason)
-- source: player server ID
-- account: 'cash', 'bank', etc. (default: 'cash')
-- amount: amount to add
-- reason: reason for adding money (default: 'Money added')

-- Remove money from player
local success = Fiji.RemoveMoney(source, account, amount, reason)
-- source: player server ID
-- account: 'cash', 'bank', etc. (default: 'cash')
-- amount: amount to remove
-- reason: reason for removing money (default: 'Money removed')
```

### Inventory Functions
```lua
-- Check if player has an item
local hasItem, itemCount = Fiji.HasItem(source, item, amount)
-- source: player server ID
-- item: item name
-- amount: amount to check (default: 1)
-- returns: boolean success, number count

-- Add item to player inventory
local success = Fiji.AddItem(source, item, amount, metadata)
-- source: player server ID
-- item: item name
-- amount: amount to add (default: 1)
-- metadata: item metadata (optional)

-- Remove item from player inventory
local success = Fiji.RemoveItem(source, item, amount, metadata)
-- source: player server ID
-- item: item name
-- amount: amount to remove (default: 1)
-- metadata: item metadata (optional)

-- Get item label
local label = Fiji.GetItemLabel(item)
-- item: item name
```

### Target Systems
```lua
-- Add target box zone
local success = Fiji.AddTargetBoxZone(name, coords, size, rotation, options, debug)
-- name: unique zone name
-- coords: vector3 coordinates
-- size: vector3 size
-- rotation: rotation in degrees
-- options: table of interaction options
-- debug: show debug visuals (default: false)

-- Add target sphere zone
local success = Fiji.AddTargetSphereZone(name, coords, radius, options, debug)
-- name: unique zone name
-- coords: vector3 coordinates
-- radius: interaction radius
-- options: table of interaction options
-- debug: show debug visuals (default: false)

-- Remove target zone
local success = Fiji.RemoveTargetZone(name)
-- name: zone name to remove

-- Add target entity
local success = Fiji.AddTargetEntity(entity, options)
-- entity: entity handle
-- options: table of interaction options

-- Get target system
local targetSystem = Fiji.GetTargetSystem()
-- returns: 'ox', 'qb', 'qtarget', or 'none'
```

### Notifications
```lua
-- Send notification to player
Fiji.Notify(source, message, type, duration)
-- source: player server ID
-- message: notification message
-- type: notification type ('info', 'error', 'success', etc.)
-- duration: display duration in ms (default from settings)
```

### Progress Bars
```lua
-- Display progress bar
Fiji.ProgressBar(data, cb)
-- data: table with progress bar configuration
-- cb: callback function(success)

-- Example:
Fiji.ProgressBar({
    duration = 5000,
    label = 'Processing...',
    useWhileDead = false,
    canCancel = true,
    controlDisables = {
        disableMovement = true,
        disableCarMovement = true,
        disableMouse = false,
        disableCombat = true
    },
    animation = {
        animDict = "missheistdockssetup1clipboard@base",
        anim = "base"
    },
    prop = {
        model = `prop_notepad_01`,
        bone = 18905,
        coords = { x = 0.1, y = 0.02, z = 0.05 },
        rotation = { x = 10.0, y = 0.0, z = 0.0 }
    }
}, function(success)
    if success then
        print("Progress completed!")
    else
        print("Progress cancelled!")
    end
end)
```

### Callbacks
```lua
-- Server-side: Register callback
Fiji.RegisterCallback(name, cb)
-- name: callback name
-- cb: callback function(source, cb, ...)

-- Example:
Fiji.RegisterCallback('fiji:getPlayerData', function(source, cb)
    -- Get player data
    local data = {
        name = "John Doe",
        job = "police"
    }
    cb(data)
end)

-- Client-side: Trigger callback
Fiji.TriggerCallback(name, cb, ...)
-- name: callback name
-- cb: callback function(result)
-- ...: additional parameters

-- Example:
Fiji.TriggerCallback('fiji:getPlayerData', function(data)
    if data then
        print("Player name: " .. data.name)
    end
end)
```

### Utility
```lua
-- Reset cache
Fiji.ResetCache()

-- Get debug info
local debugInfo = Fiji.GetDebugInfo()
```

--- 
Made with ❤️ by Zotters
