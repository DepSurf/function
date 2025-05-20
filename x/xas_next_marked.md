# Function: <code>xas_next_marked</code>

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
In mm/filemap.c (ffffffff811fdf7c)
Location: include/linux/xarray.h:1483
Inline: True
Inline callers:
  - mm/filemap.c:find_get_entries_tag
  - mm/filemap.c:find_get_pages_range_tag
```
```
In mm/page-writeback.c (ffffffff8120ea95)
Location: include/linux/xarray.h:1483
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/memfd.c (ffffffff812a9086)
Location: include/linux/xarray.h:1483
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/fs-writeback.c (ffffffff812e15f2)
Location: include/linux/xarray.h:1483
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff8130ee0c)
Location: include/linux/xarray.h:1483
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In lib/xarray.c (ffffffff81a178ef)
Location: include/linux/xarray.h:1483
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
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
In mm/filemap.c (ffffffff81215182)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_range_tag
```
```
In mm/page-writeback.c (ffffffff8121e695)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/memfd.c (ffffffff812c5545)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff812ffd75)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff81334af7)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In lib/xarray.c (ffffffff81a87630)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
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
In mm/filemap.c (ffffffff81223021)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_range_tag
```
```
In mm/page-writeback.c (ffffffff8122c135)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/memfd.c (ffffffff812d6f53)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff8131257b)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff813486cf)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In lib/xarray.c (ffffffff81abe8d0)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
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
In mm/filemap.c (ffffffff81250928)
Location: include/linux/xarray.h:1647
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_range_tag
```
```
In mm/page-writeback.c (ffffffff812591f5)
Location: include/linux/xarray.h:1647
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/memfd.c (ffffffff8130c084)
Location: include/linux/xarray.h:1647
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff8134bd61)
Location: include/linux/xarray.h:1647
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff8138e0bb)
Location: include/linux/xarray.h:1647
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In lib/xarray.c (ffffffff815fa3f3)
Location: include/linux/xarray.h:1647
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
In mm/filemap.c (ffffffff8125b3d5)
Location: include/linux/xarray.h:1682
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_range_tag
```
```
In mm/page-writeback.c (ffffffff812637e5)
Location: include/linux/xarray.h:1682
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/memfd.c (ffffffff81317f44)
Location: include/linux/xarray.h:1682
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff81358c76)
Location: include/linux/xarray.h:1682
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff8139f828)
Location: include/linux/xarray.h:1682
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In lib/xarray.c (ffffffff8161ebe3)
Location: include/linux/xarray.h:1682
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
In mm/page-writeback.c (ffffffff81268465)
Location: include/linux/xarray.h:1684
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/memfd.c (ffffffff8131e134)
Location: include/linux/xarray.h:1684
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff8135f7d6)
Location: include/linux/xarray.h:1684
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff813a6598)
Location: include/linux/xarray.h:1684
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In lib/xarray.c (ffffffff81602f9d)
Location: include/linux/xarray.h:1684
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
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
In mm/page-writeback.c (ffffffff812a6299)
Location: include/linux/xarray.h:1684
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/memfd.c (ffffffff8136b4e8)
Location: include/linux/xarray.h:1684
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff813ae13d)
Location: include/linux/xarray.h:1684
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/dax.c (ffffffff813f6008)
Location: include/linux/xarray.h:1684
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In lib/xarray.c (ffffffff81671461)
Location: include/linux/xarray.h:1684
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
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
In mm/page-writeback.c (ffffffff812fc78a)
Location: include/linux/xarray.h:1711
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/memfd.c (ffffffff813e954c)
Location: include/linux/xarray.h:1711
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff8143242e)
Location: include/linux/xarray.h:1711
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/dax.c (ffffffff81469bd4)
Location: include/linux/xarray.h:1711
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In lib/xarray.c (ffffffff8178aee5)
Location: include/linux/xarray.h:1711
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
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
In mm/page-writeback.c (ffffffff81366abd)
Location: include/linux/xarray.h:1726
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/memfd.c (ffffffff8147152e)
Location: include/linux/xarray.h:1726
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff814c04dd)
Location: include/linux/xarray.h:1726
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/dax.c (ffffffff814fa324)
Location: include/linux/xarray.h:1726
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In lib/xarray.c (ffffffff82048455)
Location: include/linux/xarray.h:1726
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
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
In mm/page-writeback.c (ffffffff8139910d)
Location: include/linux/xarray.h:1727
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/memfd.c (ffffffff814a5a82)
Location: include/linux/xarray.h:1727
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff814f58cd)
Location: include/linux/xarray.h:1727
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/dax.c (ffffffff815317a1)
Location: include/linux/xarray.h:1727
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In lib/xarray.c (ffffffff820c6b61)
Location: include/linux/xarray.h:1727
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
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
In mm/page-writeback.c (ffffffff813c2f0d)
Location: include/linux/xarray.h:1745
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/memfd.c (ffffffff814d6a32)
Location: include/linux/xarray.h:1745
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff81529fda)
Location: include/linux/xarray.h:1745
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/dax.c (ffffffff81566681)
Location: include/linux/xarray.h:1745
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In lib/xarray.c (ffffffff821a14e1)
Location: include/linux/xarray.h:1745
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
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
In mm/filemap.c (ffff8000102b0490)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_range_tag
```
```
In mm/page-writeback.c (ffff8000102ba888)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/memfd.c (ffff80001037bef0)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffff8000103c7630)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffff80001040969c)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In lib/xarray.c (ffff800010d99b10)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
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
In mm/filemap.c (c04dd0b0)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_range_tag
```
```
In mm/page-writeback.c (c04e6bb8)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/memfd.c (c0566c8c)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (c05a44e8)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In lib/xarray.c (c0e96494)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
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
In mm/filemap.c (c000000000365888)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_range_tag
```
```
In mm/page-writeback.c (c000000000373440)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/memfd.c (c000000000471408)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (c0000000004c9094)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (c000000000514cbc)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In lib/xarray.c (c000000000edfafc)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
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
In mm/filemap.c (ffffffe0001d60ac)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_range_tag
```
```
In mm/page-writeback.c (ffffffe0001ddc88)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/memfd.c (ffffffe00025257c)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffe00028626c)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffe0002b41a0)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In lib/xarray.c (ffffffe0008c32d4)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
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
In mm/filemap.c (ffffffff8121b671)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_range_tag
```
```
In mm/page-writeback.c (ffffffff81224785)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/memfd.c (ffffffff812cf533)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff8130ab5b)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff81340caf)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In lib/xarray.c (ffffffff81a5d720)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
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
In mm/filemap.c (ffffffff8120e861)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_range_tag
```
```
In mm/page-writeback.c (ffffffff81217935)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/memfd.c (ffffffff812c01b1)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff812fb77b)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff81331693)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In lib/xarray.c (ffffffff81a1a7f0)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
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
In mm/filemap.c (ffffffff81219411)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_range_tag
```
```
In mm/page-writeback.c (ffffffff81222525)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/memfd.c (ffffffff812cd343)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff8130894b)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff8133e77f)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In lib/xarray.c (ffffffff81ac9b10)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
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
In mm/filemap.c (ffffffff81228519)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_range_tag
```
```
In mm/page-writeback.c (ffffffff81231915)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/memfd.c (ffffffff812de0bb)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff8131a5cb)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff81351608)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In lib/xarray.c (ffffffff81ad6063)
Location: include/linux/xarray.h:1612
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
```
</details>
</li>
</ul>

## Differences
