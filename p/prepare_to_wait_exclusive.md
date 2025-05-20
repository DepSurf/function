# Function: <code>prepare_to_wait_exclusive</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void prepare_to_wait_exclusive(wait_queue_head_t *q, wait_queue_t *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c34a0)
Location: kernel/sched/wait.c:186
Inline: False
Direct callers:
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/sched/wait.c:__wait_on_bit_lock
  - block/blk-core.c:get_request
  - net/core/sock.c:__lock_sock
  - net/core/datagram.c:__skb_recv_datagram
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
ffffffff810c34a0-ffffffff810c351b: prepare_to_wait_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void prepare_to_wait_exclusive(wait_queue_head_t *q, wait_queue_t *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c6e20)
Location: kernel/sched/wait.c:186
Inline: False
Direct callers:
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/sched/wait.c:__wait_on_bit_lock
  - fs/dax.c:get_unlocked_mapping_entry
  - block/blk-core.c:get_request
  - net/core/sock.c:__lock_sock
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
ffffffff810c6e20-ffffffff810c6e9b: prepare_to_wait_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void prepare_to_wait_exclusive(wait_queue_head_t *q, wait_queue_t *wait, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810cce00)
Location: kernel/sched/wait.c:186
Inline: False
Direct callers:
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/sched/wait.c:__wait_on_bit_lock
  - fs/dax.c:get_unlocked_mapping_entry
  - block/blk-core.c:get_request
  - block/blk-wbt.c:wbt_wait
  - net/core/sock.c:__lock_sock
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
ffffffff810cce00-ffffffff810cce7c: prepare_to_wait_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void prepare_to_wait_exclusive(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c96d0)
Location: kernel/sched/wait.c:188
Inline: False
Direct callers:
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - fs/dax.c:get_unlocked_mapping_entry
  - block/blk-core.c:get_request
  - block/blk-wbt.c:wbt_wait
  - net/core/sock.c:__lock_sock
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
ffffffff810c96d0-ffffffff810c974d: prepare_to_wait_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void prepare_to_wait_exclusive(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810d0f10)
Location: kernel/sched/wait.c:243
Inline: False
Direct callers:
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - fs/dax.c:get_unlocked_mapping_entry
  - block/blk-core.c:get_request
  - block/blk-wbt.c:wbt_wait
  - net/core/sock.c:__lock_sock
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
ffffffff810d0f10-ffffffff810d0f8d: prepare_to_wait_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void prepare_to_wait_exclusive(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810d94c0)
Location: kernel/sched/wait.c:237
Inline: False
Direct callers:
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - fs/dax.c:__get_unlocked_mapping_entry
  - block/blk-core.c:get_request
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-wbt.c:wbt_wait
  - net/core/sock.c:__lock_sock
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
ffffffff810d94c0-ffffffff810d953c: prepare_to_wait_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void prepare_to_wait_exclusive(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810e2fc0)
Location: kernel/sched/wait.c:239
Inline: False
Direct callers:
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - fs/dax.c:get_unlocked_entry
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-rq-qos.c:rq_qos_wait
  - lib/sbitmap.c:sbitmap_prepare_to_wait
  - net/core/sock.c:__lock_sock
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
ffffffff810e2fc0-ffffffff810e303c: prepare_to_wait_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void prepare_to_wait_exclusive(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810e9b60)
Location: kernel/sched/wait.c:236
Inline: False
Direct callers:
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - fs/dax.c:get_unlocked_entry
  - block/blk-rq-qos.c:rq_qos_wait
  - lib/sbitmap.c:sbitmap_prepare_to_wait
  - net/core/sock.c:__lock_sock
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
ffffffff810e9b60-ffffffff810e9bdc: prepare_to_wait_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void prepare_to_wait_exclusive(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810f5530)
Location: kernel/sched/wait.c:236
Inline: False
Direct callers:
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - fs/io_uring.c:io_cqring_wait
  - fs/dax.c:get_unlocked_entry
  - block/blk-rq-qos.c:rq_qos_wait
  - lib/sbitmap.c:sbitmap_prepare_to_wait
  - net/core/sock.c:__lock_sock
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
ffffffff810f5530-ffffffff810f55ac: prepare_to_wait_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void prepare_to_wait_exclusive(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810fec70)
Location: kernel/sched/wait.c:253
Inline: False
Direct callers:
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - fs/io_uring.c:io_cqring_wait
  - fs/dax.c:get_unlocked_entry
  - block/blk-rq-qos.c:rq_qos_wait
  - lib/sbitmap.c:sbitmap_prepare_to_wait
  - net/core/sock.c:__lock_sock
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/ipv4/inet_connection_sock.c:inet_csk_wait_for_connect
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
ffffffff810fec70-ffffffff810fecec: prepare_to_wait_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void prepare_to_wait_exclusive(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810fd570)
Location: kernel/sched/wait.c:268
Inline: False
Direct callers:
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - fs/io_uring.c:io_cqring_wait
  - fs/dax.c:get_unlocked_entry
  - block/blk-rq-qos.c:rq_qos_wait
  - lib/sbitmap.c:sbitmap_prepare_to_wait
  - net/core/sock.c:__lock_sock
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/ipv4/inet_connection_sock.c:inet_csk_wait_for_connect
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
ffffffff810fd570-ffffffff810fd5ec: prepare_to_wait_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool prepare_to_wait_exclusive(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ff930)
Location: kernel/sched/wait.c:269
Inline: False
Direct callers:
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - fs/io_uring.c:io_cqring_wait
  - fs/dax.c:get_unlocked_entry
  - block/blk-rq-qos.c:rq_qos_wait
  - lib/sbitmap.c:sbitmap_prepare_to_wait
  - lib/sbitmap.c:sbitmap_prepare_to_wait
  - net/core/sock.c:__lock_sock
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
ffffffff810ff930-ffffffff810ff9c5: prepare_to_wait_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool prepare_to_wait_exclusive(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff8111ba20)
Location: kernel/sched/wait.c:277
Inline: False
Direct callers:
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - fs/io_uring.c:io_cqring_wait
  - fs/dax.c:get_unlocked_entry
  - block/blk-rq-qos.c:rq_qos_wait
  - lib/sbitmap.c:sbitmap_prepare_to_wait
  - lib/sbitmap.c:sbitmap_prepare_to_wait
  - net/core/sock.c:__lock_sock
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
ffffffff8111ba20-ffffffff8111ba9f: prepare_to_wait_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool prepare_to_wait_exclusive(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry, int state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81f22ac1)
Location: kernel/sched/wait.c:276
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__wait_on_bit_lock
Direct callers:
  - kernel/workqueue.c:__cancel_work_timer
  - fs/dax.c:get_unlocked_entry
  - block/blk-rq-qos.c:rq_qos_wait
  - io_uring/io_uring.c:io_cqring_wait
  - lib/sbitmap.c:sbitmap_prepare_to_wait
  - lib/sbitmap.c:sbitmap_prepare_to_wait
  - net/core/sock.c:__lock_sock
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
ffffffff8113bdc0-ffffffff8113be4b: prepare_to_wait_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool prepare_to_wait_exclusive(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry, int state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff820cd411)
Location: kernel/sched/wait.c:280
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__wait_on_bit_lock
Direct callers:
  - kernel/workqueue.c:__cancel_work_timer
  - fs/dax.c:get_unlocked_entry
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:wait_transaction_locked
  - block/blk-rq-qos.c:rq_qos_wait
  - io_uring/io_uring.c:io_cqring_wait
  - lib/sbitmap.c:sbitmap_prepare_to_wait
  - lib/sbitmap.c:sbitmap_prepare_to_wait
  - net/core/sock.c:__lock_sock
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
ffffffff811668c0-ffffffff8116694b: prepare_to_wait_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool prepare_to_wait_exclusive(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry, int state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff82151891)
Location: kernel/sched/wait.c:280
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__wait_on_bit_lock
Direct callers:
  - kernel/workqueue.c:__cancel_work_timer
  - fs/dax.c:get_unlocked_entry
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:wait_transaction_locked
  - block/blk-rq-qos.c:rq_qos_wait
  - io_uring/io_uring.c:io_cqring_wait
  - lib/sbitmap.c:sbitmap_prepare_to_wait
  - lib/sbitmap.c:sbitmap_prepare_to_wait
  - net/core/sock.c:__lock_sock
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
ffffffff81176d30-ffffffff81176dbb: prepare_to_wait_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool prepare_to_wait_exclusive(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry, int state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff822346d1)
Location: kernel/sched/wait.c:245
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__wait_on_bit_lock
Direct callers:
  - kernel/workqueue.c:__cancel_work_timer
  - fs/dax.c:get_unlocked_entry
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:wait_transaction_locked
  - block/blk-rq-qos.c:rq_qos_wait
  - io_uring/io_uring.c:io_cqring_wait
  - lib/sbitmap.c:sbitmap_prepare_to_wait
  - lib/sbitmap.c:sbitmap_prepare_to_wait
  - net/core/sock.c:__lock_sock
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
ffffffff81184cf0-ffffffff81184d7b: prepare_to_wait_exclusive (STB_GLOBAL)
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
void prepare_to_wait_exclusive(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffff800010158b38)
Location: kernel/sched/wait.c:236
Inline: False
Direct callers:
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - fs/io_uring.c:__arm64_sys_io_uring_enter
  - fs/dax.c:get_unlocked_entry
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-rq-qos.c:rq_qos_wait
  - lib/sbitmap.c:sbitmap_prepare_to_wait
  - lib/sbitmap.c:sbitmap_prepare_to_wait
  - net/core/sock.c:__lock_sock
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
ffff800010158b38-ffff800010158c50: prepare_to_wait_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void prepare_to_wait_exclusive(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (c03a5c18)
Location: kernel/sched/wait.c:236
Inline: False
Direct callers:
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - fs/io_uring.c:__se_sys_io_uring_enter
  - block/blk-rq-qos.c:rq_qos_wait
  - lib/sbitmap.c:sbitmap_prepare_to_wait
  - net/core/sock.c:__lock_sock
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
c03a5c18-c03a5cd4: prepare_to_wait_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void prepare_to_wait_exclusive(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (c0000000001acc80)
Location: kernel/sched/wait.c:236
Inline: False
Direct callers:
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/dax.c:get_unlocked_entry
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-rq-qos.c:rq_qos_wait
  - lib/sbitmap.c:sbitmap_prepare_to_wait
  - lib/sbitmap.c:sbitmap_prepare_to_wait
  - net/core/sock.c:__lock_sock
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
c0000000001acc80-c0000000001acd54: prepare_to_wait_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void prepare_to_wait_exclusive(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffe0000feb24)
Location: kernel/sched/wait.c:236
Inline: False
Direct callers:
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/dax.c:get_unlocked_entry
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-rq-qos.c:rq_qos_wait
  - lib/sbitmap.c:sbitmap_prepare_to_wait
  - lib/sbitmap.c:sbitmap_prepare_to_wait
  - net/core/sock.c:__lock_sock
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
ffffffe0000feb24-ffffffe0000feb94: prepare_to_wait_exclusive (STB_GLOBAL)
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
void prepare_to_wait_exclusive(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ee930)
Location: kernel/sched/wait.c:236
Inline: False
Direct callers:
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - fs/io_uring.c:io_cqring_wait
  - fs/dax.c:get_unlocked_entry
  - block/blk-rq-qos.c:rq_qos_wait
  - lib/sbitmap.c:sbitmap_prepare_to_wait
  - net/core/sock.c:__lock_sock
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
ffffffff810ee930-ffffffff810ee9ac: prepare_to_wait_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void prepare_to_wait_exclusive(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810de9c0)
Location: kernel/sched/wait.c:236
Inline: False
Direct callers:
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - fs/io_uring.c:io_cqring_wait
  - fs/dax.c:get_unlocked_entry
  - block/blk-rq-qos.c:rq_qos_wait
  - lib/sbitmap.c:sbitmap_prepare_to_wait
  - net/core/sock.c:__lock_sock
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
ffffffff810de9c0-ffffffff810dea3c: prepare_to_wait_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void prepare_to_wait_exclusive(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810eba60)
Location: kernel/sched/wait.c:236
Inline: False
Direct callers:
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - fs/io_uring.c:io_cqring_wait
  - fs/dax.c:get_unlocked_entry
  - block/blk-rq-qos.c:rq_qos_wait
  - lib/sbitmap.c:sbitmap_prepare_to_wait
  - net/core/sock.c:__lock_sock
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
ffffffff810eba60-ffffffff810ebadc: prepare_to_wait_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void prepare_to_wait_exclusive(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810f6ac0)
Location: kernel/sched/wait.c:236
Inline: False
Direct callers:
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/sched/wait_bit.c:__wait_on_bit_lock
  - fs/io_uring.c:io_cqring_wait
  - fs/dax.c:get_unlocked_entry
  - block/blk-rq-qos.c:rq_qos_wait
  - lib/sbitmap.c:sbitmap_prepare_to_wait
  - net/core/sock.c:__lock_sock
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
ffffffff810f6ac0-ffffffff810f6b3c: prepare_to_wait_exclusive (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct wait_queue_head *wq_head</code>
</li>
<li>
<b>Param added. </b>
<code>struct wait_queue_entry *wq_entry</code>
</li>
<li>
<b>Param removed. </b>
<code>wait_queue_head_t *q</code>
</li>
<li>
<b>Param removed. </b>
<code>wait_queue_t *wait</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
