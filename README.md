# Download VisionWorks-1.6-Samples
```
git clone https://github.com/jugfk/VisionWorks-1.6-Samples.git
cd VisionWorks-1.6-Samples
unzip 3rdparty.zip
unzip nvxio.zip
cd VisionWorks-1.6-Samples
cd bin/aarch64/linux/release
sudo chmod 777 *
```

# Excute with USB-Camera
```
./nvx_demo_feature_tracker --source="device:///v4l2?index=0"
./nvx_demo_feature_tracker_nvxcu --source="device:///v4l2?index=0"
./nvx_demo_hough_transform --source="device:///v4l2?index=0"
./nvx_demo_motion_estimation --source="device:///v4l2?index=0"
./nvx_demo_stereo_matching --source="device:///v4l2?index=0"
./nvx_demo_video_stabilizer --source="device:///v4l2?index=0"
./nvx_sample_object_tracker_nvxcu --source="device:///v4l2?index=0"
./nvx_sample_opengl_interop --source="device:///v4l2?index=0"
./nvx_sample_player --source="device:///v4l2?index=0"
```
