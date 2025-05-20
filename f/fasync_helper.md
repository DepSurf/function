# Function: <code>fasync_helper</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fasync_helper(int fd, struct file *filp, int on, struct fasync_struct **fapp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff8121f890)
Location: fs/fcntl.c:686
Inline: False
Direct callers:
  - kernel/events/core.c:perf_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/notify/group.c:fsnotify_fasync
  - fs/fuse/dev.c:fuse_dev_fasync
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/vt/vc_screen.c:vcs_fasync
  - drivers/char/random.c:random_fasync
  - drivers/char/virtio_console.c:port_fops_fasync
  - drivers/char/hpet.c:hpet_fasync
  - drivers/scsi/sg.c:sg_fasync
  - drivers/net/tun.c:tun_chr_fasync
  - drivers/input/mousedev.c:mousedev_fasync
  - drivers/input/evdev.c:evdev_fasync
  - drivers/rtc/rtc-dev.c:rtc_dev_fasync
  - net/socket.c:sock_fasync
```
**Symbols:**

```
ffffffff8121f890-ffffffff8121f919: fasync_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fasync_helper(int fd, struct file *filp, int on, struct fasync_struct **fapp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81247100)
Location: fs/fcntl.c:690
Inline: False
Direct callers:
  - kernel/events/core.c:perf_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/notify/group.c:fsnotify_fasync
  - fs/fuse/dev.c:fuse_dev_fasync
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/vt/vc_screen.c:vcs_fasync
  - drivers/char/random.c:random_fasync
  - drivers/char/virtio_console.c:port_fops_fasync
  - drivers/char/hpet.c:hpet_fasync
  - drivers/scsi/sg.c:sg_fasync
  - drivers/net/tun.c:tun_chr_fasync
  - drivers/input/mousedev.c:mousedev_fasync
  - drivers/input/evdev.c:evdev_fasync
  - drivers/rtc/rtc-dev.c:rtc_dev_fasync
  - net/socket.c:sock_fasync
```
**Symbols:**

```
ffffffff81247100-ffffffff81247189: fasync_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fasync_helper(int fd, struct file *filp, int on, struct fasync_struct **fapp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff8125a0f0)
Location: fs/fcntl.c:690
Inline: False
Direct callers:
  - kernel/events/core.c:perf_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/notify/group.c:fsnotify_fasync
  - fs/fuse/dev.c:fuse_dev_fasync
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/vt/vc_screen.c:vcs_fasync
  - drivers/char/random.c:random_fasync
  - drivers/char/virtio_console.c:port_fops_fasync
  - drivers/char/hpet.c:hpet_fasync
  - drivers/scsi/sg.c:sg_fasync
  - drivers/net/tun.c:tun_chr_fasync
  - drivers/input/mousedev.c:mousedev_fasync
  - drivers/input/evdev.c:evdev_fasync
  - drivers/rtc/rtc-dev.c:rtc_dev_fasync
  - net/socket.c:sock_fasync
```
**Symbols:**

```
ffffffff8125a0f0-ffffffff8125a179: fasync_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fasync_helper(int fd, struct file *filp, int on, struct fasync_struct **fapp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81266ab0)
Location: fs/fcntl.c:960
Inline: False
Direct callers:
  - kernel/events/core.c:perf_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/notify/group.c:fsnotify_fasync
  - fs/fuse/dev.c:fuse_dev_fasync
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/vt/vc_screen.c:vcs_fasync
  - drivers/char/random.c:random_fasync
  - drivers/char/virtio_console.c:port_fops_fasync
  - drivers/char/hpet.c:hpet_fasync
  - drivers/scsi/sg.c:sg_fasync
  - drivers/net/tun.c:tun_chr_fasync
  - drivers/input/mousedev.c:mousedev_fasync
  - drivers/input/evdev.c:evdev_fasync
  - drivers/rtc/rtc-dev.c:rtc_dev_fasync
  - net/socket.c:sock_fasync
```
**Symbols:**

```
ffffffff81266ab0-ffffffff81266b39: fasync_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fasync_helper(int fd, struct file *filp, int on, struct fasync_struct **fapp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81289350)
Location: fs/fcntl.c:970
Inline: False
Direct callers:
  - kernel/events/core.c:perf_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/notify/group.c:fsnotify_fasync
  - fs/fuse/dev.c:fuse_dev_fasync
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/vt/vc_screen.c:vcs_fasync
  - drivers/char/random.c:random_fasync
  - drivers/char/virtio_console.c:port_fops_fasync
  - drivers/char/hpet.c:hpet_fasync
  - drivers/scsi/sg.c:sg_fasync
  - drivers/net/tun.c:tun_chr_fasync
  - drivers/input/mousedev.c:mousedev_fasync
  - drivers/input/evdev.c:evdev_fasync
  - drivers/rtc/rtc-dev.c:rtc_dev_fasync
  - net/socket.c:sock_fasync
