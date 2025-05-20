# Function: <code>vfs_poll</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812815f8)
Location: include/linux/poll.h:82
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff812b2977)
Location: include/linux/poll.h:82
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff812eaae0)
Location: include/linux/poll.h:82
Inline: True
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
In mm/memcontrol.c (ffffffff81296028)
Location: include/linux/poll.h:82
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff812c7a87)
Location: include/linux/poll.h:82
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff812ff690)
Location: include/linux/poll.h:82
Inline: True
```
```
In fs/aio.c (ffffffff813098a0)
Location: include/linux/poll.h:82
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_complete_work
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
In mm/memcontrol.c (ffffffff812b1ffb)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff812e46ee)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff81320842)
Location: include/linux/poll.h:86
Inline: True
```
```
In fs/aio.c (ffffffff8132aacd)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_complete_work
```
```
In fs/io_uring.c (ffffffff8132f479)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_poll_complete_work
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
In mm/memcontrol.c (ffffffff812c39a6)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff812f60b5)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff813335f2)
Location: include/linux/poll.h:86
Inline: True
```
```
In fs/aio.c (ffffffff8133dc6d)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_complete_work
```
```
In fs/io_uring.c (ffffffff81342b23)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_poll_complete_work
```
```
In drivers/vfio/virqfd.c (ffffffff817d2936)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
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
In mm/memcontrol.c (ffffffff812f95a1)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff8132dce1)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8136d87f)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_item_poll
```
```
In fs/aio.c (ffffffff81377dcc)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - fs/aio.c:aio_poll
  - fs/aio.c:aio_poll_complete_work
```
```
In fs/io_uring.c (ffffffff8137f1fa)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - fs/io_uring.c:__io_arm_poll_handler
  - fs/io_uring.c:io_poll_rewait
```
```
In drivers/vfio/virqfd.c (ffffffff8189da96)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
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
In mm/memcontrol.c (ffffffff81305c41)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff81339530)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8137ad33)
Location: include/linux/poll.h:86
Inline: True
```
```
In fs/aio.c (ffffffff81385abc)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - fs/aio.c:aio_poll
  - fs/aio.c:aio_poll_complete_work
```
```
In fs/io_uring.c (ffffffff8138d2d8)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - fs/io_uring.c:__io_arm_poll_handler
  - fs/io_uring.c:io_poll_rewait
```
```
In drivers/vfio/virqfd.c (ffffffff818ac6b6)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
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
In mm/memcontrol.c (ffffffff8130b0b4)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff8133fae4)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff813818a3)
Location: include/linux/poll.h:86
Inline: True
```
```
In fs/aio.c (ffffffff8138da5c)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_complete_work
```
```
In fs/io_uring.c (ffffffff81397a3f)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - fs/io_uring.c:__io_arm_poll_handler
  - fs/io_uring.c:io_poll_rewait
```
```
In drivers/vfio/virqfd.c (ffffffff8188f7d3)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
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
In mm/memcontrol.c (ffffffff81355934)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff8138d46a)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff813ceae3)
Location: include/linux/poll.h:86
Inline: True
```
```
In fs/aio.c (ffffffff813db12e)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_complete_work
```
```
In fs/io_uring.c (ffffffff813e464f)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - fs/io_uring.c:__io_arm_poll_handler
  - fs/io_uring.c:io_poll_rewait
```
```
In drivers/vfio/virqfd.c (ffffffff819230d3)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
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
In mm/memcontrol.c (ffffffff813ce36d)
Location: include/linux/poll.h:84
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff8140e7ba)
Location: include/linux/poll.h:84
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff81457d43)
Location: include/linux/poll.h:84
Inline: True
```
```
In fs/aio.c (ffffffff8146498e)
Location: include/linux/poll.h:84
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_complete_work
```
```
In io_uring/io_uring.c (ffffffff816ce871)
Location: include/linux/poll.h:84
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_arm_poll_handler
  - io_uring/io_uring.c:io_poll_check_events
