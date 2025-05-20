# Function: <code>memblock_alloc_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_range(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, ulong flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81f8b171)
Location: mm/memblock.c:1160
Inline: False
Direct callers:
  - mm/cma.c:cma_declare_contiguous
  - mm/cma.c:cma_declare_contiguous
```
**Symbols:**

```
ffffffff81f8b171-ffffffff81f8b183: memblock_alloc_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_range(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, ulong flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81fb4db8)
Location: mm/memblock.c:1161
Inline: False
Direct callers:
  - mm/cma.c:cma_declare_contiguous
  - mm/cma.c:cma_declare_contiguous
```
**Symbols:**

```
ffffffff81fb4db8-ffffffff81fb4dca: memblock_alloc_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_range(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, ulong flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ff179c)
Location: mm/memblock.c:1161
Inline: False
Direct callers:
  - mm/cma.c:cma_declare_contiguous
  - mm/cma.c:cma_declare_contiguous
```
**Symbols:**

```
ffffffff81ff179c-ffffffff81ff17ae: memblock_alloc_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_range(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, ulong flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff820d3bf3)
Location: mm/memblock.c:1185
Inline: False
Direct callers:
  - mm/cma.c:cma_declare_contiguous
  - mm/cma.c:cma_declare_contiguous
```
**Symbols:**

```
ffffffff820d3bf3-ffffffff820d3c0a: memblock_alloc_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_range(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, ulong flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff826dc613)
Location: mm/memblock.c:1157
Inline: False
Direct callers:
  - mm/cma.c:cma_declare_contiguous
  - mm/cma.c:cma_declare_contiguous
```
**Symbols:**

```
ffffffff826dc613-ffffffff826dc62a: memblock_alloc_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_range(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, ulong flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff82706adb)
Location: mm/memblock.c:1165
Inline: False
Direct callers:
  - mm/cma.c:cma_declare_contiguous
  - mm/cma.c:cma_declare_contiguous
```
**Symbols:**

```
ffffffff82706adb-ffffffff82706b26: memblock_alloc_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_range(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, enum memblock_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828bde1e)
Location: mm/memblock.c:1284
Inline: False
Direct callers:
  - mm/cma.c:cma_declare_contiguous
  - mm/cma.c:cma_declare_contiguous
```
**Symbols:**

```
ffffffff828bde1e-ffffffff828bde85: memblock_alloc_range (STB_GLOBAL)
```
</details>
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
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>ulong flags</code> ➡️ <code>enum memblock_flags flags</code>
</li>
</ul>
</details>
</li>
</ul>
