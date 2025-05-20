# Function: <code>nonseekable_open</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int nonseekable_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81209110)
Location: fs/open.c:1154
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_open
  - kernel/power/user.c:snapshot_open
  - kernel/relay.c:relay_file_open
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_buffers_open
  - fs/libfs.c:simple_attr_open
  - fs/fuse/file.c:fuse_finish_open
  - fs/debugfs/file.c:u32_array_open
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/scsi/sg.c:sg_open
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/evdev.c:evdev_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - net/rfkill/core.c:rfkill_fop_open
```
**Symbols:**

```
ffffffff81209110-ffffffff81209121: nonseekable_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int nonseekable_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8122edf0)
Location: fs/open.c:1165
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_open
  - kernel/power/user.c:snapshot_open
  - kernel/relay.c:relay_file_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_open_pipe
  - fs/libfs.c:simple_attr_open
  - fs/fuse/file.c:fuse_finish_open
  - fs/debugfs/file.c:u32_array_open
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/scsi/sg.c:sg_open
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/evdev.c:evdev_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - net/rfkill/core.c:rfkill_fop_open
```
**Symbols:**

```
ffffffff8122edf0-ffffffff8122ee01: nonseekable_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int nonseekable_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81241350)
Location: fs/open.c:1182
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_open
  - kernel/power/user.c:snapshot_open
  - kernel/relay.c:relay_file_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_open_pipe
  - fs/libfs.c:simple_attr_open
  - fs/fuse/file.c:fuse_finish_open
  - fs/debugfs/file.c:u32_array_open
  - drivers/gpio/gpiolib.c:gpio_chrdev_open
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/scsi/sg.c:sg_open
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/evdev.c:evdev_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - net/rfkill/core.c:rfkill_fop_open
```
**Symbols:**

```
ffffffff81241350-ffffffff81241361: nonseekable_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int nonseekable_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8124ca90)
Location: fs/open.c:1208
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_open
  - kernel/power/user.c:snapshot_open
  - kernel/relay.c:relay_file_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_open_pipe
  - fs/libfs.c:simple_attr_open
  - fs/fuse/file.c:fuse_finish_open
  - fs/debugfs/file.c:u32_array_open
  - drivers/gpio/gpiolib.c:gpio_chrdev_open
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/scsi/sg.c:sg_open
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/evdev.c:evdev_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/md/dm-ioctl.c:dm_open
  - net/rfkill/core.c:rfkill_fop_open
```
**Symbols:**

```
ffffffff8124ca90-ffffffff8124caa1: nonseekable_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int nonseekable_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8126ea00)
Location: fs/open.c:1208
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_chrdev_open
  - arch/x86/kernel/cpu/microcode/core.c:microcode_open
  - kernel/power/user.c:snapshot_open
  - kernel/relay.c:relay_file_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_open_pipe
  - fs/libfs.c:simple_attr_open
  - fs/fuse/file.c:fuse_finish_open
  - fs/debugfs/file.c:u32_array_open
  - drivers/gpio/gpiolib.c:gpio_chrdev_open
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_open
  - drivers/xen/mcelog.c:xen_mce_chrdev_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/scsi/sg.c:sg_open
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/evdev.c:evdev_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/md/dm-ioctl.c:dm_open
  - net/rfkill/core.c:rfkill_fop_open
```
**Symbols:**

```
ffffffff8126ea00-ffffffff8126ea11: nonseekable_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int nonseekable_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812945d0)
Location: fs/open.c:1249
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_chrdev_open
  - arch/x86/kernel/cpu/microcode/core.c:microcode_open
  - kernel/power/user.c:snapshot_open
  - kernel/relay.c:relay_file_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_open_pipe
  - fs/libfs.c:simple_attr_open
  - fs/fuse/file.c:fuse_finish_open
  - fs/debugfs/file.c:u32_array_open
  - drivers/gpio/gpiolib.c:gpio_chrdev_open
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_open
  - drivers/xen/mcelog.c:xen_mce_chrdev_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/scsi/sg.c:sg_open
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/evdev.c:evdev_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/md/dm-ioctl.c:dm_open
  - net/rfkill/core.c:rfkill_fop_open
