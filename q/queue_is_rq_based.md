# Function: <code>queue_is_rq_based</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff813d54fb)
Location: include/linux/blkdev.h:602
Inline: True
Inline callers:
  - block/bsg.c:bsg_register_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff8141b1bb)
Location: include/linux/blkdev.h:620
Inline: True
Inline callers:
  - block/bsg.c:bsg_register_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff814366fb)
Location: include/linux/blkdev.h:715
Inline: True
Inline callers:
  - block/bsg.c:bsg_register_queue
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
In block/blk-core.c (ffffffff81424573)
Location: include/linux/blkdev.h:758
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
```
In block/bsg.c (ffffffff81443f57)
Location: include/linux/blkdev.h:758
Inline: True
Inline callers:
  - block/bsg.c:bsg_register_queue
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
In block/elevator.c (ffffffff8144a446)
Location: include/linux/blkdev.h:778
Inline: True
Inline callers:
  - block/elevator.c:elv_iosched_show
```
```
In block/blk-core.c (ffffffff8144d72c)
Location: include/linux/blkdev.h:778
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
```
In block/bsg.c (ffffffff81470cda)
Location: include/linux/blkdev.h:778
Inline: True
Inline callers:
  - block/bsg.c:bsg_register_queue
```
```
In drivers/md/dm-table.c (ffffffff817c3aca)
Location: include/linux/blkdev.h:778
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
```
```
In drivers/md/dm-rq.c (ffffffff817cd832)
Location: include/linux/blkdev.h:778
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_request_based
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
In block/elevator.c (ffffffff8147d521)
Location: include/linux/blkdev.h:771
Inline: True
Inline callers:
  - block/elevator.c:elv_iosched_show
```
```
In block/blk-core.c (ffffffff814825b2)
Location: include/linux/blkdev.h:771
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
```
In block/bsg.c (ffffffff814a5388)
Location: include/linux/blkdev.h:771
Inline: True
```
```
In block/blk-throttle.c (ffffffff814ad303)
Location: include/linux/blkdev.h:771
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_register_queue
```
```
In drivers/md/dm-table.c (ffffffff8180ab19)
Location: include/linux/blkdev.h:771
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_is_rq_based
```
```
In drivers/md/dm-rq.c (ffffffff8181661d)
Location: include/linux/blkdev.h:771
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_request_based
```
</details>
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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
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
