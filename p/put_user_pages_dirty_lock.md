# Function: <code>put_user_pages_dirty_lock</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void put_user_pages_dirty_lock(struct page **pages, long unsigned int npages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8124abc0)
Location: mm/gup.c:108
Inline: False
```
**Symbols:**

```
ffffffff8124abc0-ffffffff8124abd7: put_user_pages_dirty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void put_user_pages_dirty_lock(struct page **pages, long unsigned int npages, bool make_dirty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81258fa0)
Location: mm/gup.c:54
Inline: True
```
**Symbols:**

```
ffffffff81258fa0-ffffffff812590c3: put_user_pages_dirty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void put_user_pages_dirty_lock(struct page **pages, long unsigned int npages, bool make_dirty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffff8000102f0ea8)
Location: mm/gup.c:54
Inline: True
```
**Symbols:**

```
ffff8000102f0ea8-ffff8000102f0fe0: put_user_pages_dirty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void put_user_pages_dirty_lock(struct page **pages, long unsigned int npages, bool make_dirty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (c0514598)
Location: mm/gup.c:54
Inline: True
Direct callers:
  - net/xdp/xdp_umem.c:xdp_umem_unpin_pages
```
**Symbols:**

```
c0514598-c05146b8: put_user_pages_dirty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void put_user_pages_dirty_lock(struct page **pages, long unsigned int npages, bool make_dirty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (c0000000003b5b50)
Location: mm/gup.c:54
Inline: True
Direct callers:
  - net/xdp/xdp_umem.c:xdp_umem_unpin_pages
```
**Symbols:**

```
c0000000003b5b50-c0000000003b5d9c: put_user_pages_dirty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void put_user_pages_dirty_lock(struct page **pages, long unsigned int npages, bool make_dirty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffe0002044a8)
Location: mm/gup.c:54
Inline: True
Direct callers:
  - net/xdp/xdp_umem.c:xdp_umem_unpin_pages
```
**Symbols:**

```
ffffffe0002044a8-ffffffe0002045c8: put_user_pages_dirty_lock (STB_GLOBAL)
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
void put_user_pages_dirty_lock(struct page **pages, long unsigned int npages, bool make_dirty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812515f0)
Location: mm/gup.c:54
Inline: True
```
**Symbols:**

```
ffffffff812515f0-ffffffff81251713: put_user_pages_dirty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void put_user_pages_dirty_lock(struct page **pages, long unsigned int npages, bool make_dirty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812444e0)
Location: mm/gup.c:54
Inline: True
```
**Symbols:**

```
ffffffff812444e0-ffffffff81244603: put_user_pages_dirty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void put_user_pages_dirty_lock(struct page **pages, long unsigned int npages, bool make_dirty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8124f390)
Location: mm/gup.c:54
Inline: True
```
**Symbols:**

```
ffffffff8124f390-ffffffff8124f4b3: put_user_pages_dirty_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void put_user_pages_dirty_lock(struct page **pages, long unsigned int npages, bool make_dirty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8125ed00)
Location: mm/gup.c:54
Inline: True
```
**Symbols:**

```
ffffffff8125ed00-ffffffff8125ee23: put_user_pages_dirty_lock (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool make_dirty</code>
</li>
</ul>
</details>
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
