# Function: <code>__free_pages_core</code>

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
void __free_pages_core(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812704b0)
Location: mm/page_alloc.c:1430
Inline: False
Direct callers:
  - mm/page_alloc.c:memblock_free_pages
  - mm/memory_hotplug.c:generic_online_page
```
**Symbols:**

```
ffffffff812704b0-ffffffff81270546: __free_pages_core (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __free_pages_core(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127f2f0)
Location: mm/page_alloc.c:1417
Inline: False
Direct callers:
  - mm/page_alloc.c:memblock_free_pages
  - mm/memory_hotplug.c:generic_online_page
```
**Symbols:**

```
ffffffff8127f2f0-ffffffff8127f386: __free_pages_core (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __free_pages_core(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812b15e0)
Location: mm/page_alloc.c:1472
Inline: False
Direct callers:
  - mm/page_alloc.c:memblock_free_pages
  - mm/memory_hotplug.c:generic_online_page
```
**Symbols:**

```
ffffffff812b15e0-ffffffff812b166e: __free_pages_core (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __free_pages_core(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bb3e0)
Location: mm/page_alloc.c:1538
Inline: False
Direct callers:
  - mm/page_alloc.c:memblock_free_pages
  - mm/memory_hotplug.c:generic_online_page
```
**Symbols:**

```
ffffffff812bb3e0-ffffffff812bb46e: __free_pages_core (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __free_pages_core(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812c0550)
Location: mm/page_alloc.c:1573
Inline: False
Direct callers:
  - mm/page_alloc.c:memblock_free_pages
  - mm/memory_hotplug.c:generic_online_page
```
**Symbols:**

```
ffffffff812c0550-ffffffff812c05e1: __free_pages_core (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __free_pages_core(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:1659
Inline: False
Direct callers:
  - mm/page_alloc.c:memblock_free_pages
  - mm/memory_hotplug.c:generic_online_page
  - mm/memory_hotplug.c:generic_online_page
```
**Symbols:**

```
ffffffff81cbd471-ffffffff81cbd489: __free_pages_core.cold (STB_LOCAL)
ffffffff81303340-ffffffff81303413: __free_pages_core (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __free_pages_core(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:1642
Inline: False
Direct callers:
  - mm/page_alloc.c:memblock_free_pages
  - mm/memory_hotplug.c:generic_online_page
  - mm/memory_hotplug.c:generic_online_page
```
**Symbols:**

```
ffffffff81e6f44f-ffffffff81e6f46d: __free_pages_core.cold (STB_LOCAL)
ffffffff8136b0b0-ffffffff8136b19b: __free_pages_core (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __free_pages_core(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:1723
Inline: False
Direct callers:
  - mm/page_alloc.c:memblock_free_pages
  - mm/memory_hotplug.c:generic_online_page
  - mm/memory_hotplug.c:generic_online_page
```
**Symbols:**

```
ffffffff820651f1-ffffffff8206520f: __free_pages_core.cold (STB_LOCAL)
ffffffff813e73b0-ffffffff813e749b: __free_pages_core (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __free_pages_core(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:1321
Inline: False
Direct callers:
  - mm/mm_init.c:memblock_free_pages
  - mm/memory_hotplug.c:generic_online_page
  - mm/memory_hotplug.c:generic_online_page
```
**Symbols:**

```
ffffffff820e4963-ffffffff820e49ee: __free_pages_core.cold (STB_LOCAL)
ffffffff8141c4c0-ffffffff8141c71b: __free_pages_core (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __free_pages_core(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:1284
Inline: False
Direct callers:
  - mm/mm_init.c:memblock_free_pages
  - mm/memory_hotplug.c:generic_online_page
  - mm/memory_hotplug.c:generic_online_page
```
**Symbols:**

```
ffffffff821c15fe-ffffffff821c1689: __free_pages_core.cold (STB_LOCAL)
ffffffff81448f60-ffffffff814491bb: __free_pages_core (STB_GLOBAL)
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
void __free_pages_core(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010316e30)
Location: mm/page_alloc.c:1417
Inline: False
Direct callers:
  - mm/page_alloc.c:memblock_free_pages
  - mm/memory_hotplug.c:generic_online_page
```
**Symbols:**

```
ffff800010316e30-ffff800010316f2c: __free_pages_core (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __free_pages_core(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0531684)
Location: mm/page_alloc.c:1417
Inline: False
Direct callers:
  - mm/page_alloc.c:memblock_free_pages
```
**Symbols:**

```
c0531684-c0531748: __free_pages_core (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __free_pages_core(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003e91a0)
Location: mm/page_alloc.c:1417
Inline: False
Direct callers:
  - mm/page_alloc.c:memblock_free_pages
  - mm/memory_hotplug.c:generic_online_page
```
**Symbols:**

```
c0000000003e91a0-c0000000003e9288: __free_pages_core (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __free_pages_core(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021d1ca)
Location: mm/page_alloc.c:1417
Inline: False
Direct callers:
  - mm/page_alloc.c:memblock_free_pages
```
**Symbols:**

```
ffffffe00021d1ca-ffffffe00021d27e: __free_pages_core (STB_GLOBAL)
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
void __free_pages_core(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81277940)
Location: mm/page_alloc.c:1417
Inline: False
Direct callers:
  - mm/page_alloc.c:memblock_free_pages
  - mm/memory_hotplug.c:generic_online_page
```
**Symbols:**

```
ffffffff81277940-ffffffff812779d6: __free_pages_core (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __free_pages_core(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81269850)
Location: mm/page_alloc.c:1417
Inline: False
Direct callers:
  - mm/page_alloc.c:memblock_free_pages
  - mm/memory_hotplug.c:generic_online_page
```
**Symbols:**

```
ffffffff81269850-ffffffff812698e6: __free_pages_core (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __free_pages_core(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812756e0)
Location: mm/page_alloc.c:1417
Inline: False
Direct callers:
  - mm/page_alloc.c:memblock_free_pages
  - mm/memory_hotplug.c:generic_online_page
```
**Symbols:**

```
ffffffff812756e0-ffffffff81275776: __free_pages_core (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __free_pages_core(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812852a0)
Location: mm/page_alloc.c:1417
Inline: False
Direct callers:
  - mm/page_alloc.c:memblock_free_pages
  - mm/memory_hotplug.c:generic_online_page
```
**Symbols:**

```
ffffffff812852a0-ffffffff81285336: __free_pages_core (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
