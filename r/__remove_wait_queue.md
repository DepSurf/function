# Function: <code>__remove_wait_queue</code>

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
In kernel/sched/wait.c (ffffffff810c32b7)
Location: include/linux/wait.h:143
Inline: True
Inline callers:
  - kernel/sched/wait.c:remove_wait_queue
```
```
In kernel/sched/completion.c (ffffffff81820e66)
Location: include/linux/wait.h:143
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_io
```
```
In fs/eventpoll.c (ffffffff812556d0)
Location: include/linux/wait.h:143
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff8125841b)
Location: include/linux/wait.h:143
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_read
```
```
In fs/eventfd.c (ffffffff81259040)
Location: include/linux/wait.h:143
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_ctx_read
```
```
In fs/userfaultfd.c (ffffffff81259c84)
Location: include/linux/wait.h:143
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
```
```
In fs/fuse/dev.c (ffffffff81310d38)
Location: include/linux/wait.h:143
Inline: True
```
```
In drivers/pci/access.c (ffffffff8142e6fd)
Location: include/linux/wait.h:143
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_wait_cfg
```
```
In net/unix/af_unix.c (ffffffff817bd57e)
Location: include/linux/wait.h:143
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_peer_wake_disconnect
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
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
In kernel/sched/wait.c (ffffffff810c6c47)
Location: include/linux/wait.h:194
Inline: True
Inline callers:
  - kernel/sched/wait.c:remove_wait_queue
```
```
In kernel/sched/completion.c (ffffffff8189b551)
Location: include/linux/wait.h:194
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
```
```
In fs/eventpoll.c (ffffffff8127da03)
Location: include/linux/wait.h:194
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff81280d22)
Location: include/linux/wait.h:194
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_read
```
```
In fs/eventfd.c (ffffffff81281f6b)
Location: include/linux/wait.h:194
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_ctx_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
```
```
In fs/userfaultfd.c (ffffffff8128269f)
Location: include/linux/wait.h:194
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
```
```
In fs/fuse/dev.c (ffffffff81345193)
Location: include/linux/wait.h:194
Inline: True
```
```
In drivers/pci/access.c (ffffffff81479cbd)
Location: include/linux/wait.h:194
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_wait_cfg
```
```
In net/unix/af_unix.c (ffffffff8182a4ee)
Location: include/linux/wait.h:194
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_peer_wake_disconnect
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
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
In kernel/sched/wait.c (ffffffff810ccc27)
Location: include/linux/wait.h:194
Inline: True
Inline callers:
  - kernel/sched/wait.c:remove_wait_queue
```
```
In kernel/sched/completion.c (ffffffff818cfb6d)
Location: include/linux/wait.h:194
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
```
```
In fs/eventpoll.c (ffffffff8129159d)
Location: include/linux/wait.h:194
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff8129485e)
Location: include/linux/wait.h:194
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_read
```
```
In fs/eventfd.c (ffffffff81295a98)
Location: include/linux/wait.h:194
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_ctx_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
```
```
In fs/userfaultfd.c (ffffffff812961bb)
Location: include/linux/wait.h:194
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
```
```
In fs/fuse/dev.c (ffffffff8135af4a)
Location: include/linux/wait.h:194
Inline: True
```
```
In drivers/pci/access.c (ffffffff8149b14e)
Location: include/linux/wait.h:194
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_wait_cfg
```
```
In net/unix/af_unix.c (ffffffff8185bf5e)
Location: include/linux/wait.h:194
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_peer_wake_disconnect
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
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
In kernel/sched/wait.c (ffffffff810c94e7)
Location: include/linux/wait.h:180
Inline: True
Inline callers:
  - kernel/sched/wait.c:remove_wait_queue
