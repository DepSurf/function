# Function: <code>__hash_init</code>

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
In kernel/workqueue.c (ffffffff8109b5e4)
Location: include/linux/hashtable.h:29
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In block/elevator.c (ffffffff813b3d3b)
Location: include/linux/hashtable.h:29
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
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
In kernel/workqueue.c (ffffffff8109ebef)
Location: include/linux/hashtable.h:33
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In block/elevator.c (ffffffff813f793b)
Location: include/linux/hashtable.h:33
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
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
In kernel/workqueue.c (ffffffff810a3abf)
Location: include/linux/hashtable.h:33
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In block/elevator.c (ffffffff81411298)
Location: include/linux/hashtable.h:33
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In net/core/dev.c (ffffffff817b1a29)
Location: include/linux/hashtable.h:33
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
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
In kernel/workqueue.c (ffffffff810a0c39)
Location: include/linux/hashtable.h:33
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In block/elevator.c (ffffffff8141ed98)
Location: include/linux/hashtable.h:33
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In net/core/dev.c (ffffffff817cb799)
Location: include/linux/hashtable.h:33
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
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
In kernel/workqueue.c (ffffffff810a74b7)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In block/elevator.c (ffffffff81449878)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In net/core/dev.c (ffffffff81844fe6)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
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
In kernel/workqueue.c (ffffffff810ae040)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In block/elevator.c (ffffffff8147c20d)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In net/core/dev.c (ffffffff8189122f)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
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
In kernel/workqueue.c (ffffffff810b7170)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In block/elevator.c (ffffffff8149a32d)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In net/core/dev.c (ffffffff818b185f)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
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
In kernel/workqueue.c (ffffffff810ba700)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In security/safesetid/securityfs.c (ffffffff81499512)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
```
```
In block/elevator.c (ffffffff814c840e)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In net/core/dev.c (ffffffff818fe5ff)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
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
In kernel/workqueue.c (ffffffff810c3250)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In security/safesetid/securityfs.c (ffffffff814b3432)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
```
```
In block/elevator.c (ffffffff814e150e)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In net/core/dev.c (ffffffff8193093c)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
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
In kernel/workqueue.c (ffffffff810caced)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In fs/io_uring.c (ffffffff8137cda2)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_alloc
```
```
In security/selinux/ss/sidtab.c (ffffffff814c0285)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_init
```
```
In security/safesetid/securityfs.c (ffffffff81512989)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:handle_policy_update
```
```
In block/elevator.c (ffffffff8153ff3e)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In net/core/dev.c (ffffffff81a04585)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
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
In kernel/workqueue.c (ffffffff810c5e1d)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In fs/io_uring.c (ffffffff8138b582)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_alloc
```
```
In security/selinux/ss/sidtab.c (ffffffff814ddce5)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_init
```
```
In security/safesetid/securityfs.c (ffffffff8152faf3)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:handle_policy_update
```
```
In block/elevator.c (ffffffff8155c6de)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In net/core/dev.c (ffffffff81a065e5)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
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
In kernel/workqueue.c (ffffffff810c775d)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
```
```
In fs/io_uring.c (ffffffff8139276f)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_alloc
```
```
In security/selinux/ss/sidtab.c (ffffffff814e4668)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_init
```
```
In security/safesetid/securityfs.c (ffffffff81535b95)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:handle_policy_update
```
```
In block/elevator.c (ffffffff81564f6e)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In net/core/dev.c (ffffffff819ed135)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
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
In kernel/workqueue.c (ffffffff810da4bd)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
```
```
In fs/io_uring.c (ffffffff813e0a0e)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_alloc
```
```
In security/selinux/ss/sidtab.c (ffffffff8153dbfa)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_init
```
```
In security/safesetid/securityfs.c (ffffffff81594195)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:handle_policy_update
```
```
In block/elevator.c (ffffffff815c92ee)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In net/core/dev.c (ffffffff81a9e351)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
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
In kernel/workqueue.c (ffffffff810f3beb)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
```
```
In security/selinux/ss/sidtab.c (ffffffff815d55aa)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_init
```
```
In security/safesetid/securityfs.c (ffffffff816361e5)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:handle_policy_update
```
```
In block/elevator.c (ffffffff8167457d)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In io_uring/io_uring.c (ffffffff81e8edcc)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_ctx_alloc
```
```
In net/core/dev.c (ffffffff81c12b81)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
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
In kernel/workqueue.c (ffffffff81115e2b)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
```
```
In security/selinux/ss/sidtab.c (ffffffff816837ba)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_init
```
```
In security/safesetid/securityfs.c (ffffffff816ed1e5)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:handle_policy_update
```
```
In block/elevator.c (ffffffff817302ca)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In net/core/dev.c (ffffffff81dc2ca8)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
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
In kernel/workqueue.c (ffffffff81122b8e)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In kernel/trace/trace_events_user.c (ffffffff836dbcaf)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:trace_events_user_init
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
```
```
In security/selinux/ss/sidtab.c (ffffffff816bbaba)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_init
```
```
In security/safesetid/securityfs.c (ffffffff81727605)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:handle_policy_update
```
```
In block/elevator.c (ffffffff8176c4fa)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In net/core/dev.c (ffffffff81e32150)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
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
In kernel/workqueue.c (ffffffff8112cb69)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In kernel/trace/trace_events_user.c (ffffffff8390e2ad)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:trace_events_user_init
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
```
```
In security/selinux/ss/sidtab.c (ffffffff816f85ea)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_init
```
```
In security/safesetid/securityfs.c (ffffffff817688d2)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:handle_policy_update
```
```
In block/elevator.c (ffffffff817ae71d)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In net/core/dev.c (ffffffff81ef0610)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
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
In kernel/workqueue.c (ffff800010120fdc)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In security/safesetid/securityfs.c (ffff8000105ab144)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
```
```
In block/elevator.c (ffff8000105de0a4)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In net/core/dev.c (ffff800010bcc804)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
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
In kernel/workqueue.c (c0374f38)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In security/safesetid/securityfs.c (c075acdc)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
```
```
In block/elevator.c (c078b1d0)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In net/core/dev.c (c0ce6bf8)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
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
In kernel/workqueue.c (c00000000016a524)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In security/safesetid/securityfs.c (c000000000728e2c)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
```
```
In block/elevator.c (c000000000770514)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In net/core/dev.c (c000000000cabb68)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
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
In kernel/workqueue.c (ffffffe0000d9f36)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In security/safesetid/securityfs.c (ffffffe0003f3d34)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
```
```
In block/elevator.c (ffffffe000421102)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In net/core/dev.c (ffffffe00075827a)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
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
In kernel/workqueue.c (ffffffff810bd5c0)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In security/safesetid/securityfs.c (ffffffff814aba12)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
```
```
In block/elevator.c (ffffffff814d9aee)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In net/core/dev.c (ffffffff818d093c)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
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
In kernel/workqueue.c (ffffffff810abdf0)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In security/safesetid/securityfs.c (ffffffff8149c432)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
```
```
In block/elevator.c (ffffffff814ca49e)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In net/core/dev.c (ffffffff8188a81c)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
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
In kernel/workqueue.c (ffffffff810bcb20)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In security/safesetid/securityfs.c (ffffffff814a7ab2)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
```
```
In block/elevator.c (ffffffff814d5b7e)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In net/core/dev.c (ffffffff8192193c)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
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
In kernel/workqueue.c (ffffffff810c4ea0)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - kernel/workqueue.c:init_worker_pool
```
```
In security/safesetid/securityfs.c (ffffffff814c0442)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
```
```
In block/elevator.c (ffffffff814ee9ee)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In net/core/dev.c (ffffffff8194030c)
Location: include/linux/hashtable.h:34
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
```
</details>
</li>
</ul>

## Differences
