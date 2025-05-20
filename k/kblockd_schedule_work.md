# Function: <code>kblockd_schedule_work</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kblockd_schedule_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b5c90)
Location: block/blk-core.c:3122
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_kick_requeue_list
  - block/cfq-iosched.c:cfq_idle_slice_timer
  - block/cfq-iosched.c:cfq_put_queue
  - block/cfq-iosched.c:cfq_exit_cfqq
  - block/cfq-iosched.c:cfq_completed_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
**Symbols:**

```
ffffffff813b5c90-ffffffff813b5cb2: kblockd_schedule_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int kblockd_schedule_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fab66)
Location: block/blk-core.c:3094
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_timed_out_timer
Direct callers:
  - block/blk-mq.c:blk_mq_kick_requeue_list
  - block/cfq-iosched.c:cfq_idle_slice_timer
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_exit_cfqq
  - block/cfq-iosched.c:cfq_put_queue
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
**Symbols:**

```
ffffffff813fab30-ffffffff813fab52: kblockd_schedule_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int kblockd_schedule_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814144a6)
Location: block/blk-core.c:3088
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_timed_out_timer
Direct callers:
  - block/cfq-iosched.c:cfq_idle_slice_timer
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_exit_cfqq
  - block/cfq-iosched.c:cfq_put_queue
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
**Symbols:**

```
ffffffff81414470-ffffffff81414492: kblockd_schedule_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int kblockd_schedule_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81422026)
Location: block/blk-core.c:3184
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_timed_out_timer
Direct callers:
  - block/cfq-iosched.c:cfq_idle_slice_timer
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_exit_cfqq
  - block/cfq-iosched.c:cfq_put_queue
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
**Symbols:**

```
ffffffff81421ff0-ffffffff81422012: kblockd_schedule_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int kblockd_schedule_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8144ce96)
Location: block/blk-core.c:3408
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_timed_out_timer
Direct callers:
  - block/cfq-iosched.c:cfq_idle_slice_timer
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_exit_cfqq
  - block/cfq-iosched.c:cfq_put_queue
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
**Symbols:**

```
ffffffff8144ce60-ffffffff8144ce82: kblockd_schedule_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int kblockd_schedule_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81480105)
Location: block/blk-core.c:3559
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_timed_out_timer
Direct callers:
  - block/cfq-iosched.c:cfq_idle_slice_timer
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_exit_cfqq
  - block/cfq-iosched.c:cfq_put_queue
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
```
**Symbols:**

```
ffffffff814800d0-ffffffff814800f2: kblockd_schedule_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int kblockd_schedule_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8149d185)
Location: block/blk-core.c:1665
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_timed_out_timer
Direct callers:
  - block/blk-timeout.c:blk_abort_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
**Symbols:**

```
ffffffff8149d150-ffffffff8149d172: kblockd_schedule_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int kblockd_schedule_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cb325)
Location: block/blk-core.c:1616
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_timed_out_timer
Direct callers:
  - block/blk-timeout.c:blk_abort_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
**Symbols:**

```
ffffffff814cb2f0-ffffffff814cb312: kblockd_schedule_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int kblockd_schedule_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814e4515)
Location: block/blk-core.c:1657
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_timed_out_timer
Direct callers:
  - block/blk-timeout.c:blk_abort_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
**Symbols:**

```
ffffffff814e44e0-ffffffff814e4502: kblockd_schedule_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int kblockd_schedule_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81543065)
Location: block/blk-core.c:1754
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_timed_out_timer
Direct callers:
  - block/blk-timeout.c:blk_abort_request
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
**Symbols:**

```
ffffffff81542d60-ffffffff81542d82: kblockd_schedule_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int kblockd_schedule_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8155f8b5)
Location: block/blk-core.c:1648
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_timed_out_timer
Direct callers:
  - block/blk-timeout.c:blk_abort_request
```
**Symbols:**

```
ffffffff8155f670-ffffffff8155f692: kblockd_schedule_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int kblockd_schedule_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81568135)
Location: block/blk-core.c:1640
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_timed_out_timer
Direct callers:
  - block/blk-timeout.c:blk_abort_request
```
**Symbols:**

```
ffffffff81567e10-ffffffff81567e32: kblockd_schedule_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int kblockd_schedule_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815cc725)
Location: block/blk-core.c:1626
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_timed_out_timer
Direct callers:
  - block/blk-timeout.c:blk_abort_request
```
**Symbols:**

