# Function: <code>writeback_in_progress</code>

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
In mm/page-writeback.c (ffffffff811999f3)
Location: include/linux/backing-dev.h:170
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81239a41)
Location: include/linux/backing-dev.h:170
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
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
In mm/page-writeback.c (ffffffff811ae35e)
Location: include/linux/backing-dev.h:171
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81261a05)
Location: include/linux/backing-dev.h:171
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
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
In mm/page-writeback.c (ffffffff811bea18)
Location: include/linux/backing-dev.h:171
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81274f05)
Location: include/linux/backing-dev.h:171
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
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
In mm/page-writeback.c (ffffffff811c68fd)
Location: include/linux/backing-dev.h:146
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812823e4)
Location: include/linux/backing-dev.h:146
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
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
In mm/page-writeback.c (ffffffff811db70f)
Location: include/linux/backing-dev.h:148
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
```
```
In fs/fs-writeback.c (ffffffff812a4f54)
Location: include/linux/backing-dev.h:148
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
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
In mm/page-writeback.c (ffffffff811fcde3)
Location: include/linux/backing-dev.h:149
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
```
```
In fs/fs-writeback.c (ffffffff812cbe13)
Location: include/linux/backing-dev.h:149
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
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
In mm/page-writeback.c (ffffffff8120f900)
Location: include/linux/backing-dev.h:149
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
```
```
In fs/fs-writeback.c (ffffffff812e0d3c)
Location: include/linux/backing-dev.h:149
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
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
In mm/page-writeback.c (ffffffff8121f1c7)
Location: include/linux/backing-dev.h:150
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
```
```
In fs/fs-writeback.c (ffffffff812ff455)
Location: include/linux/backing-dev.h:150
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
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
In mm/page-writeback.c (ffffffff8122cc67)
Location: include/linux/backing-dev.h:154
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
```
```
In fs/fs-writeback.c (ffffffff81314375)
Location: include/linux/backing-dev.h:154
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
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
In mm/page-writeback.c (ffffffff8125a702)
Location: include/linux/backing-dev.h:150
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
```
```
In fs/fs-writeback.c (ffffffff8134de9f)
Location: include/linux/backing-dev.h:150
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
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
In mm/page-writeback.c (ffffffff81264882)
Location: include/linux/backing-dev.h:131
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
```
```
In fs/fs-writeback.c (ffffffff8135ad24)
Location: include/linux/backing-dev.h:131
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
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
In mm/page-writeback.c (ffffffff81268a93)
Location: include/linux/backing-dev.h:131
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
```
```
In fs/fs-writeback.c (ffffffff81361924)
Location: include/linux/backing-dev.h:131
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
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
In mm/page-writeback.c (ffffffff812a5527)
Location: include/linux/backing-dev.h:131
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
```
```
In fs/fs-writeback.c (ffffffff813aff84)
Location: include/linux/backing-dev.h:131
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
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
In mm/page-writeback.c (ffffffff812fe094)
Location: include/linux/backing-dev.h:131
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
```
```
In fs/fs-writeback.c (ffffffff81434b7d)
Location: include/linux/backing-dev.h:131
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
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
In mm/page-writeback.c (ffffffff81368a3e)
Location: include/linux/backing-dev.h:141
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
```
```
In fs/fs-writeback.c (ffffffff814c2b7d)
Location: include/linux/backing-dev.h:141
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
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
In mm/page-writeback.c (ffffffff8139abde)
Location: include/linux/backing-dev.h:141
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
```
```
In fs/fs-writeback.c (ffffffff814f7f3d)
Location: include/linux/backing-dev.h:141
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
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
In mm/page-writeback.c (ffffffff813c4b19)
Location: include/linux/backing-dev.h:140
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
```
```
In fs/fs-writeback.c (ffffffff8152c68d)
Location: include/linux/backing-dev.h:140
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
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
In mm/page-writeback.c (ffff8000102bb514)
Location: include/linux/backing-dev.h:154
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
```
```
In fs/fs-writeback.c (ffff8000103ca158)
Location: include/linux/backing-dev.h:154
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
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
In mm/page-writeback.c (c04e8110)
Location: include/linux/backing-dev.h:154
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
```
```
In fs/fs-writeback.c (c05a6780)
Location: include/linux/backing-dev.h:154
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
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
In mm/page-writeback.c (c000000000373d84)
Location: include/linux/backing-dev.h:154
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
```
```
In fs/fs-writeback.c (c0000000004cba0c)
Location: include/linux/backing-dev.h:154
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
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
In mm/page-writeback.c (ffffffe0001de766)
Location: include/linux/backing-dev.h:154
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
```
```
In fs/fs-writeback.c (ffffffe000288430)
Location: include/linux/backing-dev.h:154
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
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
In mm/page-writeback.c (ffffffff812252b7)
Location: include/linux/backing-dev.h:154
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
```
```
In fs/fs-writeback.c (ffffffff8130c955)
Location: include/linux/backing-dev.h:154
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
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
In mm/page-writeback.c (ffffffff81218457)
Location: include/linux/backing-dev.h:154
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
```
```
In fs/fs-writeback.c (ffffffff812fd575)
Location: include/linux/backing-dev.h:154
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
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
In mm/page-writeback.c (ffffffff81223057)
Location: include/linux/backing-dev.h:154
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
```
```
In fs/fs-writeback.c (ffffffff8130a745)
Location: include/linux/backing-dev.h:154
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
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
In mm/page-writeback.c (ffffffff8123223a)
Location: include/linux/backing-dev.h:154
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
```
```
In fs/fs-writeback.c (ffffffff8131be13)
Location: include/linux/backing-dev.h:154
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
```
</details>
</li>
</ul>

## Differences