```
**Symbols:**

```
ffffffff81289350-ffffffff812893d9: fasync_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fasync_helper(int fd, struct file *filp, int on, struct fasync_struct **fapp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812af6d0)
Location: fs/fcntl.c:977
Inline: False
Direct callers:
  - kernel/events/core.c:perf_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/notify/group.c:fsnotify_fasync
  - fs/fuse/dev.c:fuse_dev_fasync
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/vt/vc_screen.c:vcs_fasync
  - drivers/char/random.c:random_fasync
  - drivers/char/virtio_console.c:port_fops_fasync
  - drivers/char/hpet.c:hpet_fasync
  - drivers/scsi/sg.c:sg_fasync
  - drivers/net/tun.c:tun_chr_fasync
  - drivers/input/mousedev.c:mousedev_fasync
  - drivers/input/evdev.c:evdev_fasync
  - drivers/rtc/rtc-dev.c:rtc_dev_fasync
  - drivers/pps/pps.c:pps_cdev_fasync
  - net/socket.c:sock_fasync
```
**Symbols:**

```
ffffffff812af6d0-ffffffff812af762: fasync_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fasync_helper(int fd, struct file *filp, int on, struct fasync_struct **fapp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812c4850)
Location: fs/fcntl.c:981
Inline: False
Direct callers:
  - kernel/events/core.c:perf_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/notify/group.c:fsnotify_fasync
  - fs/fuse/dev.c:fuse_dev_fasync
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/vt/vc_screen.c:vcs_fasync
  - drivers/char/random.c:random_fasync
  - drivers/char/virtio_console.c:port_fops_fasync
  - drivers/char/hpet.c:hpet_fasync
  - drivers/scsi/sg.c:sg_fasync
  - drivers/net/tun.c:tun_chr_fasync
  - drivers/input/mousedev.c:mousedev_fasync
  - drivers/input/evdev.c:evdev_fasync
  - drivers/rtc/dev.c:rtc_dev_fasync
  - drivers/pps/pps.c:pps_cdev_fasync
  - net/socket.c:sock_fasync
```
**Symbols:**

```
ffffffff812c4850-ffffffff812c48e2: fasync_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fasync_helper(int fd, struct file *filp, int on, struct fasync_struct **fapp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812e1280)
Location: fs/fcntl.c:981
Inline: False
Direct callers:
  - kernel/events/core.c:perf_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/notify/group.c:fsnotify_fasync
  - fs/io_uring.c:io_uring_fasync
  - fs/fuse/dev.c:fuse_dev_fasync
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/vt/vc_screen.c:vcs_fasync
  - drivers/char/random.c:random_fasync
  - drivers/char/virtio_console.c:port_fops_fasync
  - drivers/char/hpet.c:hpet_fasync
  - drivers/scsi/sg.c:sg_fasync
  - drivers/net/tun.c:tun_chr_fasync
  - drivers/input/mousedev.c:mousedev_fasync
  - drivers/input/evdev.c:evdev_fasync
  - drivers/rtc/dev.c:rtc_dev_fasync
  - drivers/pps/pps.c:pps_cdev_fasync
  - net/socket.c:sock_fasync
```
**Symbols:**

```
ffffffff812e1280-ffffffff812e1316: fasync_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fasync_helper(int fd, struct file *filp, int on, struct fasync_struct **fapp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812f2d30)
Location: fs/fcntl.c:981
Inline: False
Direct callers:
  - kernel/events/core.c:perf_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/notify/group.c:fsnotify_fasync
  - fs/io_uring.c:io_uring_fasync
  - fs/fuse/dev.c:fuse_dev_fasync
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/vt/vc_screen.c:vcs_fasync
  - drivers/char/random.c:random_fasync
  - drivers/char/virtio_console.c:port_fops_fasync
  - drivers/char/hpet.c:hpet_fasync
  - drivers/scsi/sg.c:sg_fasync
  - drivers/net/tun.c:tun_chr_fasync
  - drivers/input/mousedev.c:mousedev_fasync
  - drivers/input/evdev.c:evdev_fasync
  - drivers/rtc/dev.c:rtc_dev_fasync
  - drivers/pps/pps.c:pps_cdev_fasync
  - net/socket.c:sock_fasync
