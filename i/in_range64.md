# Function: <code>in_range64</code>

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
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813b9752)
Location: include/linux/minmax.h:239
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
```
```
In mm/memory.c (0)
Location: include/linux/minmax.h:239
Inline: True
```
```
In mm/mlock.c (ffffffff8142545d)
Location: include/linux/minmax.h:239
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
```
```
In mm/rmap.c (ffffffff8143782d)
Location: include/linux/minmax.h:239
Inline: True
Inline callers:
  - mm/rmap.c:folio_referenced_one
```
```
In fs/ext4/extents.c (ffffffff815d440d)
Location: include/linux/minmax.h:239
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
```
In fs/ext4/fast_commit.c (ffffffff8164871d)
Location: include/linux/minmax.h:239
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay_check_excluded
```
```
In lib/logic_pio.c (ffffffff8217d93d)
Location: include/linux/minmax.h:239
Inline: True
Inline callers:
  - lib/logic_pio.c:logic_pio_trans_cpuaddr
  - lib/logic_pio.c:logic_pio_to_hwaddr
```
</details>
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
