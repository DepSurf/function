# Function: <code>__free_pages_bootmem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __free_pages_bootmem(struct page *page, long unsigned int pfn, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81f870b0)
Location: mm/page_alloc.c:1079
Inline: False
Direct callers:
  - mm/nobootmem.c:__free_memory_core
  - mm/nobootmem.c:free_bootmem_late
  - mm/memblock.c:__memblock_free_late
```
**Symbols:**

```
ffffffff81f870b0-ffffffff81f8716b: __free_pages_bootmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __free_pages_bootmem(struct page *page, long unsigned int pfn, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81fb086b)
Location: mm/page_alloc.c:1309
Inline: False
Direct callers:
  - mm/nobootmem.c:__free_memory_core
  - mm/nobootmem.c:free_bootmem_late
  - mm/memblock.c:__memblock_free_late
```
**Symbols:**

```
ffffffff81fb086b-ffffffff81fb0923: __free_pages_bootmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __free_pages_bootmem(struct page *page, long unsigned int pfn, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81fecb7a)
Location: mm/page_alloc.c:1325
Inline: False
Direct callers:
  - mm/nobootmem.c:__free_memory_core
  - mm/nobootmem.c:free_bootmem_late
  - mm/memblock.c:__memblock_free_late
```
**Symbols:**

```
ffffffff81fecb7a-ffffffff81fecc32: __free_pages_bootmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __free_pages_bootmem(struct page *page, long unsigned int pfn, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff820ce7cb)
Location: mm/page_alloc.c:1332
Inline: False
Direct callers:
  - mm/nobootmem.c:free_all_bootmem
  - mm/nobootmem.c:free_bootmem_late
  - mm/memblock.c:__memblock_free_late
```
**Symbols:**

```
ffffffff820ce7cb-ffffffff820ce888: __free_pages_bootmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __free_pages_bootmem(struct page *page, long unsigned int pfn, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff826d71e6)
Location: mm/page_alloc.c:1348
Inline: False
Direct callers:
  - mm/nobootmem.c:free_all_bootmem
  - mm/nobootmem.c:free_bootmem_late
  - mm/memblock.c:__memblock_free_late
```
**Symbols:**

```
ffffffff826d71e6-ffffffff826d72a3: __free_pages_bootmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __free_pages_bootmem(struct page *page, long unsigned int pfn, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff82701620)
Location: mm/page_alloc.c:1329
Inline: False
Direct callers:
  - mm/nobootmem.c:free_all_bootmem
  - mm/nobootmem.c:free_bootmem_late
  - mm/memblock.c:__memblock_free_late
```
**Symbols:**

```
ffffffff82701620-ffffffff827016de: __free_pages_bootmem (STB_GLOBAL)
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
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
</ul>