```
**Symbols:**

```
ffffffff812945d0-ffffffff812945e1: nonseekable_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int nonseekable_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812a92f0)
Location: fs/open.c:1216
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_open
  - arch/x86/kernel/cpu/microcode/core.c:microcode_open
  - kernel/power/user.c:snapshot_open
  - kernel/relay.c:relay_file_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_open_pipe
  - fs/libfs.c:simple_attr_open
  - fs/fuse/file.c:fuse_finish_open
  - fs/debugfs/file.c:u32_array_open
  - drivers/gpio/gpiolib.c:gpio_chrdev_open
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_open
  - drivers/xen/mcelog.c:xen_mce_chrdev_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/scsi/sg.c:sg_open
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/evdev.c:evdev_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - drivers/md/dm-ioctl.c:dm_open
  - net/rfkill/core.c:rfkill_fop_open
```
**Symbols:**

```
ffffffff812a92f0-ffffffff812a9301: nonseekable_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int nonseekable_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c5a10)
Location: fs/open.c:1236
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_open
  - kernel/power/user.c:snapshot_open
  - kernel/relay.c:relay_file_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_open_pipe
  - fs/libfs.c:simple_attr_open
  - fs/fuse/file.c:fuse_finish_open
  - fs/debugfs/file.c:u32_array_open
  - drivers/gpio/gpiolib.c:gpio_chrdev_open
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_open
  - drivers/xen/mcelog.c:xen_mce_chrdev_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/scsi/sg.c:sg_open
  - drivers/md/dm-ioctl.c:dm_open
```
**Symbols:**

```
ffffffff812c5a10-ffffffff812c5a21: nonseekable_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int nonseekable_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d7420)
Location: fs/open.c:1241
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_open
  - kernel/power/user.c:snapshot_open
  - kernel/relay.c:relay_file_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_open_pipe
  - fs/libfs.c:simple_attr_open
  - fs/fuse/file.c:fuse_finish_open
  - fs/debugfs/file.c:u32_array_open
  - drivers/gpio/gpiolib.c:gpio_chrdev_open
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_open
  - drivers/xen/mcelog.c:xen_mce_chrdev_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/scsi/sg.c:sg_open
  - drivers/md/dm-ioctl.c:dm_open
```
**Symbols:**

```
ffffffff812d7420-ffffffff812d7431: nonseekable_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int nonseekable_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8130d5f0)
Location: fs/open.c:1348
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_open
  - kernel/power/user.c:snapshot_open
  - kernel/relay.c:relay_file_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_open_pipe
  - fs/libfs.c:simple_attr_open
  - fs/fuse/file.c:fuse_finish_open
  - fs/debugfs/file.c:u32_array_open
  - drivers/gpio/gpiolib.c:gpio_chrdev_open
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_open
  - drivers/xen/mcelog.c:xen_mce_chrdev_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/scsi/sg.c:sg_open
  - drivers/md/dm-ioctl.c:dm_open
```
**Symbols:**

```
ffffffff8130d5f0-ffffffff8130d601: nonseekable_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int nonseekable_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81319550)
Location: fs/open.c:1363
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_open
  - kernel/power/user.c:snapshot_open
  - kernel/relay.c:relay_file_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_open_pipe
  - fs/libfs.c:simple_attr_open
  - fs/fuse/file.c:fuse_finish_open
  - fs/debugfs/file.c:u32_array_open
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_open
  - drivers/xen/mcelog.c:xen_mce_chrdev_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/scsi/sg.c:sg_open
  - drivers/md/dm-ioctl.c:dm_open
```
**Symbols:**

```
ffffffff81319550-ffffffff81319561: nonseekable_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int nonseekable_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8131f720)
Location: fs/open.c:1385
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_open
  - kernel/power/user.c:snapshot_open
  - kernel/relay.c:relay_file_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_open_pipe
  - fs/libfs.c:simple_attr_open
  - fs/fuse/file.c:fuse_finish_open
  - fs/debugfs/file.c:u32_array_open
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_open
  - drivers/xen/mcelog.c:xen_mce_chrdev_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/scsi/sg.c:sg_open
  - drivers/md/dm-ioctl.c:dm_open
