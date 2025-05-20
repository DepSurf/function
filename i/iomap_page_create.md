# Function: <code>iomap_page_create</code>

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
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct iomap_page *iomap_page_create(struct inode *inode, struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff813245a0)
Location: fs/iomap.c:108
Inline: True
Direct callers:
  - fs/iomap.c:iomap_readpage_actor
```
**Symbols:**

```
ffffffff813245a0-ffffffff81324615: iomap_page_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct iomap_page *iomap_page_create(struct inode *inode, struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8134b7b0)
Location: fs/iomap/buffered-io.c:23
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
**Symbols:**

```
ffffffff8134b7b0-ffffffff8134b827: iomap_page_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct iomap_page *iomap_page_create(struct inode *inode, struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81363a80)
Location: fs/iomap/buffered-io.c:23
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
**Symbols:**

```
ffffffff81363a80-ffffffff81363af7: iomap_page_create (STB_LOCAL)
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
In fs/iomap/buffered-io.c (ffffffff813aba3b)
Location: fs/iomap/buffered-io.c:45
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_actor
Direct callers:
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
**Symbols:**

```
ffffffff813aa690-ffffffff813aa6f1: iomap_page_create.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct iomap_page *iomap_page_create(struct inode *inode, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813bcbb0)
Location: fs/iomap/buffered-io.c:52
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
**Symbols:**

```
ffffffff813bcbb0-ffffffff813bcc87: iomap_page_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct iomap_page *iomap_page_create(struct inode *inode, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813c3cc0)
Location: fs/iomap/buffered-io.c:52
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
**Symbols:**

```
ffffffff813c3cc0-ffffffff813c3d9c: iomap_page_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct iomap_page *iomap_page_create(struct inode *inode, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:52
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_iter
  - fs/iomap/buffered-io.c:iomap_read_inline_data
```
**Symbols:**

```
ffffffff81412f50-ffffffff81413044: iomap_page_create (STB_LOCAL)
ffffffff81cc790c-ffffffff81cc792a: iomap_page_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct iomap_page *iomap_page_create(struct inode *inode, struct folio *folio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:47
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_iter
  - fs/iomap/buffered-io.c:iomap_read_inline_data
```
**Symbols:**

```
ffffffff81489090-ffffffff814891d1: iomap_page_create (STB_LOCAL)
ffffffff81e79f7d-ffffffff81e79fb7: iomap_page_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct iomap_page *iomap_page_create(struct inode *inode, struct folio *folio, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:47
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_iter
  - fs/iomap/buffered-io.c:iomap_read_inline_data
```
**Symbols:**

```
ffffffff8151cce0-ffffffff8151cdf0: iomap_page_create (STB_LOCAL)
ffffffff8206aec4-ffffffff8206af04: iomap_page_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct iomap_page *iomap_page_create(struct inode *inode, struct folio *folio, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:47
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:__iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_iter
  - fs/iomap/buffered-io.c:iomap_read_inline_data
```
**Symbols:**

```
ffffffff81554eb0-ffffffff81554fa1: iomap_page_create (STB_LOCAL)
ffffffff820eae1e-ffffffff820eae51: iomap_page_create.cold (STB_LOCAL)
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct iomap_page *iomap_page_create(struct inode *inode, struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffff80001042a528)
Location: fs/iomap/buffered-io.c:23
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
**Symbols:**

```
ffff80001042a528-ffff80001042a5f0: iomap_page_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct iomap_page *iomap_page_create(struct inode *inode, struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (c05f2f20)
Location: fs/iomap/buffered-io.c:23
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
**Symbols:**

```
c05f2f20-c05f2fd8: iomap_page_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct iomap_page *iomap_page_create(struct inode *inode, struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (c00000000053b020)
Location: fs/iomap/buffered-io.c:23
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
**Symbols:**

```
c00000000053b020-c00000000053b118: iomap_page_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct iomap_page *iomap_page_create(struct inode *inode, struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffe0002c7ff2)
Location: fs/iomap/buffered-io.c:23
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
**Symbols:**

```
ffffffe0002c7ff2-ffffffe0002c8082: iomap_page_create (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct iomap_page *iomap_page_create(struct inode *inode, struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8135c060)
Location: fs/iomap/buffered-io.c:23
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
**Symbols:**

```
ffffffff8135c060-ffffffff8135c0d7: iomap_page_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct iomap_page *iomap_page_create(struct inode *inode, struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8134cd00)
Location: fs/iomap/buffered-io.c:23
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
**Symbols:**

```
ffffffff8134cd00-ffffffff8134cd77: iomap_page_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct iomap_page *iomap_page_create(struct inode *inode, struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81359b30)
Location: fs/iomap/buffered-io.c:23
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
**Symbols:**

```
ffffffff81359b30-ffffffff81359ba7: iomap_page_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct iomap_page *iomap_page_create(struct inode *inode, struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8136d240)
Location: fs/iomap/buffered-io.c:23
Inline: True
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
**Symbols:**

```
ffffffff8136d240-ffffffff8136d2b7: iomap_page_create (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int flags</code>
</li>
</ul>
</details>
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
