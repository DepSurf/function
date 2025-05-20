# Function: <code>blk_mq_run_hw_queues</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_mq_run_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff813c4e00)
Location: block/blk-mq.c:877
Inline: False
Direct callers:
  - drivers/md/dm.c:rq_completed
```
**Symbols:**

```
ffffffff813c4e00-ffffffff813c4e9f: blk_mq_run_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_mq_run_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81408fd0)
Location: block/blk-mq.c:955
Inline: False
```
**Symbols:**

```
ffffffff81408fd0-ffffffff8140906f: blk_mq_run_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_mq_run_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814239a0)
Location: block/blk-mq.c:994
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_requeue_work
```
**Symbols:**

```
ffffffff814239a0-ffffffff81423a30: blk_mq_run_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_mq_run_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81430bc0)
Location: block/blk-mq.c:1183
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_unquiesce_queue
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
**Symbols:**

```
ffffffff81430bc0-ffffffff81430c2a: blk_mq_run_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_mq_run_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145b380)
Location: block/blk-mq.c:1319
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_unquiesce_queue
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
**Symbols:**

```
ffffffff8145b380-ffffffff8145b3d4: blk_mq_run_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_mq_run_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8148e7f0)
Location: block/blk-mq.c:1378
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
**Symbols:**

```
ffffffff8148e7f0-ffffffff8148e843: blk_mq_run_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_mq_run_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814a8180)
Location: block/blk-mq.c:1502
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
**Symbols:**

```
ffffffff814a8180-ffffffff814a81ca: blk_mq_run_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_mq_run_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d6c90)
Location: block/blk-mq.c:1500
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_freeze_queue_start
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_sysfs.c:store_state_field
```
**Symbols:**

```
ffffffff814d6c90-ffffffff814d6cda: blk_mq_run_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_mq_run_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814f0010)
Location: block/blk-mq.c:1516
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_freeze_queue_start
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_sysfs.c:store_state_field
```
**Symbols:**

```
ffffffff814f0010-ffffffff814f005a: blk_mq_run_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_run_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8155466a)
Location: block/blk-mq.c:1563
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_freeze_queue_start
Direct callers:
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
  - drivers/scsi/scsi_lib.c:scsi_single_lun_run
  - drivers/scsi/scsi_lib.c:scsi_single_lun_run
  - drivers/scsi/scsi_sysfs.c:store_state_field
```
**Symbols:**

```
ffffffff81550320-ffffffff8155036a: blk_mq_run_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_run_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81570d8e)
Location: block/blk-mq.c:1654
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_freeze_queue_start
Direct callers:
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
  - drivers/scsi/scsi_lib.c:scsi_single_lun_run
  - drivers/scsi/scsi_lib.c:scsi_single_lun_run
  - drivers/scsi/scsi_sysfs.c:store_state_field
```
**Symbols:**

```
ffffffff8156c7c0-ffffffff8156c80a: blk_mq_run_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_mq_run_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81574250)
Location: block/blk-mq.c:1655
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_freeze_queue_start
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
  - drivers/scsi/scsi_sysfs.c:store_state_field
```
**Symbols:**

```
ffffffff81574250-ffffffff81574317: blk_mq_run_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_mq_run_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815d87a0)
Location: block/blk-mq.c:1666
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_freeze_queue_start
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
  - drivers/scsi/scsi_sysfs.c:store_state_field
```
**Symbols:**

```
ffffffff815d87a0-ffffffff815d8867: blk_mq_run_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_mq_run_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81684f40)
Location: block/blk-mq.c:2172
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_unquiesce_queue
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
  - drivers/scsi/scsi_sysfs.c:store_state_field
```
**Symbols:**

```
ffffffff81684f40-ffffffff81685078: blk_mq_run_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_mq_run_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81742eb0)
Location: block/blk-mq.c:2335
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_unquiesce_queue
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
  - drivers/scsi/scsi_sysfs.c:store_state_field
```
**Symbols:**

```
ffffffff81742eb0-ffffffff81742fe8: blk_mq_run_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_mq_run_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8177e4f0)
Location: block/blk-mq.c:2297
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
  - drivers/scsi/scsi_sysfs.c:store_state_field
```
**Symbols:**

```
ffffffff8177e4f0-ffffffff8177e62b: blk_mq_run_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_mq_run_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c0b90)
Location: block/blk-mq.c:2316
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
  - drivers/scsi/scsi_sysfs.c:store_state_field
```
**Symbols:**

```
ffffffff817c0b90-ffffffff817c0cc8: blk_mq_run_hw_queues (STB_GLOBAL)
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
void blk_mq_run_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105eef68)
Location: block/blk-mq.c:1516
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_freeze_queue_start
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_sysfs.c:store_state_field
  - drivers/mmc/core/block.c:mmc_blk_cqe_complete_rq
  - drivers/mmc/core/queue.c:mmc_mq_recovery_handler
```
**Symbols:**

```
ffff8000105eef68-ffff8000105eefd0: blk_mq_run_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_mq_run_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079b8b0)
Location: block/blk-mq.c:1516
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_freeze_queue_start
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_sysfs.c:store_state_field
  - drivers/mmc/core/block.c:mmc_blk_cqe_complete_rq
  - drivers/mmc/core/queue.c:mmc_mq_recovery_handler
```
**Symbols:**

```
c079b8b0-c079b90c: blk_mq_run_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_mq_run_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000785a80)
Location: block/blk-mq.c:1516
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_freeze_queue_start
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_sysfs.c:store_state_field
```
**Symbols:**

```
c000000000785a80-c000000000785b10: blk_mq_run_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_mq_run_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042e36e)
Location: block/blk-mq.c:1516
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_freeze_queue_start
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_sysfs.c:store_state_field
  - drivers/mmc/core/block.c:mmc_blk_cqe_complete_rq
  - drivers/mmc/core/queue.c:mmc_mq_recovery_handler
```
**Symbols:**

```
ffffffe00042e36e-ffffffe00042e3ce: blk_mq_run_hw_queues (STB_GLOBAL)
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
void blk_mq_run_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e85f0)
Location: block/blk-mq.c:1516
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_freeze_queue_start
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_sysfs.c:store_state_field
```
**Symbols:**

```
ffffffff814e85f0-ffffffff814e863a: blk_mq_run_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_mq_run_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d8b60)
Location: block/blk-mq.c:1516
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_freeze_queue_start
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_sysfs.c:store_state_field
  - drivers/scsi/scsi_transport_fc.c:fc_remote_port_add
```
**Symbols:**

```
ffffffff814d8b60-ffffffff814d8baa: blk_mq_run_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_mq_run_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e4680)
Location: block/blk-mq.c:1516
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_freeze_queue_start
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_sysfs.c:store_state_field
```
**Symbols:**

```
ffffffff814e4680-ffffffff814e46ca: blk_mq_run_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_mq_run_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fcae0)
Location: block/blk-mq.c:1516
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_freeze_queue_start
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_sysfs.c:store_state_field
```
**Symbols:**

```
ffffffff814fcae0-ffffffff814fcb2a: blk_mq_run_hw_queues (STB_GLOBAL)
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
