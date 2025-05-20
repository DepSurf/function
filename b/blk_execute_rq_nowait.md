# Function: <code>blk_execute_rq_nowait</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_execute_rq_nowait(struct request_queue *q, struct gendisk *bd_disk, struct request *rq, int at_head, rq_end_io_fn *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-exec.c (ffffffff813bf8c0)
Location: block/blk-exec.c:51
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq
  - block/bsg.c:bsg_write
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
**Symbols:**

```
ffffffff813bf8c0-ffffffff813bfa1e: blk_execute_rq_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_execute_rq_nowait(struct request_queue *q, struct gendisk *bd_disk, struct request *rq, int at_head, rq_end_io_fn *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-exec.c (ffffffff81403800)
Location: block/blk-exec.c:51
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq
  - block/bsg.c:bsg_write
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
**Symbols:**

```
ffffffff81403800-ffffffff81403959: blk_execute_rq_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_execute_rq_nowait(struct request_queue *q, struct gendisk *bd_disk, struct request *rq, int at_head, rq_end_io_fn *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-exec.c (ffffffff8141d560)
Location: block/blk-exec.c:51
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq
  - block/bsg.c:bsg_write
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
**Symbols:**

```
ffffffff8141d560-ffffffff8141d6b8: blk_execute_rq_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_execute_rq_nowait(struct request_queue *q, struct gendisk *bd_disk, struct request *rq, int at_head, rq_end_io_fn *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-exec.c (ffffffff8142b5b0)
Location: block/blk-exec.c:47
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq
  - block/bsg.c:bsg_write
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
**Symbols:**

```
ffffffff8142b5b0-ffffffff8142b6ab: blk_execute_rq_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_execute_rq_nowait(struct request_queue *q, struct gendisk *bd_disk, struct request *rq, int at_head, rq_end_io_fn *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-exec.c (ffffffff814567c0)
Location: block/blk-exec.c:47
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq
  - block/bsg.c:bsg_write
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
**Symbols:**

```
ffffffff814567c0-ffffffff814568bb: blk_execute_rq_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_execute_rq_nowait(struct request_queue *q, struct gendisk *bd_disk, struct request *rq, int at_head, rq_end_io_fn *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-exec.c (ffffffff81489c00)
Location: block/blk-exec.c:47
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq
  - block/bsg.c:bsg_write
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
**Symbols:**

```
ffffffff81489c00-ffffffff81489cf8: blk_execute_rq_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_execute_rq_nowait(struct request_queue *q, struct gendisk *bd_disk, struct request *rq, int at_head, rq_end_io_fn *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-exec.c (ffffffff814a3a10)
Location: block/blk-exec.c:47
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
**Symbols:**

```
ffffffff814a3a10-ffffffff814a3a5e: blk_execute_rq_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void blk_execute_rq_nowait(struct request_queue *q, struct gendisk *bd_disk, struct request *rq, int at_head, rq_end_io_fn *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-exec.c (0)
Location: block/blk-exec.c:48
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
**Symbols:**

```
ffffffff814d1d65-ffffffff814d1db7: blk_execute_rq_nowait.cold (STB_LOCAL)
ffffffff814d1c20-ffffffff814d1c83: blk_execute_rq_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_execute_rq_nowait(struct request_queue *q, struct gendisk *bd_disk, struct request *rq, int at_head, rq_end_io_fn *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-exec.c (ffffffff814eafd0)
Location: block/blk-exec.c:48
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
**Symbols:**

```
ffffffff814eafd0-ffffffff814eb01e: blk_execute_rq_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_execute_rq_nowait(struct request_queue *q, struct gendisk *bd_disk, struct request *rq, int at_head, rq_end_io_fn *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-exec.c (ffffffff8154acf0)
Location: block/blk-exec.c:48
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq
  - drivers/scsi/scsi_error.c:scsi_eh_lock_door
```
**Symbols:**

```
ffffffff8154acf0-ffffffff8154ad55: blk_execute_rq_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_execute_rq_nowait(struct request_queue *q, struct gendisk *bd_disk, struct request *rq, int at_head, rq_end_io_fn *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-exec.c (ffffffff81566ab0)
Location: block/blk-exec.c:48
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq
  - drivers/scsi/scsi_error.c:scsi_eh_lock_door
```
**Symbols:**

```
ffffffff81566ab0-ffffffff81566b15: blk_execute_rq_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_execute_rq_nowait(struct gendisk *bd_disk, struct request *rq, int at_head, rq_end_io_fn *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-exec.c (ffffffff8156eff0)
Location: block/blk-exec.c:47
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq
```
**Symbols:**

```
ffffffff8156eff0-ffffffff8156f055: blk_execute_rq_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_execute_rq_nowait(struct gendisk *bd_disk, struct request *rq, int at_head, rq_end_io_fn *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-exec.c (ffffffff815d3630)
Location: block/blk-exec.c:47
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq
```
**Symbols:**

```
ffffffff815d3630-ffffffff815d36a3: blk_execute_rq_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_execute_rq_nowait(struct request *rq, bool at_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81689390)
Location: block/blk-mq.c:1203
Inline: False
```
**Symbols:**

```
ffffffff81689390-ffffffff81689478: blk_execute_rq_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_execute_rq_nowait(struct request *rq, bool at_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81747950)
Location: block/blk-mq.c:1323
Inline: False
```
**Symbols:**

```
ffffffff81747950-ffffffff81747a38: blk_execute_rq_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_execute_rq_nowait(struct request *rq, bool at_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81783580)
Location: block/blk-mq.c:1326
Inline: False
```
**Symbols:**

```
ffffffff81783580-ffffffff817836fa: blk_execute_rq_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_execute_rq_nowait(struct request *rq, bool at_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c58e0)
Location: block/blk-mq.c:1329
Inline: False
```
**Symbols:**

```
ffffffff817c58e0-ffffffff817c5a6e: blk_execute_rq_nowait (STB_GLOBAL)
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
void blk_execute_rq_nowait(struct request_queue *q, struct gendisk *bd_disk, struct request *rq, int at_head, rq_end_io_fn *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-exec.c (ffff8000105e9a08)
Location: block/blk-exec.c:48
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
**Symbols:**

```
ffff8000105e9a08-ffff8000105e9a88: blk_execute_rq_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_execute_rq_nowait(struct request_queue *q, struct gendisk *bd_disk, struct request *rq, int at_head, rq_end_io_fn *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-exec.c (c0795e4c)
Location: block/blk-exec.c:48
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
**Symbols:**

```
c0795e4c-c0795ee4: blk_execute_rq_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_execute_rq_nowait(struct request_queue *q, struct gendisk *bd_disk, struct request *rq, int at_head, rq_end_io_fn *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-exec.c (c00000000077e7b0)
Location: block/blk-exec.c:48
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
**Symbols:**

```
c00000000077e7b0-c00000000077e824: blk_execute_rq_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_execute_rq_nowait(struct request_queue *q, struct gendisk *bd_disk, struct request *rq, int at_head, rq_end_io_fn *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-exec.c (ffffffe000429f24)
Location: block/blk-exec.c:48
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
**Symbols:**

```
ffffffe000429f24-ffffffe000429f8a: blk_execute_rq_nowait (STB_GLOBAL)
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
void blk_execute_rq_nowait(struct request_queue *q, struct gendisk *bd_disk, struct request *rq, int at_head, rq_end_io_fn *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-exec.c (ffffffff814e35b0)
Location: block/blk-exec.c:48
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/nvme/host/core.c:__nvme_submit_sync_cmd
  - drivers/nvme/host/lightnvm.c:nvme_nvm_submit_io
  - drivers/nvme/host/pci.c:__nvme_disable_io_queues
  - drivers/nvme/host/pci.c:nvme_timeout
```
**Symbols:**

```
ffffffff814e35b0-ffffffff814e35fe: blk_execute_rq_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_execute_rq_nowait(struct request_queue *q, struct gendisk *bd_disk, struct request *rq, int at_head, rq_end_io_fn *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-exec.c (ffffffff814d3f30)
Location: block/blk-exec.c:48
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/nvme/host/core.c:__nvme_submit_sync_cmd
  - drivers/nvme/host/pci.c:__nvme_disable_io_queues
  - drivers/nvme/host/pci.c:nvme_timeout
```
**Symbols:**

```
ffffffff814d3f30-ffffffff814d3f79: blk_execute_rq_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_execute_rq_nowait(struct request_queue *q, struct gendisk *bd_disk, struct request *rq, int at_head, rq_end_io_fn *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-exec.c (ffffffff814df640)
Location: block/blk-exec.c:48
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
**Symbols:**

```
ffffffff814df640-ffffffff814df68e: blk_execute_rq_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_execute_rq_nowait(struct request_queue *q, struct gendisk *bd_disk, struct request *rq, int at_head, rq_end_io_fn *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-exec.c (ffffffff814f84b0)
Location: block/blk-exec.c:48
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
**Symbols:**

```
ffffffff814f84b0-ffffffff814f84fe: blk_execute_rq_nowait (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct request_queue *q</code>
</li>
<li>
<b>Param reordered. </b>
<code>q, bd_disk, rq, at_head, done</code> ➡️ <code>bd_disk, rq, at_head, done</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct gendisk *bd_disk</code>
</li>
<li>
<b>Param removed. </b>
<code>rq_end_io_fn *done</code>
</li>
<li>
<b>Param reordered. </b>
<code>bd_disk, rq, at_head, done</code> ➡️ <code>rq, at_head</code>
</li>
<li>
<b>Param type changed. </b>
<code>int at_head</code> ➡️ <code>bool at_head</code>
</li>
</ul>
</details>
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
