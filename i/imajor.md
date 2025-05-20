# Function: <code>imajor</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (0)
Location: include/linux/fs.h:776
Inline: True
```
```
In mm/page_io.c (0)
Location: include/linux/fs.h:776
Inline: True
```
```
In security/device_cgroup.c (0)
Location: include/linux/fs.h:776
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/fs.h:776
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/fs.h:776
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/fs.h:776
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/fs.h:776
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810d7601)
Location: include/linux/fs.h:838
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff811efb0d)
Location: include/linux/fs.h:838
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In security/device_cgroup.c (ffffffff813d140c)
Location: include/linux/fs.h:838
Inline: True
Inline callers:
  - security/device_cgroup.c:__devcgroup_inode_permission
```
```
In drivers/tty/tty_io.c (ffffffff81530ef2)
Location: include/linux/fs.h:838
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff8167b89c)
Location: include/linux/fs.h:838
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_open
```
```
In drivers/input/mousedev.c (ffffffff816cc785)
Location: include/linux/fs.h:838
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff816ec9c6)
Location: include/linux/fs.h:838
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810de17d)
Location: include/linux/fs.h:791
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff812004ad)
Location: include/linux/fs.h:791
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In security/device_cgroup.c (ffffffff813e8b3c)
Location: include/linux/fs.h:791
Inline: True
Inline callers:
  - security/device_cgroup.c:__devcgroup_inode_permission
```
```
In drivers/tty/tty_io.c (ffffffff8155d642)
Location: include/linux/fs.h:791
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff816a955c)
Location: include/linux/fs.h:791
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_open
```
```
In drivers/input/mousedev.c (ffffffff816fa725)
Location: include/linux/fs.h:791
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8171da66)
Location: include/linux/fs.h:791
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810dd28c)
Location: include/linux/fs.h:810
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff8120b105)
Location: include/linux/fs.h:810
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In security/device_cgroup.c (ffffffff813f4ed8)
Location: include/linux/fs.h:810
Inline: True
Inline callers:
  - security/device_cgroup.c:__devcgroup_inode_permission
```
```
In drivers/tty/tty_io.c (ffffffff81572532)
Location: include/linux/fs.h:810
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff816be80b)
Location: include/linux/fs.h:810
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_open
```
```
In drivers/input/mousedev.c (ffffffff817101b5)
Location: include/linux/fs.h:810
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81735916)
Location: include/linux/fs.h:810
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8127f07e)
Location: include/linux/fs.h:814
Inline: True
```
```
In fs/block_dev.c (ffffffff812b4e89)
Location: include/linux/fs.h:814
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In drivers/tty/tty_io.c (ffffffff815d68b2)
Location: include/linux/fs.h:814
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff8172a1db)
Location: include/linux/fs.h:814
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_open
```
```
In drivers/input/mousedev.c (ffffffff81781435)
Location: include/linux/fs.h:814
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff817a7646)
Location: include/linux/fs.h:814
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812a7a95)
Location: include/linux/fs.h:821
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/block_dev.c (ffffffff812dd023)
Location: include/linux/fs.h:821
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In drivers/tty/tty_io.c (ffffffff8161306d)
Location: include/linux/fs.h:821
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff81768aeb)
Location: include/linux/fs.h:821
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_open
```
```
In drivers/input/mousedev.c (ffffffff817c2645)
Location: include/linux/fs.h:821
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff817ef085)
Location: include/linux/fs.h:821
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812bcb35)
Location: include/linux/fs.h:869
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/block_dev.c (ffffffff812f2483)
Location: include/linux/fs.h:869
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In drivers/tty/tty_io.c (ffffffff8163010d)
Location: include/linux/fs.h:869
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff8178babb)
Location: include/linux/fs.h:869
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_open
```
```
In drivers/input/mousedev.c (ffffffff817ea155)
Location: include/linux/fs.h:869
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8181af55)
Location: include/linux/fs.h:869
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d9642)
Location: include/linux/fs.h:884
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/block_dev.c (ffffffff81313eb6)
Location: include/linux/fs.h:884
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In drivers/tty/tty_io.c (ffffffff81664039)
Location: include/linux/fs.h:884
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff817cb2b1)
Location: include/linux/fs.h:884
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_open
```
```
In drivers/input/mousedev.c (ffffffff8182a745)
Location: include/linux/fs.h:884
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8185d195)
Location: include/linux/fs.h:884
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812eb152)
Location: include/linux/fs.h:898
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/block_dev.c (ffffffff81327696)
Location: include/linux/fs.h:898
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In drivers/tty/tty_io.c (ffffffff816866a9)
Location: include/linux/fs.h:898
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff817fc160)
Location: include/linux/fs.h:898
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_open
```
```
In drivers/input/mousedev.c (ffffffff8185c0d5)
Location: include/linux/fs.h:898
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8188ef85)
Location: include/linux/fs.h:898
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81323741)
Location: include/linux/fs.h:916
Inline: True
```
```
In fs/block_dev.c (ffffffff8136098b)
Location: include/linux/fs.h:916
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In drivers/tty/tty_io.c (ffffffff81738798)
Location: include/linux/fs.h:916
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_poll
```
```
In drivers/usb/core/devio.c (ffffffff818cd8ed)
Location: include/linux/fs.h:916
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_open
```
```
In drivers/input/mousedev.c (ffffffff8192e9f5)
Location: include/linux/fs.h:916
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8195dc35)
Location: include/linux/fs.h:916
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8132ece1)
Location: include/linux/fs.h:879
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81c07660)
Location: include/linux/fs.h:879
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_poll
```
```
In drivers/usb/core/devio.c (ffffffff818d841d)
Location: include/linux/fs.h:879
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_open
```
```
In drivers/input/mousedev.c (ffffffff81935d95)
Location: include/linux/fs.h:879
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81964625)
Location: include/linux/fs.h:879
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81334ab2)
Location: include/linux/fs.h:880
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81bf91cc)
Location: include/linux/fs.h:880
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_poll
```
```
In drivers/block/loop.c (ffffffff817e2fc6)
Location: include/linux/fs.h:880
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
  - drivers/block/loop.c:loop_validate_file
