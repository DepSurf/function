# Function: <code>iomap_writepage_map</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int iomap_writepage_map(struct iomap_writepage_ctx *wpc, struct writeback_control *wbc, struct inode *inode, struct page *page, u64 end_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813ab650)
Location: fs/iomap/buffered-io.c:1367
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
```
**Symbols:**

```
ffffffff813ab650-ffffffff813ab9f2: iomap_writepage_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int iomap_writepage_map(struct iomap_writepage_ctx *wpc, struct writeback_control *wbc, struct inode *inode, struct page *page, u64 end_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813bc020)
Location: fs/iomap/buffered-io.c:1337
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
```
**Symbols:**

```
ffffffff813bc020-ffffffff813bc410: iomap_writepage_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int iomap_writepage_map(struct iomap_writepage_ctx *wpc, struct writeback_control *wbc, struct inode *inode, struct page *page, u64 end_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813c3500)
Location: fs/iomap/buffered-io.c:1333
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
```
**Symbols:**

```
ffffffff813c3500-ffffffff813c38ee: iomap_writepage_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int iomap_writepage_map(struct iomap_writepage_ctx *wpc, struct writeback_control *wbc, struct inode *inode, struct page *page, u64 end_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:1295
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
```
**Symbols:**

```
ffffffff81413bb0-ffffffff81413f15: iomap_writepage_map (STB_LOCAL)
ffffffff81cc7974-ffffffff81cc79bc: iomap_writepage_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int iomap_writepage_map(struct iomap_writepage_ctx *wpc, struct writeback_control *wbc, struct inode *inode, struct folio *folio, u64 end_pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:1328
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
```
**Symbols:**

```
ffffffff81489760-ffffffff81489b5c: iomap_writepage_map (STB_LOCAL)
ffffffff81e7a05c-ffffffff81e7a0ea: iomap_writepage_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int iomap_writepage_map(struct iomap_writepage_ctx *wpc, struct writeback_control *wbc, struct inode *inode, struct folio *folio, u64 end_pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:1589
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
```
**Symbols:**

```
ffffffff8151d640-ffffffff8151da47: iomap_writepage_map (STB_LOCAL)
ffffffff8206b00f-ffffffff8206b0a9: iomap_writepage_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int iomap_writepage_map(struct iomap_writepage_ctx *wpc, struct writeback_control *wbc, struct inode *inode, struct folio *folio, u64 end_pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:1609
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
```
**Symbols:**

```
ffffffff815558e0-ffffffff81555cf2: iomap_writepage_map (STB_LOCAL)
ffffffff820eaf79-ffffffff820eb040: iomap_writepage_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int iomap_writepage_map(struct iomap_writepage_ctx *wpc, struct writeback_control *wbc, struct inode *inode, struct folio *folio, u64 end_pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:1777
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
```
**Symbols:**

```
ffffffff8158bb60-ffffffff8158c045: iomap_writepage_map (STB_LOCAL)
ffffffff821c7f80-ffffffff821c80cf: iomap_writepage_map.cold (STB_LOCAL)
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
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio *folio</code>
</li>
<li>
<b>Param added. </b>
<code>u64 end_pos</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 end_offset</code>
</li>
</ul>
</details>
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
