```bash
echo "deb [trusted=yes] https://github.com/christian-rauch/mmf-ros-deb-builder/raw/jammy-humble/ ./" | sudo tee /etc/apt/sources.list.d/christian-rauch_mmf-ros-deb-builder.list
echo "yaml https://github.com/christian-rauch/mmf-ros-deb-builder/raw/jammy-humble/local.yaml humble" | sudo tee /etc/ros/rosdep/sources.list.d/1-christian-rauch_mmf-ros-deb-builder.list
```
