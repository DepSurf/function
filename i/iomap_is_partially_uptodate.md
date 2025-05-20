# Function: <code>iomap_is_partially_uptodate</code>

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
int iomap_is_partially_uptodate(struct page *page, long unsigned int from, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff813235b0)
Location: fs/iomap.c:510
Inline: False
```
**Symbols:**

```
ffffffff813235b0-ffffffff8132362d: iomap_is_partially_uptodate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int iomap_is_partially_uptodate(struct page *page, long unsigned int from, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8134b270)
Location: fs/iomap/buffered-io.c:429
Inline: False
```
**Symbols:**

```
ffffffff8134b270-ffffffff8134b2df: iomap_is_partially_uptodate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int iomap_is_partially_uptodate(struct page *page, long unsigned int from, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81363520)
Location: fs/iomap/buffered-io.c:429
Inline: False
```
**Symbols:**

```
ffffffff81363520-ffffffff8136358f: iomap_is_partially_uptodate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int iomap_is_partially_uptodate(struct page *page, long unsigned int from, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813aa590)
Location: fs/iomap/buffered-io.c:452
Inline: False
```
**Symbols:**

```
ffffffff813aa590-ffffffff813aa608: iomap_is_partially_uptodate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int iomap_is_partially_uptodate(struct page *page, long unsigned int from, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813bbbe0)
Location: fs/iomap/buffered-io.c:433
Inline: False
```
**Symbols:**

```
ffffffff813bbbe0-ffffffff813bbc58: iomap_is_partially_uptodate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int iomap_is_partially_uptodate(struct page *page, long unsigned int from, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813c2ff0)
Location: fs/iomap/buffered-io.c:433
Inline: False
```
**Symbols:**

```
ffffffff813c2ff0-ffffffff813c3063: iomap_is_partially_uptodate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int iomap_is_partially_uptodate(struct page *page, long unsigned int from, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:434
Inline: False
```
**Symbols:**

```
ffffffff81cc76de-ffffffff81cc7727: iomap_is_partially_uptodate.cold (STB_LOCAL)
ffffffff814122b0-ffffffff81412359: iomap_is_partially_uptodate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool iomap_is_partially_uptodate(struct folio *folio, size_t from, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:432
Inline: False
```
**Symbols:**

```
ffffffff81e79e30-ffffffff81e79eb0: iomap_is_partially_uptodate.cold (STB_LOCAL)
ffffffff81488bb0-ffffffff81488cc8: iomap_is_partially_uptodate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool iomap_is_partially_uptodate(struct folio *folio, size_t from, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:437
Inline: False
```
**Symbols:**

```
ffffffff8206ad6f-ffffffff8206adef: iomap_is_partially_uptodate.cold (STB_LOCAL)
ffffffff8151c8a0-ffffffff8151c982: iomap_is_partially_uptodate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool iomap_is_partially_uptodate(struct folio *folio, size_t from, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:437
Inline: False
```
**Symbols:**

```
ffffffff820eacd3-ffffffff820ead53: iomap_is_partially_uptodate.cold (STB_LOCAL)
ffffffff81554aa0-ffffffff81554b7e: iomap_is_partially_uptodate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool iomap_is_partially_uptodate(struct folio *folio, size_t from, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:517
Inline: False
```
**Symbols:**

```
ffffffff821c7c20-ffffffff821c7c8d: iomap_is_partially_uptodate.cold (STB_LOCAL)
ffffffff8158ac90-ffffffff8158ad74: iomap_is_partially_uptodate (STB_GLOBAL)
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
int iomap_is_partially_uptodate(struct page *page, long unsigned int from, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffff800010429ee8)
Location: fs/iomap/buffered-io.c:429
Inline: False
```
**Symbols:**

```
ffff800010429ee8-ffff800010429fe0: iomap_is_partially_uptodate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int iomap_is_partially_uptodate(struct page *page, long unsigned int from, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (c05f26c8)
Location: fs/iomap/buffered-io.c:429
Inline: False
```
**Symbols:**

```
c05f26c8-c05f2798: iomap_is_partially_uptodate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int iomap_is_partially_uptodate(struct page *page, long unsigned int from, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (c00000000053a160)
Location: fs/iomap/buffered-io.c:429
Inline: False
```
**Symbols:**

```
c00000000053a160-c00000000053a240: iomap_is_partially_uptodate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int iomap_is_partially_uptodate(struct page *page, long unsigned int from, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffe0002c793a)
Location: fs/iomap/buffered-io.c:429
Inline: False
```
**Symbols:**

```
ffffffe0002c793a-ffffffe0002c7a08: iomap_is_partially_uptodate (STB_GLOBAL)
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
int iomap_is_partially_uptodate(struct page *page, long unsigned int from, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8135bb00)
Location: fs/iomap/buffered-io.c:429
Inline: False
```
**Symbols:**

```
ffffffff8135bb00-ffffffff8135bb6f: iomap_is_partially_uptodate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int iomap_is_partially_uptodate(struct page *page, long unsigned int from, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8134c7a0)
Location: fs/iomap/buffered-io.c:429
Inline: False
```
**Symbols:**

```
ffffffff8134c7a0-ffffffff8134c80f: iomap_is_partially_uptodate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int iomap_is_partially_uptodate(struct page *page, long unsigned int from, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813595d0)
Location: fs/iomap/buffered-io.c:429
Inline: False
```
**Symbols:**

```
ffffffff813595d0-ffffffff8135963f: iomap_is_partially_uptodate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int iomap_is_partially_uptodate(struct page *page, long unsigned int from, long unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8136ccd0)
Location: fs/iomap/buffered-io.c:429
Inline: False
```
**Symbols:**

```
ffffffff8136ccd0-ffffffff8136cd3f: iomap_is_partially_uptodate (STB_GLOBAL)
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
<code>long unsigned int from</code> ➡️ <code>size_t from</code>
</li>
<li>
<b>Param type changed. </b>
<code>long unsigned int count</code> ➡️ <code>size_t count</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
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
