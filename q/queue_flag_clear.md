# Function: <code>queue_flag_clear</code>

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
In block/blk-core.c (ffffffff813b55b9)
Location: include/linux/blkdev.h:557
Inline: True
Inline callers:
  - block/blk-core.c:blk_start_queue
  - block/blk-core.c:blk_start_queue_async
  - block/blk-core.c:blk_queue_bypass_end
```
```
In block/blk-sysfs.c (ffffffff813bccb1)
Location: include/linux/blkdev.h:557
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
```
In drivers/block/xen-blkfront.c (ffffffff8157480d)
Location: include/linux/blkdev.h:557
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
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
In block/blk-core.c (ffffffff813fc7dc)
Location: include/linux/blkdev.h:574
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_bypass_end
  - block/blk-core.c:blk_start_queue
  - block/blk-core.c:blk_start_queue_async
```
```
In block/blk-sysfs.c (ffffffff81400b14)
Location: include/linux/blkdev.h:574
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
In block/blk-settings.c (ffffffff81402b4c)
Location: include/linux/blkdev.h:574
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-settings.c:blk_queue_write_cache
```
```
In drivers/block/xen-blkfront.c (ffffffff815cb895)
Location: include/linux/blkdev.h:574
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
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
In block/blk-core.c (ffffffff8141617c)
Location: include/linux/blkdev.h:669
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_bypass_end
  - block/blk-core.c:blk_start_queue
  - block/blk-core.c:blk_start_queue_async
```
```
In block/blk-sysfs.c (ffffffff8141a744)
Location: include/linux/blkdev.h:669
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
In block/blk-settings.c (ffffffff8141c6fc)
Location: include/linux/blkdev.h:669
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-settings.c:blk_queue_write_cache
```
```
In drivers/block/xen-blkfront.c (ffffffff815f84b0)
Location: include/linux/blkdev.h:669
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
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
In block/blk-core.c (ffffffff8142375c)
Location: include/linux/blkdev.h:708
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_bypass_end
  - block/blk-core.c:blk_start_queue
  - block/blk-core.c:blk_start_queue_async
```
```
In block/blk-sysfs.c (ffffffff814287b4)
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
In block/blk-settings.c (ffffffff8142a655)
Location: include/linux/blkdev.h:708
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-settings.c:blk_queue_write_cache
```
```
In block/blk-mq.c (ffffffff81430d19)
Location: include/linux/blkdev.h:708
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_unquiesce_queue
```
```
In drivers/block/xen-blkfront.c (ffffffff8160c375)
Location: include/linux/blkdev.h:708
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
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
In block/blk-core.c (ffffffff8144ec0c)
Location: include/linux/blkdev.h:725
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_bypass_end
  - block/blk-core.c:blk_clear_preempt_only
  - block/blk-core.c:blk_start_queue
  - block/blk-core.c:blk_start_queue_async
```
```
In block/blk-sysfs.c (ffffffff81453884)
Location: include/linux/blkdev.h:725
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
In block/blk-settings.c (ffffffff814559a5)
Location: include/linux/blkdev.h:725
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-settings.c:blk_queue_write_cache
```
```
In block/blk-mq.c (ffffffff8145b3f9)
Location: include/linux/blkdev.h:725
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_unquiesce_queue
```
```
In drivers/block/xen-blkfront.c (ffffffff81674e11)
Location: include/linux/blkdev.h:725
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
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
In block/blk-core.c (ffffffff8148171a)
Location: block/blk.h:107
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_bypass_end
  - block/blk-core.c:blk_start_queue
  - block/blk-core.c:blk_start_queue_async
  - block/blk-core.c:blk_queue_flag_clear
```
```
In block/blk-sysfs.c (ffffffff81486885)
Location: block/blk.h:107
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_rq_affinity_store
  - block/blk-sysfs.c:queue_nomerges_store
  - block/blk-sysfs.c:queue_nomerges_store
```
```
In block/blk-settings.c (ffffffff81488c72)
Location: block/blk.h:107
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