```
```
In drivers/vfio/virqfd.c (ffffffff81a78af4)
Location: include/linux/poll.h:84
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
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
In mm/memcontrol.c (ffffffff8145390d)
Location: include/linux/poll.h:84
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff8149933c)
Location: include/linux/poll.h:84
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff814e7083)
Location: include/linux/poll.h:84
Inline: True
```
```
In fs/aio.c (ffffffff814f499e)
Location: include/linux/poll.h:84
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_complete_work
```
```
In io_uring/poll.c (ffffffff8179d400)
Location: include/linux/poll.h:84
Inline: True
Inline callers:
  - io_uring/poll.c:__io_arm_poll_handler
  - io_uring/poll.c:io_poll_check_events
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
In mm/memcontrol.c (ffffffff81489727)
Location: include/linux/poll.h:84
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff814ce3dc)
Location: include/linux/poll.h:84
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8151d8c6)
Location: include/linux/poll.h:84
Inline: True
```
```
In fs/aio.c (ffffffff8152b76e)
Location: include/linux/poll.h:84
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_complete_work
```
```
In io_uring/poll.c (ffffffff817de630)
Location: include/linux/poll.h:84
Inline: True
Inline callers:
  - io_uring/poll.c:__io_arm_poll_handler
  - io_uring/poll.c:io_poll_check_events
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
In mm/memcontrol.c (ffffffff814b8b86)
Location: include/linux/poll.h:84
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff81500d1c)
Location: include/linux/poll.h:84
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff81551ea6)
Location: include/linux/poll.h:84
Inline: True
```
```
In fs/aio.c (ffffffff8156064e)
Location: include/linux/poll.h:84
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_complete_work
```
```
In io_uring/poll.c (ffffffff81822a00)
Location: include/linux/poll.h:84
Inline: True
Inline callers:
  - io_uring/poll.c:__io_arm_poll_handler
  - io_uring/poll.c:io_poll_check_events
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
In virt/kvm/eventfd.c (ffff8000100c1320)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - virt/kvm/eventfd.c:kvm_irqfd_assign
```
```
In mm/memcontrol.c (ffff800010365024)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffff8000103a31e4)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffff8000103f0a50)
Location: include/linux/poll.h:86
Inline: True
```
```
In fs/aio.c (ffff8000103fdca0)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_complete_work
```
```
In fs/io_uring.c (ffff8000104045e8)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_poll_complete_work
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
In mm/memcontrol.c (c0557f60)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (c0585b34)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (c05c6924)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_item_poll
```
```
In fs/aio.c (c05d00b4)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_complete_work
```
```
In fs/io_uring.c (c05d3ee8)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_poll_complete_work
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
In mm/memcontrol.c (c000000000453770)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (c00000000049cf88)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (c0000000004f8810)
Location: include/linux/poll.h:86
Inline: True
```
```
In fs/aio.c (c000000000507140)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_complete_work
```
```
In fs/io_uring.c (c00000000050cbc4)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_poll_complete_work
```
```
In drivers/vfio/virqfd.c (c000000000ab1d2c)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
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
In mm/memcontrol.c (ffffffe000244b00)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffe00026b20c)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffe0002a355a)
Location: include/linux/poll.h:86
Inline: True
```
```
In fs/aio.c (ffffffe0002ab0dc)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_complete_work
```
```
In fs/io_uring.c (ffffffe0002aec94)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_poll_complete_work
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
In mm/memcontrol.c (ffffffff812bbf86)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff812ee695)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8132bbd2)
Location: include/linux/poll.h:86
Inline: True
```
```
In fs/aio.c (ffffffff8133624d)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_complete_work
```
```
In fs/io_uring.c (ffffffff8133b103)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_poll_complete_work
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
In mm/memcontrol.c (ffffffff812ad0e6)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff812df2c5)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8131c332)
Location: include/linux/poll.h:86
Inline: True
```
```
In fs/aio.c (ffffffff81326977)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_complete_work
```
```
In fs/io_uring.c (ffffffff8132bded)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_poll_complete_work
```
```
In drivers/vfio/virqfd.c (ffffffff8177c9da)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
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
In mm/memcontrol.c (ffffffff812b9d96)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff812ec4a5)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff813296a2)
Location: include/linux/poll.h:86
Inline: True
```
```
In fs/aio.c (ffffffff81333d1d)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_complete_work
```
```
In fs/io_uring.c (ffffffff81338bd3)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_poll_complete_work
```
```
In drivers/vfio/virqfd.c (ffffffff817c77b6)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
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
In mm/memcontrol.c (ffffffff812ca426)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff812fd4a5)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8133b002)
Location: include/linux/poll.h:86
Inline: True
```
```
In fs/aio.c (ffffffff81345384)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_complete_work
```
```
In fs/io_uring.c (ffffffff8134b420)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_poll_complete_work
```
```
In drivers/vfio/virqfd.c (ffffffff817e19db)
Location: include/linux/poll.h:86
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
```
</details>
</li>
</ul>

## Differences
