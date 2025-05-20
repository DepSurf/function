# Function: <code>xas_find_marked</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
void *xas_find_marked(struct xa_state *xas, long unsigned int max, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a16c30)
Location: lib/xarray.c:1122
Inline: False
Direct callers:
  - mm/filemap.c:find_get_entries_tag
  - mm/filemap.c:find_get_entries_tag
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_range_tag
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
  - lib/xarray.c:__xa_alloc
```
**Symbols:**

```
ffffffff81a16c30-ffffffff81a16ef0: xas_find_marked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *xas_find_marked(struct xa_state *xas, long unsigned int max, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a867c0)
Location: lib/xarray.c:1141
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_range_tag
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
  - lib/xarray.c:__xa_alloc
```
**Symbols:**

```
ffffffff81a867c0-ffffffff81a86a80: xas_find_marked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *xas_find_marked(struct xa_state *xas, long unsigned int max, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81abda50)
Location: lib/xarray.c:1150
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_range_tag
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
  - lib/xarray.c:__xa_alloc
```
**Symbols:**

```
ffffffff81abda50-ffffffff81abdce5: xas_find_marked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *xas_find_marked(struct xa_state *xas, long unsigned int max, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff815fa040)
Location: lib/xarray.c:1150
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_range_tag
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
  - lib/xarray.c:__xa_alloc
```
**Symbols:**

```
ffffffff815fa040-ffffffff815fa32a: xas_find_marked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *xas_find_marked(struct xa_state *xas, long unsigned int max, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8161e840)
Location: lib/xarray.c:1300
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_range_tag
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
  - lib/xarray.c:__xa_alloc
```
**Symbols:**

```
ffffffff8161e840-ffffffff8161eb20: xas_find_marked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *xas_find_marked(struct xa_state *xas, long unsigned int max, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81602170)
Location: lib/xarray.c:1301
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_range_tag
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
  - lib/xarray.c:__xa_alloc
```
**Symbols:**

```
ffffffff81602170-ffffffff8160245f: xas_find_marked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *xas_find_marked(struct xa_state *xas, long unsigned int max, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:1301
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_range_tag
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
  - lib/xarray.c:__xa_alloc
```
**Symbols:**

```
ffffffff81cdfc87-ffffffff81cdfd4c: xas_find_marked.cold (STB_LOCAL)
ffffffff816702d0-ffffffff8167062d: xas_find_marked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *xas_find_marked(struct xa_state *xas, long unsigned int max, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:1308
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_range_tag
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
  - lib/xarray.c:__xa_alloc
```
**Symbols:**

```
ffffffff81ea643b-ffffffff81ea64c4: xas_find_marked.cold (STB_LOCAL)
ffffffff8178a3a0-ffffffff8178a710: xas_find_marked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void *xas_find_marked(struct xa_state *xas, long unsigned int max, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:1308
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_range_tag
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
  - lib/xarray.c:__xa_alloc
```
**Symbols:**

```
ffffffff820b7cc1-ffffffff820b7d4a: xas_find_marked.cold (STB_LOCAL)
ffffffff820478b0-ffffffff82047c20: xas_find_marked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *xas_find_marked(struct xa_state *xas, long unsigned int max, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:1306
Inline: False
Direct callers:
  - mm/filemap.c:filemap_get_folios_tag
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
  - lib/xarray.c:__xa_alloc
```
**Symbols:**

```
ffffffff8213912a-ffffffff821391ba: xas_find_marked.cold (STB_LOCAL)
ffffffff820c5f50-ffffffff820c63a8: xas_find_marked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *xas_find_marked(struct xa_state *xas, long unsigned int max, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:1306
Inline: False
Direct callers:
  - mm/filemap.c:filemap_get_folios_tag
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
  - lib/xarray.c:__xa_alloc
```
**Symbols:**

```
ffffffff8221aecf-ffffffff8221af5f: xas_find_marked.cold (STB_LOCAL)
ffffffff821a08d0-ffffffff821a0d28: xas_find_marked (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void *xas_find_marked(struct xa_state *xas, long unsigned int max, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffff800010d98ef0)
Location: lib/xarray.c:1150
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_range_tag
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
  - lib/xarray.c:__xa_alloc
```
**Symbols:**

```
ffff800010d98ef0-ffff800010d99158: xas_find_marked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *xas_find_marked(struct xa_state *xas, long unsigned int max, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c0e95898)
Location: lib/xarray.c:1150
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_range_tag
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
  - lib/xarray.c:__xa_alloc
```
**Symbols:**

```
c0e95898-c0e95ac0: xas_find_marked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *xas_find_marked(struct xa_state *xas, long unsigned int max, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c000000000ede860)
Location: lib/xarray.c:1150
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_range_tag
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
  - lib/xarray.c:__xa_alloc
```
**Symbols:**

```
c000000000ede860-c000000000edeb94: xas_find_marked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *xas_find_marked(struct xa_state *xas, long unsigned int max, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffe0008c1f7e)
Location: lib/xarray.c:1150
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_range_tag
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
  - lib/xarray.c:__xa_alloc
```
**Symbols:**

```
ffffffe0008c1f7e-ffffffe0008c21be: xas_find_marked (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void *xas_find_marked(struct xa_state *xas, long unsigned int max, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a5c8a0)
Location: lib/xarray.c:1150
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_range_tag
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
  - lib/xarray.c:__xa_alloc
```
**Symbols:**

```
ffffffff81a5c8a0-ffffffff81a5cb35: xas_find_marked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *xas_find_marked(struct xa_state *xas, long unsigned int max, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a19980)
Location: lib/xarray.c:1150
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_range_tag
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
  - lib/xarray.c:__xa_alloc
```
**Symbols:**

```
ffffffff81a19980-ffffffff81a19c15: xas_find_marked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *xas_find_marked(struct xa_state *xas, long unsigned int max, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ac8c90)
Location: lib/xarray.c:1150
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_range_tag
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
  - lib/xarray.c:__xa_alloc
```
**Symbols:**

```
ffffffff81ac8c90-ffffffff81ac8f25: xas_find_marked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *xas_find_marked(struct xa_state *xas, long unsigned int max, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ad5170)
Location: lib/xarray.c:1150
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_range_tag
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/page-writeback.c:tag_pages_for_writeback
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_find
  - lib/xarray.c:__xa_alloc
```
**Symbols:**

```
ffffffff81ad5170-ffffffff81ad5405: xas_find_marked (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
