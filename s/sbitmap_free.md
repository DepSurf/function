# Function: <code>sbitmap_free</code>

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
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81422a2d)
Location: include/linux/sbitmap.h:150
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
```
In block/blk-mq-tag.c (ffffffff8142627f)
Location: include/linux/sbitmap.h:150
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In lib/sbitmap.c (ffffffff814826d9)
Location: include/linux/sbitmap.h:150
Inline: True
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
In block/blk-mq.c (ffffffff81432554)
Location: include/linux/sbitmap.h:150
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_exit_hctx
```
```
In block/blk-mq-tag.c (ffffffff81433fcf)
Location: include/linux/sbitmap.h:150
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In lib/sbitmap.c (ffffffff8148be3f)
Location: include/linux/sbitmap.h:150
Inline: True
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
In block/blk-mq.c (ffffffff8145e0d7)
Location: include/linux/sbitmap.h:150
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_exit_hctx
```
```
In block/blk-mq-tag.c (ffffffff8145fcff)
Location: include/linux/sbitmap.h:150
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In lib/sbitmap.c (ffffffff814c7f2b)
Location: include/linux/sbitmap.h:150
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
In block/blk-mq.c (ffffffff814919f3)
Location: include/linux/sbitmap.h:156
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_exit_hctx
```
```
In block/blk-mq-tag.c (ffffffff814935df)
Location: include/linux/sbitmap.h:156
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In lib/sbitmap.c (ffffffff814f8cd1)
Location: include/linux/sbitmap.h:156
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
In block/blk-mq.c (ffffffff814ab445)
Location: include/linux/sbitmap.h:173
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
```
In block/blk-mq-tag.c (ffffffff814ad60f)
Location: include/linux/sbitmap.h:173
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In lib/sbitmap.c (ffffffff8150d12f)
Location: include/linux/sbitmap.h:173
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
In block/blk-mq.c (ffffffff814d967d)
Location: include/linux/sbitmap.h:162
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
```
In block/blk-mq-tag.c (ffffffff814db891)
Location: include/linux/sbitmap.h:162
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In block/blk-mq-sysfs.c (ffffffff814dc377)
Location: include/linux/sbitmap.h:162
Inline: True
Inline callers:
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release
```
```
In lib/sbitmap.c (ffffffff8153b825)
Location: include/linux/sbitmap.h:162
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
In block/blk-mq.c (ffffffff814f2a3d)
Location: include/linux/sbitmap.h:162
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
```
In block/blk-mq-tag.c (ffffffff814f4cc1)
Location: include/linux/sbitmap.h:162
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In block/blk-mq-sysfs.c (ffffffff814f57e7)
Location: include/linux/sbitmap.h:162
Inline: True
Inline callers:
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release
```
```
In lib/sbitmap.c (ffffffff8155c635)
Location: include/linux/sbitmap.h:162
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
In block/blk-mq.c (ffffffff81551825)
Location: include/linux/sbitmap.h:162
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
```
```
In block/blk-mq-tag.c (ffffffff81555691)
Location: include/linux/sbitmap.h:162
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In block/blk-mq-sysfs.c (ffffffff815561b7)
Location: include/linux/sbitmap.h:162
Inline: True
Inline callers:
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release
```
```
In lib/sbitmap.c (ffffffff815e5ef2)
Location: include/linux/sbitmap.h:162
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
In block/blk-mq.c (ffffffff8156d971)
Location: include/linux/sbitmap.h:157
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
```
```
In block/blk-mq-tag.c (ffffffff81571ee7)
Location: include/linux/sbitmap.h:157
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:blk_mq_exit_shared_sbitmap
  - block/blk-mq-tag.c:blk_mq_exit_shared_sbitmap
  - block/blk-mq-tag.c:blk_mq_init_shared_sbitmap
```
```
In block/blk-mq-sysfs.c (ffffffff815729fb)
Location: include/linux/sbitmap.h:157
Inline: True
Inline callers:
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release
```
```
In lib/sbitmap.c (ffffffff8160a2a2)
Location: include/linux/sbitmap.h:157
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
In block/blk-mq.c (ffffffff8157495f)
Location: include/linux/sbitmap.h:162
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
```
```
In block/blk-mq-tag.c (ffffffff81579efe)
Location: include/linux/sbitmap.h:162
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:blk_mq_exit_shared_sbitmap
  - block/blk-mq-tag.c:blk_mq_exit_shared_sbitmap
  - block/blk-mq-tag.c:blk_mq_init_shared_sbitmap
