# Function: <code>atomic_or</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff810dbe18)
Location: arch/x86/include/asm/atomic.h:218
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:SyS_membarrier
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff810e4123)
Location: include/asm-generic/atomic-instrumented.h:160
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_global_expedited
  - kernel/sched/membarrier.c:membarrier_register_global_expedited
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
In kernel/sched/membarrier.c (ffffffff810ee8a3)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_global_expedited
  - kernel/sched/membarrier.c:membarrier_register_global_expedited
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff815508b5)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81551943)
Location: include/asm-generic/atomic-instrumented.h:177
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
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
In kernel/sched/membarrier.c (ffffffff810f56c6)
Location: include/asm-generic/atomic-instrumented.h:514
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_global_expedited
  - kernel/sched/membarrier.c:membarrier_register_global_expedited
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81580765)
Location: include/asm-generic/atomic-instrumented.h:514
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8158188a)
Location: include/asm-generic/atomic-instrumented.h:514
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
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
In kernel/sched/membarrier.c (ffffffff811016fd)
Location: include/asm-generic/atomic-instrumented.h:514
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_global_expedited
  - kernel/sched/membarrier.c:membarrier_register_global_expedited
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff815a2235)
Location: include/asm-generic/atomic-instrumented.h:514
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815a338a)
Location: include/asm-generic/atomic-instrumented.h:514
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
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
In kernel/sched/membarrier.c (ffffffff8110bf24)
Location: include/asm-generic/atomic-instrumented.h:515
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_global_expedited
  - kernel/sched/membarrier.c:membarrier_register_global_expedited
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8164b2f3)
Location: include/asm-generic/atomic-instrumented.h:515
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8164bf56)
Location: include/asm-generic/atomic-instrumented.h:515
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
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
In kernel/sched/membarrier.c (ffffffff8110904b)
Location: include/asm-generic/atomic-instrumented.h:515
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_global_expedited
  - kernel/sched/membarrier.c:membarrier_register_global_expedited
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8166fa83)
Location: include/asm-generic/atomic-instrumented.h:515
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff816702a6)
Location: include/asm-generic/atomic-instrumented.h:515
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
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
In kernel/sched/fair.c (ffffffff810f5a11)
Location: include/asm-generic/atomic-instrumented.h:515
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
```
```
In kernel/sched/membarrier.c (ffffffff8110acdb)
Location: include/asm-generic/atomic-instrumented.h:515
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_global_expedited
  - kernel/sched/membarrier.c:membarrier_register_global_expedited
```
```
In kernel/locking/qrwlock.c (ffffffff8110eec1)
Location: include/asm-generic/atomic-instrumented.h:515
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81651f83)
Location: include/asm-generic/atomic-instrumented.h:515
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff816527a6)
Location: include/asm-generic/atomic-instrumented.h:515
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
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
In kernel/sched/fair.c (ffffffff8110f52a)
Location: include/linux/atomic/atomic-instrumented.h:375
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
```
```
In kernel/sched/membarrier.c (ffffffff811294eb)
Location: include/linux/atomic/atomic-instrumented.h:375
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_global_expedited
  - kernel/sched/membarrier.c:membarrier_register_global_expedited
```
```
In kernel/locking/qrwlock.c (ffffffff8112e761)
Location: include/linux/atomic/atomic-instrumented.h:375
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff816c391e)
Location: include/linux/atomic/atomic-instrumented.h:375
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff816c4532)
Location: include/linux/atomic/atomic-instrumented.h:375
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
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
In kernel/sched/fair.c (ffffffff8112b6e5)
Location: include/linux/atomic/atomic-instrumented.h:396
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
```
```
In kernel/sched/build_utility.c (ffffffff8113df29)
Location: include/linux/atomic/atomic-instrumented.h:396
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:membarrier_register_private_expedited
  - kernel/sched/build_utility.c:membarrier_register_private_expedited
  - kernel/sched/build_utility.c:membarrier_register_global_expedited
  - kernel/sched/build_utility.c:membarrier_register_global_expedited