```
```
In drivers/usb/core/devio.c (ffffffff818bb4bd)
Location: include/linux/fs.h:880
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_open
```
```
In drivers/input/mousedev.c (ffffffff81919d55)
Location: include/linux/fs.h:880
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81948a45)
Location: include/linux/fs.h:880
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813823f2)
Location: include/linux/fs.h:925
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81cf8969)
Location: include/linux/fs.h:925
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_poll
```
```
In drivers/block/loop.c (ffffffff8186e13d)
Location: include/linux/fs.h:925
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
  - drivers/block/loop.c:loop_validate_file
```
```
In drivers/usb/core/devio.c (ffffffff81951abd)
Location: include/linux/fs.h:925
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_open
```
```
In drivers/input/mousedev.c (ffffffff819bc155)
Location: include/linux/fs.h:925
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff819eda45)
Location: include/linux/fs.h:925
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81401902)
Location: include/linux/fs.h:880
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81ec0a14)
Location: include/linux/fs.h:880
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_poll
```
```
In drivers/block/loop.c (ffffffff819b7d21)
Location: include/linux/fs.h:880
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
  - drivers/block/loop.c:loop_validate_file
```
```
In drivers/usb/core/devio.c (ffffffff81aa97cd)
Location: include/linux/fs.h:880
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_open
```
```
In drivers/input/mousedev.c (ffffffff81b1bdf5)
Location: include/linux/fs.h:880
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81b54365)
Location: include/linux/fs.h:880
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8148ba02)
Location: include/linux/fs.h:895
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81a4b6ce)
Location: include/linux/fs.h:895
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_read
```
```
In drivers/block/loop.c (ffffffff81b2d061)
Location: include/linux/fs.h:895
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
  - drivers/block/loop.c:loop_validate_file
```
```
In drivers/usb/core/devio.c (ffffffff81c30aed)
Location: include/linux/fs.h:895
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_open
```
```
In drivers/input/mousedev.c (ffffffff81cadc35)
Location: include/linux/fs.h:895
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81ced0e5)
Location: include/linux/fs.h:895
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814bfa57)
Location: include/linux/fs.h:910
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81a957d6)
Location: include/linux/fs.h:910
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_read
```
```
In drivers/block/loop.c (ffffffff81b7d2e9)
Location: include/linux/fs.h:910
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
  - drivers/block/loop.c:loop_validate_file
```
```
In drivers/usb/core/devio.c (ffffffff81c97d7d)
Location: include/linux/fs.h:910
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_open
```
```
In drivers/input/mousedev.c (ffffffff81d15225)
Location: include/linux/fs.h:910
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81d55e25)
Location: include/linux/fs.h:910
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f1f47)
Location: include/linux/fs.h:943
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81ae8236)
Location: include/linux/fs.h:943
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_read
```
```
In drivers/block/loop.c (ffffffff81bd1271)
Location: include/linux/fs.h:943
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
  - drivers/block/loop.c:loop_validate_file