```
```
In kernel/sched/completion.c (ffffffff819072dc)
Location: include/linux/wait.h:180
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
```
```
In fs/eventpoll.c (ffffffff8129e4ab)
Location: include/linux/wait.h:180
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff812a1b6e)
Location: include/linux/wait.h:180
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_read
```
```
In fs/eventfd.c (ffffffff812a2c51)
Location: include/linux/wait.h:180
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_ctx_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
```
```
In fs/userfaultfd.c (ffffffff812a356a)
Location: include/linux/wait.h:180
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/fuse/dev.c (ffffffff8136e869)
Location: include/linux/wait.h:180
Inline: True
```
```
In drivers/pci/access.c (ffffffff814a4f2e)
Location: include/linux/wait.h:180
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_wait_cfg
```
```
In net/unix/af_unix.c (ffffffff8188062d)
Location: include/linux/wait.h:180
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_peer_wake_disconnect
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
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
In kernel/sched/wait.c (ffffffff810d0bd7)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - kernel/sched/wait.c:remove_wait_queue
```
```
In kernel/sched/completion.c (ffffffff819914f7)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
```
```
In fs/eventpoll.c (ffffffff812c1991)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff812c4e8e)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_read
```
```
In fs/eventfd.c (ffffffff812c5fd0)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_ctx_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
```
```
In fs/userfaultfd.c (ffffffff812c6afe)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/fuse/dev.c (ffffffff81393474)
Location: include/linux/wait.h:182
Inline: True
```
```
In drivers/pci/access.c (ffffffff814e3d16)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_wait_cfg
```
```
In net/unix/af_unix.c (ffffffff819017bd)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_peer_wake_disconnect
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
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
In kernel/sched/wait.c (ffffffff810d9117)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - kernel/sched/wait.c:remove_wait_queue
```
```
In kernel/sched/completion.c (ffffffff819ed8a2)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
```
```
In fs/eventpoll.c (ffffffff812ea758)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff812edf65)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_read
```
```
In fs/eventfd.c (ffffffff812ef27c)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
```
```
In fs/userfaultfd.c (ffffffff812f0ec3)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/fuse/dev.c (ffffffff813c1bb0)
Location: include/linux/wait.h:182
Inline: True
```
```
In drivers/pci/access.c (ffffffff81513706)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_wait_cfg
```
```
In net/unix/af_unix.c (ffffffff8195937e)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_peer_wake_disconnect
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
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
In kernel/sched/wait.c (ffffffff810e2c17)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - kernel/sched/wait.c:remove_wait_queue
```
```
In kernel/sched/completion.c (ffffffff81a28ab2)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
```
```
In fs/eventpoll.c (ffffffff8130085a)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff813029f5)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_read
```
```
In fs/eventfd.c (ffffffff81303c0c)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
```
```
In fs/userfaultfd.c (ffffffff813045dc)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/fuse/dev.c (ffffffff813db37c)
Location: include/linux/wait.h:182
Inline: True
```
```
In drivers/pci/access.c (ffffffff81528e66)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_wait_cfg
```
```
In net/unix/af_unix.c (ffffffff8198df2e)
Location: include/linux/wait.h:182
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_peer_wake_disconnect
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
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
In kernel/sched/wait.c (ffffffff810e9831)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - kernel/sched/wait.c:remove_wait_queue
```
```
In kernel/sched/completion.c (ffffffff81a994a9)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
```
```
In fs/eventpoll.c (ffffffff81321b30)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff81323f61)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_read
```
```
In fs/eventfd.c (ffffffff813251b3)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
```
```
In fs/userfaultfd.c (ffffffff8132646c)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/fuse/dev.c (ffffffff81407814)
Location: include/linux/wait.h:195
Inline: True
```
```
In drivers/pci/access.c (ffffffff8155806e)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_wait_cfg
```
```
In net/unix/af_unix.c (ffffffff819f94bd)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_peer_wake_disconnect
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
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
In kernel/sched/wait.c (ffffffff810f5201)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - kernel/sched/wait.c:remove_wait_queue
```
```
In kernel/sched/completion.c (ffffffff81ad0df9)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
```
```
In fs/eventpoll.c (ffffffff81334091)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff81336cc1)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_read
```
```
In fs/eventfd.c (ffffffff81337f43)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
```
```
In fs/userfaultfd.c (ffffffff813391fc)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In drivers/pci/access.c (ffffffff8157967e)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_wait_cfg
```
```
In net/unix/af_unix.c (ffffffff81a3011d)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_peer_wake_disconnect
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
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
In kernel/sched/wait.c (ffffffff810fe921)
Location: include/linux/wait.h:196
Inline: True
Inline callers:
  - kernel/sched/wait.c:remove_wait_queue
