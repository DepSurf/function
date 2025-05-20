# Function: <code>memblock_phys_alloc_try_nid</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
phys_addr_t memblock_phys_alloc_try_nid(phys_addr_t size, phys_addr_t align, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828bdf92)
Location: mm/memblock.c:1339
Inline: False
```
**Symbols:**

```
ffffffff828bdf92-ffffffff828bdfc0: memblock_phys_alloc_try_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
phys_addr_t memblock_phys_alloc_try_nid(phys_addr_t size, phys_addr_t align, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828d722a)
Location: mm/memblock.c:1432
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
**Symbols:**

```
ffffffff828d722a-ffffffff828d7241: memblock_phys_alloc_try_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
phys_addr_t memblock_phys_alloc_try_nid(phys_addr_t size, phys_addr_t align, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828df69b)
Location: mm/memblock.c:1429
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
**Symbols:**

```
ffffffff828df69b-ffffffff828df6b2: memblock_phys_alloc_try_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
phys_addr_t memblock_phys_alloc_try_nid(phys_addr_t size, phys_addr_t align, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff82cfcbd4)
Location: mm/memblock.c:1443
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
**Symbols:**

```
ffffffff82cfcbd4-ffffffff82cfcbee: memblock_phys_alloc_try_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
phys_addr_t memblock_phys_alloc_try_nid(phys_addr_t size, phys_addr_t align, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff82fe9657)
Location: mm/memblock.c:1405
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
**Symbols:**

```
ffffffff82fe9657-ffffffff82fe9671: memblock_phys_alloc_try_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
phys_addr_t memblock_phys_alloc_try_nid(phys_addr_t size, phys_addr_t align, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff831f3d00)
Location: mm/memblock.c:1406
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
**Symbols:**

```
ffffffff831f3d00-ffffffff831f3d1a: memblock_phys_alloc_try_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
phys_addr_t memblock_phys_alloc_try_nid(phys_addr_t size, phys_addr_t align, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff832da046)
Location: mm/memblock.c:1441
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
**Symbols:**

```
ffffffff832da046-ffffffff832da060: memblock_phys_alloc_try_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
phys_addr_t memblock_phys_alloc_try_nid(phys_addr_t size, phys_addr_t align, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8348f08e)
Location: mm/memblock.c:1448
Inline: False
```
**Symbols:**

```
ffffffff8348f08e-ffffffff8348f0ba: memblock_phys_alloc_try_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
phys_addr_t memblock_phys_alloc_try_nid(phys_addr_t size, phys_addr_t align, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff83ec1520)
Location: mm/memblock.c:1466
Inline: False
```
**Symbols:**

```
ffffffff83ec1520-ffffffff83ec154c: memblock_phys_alloc_try_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
phys_addr_t memblock_phys_alloc_try_nid(phys_addr_t size, phys_addr_t align, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff836e6d30)
Location: mm/memblock.c:1488
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
**Symbols:**

```
ffffffff836e6d30-ffffffff836e6d5c: memblock_phys_alloc_try_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
phys_addr_t memblock_phys_alloc_try_nid(phys_addr_t size, phys_addr_t align, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff839192e0)
Location: mm/memblock.c:1546
Inline: False
```
**Symbols:**

```
ffffffff839192e0-ffffffff8391930c: memblock_phys_alloc_try_nid (STB_GLOBAL)
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
phys_addr_t memblock_phys_alloc_try_nid(phys_addr_t size, phys_addr_t align, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffff8000114586a4)
Location: mm/memblock.c:1429
Inline: False
Direct callers:
  - arch/arm64/mm/numa.c:numa_init
```
**Symbols:**

```
ffff8000114586a4-ffff8000114586f0: memblock_phys_alloc_try_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
phys_addr_t memblock_phys_alloc_try_nid(phys_addr_t size, phys_addr_t align, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (c1532604)
Location: mm/memblock.c:1429
Inline: False
```
**Symbols:**

```
c1532604-c1532638: memblock_phys_alloc_try_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
phys_addr_t memblock_phys_alloc_try_nid(phys_addr_t size, phys_addr_t align, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (c000000001381ed8)
Location: mm/memblock.c:1429
Inline: False
Direct callers:
  - arch/powerpc/mm/numa.c:initmem_init
```
**Symbols:**

```
c000000001381ed8-c000000001381ef8: memblock_phys_alloc_try_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
phys_addr_t memblock_phys_alloc_try_nid(phys_addr_t size, phys_addr_t align, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffe000016d8e)
Location: mm/memblock.c:1429
Inline: False
```
**Symbols:**

```
ffffffe000016d8e-ffffffe000016dcc: memblock_phys_alloc_try_nid (STB_GLOBAL)
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
phys_addr_t memblock_phys_alloc_try_nid(phys_addr_t size, phys_addr_t align, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828c854f)
Location: mm/memblock.c:1429
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
**Symbols:**

```
ffffffff828c854f-ffffffff828c8566: memblock_phys_alloc_try_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
phys_addr_t memblock_phys_alloc_try_nid(phys_addr_t size, phys_addr_t align, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828c0c74)
Location: mm/memblock.c:1429
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
**Symbols:**

```
ffffffff828c0c74-ffffffff828c0c8b: memblock_phys_alloc_try_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
phys_addr_t memblock_phys_alloc_try_nid(phys_addr_t size, phys_addr_t align, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828db2cf)
Location: mm/memblock.c:1429
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
**Symbols:**

```
ffffffff828db2cf-ffffffff828db2e6: memblock_phys_alloc_try_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
phys_addr_t memblock_phys_alloc_try_nid(phys_addr_t size, phys_addr_t align, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828e06f0)
Location: mm/memblock.c:1429
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
**Symbols:**

```
ffffffff828e06f0-ffffffff828e0707: memblock_phys_alloc_try_nid (STB_GLOBAL)
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
