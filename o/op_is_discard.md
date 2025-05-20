# Function: <code>op_is_discard</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81499cf8)
Location: include/linux/blk_types.h:406
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
```
```
In block/blk-core.c (0)
Location: include/linux/blk_types.h:406
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/blk_types.h:406
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/blk_types.h:406
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
In block/bio.c (ffffffff814c7da0)
Location: include/linux/blk_types.h:407
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
```
```
In block/blk-core.c (0)
Location: include/linux/blk_types.h:407
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/blk_types.h:407
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/blk_types.h:407
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
In block/bio.c (ffffffff814e0ea0)
Location: include/linux/blk_types.h:415
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
```
```
In block/blk-core.c (0)
Location: include/linux/blk_types.h:415
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/blk_types.h:415
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/blk_types.h:415
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
In block/blk-core.c (ffffffff81542c54)
Location: include/linux/blk_types.h:440
Inline: True
Inline callers:
  - block/blk-core.c:disk_end_io_acct
  - block/blk-core.c:disk_start_io_acct
  - block/blk-core.c:blkcg_bio_issue_check
```
```
In block/blk-merge.c (0)
Location: include/linux/blk_types.h:440
Inline: True
```
```
In block/blk-throttle.c (ffffffff8156ff2d)
Location: include/linux/blk_types.h:440
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
```
```
In drivers/md/dm.c (0)
Location: include/linux/blk_types.h:440
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
In block/blk-core.c (ffffffff8155f547)
Location: include/linux/blk_types.h:504
Inline: True
Inline callers:
  - block/blk-core.c:__part_end_io_acct
  - block/blk-core.c:__part_start_io_acct
```
```
In block/blk-merge.c (0)
Location: include/linux/blk_types.h:504
Inline: True
```
```
In block/blk-cgroup.c (ffffffff81586e58)
Location: include/linux/blk_types.h:504
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_bio_start
```
```
In block/blk-throttle.c (ffffffff8158ad1a)
Location: include/linux/blk_types.h:504
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
```
```
In drivers/md/dm.c (0)
Location: include/linux/blk_types.h:504
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
In block/blk-core.c (ffffffff81567cc5)
Location: include/linux/blk_types.h:478
Inline: True
Inline callers:
  - block/blk-core.c:__part_end_io_acct
  - block/blk-core.c:__part_start_io_acct
```
```
In block/blk-merge.c (0)
Location: include/linux/blk_types.h:478
Inline: True
```
```
In block/blk-cgroup.c (ffffffff8158dc98)
Location: include/linux/blk_types.h:478
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_bio_start
```
```
In block/blk-throttle.c (ffffffff81591805)
Location: include/linux/blk_types.h:478
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
```
```
In drivers/md/dm.c (0)
Location: include/linux/blk_types.h:478
Inline: True
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
In block/blk-core.c (ffffffff815cc2f5)
Location: include/linux/blk_types.h:469
Inline: True
Inline callers:
  - block/blk-core.c:__part_end_io_acct
  - block/blk-core.c:__part_start_io_acct
```
```
In block/blk-merge.c (0)
Location: include/linux/blk_types.h:469
Inline: True
```
```
In block/blk-cgroup.c (ffffffff815f371c)
Location: include/linux/blk_types.h:469
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_bio_start
```
```
In block/blk-throttle.c (ffffffff815f8a48)
Location: include/linux/blk_types.h:469
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
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
In block/blk-core.c (ffffffff81679bc5)
Location: include/linux/blk_types.h:501
Inline: True
Inline callers:
  - block/blk-core.c:bdev_end_io_acct
  - block/blk-core.c:bdev_start_io_acct
```
```
In block/blk-merge.c (0)
Location: include/linux/blk_types.h:501
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/blk_types.h:501
Inline: True
```
```
In block/blk-cgroup.c (ffffffff816a4d4c)
Location: include/linux/blk_types.h:501
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_bio_start
```
```
In block/blk-throttle.c (ffffffff816aabc2)
Location: include/linux/blk_types.h:501
Inline: True
Inline callers:
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:__blk_throtl_bio
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
In block/blk-core.c (ffffffff81736025)
Location: include/linux/blk_types.h:500
Inline: True
Inline callers:
  - block/blk-core.c:bdev_end_io_acct
  - block/blk-core.c:bdev_start_io_acct
```
```
In block/blk-merge.c (0)
Location: include/linux/blk_types.h:500
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/blk_types.h:500
Inline: True
```
```
In block/blk-cgroup.c (ffffffff81763b11)
Location: include/linux/blk_types.h:500
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_bio_start
```
```
In block/blk-throttle.c (ffffffff817695c3)
Location: include/linux/blk_types.h:500
Inline: True
Inline callers:
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:__blk_throtl_bio
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
In block/blk-core.c (ffffffff81772545)
Location: include/linux/blk_types.h:505
Inline: True
Inline callers:
  - block/blk-core.c:bdev_end_io_acct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
```
```
In block/blk-merge.c (0)
Location: include/linux/blk_types.h:505
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/blk_types.h:505
Inline: True
```
```
In block/blk-cgroup.c (ffffffff817a2bb1)
Location: include/linux/blk_types.h:505
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_bio_start
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
In block/blk-core.c (ffffffff817b48e5)
Location: include/linux/blk_types.h:504
Inline: True
Inline callers:
  - block/blk-core.c:bdev_end_io_acct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
```
```
In block/blk-merge.c (0)
Location: include/linux/blk_types.h:504
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/blk_types.h:504
Inline: True
```
```
In block/blk-cgroup.c (ffffffff817e66f1)
Location: include/linux/blk_types.h:504
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_bio_start
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
In block/bio.c (ffff8000105ddac0)
Location: include/linux/blk_types.h:415
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
```
```
In block/blk-core.c (0)
Location: include/linux/blk_types.h:415
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/blk_types.h:415
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/blk_types.h:415
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
In block/bio.c (c078ae34)
Location: include/linux/blk_types.h:415
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
```
```
In block/blk-core.c (0)
Location: include/linux/blk_types.h:415
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/blk_types.h:415
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/blk_types.h:415
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
In block/bio.c (c00000000076f3c8)
Location: include/linux/blk_types.h:415
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
```
```
In block/blk-core.c (0)
Location: include/linux/blk_types.h:415
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/blk_types.h:415
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/blk_types.h:415
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
In block/bio.c (ffffffe000420a6c)
Location: include/linux/blk_types.h:415
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
```
```
In block/blk-core.c (0)
Location: include/linux/blk_types.h:415
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/blk_types.h:415
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/blk_types.h:415
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
In block/bio.c (ffffffff814d9480)
Location: include/linux/blk_types.h:415
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
```
```
In block/blk-core.c (0)
Location: include/linux/blk_types.h:415
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/blk_types.h:415
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/blk_types.h:415
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
In block/bio.c (ffffffff814c9e30)
Location: include/linux/blk_types.h:415
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
```
```
In block/blk-core.c (0)
Location: include/linux/blk_types.h:415
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/blk_types.h:415
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/blk_types.h:415
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
In block/bio.c (ffffffff814d5510)
Location: include/linux/blk_types.h:415
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
```
```
In block/blk-core.c (0)
Location: include/linux/blk_types.h:415
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/blk_types.h:415
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/blk_types.h:415
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
In block/bio.c (ffffffff814ee0fb)
Location: include/linux/blk_types.h:415
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
```
```
In block/blk-core.c (0)
Location: include/linux/blk_types.h:415
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/blk_types.h:415
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/blk_types.h:415
Inline: True
```
</details>
</li>
</ul>

## Differences
