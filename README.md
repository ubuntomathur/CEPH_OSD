# CEPH_OSD


![Image Alt](https://github.com/ubuntomathur/CEPH_OSD/blob/main/ceph-d.png)


Here's the tabular representation of the handwritten notes:

| OSD   | Node   | Device  |
|-------|--------|---------|
| osd.0 | node01 | /dev/sda |
| osd.1 | node01 | /dev/sdb |
| osd.2 | node01 | /dev/sdc |
| osd.3 | node02 | /dev/sda |
| osd.4 | node02 | /dev/sdb |
| osd.5 | node02 | /dev/sdc |
| osd.6 | node02 | /dev/sdd |
| osd.7 | node03 | /dev/sdb |
| osd.8 | node03 | /dev/sdc |

OSD means object storage daemon which is running as daemon service it is always talk to your physical disk /dev/sda or virtual disk /dev/vda, talking means - data read and write operation 