```
**Symbols:**

```
ffffffff8131f720-ffffffff8131f731: nonseekable_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int nonseekable_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8136cbf0)
Location: fs/open.c:1403
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_open
  - kernel/power/user.c:snapshot_open
  - kernel/relay.c:relay_file_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_open_pipe
  - fs/libfs.c:simple_attr_open
  - fs/fuse/file.c:fuse_finish_open
  - fs/debugfs/file.c:u32_array_open
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_open
  - drivers/xen/mcelog.c:xen_mce_chrdev_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/scsi/sg.c:sg_open
  - drivers/md/dm-ioctl.c:dm_open
```
**Symbols:**

```
ffffffff8136cbf0-ffffffff8136cc01: nonseekable_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int nonseekable_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff813eaf90)
Location: fs/open.c:1470
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_open
  - kernel/power/user.c:snapshot_open
  - kernel/relay.c:relay_file_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_open_pipe
  - fs/libfs.c:simple_attr_open
  - fs/fuse/file.c:fuse_finish_open
  - fs/debugfs/file.c:u32_array_open
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_open
  - drivers/xen/mcelog.c:xen_mce_chrdev_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/scsi/sg.c:sg_open
  - drivers/md/dm-ioctl.c:dm_open
```
**Symbols:**

```
ffffffff813eaf90-ffffffff813eafa7: nonseekable_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int nonseekable_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814731c0)
Location: fs/open.c:1503
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_open
  - kernel/power/user.c:snapshot_open
  - kernel/relay.c:relay_file_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_open_pipe
  - fs/libfs.c:simple_attr_open
  - fs/fuse/file.c:fuse_finish_open
  - fs/debugfs/file.c:u32_array_open
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_open
  - drivers/xen/mcelog.c:xen_mce_chrdev_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/scsi/sg.c:sg_open
  - drivers/md/dm-ioctl.c:dm_open
```
**Symbols:**

```
ffffffff814731c0-ffffffff814731d7: nonseekable_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int nonseekable_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814a7930)
Location: fs/open.c:1599
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_open
  - kernel/power/user.c:snapshot_open
  - kernel/relay.c:relay_file_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_open_pipe
  - fs/libfs.c:simple_attr_open
  - fs/fuse/file.c:fuse_finish_open
  - fs/debugfs/file.c:u32_array_open
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_open
  - drivers/xen/mcelog.c:xen_mce_chrdev_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/scsi/sg.c:sg_open
  - drivers/md/dm-ioctl.c:dm_open
```
**Symbols:**

```
ffffffff814a7930-ffffffff814a7947: nonseekable_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int nonseekable_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814d8960)
Location: fs/open.c:1617
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_open
  - kernel/power/user.c:snapshot_open
  - kernel/relay.c:relay_file_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_open_pipe
  - fs/libfs.c:simple_attr_open
  - fs/fuse/file.c:fuse_finish_open
  - fs/debugfs/file.c:u32_array_open
  - drivers/gpio/gpiolib-cdev.c:gpio_chrdev_open
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_open
  - drivers/xen/mcelog.c:xen_mce_chrdev_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/scsi/sg.c:sg_open
  - drivers/md/dm-ioctl.c:dm_open
```
**Symbols:**

```
ffffffff814d8960-ffffffff814d8977: nonseekable_open (STB_GLOBAL)
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
int nonseekable_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffff80001037c748)
Location: fs/open.c:1241
Inline: False
Direct callers:
  - kernel/relay.c:relay_file_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_open_pipe
  - fs/libfs.c:simple_attr_open
  - fs/fuse/file.c:fuse_finish_open
  - fs/debugfs/file.c:u32_array_open
  - drivers/gpio/gpiolib.c:gpio_chrdev_open
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/scsi/sg.c:sg_open
  - drivers/md/dm-ioctl.c:dm_open
  - drivers/mmc/core/block.c:mmc_rpmb_chrdev_open
```
**Symbols:**

```
ffff80001037c748-ffff80001037c77c: nonseekable_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int nonseekable_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c05671a8)
Location: fs/open.c:1241
Inline: False
Direct callers:
  - kernel/power/user.c:snapshot_open
  - kernel/relay.c:relay_file_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_open_pipe
  - fs/libfs.c:simple_attr_open
  - fs/fuse/file.c:fuse_finish_open
  - fs/debugfs/file.c:u32_array_open
  - drivers/gpio/gpiolib.c:gpio_chrdev_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/scsi/sg.c:sg_open
  - drivers/md/dm-ioctl.c:dm_open
  - drivers/mmc/core/block.c:mmc_rpmb_chrdev_open
