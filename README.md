
#Synsei
Easily manage synaptics configurations, because who doesn't have a bunch lying around?

Author: Chris Sivanich - csivanich@gmail.com

###Usage
```
synsei <action> [arg1,arg2,...]
```

Actions

- ```delete <profile> - Deletes a profile```
- ```edit <profile> - Edits a profile with $EDITOR```
- ```help - Displays help page```
- ```list - Lists all loadable profiles```
- ```load <profile> - Loads a profile into use```
- ```save <profile> - Saves the current config into a profile```
- ```view [profile] - Views a profile's config, otherwise views current synclient config```

###Examples

Edit the profile 'foo' with `vim -- `
```bash
synsei edit foo vim --
```

Save the current config to profile 'foo'
```bash
synsei save foo
```

Replace the current config with profile 'foo's
```bash
synsei load foo
```

Delete profile 'foo'
```bash
synsei delete foo
```

> Written with [StackEdit](https://stackedit.io/).
