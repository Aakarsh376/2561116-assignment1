# Assignment 1: The ROS 2 Developer Foundation

**Student Name:**
**Roll Number / Batch:**

## 1. Base Workspace vs. Overlay Workspace

_(Explain the difference here — what is the base ROS 2 Jazzy installation, and what does "overlaying" your `ug_3sem_ws` workspace on top of it mean?)_

## 2. Purpose of `src` and `install` Directories

_(Explain what goes into `src/` vs what `colcon build` generates into `install/`, and why `install/` is not committed to Git.)_

## 3. Verification Screenshot

_(Paste your terminal screenshot here showing `ros2 run robot_info_py info_script` running successfully.)_

`![terminal screenshot](screenshot.png)`

---

## Repository Structure

```
ug_3sem_ws/
└── src/
    ├── robot_info_py/      # ament_python package
    └── robot_info_cpp/     # ament_cmake package
```

Do **not** commit `build/`, `install/`, or `log/` — these are excluded via `.gitignore`.
