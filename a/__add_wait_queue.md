# Function: <code>__add_wait_queue</code>

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
In kernel/sched/wait.c (ffffffff810c321a)
Location: include/linux/wait.h:114
Inline: True
Inline callers:
  - kernel/sched/wait.c:add_wait_queue
  - kernel/sched/wait.c:prepare_to_wait
  - kernel/sched/wait.c:prepare_to_wait_event
```
```
In mm/filemap.c (ffffffff8118c5b9)
Location: include/linux/wait.h:114
Inline: True
Inline callers:
  - mm/filemap.c:add_page_wait_queue
```
```
In fs/fs_pin.c (ffffffff81242116)
Location: include/linux/wait.h:114
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_kill
```
```
In fs/eventpoll.c (ffffffff812555e0)
Location: include/linux/wait.h:114
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/eventfd.c (ffffffff81259501)
Location: include/linux/wait.h:114
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_ctx_read
```
```
In fs/userfaultfd.c (ffffffff81259be7)
Location: include/linux/wait.h:114
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:handle_userfault
```
```
In drivers/pci/access.c (ffffffff8142e675)
Location: include/linux/wait.h:114
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_wait_cfg
```
```
In net/unix/af_unix.c (ffffffff817bd654)
Location: include/linux/wait.h:114
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
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
In kernel/sched/wait.c (ffffffff810c7305)
Location: include/linux/wait.h:165
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:prepare_to_wait
  - kernel/sched/wait.c:add_wait_queue
```
```
In mm/filemap.c (ffffffff8119f409)
Location: include/linux/wait.h:165
Inline: True
Inline callers:
  - mm/filemap.c:add_page_wait_queue
```
```
In fs/fs_pin.c (ffffffff8126a46a)
Location: include/linux/wait.h:165
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_kill
```
```
In fs/eventpoll.c (ffffffff8127d914)
Location: include/linux/wait.h:165
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/eventfd.c (ffffffff81281ed5)
Location: include/linux/wait.h:165
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_ctx_read
```
```
In fs/userfaultfd.c (ffffffff812825fb)
Location: include/linux/wait.h:165
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:handle_userfault
```
```
In drivers/pci/access.c (ffffffff81479c35)
Location: include/linux/wait.h:165
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_wait_cfg
```
```
In net/unix/af_unix.c (ffffffff8182a5bf)
Location: include/linux/wait.h:165
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
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
In kernel/sched/wait.c (ffffffff810cd1b4)
Location: include/linux/wait.h:165
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:prepare_to_wait
  - kernel/sched/wait.c:add_wait_queue
```
```
In mm/filemap.c (ffffffff811b108e)
Location: include/linux/wait.h:165
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:add_page_wait_queue
```
```
In fs/fs_pin.c (ffffffff8127d41a)
Location: include/linux/wait.h:165
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_kill
```
```
In fs/eventpoll.c (ffffffff812914a4)
Location: include/linux/wait.h:165
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/eventfd.c (ffffffff81295a05)
Location: include/linux/wait.h:165
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_ctx_read
```
```
In fs/userfaultfd.c (ffffffff8129611b)
Location: include/linux/wait.h:165
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:handle_userfault
```
```
In drivers/pci/access.c (ffffffff8149b0c5)
Location: include/linux/wait.h:165
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_wait_cfg
```
```
In net/unix/af_unix.c (ffffffff8185c02f)
Location: include/linux/wait.h:165
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
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
In kernel/sched/wait.c (ffffffff810c9910)
Location: include/linux/wait.h:152
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:prepare_to_wait
```
```
In fs/fs_pin.c (ffffffff8128af9b)
Location: include/linux/wait.h:152
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_kill
```
```
In fs/eventpoll.c (ffffffff8129e3c5)
Location: include/linux/wait.h:152
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/eventfd.c (ffffffff812a2be7)
Location: include/linux/wait.h:152
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_ctx_read
```
```
In fs/userfaultfd.c (ffffffff812a3478)
Location: include/linux/wait.h:152
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
```
```
In drivers/pci/access.c (ffffffff814a4ea5)
Location: include/linux/wait.h:152
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_wait_cfg
```
```
In net/unix/af_unix.c (ffffffff818806c6)
Location: include/linux/wait.h:152
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
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
In kernel/sched/wait.c (ffffffff810d1133)
Location: include/linux/wait.h:154
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:prepare_to_wait
  - kernel/sched/wait.c:add_wait_queue
