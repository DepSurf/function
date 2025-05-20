# Function: <code>has_extra_refcount</code>

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
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool has_extra_refcount(struct page_state *ps, struct page *p, bool extra_pins);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff813d9d08)
Location: mm/memory-failure.c:821
Inline: True
Inline callers:
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:me_swapcache_clean
Direct callers:
  - mm/memory-failure.c:me_swapcache_dirty
  - mm/memory-failure.c:me_pagecache_clean
```
**Symbols:**

```
ffffffff813d9110-ffffffff813d91cb: has_extra_refcount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool has_extra_refcount(struct page_state *ps, struct page *p, bool extra_pins);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff8145fa47)
Location: mm/memory-failure.c:883
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_clean
Direct callers:
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:me_swapcache_dirty
  - mm/memory-failure.c:me_pagecache_clean
```
**Symbols:**

```
ffffffff8145f140-ffffffff8145f215: has_extra_refcount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool has_extra_refcount(struct page_state *ps, struct page *p, bool extra_pins);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81495c57)
Location: mm/memory-failure.c:980
Inline: True
Inline callers:
  - mm/memory-failure.c:me_swapcache_clean
Direct callers:
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:me_swapcache_dirty
  - mm/memory-failure.c:me_pagecache_clean
```
**Symbols:**

```
ffffffff814952d0-ffffffff814953b2: has_extra_refcount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool has_extra_refcount(struct page_state *ps, struct page *p, bool extra_pins);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff814c4ff0)
Location: mm/memory-failure.c:979
Inline: False
Direct callers:
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:me_swapcache_clean
  - mm/memory-failure.c:me_swapcache_dirty
  - mm/memory-failure.c:me_pagecache_clean
```
**Symbols:**

```
ffffffff814c4ff0-ffffffff814c5127: has_extra_refcount (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