```
```
In kernel/locking/qrwlock.c (ffffffff8114fa88)
Location: include/linux/atomic/atomic-instrumented.h:396
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
```
```
In io_uring/io_uring.c (ffffffff816d93e4)
Location: include/linux/atomic/atomic-instrumented.h:396
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_sq_thread
  - io_uring/io_uring.c:io_sq_thread
  - io_uring/io_uring.c:io_poll_wake
  - io_uring/io_uring.c:io_poll_cancel_req
  - io_uring/io_uring.c:__io_req_task_work_add
  - io_uring/io_uring.c:io_cqring_event_overflow
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff817e938f)
Location: include/linux/atomic/atomic-instrumented.h:396
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff817ea128)
Location: include/linux/atomic/atomic-instrumented.h:396
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
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
In kernel/sched/fair.c (ffffffff811550b5)
Location: include/linux/atomic/atomic-instrumented.h:396
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
```
```
In kernel/sched/build_utility.c (ffffffff8116de59)
Location: include/linux/atomic/atomic-instrumented.h:396
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:membarrier_register_private_expedited
  - kernel/sched/build_utility.c:membarrier_register_private_expedited
  - kernel/sched/build_utility.c:membarrier_register_global_expedited
  - kernel/sched/build_utility.c:membarrier_register_global_expedited
```
```
In kernel/locking/qrwlock.c (ffffffff820d6de8)
Location: include/linux/atomic/atomic-instrumented.h:396
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
```
```
In io_uring/io_uring.c (ffffffff8178de36)
Location: include/linux/atomic/atomic-instrumented.h:396
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_req_task_work_add
  - io_uring/io_uring.c:__io_req_task_work_add
  - io_uring/io_uring.c:io_cqring_event_overflow
```
```
In io_uring/sqpoll.c (ffffffff8179a894)
Location: include/linux/atomic/atomic-instrumented.h:396
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread
  - io_uring/sqpoll.c:io_sq_thread
```
```
In io_uring/poll.c (ffffffff8179cc94)
Location: include/linux/atomic/atomic-instrumented.h:396
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_remove_all_table
  - io_uring/poll.c:__io_arm_poll_handler
  - io_uring/poll.c:io_poll_wake
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8190f02f)
Location: include/linux/atomic/atomic-instrumented.h:396
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff819101c4)
Location: include/linux/atomic/atomic-instrumented.h:396
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
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
In kernel/sched/fair.c (ffffffff81165261)
Location: include/linux/atomic/atomic-instrumented.h:932
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
```
```
In kernel/sched/build_utility.c (ffffffff8117e42e)
Location: include/linux/atomic/atomic-instrumented.h:932
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:membarrier_register_private_expedited
  - kernel/sched/build_utility.c:membarrier_register_private_expedited
  - kernel/sched/build_utility.c:membarrier_register_global_expedited
  - kernel/sched/build_utility.c:membarrier_register_global_expedited
```
```
In kernel/locking/qrwlock.c (ffffffff8215a178)
Location: include/linux/atomic/atomic-instrumented.h:932
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
```
```
In io_uring/io_uring.c (ffffffff817cbcd5)
Location: include/linux/atomic/atomic-instrumented.h:932
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_req_normal_work_add
  - io_uring/io_uring.c:io_cqring_event_overflow
```
```
In io_uring/sqpoll.c (ffffffff817db931)
Location: include/linux/atomic/atomic-instrumented.h:932
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread
  - io_uring/sqpoll.c:io_sq_thread
```
```
In io_uring/poll.c (ffffffff817ddec4)
Location: include/linux/atomic/atomic-instrumented.h:932
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_remove_all_table
  - io_uring/poll.c:__io_arm_poll_handler
  - io_uring/poll.c:io_poll_wake
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8195269f)
Location: include/linux/atomic/atomic-instrumented.h:932
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff819538e4)
Location: include/linux/atomic/atomic-instrumented.h:932
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
Location: include/linux/atomic/atomic-instrumented.h:932
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
```
```
In kernel/sched/build_utility.c (ffffffff8118fccd)
Location: include/linux/atomic/atomic-instrumented.h:932
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__do_sys_membarrier
  - kernel/sched/build_utility.c:__do_sys_membarrier
  - kernel/sched/build_utility.c:membarrier_register_private_expedited
  - kernel/sched/build_utility.c:membarrier_register_private_expedited
