# Function: <code>iomap_add_to_ioend</code>

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
void iomap_add_to_ioend(struct inode *inode, loff_t offset, struct page *page, struct iomap_page *iop, struct iomap_writepage_ctx *wpc, struct writeback_control *wbc, struct list_head *iolist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813aa230)
Location: fs/iomap/buffered-io.c:1318
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
```
**Symbols:**

```
ffffffff813aa230-ffffffff813aa43f: iomap_add_to_ioend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void iomap_add_to_ioend(struct inode *inode, loff_t offset, struct page *page, struct iomap_page *iop, struct iomap_writepage_ctx *wpc, struct writeback_control *wbc, struct list_head *iolist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813bb880)
Location: fs/iomap/buffered-io.c:1288
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
```
**Symbols:**

```
ffffffff813bb880-ffffffff813bba86: iomap_add_to_ioend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void iomap_add_to_ioend(struct inode *inode, loff_t offset, struct page *page, struct iomap_page *iop, struct iomap_writepage_ctx *wpc, struct writeback_control *wbc, struct list_head *iolist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813c2870)
Location: fs/iomap/buffered-io.c:1284
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
```
**Symbols:**

```
ffffffff813c2870-ffffffff813c2b7c: iomap_add_to_ioend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void iomap_add_to_ioend(struct inode *inode, loff_t offset, struct page *page, struct iomap_page *iop, struct iomap_writepage_ctx *wpc, struct writeback_control *wbc, struct list_head *iolist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:1253
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
```
**Symbols:**

```
ffffffff814127e0-ffffffff81412aca: iomap_add_to_ioend (STB_LOCAL)
ffffffff81cc785f-ffffffff81cc7898: iomap_add_to_ioend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void iomap_add_to_ioend(struct inode *inode, loff_t pos, struct folio *folio, struct iomap_page *iop, struct iomap_writepage_ctx *wpc, struct writeback_control *wbc, struct list_head *iolist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:1286
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
```
**Symbols:**

```
ffffffff81489440-ffffffff8148975b: iomap_add_to_ioend (STB_LOCAL)
ffffffff81e79fe1-ffffffff81e7a05c: iomap_add_to_ioend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void iomap_add_to_ioend(struct inode *inode, loff_t pos, struct folio *folio, struct iomap_page *iop, struct iomap_writepage_ctx *wpc, struct writeback_control *wbc, struct list_head *iolist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:1547
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
```
**Symbols:**

```
ffffffff8151ce00-ffffffff8151d0d0: iomap_add_to_ioend (STB_LOCAL)
ffffffff8206af04-ffffffff8206af7f: iomap_add_to_ioend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void iomap_add_to_ioend(struct inode *inode, loff_t pos, struct folio *folio, struct iomap_page *iop, struct iomap_writepage_ctx *wpc, struct writeback_control *wbc, struct list_head *iolist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:1567
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
```
**Symbols:**

```
ffffffff81554fc0-ffffffff81555277: iomap_add_to_ioend (STB_LOCAL)
ffffffff820eae51-ffffffff820eaecf: iomap_add_to_ioend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void iomap_add_to_ioend(struct inode *inode, loff_t pos, struct folio *folio, struct iomap_folio_state *ifs, struct iomap_writepage_ctx *wpc, struct writeback_control *wbc, struct list_head *iolist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:1735
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
```
**Symbols:**

```
ffffffff8158b290-ffffffff8158b549: iomap_add_to_ioend (STB_LOCAL)
ffffffff821c7e3b-ffffffff821c7eba: iomap_add_to_ioend.cold (STB_LOCAL)
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
<code>loff_t pos</code>
</li>
<li>
<b>Param added. </b>
<code>struct folio *folio</code>
</li>
<li>
<b>Param removed. </b>
<code>loff_t offset</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct iomap_folio_state *ifs</code>
</li>
<li>
<b>Param removed. </b>
<code>struct iomap_page *iop</code>
</li>
</ul>
</details>
</li>
</ul>
