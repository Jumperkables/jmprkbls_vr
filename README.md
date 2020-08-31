# Jumperkables's VR Project
The VR project, be it dataset collection or otherwise, ran by Tom Winterbottom

## Steam games on VR compatible with Arch Linx
1. Follow the instructions of [this point](https://www.reddit.com/r/SteamPlay/comments/gbdiia/playing_regular_games_in_vr_works_on_linux_finally/)
    * Boot the game
    * Indetify the window ID of the game on desktop (xwininfo)
    * `vr-video-setup --flat <window_ID>`
## Unity Project Setup
1. `git clone https://github.com/Jumperkables/jmprkbls_vr.git`
2. Create a `lib` directory in the root repository. Inside of `lib`:
    * Clone the VRTK repo: `git clone https://github.com/ExtendRealityLtd/VRTK.git`
    * Download the [SteamVR plugin from GitHub](https://github.com/ValveSoftware/steamvr_unity_plugin/releases/download/1.2.3/SteamVR.Plugin.unitypackage)
    * Download and extract [this zip file](https://github.com/ExtendRealityLtd/VRTK/archive/master.zip)
