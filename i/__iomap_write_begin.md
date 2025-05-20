# Function: <code>__iomap_write_begin</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff813253f9)
Location: fs/iomap.c:631
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8134c0d7)
Location: fs/iomap/buffered-io.c:550
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813643a7)
Location: fs/iomap/buffered-io.c:550
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __iomap_write_begin(struct inode *inode, loff_t pos, unsigned int len, int flags, struct page *page, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813aba00)
Location: fs/iomap/buffered-io.c:569
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
```
**Symbols:**

```
ffffffff813aba00-ffffffff813abccb: __iomap_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __iomap_write_begin(struct inode *inode, loff_t pos, unsigned int len, int flags, struct page *page, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813bcf90)
Location: fs/iomap/buffered-io.c:550
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
```
**Symbols:**

```
ffffffff813bcf90-ffffffff813bd19f: __iomap_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __iomap_write_begin(struct inode *inode, loff_t pos, unsigned int len, int flags, struct page *page, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813c40c0)
Location: fs/iomap/buffered-io.c:550
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
```
**Symbols:**

```
ffffffff813c40c0-ffffffff813c42ee: __iomap_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __iomap_write_begin(const struct iomap_iter *iter, loff_t pos, unsigned int len, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:546
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
```
**Symbols:**

```
ffffffff814136c0-ffffffff81413910: __iomap_write_begin (STB_LOCAL)
ffffffff81cc7952-ffffffff81cc7974: __iomap_write_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __iomap_write_begin(const struct iomap_iter *iter, loff_t pos, size_t len, struct folio *folio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:546
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
```
**Symbols:**

```
ffffffff8148ae40-ffffffff8148b10c: __iomap_write_begin (STB_LOCAL)
ffffffff81e7a3eb-ffffffff81e7a447: __iomap_write_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __iomap_write_begin(const struct iomap_iter *iter, loff_t pos, size_t len, struct folio *folio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:526
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
```
**Symbols:**

```
ffffffff8151ee10-ffffffff8151f120: __iomap_write_begin (STB_LOCAL)
ffffffff8206b406-ffffffff8206b4ca: __iomap_write_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __iomap_write_begin(const struct iomap_iter *iter, loff_t pos, size_t len, struct folio *folio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:541
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
```
**Symbols:**

```
ffffffff81556f60-ffffffff81557252: __iomap_write_begin (STB_LOCAL)
ffffffff820eb354-ffffffff820eb450: __iomap_write_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __iomap_write_begin(const struct iomap_iter *iter, loff_t pos, size_t len, struct folio *folio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:633
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
```
**Symbols:**

```
ffffffff8158d430-ffffffff8158d782: __iomap_write_begin (STB_LOCAL)
ffffffff821c8457-ffffffff821c8596: __iomap_write_begin.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffff80001042b6b4)
Location: fs/iomap/buffered-io.c:550
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (c05f4170)
Location: fs/iomap/buffered-io.c:550
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (c00000000053c7d0)
Location: fs/iomap/buffered-io.c:550
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffe0002c8f80)
Location: fs/iomap/buffered-io.c:550
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8135c987)
Location: fs/iomap/buffered-io.c:550
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8134d627)
Location: fs/iomap/buffered-io.c:550
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8135a457)
Location: fs/iomap/buffered-io.c:550
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8136dba7)
Location: fs/iomap/buffered-io.c:550
Inline: True
```
</details>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct iomap_iter *iter</code>
</li>
<li>
<b>Param removed. </b>
<code>struct inode *inode</code>
</li>
<li>
<b>Param removed. </b>
<code>int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>struct iomap *srcmap</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, pos, len, flags, page, srcmap</code> ➡️ <code>iter, pos, len, page</code>
</li>
</ul>
</details>
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
<b>Param removed. </b>
<code>struct page *page</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int len</code> ➡️ <code>size_t len</code>
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
