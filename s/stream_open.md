# Function: <code>stream_open</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int stream_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c5a30)
Location: fs/open.c:1254
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_open
  - fs/fuse/file.c:fuse_finish_open
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/evdev.c:evdev_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - net/rfkill/core.c:rfkill_fop_open
```
**Symbols:**

```
ffffffff812c5a30-ffffffff812c5a4d: stream_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int stream_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d7440)
Location: fs/open.c:1259
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_open
  - fs/fuse/file.c:fuse_finish_open
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/evdev.c:evdev_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - net/rfkill/core.c:rfkill_fop_open
```
**Symbols:**

```
ffffffff812d7440-ffffffff812d745d: stream_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int stream_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8130d610)
Location: fs/open.c:1366
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_open
  - fs/pipe.c:fifo_open
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:create_pipe_files
  - fs/fuse/file.c:fuse_finish_open
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/evdev.c:evdev_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - net/socket.c:sock_alloc_file
  - net/rfkill/core.c:rfkill_fop_open
```
**Symbols:**

```
ffffffff8130d610-ffffffff8130d62d: stream_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int stream_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81319570)
Location: fs/open.c:1381
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_open
  - fs/pipe.c:fifo_open
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:create_pipe_files
  - fs/fuse/file.c:fuse_finish_open
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/evdev.c:evdev_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - net/socket.c:sock_alloc_file
  - net/rfkill/core.c:rfkill_fop_open
```
**Symbols:**

```
ffffffff81319570-ffffffff8131958d: stream_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int stream_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8131f740)
Location: fs/open.c:1403
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_open
  - fs/pipe.c:fifo_open
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:create_pipe_files
  - fs/fuse/file.c:fuse_finish_open
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_open
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/evdev.c:evdev_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - net/socket.c:sock_alloc_file
  - net/rfkill/core.c:rfkill_fop_open
```
**Symbols:**

```
ffffffff8131f740-ffffffff8131f75d: stream_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int stream_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8136cc10)
Location: fs/open.c:1421
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_open
  - fs/pipe.c:fifo_open
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:create_pipe_files
  - fs/fuse/file.c:fuse_finish_open
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_open
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/evdev.c:evdev_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - net/socket.c:sock_alloc_file
  - net/rfkill/core.c:rfkill_fop_open
```
**Symbols:**

```
ffffffff8136cc10-ffffffff8136cc2d: stream_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int stream_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff813eafb0)
Location: fs/open.c:1488
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_open
  - fs/pipe.c:fifo_open
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:create_pipe_files
  - fs/fuse/file.c:fuse_finish_open
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_open
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/evdev.c:evdev_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - net/socket.c:sock_alloc_file
  - net/rfkill/core.c:rfkill_fop_open
```
**Symbols:**

```
ffffffff813eafb0-ffffffff813eafd3: stream_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int stream_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814731f0)
Location: fs/open.c:1521
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_open
  - fs/pipe.c:fifo_open
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:create_pipe_files
  - fs/fuse/file.c:fuse_finish_open
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_open
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/evdev.c:evdev_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - net/socket.c:sock_alloc_file
  - net/rfkill/core.c:rfkill_fop_open
```
**Symbols:**

```
ffffffff814731f0-ffffffff81473213: stream_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int stream_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814a7960)
Location: fs/open.c:1617
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_open
  - fs/pipe.c:fifo_open
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:create_pipe_files
  - fs/fuse/file.c:fuse_finish_open
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_open
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/evdev.c:evdev_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - net/socket.c:sock_alloc_file
  - net/rfkill/core.c:rfkill_fop_open
```
**Symbols:**

```
ffffffff814a7960-ffffffff814a7983: stream_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int stream_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814d8990)
Location: fs/open.c:1635
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_open
  - fs/pipe.c:fifo_open
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:create_pipe_files
  - fs/fuse/file.c:fuse_finish_open
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/evdev.c:evdev_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - net/socket.c:sock_alloc_file
  - net/rfkill/core.c:rfkill_fop_open
```
**Symbols:**

```
ffffffff814d8990-ffffffff814d89b3: stream_open (STB_GLOBAL)
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
int stream_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffff80001037c780)
Location: fs/open.c:1259
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_finish_open
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/evdev.c:evdev_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - net/rfkill/core.c:rfkill_fop_open
```
**Symbols:**

```
ffff80001037c780-ffff80001037c7bc: stream_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int stream_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c05671d0)
Location: fs/open.c:1259
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_finish_open
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/evdev.c:evdev_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - net/rfkill/core.c:rfkill_fop_open
```
**Symbols:**

```
c05671d0-c0567200: stream_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int stream_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c000000000471910)
Location: fs/open.c:1259
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_finish_open
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/evdev.c:evdev_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - net/rfkill/core.c:rfkill_fop_open
```
**Symbols:**

```
c000000000471910-c000000000471934: stream_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int stream_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffe000252bc0)
Location: fs/open.c:1259
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_finish_open
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/evdev.c:evdev_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - net/rfkill/core.c:rfkill_fop_open
```
**Symbols:**

```
ffffffe000252bc0-ffffffe000252bf2: stream_open (STB_GLOBAL)
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
int stream_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812cfa20)
Location: fs/open.c:1259
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_open
  - fs/fuse/file.c:fuse_finish_open
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/evdev.c:evdev_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - net/rfkill/core.c:rfkill_fop_open
```
**Symbols:**

```
ffffffff812cfa20-ffffffff812cfa3d: stream_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int stream_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c06a0)
Location: fs/open.c:1259
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_open
  - fs/fuse/file.c:fuse_finish_open
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/evdev.c:evdev_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - net/rfkill/core.c:rfkill_fop_open
```
**Symbols:**

```
ffffffff812c06a0-ffffffff812c06bd: stream_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int stream_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812cd830)
Location: fs/open.c:1259
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_open
  - fs/fuse/file.c:fuse_finish_open
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/evdev.c:evdev_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - net/rfkill/core.c:rfkill_fop_open
```
**Symbols:**

```
ffffffff812cd830-ffffffff812cd84d: stream_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int stream_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812de640)
Location: fs/open.c:1259
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_open
  - fs/fuse/file.c:fuse_finish_open
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
  - drivers/input/mousedev.c:mousedev_open
  - drivers/input/evdev.c:evdev_open
  - drivers/input/misc/uinput.c:uinput_open
  - drivers/watchdog/watchdog_dev.c:watchdog_open
  - net/rfkill/core.c:rfkill_fop_open
```
**Symbols:**

```
ffffffff812de640-ffffffff812de65d: stream_open (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
