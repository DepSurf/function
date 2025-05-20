# Function: <code>wq_has_sleeper</code>

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
In net/core/sock.c (ffffffff81700eec)
Location: include/net/sock.h:1917
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff8170e2dc)
Location: include/net/sock.h:1917
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff817be80d)
Location: include/net/sock.h:1917
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
In net/core/sock.c (ffffffff81767a71)
Location: include/linux/wait.h:148
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff81775a16)
Location: include/linux/wait.h:148
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff8182bd44)
Location: include/linux/wait.h:148
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/core/sock.c (ffffffff81794a91)
Location: include/linux/wait.h:148
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff817a2fe6)
Location: include/linux/wait.h:148
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff8185d770)
Location: include/linux/wait.h:148
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/core/sock.c (ffffffff817b2c81)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff817c1132)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff81881f40)
Location: include/linux/wait.h:135
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In kernel/bpf/sockmap.c (ffffffff811b171d)
Location: include/linux/wait.h:137
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:smap_state_change
```
```
In mm/compaction.c (ffffffff812024d6)
Location: include/linux/wait.h:137
Inline: True
Inline callers:
  - mm/compaction.c:wakeup_kcompactd
```
```
In net/core/sock.c (ffffffff8182af75)
Location: include/linux/wait.h:137
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff8183ab55)
Location: include/linux/wait.h:137
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff81902ff0)
Location: include/linux/wait.h:137
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In mm/compaction.c (ffffffff81223886)
Location: include/linux/wait.h:137
Inline: True
Inline callers:
  - mm/compaction.c:wakeup_kcompactd
```
```
In drivers/char/random.c (ffffffff81647314)
Location: include/linux/wait.h:137
Inline: True
Inline callers:
  - drivers/char/random.c:credit_entropy_bits
```
```
In net/core/sock.c (ffffffff81875061)
Location: include/linux/wait.h:137
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff81885294)
Location: include/linux/wait.h:137
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff8195b2c4)
Location: include/linux/wait.h:137
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In mm/compaction.c (ffffffff812368e6)
Location: include/linux/wait.h:137
Inline: True
Inline callers:
  - mm/compaction.c:wakeup_kcompactd
```
```
In block/blk-rq-qos.c (ffffffff814bdaf8)
Location: include/linux/wait.h:137
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In block/blk-wbt.c (ffffffff814ccc84)
Location: include/linux/wait.h:137
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
  - block/blk-wbt.c:rwb_wake_all
```
```
In drivers/char/random.c (ffffffff816657b4)
Location: include/linux/wait.h:137
Inline: True
Inline callers:
  - drivers/char/random.c:credit_entropy_bits
```
```
In drivers/md/dm.c (ffffffff818335f4)
Location: include/linux/wait.h:137
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
```
```
In drivers/md/dm-rq.c (ffffffff818419d5)
Location: include/linux/wait.h:137
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:rq_completed
```
```
In net/core/sock.c (ffffffff81895931)
Location: include/linux/wait.h:137
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff818a59c9)
Location: include/linux/wait.h:137
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff8198fb04)
Location: include/linux/wait.h:137
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In mm/compaction.c (ffffffff81247e21)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - mm/compaction.c:wakeup_kcompactd
```
```
In fs/io_uring.c (ffffffff8132e09a)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - fs/io_uring.c:io_commit_cqring
```
```
In block/blk-rq-qos.c (ffffffff814ec1a1)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In block/blk-wbt.c (ffffffff814fb6f8)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
  - block/blk-wbt.c:rwb_wake_all
```
```
In drivers/char/random.c (ffffffff8169b3e7)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - drivers/char/random.c:credit_entropy_bits
```
```
In drivers/md/dm.c (ffffffff81875530)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
```
```
In drivers/md/dm-rq.c (ffffffff818847f5)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:rq_completed
```
```
In net/core/sock.c (ffffffff818e0bfb)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff818f0cd9)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff819fb261)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
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
In mm/compaction.c (ffffffff81256281)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - mm/compaction.c:wakeup_kcompactd
```
```
In fs/io_uring.c (ffffffff8134154c)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - fs/io_uring.c:io_commit_cqring
```
```
In block/blk-rq-qos.c (ffffffff815055f1)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In block/blk-wbt.c (ffffffff81519648)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
  - block/blk-wbt.c:rwb_wake_all
