clone this repo into ~/ros2_ws/src

file system should look like
    ~/
    ----/ros2_ws/
                    /build
                    /install
                    /log
                    /src
                        /ngcp_webserver

run "colcon build --symlink-install" from ~/ros2_ws 

after done building, run ". install/setup.bash"

then, "ros2 run ngcp_webserver Webserver"