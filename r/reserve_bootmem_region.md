# Function: <code>reserve_bootmem_region</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void reserve_bootmem_region(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8181ce06)
Location: mm/page_alloc.c:934
Inline: False
Direct callers:
  - mm/nobootmem.c:free_all_bootmem
```
**Symbols:**

```
ffffffff8181ce06-ffffffff8181ce7e: reserve_bootmem_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void reserve_bootmem_region(phys_addr_t start, phys_addr_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81897068)
Location: mm/page_alloc.c:1202
Inline: False
Direct callers:
  - mm/nobootmem.c:free_all_bootmem
```
**Symbols:**

```
ffffffff81897068-ffffffff818970e2: reserve_bootmem_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void reserve_bootmem_region(phys_addr_t start, phys_addr_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff818cb7b4)
Location: mm/page_alloc.c:1218
Inline: False
Direct callers:
  - mm/nobootmem.c:free_all_bootmem
```
**Symbols:**

```
ffffffff818cb7b4-ffffffff818cb82d: reserve_bootmem_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void reserve_bootmem_region(phys_addr_t start, phys_addr_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81902d83)
Location: mm/page_alloc.c:1223
Inline: False
Direct callers:
  - mm/nobootmem.c:free_all_bootmem
```
**Symbols:**

```
ffffffff81902d83-ffffffff81902df5: reserve_bootmem_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void reserve_bootmem_region(phys_addr_t start, phys_addr_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8198ccc6)
Location: mm/page_alloc.c:1239
Inline: False
Direct callers:
  - mm/nobootmem.c:free_all_bootmem
```
**Symbols:**

```
ffffffff8198ccc6-ffffffff8198cd19: reserve_bootmem_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void reserve_bootmem_region(phys_addr_t start, phys_addr_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff819e9552)
Location: mm/page_alloc.c:1220
Inline: False
Direct callers:
  - mm/nobootmem.c:free_all_bootmem
```
**Symbols:**

```
ffffffff819e9552-ffffffff819e95a5: reserve_bootmem_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void reserve_bootmem_region(phys_addr_t start, phys_addr_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81a24f62)
Location: mm/page_alloc.c:1266
Inline: False
Direct callers:
  - mm/memblock.c:memblock_free_all
```
**Symbols:**

```
ffffffff81a24f62-ffffffff81a24fb5: reserve_bootmem_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void reserve_bootmem_region(phys_addr_t start, phys_addr_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81a95350)
Location: mm/page_alloc.c:1390
Inline: False
Direct callers:
  - mm/memblock.c:memblock_free_all
```
**Symbols:**

```
ffffffff81a95350-ffffffff81a953a3: reserve_bootmem_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void reserve_bootmem_region(phys_addr_t start, phys_addr_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81accc33)
Location: mm/page_alloc.c:1377
Inline: False
Direct callers:
  - mm/memblock.c:memblock_free_all
```
**Symbols:**

```
ffffffff81accc33-ffffffff81accc86: reserve_bootmem_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void reserve_bootmem_region(phys_addr_t start, phys_addr_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81bc5597)
Location: mm/page_alloc.c:1432
Inline: False
Direct callers:
  - mm/memblock.c:free_low_memory_core_early
```
**Symbols:**

```
ffffffff81bc5597-ffffffff81bc55ea: reserve_bootmem_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void reserve_bootmem_region(phys_addr_t start, phys_addr_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81c3e510)
Location: mm/page_alloc.c:1496
Inline: False
Direct callers:
  - mm/memblock.c:free_low_memory_core_early
```
**Symbols:**

```
ffffffff81c3e510-ffffffff81c3e563: reserve_bootmem_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void reserve_bootmem_region(phys_addr_t start, phys_addr_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81c30796)
Location: mm/page_alloc.c:1531
Inline: False
Direct callers:
  - mm/memblock.c:memblock_free_all