```
```
In drivers/char/random.c (ffffffff816be107)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - drivers/char/random.c:credit_entropy_bits
```
```
In drivers/md/dm.c (ffffffff818a72e0)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
```
```
In drivers/md/dm-rq.c (ffffffff818b66e5)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:rq_completed
```
```
In net/core/sock.c (ffffffff81912dcb)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff81922c4e)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff81a31ef1)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
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
In mm/compaction.c (ffffffff81284918)
Location: include/linux/wait.h:151
Inline: True
Inline callers:
  - mm/compaction.c:wakeup_kcompactd
```
```
In fs/io_uring.c (ffffffff8137b16a)
Location: include/linux/wait.h:151
Inline: True
Inline callers:
  - fs/io_uring.c:io_iopoll_req_issued
  - fs/io_uring.c:io_commit_cqring
```
```
In block/blk-rq-qos.c (ffffffff81565fb1)
Location: include/linux/wait.h:151
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In block/blk-wbt.c (ffffffff8157a291)
Location: include/linux/wait.h:151
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_update_limits
  - block/blk-wbt.c:wbt_rqw_done
  - block/blk-wbt.c:wbt_rqw_done
```
```
In drivers/md/dm.c (ffffffff8197700c)
Location: include/linux/wait.h:151
Inline: True
Inline callers:
  - drivers/md/dm.c:end_io_acct
```
```
In net/core/sock.c (ffffffff819e4b9b)
Location: include/linux/wait.h:151
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff819f66ca)
Location: include/linux/wait.h:151
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff81b260c1)
Location: include/linux/wait.h:151
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
```
```
In net/mptcp/subflow.c (ffffffff81baf90c)
Location: include/linux/wait.h:151
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
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
In mm/compaction.c (ffffffff8128ec38)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - mm/compaction.c:wakeup_kcompactd
```
```
In fs/io_uring.c (ffffffff81399c7b)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - fs/io_uring.c:__io_sq_thread
  - fs/io_uring.c:io_issue_sqe
```
```
In block/blk-rq-qos.c (ffffffff81580f31)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In block/blk-wbt.c (ffffffff8159717f)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_queue_depth_changed
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_rqw_done
  - block/blk-wbt.c:wbt_rqw_done
```
```
In drivers/md/dm.c (ffffffff8197bdac)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - drivers/md/dm.c:end_io_acct
```
```
In net/core/sock.c (ffffffff819e440b)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff819f62ab)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff81b34cb0)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
```
```
In net/mptcp/subflow.c (ffffffff81bc30bf)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
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
In mm/compaction.c (ffffffff812942b8)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - mm/compaction.c:wakeup_kcompactd
```
```
In fs/io_uring.c (ffffffff8139e65e)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_issue_sqe
```
```
In fs/io-wq.c (ffffffff813a2e9b)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - fs/io-wq.c:io_worker_handle_work
```
```
In block/blk-rq-qos.c (ffffffff81588a8d)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In block/blk-wbt.c (ffffffff8159df3f)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_queue_depth_changed
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_rqw_done
  - block/blk-wbt.c:wbt_rqw_done
```
```
In drivers/md/dm.c (ffffffff819608ce)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
```
```
In net/core/sock.c (ffffffff819ca49b)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff819dc437)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff81b22890)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
```
```
In net/mptcp/subflow.c (ffffffff81bb37cb)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
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
In mm/compaction.c (ffffffff812d48e8)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - mm/compaction.c:wakeup_kcompactd
```
```
In fs/io_uring.c (ffffffff813ee9ee)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_cqring_ev_posted
```
```
In fs/io-wq.c (ffffffff813f2487)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - fs/io-wq.c:io_worker_handle_work
```
```
In block/blk-rq-qos.c (ffffffff815ee7a1)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In block/blk-wbt.c (ffffffff81606628)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_queue_depth_changed
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_rqw_done
  - block/blk-wbt.c:wbt_rqw_done