```
```
In fs/fs_pin.c (ffffffff812adad9)
Location: include/linux/wait.h:154
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_kill
```
```
In fs/eventpoll.c (ffffffff812c18b5)
Location: include/linux/wait.h:154
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/eventfd.c (ffffffff812c5f2c)
Location: include/linux/wait.h:154
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_ctx_read
```
```
In fs/userfaultfd.c (ffffffff812c6a11)
Location: include/linux/wait.h:154
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
```
```
In drivers/pci/access.c (ffffffff814e3c7f)
Location: include/linux/wait.h:154
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_wait_cfg
```
```
In net/unix/af_unix.c (ffffffff81901856)
Location: include/linux/wait.h:154
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
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
In kernel/sched/wait.c (ffffffff810d9646)
Location: include/linux/wait.h:154
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:prepare_to_wait
  - kernel/sched/wait.c:add_wait_queue
```
```
In fs/fs_pin.c (ffffffff812d588a)
Location: include/linux/wait.h:154
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_kill
```
```
In fs/eventpoll.c (ffffffff812ea6f8)
Location: include/linux/wait.h:154
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/eventfd.c (ffffffff812ef1d8)
Location: include/linux/wait.h:154
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (ffffffff812f0dd2)
Location: include/linux/wait.h:154
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
```
```
In drivers/pci/access.c (ffffffff815136aa)
Location: include/linux/wait.h:154
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_wait_cfg
```
```
In net/unix/af_unix.c (ffffffff8195944f)
Location: include/linux/wait.h:154
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
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
In kernel/sched/wait.c (ffffffff810e3140)
Location: include/linux/wait.h:154
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:prepare_to_wait
  - kernel/sched/wait.c:add_wait_queue
```
```
In fs/fs_pin.c (ffffffff812eac5a)
Location: include/linux/wait.h:154
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_kill
```
```
In fs/eventpoll.c (ffffffff813009d1)
Location: include/linux/wait.h:154
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/eventfd.c (ffffffff81303b68)
Location: include/linux/wait.h:154
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (ffffffff813044e1)
Location: include/linux/wait.h:154
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
```
```
In block/blk-mq.c (ffffffff814a9f9c)
Location: include/linux/wait.h:154
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In drivers/pci/access.c (ffffffff81528e0a)
Location: include/linux/wait.h:154
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_wait_cfg
```
```
In net/unix/af_unix.c (ffffffff8198dfe3)
Location: include/linux/wait.h:154
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
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
In kernel/sched/wait.c (ffffffff810e9d81)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:prepare_to_wait
  - kernel/sched/wait.c:add_wait_queue
```
```
In fs/fs_pin.c (ffffffff813096c7)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_kill
```
```
In fs/eventpoll.c (ffffffff81321c6f)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/eventfd.c (ffffffff81325137)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (ffffffff8132637f)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
```
```
In block/blk-mq.c (ffffffff814d7f5e)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In drivers/pci/access.c (ffffffff81558013)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_wait_cfg
```
```
In net/unix/af_unix.c (ffffffff819f956d)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
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
In kernel/sched/wait.c (ffffffff810f5751)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:prepare_to_wait
  - kernel/sched/wait.c:add_wait_queue
```
```
In fs/fs_pin.c (ffffffff8131c737)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_kill
```
```
In fs/eventpoll.c (ffffffff813341ca)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/eventfd.c (ffffffff81337ec7)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (ffffffff8133910f)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
```
```
In block/blk-mq.c (ffffffff814f12f0)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In drivers/pci/access.c (ffffffff81579623)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_wait_cfg
```
```
In net/unix/af_unix.c (ffffffff81a301cd)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
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
In kernel/sched/wait.c (ffffffff810ff001)
Location: include/linux/wait.h:168
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:prepare_to_wait
  - kernel/sched/wait.c:add_wait_queue
