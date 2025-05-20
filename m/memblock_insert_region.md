# Function: <code>memblock_insert_region</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void memblock_insert_region(struct memblock_type *type, int idx, phys_addr_t base, phys_addr_t size, int nid, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8181d90e)
Location: mm/memblock.c:491
Inline: True
Direct callers:
  - mm/memblock.c:memblock_add_range
  - mm/memblock.c:memblock_add_range
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_isolate_range
```
**Symbols:**

```
ffffffff8181d90e-ffffffff8181d982: memblock_insert_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void memblock_insert_region(struct memblock_type *type, int idx, phys_addr_t base, phys_addr_t size, int nid, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81897d3a)
Location: mm/memblock.c:487
Inline: True
Direct callers:
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_add_range
  - mm/memblock.c:memblock_add_range
```
**Symbols:**

```
ffffffff81897d3a-ffffffff81897dae: memblock_insert_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void memblock_insert_region(struct memblock_type *type, int idx, phys_addr_t base, phys_addr_t size, int nid, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff818cc3d9)
Location: mm/memblock.c:487
Inline: True
Direct callers:
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_add_range
  - mm/memblock.c:memblock_add_range
```
**Symbols:**

```
ffffffff818cc3d9-ffffffff818cc44d: memblock_insert_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void memblock_insert_region(struct memblock_type *type, int idx, phys_addr_t base, phys_addr_t size, int nid, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81903998)
Location: mm/memblock.c:471
Inline: False
Direct callers:
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_add_range
  - mm/memblock.c:memblock_add_range
```
**Symbols:**

```
ffffffff81903998-ffffffff81903a0c: memblock_insert_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void memblock_insert_region(struct memblock_type *type, int idx, phys_addr_t base, phys_addr_t size, int nid, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8198d9a3)
Location: mm/memblock.c:471
Inline: False
Direct callers:
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_add_range
  - mm/memblock.c:memblock_add_range
```
**Symbols:**

```
ffffffff8198d9a3-ffffffff8198da17: memblock_insert_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void memblock_insert_region(struct memblock_type *type, int idx, phys_addr_t base, phys_addr_t size, int nid, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff819ea25d)
Location: mm/memblock.c:474
Inline: False
Direct callers:
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_add_range
  - mm/memblock.c:memblock_add_range
```
**Symbols:**

```
ffffffff819ea25d-ffffffff819ea2d1: memblock_insert_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void memblock_insert_region(struct memblock_type *type, int idx, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a254d9)
Location: mm/memblock.c:551
Inline: False
Direct callers:
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_add_range
  - mm/memblock.c:memblock_add_range
```
**Symbols:**

```
ffffffff81a254d9-ffffffff81a25547: memblock_insert_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void memblock_insert_region(struct memblock_type *type, int idx, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a95c14)
Location: mm/memblock.c:548
Inline: False
Direct callers:
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_add_range
  - mm/memblock.c:memblock_add_range
```
**Symbols:**

```
ffffffff81a95c14-ffffffff81a95c87: memblock_insert_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void memblock_insert_region(struct memblock_type *type, int idx, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81acd4eb)
Location: mm/memblock.c:548
Inline: False
Direct callers:
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_add_range
  - mm/memblock.c:memblock_add_range
```
**Symbols:**

```
ffffffff81acd4eb-ffffffff81acd55e: memblock_insert_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void memblock_insert_region(struct memblock_type *type, int idx, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81bc5f20)
Location: mm/memblock.c:544
Inline: False
Direct callers:
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_isolate_range
```
**Symbols:**

```
ffffffff81bc5f20-ffffffff81bc5f93: memblock_insert_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void memblock_insert_region(struct memblock_type *type, int idx, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81c3ee80)
Location: mm/memblock.c:531
Inline: False
Direct callers:
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_isolate_range
```
**Symbols:**

```
ffffffff81c3ee80-ffffffff81c3eef3: memblock_insert_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void memblock_insert_region(struct memblock_type *type, int idx, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81c30f4f)
Location: mm/memblock.c:531
Inline: False
Direct callers:
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_isolate_range
```
**Symbols:**

```
ffffffff81c30f4f-ffffffff81c30fc2: memblock_insert_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void memblock_insert_region(struct memblock_type *type, int idx, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81d4f86f)
Location: mm/memblock.c:539
Inline: False
Direct callers:
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_isolate_range
```
**Symbols:**

```
ffffffff81d4f86f-ffffffff81d4f8e2: memblock_insert_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void memblock_insert_region(struct memblock_type *type, int idx, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81f1f77e)
Location: mm/memblock.c:539
Inline: False
Direct callers:
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_add_range
  - mm/memblock.c:memblock_add_range
