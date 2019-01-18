#Usage

docker run -it --rm -p 5901:5901 -e USER=root babim/oraclelinuxbase:6.gui

attach container and enter vnc password (first run)

Connect to vnc://<host>:5901 via VNC client.

Change password over vncpasswd command in container
