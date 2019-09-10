# electricui-plugin-autoconnect

Import the plugin, it accepts a list of metadata objects to check for. If a
device matches, it adds a `ui` usage request automatically.

```
import { AutoConnectPlugin } from '@electricui/plugin-autoconnect'

const autoConnectPlugin = new AutoConnectPlugin([
  { type: 'Camera' },
])

deviceManager.addPlugins([actionsPlugin, autoConnectPlugin])
```