```
**Symbols:**

```
ffffffff81c30796-ffffffff81c307e9: reserve_bootmem_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void reserve_bootmem_region(phys_addr_t start, phys_addr_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81d4efbf)
Location: mm/page_alloc.c:1611
Inline: False
Direct callers:
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_free_all
```
**Symbols:**

```
ffffffff81d4efbf-ffffffff81d4f012: reserve_bootmem_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void reserve_bootmem_region(phys_addr_t start, phys_addr_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81f1eea9)
Location: mm/page_alloc.c:1594
Inline: False
Direct callers:
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_free_all
```
**Symbols:**

```
ffffffff81f1eea9-ffffffff81f1ef08: reserve_bootmem_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void reserve_bootmem_region(phys_addr_t start, phys_addr_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff820c7e20)
Location: mm/page_alloc.c:1670
Inline: False
Direct callers:
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_free_all
```
**Symbols:**

```
ffffffff820c7e20-ffffffff820c7efd: reserve_bootmem_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void reserve_bootmem_region(phys_addr_t start, phys_addr_t end, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mm_init.c (ffffffff8214be20)
Location: mm/mm_init.c:738
Inline: False
Direct callers:
  - mm/memblock.c:free_low_memory_core_early
  - mm/memblock.c:free_low_memory_core_early
```
**Symbols:**

```
ffffffff8214be20-ffffffff8214befd: reserve_bootmem_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void reserve_bootmem_region(phys_addr_t start, phys_addr_t end, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mm_init.c (ffffffff8222e950)
Location: mm/mm_init.c:748
Inline: False
Direct callers:
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:memblock_free_all
```
**Symbols:**

```
ffffffff8222e950-ffffffff8222ea84: reserve_bootmem_region (STB_GLOBAL)
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
void reserve_bootmem_region(phys_addr_t start, phys_addr_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010d9fbcc)
Location: mm/page_alloc.c:1377
Inline: False
Direct callers:
  - mm/memblock.c:memblock_free_all
```
**Symbols:**

```
ffff800010d9fbcc-ffff800010d9fc3c: reserve_bootmem_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void reserve_bootmem_region(phys_addr_t start, phys_addr_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c15bdb98)
Location: mm/page_alloc.c:1377
Inline: False
Direct callers:
  - mm/memblock.c:memblock_free_all
```
**Symbols:**

```
c15bdb98-c15bdc14: reserve_bootmem_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void reserve_bootmem_region(phys_addr_t start, phys_addr_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c000000000eec5e8)
Location: mm/page_alloc.c:1377
Inline: False
Direct callers:
  - mm/memblock.c:memblock_free_all
```
**Symbols:**

```
c000000000eec5e8-c000000000eec678: reserve_bootmem_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void reserve_bootmem_region(phys_addr_t start, phys_addr_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe000046fd0)
Location: mm/page_alloc.c:1377
Inline: False
Direct callers:
  - mm/memblock.c:memblock_free_all
```
**Symbols:**

```
ffffffe000046fd0-ffffffe000047038: reserve_bootmem_region (STB_GLOBAL)
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
void reserve_bootmem_region(phys_addr_t start, phys_addr_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81a6baa3)
Location: mm/page_alloc.c:1377
Inline: False
Direct callers:
  - mm/memblock.c:memblock_free_all
```
**Symbols:**

```
ffffffff81a6baa3-ffffffff81a6baf6: reserve_bootmem_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void reserve_bootmem_region(phys_addr_t start, phys_addr_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81a27fea)
Location: mm/page_alloc.c:1377
Inline: False
Direct callers:
  - mm/memblock.c:memblock_free_all
```
**Symbols:**

```
ffffffff81a27fea-ffffffff81a2803d: reserve_bootmem_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void reserve_bootmem_region(phys_addr_t start, phys_addr_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81ad7eb3)
Location: mm/page_alloc.c:1377
Inline: False
Direct callers:
  - mm/memblock.c:memblock_free_all
```
**Symbols:**

```
ffffffff81ad7eb3-ffffffff81ad7f06: reserve_bootmem_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void reserve_bootmem_region(phys_addr_t start, phys_addr_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81ae4373)
Location: mm/page_alloc.c:1377
Inline: False
Direct callers:
  - mm/memblock.c:memblock_free_all
```
**Symbols:**

```
ffffffff81ae4373-ffffffff81ae43c6: reserve_bootmem_region (STB_GLOBAL)
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
<b>Param type changed. </b>
<code>long unsigned int start</code> ➡️ <code>phys_addr_t start</code>
</li>
<li>
<b>Param type changed. </b>
<code>long unsigned int end</code> ➡️ <code>phys_addr_t end</code>
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
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int nid</code>
</li>
</ul>
</details>
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
