# Function: <code>queue_flag_set</code>

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
In block/blk-core.c (ffffffff813b55f9)
Location: include/linux/blkdev.h:540
Inline: True
Inline callers:
  - block/blk-core.c:blk_stop_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
```
```
In block/blk-tag.c (ffffffff813bc2eb)
Location: include/linux/blkdev.h:540
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_init_tags
```
```
In block/blk-sysfs.c (ffffffff813bccee)
Location: include/linux/blkdev.h:540
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_store_nonrot
  - block/blk-sysfs.c:queue_store_random
  - block/blk-sysfs.c:queue_store_iostats
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
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
In block/blk-core.c (ffffffff813fc9fe)
Location: include/linux/blkdev.h:557
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_stop_queue
```
```
In block/blk-tag.c (ffffffff814000eb)
Location: include/linux/blkdev.h:557
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_init_tags
```
```
In block/blk-sysfs.c (ffffffff81400b2a)
Location: include/linux/blkdev.h:557
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wc_store
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_store_iostats
  - block/blk-sysfs.c:queue_store_random
  - block/blk-sysfs.c:queue_store_nonrot
```
```
In block/blk-settings.c (ffffffff81402b36)
Location: include/linux/blkdev.h:557
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-settings.c:blk_queue_write_cache
```
```
In drivers/md/dm-rq.c (ffffffff8170fc35)
Location: include/linux/blkdev.h:557
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_stop_queue
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
In block/blk-core.c (ffffffff8141639e)
Location: include/linux/blkdev.h:652
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_stop_queue
```
```
In block/blk-tag.c (ffffffff8141998b)
Location: include/linux/blkdev.h:652
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_init_tags
```
```
In block/blk-sysfs.c (ffffffff8141a75a)
Location: include/linux/blkdev.h:652
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wc_store
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_store_iostats
  - block/blk-sysfs.c:queue_store_random
  - block/blk-sysfs.c:queue_store_nonrot
```
```
In block/blk-settings.c (ffffffff8141c6e6)
Location: include/linux/blkdev.h:652
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-settings.c:blk_queue_write_cache
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
In block/blk-core.c (ffffffff81423a7e)
Location: include/linux/blkdev.h:691
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_stop_queue
```
```
In block/blk-tag.c (ffffffff814278bd)
Location: include/linux/blkdev.h:691
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_init_tags
```
```
In block/blk-sysfs.c (ffffffff81428801)
Location: include/linux/blkdev.h:691
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wc_store
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_store_iostats
  - block/blk-sysfs.c:queue_store_random
  - block/blk-sysfs.c:queue_store_nonrot
```
```
In block/blk-settings.c (ffffffff8142a648)
Location: include/linux/blkdev.h:691
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-settings.c:blk_queue_write_cache
```
```
In block/blk-mq.c (ffffffff8142ec49)
Location: include/linux/blkdev.h:691
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_quiesce_queue_nowait
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
In block/blk-core.c (ffffffff8144f21e)
Location: include/linux/blkdev.h:708
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_set_queue_dying
  - block/blk-core.c:blk_stop_queue
```
```
In block/blk-tag.c (ffffffff814528bd)
Location: include/linux/blkdev.h:708
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_init_tags
```
```
In block/blk-sysfs.c (ffffffff814538d1)
Location: include/linux/blkdev.h:708
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_wc_store
  - block/blk-sysfs.c:queue_poll_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_store_iostats
  - block/blk-sysfs.c:queue_store_random
  - block/blk-sysfs.c:queue_store_nonrot
```
```
In block/blk-settings.c (ffffffff81455998)
Location: include/linux/blkdev.h:708
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-settings.c:blk_queue_write_cache
```
```
In block/blk-mq.c (ffffffff8145a0d9)
Location: include/linux/blkdev.h:708
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_quiesce_queue_nowait
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
In block/blk-core.c (ffffffff81482cbe)
Location: block/blk.h:101
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-core.c:blk_stop_queue
  - block/blk-core.c:blk_queue_flag_set
```
```
In block/blk-tag.c (ffffffff81485c8d)
Location: block/blk.h:101
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_init_tags
```
```
In block/blk-sysfs.c (ffffffff814868cc)
Location: block/blk.h:101
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_nomerges_store
```
```
In block/blk-settings.c (ffffffff81488c28)
Location: block/blk.h:101
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-settings.c:blk_queue_write_cache
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
