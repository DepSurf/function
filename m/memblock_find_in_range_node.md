# Function: <code>memblock_find_in_range_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
phys_addr_t memblock_find_in_range_node(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, int nid, ulong flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8181e053)
Location: mm/memblock.c:203
Inline: False
Direct callers:
  - mm/nobootmem.c:__alloc_memory_core_early
  - mm/memblock.c:memblock_find_in_range
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_virt_alloc_internal
  - mm/memblock.c:memblock_virt_alloc_internal
```
**Symbols:**

```
ffffffff8181e053-ffffffff8181e2b6: memblock_find_in_range_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
phys_addr_t memblock_find_in_range_node(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, int nid, ulong flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81898503)
Location: mm/memblock.c:200
Inline: False
Direct callers:
  - mm/nobootmem.c:__alloc_memory_core_early
  - mm/memblock.c:memblock_virt_alloc_internal
  - mm/memblock.c:memblock_virt_alloc_internal
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_find_in_range
```
**Symbols:**

```
ffffffff81898503-ffffffff81898766: memblock_find_in_range_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
phys_addr_t memblock_find_in_range_node(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, int nid, ulong flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff818ccbab)
Location: mm/memblock.c:200
Inline: False
Direct callers:
  - mm/nobootmem.c:__alloc_memory_core_early
  - mm/memblock.c:memblock_virt_alloc_internal
  - mm/memblock.c:memblock_virt_alloc_internal
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_find_in_range
```
**Symbols:**

```
ffffffff818ccbab-ffffffff818cce0e: memblock_find_in_range_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
phys_addr_t memblock_find_in_range_node(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, int nid, ulong flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8190404a)
Location: mm/memblock.c:188
Inline: False
Direct callers:
  - mm/nobootmem.c:__alloc_memory_core_early
  - mm/memblock.c:memblock_virt_alloc_internal
  - mm/memblock.c:memblock_virt_alloc_internal
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_find_in_range
```
**Symbols:**

```
ffffffff8190404a-ffffffff81904284: memblock_find_in_range_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
phys_addr_t memblock_find_in_range_node(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, int nid, ulong flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8198e053)
Location: mm/memblock.c:188
Inline: False
Direct callers:
  - mm/nobootmem.c:__alloc_memory_core_early
  - mm/memblock.c:memblock_virt_alloc_internal
  - mm/memblock.c:memblock_virt_alloc_internal
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_find_in_range
```
**Symbols:**

```
ffffffff8198e053-ffffffff8198e28d: memblock_find_in_range_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
phys_addr_t memblock_find_in_range_node(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, int nid, ulong flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff819ea8dd)
Location: mm/memblock.c:190
Inline: False
Direct callers:
  - mm/nobootmem.c:__alloc_memory_core_early
  - mm/memblock.c:memblock_virt_alloc_internal
  - mm/memblock.c:memblock_virt_alloc_internal
  - mm/memblock.c:memblock_alloc_base_nid
  - mm/memblock.c:memblock_find_in_range
  - mm/memblock.c:memblock_alloc_range
```
**Symbols:**

```
ffffffff819ea8dd-ffffffff819eab10: memblock_find_in_range_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
phys_addr_t memblock_find_in_range_node(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, int nid, enum memblock_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a25b3b)
Location: mm/memblock.c:264
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_alloc_base_nid
  - mm/memblock.c:memblock_find_in_range
  - mm/memblock.c:memblock_alloc_range
