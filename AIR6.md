# AIR6 video feed

The `air6` branch starts from `92f51f0f3fffa718fc9d3717a5e852e8ddb2b1e7`, the video feed revision recorded for the previous AIR6 build. No video package source changes were needed for the initial source migration.

This branch is selected by `src-git video https://github.com/royzheng/openwrt-video.git;air6`. Record the actual commit in each build's `feeds.buildinfo`; the branch can advance independently of the parent workspace's submodule pointer.