```
ffffffff815cc460-ffffffff815cc482: kblockd_schedule_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int kblockd_schedule_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81678475)
Location: block/blk-core.c:1091
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_timed_out_timer
Direct callers:
  - block/blk-timeout.c:blk_abort_request
```
**Symbols:**

```
ffffffff81678220-ffffffff8167824c: kblockd_schedule_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int kblockd_schedule_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81734955)
Location: block/blk-core.c:1029
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_timed_out_timer
Direct callers:
  - block/blk-timeout.c:blk_abort_request
```
**Symbols:**

```
ffffffff817338e0-ffffffff8173390c: kblockd_schedule_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int kblockd_schedule_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81770f25)
Location: block/blk-core.c:1028
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_timed_out_timer
Direct callers:
  - block/blk-timeout.c:blk_abort_request
```
**Symbols:**

```
ffffffff8176fd00-ffffffff8176fd2c: kblockd_schedule_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int kblockd_schedule_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817b32e5)
Location: block/blk-core.c:1063
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_timed_out_timer
Direct callers:
  - block/blk-timeout.c:blk_abort_request
```
**Symbols:**

```
ffffffff817b1f70-ffffffff817b1f9c: kblockd_schedule_work (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int kblockd_schedule_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105e08f8)
Location: block/blk-core.c:1657
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_timed_out_timer
Direct callers:
  - block/blk-timeout.c:blk_abort_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
**Symbols:**

```
ffff8000105e08a0-ffff8000105e08dc: kblockd_schedule_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int kblockd_schedule_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c078eb94)
Location: block/blk-core.c:1657
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_timed_out_timer
Direct callers:
  - block/blk-timeout.c:blk_abort_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
**Symbols:**

```
c078eb50-c078eb80: kblockd_schedule_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int kblockd_schedule_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c000000000774d8c)
Location: block/blk-core.c:1657
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_timed_out_timer
Direct callers:
  - block/blk-timeout.c:blk_abort_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
**Symbols:**

```
c000000000774d20-c000000000774d68: kblockd_schedule_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int kblockd_schedule_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffe000423c2e)
Location: block/blk-core.c:1657
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_timed_out_timer
Direct callers:
  - block/blk-timeout.c:blk_abort_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
**Symbols:**

```
ffffffe000423be2-ffffffe000423c18: kblockd_schedule_work (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int kblockd_schedule_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814dcaf5)
Location: block/blk-core.c:1657
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_timed_out_timer
Direct callers:
  - block/blk-timeout.c:blk_abort_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/nvme/host/multipath.c:nvme_mpath_remove_disk
  - drivers/nvme/host/multipath.c:nvme_mpath_set_live
  - drivers/nvme/host/multipath.c:nvme_mpath_clear_ctrl_paths
  - drivers/nvme/host/multipath.c:nvme_kick_requeue_lists
  - drivers/nvme/host/multipath.c:nvme_failover_req
```
**Symbols:**

```
ffffffff814dcac0-ffffffff814dcae2: kblockd_schedule_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int kblockd_schedule_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cd4a5)
Location: block/blk-core.c:1657
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_timed_out_timer
Direct callers:
  - block/blk-timeout.c:blk_abort_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/nvme/host/multipath.c:nvme_mpath_remove_disk
  - drivers/nvme/host/multipath.c:nvme_mpath_set_live
  - drivers/nvme/host/multipath.c:nvme_mpath_clear_ctrl_paths
  - drivers/nvme/host/multipath.c:nvme_kick_requeue_lists
  - drivers/nvme/host/multipath.c:nvme_failover_req
```
**Symbols:**

```
ffffffff814cd470-ffffffff814cd492: kblockd_schedule_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int kblockd_schedule_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814d8b85)
Location: block/blk-core.c:1657
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_timed_out_timer
Direct callers:
  - block/blk-timeout.c:blk_abort_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
**Symbols:**

```
ffffffff814d8b50-ffffffff814d8b72: kblockd_schedule_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int kblockd_schedule_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814f1795)
Location: block/blk-core.c:1657
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_timed_out_timer
Direct callers:
  - block/blk-timeout.c:blk_abort_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
**Symbols:**

```
ffffffff814f1760-ffffffff814f1782: kblockd_schedule_work (STB_GLOBAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