```
**Symbols:**

```
ffffffff81a25b3b-ffffffff81a25d6f: memblock_find_in_range_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
phys_addr_t memblock_find_in_range_node(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, int nid, enum memblock_flags flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a96253)
Location: mm/memblock.c:271
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_find_in_range
```
**Symbols:**

```
ffffffff81a96253-ffffffff81a9648e: memblock_find_in_range_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
phys_addr_t memblock_find_in_range_node(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, int nid, enum memblock_flags flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81acdb2a)
Location: mm/memblock.c:271
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_find_in_range
```
**Symbols:**

```
ffffffff81acdb2a-ffffffff81acdd65: memblock_find_in_range_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
phys_addr_t memblock_find_in_range_node(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, int nid, enum memblock_flags flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81bc6507)
Location: mm/memblock.c:267
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_find_in_range
```
**Symbols:**

```
ffffffff81bc6507-ffffffff81bc674d: memblock_find_in_range_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
phys_addr_t memblock_find_in_range_node(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, int nid, enum memblock_flags flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81c3f282)
Location: mm/memblock.c:281
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_find_in_range
```
**Symbols:**

```
ffffffff81c3f282-ffffffff81c3f46f: memblock_find_in_range_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
phys_addr_t memblock_find_in_range_node(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, int nid, enum memblock_flags flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81c31354)
Location: mm/memblock.c:281
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_find_in_range
```
**Symbols:**

```
ffffffff81c31354-ffffffff81c31535: memblock_find_in_range_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
phys_addr_t memblock_find_in_range_node(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, int nid, enum memblock_flags flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81d4fcc4)
Location: mm/memblock.c:283
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_alloc_range_nid
```
**Symbols:**

```
ffffffff81d4fcc4-ffffffff81d4fece: memblock_find_in_range_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
phys_addr_t memblock_find_in_range_node(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, int nid, enum memblock_flags flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81f1fcdb)
Location: mm/memblock.c:283
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_alloc_range_nid
```
**Symbols:**

```
ffffffff81f1fcdb-ffffffff81f1ff0c: memblock_find_in_range_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
phys_addr_t memblock_find_in_range_node(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, int nid, enum memblock_flags flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff820c9070)
Location: mm/memblock.c:287
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_alloc_range_nid
```
**Symbols:**

```
ffffffff820c9070-ffffffff820c92f0: memblock_find_in_range_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
phys_addr_t memblock_find_in_range_node(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, int nid, enum memblock_flags flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8214d2d0)
Location: mm/memblock.c:287
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_alloc_range_nid
```
**Symbols:**

```
ffffffff8214d2d0-ffffffff8214d550: memblock_find_in_range_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
phys_addr_t memblock_find_in_range_node(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, int nid, enum memblock_flags flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8222fe80)
Location: mm/memblock.c:293
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_alloc_range_nid
```
**Symbols:**

```
ffffffff8222fe80-ffffffff82230100: memblock_find_in_range_node (STB_LOCAL)
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
phys_addr_t memblock_find_in_range_node(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, int nid, enum memblock_flags flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffff80001031bd30)
Location: mm/memblock.c:271
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_find_in_range
```
**Symbols:**

```
ffff80001031bd30-ffff80001031bfcc: memblock_find_in_range_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
phys_addr_t memblock_find_in_range_node(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, int nid, enum memblock_flags flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (c0535bfc)
Location: mm/memblock.c:271
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_find_in_range
```
**Symbols:**

```
c0535bfc-c0535f08: memblock_find_in_range_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
phys_addr_t memblock_find_in_range_node(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, int nid, enum memblock_flags flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (c0000000003ef890)
Location: mm/memblock.c:271
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_find_in_range
```
**Symbols:**

```
c0000000003ef890-c0000000003efc08: memblock_find_in_range_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
phys_addr_t memblock_find_in_range_node(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, int nid, enum memblock_flags flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffe000047ea4)
Location: mm/memblock.c:271
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_find_in_range
```
**Symbols:**

```
ffffffe000047ea4-ffffffe000048080: memblock_find_in_range_node (STB_LOCAL)
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
phys_addr_t memblock_find_in_range_node(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, int nid, enum memblock_flags flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a6c99a)
Location: mm/memblock.c:271
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_find_in_range
```
**Symbols:**

```
ffffffff81a6c99a-ffffffff81a6cbd5: memblock_find_in_range_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
phys_addr_t memblock_find_in_range_node(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, int nid, enum memblock_flags flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a28ee1)
Location: mm/memblock.c:271
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_find_in_range
```
**Symbols:**

```
ffffffff81a28ee1-ffffffff81a2911c: memblock_find_in_range_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
phys_addr_t memblock_find_in_range_node(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, int nid, enum memblock_flags flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ad8daa)
Location: mm/memblock.c:271
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_find_in_range
```
**Symbols:**

```
ffffffff81ad8daa-ffffffff81ad8fe5: memblock_find_in_range_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
phys_addr_t memblock_find_in_range_node(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, int nid, enum memblock_flags flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ae5260)
Location: mm/memblock.c:271
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_alloc_range_nid
  - mm/memblock.c:memblock_find_in_range
```
**Symbols:**

```
ffffffff81ae5260-ffffffff81ae549b: memblock_find_in_range_node (STB_LOCAL)
```
</details>
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