```
**Symbols:**

```
ffffffff812f2d30-ffffffff812f2dc6: fasync_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fasync_helper(int fd, struct file *filp, int on, struct fasync_struct **fapp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff8132afc0)
Location: fs/fcntl.c:983
Inline: False
Direct callers:
  - kernel/events/core.c:perf_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/notify/group.c:fsnotify_fasync
  - fs/io_uring.c:io_uring_fasync
  - fs/fuse/dev.c:fuse_dev_fasync
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/vt/vc_screen.c:vcs_fasync
  - drivers/char/random.c:random_fasync
  - drivers/char/virtio_console.c:port_fops_fasync
  - drivers/char/hpet.c:hpet_fasync
  - drivers/scsi/sg.c:sg_fasync
  - drivers/net/tun.c:tun_chr_fasync
  - drivers/input/mousedev.c:mousedev_fasync
  - drivers/input/evdev.c:evdev_fasync
  - drivers/rtc/dev.c:rtc_dev_fasync
  - drivers/pps/pps.c:pps_cdev_fasync
  - net/socket.c:sock_fasync
```
**Symbols:**

```
ffffffff8132afc0-ffffffff8132b056: fasync_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fasync_helper(int fd, struct file *filp, int on, struct fasync_struct **fapp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81336590)
Location: fs/fcntl.c:985
Inline: False
Direct callers:
  - kernel/events/core.c:perf_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/notify/group.c:fsnotify_fasync
  - fs/io_uring.c:io_uring_fasync
  - fs/fuse/dev.c:fuse_dev_fasync
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/vt/vc_screen.c:vcs_fasync
  - drivers/char/random.c:random_fasync
  - drivers/char/virtio_console.c:port_fops_fasync
  - drivers/char/hpet.c:hpet_fasync
  - drivers/scsi/sg.c:sg_fasync
  - drivers/net/tun.c:tun_chr_fasync
  - drivers/input/mousedev.c:mousedev_fasync
  - drivers/input/evdev.c:evdev_fasync
  - drivers/rtc/dev.c:rtc_dev_fasync
  - drivers/pps/pps.c:pps_cdev_fasync
  - net/socket.c:sock_fasync
```
**Symbols:**

```
ffffffff81336590-ffffffff81336626: fasync_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fasync_helper(int fd, struct file *filp, int on, struct fasync_struct **fapp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff8133c730)
Location: fs/fcntl.c:990
Inline: False
Direct callers:
  - kernel/events/core.c:perf_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/notify/group.c:fsnotify_fasync
  - fs/io_uring.c:io_uring_fasync
  - fs/fuse/dev.c:fuse_dev_fasync
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/vt/vc_screen.c:vcs_fasync
  - drivers/char/random.c:random_fasync
  - drivers/char/virtio_console.c:port_fops_fasync
  - drivers/char/hpet.c:hpet_fasync
  - drivers/scsi/sg.c:sg_fasync
  - drivers/net/tun.c:tun_chr_fasync
  - drivers/input/mousedev.c:mousedev_fasync
  - drivers/input/evdev.c:evdev_fasync
  - drivers/rtc/dev.c:rtc_dev_fasync
  - drivers/pps/pps.c:pps_cdev_fasync
  - net/socket.c:sock_fasync
```
**Symbols:**

```
ffffffff8133c730-ffffffff8133c7c6: fasync_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fasync_helper(int fd, struct file *filp, int on, struct fasync_struct **fapp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff8138a430)
Location: fs/fcntl.c:994
Inline: False
Direct callers:
  - kernel/events/core.c:perf_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/notify/group.c:fsnotify_fasync
  - fs/fuse/dev.c:fuse_dev_fasync
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/vt/vc_screen.c:vcs_fasync
  - drivers/char/random.c:random_fasync
  - drivers/char/virtio_console.c:port_fops_fasync
  - drivers/char/hpet.c:hpet_fasync
  - drivers/scsi/sg.c:sg_fasync
  - drivers/net/tun.c:tun_chr_fasync
  - drivers/input/mousedev.c:mousedev_fasync
  - drivers/input/evdev.c:evdev_fasync
  - drivers/rtc/dev.c:rtc_dev_fasync
  - drivers/pps/pps.c:pps_cdev_fasync
  - net/socket.c:sock_fasync
