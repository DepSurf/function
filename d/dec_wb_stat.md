# Function: <code>dec_wb_stat</code>

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
In mm/page-writeback.c (ffffffff81198d81)
Location: include/linux/backing-dev.h:84
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
```
```
In fs/fuse/file.c (ffffffff81317015)
Location: include/linux/backing-dev.h:84
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
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
In mm/page-writeback.c (ffffffff811af648)
Location: include/linux/backing-dev.h:85
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
```
```
In fs/fuse/file.c (ffffffff8134f140)
Location: include/linux/backing-dev.h:85
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
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
In mm/page-writeback.c (ffffffff811bfd08)
Location: include/linux/backing-dev.h:85
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
```
```
In fs/fuse/file.c (ffffffff81364a56)
Location: include/linux/backing-dev.h:85
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
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
In mm/page-writeback.c (ffffffff811c94cd)
Location: include/linux/backing-dev.h:77
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
```
```
In fs/fs-writeback.c (ffffffff81282d8b)
Location: include/linux/backing-dev.h:77
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/fuse/file.c (ffffffff813791d3)
Location: include/linux/backing-dev.h:77
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
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
In mm/page-writeback.c (ffffffff811de2f3)
Location: include/linux/backing-dev.h:76
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
```
```
In fs/fs-writeback.c (ffffffff812a58db)
Location: include/linux/backing-dev.h:76
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/fuse/file.c (ffffffff8139e073)
Location: include/linux/backing-dev.h:76
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
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
In mm/page-writeback.c (ffffffff811ff99b)
Location: include/linux/backing-dev.h:77
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
```
```
In fs/fs-writeback.c (ffffffff812cc657)
Location: include/linux/backing-dev.h:77
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/fuse/file.c (ffffffff813cd43e)
Location: include/linux/backing-dev.h:77
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
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
In mm/page-writeback.c (ffffffff81212268)
Location: include/linux/backing-dev.h:77
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
```
```
In fs/fs-writeback.c (ffffffff812e1887)
Location: include/linux/backing-dev.h:77
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/fuse/file.c (ffffffff813e67ba)
Location: include/linux/backing-dev.h:77
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
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
In mm/page-writeback.c (ffffffff81221b6c)
Location: include/linux/backing-dev.h:78
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
```
```
In fs/fs-writeback.c (ffffffff812fffc1)
Location: include/linux/backing-dev.h:78
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/fuse/file.c (ffffffff81412461)
Location: include/linux/backing-dev.h:78
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
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
In mm/page-writeback.c (ffffffff8122f61c)
Location: include/linux/backing-dev.h:82
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
```
```
In fs/fs-writeback.c (ffffffff813128ff)
Location: include/linux/backing-dev.h:82
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/fuse/file.c (ffffffff8142c1a9)
Location: include/linux/backing-dev.h:82
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
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
In mm/page-writeback.c (ffffffff8125c6af)
Location: include/linux/backing-dev.h:78
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
```
```
In fs/fs-writeback.c (ffffffff8134be56)
Location: include/linux/backing-dev.h:78
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/fuse/file.c (ffffffff814774f5)
Location: include/linux/backing-dev.h:78
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepage_add
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
In mm/page-writeback.c (ffffffff81266a5d)
Location: include/linux/backing-dev.h:78
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
```
```
In fs/fs-writeback.c (ffffffff81359028)
Location: include/linux/backing-dev.h:78
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/fuse/file.c (ffffffff81493711)
Location: include/linux/backing-dev.h:78
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepage_add
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
In mm/page-writeback.c (ffffffff8126b4f1)
Location: include/linux/backing-dev.h:78
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
```
```
In fs/fs-writeback.c (ffffffff8135fb80)
Location: include/linux/backing-dev.h:78
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/fuse/file.c (ffffffff8149869e)
Location: include/linux/backing-dev.h:78
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepage_add
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
In mm/page-writeback.c (ffffffff812a81ad)
Location: include/linux/backing-dev.h:78
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
```
```
In fs/fs-writeback.c (ffffffff813ae48e)
Location: include/linux/backing-dev.h:78
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/fuse/file.c (ffffffff814f3954)
Location: include/linux/backing-dev.h:78
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81583399)
Location: include/linux/backing-dev.h:76
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81629329)
Location: include/linux/backing-dev.h:76
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8166153e)
Location: include/linux/backing-dev.h:76
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8169b3fe)
Location: include/linux/backing-dev.h:75
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
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
In mm/page-writeback.c (ffff8000102beac0)
Location: include/linux/backing-dev.h:82
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
```
```
In fs/fs-writeback.c (ffff8000103c79ac)
Location: include/linux/backing-dev.h:82
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/fuse/file.c (ffff800010510050)
Location: include/linux/backing-dev.h:82
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
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
In mm/page-writeback.c (c04ea97c)
Location: include/linux/backing-dev.h:82
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
```
```
In fs/fs-writeback.c (c05a4860)
Location: include/linux/backing-dev.h:82
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/fuse/file.c (c06cbaf4)
Location: include/linux/backing-dev.h:82
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
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
In mm/page-writeback.c (c0000000003777ec)
Location: include/linux/backing-dev.h:82
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
```
```
In fs/fs-writeback.c (c0000000004c96e0)
Location: include/linux/backing-dev.h:82
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/fuse/file.c (c0000000006578cc)
Location: include/linux/backing-dev.h:82
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
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
In mm/page-writeback.c (ffffffe0001e10d2)
Location: include/linux/backing-dev.h:82
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
```
```
In fs/fs-writeback.c (ffffffe00028626a)
Location: include/linux/backing-dev.h:82
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/fuse/file.c (ffffffe00037a88e)
Location: include/linux/backing-dev.h:82
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
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
In mm/page-writeback.c (ffffffff81227c6c)
Location: include/linux/backing-dev.h:82
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
```
```
In fs/fs-writeback.c (ffffffff8130aedf)
Location: include/linux/backing-dev.h:82
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/fuse/file.c (ffffffff81424789)
Location: include/linux/backing-dev.h:82
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
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
In mm/page-writeback.c (ffffffff8121ada6)
Location: include/linux/backing-dev.h:82
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
```
```
In fs/fs-writeback.c (ffffffff812fbaf9)
Location: include/linux/backing-dev.h:82
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/fuse/file.c (ffffffff81415209)
Location: include/linux/backing-dev.h:82
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
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
In mm/page-writeback.c (ffffffff81225a0c)
Location: include/linux/backing-dev.h:82
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
```
```
In fs/fs-writeback.c (ffffffff81308ccf)
Location: include/linux/backing-dev.h:82
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/fuse/file.c (ffffffff81420929)
Location: include/linux/backing-dev.h:82
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
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
In mm/page-writeback.c (ffffffff81234d0c)
Location: include/linux/backing-dev.h:82
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_redirty
```
```
In fs/fs-writeback.c (ffffffff8131a981)
Location: include/linux/backing-dev.h:82
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/fuse/file.c (ffffffff81437714)
Location: include/linux/backing-dev.h:82
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
```
</details>
</li>
</ul>

## Differences
