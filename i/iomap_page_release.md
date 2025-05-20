# Function: <code>iomap_page_release</code>

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
void iomap_page_release(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff813259b0)
Location: fs/iomap.c:131
Inline: False
Direct callers:
  - fs/iomap.c:iomap_releasepage
```
**Symbols:**

```
ffffffff813259b0-ffffffff81325a42: iomap_page_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void iomap_page_release(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8134cb80)
Location: fs/iomap/buffered-io.c:46
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_releasepage
```
**Symbols:**

```
ffffffff8134cb80-ffffffff8134cc18: iomap_page_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void iomap_page_release(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81364e50)
Location: fs/iomap/buffered-io.c:46
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_releasepage
```
**Symbols:**

```
ffffffff81364e50-ffffffff81364ee8: iomap_page_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void iomap_page_release(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813abf40)
Location: fs/iomap/buffered-io.c:67
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_releasepage
```
**Symbols:**

```
ffffffff813abf40-ffffffff813abfd8: iomap_page_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void iomap_page_release(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813bdd90)
Location: fs/iomap/buffered-io.c:70
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_releasepage
```
**Symbols:**

```
ffffffff813bdd90-ffffffff813bdebc: iomap_page_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void iomap_page_release(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813c4f50)
Location: fs/iomap/buffered-io.c:70
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_releasepage
```
**Symbols:**

```
ffffffff813c4f50-ffffffff813c507c: iomap_page_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void iomap_page_release(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:70
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_releasepage
```
**Symbols:**

```
ffffffff81414980-ffffffff81414aba: iomap_page_release (STB_LOCAL)
ffffffff81cc79e5-ffffffff81cc7a03: iomap_page_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void iomap_page_release(struct folio *folio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:64
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_invalidate_folio
  - fs/iomap/buffered-io.c:iomap_invalidate_folio
  - fs/iomap/buffered-io.c:iomap_release_folio
```
**Symbols:**

```
ffffffff81488cd0-ffffffff81488e19: iomap_page_release (STB_LOCAL)
ffffffff81e79eb0-ffffffff81e79ee2: iomap_page_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void iomap_page_release(struct folio *folio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:72
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_invalidate_folio
  - fs/iomap/buffered-io.c:iomap_invalidate_folio
  - fs/iomap/buffered-io.c:iomap_release_folio
```
**Symbols:**

```
ffffffff8151c9a0-ffffffff8151ca98: iomap_page_release (STB_LOCAL)
ffffffff8206adef-ffffffff8206ae21: iomap_page_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void iomap_page_release(struct folio *folio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:72
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_release_folio
```
**Symbols:**

```
ffffffff81554b90-ffffffff81554c79: iomap_page_release (STB_LOCAL)
ffffffff820ead53-ffffffff820ead87: iomap_page_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void iomap_page_release(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffff80001042a890)
Location: fs/iomap/buffered-io.c:46
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_releasepage
```
**Symbols:**

```
ffff80001042a890-ffff80001042a958: iomap_page_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void iomap_page_release(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (c05f4ad0)
Location: fs/iomap/buffered-io.c:46
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_releasepage
```
**Symbols:**

```
c05f4ad0-c05f4be4: iomap_page_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void iomap_page_release(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (c00000000053c190)
Location: fs/iomap/buffered-io.c:46
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_releasepage
```
**Symbols:**

```
c00000000053c190-c00000000053c2c8: iomap_page_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void iomap_page_release(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffe0002c8a50)
Location: fs/iomap/buffered-io.c:46
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_releasepage
```
**Symbols:**

```
ffffffe0002c8a50-ffffffe0002c8ade: iomap_page_release (STB_LOCAL)
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
void iomap_page_release(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8135d430)
Location: fs/iomap/buffered-io.c:46
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_releasepage
```
**Symbols:**

```
ffffffff8135d430-ffffffff8135d4c8: iomap_page_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void iomap_page_release(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8134e0d0)
Location: fs/iomap/buffered-io.c:46
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_releasepage
```
**Symbols:**

```
ffffffff8134e0d0-ffffffff8134e168: iomap_page_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void iomap_page_release(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8135af00)
Location: fs/iomap/buffered-io.c:46
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_releasepage
```
**Symbols:**

```
ffffffff8135af00-ffffffff8135af98: iomap_page_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void iomap_page_release(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8136e680)
Location: fs/iomap/buffered-io.c:46
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_releasepage
```
**Symbols:**

```
ffffffff8136e680-ffffffff8136e718: iomap_page_release (STB_LOCAL)
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
</ul>
</details>
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
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