```
```
In fs/fs_pin.c (ffffffff81356477)
Location: include/linux/wait.h:168
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_kill
```
```
In fs/eventpoll.c (ffffffff8136e7b6)
Location: include/linux/wait.h:168
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/eventfd.c (ffffffff81371bf7)
Location: include/linux/wait.h:168
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (ffffffff81373c6b)
Location: include/linux/wait.h:168
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
```
```
In block/blk-mq.c (ffffffff81551a77)
Location: include/linux/wait.h:168
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In net/unix/af_unix.c (ffffffff81b24988)
Location: include/linux/wait.h:168
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
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
In kernel/sched/wait.c (ffffffff810fd88b)
Location: include/linux/wait.h:171
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:prepare_to_wait
  - kernel/sched/wait.c:add_wait_queue_priority
  - kernel/sched/wait.c:add_wait_queue
```
```
In fs/fs_pin.c (ffffffff81362dc3)
Location: include/linux/wait.h:171
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_kill
```
```
In fs/eventpoll.c (ffffffff8137bb62)
Location: include/linux/wait.h:171
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/eventfd.c (ffffffff8137f9b9)
Location: include/linux/wait.h:171
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (ffffffff81381bd7)
Location: include/linux/wait.h:171
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
```
```
In block/blk-mq.c (ffffffff8156dbff)
Location: include/linux/wait.h:171
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In net/unix/af_unix.c (ffffffff81b3365e)
Location: include/linux/wait.h:171
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
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
In kernel/sched/wait.c (ffffffff810ffc6b)
Location: include/linux/wait.h:171
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:prepare_to_wait
  - kernel/sched/wait.c:add_wait_queue_priority
  - kernel/sched/wait.c:add_wait_queue
```
```
In fs/fs_pin.c (ffffffff81369863)
Location: include/linux/wait.h:171
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_kill
```
```
In fs/eventpoll.c (ffffffff813822e2)
Location: include/linux/wait.h:171
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/eventfd.c (ffffffff81386638)
Location: include/linux/wait.h:171
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (ffffffff81388c3e)
Location: include/linux/wait.h:171
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/io-wq.c (ffffffff813a3046)
Location: include/linux/wait.h:171
Inline: True
Inline callers:
  - fs/io-wq.c:io_worker_handle_work
```
```
In block/blk-mq.c (ffffffff815756df)
Location: include/linux/wait.h:171
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In net/unix/af_unix.c (ffffffff81b2156e)
Location: include/linux/wait.h:171
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
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
In kernel/sched/wait.c (ffffffff8111bd50)
Location: include/linux/wait.h:171
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:prepare_to_wait
  - kernel/sched/wait.c:add_wait_queue_priority
  - kernel/sched/wait.c:add_wait_queue
```
```
In fs/fs_pin.c (ffffffff813b8563)
Location: include/linux/wait.h:171
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_kill
```
```
In fs/eventpoll.c (ffffffff813cf550)
Location: include/linux/wait.h:171
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/eventfd.c (ffffffff813d3908)
Location: include/linux/wait.h:171
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (ffffffff813d5f58)
Location: include/linux/wait.h:171
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/io-wq.c (ffffffff813f1c31)
Location: include/linux/wait.h:171
Inline: True
```
```
In block/blk-mq.c (ffffffff815da3df)
Location: include/linux/wait.h:171
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In net/unix/af_unix.c (ffffffff81be670e)
Location: include/linux/wait.h:171
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
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
In kernel/sched/build_utility.c (ffffffff8113fb81)
Location: include/linux/wait.h:171
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:prepare_to_wait_event
  - kernel/sched/build_utility.c:add_wait_queue_priority
  - kernel/sched/build_utility.c:add_wait_queue
  - kernel/sched/build_utility.c:__wait_on_bit