```
```
In drivers/md/dm.c (ffffffff81a0a2c6)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_io_dec_pending
```
```
In net/core/sock.c (ffffffff81a79a3b)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff81a8c677)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff81bea794)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
```
```
In net/mptcp/subflow.c (ffffffff81c81eff)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
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
In kernel/printk/printk.c (ffffffff8115bcf0)
Location: include/linux/wait.h:153
Inline: True
```
```
In mm/compaction.c (ffffffff81333917)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - mm/compaction.c:wakeup_kcompactd
```
```
In block/blk-rq-qos.c (ffffffff8169f071)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In block/blk-wbt.c (ffffffff816ba392)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_queue_depth_changed
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_rqw_done
  - block/blk-wbt.c:wbt_rqw_done
```
```
In io_uring/io_uring.c (ffffffff816d8a74)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:io_rsrc_put_work
  - io_uring/io_uring.c:io_sq_thread
  - io_uring/io_uring.c:io_issue_sqe
  - io_uring/io_uring.c:io_poll_task_func
  - io_uring/io_uring.c:io_poll_check_events
  - io_uring/io_uring.c:io_accept
  - io_uring/io_uring.c:io_msg_ring
  - io_uring/io_uring.c:io_do_iopoll
  - io_uring/io_uring.c:__io_submit_flush_completions
  - io_uring/io_uring.c:io_free_batch_list
  - io_uring/io_uring.c:handle_prev_tw_list
  - io_uring/io_uring.c:handle_prev_tw_list
  - io_uring/io_uring.c:io_req_complete_post
  - io_uring/io_uring.c:__io_cqring_overflow_flush
```
```
In io_uring/io-wq.c (ffffffff816daecd)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_worker_handle_work
```
```
In drivers/md/dm.c (ffffffff81b71fd0)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_io_complete
```
```
In net/core/sock.c (ffffffff81beddd0)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff81c01efa)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff81d82b49)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
```
```
In net/mptcp/subflow.c (ffffffff81e27c14)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
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
In kernel/printk/printk.c (ffffffff8118e740)
Location: include/linux/wait.h:153
Inline: True
```
```
In mm/vmscan.c (ffffffff81382224)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - mm/vmscan.c:try_to_inc_max_seq
  - mm/vmscan.c:walk_pud_range
```
```
In mm/compaction.c (ffffffff813aa647)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - mm/compaction.c:wakeup_kcompactd
```
```
In block/blk-rq-qos.c (ffffffff8175d931)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In block/blk-wbt.c (ffffffff8177a912)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_queue_depth_changed
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_rqw_done
  - block/blk-wbt.c:wbt_rqw_done
```
```
In io_uring/io_uring.c (ffffffff8178c27b)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:io_issue_sqe
```
```
In io_uring/sqpoll.c (ffffffff8179a5c3)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread
```
```
In io_uring/io-wq.c (ffffffff817a6fbb)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_worker_handle_work
```
```
In drivers/md/dm.c (ffffffff81d0e95a)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_io_complete
```
```
In net/core/sock.c (ffffffff81d9ad60)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff81db12da)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff81f50159)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
```
```
In net/mptcp/subflow.c (ffffffff81fffb44)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
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
In kernel/printk/printk.c (ffffffff811a00a0)
Location: include/linux/wait.h:153
Inline: True
```
```
In mm/compaction.c (ffffffff813dd768)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - mm/compaction.c:wakeup_kcompactd
```
```
In crypto/jitterentropy-testing.c (ffffffff8175e271)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - crypto/jitterentropy-testing.c:jent_raw_hires_entropy_store
```
```
In block/blk-rq-qos.c (ffffffff8179c691)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In block/blk-wbt.c (ffffffff817ba864)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_update_limits
  - block/blk-wbt.c:wbt_rqw_done
```
```
In io_uring/io_uring.c (ffffffff817cd4da)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:io_issue_sqe
  - io_uring/io_uring.c:__io_submit_flush_completions
  - io_uring/io_uring.c:io_aux_cqe
  - io_uring/io_uring.c:io_cq_unlock_post
  - io_uring/io_uring.c:__io_commit_cqring_flush
```
```
In io_uring/sqpoll.c (ffffffff817db619)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread
```
```
In io_uring/rw.c (ffffffff817e5e4c)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - io_uring/rw.c:io_do_iopoll
```
```
In io_uring/io-wq.c (ffffffff817e80ee)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_worker_handle_work
```
```
In drivers/md/dm.c (ffffffff81d76d09)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_io_complete
```
```
In net/core/sock.c (ffffffff81e095e0)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff81e217ea)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff81faf9b5)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
```
```
In net/mptcp/subflow.c (ffffffff8207bae2)
Location: include/linux/wait.h:153
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
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
In kernel/printk/printk.c (ffffffff811af0a0)
Location: include/linux/wait.h:151
Inline: True
```
```
In mm/compaction.c (ffffffff814076c8)
Location: include/linux/wait.h:151
Inline: True
Inline callers:
  - mm/compaction.c:wakeup_kcompactd
