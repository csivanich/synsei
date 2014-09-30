
#Synsave
Easily manage synaptics configurations, because who doesn't have a bunch lying around?

Author: Chris Sivanich - csivanich@gmail.com

###Usage
```
synsave <action> [arg1,arg2,...]
```

Actions

- ```help - Displays help page``` 
- ```edit <profile> - Edits a profile with $EDITOR``` 
- ```list - Lists all loadable profiles``` 
- ```load <profile> - Loads a profile into use``` 
- ```save <profile> - Saves the current config into a profile``` 
- ```view [profile] - Views a profile's config, otherwise views current synclient config```

###Examples
Save the current config to profile 'foo'
```
synsave save foo
```

Replace the current config with profile 'foo's
```
synsave load foo
```

more to come...
> Written with [StackEdit](https://stackedit.io/).