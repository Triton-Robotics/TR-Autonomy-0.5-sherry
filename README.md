# TR-Autonomy-0.5

[![CV Training Resources](https://img.shields.io/badge/CV-%20Training%20Resources-eac817?labelColor=2a77a2&style=for-the-badge)](https://github.com/Triton-Robotics-Training/TR-CV-0/blob/main/resources.md)

## How to Work On and Submit This Assignment

**Read this before you clone anything.** Do not push directly to this repository. All work happens in your own fork.

1. Click "Fork" at the top right of this page, set the **Owner** to `Triton-Robotics-Training`, and name the fork so it's clearly yours, e.g. `TR-Autonomy-0.5-your-name`. (The screenshots below are from `TR-Autonomy-1`, but the steps are identical here.)

   ![Creating a fork in the Triton-Robotics-Training organization](images/create-fork.png)

2. **Clone *your fork*** (not this repo) and do all of your work there:
   ```bash
   git clone git@github.com:Triton-Robotics-Training/TR-Autonomy-0.5-your-name.git
   ```
3. **Commit and push your work to your fork** as you go. Everywhere below that says "commit/upload to this repo," it means your fork.
4. **When you're done, open a pull request** from your fork back to `Triton-Robotics-Training/TR-Autonomy-0.5` `main`. Once your fork is ahead of the upstream repo, GitHub shows a **Contribute → Open pull request** button on your fork's front page:

   ![Opening a pull request from your fork back to the upstream repo](images/open-pull-request.png)

   That pull request is your submission. You do not need to do anything else to submit.

If you can't fork into the org because you don't have access, ask an autonomy lead to add you to the GitHub organization.

## Part 1 | Workspaces

This is an assignment meant to give you a highly structured introduction to some of the ros2 concepts needed for the upcoming training-1 assignment

1. Follow [this tutorial](https://docs.ros.org/en/humble/Tutorials/Beginner-Client-Libraries/Creating-A-Workspace/Creating-A-Workspace.html)
2. [Screenshot](https://help.ubuntu.com/stable/ubuntu-help/screen-shot-record.html) the modified turtlesim window you get at the end of the tutorial. Change the window title to say your GitHub username:

> <img src="yourusernamehere.png" style="width: 30%">

3. Commit the screenshot to this repo.

- To do this, you will need to install git on your Ubuntu machine and set up authentication with a SSH key
  - [using SSH Keys to authenticate](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

## Part 2 | Packages

1. Follow the [next tutorial](https://docs.ros.org/en/humble/Tutorials/Beginner-Client-Libraries/Creating-Your-First-ROS2-Package.html) in the sequence
2. running your new package will output `hello world my_package package`. Change this to output `hello world [your github username]!`
3. upload a screenshot of your modified output to this repo

## Part 3 | Publishers and Subscribers

1. Follow the [next tutorial](https://docs.ros.org/en/humble/Tutorials/Beginner-Client-Libraries/Writing-A-Simple-Cpp-Publisher-And-Subscriber.html) in the sequence
2. upload a screenshot of the publisher node terminal and the subscription node terminal running side by side
