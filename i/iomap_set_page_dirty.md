# Function: <code>iomap_set_page_dirty</code>

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
int iomap_set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff81323770)
Location: fs/iomap.c:699
Inline: False
Direct callers:
  - fs/iomap.c:iomap_write_end
```
**Symbols:**

```
ffffffff81323770-ffffffff81323803: iomap_set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int iomap_set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8134b2e0)
Location: fs/iomap/buffered-io.c:633
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
**Symbols:**

```
ffffffff8134b2e0-ffffffff8134b378: iomap_set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int iomap_set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81363590)
Location: fs/iomap/buffered-io.c:633
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
**Symbols:**

```
ffffffff81363590-ffffffff81363628: iomap_set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int iomap_set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813a9e90)
Location: fs/iomap/buffered-io.c:664
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
**Symbols:**

```
ffffffff813a9e90-ffffffff813a9f28: iomap_set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int iomap_set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813bb4e0)
Location: fs/iomap/buffered-io.c:644
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
**Symbols:**

```
ffffffff813bb4e0-ffffffff813bb578: iomap_set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int iomap_set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813c2600)
Location: fs/iomap/buffered-io.c:644
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
**Symbols:**

```
ffffffff813c2600-ffffffff813c2697: iomap_set_page_dirty (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int iomap_set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffff80001042a250)
Location: fs/iomap/buffered-io.c:633
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
**Symbols:**

```
ffff80001042a250-ffff80001042a36c: iomap_set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int iomap_set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (c05f2e78)
Location: fs/iomap/buffered-io.c:633
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
**Symbols:**

```
c05f2e78-c05f2f20: iomap_set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int iomap_set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (c00000000053ab40)
Location: fs/iomap/buffered-io.c:633
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
**Symbols:**

```
c00000000053ab40-c00000000053ac90: iomap_set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int iomap_set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffe0002c846a)
Location: fs/iomap/buffered-io.c:633
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
**Symbols:**

```
ffffffe0002c846a-ffffffe0002c8528: iomap_set_page_dirty (STB_GLOBAL)
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
int iomap_set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8135bb70)
Location: fs/iomap/buffered-io.c:633
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
**Symbols:**

```
ffffffff8135bb70-ffffffff8135bc08: iomap_set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int iomap_set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8134c810)
Location: fs/iomap/buffered-io.c:633
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
**Symbols:**

```
ffffffff8134c810-ffffffff8134c8a8: iomap_set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int iomap_set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81359640)
Location: fs/iomap/buffered-io.c:633
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
**Symbols:**

```
ffffffff81359640-ffffffff813596d8: iomap_set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int iomap_set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8136cd40)
Location: fs/iomap/buffered-io.c:633
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
**Symbols:**

```
ffffffff8136cd40-ffffffff8136cdd8: iomap_set_page_dirty (STB_GLOBAL)
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
