# Function: <code>memblock_alloc_internal</code>

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
void *memblock_alloc_internal(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828bdcd2)
Location: mm/memblock.c:1373
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_try_nid
  - mm/memblock.c:memblock_alloc_try_nid_nopanic
  - mm/memblock.c:memblock_alloc_try_nid_raw
```
**Symbols:**

```
ffffffff828bdcd2-ffffffff828bde1e: memblock_alloc_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *memblock_alloc_internal(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828d7184)
Location: mm/memblock.c:1457
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_try_nid
  - mm/memblock.c:memblock_alloc_try_nid_raw
```
**Symbols:**

```
ffffffff828d7184-ffffffff828d7216: memblock_alloc_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *memblock_alloc_internal(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828df5e6)
Location: mm/memblock.c:1454
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_try_nid
  - mm/memblock.c:memblock_alloc_try_nid_raw
```
**Symbols:**

```
ffffffff828df5e6-ffffffff828df687: memblock_alloc_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *memblock_alloc_internal(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid, bool exact_nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff82cfcb06)
Location: mm/memblock.c:1469
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_try_nid
  - mm/memblock.c:memblock_alloc_try_nid_raw
  - mm/memblock.c:memblock_alloc_exact_nid_raw
```
**Symbols:**

```
ffffffff82cfcb06-ffffffff82cfcbbd: memblock_alloc_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *memblock_alloc_internal(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid, bool exact_nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff82fe952f)
Location: mm/memblock.c:1431
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_try_nid
  - mm/memblock.c:memblock_alloc_try_nid_raw
  - mm/memblock.c:memblock_alloc_exact_nid_raw
```
**Symbols:**

```
ffffffff82fe952f-ffffffff82fe95e6: memblock_alloc_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *memblock_alloc_internal(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid, bool exact_nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff831f3bd9)
Location: mm/memblock.c:1432
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_try_nid
  - mm/memblock.c:memblock_alloc_try_nid_raw
  - mm/memblock.c:memblock_alloc_exact_nid_raw
```
**Symbols:**

```
ffffffff831f3bd9-ffffffff831f3c8f: memblock_alloc_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *memblock_alloc_internal(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid, bool exact_nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff832d9f1f)
Location: mm/memblock.c:1467
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_try_nid
  - mm/memblock.c:memblock_alloc_try_nid_raw
  - mm/memblock.c:memblock_alloc_exact_nid_raw
```
**Symbols:**

```
ffffffff832d9f1f-ffffffff832d9fd5: memblock_alloc_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *memblock_alloc_internal(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid, bool exact_nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8348ef42)
Location: mm/memblock.c:1474
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_try_nid
  - mm/memblock.c:memblock_alloc_try_nid_raw
  - mm/memblock.c:memblock_alloc_exact_nid_raw
```
**Symbols:**

```
ffffffff8348ef42-ffffffff8348f00d: memblock_alloc_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *memblock_alloc_internal(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid, bool exact_nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff83ec1360)
Location: mm/memblock.c:1492
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_try_nid
  - mm/memblock.c:memblock_alloc_try_nid_raw
  - mm/memblock.c:memblock_alloc_exact_nid_raw
```
**Symbols:**

```
ffffffff83ec1360-ffffffff83ec146c: memblock_alloc_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *memblock_alloc_internal(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid, bool exact_nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff836e6b70)
Location: mm/memblock.c:1514
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_try_nid
  - mm/memblock.c:memblock_alloc_try_nid_raw
  - mm/memblock.c:memblock_alloc_exact_nid_raw
```
**Symbols:**

```
ffffffff836e6b70-ffffffff836e6c7c: memblock_alloc_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *memblock_alloc_internal(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid, bool exact_nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff83919120)
Location: mm/memblock.c:1572
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_try_nid
  - mm/memblock.c:memblock_alloc_try_nid_raw
  - mm/memblock.c:memblock_alloc_exact_nid_raw
```
**Symbols:**

```
ffffffff83919120-ffffffff8391922c: memblock_alloc_internal (STB_LOCAL)
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
void *memblock_alloc_internal(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffff800011458588)
Location: mm/memblock.c:1454
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_try_nid
  - mm/memblock.c:memblock_alloc_try_nid_raw
```
**Symbols:**

```
ffff800011458588-ffff800011458654: memblock_alloc_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *memblock_alloc_internal(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (c15324f0)
Location: mm/memblock.c:1454
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_try_nid
  - mm/memblock.c:memblock_alloc_try_nid_raw
```
**Symbols:**

```
c15324f0-c15325d8: memblock_alloc_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *memblock_alloc_internal(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (c000000001381dc0)
Location: mm/memblock.c:1454
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_try_nid
  - mm/memblock.c:memblock_alloc_try_nid_raw
```
**Symbols:**

```
c000000001381dc0-c000000001381ec0: memblock_alloc_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *memblock_alloc_internal(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffe000016ca8)
Location: mm/memblock.c:1454
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_try_nid
  - mm/memblock.c:memblock_alloc_try_nid_raw
```
**Symbols:**

```
ffffffe000016ca8-ffffffe000016d4a: memblock_alloc_internal (STB_LOCAL)
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
void *memblock_alloc_internal(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828c849a)
Location: mm/memblock.c:1454
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_try_nid
  - mm/memblock.c:memblock_alloc_try_nid_raw
```
**Symbols:**

```
ffffffff828c849a-ffffffff828c853b: memblock_alloc_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *memblock_alloc_internal(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828c0bbf)
Location: mm/memblock.c:1454
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_try_nid
  - mm/memblock.c:memblock_alloc_try_nid_raw
```
**Symbols:**

```
ffffffff828c0bbf-ffffffff828c0c60: memblock_alloc_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *memblock_alloc_internal(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828db21a)
Location: mm/memblock.c:1454
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_try_nid
  - mm/memblock.c:memblock_alloc_try_nid_raw
```
**Symbols:**

```
ffffffff828db21a-ffffffff828db2bb: memblock_alloc_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *memblock_alloc_internal(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828e063b)
Location: mm/memblock.c:1454
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_try_nid
  - mm/memblock.c:memblock_alloc_try_nid_raw
```
**Symbols:**

```
ffffffff828e063b-ffffffff828e06dc: memblock_alloc_internal (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool exact_nid</code>
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