```
```
In kernel/locking/qrwlock.c (ffffffff8223d9f8)
Location: include/linux/atomic/atomic-instrumented.h:932
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
```
```
In io_uring/io_uring.c (ffffffff818101c5)
Location: include/linux/atomic/atomic-instrumented.h:932
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_req_normal_work_add
  - io_uring/io_uring.c:io_cqring_event_overflow
```
```
In io_uring/sqpoll.c (ffffffff8181fcaa)
Location: include/linux/atomic/atomic-instrumented.h:932
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread
  - io_uring/sqpoll.c:io_sq_thread
```
```
In io_uring/poll.c (ffffffff81822264)
Location: include/linux/atomic/atomic-instrumented.h:932
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_remove_all_table
  - io_uring/poll.c:__io_arm_poll_handler
  - io_uring/poll.c:io_poll_wake
```
```
In io_uring/waitid.c (ffffffff8182a853)
Location: include/linux/atomic/atomic-instrumented.h:932
Inline: True
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8199bb2f)
Location: include/linux/atomic/atomic-instrumented.h:932
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8199cd74)
Location: include/linux/atomic/atomic-instrumented.h:932
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffff800010166370)
Location: include/asm-generic/atomic-instrumented.h:514
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__arm64_sys_membarrier
  - kernel/sched/membarrier.c:__arm64_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffff80001070ab08)
Location: include/asm-generic/atomic-instrumented.h:514
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffff80001070beb8)
Location: include/asm-generic/atomic-instrumented.h:514
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
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
In kernel/sched/membarrier.c (c03b2864)
Location: arch/arm/include/asm/atomic.h:237
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__se_sys_membarrier
  - kernel/sched/membarrier.c:__se_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
```
```
In kernel/locking/mutex.c (c0e9b444)
Location: arch/arm/include/asm/atomic.h:237
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__mutex_add_waiter
```
```
In kernel/locking/rwsem.c (c03b6040)
Location: arch/arm/include/asm/atomic.h:237
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (c0000000001bdae0)
Location: arch/powerpc/include/asm/atomic.h:114
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__se_sys_membarrier
  - kernel/sched/membarrier.c:__se_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
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
In kernel/sched/membarrier.c (ffffffe00010873c)
Location: arch/riscv/include/asm/atomic.h:79
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__se_sys_membarrier
  - kernel/sched/membarrier.c:__se_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffe0004d8048)
Location: arch/riscv/include/asm/atomic.h:79
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffe0004d87d8)
Location: arch/riscv/include/asm/atomic.h:79
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
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
In kernel/sched/membarrier.c (ffffffff810faa0d)
Location: include/asm-generic/atomic-instrumented.h:514
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_global_expedited
  - kernel/sched/membarrier.c:membarrier_register_global_expedited
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81595a45)
Location: include/asm-generic/atomic-instrumented.h:514
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81596b9a)
Location: include/asm-generic/atomic-instrumented.h:514
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
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
In kernel/sched/membarrier.c (ffffffff810eabed)
Location: include/asm-generic/atomic-instrumented.h:514
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_global_expedited
  - kernel/sched/membarrier.c:membarrier_register_global_expedited
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81584bd5)
Location: include/asm-generic/atomic-instrumented.h:514
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81585d2a)
Location: include/asm-generic/atomic-instrumented.h:514
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
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
In kernel/sched/membarrier.c (ffffffff810f7bcd)
Location: include/asm-generic/atomic-instrumented.h:514
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_global_expedited
  - kernel/sched/membarrier.c:membarrier_register_global_expedited
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81595f85)
Location: include/asm-generic/atomic-instrumented.h:514
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815970da)
Location: include/asm-generic/atomic-instrumented.h:514
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
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
In kernel/sched/membarrier.c (ffffffff81102d0d)
Location: include/asm-generic/atomic-instrumented.h:514
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_global_expedited
  - kernel/sched/membarrier.c:membarrier_register_global_expedited
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff815b0405)
Location: include/asm-generic/atomic-instrumented.h:514
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815b151a)
Location: include/asm-generic/atomic-instrumented.h:514
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
</details>
</li>
</ul>

## Differences