```
```
In drivers/usb/core/devio.c (ffffffff81d4c88a)
Location: include/linux/fs.h:943
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_open
```
```
In drivers/input/mousedev.c (ffffffff81dcae45)
Location: include/linux/fs.h:943
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81e0cd35)
Location: include/linux/fs.h:943
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff80001039482c)
Location: include/linux/fs.h:898
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/block_dev.c (ffff8000103e25ec)
Location: include/linux/fs.h:898
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In drivers/tty/tty_io.c (ffff80001084f060)
Location: include/linux/fs.h:898
Inline: True
```
```
In drivers/usb/core/devio.c (ffff800010a2f5f4)
Location: include/linux/fs.h:898
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_open
```
```
In drivers/input/mousedev.c (ffff800010a9c584)
Location: include/linux/fs.h:898
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/watchdog/watchdog_dev.c (ffff800010adfed8)
Location: include/linux/fs.h:898
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (c0579d18)
Location: include/linux/fs.h:898
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/block_dev.c (c05ba7e0)
Location: include/linux/fs.h:898
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In drivers/tty/tty_io.c (c095b25c)
Location: include/linux/fs.h:898
Inline: True
```
```
In drivers/usb/core/devio.c (c0b01d04)
Location: include/linux/fs.h:898
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_open
```
```
In drivers/input/mousedev.c (c0b7e454)
Location: include/linux/fs.h:898
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/watchdog/watchdog_dev.c (c0bc181c)
Location: include/linux/fs.h:898
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In sound/core/pcm_native.c (c0c95b24)
Location: include/linux/fs.h:898
Inline: True
Inline callers:
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
```
```
In sound/core/compress_offload.c (c0c9d318)
Location: include/linux/fs.h:898
Inline: True
Inline callers:
  - sound/core/compress_offload.c:snd_compr_open
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (c00000000048b248)
Location: include/linux/fs.h:898
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/block_dev.c (c0000000004e82d0)
Location: include/linux/fs.h:898
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In drivers/tty/tty_io.c (c0000000008ee4d4)
Location: include/linux/fs.h:898
Inline: True
```
```
In drivers/usb/core/devio.c (c000000000aeb930)
Location: include/linux/fs.h:898
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_open
```
```
In drivers/input/mousedev.c (c000000000b7d420)
Location: include/linux/fs.h:898
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/watchdog/watchdog_dev.c (c000000000bc8058)
Location: include/linux/fs.h:898
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe0002632e0)
Location: include/linux/fs.h:898
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/block_dev.c (ffffffe000298b72)
Location: include/linux/fs.h:898
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In drivers/tty/tty_io.c (ffffffe00052d6a0)
Location: include/linux/fs.h:898
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffe00064d8e6)
Location: include/linux/fs.h:898
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_open
```
```
In drivers/input/mousedev.c (ffffffe0006acd36)
Location: include/linux/fs.h:898
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/watchdog/watchdog_dev.c (ffffffe0006d794e)
Location: include/linux/fs.h:898
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e3732)
Location: include/linux/fs.h:898
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/block_dev.c (ffffffff8131fc76)
Location: include/linux/fs.h:898
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In drivers/tty/tty_io.c (ffffffff8164c129)
Location: include/linux/fs.h:898
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff817b4540)
Location: include/linux/fs.h:898
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_open
```
```
In drivers/input/mousedev.c (ffffffff818110e5)
Location: include/linux/fs.h:898
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81834e05)
Location: include/linux/fs.h:898
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d4372)
Location: include/linux/fs.h:898
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/block_dev.c (ffffffff81310816)
Location: include/linux/fs.h:898
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In drivers/tty/tty_io.c (ffffffff8162c579)
Location: include/linux/fs.h:898
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff817a5f70)
Location: include/linux/fs.h:898
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_open
```
```
In drivers/input/mousedev.c (ffffffff817d8825)
Location: include/linux/fs.h:898
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff817fc495)
Location: include/linux/fs.h:898
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e1542)
Location: include/linux/fs.h:898
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/block_dev.c (ffffffff8131d746)
Location: include/linux/fs.h:898
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In drivers/tty/tty_io.c (ffffffff8167a4e9)
Location: include/linux/fs.h:898
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff817f0fe0)
Location: include/linux/fs.h:898
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_open
```
```
In drivers/input/mousedev.c (ffffffff81850265)
Location: include/linux/fs.h:898
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81884435)
Location: include/linux/fs.h:898
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f0b22)
Location: include/linux/fs.h:898
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/block_dev.c (ffffffff8132f446)
Location: include/linux/fs.h:898
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In drivers/tty/tty_io.c (ffffffff81694b91)
Location: include/linux/fs.h:898
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff8180b220)
Location: include/linux/fs.h:898
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_open
```
```
In drivers/input/mousedev.c (ffffffff8186af85)
Location: include/linux/fs.h:898
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8189fef5)
Location: include/linux/fs.h:898
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
</details>
</li>
</ul>

## Differences