```
```
In block/blk-rq-qos.c (ffffffff817e00f1)
Location: include/linux/wait.h:151
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In block/blk-wbt.c (ffffffff817fefd4)
Location: include/linux/wait.h:151
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_update_limits
  - block/blk-wbt.c:wbt_rqw_done
```
```
In io_uring/io_uring.c (ffffffff81815556)
Location: include/linux/wait.h:151
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_issue_sqe
  - io_uring/io_uring.c:__io_submit_flush_completions
  - io_uring/io_uring.c:io_fill_cqe_req_aux
  - io_uring/io_uring.c:io_cq_unlock_post
  - io_uring/io_uring.c:__io_commit_cqring_flush
```
```
In io_uring/sqpoll.c (ffffffff8181f964)
Location: include/linux/wait.h:151
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread
```
```
In io_uring/register.c (ffffffff8182ba11)
Location: include/linux/wait.h:151
Inline: True
Inline callers:
  - io_uring/register.c:__io_uring_register
  - io_uring/register.c:__io_uring_register
```
```
In io_uring/io-wq.c (ffffffff8182dea3)
Location: include/linux/wait.h:151
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_worker_handle_work
```
```
In drivers/md/dm.c (ffffffff81e2df39)
Location: include/linux/wait.h:151
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_io_complete
```
```
In net/core/sock.c (ffffffff81ec5fd0)
Location: include/linux/wait.h:151
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff81edf70a)
Location: include/linux/wait.h:151
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff8207cfb5)
Location: include/linux/wait.h:151
Inline: True
Inline callers:
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
```
```
In net/mptcp/subflow.c (ffffffff82150ee2)
Location: include/linux/wait.h:151
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
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
In mm/compaction.c (ffff8000102ed8bc)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - mm/compaction.c:wakeup_kcompactd
```
```
In fs/io_uring.c (ffff800010401614)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - fs/io_uring.c:io_commit_cqring
```
```
In block/blk-rq-qos.c (ffff800010607754)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In block/blk-wbt.c (ffff8000106210c8)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
  - block/blk-wbt.c:rwb_wake_all
```
```
In drivers/char/random.c (ffff8000108aecc4)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - drivers/char/random.c:credit_entropy_bits
```
```
In drivers/md/dm.c (ffff800010afe5b0)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
```
```
In drivers/md/dm-rq.c (ffff800010b0e708)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:rq_completed
```
```
In net/core/sock.c (ffff800010baa4f8)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffff800010bbd8d4)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffff800010cf2dc8)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
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
In mm/compaction.c (c0511868)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - mm/compaction.c:wakeup_kcompactd
```
```
In fs/io_uring.c (c05d35ac)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - fs/io_uring.c:io_commit_cqring
```
```
In block/blk-rq-qos.c (c07b2908)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In block/blk-wbt.c (c07c88a8)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
  - block/blk-wbt.c:rwb_wake_all
```
```
In drivers/char/random.c (c09aabc8)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - drivers/char/random.c:credit_entropy_bits
```
```
In drivers/md/dm.c (c0bdccf4)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
```
```
In drivers/md/dm-rq.c (c0becb1c)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:rq_completed
```
```
In net/core/sock.c (c0cc904c)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (c0cd9a1c)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (c0df9180)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
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
In mm/compaction.c (c0000000003b1730)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - mm/compaction.c:wakeup_kcompactd
```
```
In fs/io_uring.c (c00000000050b240)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - fs/io_uring.c:io_commit_cqring
```
```
In block/blk-rq-qos.c (c0000000007a4378)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In block/blk-wbt.c (c0000000007c0f20)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
  - block/blk-wbt.c:rwb_wake_all
