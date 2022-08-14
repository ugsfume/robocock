# 🦚 Robocock

Project Robocock is a versatile fully automated high-resolution interior photogrammetry solution.

The system will utilise [SLAM](https://www.notion.so/About-caf9711042f84a92b1a0a05f0bd871f7), an [omni wheel system](https://en.wikipedia.org/wiki/Omni_wheel), and a custom path planning algorithm to provide a moving platform to mount cameras on, of which will be connected to the onboard computer to automatically acquire images for [photogrammetry](https://www.notion.so/About-caf9711042f84a92b1a0a05f0bd871f7) while traversing the interior space.

For the field of 3D capture, this tool will be a valuable replacement to [mainstream ground-based LIDAR scanning](https://en.wikipedia.org/wiki/Lidar#Surveying), which captures geometry well, but not so much on model texture detail important for model visualization; or drone photogrammetry, since it may be impractical to fly drones in interior spaces. 

Moreover, in the recent rise in [neural radiance field research](https://www.matthewtancik.com/nerf), the dense image datasets our automation captures may also be increasingly useful.

## Roadmap
- [x]  Assemble frame
- [ ]  Install motors and wheels
- [ ]  Assemble electronics to drive wheels
- [ ]  Add sensors to frame
- [ ]  Path planning
- [ ]  Photogrammetry integration
