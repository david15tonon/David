# David
Hello this repo is for my personal roadmap. You'll find project about ML, DpL, RNN,BCI and LLM.




{
  "name": "ROS2 Humble Development",
  "image": "mcr.microsoft.com/devcontainers/base:ubuntu",
  "features": {
    "ghcr.io/devcontainers/features/docker-in-docker:1": {},
    "ghcr.io/devcontainers/features/common-utils:1": {}
  },
  "postCreateCommand": "sudo apt update && sudo apt install -y curl gnupg2 lsb-release && curl -sSL https://raw.githubusercontent.com/ros/rosdistro/master/ros.asc | sudo apt-key add - && sudo sh -c 'echo \"deb http://packages.ros.org/ros2/ubuntu $(lsb_release -cs) main\" > /etc/apt/sources.list.d/ros2-latest.list' && sudo apt update && sudo apt install -y ros-humble-desktop",
  "customizations": {
    "vscode": {
      "extensions": [
        "ms-iot.vscode-ros"
      ]
    }
  }

  
}
