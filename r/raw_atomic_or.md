# Function: <code>raw_atomic_or</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81165261)
Location: include/linux/atomic/atomic-arch-fallback.h:1661
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
```
```
In kernel/sched/build_utility.c (ffffffff8117e42e)
Location: include/linux/atomic/atomic-arch-fallback.h:1661
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:membarrier_register_private_expedited
  - kernel/sched/build_utility.c:membarrier_register_private_expedited
  - kernel/sched/build_utility.c:membarrier_register_global_expedited
  - kernel/sched/build_utility.c:membarrier_register_global_expedited
```
```
In kernel/locking/qrwlock.c (ffffffff8215a178)
Location: include/linux/atomic/atomic-arch-fallback.h:1661
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
```
```
In io_uring/io_uring.c (ffffffff817cbcd5)
Location: include/linux/atomic/atomic-arch-fallback.h:1661
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_req_normal_work_add
  - io_uring/io_uring.c:io_cqring_event_overflow
```
```
In io_uring/sqpoll.c (ffffffff817db931)
Location: include/linux/atomic/atomic-arch-fallback.h:1661
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread
  - io_uring/sqpoll.c:io_sq_thread
```
```
In io_uring/poll.c (ffffffff817ddec4)
Location: include/linux/atomic/atomic-arch-fallback.h:1661
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_remove_all_table
  - io_uring/poll.c:__io_arm_poll_handler
  - io_uring/poll.c:io_poll_wake
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8195269f)
Location: include/linux/atomic/atomic-arch-fallback.h:1661
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff819538e4)
Location: include/linux/atomic/atomic-arch-fallback.h:1661
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
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
In kernel/sched/fair.c (ffffffff81171fb1)
Location: include/linux/atomic/atomic-arch-fallback.h:1670
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
```
```
In kernel/sched/build_utility.c (ffffffff8118fccd)
Location: include/linux/atomic/atomic-arch-fallback.h:1670
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__do_sys_membarrier
  - kernel/sched/build_utility.c:__do_sys_membarrier
  - kernel/sched/build_utility.c:membarrier_register_private_expedited
  - kernel/sched/build_utility.c:membarrier_register_private_expedited
```
```
In kernel/locking/qrwlock.c (ffffffff8223d9f8)
Location: include/linux/atomic/atomic-arch-fallback.h:1670
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
```
```
In io_uring/io_uring.c (ffffffff818101c5)
Location: include/linux/atomic/atomic-arch-fallback.h:1670
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_req_normal_work_add
  - io_uring/io_uring.c:io_cqring_event_overflow
```
```
In io_uring/sqpoll.c (ffffffff8181fcaa)
Location: include/linux/atomic/atomic-arch-fallback.h:1670
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread
  - io_uring/sqpoll.c:io_sq_thread
```
```
In io_uring/poll.c (ffffffff81822264)
Location: include/linux/atomic/atomic-arch-fallback.h:1670
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_remove_all_table
  - io_uring/poll.c:__io_arm_poll_handler
  - io_uring/poll.c:io_poll_wake
```
```
In io_uring/waitid.c (ffffffff8182a853)
Location: include/linux/atomic/atomic-arch-fallback.h:1670
Inline: True
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8199bb2f)
Location: include/linux/atomic/atomic-arch-fallback.h:1670
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8199cd74)
Location: include/linux/atomic/atomic-arch-fallback.h:1670
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