```
```
In fs/eventpoll.c (ffffffff8136e5fb)
Location: include/linux/wait.h:196
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff813705f1)
Location: include/linux/wait.h:196
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_read
```
```
In fs/eventfd.c (ffffffff81371c8a)
Location: include/linux/wait.h:196
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
```
```
In fs/userfaultfd.c (ffffffff81373d44)
Location: include/linux/wait.h:196
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In drivers/gpio/gpiolib.c (ffffffff81611c21)
Location: include/linux/wait.h:196
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineinfo_watch_read
  - drivers/gpio/gpiolib.c:lineevent_read
```
```
In net/unix/af_unix.c (ffffffff81b28f31)
Location: include/linux/wait.h:196
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
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
In kernel/sched/wait.c (ffffffff810fd2a1)
Location: include/linux/wait.h:207
Inline: True
Inline callers:
  - kernel/sched/wait.c:remove_wait_queue
```
```
In mm/filemap.c (ffffffff81259a83)
Location: include/linux/wait.h:207
Inline: True
Inline callers:
  - mm/filemap.c:__wait_on_page_locked_async
```
```
In fs/eventpoll.c (ffffffff8137bae3)
Location: include/linux/wait.h:207
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff8137e361)
Location: include/linux/wait.h:207
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_read
```
```
In fs/eventfd.c (ffffffff8137fa89)
Location: include/linux/wait.h:207
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
```
```
In fs/userfaultfd.c (ffffffff81381cf4)
Location: include/linux/wait.h:207
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8163bf37)
Location: include/linux/wait.h:207
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_watch_read
  - drivers/gpio/gpiolib-cdev.c:linereq_read
```
```
In net/unix/af_unix.c (ffffffff81b371c0)
Location: include/linux/wait.h:207
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
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
In kernel/sched/wait.c (ffffffff810ff661)
Location: include/linux/wait.h:207
Inline: True
Inline callers:
  - kernel/sched/wait.c:remove_wait_queue
```
```
In mm/filemap.c (ffffffff81261ce5)
Location: include/linux/wait.h:207
Inline: True
Inline callers:
  - mm/filemap.c:__lock_page_async
```
```
In fs/eventpoll.c (ffffffff81382263)
Location: include/linux/wait.h:207
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff81384fe1)
Location: include/linux/wait.h:207
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_read
```
```
In fs/eventfd.c (ffffffff81386703)
Location: include/linux/wait.h:207
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
```
```
In fs/userfaultfd.c (ffffffff81388d5b)
Location: include/linux/wait.h:207
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8161fc57)
Location: include/linux/wait.h:207
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_watch_read
  - drivers/gpio/gpiolib-cdev.c:linereq_read
```
```
In net/unix/af_unix.c (ffffffff81b24d97)
Location: include/linux/wait.h:207
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
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
In kernel/sched/wait.c (ffffffff8111b751)
Location: include/linux/wait.h:207
Inline: True
Inline callers:
  - kernel/sched/wait.c:remove_wait_queue
```
```
In mm/filemap.c (ffffffff8129e2c5)
Location: include/linux/wait.h:207
Inline: True
Inline callers:
  - mm/filemap.c:__lock_page_async
```
```
In fs/eventpoll.c (ffffffff813cf4d1)
Location: include/linux/wait.h:207
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff813d22a2)
Location: include/linux/wait.h:207
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_read
```
```
In fs/eventfd.c (ffffffff813d399b)
Location: include/linux/wait.h:207
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
```
```
In fs/userfaultfd.c (ffffffff813d6060)
Location: include/linux/wait.h:207
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8168f007)
Location: include/linux/wait.h:207
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_watch_read
  - drivers/gpio/gpiolib-cdev.c:linereq_read
```
```
In net/unix/af_unix.c (ffffffff81be9dde)
Location: include/linux/wait.h:207
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
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
In kernel/sched/build_utility.c (ffffffff8113b9c1)
Location: include/linux/wait.h:207
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:remove_wait_queue
```
```
In mm/filemap.c (ffffffff812f210c)
Location: include/linux/wait.h:207
Inline: True
Inline callers:
  - mm/filemap.c:filemap_update_page
```
```
In fs/eventpoll.c (ffffffff814582b7)
Location: include/linux/wait.h:207
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff8145be11)
Location: include/linux/wait.h:207
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_read
```
```
In fs/eventfd.c (ffffffff8145cd8c)
Location: include/linux/wait.h:207
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
```
```
In fs/userfaultfd.c (ffffffff8145dd34)
Location: include/linux/wait.h:207
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff817abc55)
Location: include/linux/wait.h:207
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_watch_read
  - drivers/gpio/gpiolib-cdev.c:lineevent_read
  - drivers/gpio/gpiolib-cdev.c:linereq_read
