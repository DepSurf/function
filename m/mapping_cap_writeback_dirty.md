# Function: <code>mapping_cap_writeback_dirty</code>

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
In mm/filemap.c (ffffffff8118e8a0)
Location: include/linux/backing-dev.h:226
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/memory-failure.c (ffffffff81202809)
Location: include/linux/backing-dev.h:226
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/fs-writeback.c (ffffffff8123c240)
Location: include/linux/backing-dev.h:226
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
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
In mm/filemap.c (ffffffff811a2430)
Location: include/linux/backing-dev.h:227
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/memory-failure.c (ffffffff81226ec0)
Location: include/linux/backing-dev.h:227
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/fs-writeback.c (ffffffff81264125)
Location: include/linux/backing-dev.h:227
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
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
In mm/filemap.c (ffffffff811b2270)
Location: include/linux/backing-dev.h:227
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/memory-failure.c (ffffffff81239487)
Location: include/linux/backing-dev.h:227
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/fs-writeback.c (ffffffff81277565)
Location: include/linux/backing-dev.h:227
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
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
In mm/filemap.c (ffffffff811b8eea)
Location: include/linux/backing-dev.h:202
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/memory-failure.c (ffffffff81244d4d)
Location: include/linux/backing-dev.h:202
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812848ff)
Location: include/linux/backing-dev.h:202
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
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
In mm/filemap.c (ffffffff811cd7ea)
Location: include/linux/backing-dev.h:207
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/memory-failure.c (ffffffff81264c3d)
Location: include/linux/backing-dev.h:207
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812a743f)
Location: include/linux/backing-dev.h:207
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
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
In mm/filemap.c (ffffffff811ef325)
Location: include/linux/backing-dev.h:208
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/memory-failure.c (ffffffff812891b8)
Location: include/linux/backing-dev.h:208
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812cdfff)
Location: include/linux/backing-dev.h:208
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
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
In mm/filemap.c (ffffffff81200b25)
Location: include/linux/backing-dev.h:208
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/memory-failure.c (ffffffff8129e108)
Location: include/linux/backing-dev.h:208
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812e32ff)
Location: include/linux/backing-dev.h:208
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
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
In mm/filemap.c (ffffffff81218740)
Location: include/linux/backing-dev.h:209
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/memory-failure.c (ffffffff812b92ba)
Location: include/linux/backing-dev.h:209
Inline: True
```
```
In fs/fs-writeback.c (ffffffff813010e1)
Location: include/linux/backing-dev.h:209
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
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
In mm/filemap.c (ffffffff81225fb0)
Location: include/linux/backing-dev.h:213
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/memory-failure.c (ffffffff812cb1aa)
Location: include/linux/backing-dev.h:213
Inline: True
```
```
In fs/fs-writeback.c (ffffffff813137c1)
Location: include/linux/backing-dev.h:213
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
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
In mm/filemap.c (ffffffff812510f0)
Location: include/linux/backing-dev.h:209
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/memory-failure.c (ffffffff813012d5)
Location: include/linux/backing-dev.h:209
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8134d081)
Location: include/linux/backing-dev.h:209
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
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
In mm/filemap.c (ffff8000102b3190)
Location: include/linux/backing-dev.h:213
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/memory-failure.c (ffff80001036ed58)
Location: include/linux/backing-dev.h:213
Inline: True
```
```
In fs/fs-writeback.c (ffff8000103c9290)
Location: include/linux/backing-dev.h:213
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
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
In mm/filemap.c (c04e03f4)
Location: include/linux/backing-dev.h:213
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In fs/fs-writeback.c (c05a6488)
Location: include/linux/backing-dev.h:213
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
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
In mm/filemap.c (c000000000369d00)
Location: include/linux/backing-dev.h:213
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/memory-failure.c (c00000000045f7c0)
Location: include/linux/backing-dev.h:213
Inline: True
```
```
In fs/fs-writeback.c (c0000000004cb690)
Location: include/linux/backing-dev.h:213
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
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
In mm/filemap.c (ffffffe0001d88f2)
Location: include/linux/backing-dev.h:213
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In fs/fs-writeback.c (ffffffe0002877a6)
Location: include/linux/backing-dev.h:213
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
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
In mm/filemap.c (ffffffff8121e600)
Location: include/linux/backing-dev.h:213
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/memory-failure.c (ffffffff812c378a)
Location: include/linux/backing-dev.h:213
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8130bda1)
Location: include/linux/backing-dev.h:213
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
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
In mm/filemap.c (ffffffff812117c0)
Location: include/linux/backing-dev.h:213
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/memory-failure.c (ffffffff812b47ca)
Location: include/linux/backing-dev.h:213
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812fc9c1)
Location: include/linux/backing-dev.h:213
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
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
In mm/filemap.c (ffffffff8121c3a0)
Location: include/linux/backing-dev.h:213
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/memory-failure.c (ffffffff812c159a)
Location: include/linux/backing-dev.h:213
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81309b91)
Location: include/linux/backing-dev.h:213
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
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
In mm/filemap.c (ffffffff8122b430)
Location: include/linux/backing-dev.h:213
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_fdatawrite_range
```
```
In mm/memory-failure.c (ffffffff812d205a)
Location: include/linux/backing-dev.h:213
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8131bbb1)
Location: include/linux/backing-dev.h:213
Inline: True
Inline callers:
  - fs/fs-writeback.c:write_inode_now
```
</details>
</li>
</ul>

## Differences
