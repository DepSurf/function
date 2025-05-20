# Function: <code>blk_op_is_scsi</code>

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
In kernel/trace/blktrace.c (ffffffff81182d81)
Location: include/linux/blkdev.h:244
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (0)
Location: include/linux/blkdev.h:244
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/blkdev.h:244
Inline: True
```
```
In block/blk-exec.c (0)
Location: include/linux/blkdev.h:244
Inline: True
```
```
In block/blk-merge.c (ffffffff8145878d)
Location: include/linux/blkdev.h:244
Inline: True
Inline callers:
  - block/blk-merge.c:attempt_merge
```
```
In block/blk-mq.c (0)
Location: include/linux/blkdev.h:244
Inline: True
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/blkdev.h:244
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/blkdev.h:244
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/blkdev.h:244
Inline: True
```
```
In drivers/scsi/scsi.c (0)
Location: include/linux/blkdev.h:244
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/blkdev.h:244
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff816b459d)
Location: include/linux/blkdev.h:244
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_setup_cmnd
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blkdev.h:244
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
In kernel/trace/blktrace.c (ffffffff81191ecf)
Location: include/linux/blkdev.h:275
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (0)
Location: include/linux/blkdev.h:275
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/blkdev.h:275
Inline: True
```
```
In block/blk-exec.c (0)
Location: include/linux/blkdev.h:275
Inline: True
```
```
In block/blk-merge.c (ffffffff8148baf2)
Location: include/linux/blkdev.h:275
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/blkdev.h:275
Inline: True
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/blkdev.h:275
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/blkdev.h:275
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/blkdev.h:275
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/blkdev.h:275
Inline: True
```
```
In drivers/scsi/scsi.c (0)
Location: include/linux/blkdev.h:275
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/blkdev.h:275
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff816f06d3)
Location: include/linux/blkdev.h:275
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_setup_cmnd
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blkdev.h:275
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
In kernel/trace/blktrace.c (ffffffff8119f6fe)
Location: include/linux/blkdev.h:244
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (0)
Location: include/linux/blkdev.h:244
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/blkdev.h:244
Inline: True
```
```
In block/blk-exec.c (0)
Location: include/linux/blkdev.h:244
Inline: True
```
```
In block/blk-merge.c (ffffffff814a579f)
Location: include/linux/blkdev.h:244
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/blkdev.h:244
Inline: True
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/blkdev.h:244
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/blkdev.h:244
Inline: True
```
```
In block/mq-deadline.c (0)
Location: include/linux/blkdev.h:244
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/blkdev.h:244
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/blkdev.h:244
Inline: True
```
```
In drivers/scsi/scsi.c (0)
Location: include/linux/blkdev.h:244
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/blkdev.h:244
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff817152ba)
Location: include/linux/blkdev.h:244
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blkdev.h:244
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
In kernel/trace/blktrace.c (ffffffff811ad44d)
Location: include/linux/blkdev.h:242
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (0)
Location: include/linux/blkdev.h:242
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/blkdev.h:242
Inline: True
```
```
In block/blk-exec.c (0)
Location: include/linux/blkdev.h:242
Inline: True
```
```
In block/blk-merge.c (ffffffff814d3824)
Location: include/linux/blkdev.h:242
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/blkdev.h:242
Inline: True
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/blkdev.h:242
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/blkdev.h:242
Inline: True
```
```
In block/mq-deadline.c (0)
Location: include/linux/blkdev.h:242
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/blkdev.h:242
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/blkdev.h:242
Inline: True
```
```
In drivers/scsi/scsi.c (0)
Location: include/linux/blkdev.h:242
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/blkdev.h:242
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81750a66)
Location: include/linux/blkdev.h:242
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blkdev.h:242
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
In kernel/trace/blktrace.c (ffffffff811b8c9d)
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
In block/blk-core.c (ffffffff814e6771)
Location: include/linux/blkdev.h:249
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
```
```
In block/blk-exec.c (0)
Location: include/linux/blkdev.h:249
Inline: True
```
```
In block/blk-merge.c (ffffffff814ecb54)
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
In drivers/scsi/scsi_lib.c (ffffffff81774ca1)
Location: include/linux/blkdev.h:249
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:scsi_end_request
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
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811d179d)
Location: include/linux/blkdev.h:251
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (0)
Location: include/linux/blkdev.h:251
Inline: True
```
```
In block/blk-core.c (ffffffff81543ac0)
Location: include/linux/blkdev.h:251
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
```
```
In block/blk-exec.c (0)
Location: include/linux/blkdev.h:251
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/blkdev.h:251
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/blkdev.h:251
Inline: True
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/blkdev.h:251
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/blkdev.h:251
Inline: True
```
```
In block/mq-deadline.c (0)
Location: include/linux/blkdev.h:251
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/blkdev.h:251
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/blkdev.h:251
Inline: True
```
```
In drivers/scsi/scsi.c (0)
Location: include/linux/blkdev.h:251
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/blkdev.h:251
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81837c1f)
Location: include/linux/blkdev.h:251
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_prep_fn
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blkdev.h:251
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
In kernel/trace/blktrace.c (ffffffff811ceba7)
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
In block/blk-core.c (ffffffff81560981)
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
In drivers/scsi/scsi_lib.c (ffffffff818485e7)
Location: include/linux/blkdev.h:247
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:scsi_end_request
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
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811d019b)
Location: include/linux/blkdev.h:242
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
```
In block/elevator.c (0)
Location: include/linux/blkdev.h:242
Inline: True
```
```
In block/blk-core.c (ffffffff81569001)
Location: include/linux/blkdev.h:242
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
```
```
In block/blk-exec.c (0)
Location: include/linux/blkdev.h:242
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/blkdev.h:242
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/blkdev.h:242
Inline: True
```
```
In block/blk-mq-sched.c (0)
Location: include/linux/blkdev.h:242
Inline: True
```
```
In block/mq-deadline.c (0)
Location: include/linux/blkdev.h:242
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/blkdev.h:242
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/blkdev.h:242
Inline: True
```
```
In drivers/scsi/scsi.c (0)
Location: include/linux/blkdev.h:242
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/blkdev.h:242
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff8182b915)
Location: include/linux/blkdev.h:242
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blkdev.h:242
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
In kernel/trace/blktrace.c (ffff80001023743c)
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
In block/blk-core.c (ffff8000105e3ef0)
Location: include/linux/blkdev.h:249
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
```
```
In block/blk-exec.c (0)
Location: include/linux/blkdev.h:249
Inline: True
```
```
In block/blk-merge.c (0)
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
In drivers/scsi/scsi_lib.c (ffff800010979054)
Location: include/linux/blkdev.h:249
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:scsi_end_request
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
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (c0472d60)
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
In block/blk-core.c (c07911a0)
Location: include/linux/blkdev.h:249
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
```
```
In block/blk-exec.c (0)
Location: include/linux/blkdev.h:249
Inline: True
```
```
In block/blk-merge.c (0)
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
In drivers/scsi/scsi_lib.c (c0a4cd24)
Location: include/linux/blkdev.h:249
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:scsi_end_request
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
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (c0000000002c30c4)
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
In block/blk-core.c (c000000000777b94)
Location: include/linux/blkdev.h:249
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
```
```
In block/blk-exec.c (0)
Location: include/linux/blkdev.h:249
Inline: True
```
```
In block/blk-merge.c (0)
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
In drivers/scsi/scsi_lib.c (c000000000a334e8)
Location: include/linux/blkdev.h:249
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:scsi_end_request
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
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffe00018e26e)
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
In block/blk-core.c (ffffffe000425866)
Location: include/linux/blkdev.h:249
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
```
```
In block/blk-exec.c (0)
Location: include/linux/blkdev.h:249
Inline: True
```
```
In block/blk-merge.c (0)
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
In drivers/scsi/scsi_lib.c (ffffffe0005e05c2)
Location: include/linux/blkdev.h:249
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blkdev.h:249
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
In kernel/trace/blktrace.c (ffffffff811b12bd)
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
In block/blk-core.c (ffffffff814ded51)
Location: include/linux/blkdev.h:249
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
```
```
In block/blk-exec.c (0)
Location: include/linux/blkdev.h:249
Inline: True
```
```
In block/blk-merge.c (ffffffff814e5134)
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
In drivers/scsi/scsi_lib.c (ffffffff81729391)
Location: include/linux/blkdev.h:249
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:scsi_end_request
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
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811a425d)
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
In block/blk-core.c (ffffffff814cf6f1)
Location: include/linux/blkdev.h:249
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
```
```
In block/blk-exec.c (0)
Location: include/linux/blkdev.h:249
Inline: True
```
```
In block/blk-merge.c (0)
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
In drivers/scsi/scsi_lib.c (ffffffff817027bb)
Location: include/linux/blkdev.h:249
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:scsi_end_request
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
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811af08d)
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
In block/blk-core.c (ffffffff814dade1)
Location: include/linux/blkdev.h:249
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
```
```
In block/blk-exec.c (0)
Location: include/linux/blkdev.h:249
Inline: True
```
```
In block/blk-merge.c (ffffffff814e11c4)
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
In drivers/scsi/scsi_lib.c (ffffffff81768161)
Location: include/linux/blkdev.h:249
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:scsi_end_request
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
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811bcfdf)
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
In block/blk-core.c (ffffffff814f3b71)
Location: include/linux/blkdev.h:249
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
```
```
In block/blk-exec.c (0)
Location: include/linux/blkdev.h:249
Inline: True
```
```
In block/blk-merge.c (ffffffff814fa044)
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
In drivers/scsi/scsi_lib.c (ffffffff817838a1)
Location: include/linux/blkdev.h:249
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/blkdev.h:249
Inline: True
```
</details>
</li>
</ul>

## Differences
