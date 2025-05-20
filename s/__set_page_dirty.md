# Function: <code>__set_page_dirty</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __set_page_dirty(struct page *page, struct address_space *mapping, struct mem_cgroup *memcg, int warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81242840)
Location: fs/buffer.c:633
Inline: False
Direct callers:
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:mark_buffer_dirty
```
**Symbols:**

```
ffffffff81242840-ffffffff812428f5: __set_page_dirty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __set_page_dirty(struct page *page, struct address_space *mapping, int warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8126ab70)
Location: fs/buffer.c:627
Inline: False
Direct callers:
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
```
**Symbols:**

```
ffffffff8126ab70-ffffffff8126ac24: __set_page_dirty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __set_page_dirty(struct page *page, struct address_space *mapping, int warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8127dc80)
Location: fs/buffer.c:628
Inline: False
Direct callers:
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
```
**Symbols:**

```
ffffffff8127dc80-ffffffff8127dd51: __set_page_dirty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __set_page_dirty(struct page *page, struct address_space *mapping, int warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8128b860)
Location: fs/buffer.c:625
Inline: False
Direct callers:
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
```
**Symbols:**

```
ffffffff8128b860-ffffffff8128b91f: __set_page_dirty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __set_page_dirty(struct page *page, struct address_space *mapping, int warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812ae410)
Location: fs/buffer.c:604
Inline: False
Direct callers:
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
```
**Symbols:**

```
ffffffff812ae410-ffffffff812ae4cf: __set_page_dirty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __set_page_dirty(struct page *page, struct address_space *mapping, int warn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812d60e0)
Location: fs/buffer.c:573
Inline: False
Direct callers:
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
```
**Symbols:**

```
ffffffff812d60e0-ffffffff812d619d: __set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __set_page_dirty(struct page *page, struct address_space *mapping, int warn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812eb4b0)
Location: fs/buffer.c:574
Inline: False
Direct callers:
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/iomap.c:iomap_set_page_dirty
```
**Symbols:**

```
ffffffff812eb4b0-ffffffff812eb56d: __set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __set_page_dirty(struct page *page, struct address_space *mapping, int warn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130cbb0)
Location: fs/buffer.c:575
Inline: False
Direct callers:
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
**Symbols:**

```
ffffffff8130cbb0-ffffffff8130cc6f: __set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __set_page_dirty(struct page *page, struct address_space *mapping, int warn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8131fb80)
Location: fs/buffer.c:575
Inline: False
Direct callers:
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
**Symbols:**

```
ffffffff8131fb80-ffffffff8131fc3f: __set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __set_page_dirty(struct page *page, struct address_space *mapping, int warn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81359ed0)
Location: fs/buffer.c:601
Inline: False
Direct callers:
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
**Symbols:**

```
ffffffff81359ed0-ffffffff81359f97: __set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __set_page_dirty(struct page *page, struct address_space *mapping, int warn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81368000)
Location: fs/buffer.c:600
Inline: False
Direct callers:
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
**Symbols:**

```
ffffffff81368000-ffffffff813680c7: __set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __set_page_dirty(struct page *page, struct address_space *mapping, int warn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8136eac0)
Location: fs/buffer.c:600
Inline: False
Direct callers:
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
**Symbols:**

```
ffffffff8136eac0-ffffffff8136eb87: __set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __set_page_dirty(struct page *page, struct address_space *mapping, int warn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812a7e30)
Location: mm/page-writeback.c:2492
Inline: False
Direct callers:
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
```
**Symbols:**

```
ffffffff812a7e30-ffffffff812a7ef7: __set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81446484)
Location: include/linux/pagemap.h:1057
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff814d5564)
Location: include/linux/pagemap.h:1049
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty
```
</details>
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
<summary>In <code>arm64</code>: ✅</summary>

```c
void __set_page_dirty(struct page *page, struct address_space *mapping, int warn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffff8000103d81b8)
Location: fs/buffer.c:575
Inline: False
Direct callers:
  - fs/buffer.c:__set_page_dirty_buffers
```
**Symbols:**

```
ffff8000103d81b8-ffff8000103d82f4: __set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __set_page_dirty(struct page *page, struct address_space *mapping, int warn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c05b12ac)
Location: fs/buffer.c:575
Inline: False
Direct callers:
  - fs/buffer.c:__set_page_dirty_buffers
```
**Symbols:**

```
c05b12ac-c05b13a8: __set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __set_page_dirty(struct page *page, struct address_space *mapping, int warn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c0000000004dbf10)
Location: fs/buffer.c:575
Inline: False
Direct callers:
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
**Symbols:**

```
c0000000004dbf10-c0000000004dc058: __set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __set_page_dirty(struct page *page, struct address_space *mapping, int warn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffe00029103a)
Location: fs/buffer.c:575
Inline: False
Direct callers:
  - fs/buffer.c:__set_page_dirty_buffers
```
**Symbols:**

```
ffffffe00029103a-ffffffe0002910fc: __set_page_dirty (STB_GLOBAL)
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
void __set_page_dirty(struct page *page, struct address_space *mapping, int warn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81318160)
Location: fs/buffer.c:575
Inline: False
Direct callers:
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
**Symbols:**

```
ffffffff81318160-ffffffff8131821f: __set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __set_page_dirty(struct page *page, struct address_space *mapping, int warn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81308d50)
Location: fs/buffer.c:575
Inline: False
Direct callers:
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
**Symbols:**

```
ffffffff81308d50-ffffffff81308e0f: __set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __set_page_dirty(struct page *page, struct address_space *mapping, int warn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81315c30)
Location: fs/buffer.c:575
Inline: False
Direct callers:
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
**Symbols:**

```
ffffffff81315c30-ffffffff81315cef: __set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __set_page_dirty(struct page *page, struct address_space *mapping, int warn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81327830)
Location: fs/buffer.c:575
Inline: False
Direct callers:
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
**Symbols:**

```
ffffffff81327830-ffffffff813278ef: __set_page_dirty (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct mem_cgroup *memcg</code>
</li>
<li>
<b>Param reordered. </b>
<code>page, mapping, memcg, warn</code> ➡️ <code>page, mapping, warn</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
