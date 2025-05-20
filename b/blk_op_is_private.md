# Function: <code>blk_op_is_private</code>

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
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff81182d94)
Location: include/linux/blkdev.h:249
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (0)
Location: include/linux/blkdev.h:249
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/blkdev.h:249
Inline: True
```
```
In block/blk-exec.c (0)
Location: include/linux/blkdev.h:249
Inline: True
```
```
In block/blk-merge.c (ffffffff814588df)
Location: include/linux/blkdev.h:249
Inline: True
Inline callers:
  - block/blk-merge.c:attempt_merge
```
```
In block/blk-mq.c (0)
Location: include/linux/blkdev.h:249
Inline: True
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/blkdev.h:249
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/blkdev.h:249
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/blkdev.h:249
Inline: True
```
```
In drivers/scsi/scsi.c (0)
Location: include/linux/blkdev.h:249
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/blkdev.h:249
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff816b5910)
Location: include/linux/blkdev.h:249
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blkdev.h:249
Inline: True
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
In kernel/trace/blktrace.c (ffffffff81191ee2)
Location: include/linux/blkdev.h:280
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (0)
Location: include/linux/blkdev.h:280
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/blkdev.h:280
Inline: True
```
```
In block/blk-exec.c (0)
Location: include/linux/blkdev.h:280
Inline: True
```
```
In block/blk-merge.c (ffffffff8148baf2)
Location: include/linux/blkdev.h:280
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/blkdev.h:280
Inline: True
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/blkdev.h:280
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/blkdev.h:280
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/blkdev.h:280
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/blkdev.h:280
Inline: True
```
```
In drivers/scsi/scsi.c (0)
Location: include/linux/blkdev.h:280
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/blkdev.h:280
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff816f1b3d)
Location: include/linux/blkdev.h:280
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blkdev.h:280
Inline: True
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
In kernel/trace/blktrace.c (ffffffff8119f711)
Location: include/linux/blkdev.h:249
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (0)
Location: include/linux/blkdev.h:249
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/blkdev.h:249
Inline: True
```
```
In block/blk-exec.c (0)
Location: include/linux/blkdev.h:249
Inline: True
```
```
In block/blk-merge.c (ffffffff814a579f)
Location: include/linux/blkdev.h:249
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/blkdev.h:249
Inline: True
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/blkdev.h:249
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/blkdev.h:249
Inline: True
```
```
In block/mq-deadline.c (0)
Location: include/linux/blkdev.h:249
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/blkdev.h:249
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/blkdev.h:249
Inline: True
```
```
In drivers/scsi/scsi.c (0)
Location: include/linux/blkdev.h:249
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/blkdev.h:249
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/blkdev.h:249
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blkdev.h:249
Inline: True
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
In kernel/trace/blktrace.c (ffffffff811ad45e)
Location: include/linux/blkdev.h:247
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (0)
Location: include/linux/blkdev.h:247
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/blkdev.h:247
Inline: True
```
```
In block/blk-exec.c (0)
Location: include/linux/blkdev.h:247
Inline: True
```
```
In block/blk-merge.c (ffffffff814d3824)
Location: include/linux/blkdev.h:247
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/blkdev.h:247
Inline: True
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/blkdev.h:247
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/blkdev.h:247
Inline: True
```
```
In block/mq-deadline.c (0)
Location: include/linux/blkdev.h:247
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/blkdev.h:247
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/blkdev.h:247
Inline: True
```
```
In drivers/scsi/scsi.c (0)
Location: include/linux/blkdev.h:247
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/blkdev.h:247
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/blkdev.h:247
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blkdev.h:247
Inline: True
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
In kernel/trace/blktrace.c (ffffffff811b8cb0)
Location: include/linux/blkdev.h:254
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/blk-core.c (ffffffff814e677d)
Location: include/linux/blkdev.h:254
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
```
```
In block/blk-exec.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/blk-merge.c (ffffffff814ecb54)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/mq-deadline.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In drivers/scsi/scsi.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blkdev.h:254
Inline: True
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
In kernel/trace/blktrace.c (ffffffff811d17ae)
Location: include/linux/blkdev.h:256
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (0)
Location: include/linux/blkdev.h:256
Inline: True
```
```
In block/blk-core.c (ffffffff81543acc)
Location: include/linux/blkdev.h:256
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
```
```
In block/blk-exec.c (0)
Location: include/linux/blkdev.h:256
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/blkdev.h:256
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/blkdev.h:256
Inline: True
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/blkdev.h:256
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/blkdev.h:256
Inline: True
```
```
In block/mq-deadline.c (0)
Location: include/linux/blkdev.h:256
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/blkdev.h:256
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/blkdev.h:256
Inline: True
```
```
In drivers/scsi/scsi.c (0)
Location: include/linux/blkdev.h:256
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/blkdev.h:256
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/blkdev.h:256
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blkdev.h:256
Inline: True
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
In kernel/trace/blktrace.c (ffffffff811cebb8)
Location: include/linux/blkdev.h:252
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (0)
Location: include/linux/blkdev.h:252
Inline: True
```
```
In block/blk-core.c (ffffffff8156098d)
Location: include/linux/blkdev.h:252
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
```
```
In block/blk-exec.c (0)
Location: include/linux/blkdev.h:252
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/blkdev.h:252
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/blkdev.h:252
Inline: True
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/blkdev.h:252
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/blkdev.h:252
Inline: True
```
```
In block/mq-deadline.c (0)
Location: include/linux/blkdev.h:252
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/blkdev.h:252
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/blkdev.h:252
Inline: True
```
```
In drivers/scsi/scsi.c (0)
Location: include/linux/blkdev.h:252
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/blkdev.h:252
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/blkdev.h:252
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blkdev.h:252
Inline: True
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
In kernel/trace/blktrace.c (ffffffff811d01ac)
Location: include/linux/blkdev.h:247
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (0)
Location: include/linux/blkdev.h:247
Inline: True
```
```
In block/blk-core.c (ffffffff8156900d)
Location: include/linux/blkdev.h:247
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
```
```
In block/blk-exec.c (0)
Location: include/linux/blkdev.h:247
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/blkdev.h:247
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/blkdev.h:247
Inline: True
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/blkdev.h:247
Inline: True
```
```
In block/mq-deadline.c (0)
Location: include/linux/blkdev.h:247
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/blkdev.h:247
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/blkdev.h:247
Inline: True
```
```
In drivers/scsi/scsi.c (0)
Location: include/linux/blkdev.h:247
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/blkdev.h:247
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/blkdev.h:247
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blkdev.h:247
Inline: True
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In kernel/trace/blktrace.c (ffff80001023744c)
Location: include/linux/blkdev.h:254
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/blk-core.c (ffff8000105e3efc)
Location: include/linux/blkdev.h:254
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
```
```
In block/blk-exec.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/mq-deadline.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In drivers/scsi/scsi.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blkdev.h:254
Inline: True
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
In kernel/trace/blktrace.c (c0472d70)
Location: include/linux/blkdev.h:254
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/blk-core.c (c07911ac)
Location: include/linux/blkdev.h:254
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
```
```
In block/blk-exec.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/mq-deadline.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In drivers/scsi/scsi.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blkdev.h:254
Inline: True
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
In kernel/trace/blktrace.c (c0000000002c30d8)
Location: include/linux/blkdev.h:254
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/blk-core.c (c000000000777ba0)
Location: include/linux/blkdev.h:254
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
```
```
In block/blk-exec.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/mq-deadline.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In drivers/scsi/scsi.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blkdev.h:254
Inline: True
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
In kernel/trace/blktrace.c (ffffffe00018e27c)
Location: include/linux/blkdev.h:254
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/blk-core.c (ffffffe000425870)
Location: include/linux/blkdev.h:254
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
```
```
In block/blk-exec.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/mq-deadline.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In drivers/scsi/scsi.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blkdev.h:254
Inline: True
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
In kernel/trace/blktrace.c (ffffffff811b12d0)
Location: include/linux/blkdev.h:254
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/blk-core.c (ffffffff814ded5d)
Location: include/linux/blkdev.h:254
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
```
```
In block/blk-exec.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/blk-merge.c (ffffffff814e5134)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/mq-deadline.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In drivers/scsi/scsi.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blkdev.h:254
Inline: True
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
In kernel/trace/blktrace.c (ffffffff811a4270)
Location: include/linux/blkdev.h:254
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/blk-core.c (ffffffff814cf6fd)
Location: include/linux/blkdev.h:254
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
```
```
In block/blk-exec.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/mq-deadline.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In drivers/scsi/scsi.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blkdev.h:254
Inline: True
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
In kernel/trace/blktrace.c (ffffffff811af0a0)
Location: include/linux/blkdev.h:254
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/blk-core.c (ffffffff814daded)
Location: include/linux/blkdev.h:254
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
```
```
In block/blk-exec.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/blk-merge.c (ffffffff814e11c4)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/mq-deadline.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In drivers/scsi/scsi.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blkdev.h:254
Inline: True
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
In kernel/trace/blktrace.c (ffffffff811bcff0)
Location: include/linux/blkdev.h:254
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/blk-core.c (ffffffff814f3b7d)
Location: include/linux/blkdev.h:254
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
```
```
In block/blk-exec.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/blk-merge.c (ffffffff814fa044)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/mq-deadline.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In drivers/scsi/scsi.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blkdev.h:254
Inline: True
```
</details>
</li>
</ul>

## Differences
