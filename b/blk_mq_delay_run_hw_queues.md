# Function: <code>blk_mq_delay_run_hw_queues</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_mq_delay_run_hw_queues(struct request_queue *q, long unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815501c0)
Location: block/blk-mq.c:1582
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:blk_mq_do_dispatch_sched
```
**Symbols:**

```
ffffffff815501c0-ffffffff8155020e: blk_mq_delay_run_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_mq_delay_run_hw_queues(struct request_queue *q, long unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156c690)
Location: block/blk-mq.c:1673
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
**Symbols:**

```
ffffffff8156c690-ffffffff8156c6de: blk_mq_delay_run_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_mq_delay_run_hw_queues(struct request_queue *q, long unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815740a0)
Location: block/blk-mq.c:1683
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
**Symbols:**

```
ffffffff815740a0-ffffffff8157416b: blk_mq_delay_run_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_mq_delay_run_hw_queues(struct request_queue *q, long unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815d85b0)
Location: block/blk-mq.c:1694
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
**Symbols:**

```
ffffffff815d85b0-ffffffff815d867b: blk_mq_delay_run_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_mq_delay_run_hw_queues(struct request_queue *q, long unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81684cd0)
Location: block/blk-mq.c:2200
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
**Symbols:**

```
ffffffff81684cd0-ffffffff81684e12: blk_mq_delay_run_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_mq_delay_run_hw_queues(struct request_queue *q, long unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817427b0)
Location: block/blk-mq.c:2363
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
**Symbols:**

```
ffffffff817427b0-ffffffff817428f2: blk_mq_delay_run_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_mq_delay_run_hw_queues(struct request_queue *q, long unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8177df00)
Location: block/blk-mq.c:2325
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
**Symbols:**

```
ffffffff8177df00-ffffffff8177e040: blk_mq_delay_run_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_mq_delay_run_hw_queues(struct request_queue *q, long unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c0570)
Location: block/blk-mq.c:2344
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_ctx
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
**Symbols:**

```
ffffffff817c0570-ffffffff817c06ad: blk_mq_delay_run_hw_queues (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
