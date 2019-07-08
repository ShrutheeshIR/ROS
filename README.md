#ROS

Simple ROS Projects while learning ROS

## First task.

>roscore - to run master.

> rosrun roscpp_tutorials talker
> rosrun roscpp_tutorials listener
> rosnode info /talker (says that a topic called chatter is being published)
> rostopic infp /chatter (says that it is string)

### To publish own message

> rostopic pub /chatter std_msgs/String "data: 'Hi From Shrutheesh'" (sends out one message)
