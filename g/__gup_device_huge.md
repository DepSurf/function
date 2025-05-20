# Function: <code>__gup_device_huge</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __gup_device_huge(long unsigned int pfn, long unsigned int addr, long unsigned int end, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811eecf0)
Location: mm/gup.c:1356
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
```
**Symbols:**

```
ffffffff811eecf0-ffffffff811eee93: __gup_device_huge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __gup_device_huge(long unsigned int pfn, long unsigned int addr, long unsigned int end, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812051f0)
Location: mm/gup.c:1445
Inline: False
Direct callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
```
**Symbols:**

```
ffffffff812051f0-ffffffff81205395: __gup_device_huge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __gup_device_huge(long unsigned int pfn, long unsigned int addr, long unsigned int end, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81226150)
Location: mm/gup.c:1450
Inline: False
Direct callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
```
**Symbols:**

```
ffffffff81226150-ffffffff81226238: __gup_device_huge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __gup_device_huge(long unsigned int pfn, long unsigned int addr, long unsigned int end, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812398c0)
Location: mm/gup.c:1475
Inline: False
Direct callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
**Symbols:**

```
ffffffff812398c0-ffffffff812399a5: __gup_device_huge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __gup_device_huge(long unsigned int pfn, long unsigned int addr, long unsigned int end, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8124a9e0)
Location: mm/gup.c:1899
Inline: False
Direct callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
**Symbols:**

```
ffffffff8124a9e0-ffffffff8124aac4: __gup_device_huge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __gup_device_huge(long unsigned int pfn, long unsigned int addr, long unsigned int end, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81258eb0)
Location: mm/gup.c:1913
Inline: False
Direct callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
**Symbols:**

```
ffffffff81258eb0-ffffffff81258f94: __gup_device_huge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __gup_device_huge(long unsigned int pfn, long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8128a860)
Location: mm/gup.c:2313
Inline: False
Direct callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
```
**Symbols:**

```
ffffffff8128a860-ffffffff8128a94c: __gup_device_huge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __gup_device_huge(long unsigned int pfn, long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81294510)
Location: mm/gup.c:2091
Inline: False
Direct callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
```
**Symbols:**

```
ffffffff81294510-ffffffff81294608: __gup_device_huge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __gup_device_huge(long unsigned int pfn, long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81299f60)
Location: mm/gup.c:2157
Inline: False
Direct callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
```
**Symbols:**

```
ffffffff81299f60-ffffffff8129a058: __gup_device_huge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __gup_device_huge(long unsigned int pfn, long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812da8d0)
Location: mm/gup.c:2250
Inline: False
Direct callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
```
**Symbols:**

```
ffffffff812da8d0-ffffffff812da9e4: __gup_device_huge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __gup_device_huge(long unsigned int pfn, long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8133a3f0)
Location: mm/gup.c:2383
Inline: False
Direct callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
```
**Symbols:**

```
ffffffff8133a3f0-ffffffff8133a564: __gup_device_huge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __gup_device_huge(long unsigned int pfn, long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813b1e80)
Location: mm/gup.c:2429
Inline: False
Direct callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
```
**Symbols:**

```
ffffffff813b1e80-ffffffff813b2022: __gup_device_huge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __gup_device_huge(long unsigned int pfn, long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813e6c20)
Location: mm/gup.c:2664
Inline: False
Direct callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
```
**Symbols:**

```
ffffffff813e6c20-ffffffff813e6dc2: __gup_device_huge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __gup_device_huge(long unsigned int pfn, long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff814118b0)
Location: mm/gup.c:2682
Inline: False
Direct callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
```
**Symbols:**

```
ffffffff814118b0-ffffffff81411a4f: __gup_device_huge (STB_LOCAL)
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
In mm/gup.c (ffff8000102f131c)
Location: mm/gup.c:1913
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (c0000000003b6e3c)
Location: mm/gup.c:1913
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int __gup_device_huge(long unsigned int pfn, long unsigned int addr, long unsigned int end, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81251500)
Location: mm/gup.c:1913
Inline: False
Direct callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
**Symbols:**

```
ffffffff81251500-ffffffff812515e4: __gup_device_huge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __gup_device_huge(long unsigned int pfn, long unsigned int addr, long unsigned int end, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812443f0)
Location: mm/gup.c:1913
Inline: False
Direct callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
**Symbols:**

```
ffffffff812443f0-ffffffff812444d4: __gup_device_huge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __gup_device_huge(long unsigned int pfn, long unsigned int addr, long unsigned int end, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8124f2a0)
Location: mm/gup.c:1913
Inline: False
Direct callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
**Symbols:**

```
ffffffff8124f2a0-ffffffff8124f384: __gup_device_huge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __gup_device_huge(long unsigned int pfn, long unsigned int addr, long unsigned int end, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8125ec10)
Location: mm/gup.c:1913
Inline: False
Direct callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
**Symbols:**

```
ffffffff8125ec10-ffffffff8125ecfc: __gup_device_huge (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>pfn, addr, end, pages, nr</code> ➡️ <code>pfn, addr, end, flags, pages, nr</code>
</li>
</ul>
</details>
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
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
