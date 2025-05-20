# Function: <code>init_waitqueue_func_entry</code>

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
In kernel/exit.c (ffffffff81083437)
Location: include/linux/wait.h:98
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In mm/memcontrol.c (ffffffff811fc35c)
Location: include/linux/wait.h:98
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff81220af3)
Location: include/linux/wait.h:98
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/eventpoll.c (ffffffff812547b1)
Location: include/linux/wait.h:98
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_ptable_queue_proc
```
```
In fs/userfaultfd.c (ffffffff8125acd0)
Location: include/linux/wait.h:98
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In net/unix/af_unix.c (ffffffff817be041)
Location: include/linux/wait.h:98
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
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
In kernel/exit.c (ffffffff810864c7)
Location: include/linux/wait.h:98
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In mm/memcontrol.c (ffffffff8121f68c)
Location: include/linux/wait.h:98
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff81248743)
Location: include/linux/wait.h:98
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/eventpoll.c (ffffffff8127cfe5)
Location: include/linux/wait.h:98
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_ptable_queue_proc
```
```
In fs/userfaultfd.c (ffffffff81283896)
Location: include/linux/wait.h:98
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In net/unix/af_unix.c (ffffffff8182afcb)
Location: include/linux/wait.h:98
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
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
In kernel/exit.c (ffffffff8108b437)
Location: include/linux/wait.h:98
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In mm/memcontrol.c (ffffffff81231cfc)
Location: include/linux/wait.h:98
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff8125b773)
Location: include/linux/wait.h:98
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/eventpoll.c (ffffffff81290b85)
Location: include/linux/wait.h:98
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_ptable_queue_proc
```
```
In fs/userfaultfd.c (ffffffff812973b1)
Location: include/linux/wait.h:98
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In net/unix/af_unix.c (ffffffff8185c9fb)
Location: include/linux/wait.h:98
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
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
In kernel/exit.c (ffffffff810881b7)
Location: include/linux/wait.h:85
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In mm/memcontrol.c (ffffffff8123de6a)
Location: include/linux/wait.h:85
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff81268606)
Location: include/linux/wait.h:85
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/eventpoll.c (ffffffff8129da23)
Location: include/linux/wait.h:85
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_ptable_queue_proc
```
```
In fs/userfaultfd.c (ffffffff812a4bbe)
Location: include/linux/wait.h:85
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In block/blk-mq.c (ffffffff8143196a)
Location: include/linux/wait.h:85
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In net/unix/af_unix.c (ffffffff81881189)
Location: include/linux/wait.h:85
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
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
In kernel/exit.c (ffffffff8108ef37)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In mm/memcontrol.c (ffffffff8125d9fa)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff8128aeb6)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/eventpoll.c (ffffffff812c0da3)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_ptable_queue_proc
```
```
In fs/userfaultfd.c (ffffffff812c8026)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In block/blk-mq.c (ffffffff8145dd33)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
```
In net/unix/af_unix.c (ffffffff81902319)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
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
In kernel/exit.c (ffffffff81092a64)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In mm/memcontrol.c (ffffffff812813b3)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff812b16ae)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/eventpoll.c (ffffffff812e9cd7)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_ptable_queue_proc
```
```
In fs/userfaultfd.c (ffffffff812f1345)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In block/blk-mq.c (ffffffff814917ed)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
```
In net/unix/af_unix.c (ffffffff81959c66)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
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
In kernel/exit.c (ffffffff8109ad54)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In mm/memcontrol.c (ffffffff81295de3)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff812c68fe)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/eventpoll.c (ffffffff812fe867)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_ptable_queue_proc
```
```
In fs/userfaultfd.c (ffffffff81305d05)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff813098a0)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
```
```
In block/blk-mq.c (ffffffff814ab270)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
```
In net/unix/af_unix.c (ffffffff8198e7e7)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
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
In kernel/exit.c (ffffffff8109f3be)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In mm/memcontrol.c (ffffffff812b1e26)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff812e33cc)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/eventpoll.c (ffffffff8131fa12)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_ptable_queue_proc
```
```
In fs/userfaultfd.c (ffffffff81327288)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff8132b2a2)
Location: include/linux/wait.h:87
Inline: True
```
```
In fs/io_uring.c (ffffffff8132f479)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
```
```
In block/blk-mq.c (ffffffff814d960c)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
```
In net/unix/af_unix.c (ffffffff819f9f46)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
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
In kernel/exit.c (ffffffff810a594e)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In mm/memcontrol.c (ffffffff812c37c6)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff812f4e5c)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/eventpoll.c (ffffffff813327c2)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_ptable_queue_proc
```
```
In fs/userfaultfd.c (ffffffff8133a068)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff8133e0f2)
Location: include/linux/wait.h:87
Inline: True
```
```
In fs/io_uring.c (ffffffff81342af9)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
```
```
In block/blk-mq.c (ffffffff814f29cc)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
```
In block/blk-iocost.c (ffffffff815137c1)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/vfio/virqfd.c (ffffffff817d290a)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
```
```
In net/unix/af_unix.c (ffffffff81a30bc6)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
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
In kernel/exit.c (ffffffff810ad479)
Location: include/linux/wait.h:88
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In mm/memcontrol.c (ffffffff812f9446)
Location: include/linux/wait.h:88
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff8132d4ac)
Location: include/linux/wait.h:88
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/eventpoll.c (ffffffff8136ca62)
Location: include/linux/wait.h:88
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_ptable_queue_proc
```
```
In fs/userfaultfd.c (ffffffff81374246)
Location: include/linux/wait.h:88
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff81377dcc)
Location: include/linux/wait.h:88
Inline: True
Inline callers:
  - fs/aio.c:aio_poll
```
```
In fs/io_uring.c (ffffffff813802a9)
Location: include/linux/wait.h:88
Inline: True
Inline callers:
  - fs/io_uring.c:io_poll_queue_proc
  - fs/io_uring.c:__io_arm_poll_handler
  - fs/io_uring.c:io_async_queue_proc
```
```
In block/blk-mq.c (ffffffff815517a7)
Location: include/linux/wait.h:88
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
```
```
In block/blk-iocost.c (ffffffff81574b42)
Location: include/linux/wait.h:88
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/vfio/virqfd.c (ffffffff8189da6a)
Location: include/linux/wait.h:88
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
```
```
In net/unix/af_unix.c (ffffffff81b24df6)
Location: include/linux/wait.h:88
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
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
In kernel/exit.c (ffffffff810a8b49)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In mm/memcontrol.c (ffffffff81305ae6)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff81338c4c)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/eventpoll.c (ffffffff8137a513)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_ptable_queue_proc
```
```
In fs/userfaultfd.c (ffffffff81382244)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff81385abc)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - fs/aio.c:aio_poll
```
```
In fs/io_uring.c (ffffffff8138d2b0)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - fs/io_uring.c:__io_arm_poll_handler
  - fs/io_uring.c:__io_queue_proc
```
```
In block/blk-mq.c (ffffffff8156d8f3)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
```
```
In block/blk-iocost.c (ffffffff81591923)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/vfio/virqfd.c (ffffffff818ac68a)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
```
```
In net/unix/af_unix.c (ffffffff81b33986)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
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
In kernel/exit.c (ffffffff810a9b49)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In mm/memcontrol.c (ffffffff8130af86)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff8133f2dc)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/eventpoll.c (ffffffff81381183)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_ptable_queue_proc
```
```
In fs/userfaultfd.c (ffffffff813892be)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff8138cbf5)
Location: include/linux/wait.h:90
Inline: True
```
```
In fs/io_uring.c (ffffffff81397a17)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - fs/io_uring.c:__io_arm_poll_handler
  - fs/io_uring.c:__io_queue_proc
```
```
In block/blk-mq.c (ffffffff815748dd)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
```
```
In block/blk-iocost.c (ffffffff81598782)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/vfio/virqfd.c (ffffffff8188f7a7)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
```
```
In net/unix/af_unix.c (ffffffff81b21387)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
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
In kernel/exit.c (ffffffff810bb679)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In mm/memcontrol.c (ffffffff81355806)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff8138cc6c)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/eventpoll.c (ffffffff813ce3c3)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_ptable_queue_proc
```
```
In fs/userfaultfd.c (ffffffff813d6595)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff813da2e3)
Location: include/linux/wait.h:90
Inline: True
```
```
In fs/io_uring.c (ffffffff813e5787)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:__io_arm_poll_handler
  - fs/io_uring.c:__io_queue_proc
```
```
In block/blk-mq.c (ffffffff815d8dfd)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
```
```
In block/blk-iocost.c (ffffffff815fff5a)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/vfio/virqfd.c (ffffffff819230a7)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
```
```
In net/unix/af_unix.c (ffffffff81be6463)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
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
In kernel/exit.c (ffffffff810d20b9)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In mm/memcontrol.c (ffffffff813ce184)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff8140df4c)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/eventpoll.c (ffffffff81457403)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_ptable_queue_proc
```
```
In fs/userfaultfd.c (ffffffff8145ff31)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff81464cbc)
Location: include/linux/wait.h:90
Inline: True
```
```
In block/blk-mq.c (ffffffff8168686a)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
```
```
In block/blk-iocost.c (ffffffff816b25ec)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In io_uring/io_uring.c (ffffffff816cf7e4)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:__io_arm_poll_handler
  - io_uring/io_uring.c:__io_queue_proc
```
```
In drivers/vfio/virqfd.c (ffffffff81a78ac4)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
```
```
In net/unix/af_unix.c (ffffffff81d7eec1)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
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
In kernel/exit.c (ffffffff810f0b2d)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In mm/memcontrol.c (ffffffff814536b4)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff81498a7c)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/eventpoll.c (ffffffff814e6663)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_ptable_queue_proc
```
```
In fs/userfaultfd.c (ffffffff814efd98)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff814f4cdc)
Location: include/linux/wait.h:90
Inline: True
```
```
In block/blk-mq.c (ffffffff8174512a)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
```
```
In block/blk-iocost.c (ffffffff81771b31)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In io_uring/io_uring.c (ffffffff81791c47)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_cqring_wait
```
```
In io_uring/poll.c (ffffffff8179d3b1)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - io_uring/poll.c:__io_arm_poll_handler
  - io_uring/poll.c:__io_queue_proc
```
```
In net/unix/af_unix.c (ffffffff81f4c24e)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
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
In kernel/exit.c (ffffffff810fcab2)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In mm/memcontrol.c (ffffffff814894c4)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff814cdb1c)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/eventpoll.c (ffffffff8151d1c8)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_ptable_queue_proc
```
```
In fs/userfaultfd.c (ffffffff81526b3b)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff8152baaa)
Location: include/linux/wait.h:90
Inline: True
```
```
In block/blk-mq.c (ffffffff8178109a)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
```
```
In block/blk-iocost.c (ffffffff817b0df0)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In io_uring/io_uring.c (ffffffff817d0d02)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_cqring_wait
```
```
In io_uring/poll.c (ffffffff817de5e1)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - io_uring/poll.c:__io_arm_poll_handler
  - io_uring/poll.c:__io_queue_proc
```
```
In net/unix/af_unix.c (ffffffff81fac02e)
Location: include/linux/wait.h:90
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
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
In kernel/exit.c (ffffffff811071aa)
Location: include/linux/wait.h:88
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In mm/memcontrol.c (ffffffff814b8923)
Location: include/linux/wait.h:88
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff8150045c)
Location: include/linux/wait.h:88
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/eventpoll.c (ffffffff815517a8)
Location: include/linux/wait.h:88
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_ptable_queue_proc
```
```
In fs/userfaultfd.c (ffffffff8155b8c7)
Location: include/linux/wait.h:88
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff8156098a)
Location: include/linux/wait.h:88
Inline: True
```
```
In block/blk-mq.c (ffffffff817c38fc)
Location: include/linux/wait.h:88
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
```
```
In block/blk-iocost.c (ffffffff817f4c00)
Location: include/linux/wait.h:88
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In io_uring/io_uring.c (ffffffff8181385c)
Location: include/linux/wait.h:88
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_cqring_wait
```
```
In io_uring/poll.c (ffffffff818229b1)
Location: include/linux/wait.h:88
Inline: True
Inline callers:
  - io_uring/poll.c:__io_arm_poll_handler
  - io_uring/poll.c:__io_queue_proc
```
```
In io_uring/waitid.c (ffffffff8182accb)
Location: include/linux/wait.h:88
Inline: True
Inline callers:
  - io_uring/waitid.c:io_waitid
```
```
In net/unix/af_unix.c (ffffffff8207944e)
Location: include/linux/wait.h:88
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
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
In virt/kvm/eventfd.c (ffff8000100c124c)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - virt/kvm/eventfd.c:kvm_irqfd_assign
```
```
In kernel/exit.c (ffff8000100fb96c)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In mm/memcontrol.c (ffff800010364e88)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffff8000103a1e8c)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/eventpoll.c (ffff8000103effe0)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_ptable_queue_proc
```
```
In fs/userfaultfd.c (ffff8000103f92c0)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffff8000103fdca0)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
```
```
In fs/io_uring.c (ffff8000104045e8)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
```
```
In block/blk-mq.c (ffff8000105f21c0)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
```
In block/blk-iocost.c (ffff800010617cf4)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In net/unix/af_unix.c (ffff800010cf0e90)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
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
In kernel/exit.c (c0359918)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In mm/memcontrol.c (c0557dd4)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (c0584bb0)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/eventpoll.c (c05c6064)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_ptable_queue_proc
```
```
In fs/userfaultfd.c (c05cd1c8)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (c05cf2e8)
Location: include/linux/wait.h:87
Inline: True
```
```
In fs/io_uring.c (c05d3ee0)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
```
```
In block/blk-mq.c (c079e314)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
```
In block/blk-iocost.c (c07c3048)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In net/unix/af_unix.c (c0df7958)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
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
In kernel/exit.c (c000000000142f6c)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In mm/memcontrol.c (c000000000453334)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (c00000000049b988)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/eventpoll.c (c0000000004f7ad8)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_ptable_queue_proc
```
```
In fs/userfaultfd.c (c0000000005014fc)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (c000000000507140)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
```
```
In fs/io_uring.c (c00000000050cbc4)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
```
```
In block/blk-mq.c (c000000000789304)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
```
In block/blk-iocost.c (c0000000007b73f4)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/vfio/virqfd.c (c000000000ab1d00)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
```
```
In net/unix/af_unix.c (c000000000e14834)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
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
In kernel/exit.c (ffffffe0000c54b0)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In mm/memcontrol.c (ffffffe000244992)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffe00026a714)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/eventpoll.c (ffffffe0002a2e50)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_ptable_queue_proc
```
```
In fs/userfaultfd.c (ffffffe0002a8638)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffe0002ab4ee)
Location: include/linux/wait.h:87
Inline: True
```
```
In fs/io_uring.c (ffffffe0002aec5e)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
```
```
In block/blk-mq.c (ffffffe000430af0)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
```
In block/blk-iocost.c (ffffffe00044e268)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In net/unix/af_unix.c (ffffffe00083d1e6)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
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
In kernel/exit.c (ffffffff8109f26e)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In mm/memcontrol.c (ffffffff812bbda6)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff812ed43c)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/eventpoll.c (ffffffff8132ada2)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_ptable_queue_proc
```
```
In fs/userfaultfd.c (ffffffff81332648)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff813366d2)
Location: include/linux/wait.h:87
Inline: True
```
```
In fs/io_uring.c (ffffffff8133b0d9)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
```
```
In block/blk-mq.c (ffffffff814eafac)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
```
In block/blk-iocost.c (ffffffff8150bda1)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In net/unix/af_unix.c (ffffffff819d0256)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
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
In kernel/exit.c (ffffffff8108dc9e)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In mm/memcontrol.c (ffffffff812acf06)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff812de06c)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/eventpoll.c (ffffffff8131b942)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_ptable_queue_proc
```
```
In fs/userfaultfd.c (ffffffff81323208)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff81327052)
Location: include/linux/wait.h:87
Inline: True
```
```
In fs/io_uring.c (ffffffff8132bdc3)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
```
```
In block/blk-mq.c (ffffffff814db4fc)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
```
In block/blk-iocost.c (ffffffff814fc1eb)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/vfio/virqfd.c (ffffffff8177c9ae)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
```
```
In net/unix/af_unix.c (ffffffff8198d016)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
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
In kernel/exit.c (ffffffff8109f21e)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In mm/memcontrol.c (ffffffff812b9bb6)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff812eb24c)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/eventpoll.c (ffffffff81328872)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_ptable_queue_proc
```
```
In fs/userfaultfd.c (ffffffff81330118)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff813341a2)
Location: include/linux/wait.h:87
Inline: True
```
```
In fs/io_uring.c (ffffffff81338ba9)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
```
```
In block/blk-mq.c (ffffffff814e703c)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
```
In block/blk-iocost.c (ffffffff81507e31)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/vfio/virqfd.c (ffffffff817c778a)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
```
```
In net/unix/af_unix.c (ffffffff81a3acd6)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
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
In kernel/exit.c (ffffffff810a716e)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In mm/memcontrol.c (ffffffff812ca246)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/select.c (ffffffff812fc23c)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/eventpoll.c (ffffffff8133a692)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_ptable_queue_proc
```
```
In fs/userfaultfd.c (ffffffff81342a78)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff81344e22)
Location: include/linux/wait.h:87
Inline: True
```
```
In fs/io_uring.c (ffffffff8134b3fb)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
```
```
In block/blk-mq.c (ffffffff814fffde)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
```
In block/blk-iocost.c (ffffffff8151f129)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
```
```
In drivers/vfio/virqfd.c (ffffffff817e19af)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
```
```
In net/unix/af_unix.c (ffffffff81a45f56)
Location: include/linux/wait.h:87
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
</details>
</li>
</ul>

## Differences
