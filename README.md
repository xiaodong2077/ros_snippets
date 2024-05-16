# ROS1 snippets

VS Code extension with a collection of ROS1 snippets about roscpp, roslaunch and cmake.

## usage

Make sure you know [snippets of VS Code](https://code.visualstudio.com/docs/editor/userdefinedsnippets#_creating-your-own-snippets).

It currently support `cpp`, `xml`(.launch) and `cmake`(CMakelists.txt) languages.
Install this extension, you will see some snippets when you code with them.

### roslaunch

- `launch`
- `arg` with default
- `param` with value arg
- `node` name pkg type output respawn respawn_delay
- `rosparam` load yaml
- `include` include another luanch file
- `group`
- `remap`

### roscpp

- `rosnode`
- `rosinit`
- `rospublisher`
- `rossubscriber`
- `rossubcallback`
- `rosadservice`
- `rossercallback`
- `rosserclient`
- `rosratewhile`
- `rostimer`
- `rostimercallback`

### cmake

- `catkinincludedirs`
- `catkinlibraries`
- `catkinexportedtargets`
- `installroslib`
- `installrosnode`
- `installheaderfiles`
- `installlaunchfiles`

## license

[MIT](LICENSE)

## thanks

[ROS-Snippets](<https://github.com/SweiLz/ROS-Snippets>)
