# Function: <code>xas_find_chunk</code>

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
In mm/filemap.c (ffffffff811fdf90)
Location: include/linux/xarray.h:1451
Inline: True
Inline callers:
  - mm/filemap.c:find_get_entries_tag
  - mm/filemap.c:find_get_pages_range_tag
```
```
In mm/page-writeback.c (ffffffff8120eb0f)
Location: include/linux/xarray.h:1451
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/memfd.c (ffffffff812a90a6)
Location: include/linux/xarray.h:1451
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/fs-writeback.c (ffffffff812e1817)
Location: include/linux/xarray.h:1451
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff8130ee2b)
Location: include/linux/xarray.h:1451
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In lib/xarray.c (ffffffff81a17949)
Location: include/linux/xarray.h:1451
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xas_find_marked
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
In mm/filemap.c (ffffffff81215193)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_range_tag
```
```
In mm/page-writeback.c (ffffffff8121e70f)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/memfd.c (ffffffff812c5564)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff812ffd88)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff81334b16)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In lib/xarray.c (ffffffff81a875ad)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xas_find_marked
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
In mm/filemap.c (ffffffff81223041)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_range_tag
```
```
In mm/page-writeback.c (ffffffff8122c1af)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/memfd.c (ffffffff812d6f72)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff8131258e)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff813486ee)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In lib/xarray.c (ffffffff81abe84d)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xas_find_marked
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
In mm/filemap.c (ffffffff8125093c)
Location: include/linux/xarray.h:1615
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_range_tag
```
```
In mm/page-writeback.c (ffffffff8125926f)
Location: include/linux/xarray.h:1615
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/memfd.c (ffffffff8130c0f9)
Location: include/linux/xarray.h:1615
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff8134bd74)
Location: include/linux/xarray.h:1615
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff8138e103)
Location: include/linux/xarray.h:1615
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In lib/xarray.c (ffffffff815fa2a7)
Location: include/linux/xarray.h:1615
Inline: True
Inline callers:
  - lib/xarray.c:xas_find_marked
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
In mm/filemap.c (ffffffff8125b3e9)
Location: include/linux/xarray.h:1650
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_range_tag
```
```
In mm/page-writeback.c (ffffffff8126385f)
Location: include/linux/xarray.h:1650
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/memfd.c (ffffffff81317fb9)
Location: include/linux/xarray.h:1650
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff81358fa6)
Location: include/linux/xarray.h:1650
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff8139f870)
Location: include/linux/xarray.h:1650
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In lib/xarray.c (ffffffff8161e8c4)
Location: include/linux/xarray.h:1650
Inline: True
Inline callers:
  - lib/xarray.c:xas_find_marked
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
In mm/page-writeback.c (ffffffff812684df)
Location: include/linux/xarray.h:1652
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/memfd.c (ffffffff8131e1a9)
Location: include/linux/xarray.h:1652
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff8135fb06)
Location: include/linux/xarray.h:1652
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff813a661b)
Location: include/linux/xarray.h:1652
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In lib/xarray.c (ffffffff81602f0e)
Location: include/linux/xarray.h:1652
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xas_find_marked
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
In mm/page-writeback.c (ffffffff812a6316)
Location: include/linux/xarray.h:1652
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/memfd.c (ffffffff8136b55c)
Location: include/linux/xarray.h:1652
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff813ae396)
Location: include/linux/xarray.h:1652
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/dax.c (ffffffff813f608b)
Location: include/linux/xarray.h:1652
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In lib/xarray.c (ffffffff816713cc)
Location: include/linux/xarray.h:1652
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xas_find_marked
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
In mm/page-writeback.c (ffffffff812fc79f)
Location: include/linux/xarray.h:1679
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/memfd.c (ffffffff813e95cf)
Location: include/linux/xarray.h:1679
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff814326b7)
Location: include/linux/xarray.h:1679
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/dax.c (ffffffff81469c62)
Location: include/linux/xarray.h:1679
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In lib/xarray.c (ffffffff8178ae54)
Location: include/linux/xarray.h:1679
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xas_find_marked
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
In mm/page-writeback.c (ffffffff81366ad0)
Location: include/linux/xarray.h:1694
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/memfd.c (ffffffff814715ae)
Location: include/linux/xarray.h:1694
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff814c07ae)
Location: include/linux/xarray.h:1694
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/dax.c (ffffffff814fa362)
Location: include/linux/xarray.h:1694
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In lib/xarray.c (ffffffff820483c4)
Location: include/linux/xarray.h:1694
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xas_find_marked
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
In mm/page-writeback.c (ffffffff81399120)
Location: include/linux/xarray.h:1695
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/memfd.c (ffffffff814a5a97)
Location: include/linux/xarray.h:1695
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff814f58e2)
Location: include/linux/xarray.h:1695
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/dax.c (ffffffff815317b3)
Location: include/linux/xarray.h:1695
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In lib/xarray.c (ffffffff820c6b88)
Location: include/linux/xarray.h:1695
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xas_find_marked
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
In mm/page-writeback.c (ffffffff813c2f20)
Location: include/linux/xarray.h:1713
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/memfd.c (ffffffff814d6a47)
Location: include/linux/xarray.h:1713
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff81529fef)
Location: include/linux/xarray.h:1713
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/dax.c (ffffffff81566693)
Location: include/linux/xarray.h:1713
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In lib/xarray.c (ffffffff821a1508)
Location: include/linux/xarray.h:1713
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xas_find_marked
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
In mm/filemap.c (ffff8000102b0508)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_range_tag
```
```
In mm/page-writeback.c (ffff8000102ba938)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/memfd.c (ffff80001037bf90)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffff8000103c78e0)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffff800010409700)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In lib/xarray.c (ffff800010d99b60)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xas_find_marked
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
In mm/filemap.c (c04dd110)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_range_tag
```
```
In mm/page-writeback.c (c04e6c4c)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/memfd.c (c0566cb4)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (c05a4510)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In lib/xarray.c (c0e964bc)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xas_find_marked
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
In mm/filemap.c (c0000000003658a8)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_range_tag
```
```
In mm/page-writeback.c (c000000000373460)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/memfd.c (c000000000471428)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (c0000000004c90b4)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (c000000000514af4)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In lib/xarray.c (c000000000edfa74)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xas_find_marked
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
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_range_tag
```
```
In mm/page-writeback.c (ffffffe0001ddc88)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/memfd.c (ffffffe00025257c)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffe00028626c)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffe0002b41a0)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In lib/xarray.c (ffffffe0008c32d4)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xas_find_marked
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
In mm/filemap.c (ffffffff8121b691)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_range_tag
```
```
In mm/page-writeback.c (ffffffff812247ff)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/memfd.c (ffffffff812cf552)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff8130ab6e)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff81340cce)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In lib/xarray.c (ffffffff81a5d69d)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xas_find_marked
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
In mm/filemap.c (ffffffff8120e881)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_range_tag
```
```
In mm/page-writeback.c (ffffffff812179a9)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/memfd.c (ffffffff812c01d0)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff812fb78e)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff813316b2)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In lib/xarray.c (ffffffff81a1a76d)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xas_find_marked
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
In mm/filemap.c (ffffffff81219431)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_range_tag
```
```
In mm/page-writeback.c (ffffffff8122259f)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/memfd.c (ffffffff812cd362)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff8130895e)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff8133e79e)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In lib/xarray.c (ffffffff81ac9a8d)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xas_find_marked
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
In mm/filemap.c (ffffffff81228539)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_range_tag
```
```
In mm/page-writeback.c (ffffffff81231981)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/memfd.c (ffffffff812de0da)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff8131a5de)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff81351627)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In lib/xarray.c (ffffffff81ad5fe0)
Location: include/linux/xarray.h:1580
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xas_find_marked
```
</details>
</li>
</ul>

## Differences
