CONTRIBUTING for GAAS

# Roadmap

Our goal is to accelerate the implementation of autonomous flight, including in the widely used Unmanned Aerial Vehicles (UAV), and the passenger-carrying aerial vehicles. 

The primary objective of the project is to provide an easy-to-use and stable autonomous flight solution. The solution contains both software and hardware components.

The software component contains modules for autonomous flight, such as flight control, Simultaneous Localization and Mapping, Obstacle Avoidance, Navigation, support for upper layers, and flight simulation.

The hardware component contains a budget-friendly drone construction plan, the onboard processing unit, and sensors with complementary configuration documentation.

Communication between modules in the software is based on ROS. Each module can be replaced if needed. While replacing modules, the new module must have the same corresponding ROS topic/service pub sub. The project has provided a considerably more stable, but less optimized implementation. We look forward to working with developers around the world to improve the overall project.

我们的目标是加速飞行器全自动驾驶的广泛应用。这里的飞行器包括现在被广泛使用的无人机，也包括未来的小型载人飞行器。

这个项目的目的在于提供一个快速可上手的，稳定的飞行器自动驾驶解决方案。这套方案分为软件和硬件两个部分。


软件部分，包括各个飞行器自动驾驶必要的模块。飞控、SLAM、避障、路径规划、高层应用支持、飞行模拟等。

硬件部分，包括廉价可行的旋翼机拼装方案、机上计算机和传感器的配置安装方案。

软件部分各个模块之间的通信使用 ROS 实现。每个模块皆可替换的。进行替换时，只需新模块实现原有对应的 ROS topic/service 的 pub sub 即可。项目中会提供一个较为可靠的实现，但可能不是最优的。我们欢迎开发者提供已有模块的更优实现。


# Contributing

When contributing to this repository, please first discuss the change you wish to make via issue, email, or any other method with the owners of this repository before making a change. hi@giai.tech

向本项目提交代码前,请先通过 issue 或邮件向我们提出和讨论你想做的改变。hi@giai.tech

Please note we have a code of conduct, please follow it in all your interactions with the project.

请注意：本项目对代码规范有一定要求，请遵守这些要求。

## Pull Request Process

1. Ensure any install or build dependencies are removed before the end of the layer when doing a build.

1.请确保提交的部分代码的依赖项已经完善处理。

2. Update the README.md with details of changes to the interface, this includes new environment variables, **exposed ports**, useful file locations and container parameters.

2.请确保更新对应模块的README，表述清楚**接口的变更**，新引入的全局变量/环境变量等对外部有影响的量，暴露的端口，文件路径和配置项。

3. Increase the version numbers in any examples files and the README.md to the new version that this Pull Request would represent.

3.请确保更新依赖本次变更的示例文件版本号，并在 README 中指出版本变更。

4. If you do not have permission to merge your pull request directly, you may request the reviewer to merge it for you.

4.如果你没有直接合并 pull request 的权限,你可能需要联系我们帮你合并。

### Our Pledge

**We respect all developers who have put in efforts to make autonomous flight possible.**

**We hereby promise that any issue, pull request and suggestions in any form will be taken and treated seriously.**

**Special thanks to all contributors and developers of the project, not only as an ode to your passion towards the project, but also as an ode to what mankind has always yearned.**


**我们尊重所有致力于为飞行器自动驾驶事业做出贡献的开发者。**

**在此保证：你的 issue、pull request 或其他形式给出的建议会被严肃且详细的考虑。**

**感谢一切为此项目做出有益建议和贡献的开发者。不只是为了赞美对项目的热情，而是对人类一直向往的想法所作的礼赞**