```
```
In drivers/char/random.c (c0000000009471bc)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - drivers/char/random.c:credit_entropy_bits
```
```
In drivers/md/dm.c (c000000000beacb4)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
```
```
In drivers/md/dm-rq.c (c000000000c016e0)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:rq_completed
```
```
In net/core/sock.c (c000000000c8090c)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (c000000000c96c70)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (c000000000e16ea0)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
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
In mm/compaction.c (ffffffe000201dac)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - mm/compaction.c:wakeup_kcompactd
```
```
In fs/io_uring.c (ffffffe0002ad8cc)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - fs/io_uring.c:io_commit_cqring
```
```
In block/blk-rq-qos.c (ffffffe0004422fa)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In block/blk-wbt.c (ffffffe000453534)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
  - block/blk-wbt.c:rwb_wake_all
```
```
In drivers/char/random.c (ffffffe000562810)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - drivers/char/random.c:credit_entropy_bits
```
```
In drivers/md/dm.c (ffffffe0006ed846)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
```
```
In drivers/md/dm-rq.c (ffffffe0006fba1a)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:rq_completed
```
```
In net/core/sock.c (ffffffe00073deac)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffe00074bcfe)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffe00083ebfe)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
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
In mm/compaction.c (ffffffff8124e8d1)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - mm/compaction.c:wakeup_kcompactd
```
```
In fs/io_uring.c (ffffffff81339b2c)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - fs/io_uring.c:io_commit_cqring
```
```
In block/blk-rq-qos.c (ffffffff814fdbd1)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In block/blk-wbt.c (ffffffff81511c28)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
  - block/blk-wbt.c:rwb_wake_all
```
```
In drivers/char/random.c (ffffffff81683b77)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - drivers/char/random.c:credit_entropy_bits
```
```
In drivers/md/dm.c (ffffffff8184d160)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
```
```
In drivers/md/dm-rq.c (ffffffff8185c565)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:rq_completed
```
```
In net/core/sock.c (ffffffff818b2dcb)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff818c2c4e)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff819d1581)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
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
In mm/compaction.c (ffffffff81241871)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - mm/compaction.c:wakeup_kcompactd
```
```
In fs/io_uring.c (ffffffff8132a85c)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - fs/io_uring.c:io_commit_cqring
```
```
In block/blk-rq-qos.c (ffffffff814ee0e1)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In block/blk-wbt.c (ffffffff81501f48)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
  - block/blk-wbt.c:rwb_wake_all
```
```
In drivers/char/random.c (ffffffff816617f7)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - drivers/char/random.c:credit_entropy_bits
```
```
In drivers/md/dm.c (ffffffff81814780)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
```
```
In drivers/md/dm-rq.c (ffffffff81823b35)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:rq_completed
```
```
In net/core/sock.c (ffffffff8186cd1b)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff8187cb8e)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff8198e341)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
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
In mm/compaction.c (ffffffff8124c671)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - mm/compaction.c:wakeup_kcompactd
```
```
In fs/io_uring.c (ffffffff813375fc)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - fs/io_uring.c:io_commit_cqring
```
```
In block/blk-rq-qos.c (ffffffff814f9c61)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In block/blk-wbt.c (ffffffff8150dcb8)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
  - block/blk-wbt.c:rwb_wake_all
```
```
In drivers/char/random.c (ffffffff816b1f47)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - drivers/char/random.c:credit_entropy_bits
```
```
In drivers/md/dm.c (ffffffff8189c790)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
```
```
In drivers/md/dm-rq.c (ffffffff818abb95)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:rq_completed
```
```
In net/core/sock.c (ffffffff81903dcb)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff81913c4e)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff81a3c001)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
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
In mm/compaction.c (ffffffff8125c011)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - mm/compaction.c:wakeup_kcompactd
```
```
In fs/io_uring.c (ffffffff8134a97c)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - fs/io_uring.c:io_commit_cqring
```
```
In block/blk-rq-qos.c (ffffffff81512cc1)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In block/blk-wbt.c (ffffffff815272d8)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
  - block/blk-wbt.c:rwb_wake_all
```
```
In drivers/char/random.c (ffffffff816cc43d)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - drivers/char/random.c:credit_entropy_bits
```
```
In drivers/md/dm.c (ffffffff818b89d0)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
```
```
In drivers/md/dm-rq.c (ffffffff818c7dd5)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:rq_completed
```
```
In net/core/sock.c (ffffffff81924dd0)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff81934de3)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff81a4799f)
Location: include/linux/wait.h:150
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
```
</details>
</li>
</ul>

## Differences