```
```
In fs/fs_pin.c (ffffffff8143de56)
Location: include/linux/wait.h:171
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_kill
```
```
In fs/eventpoll.c (ffffffff8145830a)
Location: include/linux/wait.h:171
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/eventfd.c (ffffffff8145cdf0)
Location: include/linux/wait.h:171
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (ffffffff8145dc38)
Location: include/linux/wait.h:171
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
```
```
In block/blk-mq.c (ffffffff816884cf)
Location: include/linux/wait.h:171
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In io_uring/io-wq.c (ffffffff816d98b0)
Location: include/linux/wait.h:171
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81d7d402)
Location: include/linux/wait.h:171
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
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
In kernel/sched/build_utility.c (ffffffff8116a761)
Location: include/linux/wait.h:171
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:prepare_to_wait_event
  - kernel/sched/build_utility.c:add_wait_queue_priority
  - kernel/sched/build_utility.c:add_wait_queue
  - kernel/sched/build_utility.c:__wait_on_bit
```
```
In fs/fs_pin.c (ffffffff814cc816)
Location: include/linux/wait.h:171
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_kill
```
```
In fs/eventpoll.c (ffffffff814e7c3a)
Location: include/linux/wait.h:171
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/eventfd.c (ffffffff814ec4b9)
Location: include/linux/wait.h:171
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (ffffffff814ed698)
Location: include/linux/wait.h:171
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
```
```
In block/blk-mq.c (ffffffff8174697e)
Location: include/linux/wait.h:171
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In io_uring/io-wq.c (ffffffff817a5790)
Location: include/linux/wait.h:171
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81f4a923)
Location: include/linux/wait.h:171
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
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
In kernel/sched/build_utility.c (ffffffff8117ae71)
Location: include/linux/wait.h:171
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:prepare_to_wait_event
  - kernel/sched/build_utility.c:add_wait_queue_priority
  - kernel/sched/build_utility.c:add_wait_queue
  - kernel/sched/build_utility.c:__wait_on_bit
```
```
In fs/fs_pin.c (ffffffff81502a56)
Location: include/linux/wait.h:171
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_kill
```
```
In fs/eventpoll.c (ffffffff8151deed)
Location: include/linux/wait.h:171
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/userfaultfd.c (ffffffff815246a8)
Location: include/linux/wait.h:171
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
```
```
In block/blk-mq.c (ffffffff81783bde)
Location: include/linux/wait.h:171
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In io_uring/io-wq.c (ffffffff817e675c)
Location: include/linux/wait.h:171
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81faa5c3)
Location: include/linux/wait.h:171
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
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
In kernel/sched/build_utility.c (ffffffff81188881)
Location: include/linux/wait.h:169
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:prepare_to_wait_event
  - kernel/sched/build_utility.c:add_wait_queue_priority
  - kernel/sched/build_utility.c:add_wait_queue
  - kernel/sched/build_utility.c:__wait_on_bit
```
```
In fs/fs_pin.c (ffffffff815376a6)
Location: include/linux/wait.h:169
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_kill
```
```
In fs/eventpoll.c (ffffffff815524cd)
Location: include/linux/wait.h:169
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/userfaultfd.c (ffffffff8155b198)
Location: include/linux/wait.h:169
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
```
```
In block/blk-mq.c (ffffffff817c5f46)
Location: include/linux/wait.h:169
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In io_uring/io-wq.c (ffffffff8182c51c)
Location: include/linux/wait.h:169
Inline: True
```
```
In net/unix/af_unix.c (ffffffff820779e3)
Location: include/linux/wait.h:169
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
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
In kernel/sched/wait.c (ffff800010158370)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:prepare_to_wait
  - kernel/sched/wait.c:add_wait_queue
```
```
In fs/fs_pin.c (ffff8000103d420c)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_kill
```
```
In fs/eventpoll.c (ffff8000103f29fc)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/eventfd.c (ffff8000103f6430)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (ffff8000103f7144)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
```
```
In block/blk-mq.c (ffff8000105f084c)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In drivers/pci/access.c (0)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_wait_cfg
```
```
In net/unix/af_unix.c (ffff800010cefe3c)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
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
In kernel/sched/wait.c (c03a5f08)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:prepare_to_wait
  - kernel/sched/wait.c:add_wait_queue