```
```
In block/blk-mq-sysfs.c (ffffffff8157aa1b)
Location: include/linux/sbitmap.h:162
Inline: True
Inline callers:
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release
```
```
In lib/sbitmap.c (ffffffff815ed545)
Location: include/linux/sbitmap.h:162
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_init_node
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8182fc3e)
Location: include/linux/sbitmap.h:162
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
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
In block/blk-mq.c (ffffffff815d8e7f)
Location: include/linux/sbitmap.h:162
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
```
```
In block/blk-mq-tag.c (ffffffff815df21e)
Location: include/linux/sbitmap.h:162
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_exit_shared_sbitmap
  - block/blk-mq-tag.c:blk_mq_exit_shared_sbitmap
  - block/blk-mq-tag.c:blk_mq_init_bitmaps
```
```
In block/blk-mq-sysfs.c (ffffffff815dfcfb)
Location: include/linux/sbitmap.h:162
Inline: True
Inline callers:
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release
```
```
In block/blk-mq-sched.c (ffffffff815e118d)
Location: include/linux/sbitmap.h:162
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_exit_sched
  - block/blk-mq-sched.c:blk_mq_exit_sched
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_init_sched
```
```
In lib/sbitmap.c (ffffffff8165a38d)
Location: include/linux/sbitmap.h:162
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_init_node
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff818bbb61)
Location: include/linux/sbitmap.h:162
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
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
In block/blk-mq.c (ffffffff816868e0)
Location: include/linux/sbitmap.h:174
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
```
```
In block/blk-mq-tag.c (ffffffff8168d876)
Location: include/linux/sbitmap.h:174
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_bitmaps
```
```
In block/blk-mq-sysfs.c (ffffffff8168e549)
Location: include/linux/sbitmap.h:174
Inline: True
Inline callers:
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release
```
```
In lib/sbitmap.c (ffffffff81772b93)
Location: include/linux/sbitmap.h:174
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_init_node
```
```
In drivers/scsi/scsi_scan.c (ffffffff81a03e88)
Location: include/linux/sbitmap.h:174
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81a07871)
Location: include/linux/sbitmap.h:174
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
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
In block/blk-mq.c (ffffffff817451a0)
Location: include/linux/sbitmap.h:180
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
```
```
In block/blk-mq-tag.c (ffffffff8174c0a6)
Location: include/linux/sbitmap.h:180
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_bitmaps
```
```
In block/blk-mq-sysfs.c (ffffffff8174cf19)
Location: include/linux/sbitmap.h:180
Inline: True
Inline callers:
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release
```
```
In lib/sbitmap.c (ffffffff818a3d3e)
Location: include/linux/sbitmap.h:180
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_init_node
```
```
In drivers/scsi/scsi_scan.c (ffffffff81b82a68)
Location: include/linux/sbitmap.h:180
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81b8699a)
Location: include/linux/sbitmap.h:180
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release
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
In block/blk-mq.c (ffffffff81781110)
Location: include/linux/sbitmap.h:180
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
```
```
In block/blk-mq-tag.c (ffffffff817887c6)
Location: include/linux/sbitmap.h:180
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_bitmaps
```
```
In block/blk-mq-sysfs.c (ffffffff81789539)
Location: include/linux/sbitmap.h:180
Inline: True
Inline callers:
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release
```
```
In lib/sbitmap.c (ffffffff818e621e)
Location: include/linux/sbitmap.h:180
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_init_node
```
```
In drivers/scsi/scsi_scan.c (ffffffff81bd6761)
Location: include/linux/sbitmap.h:180
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81bda76a)
Location: include/linux/sbitmap.h:180
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release
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
In block/blk-mq.c (ffffffff817c3972)
Location: include/linux/sbitmap.h:180
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
```
```
In block/blk-mq-tag.c (ffffffff817caec6)
Location: include/linux/sbitmap.h:180
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_bitmaps
```
```
In block/blk-mq-sysfs.c (ffffffff817cbcd9)
Location: include/linux/sbitmap.h:180
Inline: True
Inline callers:
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release
```
```
In lib/sbitmap.c (ffffffff8192d23e)
Location: include/linux/sbitmap.h:180
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_init_node
```
```
In drivers/scsi/scsi_scan.c (ffffffff81c2b3b1)
Location: include/linux/sbitmap.h:180
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81c2f49a)
Location: include/linux/sbitmap.h:180
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release
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
In block/blk-mq.c (ffff8000105f2274)
Location: include/linux/sbitmap.h:162
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
```
In block/blk-mq-tag.c (ffff8000105f4b34)
Location: include/linux/sbitmap.h:162
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In block/blk-mq-sysfs.c (ffff8000105f5a64)
Location: include/linux/sbitmap.h:162
Inline: True
Inline callers:
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release
```
```
In lib/sbitmap.c (ffff8000106695d4)
Location: include/linux/sbitmap.h:162
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
In block/blk-mq.c (c079e378)
Location: include/linux/sbitmap.h:162
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
```
In block/blk-mq-tag.c (c07a0780)
Location: include/linux/sbitmap.h:162
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In block/blk-mq-sysfs.c (c07a1404)
Location: include/linux/sbitmap.h:162
Inline: True
Inline callers:
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release
```
```
In lib/sbitmap.c (c08122a8)
Location: include/linux/sbitmap.h:162
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
In block/blk-mq.c (c0000000007893fc)
Location: include/linux/sbitmap.h:162
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
```
In block/blk-mq-tag.c (c00000000078c574)
Location: include/linux/sbitmap.h:162
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In block/blk-mq-sysfs.c (c00000000078d820)
Location: include/linux/sbitmap.h:162
Inline: True
Inline callers:
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release
```
```
In lib/sbitmap.c (c00000000081fae0)
Location: include/linux/sbitmap.h:162
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
In block/blk-mq.c (ffffffe000430b8a)
Location: include/linux/sbitmap.h:162
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
```
In block/blk-mq-tag.c (ffffffe000432a0a)
Location: include/linux/sbitmap.h:162
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In block/blk-mq-sysfs.c (ffffffe000433658)
Location: include/linux/sbitmap.h:162
Inline: True
Inline callers:
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release
```
```
In lib/sbitmap.c (ffffffe000494982)
Location: include/linux/sbitmap.h:162
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
In block/blk-mq.c (ffffffff814eb01d)
Location: include/linux/sbitmap.h:162
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
```
In block/blk-mq-tag.c (ffffffff814ed2a1)
Location: include/linux/sbitmap.h:162
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In block/blk-mq-sysfs.c (ffffffff814eddc7)
Location: include/linux/sbitmap.h:162
Inline: True
Inline callers:
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release
```
```
In lib/sbitmap.c (ffffffff81554c25)
Location: include/linux/sbitmap.h:162
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
In block/blk-mq.c (ffffffff814db56d)
Location: include/linux/sbitmap.h:162
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
```
In block/blk-mq-tag.c (ffffffff814dd7f1)
Location: include/linux/sbitmap.h:162
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In block/blk-mq-sysfs.c (ffffffff814de317)
Location: include/linux/sbitmap.h:162
Inline: True
Inline callers:
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release
```
```
In lib/sbitmap.c (ffffffff81544ea5)
Location: include/linux/sbitmap.h:162
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
In block/blk-mq.c (ffffffff814e70ad)
Location: include/linux/sbitmap.h:162
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
```
In block/blk-mq-tag.c (ffffffff814e9331)
Location: include/linux/sbitmap.h:162
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In block/blk-mq-sysfs.c (ffffffff814e9e57)
Location: include/linux/sbitmap.h:162
Inline: True
Inline callers:
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release
```
```
In lib/sbitmap.c (ffffffff81550965)
Location: include/linux/sbitmap.h:162
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
In block/blk-mq.c (ffffffff8150004f)
Location: include/linux/sbitmap.h:162
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
```
In block/blk-mq-tag.c (ffffffff815022f1)
Location: include/linux/sbitmap.h:162
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In block/blk-mq-sysfs.c (ffffffff81502e27)
Location: include/linux/sbitmap.h:162
Inline: True
Inline callers:
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release
```
```
In lib/sbitmap.c (ffffffff8156a7a5)
Location: include/linux/sbitmap.h:162
Inline: True
```
</details>
</li>
</ul>

## Differences