```
**Symbols:**

```
c05671a8-c05671d0: nonseekable_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int nonseekable_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c0000000004718f0)
Location: fs/open.c:1241
Inline: False
Direct callers:
  - kernel/relay.c:relay_file_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_open_pipe
  - fs/libfs.c:simple_attr_open
  - fs/fuse/file.c:fuse_finish_open
  - fs/debugfs/file.c:u32_array_open
  - drivers/gpio/gpiolib.c:gpio_chrdev_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/scsi/sg.c:sg_open
  - drivers/md/dm-ioctl.c:dm_open
```
**Symbols:**

```
c0000000004718f0-c00000000047190c: nonseekable_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int nonseekable_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffe000252b98)
Location: fs/open.c:1241
Inline: False
Direct callers:
  - kernel/relay.c:relay_file_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_open_pipe
  - fs/libfs.c:simple_attr_open
  - fs/fuse/file.c:fuse_finish_open
  - fs/debugfs/file.c:u32_array_open
  - drivers/gpio/gpiolib.c:gpio_chrdev_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/scsi/sg.c:sg_open
  - drivers/md/dm-ioctl.c:dm_open
  - drivers/mmc/core/block.c:mmc_rpmb_chrdev_open
```
**Symbols:**

```
ffffffe000252b98-ffffffe000252bc0: nonseekable_open (STB_GLOBAL)
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
int nonseekable_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812cfa00)
Location: fs/open.c:1241
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_open
  - kernel/power/user.c:snapshot_open
  - kernel/relay.c:relay_file_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_open_pipe
  - fs/libfs.c:simple_attr_open
  - fs/fuse/file.c:fuse_finish_open
  - fs/debugfs/file.c:u32_array_open
  - drivers/gpio/gpiolib.c:gpio_chrdev_open
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_open
  - drivers/xen/mcelog.c:xen_mce_chrdev_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/scsi/sg.c:sg_open
  - drivers/md/dm-ioctl.c:dm_open
```
**Symbols:**

```
ffffffff812cfa00-ffffffff812cfa11: nonseekable_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int nonseekable_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c0680)
Location: fs/open.c:1241
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_open
  - kernel/power/user.c:snapshot_open
  - kernel/relay.c:relay_file_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_open_pipe
  - fs/libfs.c:simple_attr_open
  - fs/fuse/file.c:fuse_finish_open
  - fs/debugfs/file.c:u32_array_open
  - drivers/gpio/gpiolib.c:gpio_chrdev_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/scsi/sg.c:sg_open
  - drivers/md/dm-ioctl.c:dm_open
```
**Symbols:**

```
ffffffff812c0680-ffffffff812c0691: nonseekable_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int nonseekable_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812cd810)
Location: fs/open.c:1241
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_open
  - kernel/power/user.c:snapshot_open
  - kernel/relay.c:relay_file_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_open_pipe
  - fs/libfs.c:simple_attr_open
  - fs/fuse/file.c:fuse_finish_open
  - fs/debugfs/file.c:u32_array_open
  - drivers/gpio/gpiolib.c:gpio_chrdev_open
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_open
  - drivers/xen/mcelog.c:xen_mce_chrdev_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/scsi/sg.c:sg_open
  - drivers/md/dm-ioctl.c:dm_open
```
**Symbols:**

```
ffffffff812cd810-ffffffff812cd821: nonseekable_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int nonseekable_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812de620)
Location: fs/open.c:1241
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_open
  - kernel/power/user.c:snapshot_open
  - kernel/relay.c:relay_file_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_open_pipe
  - fs/libfs.c:simple_attr_open
  - fs/fuse/file.c:fuse_finish_open
  - fs/debugfs/file.c:u32_array_open
  - drivers/gpio/gpiolib.c:gpio_chrdev_open
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_open
  - drivers/xen/mcelog.c:xen_mce_chrdev_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/scsi/sg.c:sg_open
  - drivers/md/dm-ioctl.c:dm_open
```
**Symbols:**

```
ffffffff812de620-ffffffff812de631: nonseekable_open (STB_GLOBAL)
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