```
```
In fs/fs_pin.c (c05ae34c)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_kill
```
```
In fs/eventpoll.c (c05c6824)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
```
```
In fs/eventfd.c (c05caeb0)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (c05cb714)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
```
```
In block/blk-mq.c (c079c98c)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In drivers/pci/access.c (c0877588)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_wait_cfg
```
```
In net/unix/af_unix.c (c0df6868)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
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
In kernel/sched/wait.c (c0000000001acfb0)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:prepare_to_wait
  - kernel/sched/wait.c:add_wait_queue
```
```
In fs/fs_pin.c (c0000000004d6de0)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_kill
```
```
In fs/eventpoll.c (c0000000004f858c)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/eventfd.c (c0000000004fe750)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (c000000000500cbc)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
```
```
In block/blk-mq.c (c00000000078720c)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In drivers/pci/access.c (c0000000008536a8)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_wait_cfg
```
```
In net/unix/af_unix.c (c000000000e15784)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
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
In kernel/sched/wait.c (ffffffe0000fed4e)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:prepare_to_wait
  - kernel/sched/wait.c:add_wait_queue
```
```
In fs/fs_pin.c (ffffffe00028e7d0)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_kill
```
```
In fs/eventpoll.c (ffffffe0002a34a0)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
```
```
In fs/eventfd.c (ffffffe0002a6bf4)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (ffffffe0002a7d4a)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
```
```
In block/blk-mq.c (ffffffe00042f668)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In drivers/pci/access.c (ffffffe0004b4296)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_wait_cfg
```
```
In net/unix/af_unix.c (ffffffe00083c84c)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
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
In kernel/sched/wait.c (ffffffff810eeb51)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:prepare_to_wait
  - kernel/sched/wait.c:add_wait_queue
```
```
In fs/fs_pin.c (ffffffff81314d17)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_kill
```
```
In fs/eventpoll.c (ffffffff8132c7aa)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/eventfd.c (ffffffff813304a7)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (ffffffff813316ef)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
```
```
In block/blk-mq.c (ffffffff814e98d0)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In drivers/pci/access.c (ffffffff8156db43)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_wait_cfg
```
```
In net/unix/af_unix.c (ffffffff819cf85d)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
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
In kernel/sched/wait.c (ffffffff810debe1)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:prepare_to_wait
  - kernel/sched/wait.c:add_wait_queue
```
```
In fs/fs_pin.c (ffffffff8130591d)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_kill
```
```
In fs/eventpoll.c (ffffffff8131c085)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/eventfd.c (ffffffff813210b1)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (ffffffff813222cf)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
```
```
In block/blk-mq.c (ffffffff814d9e3a)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In drivers/pci/access.c (ffffffff8155c2b3)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_wait_cfg
```
```
In net/unix/af_unix.c (ffffffff8198c61d)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
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
In kernel/sched/wait.c (ffffffff810ebc81)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:prepare_to_wait
  - kernel/sched/wait.c:add_wait_queue
```
```
In fs/fs_pin.c (ffffffff81312b07)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_kill
```
```
In fs/eventpoll.c (ffffffff8132a27a)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/eventfd.c (ffffffff8132df77)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (ffffffff8132f1bf)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
```
```
In block/blk-mq.c (ffffffff814e5960)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In drivers/pci/access.c (ffffffff8156d373)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_wait_cfg
```
```
In net/unix/af_unix.c (ffffffff81a3a2dd)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
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
In kernel/sched/wait.c (ffffffff810f6ce1)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:prepare_to_wait
  - kernel/sched/wait.c:add_wait_queue
```
```
In fs/fs_pin.c (ffffffff81324336)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_kill
```
```
In fs/eventpoll.c (ffffffff8133ad56)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/eventfd.c (ffffffff8134084f)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (ffffffff813412de)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
```
```
In block/blk-mq.c (ffffffff814fe8b5)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In drivers/pci/access.c (ffffffff815873ca)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_wait_cfg
```
```
In net/unix/af_unix.c (ffffffff81a45407)
Location: include/linux/wait.h:167
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_peer_wake_me
```
</details>
</li>
</ul>

## Differences
