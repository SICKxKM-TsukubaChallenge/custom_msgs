# custom_msgs for [ros-humble-ros1-bridge-builder](https://github.com/TommyChangUMD/ros-humble-ros1-bridge-builder)

## 使い方
custom_msgs_ros2のディレクトリまで移動し`colcon build`，`source install/setup.hoge`することで新しいメッセージのブリッジが可能になる．
メッセージの形はコードを読んでください．

## 注意
ROS と ROS 2 版のパッケージが両方含まれているので通常の`ros_ws`等にcloneすることは推奨できません．workspace内部に同じ名前のパッケージがありますと言われコンパイルできなくなってしまいます．
別途DIRにcloneしてコンパイルすることをおすすめします．

## 現状実装されているメッセージ
- MoveBaseResult.msg
- MoveBaseActionResult.msg
- MoveBaseFeedback.msg
- MoveBaseActionFeedback.msg
- MoveBaseActionGoal.msg
- MoveBaseGoal.msg
- MoveBaseAction.msg
