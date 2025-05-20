# Function: <code>iomap_read_inline_data</code>

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
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/iomap.c (ffffffff81323fb0)
Location: fs/iomap.c:252
Inline: True
Direct callers:
  - fs/iomap.c:iomap_readpage_actor
```
**Symbols:**

```
ffffffff81323fb0-ffffffff813240d6: iomap_read_inline_data.isra.29 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8134b6a0)
Location: fs/iomap/buffered-io.c:187
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
**Symbols:**

```
ffffffff8134b6a0-ffffffff8134b7ae: iomap_read_inline_data.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81363970)
Location: fs/iomap/buffered-io.c:187
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
**Symbols:**

```
ffffffff81363970-ffffffff81363a7e: iomap_read_inline_data.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813aa940)
Location: fs/iomap/buffered-io.c:217
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
**Symbols:**

```
ffffffff813aa940-ffffffff813aaa4f: iomap_read_inline_data.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813bcaa0)
Location: fs/iomap/buffered-io.c:209
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
**Symbols:**

```
ffffffff813bcaa0-ffffffff813bcbaf: iomap_read_inline_data.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813c3bb0)
Location: fs/iomap/buffered-io.c:209
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
**Symbols:**

```
ffffffff813c3bb0-ffffffff813c3cbf: iomap_read_inline_data.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
loff_t iomap_read_inline_data(const struct iomap_iter *iter, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81413050)
Location: fs/iomap/buffered-io.c:208
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
**Symbols:**

```
ffffffff81413050-ffffffff814131ea: iomap_read_inline_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int iomap_read_inline_data(const struct iomap_iter *iter, struct folio *folio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:208
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
**Symbols:**

```
ffffffff814891e0-ffffffff8148943c: iomap_read_inline_data (STB_LOCAL)
ffffffff81e79fb7-ffffffff81e79fe1: iomap_read_inline_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int iomap_read_inline_data(const struct iomap_iter *iter, struct folio *folio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:213
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
**Symbols:**

```
ffffffff8151d0e0-ffffffff8151d2e8: iomap_read_inline_data (STB_LOCAL)
ffffffff8206af7f-ffffffff8206afa9: iomap_read_inline_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int iomap_read_inline_data(const struct iomap_iter *iter, struct folio *folio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:213
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
**Symbols:**

```
ffffffff81555290-ffffffff81555491: iomap_read_inline_data (STB_LOCAL)
ffffffff820eaecf-ffffffff820eaef8: iomap_read_inline_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int iomap_read_inline_data(const struct iomap_iter *iter, struct folio *folio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:303
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
**Symbols:**

```
ffffffff8158c060-ffffffff8158c1bf: iomap_read_inline_data (STB_LOCAL)
ffffffff821c80cf-ffffffff821c811d: iomap_read_inline_data.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (ffff80001042abb0)
Location: fs/iomap/buffered-io.c:187
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
**Symbols:**

```
ffff80001042abb0-ffff80001042acc8: iomap_read_inline_data.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void iomap_read_inline_data(struct inode *inode, struct page *page, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (c05f360c)
Location: fs/iomap/buffered-io.c:187
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
**Symbols:**

```
c05f360c-c05f370c: iomap_read_inline_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (c00000000053aef0)
Location: fs/iomap/buffered-io.c:187
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
**Symbols:**

```
c00000000053aef0-c00000000053b014: iomap_read_inline_data.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffe0002c8082)
Location: fs/iomap/buffered-io.c:187
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
**Symbols:**

```
ffffffe0002c8082-ffffffe0002c8158: iomap_read_inline_data.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8135bf50)
Location: fs/iomap/buffered-io.c:187
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
**Symbols:**

```
ffffffff8135bf50-ffffffff8135c05e: iomap_read_inline_data.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8134cbf0)
Location: fs/iomap/buffered-io.c:187
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
**Symbols:**

```
ffffffff8134cbf0-ffffffff8134ccfe: iomap_read_inline_data.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81359a20)
Location: fs/iomap/buffered-io.c:187
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
**Symbols:**

```
ffffffff81359a20-ffffffff81359b2e: iomap_read_inline_data.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8136d110)
Location: fs/iomap/buffered-io.c:187
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
**Symbols:**

```
ffffffff8136d110-ffffffff8136d235: iomap_read_inline_data.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio *folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
</li>
<li>
<b>Return type changed. </b>
<code>loff_t</code> ➡️ <code>int</code>
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
<b>Arch</b>
<ul>
</ul>