```
**Symbols:**

```
ffffffff8138a430-ffffffff8138a4c6: fasync_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fasync_helper(int fd, struct file *filp, int on, struct fasync_struct **fapp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff8140b510)
Location: fs/fcntl.c:972
Inline: False
Direct callers:
  - kernel/events/core.c:perf_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/notify/group.c:fsnotify_fasync
  - fs/locks.c:lease_modify
  - fs/fuse/dev.c:fuse_dev_fasync
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/vt/vc_screen.c:vcs_fasync
  - drivers/char/random.c:random_fasync
  - drivers/char/virtio_console.c:port_fops_fasync
  - drivers/char/hpet.c:hpet_fasync
  - drivers/scsi/sg.c:sg_fasync
  - drivers/net/tun.c:tun_chr_fasync
  - drivers/input/mousedev.c:mousedev_fasync
  - drivers/input/evdev.c:evdev_fasync
  - drivers/rtc/dev.c:rtc_dev_fasync
  - drivers/pps/pps.c:pps_cdev_fasync
  - net/socket.c:sock_fasync
```
**Symbols:**

```
ffffffff8140b510-ffffffff8140b5c6: fasync_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fasync_helper(int fd, struct file *filp, int on, struct fasync_struct **fapp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81495e60)
Location: fs/fcntl.c:973
Inline: False
Direct callers:
  - kernel/events/core.c:perf_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/notify/group.c:fsnotify_fasync
  - fs/locks.c:lease_modify
  - fs/fuse/dev.c:fuse_dev_fasync
  - drivers/tty/vt/vc_screen.c:vcs_fasync
  - drivers/char/random.c:random_fasync
  - drivers/char/virtio_console.c:port_fops_fasync
  - drivers/char/hpet.c:hpet_fasync
  - drivers/scsi/sg.c:sg_fasync
  - drivers/net/tun.c:tun_chr_fasync
  - drivers/input/mousedev.c:mousedev_fasync
  - drivers/input/evdev.c:evdev_fasync
  - drivers/rtc/dev.c:rtc_dev_fasync
  - drivers/pps/pps.c:pps_cdev_fasync
  - net/socket.c:sock_fasync
```
**Symbols:**

```
ffffffff81495e60-ffffffff81495f16: fasync_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fasync_helper(int fd, struct file *filp, int on, struct fasync_struct **fapp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff814caea0)
Location: fs/fcntl.c:974
Inline: False
Direct callers:
  - kernel/events/core.c:perf_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/notify/group.c:fsnotify_fasync
  - fs/locks.c:lease_modify
  - fs/fuse/dev.c:fuse_dev_fasync
  - drivers/tty/vt/vc_screen.c:vcs_fasync
  - drivers/char/random.c:random_fasync
  - drivers/char/virtio_console.c:port_fops_fasync
  - drivers/char/hpet.c:hpet_fasync
  - drivers/scsi/sg.c:sg_fasync
  - drivers/net/tun.c:tun_chr_fasync
  - drivers/input/mousedev.c:mousedev_fasync
  - drivers/input/evdev.c:evdev_fasync
  - drivers/rtc/dev.c:rtc_dev_fasync
  - drivers/pps/pps.c:pps_cdev_fasync
  - net/socket.c:sock_fasync
```
**Symbols:**

```
ffffffff814caea0-ffffffff814caf56: fasync_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fasync_helper(int fd, struct file *filp, int on, struct fasync_struct **fapp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff814fd750)
Location: fs/fcntl.c:975
Inline: False
Direct callers:
  - kernel/events/core.c:perf_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/notify/group.c:fsnotify_fasync
  - fs/locks.c:lease_modify
  - fs/fuse/dev.c:fuse_dev_fasync
  - drivers/tty/vt/vc_screen.c:vcs_fasync
  - drivers/char/random.c:random_fasync
  - drivers/char/virtio_console.c:port_fops_fasync
  - drivers/char/hpet.c:hpet_fasync
  - drivers/scsi/sg.c:sg_fasync
  - drivers/net/tun.c:tun_chr_fasync
  - drivers/input/mousedev.c:mousedev_fasync
  - drivers/input/evdev.c:evdev_fasync
  - drivers/rtc/dev.c:rtc_dev_fasync
  - drivers/pps/pps.c:pps_cdev_fasync
  - net/socket.c:sock_fasync
