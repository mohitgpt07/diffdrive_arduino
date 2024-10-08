# diffdrive_arduino

This node is designed to provide a ros2_control hardware interface for an Arduino running firmware from `ros_arduino_bridge`.
It is designed to be used with a `diff_drive_controller` from `ros2_control` for ros-humble.
It is expected to communicate via serial and to have four motors, each with velocity control and position/velocity feedback.
