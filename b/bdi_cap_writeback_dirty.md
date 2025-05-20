# Function: <code>bdi_cap_writeback_dirty</code>

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
In mm/filemap.c (0)
Location: include/linux/backing-dev.h:209
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/backing-dev.h:209
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/backing-dev.h:209
Inline: True
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
In mm/filemap.c (0)
Location: include/linux/backing-dev.h:210
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/backing-dev.h:210
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/backing-dev.h:210
Inline: True
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
In mm/filemap.c (0)
Location: include/linux/backing-dev.h:210
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/backing-dev.h:210
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/backing-dev.h:210
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
In mm/filemap.c (0)
Location: include/linux/backing-dev.h:185
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/backing-dev.h:185
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/backing-dev.h:185
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
In mm/filemap.c (0)
Location: include/linux/backing-dev.h:190
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/backing-dev.h:190
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/backing-dev.h:190
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
In mm/filemap.c (ffffffff811ef33e)
Location: include/linux/backing-dev.h:191
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/memory-failure.c (ffffffff812891d8)
Location: include/linux/backing-dev.h:191
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812ce01f)
Location: include/linux/backing-dev.h:191
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
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
In mm/filemap.c (ffffffff81200b3e)
Location: include/linux/backing-dev.h:191
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/memory-failure.c (ffffffff8129e128)
Location: include/linux/backing-dev.h:191
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812e331f)
Location: include/linux/backing-dev.h:191
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
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
In mm/filemap.c (ffffffff8121875d)
Location: include/linux/backing-dev.h:192
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/memory-failure.c (ffffffff812b92d3)
Location: include/linux/backing-dev.h:192
Inline: True
```
```
In fs/fs-writeback.c (ffffffff813010fa)
Location: include/linux/backing-dev.h:192
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
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
In mm/filemap.c (ffffffff81225fd1)
Location: include/linux/backing-dev.h:196
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/memory-failure.c (ffffffff812cb1c3)
Location: include/linux/backing-dev.h:196
Inline: True
```
```
In fs/fs-writeback.c (ffffffff813137da)
Location: include/linux/backing-dev.h:196
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
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
In mm/filemap.c (ffffffff8125110d)
Location: include/linux/backing-dev.h:192
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/memory-failure.c (ffffffff813012ee)
Location: include/linux/backing-dev.h:192
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8134d09a)
Location: include/linux/backing-dev.h:192
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
```
</details>
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102b31bc)
Location: include/linux/backing-dev.h:196
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/memory-failure.c (ffff80001036ed74)
Location: include/linux/backing-dev.h:196
Inline: True
```
```
In fs/fs-writeback.c (ffff8000103c92ac)
Location: include/linux/backing-dev.h:196
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
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
In mm/filemap.c (c04e0418)
Location: include/linux/backing-dev.h:196
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In fs/fs-writeback.c (c05a64b8)
Location: include/linux/backing-dev.h:196
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
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
In mm/filemap.c (c000000000369d2c)
Location: include/linux/backing-dev.h:196
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/memory-failure.c (c00000000045f7e8)
Location: include/linux/backing-dev.h:196
Inline: True
```
```
In fs/fs-writeback.c (c0000000004cb6b8)
Location: include/linux/backing-dev.h:196
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
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
In mm/filemap.c (ffffffe0001d893c)
Location: include/linux/backing-dev.h:196
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In fs/fs-writeback.c (ffffffe0002877fa)
Location: include/linux/backing-dev.h:196
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
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
In mm/filemap.c (ffffffff8121e621)
Location: include/linux/backing-dev.h:196
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/memory-failure.c (ffffffff812c37a3)
Location: include/linux/backing-dev.h:196
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8130bdba)
Location: include/linux/backing-dev.h:196
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
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
In mm/filemap.c (ffffffff812117e1)
Location: include/linux/backing-dev.h:196
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/memory-failure.c (ffffffff812b47e3)
Location: include/linux/backing-dev.h:196
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812fc9da)
Location: include/linux/backing-dev.h:196
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
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
In mm/filemap.c (ffffffff8121c3c1)
Location: include/linux/backing-dev.h:196
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/memory-failure.c (ffffffff812c15b3)
Location: include/linux/backing-dev.h:196
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81309baa)
Location: include/linux/backing-dev.h:196
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
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
In mm/filemap.c (ffffffff8122b451)
Location: include/linux/backing-dev.h:196
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/memory-failure.c (ffffffff812d2073)
Location: include/linux/backing-dev.h:196
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8131bbca)
Location: include/linux/backing-dev.h:196
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
```
</details>
</li>
</ul>

## Differences