```
```
In net/unix/af_unix.c (ffffffff81d828ce)
Location: include/linux/wait.h:207
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
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
In kernel/sched/build_utility.c (ffffffff81166431)
Location: include/linux/wait.h:207
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:remove_wait_queue
```
```
In mm/filemap.c (ffffffff8135c9ec)
Location: include/linux/wait.h:207
Inline: True
Inline callers:
  - mm/filemap.c:filemap_update_page
```
```
In fs/eventpoll.c (ffffffff814e7be7)
Location: include/linux/wait.h:207
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff814eb4d1)
Location: include/linux/wait.h:207
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_read
```
```
In fs/eventfd.c (ffffffff814ec546)
Location: include/linux/wait.h:207
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
```
```
In fs/userfaultfd.c (ffffffff814ed791)
Location: include/linux/wait.h:207
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c5cd6)
Location: include/linux/wait.h:207
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_watch_read_unlocked
  - drivers/gpio/gpiolib-cdev.c:lineevent_read_unlocked
  - drivers/gpio/gpiolib-cdev.c:linereq_read_unlocked
```
```
In net/unix/af_unix.c (ffffffff81f4fea7)
Location: include/linux/wait.h:207
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
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
In kernel/sched/build_utility.c (ffffffff811768a1)
Location: include/linux/wait.h:207
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:remove_wait_queue
```
```
In mm/filemap.c (ffffffff8138ea24)
Location: include/linux/wait.h:207
Inline: True
Inline callers:
  - mm/filemap.c:filemap_update_page
```
```
In fs/eventpoll.c (ffffffff8151de9a)
Location: include/linux/wait.h:207
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff81522271)
Location: include/linux/wait.h:207
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_read
```
```
In fs/eventfd.c (ffffffff81523183)
Location: include/linux/wait.h:207
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
```
```
In fs/userfaultfd.c (ffffffff815247a1)
Location: include/linux/wait.h:207
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff81908d44)
Location: include/linux/wait.h:207
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_watch_read_unlocked
  - drivers/gpio/gpiolib-cdev.c:lineevent_read_unlocked
  - drivers/gpio/gpiolib-cdev.c:linereq_read_unlocked
```
```
In net/unix/af_unix.c (ffffffff81faf714)
Location: include/linux/wait.h:207
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
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
In kernel/sched/build_utility.c (ffffffff81184b21)
Location: include/linux/wait.h:205
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:remove_wait_queue
```
```
In mm/filemap.c (ffffffff813b82b4)
Location: include/linux/wait.h:205
Inline: True
Inline callers:
  - mm/filemap.c:filemap_update_page
```
```
In fs/eventpoll.c (ffffffff8155247a)
Location: include/linux/wait.h:205
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff81556891)
Location: include/linux/wait.h:205
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_read
```
```
In fs/eventfd.c (ffffffff81557883)
Location: include/linux/wait.h:205
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
```
```
In fs/userfaultfd.c (ffffffff8155b291)
Location: include/linux/wait.h:205
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff81950349)
Location: include/linux/wait.h:205
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_watch_read
  - drivers/gpio/gpiolib-cdev.c:lineevent_read
  - drivers/gpio/gpiolib-cdev.c:linereq_read