```
**Symbols:**

```
ffffffff814fd750-ffffffff814fd806: fasync_helper (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int fasync_helper(int fd, struct file *filp, int on, struct fasync_struct **fapp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffff80001039d368)
Location: fs/fcntl.c:981
Inline: False
Direct callers:
  - kernel/events/core.c:perf_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/notify/group.c:fsnotify_fasync
  - fs/io_uring.c:io_uring_fasync
  - fs/fuse/dev.c:fuse_dev_fasync
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/vt/vc_screen.c:vcs_fasync
  - drivers/char/random.c:random_fasync
  - drivers/char/virtio_console.c:port_fops_fasync
  - drivers/scsi/sg.c:sg_fasync
  - drivers/net/tun.c:tun_chr_fasync
  - drivers/input/mousedev.c:mousedev_fasync
  - drivers/input/evdev.c:evdev_fasync
  - drivers/rtc/dev.c:rtc_dev_fasync
  - drivers/pps/pps.c:pps_cdev_fasync
  - net/socket.c:sock_fasync
```
**Symbols:**

```
ffff80001039d368-ffff80001039d430: fasync_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fasync_helper(int fd, struct file *filp, int on, struct fasync_struct **fapp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (c0582bc8)
Location: fs/fcntl.c:981
Inline: False
Direct callers:
  - kernel/events/core.c:perf_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/notify/group.c:fsnotify_fasync
  - fs/io_uring.c:io_uring_fasync
  - fs/fuse/dev.c:fuse_dev_fasync
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/vt/vc_screen.c:vcs_fasync
  - drivers/char/random.c:random_fasync
  - drivers/char/virtio_console.c:port_fops_fasync
  - drivers/scsi/sg.c:sg_fasync
  - drivers/net/tun.c:tun_chr_fasync
  - drivers/input/mousedev.c:mousedev_fasync
  - drivers/input/evdev.c:evdev_fasync
  - drivers/rtc/dev.c:rtc_dev_fasync
  - drivers/pps/pps.c:pps_cdev_fasync
  - sound/core/control.c:snd_ctl_fasync
  - sound/core/timer.c:snd_timer_user_fasync
  - sound/core/pcm_native.c:snd_pcm_fasync
  - net/socket.c:sock_fasync
```
**Symbols:**

```
c0582bc8-c0582c5c: fasync_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fasync_helper(int fd, struct file *filp, int on, struct fasync_struct **fapp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (c0000000004980f0)
Location: fs/fcntl.c:981
Inline: False
Direct callers:
  - kernel/events/core.c:perf_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/notify/group.c:fsnotify_fasync
  - fs/io_uring.c:io_uring_fasync
  - fs/fuse/dev.c:fuse_dev_fasync
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/vt/vc_screen.c:vcs_fasync
  - drivers/char/random.c:random_fasync
  - drivers/char/virtio_console.c:port_fops_fasync
  - drivers/scsi/sg.c:sg_fasync
  - drivers/net/tun.c:tun_chr_fasync
  - drivers/input/mousedev.c:mousedev_fasync
  - drivers/input/evdev.c:evdev_fasync
  - drivers/rtc/dev.c:rtc_dev_fasync
  - drivers/pps/pps.c:pps_cdev_fasync
  - net/socket.c:sock_fasync
```
**Symbols:**

```
c0000000004980f0-c000000000498200: fasync_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fasync_helper(int fd, struct file *filp, int on, struct fasync_struct **fapp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffe000269434)
Location: fs/fcntl.c:981
Inline: False
Direct callers:
  - kernel/events/core.c:perf_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/notify/group.c:fsnotify_fasync
  - fs/io_uring.c:io_uring_fasync
  - fs/fuse/dev.c:fuse_dev_fasync
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/vt/vc_screen.c:vcs_fasync
  - drivers/char/random.c:random_fasync
  - drivers/char/virtio_console.c:port_fops_fasync
  - drivers/scsi/sg.c:sg_fasync
  - drivers/net/tun.c:tun_chr_fasync
  - drivers/input/mousedev.c:mousedev_fasync
  - drivers/input/evdev.c:evdev_fasync
  - drivers/rtc/dev.c:rtc_dev_fasync
  - drivers/pps/pps.c:pps_cdev_fasync
  - net/socket.c:sock_fasync
```
**Symbols:**

```
ffffffe000269434-ffffffe0002694c4: fasync_helper (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int fasync_helper(int fd, struct file *filp, int on, struct fasync_struct **fapp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812eb310)
Location: fs/fcntl.c:981
Inline: False
Direct callers:
  - kernel/events/core.c:perf_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/notify/group.c:fsnotify_fasync
  - fs/io_uring.c:io_uring_fasync
  - fs/fuse/dev.c:fuse_dev_fasync
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/vt/vc_screen.c:vcs_fasync
  - drivers/char/random.c:random_fasync
  - drivers/char/virtio_console.c:port_fops_fasync
  - drivers/char/hpet.c:hpet_fasync
  - drivers/scsi/sg.c:sg_fasync
  - drivers/net/tun.c:tun_chr_fasync
  - drivers/input/mousedev.c:mousedev_fasync
  - drivers/input/evdev.c:evdev_fasync
  - drivers/rtc/dev.c:rtc_dev_fasync
  - drivers/pps/pps.c:pps_cdev_fasync
  - net/socket.c:sock_fasync
```
**Symbols:**

```
ffffffff812eb310-ffffffff812eb3a6: fasync_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fasync_helper(int fd, struct file *filp, int on, struct fasync_struct **fapp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812dbf40)
Location: fs/fcntl.c:981
Inline: False
Direct callers:
  - kernel/events/core.c:perf_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/notify/group.c:fsnotify_fasync
  - fs/io_uring.c:io_uring_fasync
  - fs/fuse/dev.c:fuse_dev_fasync
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/vt/vc_screen.c:vcs_fasync
  - drivers/char/random.c:random_fasync
  - drivers/char/virtio_console.c:port_fops_fasync
  - drivers/char/hpet.c:hpet_fasync
  - drivers/scsi/sg.c:sg_fasync
  - drivers/net/tun.c:tun_chr_fasync
  - drivers/input/mousedev.c:mousedev_fasync
  - drivers/input/evdev.c:evdev_fasync
  - drivers/rtc/dev.c:rtc_dev_fasync
  - drivers/pps/pps.c:pps_cdev_fasync
  - net/socket.c:sock_fasync
```
**Symbols:**

```
ffffffff812dbf40-ffffffff812dbfd6: fasync_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fasync_helper(int fd, struct file *filp, int on, struct fasync_struct **fapp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812e9120)
Location: fs/fcntl.c:981
Inline: False
Direct callers:
  - kernel/events/core.c:perf_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/notify/group.c:fsnotify_fasync
  - fs/io_uring.c:io_uring_fasync
  - fs/fuse/dev.c:fuse_dev_fasync
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/vt/vc_screen.c:vcs_fasync
  - drivers/char/random.c:random_fasync
  - drivers/char/virtio_console.c:port_fops_fasync
  - drivers/char/hpet.c:hpet_fasync
  - drivers/scsi/sg.c:sg_fasync
  - drivers/net/tun.c:tun_chr_fasync
  - drivers/input/mousedev.c:mousedev_fasync
  - drivers/input/evdev.c:evdev_fasync
  - drivers/rtc/dev.c:rtc_dev_fasync
  - drivers/pps/pps.c:pps_cdev_fasync
  - net/socket.c:sock_fasync
```
**Symbols:**

```
ffffffff812e9120-ffffffff812e91b6: fasync_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fasync_helper(int fd, struct file *filp, int on, struct fasync_struct **fapp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812fa120)
Location: fs/fcntl.c:981
Inline: False
Direct callers:
  - kernel/events/core.c:perf_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/pipe.c:pipe_fasync
  - fs/notify/group.c:fsnotify_fasync
  - fs/io_uring.c:io_uring_fasync
  - fs/fuse/dev.c:fuse_dev_fasync
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/vt/vc_screen.c:vcs_fasync
  - drivers/char/random.c:random_fasync
  - drivers/char/virtio_console.c:port_fops_fasync
  - drivers/char/hpet.c:hpet_fasync
  - drivers/scsi/sg.c:sg_fasync
  - drivers/net/tun.c:tun_chr_fasync
  - drivers/input/mousedev.c:mousedev_fasync
  - drivers/input/evdev.c:evdev_fasync
  - drivers/rtc/dev.c:rtc_dev_fasync
  - drivers/pps/pps.c:pps_cdev_fasync
  - net/socket.c:sock_fasync
```
**Symbols:**

```
ffffffff812fa120-ffffffff812fa1b6: fasync_helper (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