```
**Symbols:**

```
ffffffff81f1f77e-ffffffff81f1f808: memblock_insert_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void memblock_insert_region(struct memblock_type *type, int idx, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff820c8ad0)
Location: mm/memblock.c:543
Inline: False
Direct callers:
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_add_range
  - mm/memblock.c:memblock_add_range
  - mm/memblock.c:memblock_add_range
```
**Symbols:**

```
ffffffff820c8ad0-ffffffff820c8b65: memblock_insert_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void memblock_insert_region(struct memblock_type *type, int idx, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8214cd50)
Location: mm/memblock.c:548
Inline: False
Direct callers:
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_add_range
  - mm/memblock.c:memblock_add_range
  - mm/memblock.c:memblock_add_range
```
**Symbols:**

```
ffffffff8214cd50-ffffffff8214cde5: memblock_insert_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void memblock_insert_region(struct memblock_type *type, int idx, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8222f860)
Location: mm/memblock.c:554
Inline: False
Direct callers:
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_add_range
  - mm/memblock.c:memblock_add_range
  - mm/memblock.c:memblock_add_range
```
**Symbols:**

```
ffffffff8222f860-ffffffff8222f8f5: memblock_insert_region (STB_LOCAL)
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
void memblock_insert_region(struct memblock_type *type, int idx, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffff80001031b438)
Location: mm/memblock.c:548
Inline: False
Direct callers:
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_add_range
  - mm/memblock.c:memblock_add_range
  - mm/memblock.c:memblock_add_range
```
**Symbols:**

```
ffff80001031b438-ffff80001031b4e8: memblock_insert_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memblock.c (c0535630)
Location: mm/memblock.c:548
Inline: True
Direct callers:
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_add_range
  - mm/memblock.c:memblock_add_range
  - mm/memblock.c:memblock_add_range
```
**Symbols:**

```
c0535630-c05356b8: memblock_insert_region.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void memblock_insert_region(struct memblock_type *type, int idx, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (c0000000003eece0)
Location: mm/memblock.c:548
Inline: False
Direct callers:
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_add_range
  - mm/memblock.c:memblock_add_range
  - mm/memblock.c:memblock_add_range
```
**Symbols:**

```
c0000000003eece0-c0000000003eedc4: memblock_insert_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void memblock_insert_region(struct memblock_type *type, int idx, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffe000047888)
Location: mm/memblock.c:548
Inline: False
Direct callers:
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_add_range
  - mm/memblock.c:memblock_add_range
```
**Symbols:**

```
ffffffe000047888-ffffffe000047904: memblock_insert_region (STB_LOCAL)
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
void memblock_insert_region(struct memblock_type *type, int idx, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a6c35b)
Location: mm/memblock.c:548
Inline: False
Direct callers:
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_add_range
  - mm/memblock.c:memblock_add_range
```
**Symbols:**

```
ffffffff81a6c35b-ffffffff81a6c3ce: memblock_insert_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void memblock_insert_region(struct memblock_type *type, int idx, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a288a2)
Location: mm/memblock.c:548
Inline: False
Direct callers:
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_add_range
  - mm/memblock.c:memblock_add_range
```
**Symbols:**

```
ffffffff81a288a2-ffffffff81a28915: memblock_insert_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void memblock_insert_region(struct memblock_type *type, int idx, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ad876b)
Location: mm/memblock.c:548
Inline: False
Direct callers:
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_add_range
  - mm/memblock.c:memblock_add_range
```
**Symbols:**

```
ffffffff81ad876b-ffffffff81ad87de: memblock_insert_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void memblock_insert_region(struct memblock_type *type, int idx, phys_addr_t base, phys_addr_t size, int nid, enum memblock_flags flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ae4c21)
Location: mm/memblock.c:548
Inline: False
Direct callers:
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_isolate_range
  - mm/memblock.c:memblock_add_range
  - mm/memblock.c:memblock_add_range
```
**Symbols:**

```
ffffffff81ae4c21-ffffffff81ae4c94: memblock_insert_region (STB_LOCAL)
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
<code>long unsigned int flags</code> ➡️ <code>enum memblock_flags flags</code>
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