```
```
In net/unix/af_unix.c (ffffffff8207ccfe)
Location: include/linux/wait.h:205
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
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
In kernel/sched/wait.c (ffff800010158830)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - kernel/sched/wait.c:remove_wait_queue
```
```
In kernel/sched/completion.c (ffff800010da2930)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - kernel/sched/completion.c:__wait_for_common
```
```
In fs/eventpoll.c (ffff8000103f2834)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffff8000103f558c)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_read
```
```
In fs/eventfd.c (ffff8000103f65b8)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
```
```
In fs/userfaultfd.c (ffff8000103f72b4)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In drivers/pci/access.c (ffff8000106da9c8)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_wait_cfg
```
```
In net/unix/af_unix.c (ffff800010cefd44)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_peer_wake_disconnect
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
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
In kernel/sched/wait.c (c03a5838)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - kernel/sched/wait.c:remove_wait_queue
```
```
In kernel/sched/completion.c (c0e9aaf8)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
```
```
In fs/eventpoll.c (c05c6548)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
```
```
In fs/timerfd.c (c05c96ac)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_read
```
```
In fs/eventfd.c (c05caf7c)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
```
```
In fs/userfaultfd.c (c05cb814)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In drivers/pci/access.c (c08775d8)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_wait_cfg
```
```
In net/unix/af_unix.c (c0df6808)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_peer_wake_disconnect
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
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
In kernel/sched/wait.c (c0000000001ac754)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - kernel/sched/wait.c:remove_wait_queue
```
```
In kernel/sched/completion.c (c000000000ee4160)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
```
```
In fs/eventpoll.c (c0000000004f8414)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (c0000000004fcaf4)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_read
```
```
In fs/eventfd.c (c0000000004fe80c)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
```
```
In fs/userfaultfd.c (c000000000500de8)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In drivers/pci/access.c (c000000000853718)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_wait_cfg
```
```
In net/unix/af_unix.c (c000000000e15630)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_peer_wake_disconnect
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
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
In kernel/sched/wait.c (ffffffe0000fe7ea)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - kernel/sched/wait.c:remove_wait_queue
```
```
In kernel/sched/completion.c (ffffffe0008c5f96)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
```
```
In fs/eventpoll.c (ffffffe0002a3302)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
```
```
In fs/timerfd.c (ffffffe0002a59d8)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_read
```
```
In fs/eventfd.c (ffffffe0002a6c98)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
```
```
In fs/userfaultfd.c (ffffffe0002a7e64)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In drivers/pci/access.c (ffffffe0004b4334)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_wait_cfg
```
```
In net/unix/af_unix.c (ffffffe00083c798)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_peer_wake_disconnect
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
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
In kernel/sched/wait.c (ffffffff810ee601)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - kernel/sched/wait.c:remove_wait_queue
```
```
In kernel/sched/completion.c (ffffffff81a6fc69)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
```
```
In fs/eventpoll.c (ffffffff8132c671)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff8132f2a1)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_read
```
```
In fs/eventfd.c (ffffffff81330523)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
```
```
In fs/userfaultfd.c (ffffffff813317dc)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In drivers/pci/access.c (ffffffff8156db9e)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_wait_cfg
```
```
In net/unix/af_unix.c (ffffffff819cf7ad)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_peer_wake_disconnect
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
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
In kernel/sched/wait.c (ffffffff810de691)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - kernel/sched/wait.c:remove_wait_queue
```
```
In kernel/sched/completion.c (ffffffff81a2c083)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
```
```
In fs/eventpoll.c (ffffffff8131bf5a)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff8131fedb)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_read
```
```
In fs/eventfd.c (ffffffff81321127)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
```
```
In fs/userfaultfd.c (ffffffff813223b6)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In drivers/pci/access.c (ffffffff8155c308)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_wait_cfg
```
```
In net/unix/af_unix.c (ffffffff8198c56d)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_peer_wake_disconnect
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
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
In kernel/sched/wait.c (ffffffff810eb731)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - kernel/sched/wait.c:remove_wait_queue
```
```
In kernel/sched/completion.c (ffffffff81adc079)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
```
```
In fs/eventpoll.c (ffffffff8132a141)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff8132cd71)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_read
```
```
In fs/eventfd.c (ffffffff8132dff3)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
```
```
In fs/userfaultfd.c (ffffffff8132f2ac)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In drivers/pci/access.c (ffffffff8156d3ce)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_wait_cfg
```
```
In net/unix/af_unix.c (ffffffff81a3a22d)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_peer_wake_disconnect
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
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
In kernel/sched/wait.c (ffffffff810f6791)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - kernel/sched/wait.c:remove_wait_queue
```
```
In kernel/sched/completion.c (ffffffff81ae827d)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
```
```
In fs/eventpoll.c (ffffffff8133ac19)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff8133f81f)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_read
```
```
In fs/eventfd.c (ffffffff813408ae)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_ctx_remove_wait_queue
```
```
In fs/userfaultfd.c (ffffffff813413c9)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In drivers/pci/access.c (ffffffff81587421)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_wait_cfg
```
```
In net/unix/af_unix.c (ffffffff81a4534b)
Location: include/linux/wait.h:195
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_peer_wake_disconnect
  - net/unix/af_unix.c:unix_dgram_peer_wake_relay
```
</details>
</li>
</ul>

## Differences
