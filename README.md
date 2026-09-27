# UEH - Bui Le Uyen Vy - Vien Cong nghe Thong minh va Tuong tac

## Description
Autonomous Robot Simulation solution for UEH CRC 2026 challenge.

Terminal 1
cd ~/Downloads
bash scripts/run_docker.sh compile
bash scripts/run_docker.sh up

Terminal 2
cd ~/Downloads
bash scripts/run_docker.sh sh
ros2 launch crc_sim sim.launch.py rviz:=true gui:=false

Terminal 3
cd ~/Downloads
bash scripts/run_docker.sh sh
ros2 run crc_sim starter
