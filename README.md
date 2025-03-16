# AdvancedInformation

AdvancedInformation is a Teamspeak client plugin that extends the visible data in info frames with useful information. It includes data for server frames, channel frames and client frames.

## Features
- Visible VirtualserverID and connected Queries in a server info frame
- Visible ChannelID in a channel info frame
- Visible ClientID and UniqueID in a client info frame

## Installation & Execution
### Requirements
- Teamspeak 3 Client 3.6.2
- CMake 3.30

### Build process
```bash
  cmake .
  
  cmake --build .
  ```

### Execution
1. Move 'AdvancedInformation.dll' into your Teamspeak plugins directory
2. Create a folder named 'AdvancedInformation' in the plugins directory
3. Move all images from 'src/icons/' into the created 'AdvancedInformation' directory
4. Start your Teamspeak client and enable the plugin with the 'Plugins' button

## Controls
| Button         | Description              |
|----------------|--------------------------|
| Enable Plugin  | Display more information |
| Disable Plugin | Display less information |

- Buttons can be accessed by clicking on the 'Plugins' button on the top bar
