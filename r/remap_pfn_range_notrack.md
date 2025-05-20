# Function: <code>remap_pfn_range_notrack</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int remap_pfn_range_notrack(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a38c0)
Location: mm/memory.c:2280
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range
```
**Symbols:**

```
ffffffff812a38c0-ffffffff812a3df0: remap_pfn_range_notrack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int remap_pfn_range_notrack(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:2375
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range
```
**Symbols:**

```
ffffffff81cbc577-ffffffff81cbc5df: remap_pfn_range_notrack.cold (STB_LOCAL)
ffffffff812e4bc0-ffffffff812e510c: remap_pfn_range_notrack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int remap_pfn_range_notrack(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:2468
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range
```
**Symbols:**

```
ffffffff81e6e0de-ffffffff81e6e14f: remap_pfn_range_notrack.cold (STB_LOCAL)
ffffffff813464f0-ffffffff81346aaa: remap_pfn_range_notrack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int remap_pfn_range_notrack(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:2439
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range
```
**Symbols:**

```
ffffffff820640e0-ffffffff82064150: remap_pfn_range_notrack.cold (STB_LOCAL)
ffffffff813be8d0-ffffffff813bee85: remap_pfn_range_notrack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int remap_pfn_range_notrack(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:2439
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range
```
**Symbols:**

```
ffffffff820e37cd-ffffffff820e384e: remap_pfn_range_notrack.cold (STB_LOCAL)
ffffffff813f3930-ffffffff813f3af4: remap_pfn_range_notrack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int remap_pfn_range_notrack(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:2462
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range
```
**Symbols:**

```
ffffffff821c0216-ffffffff821c0283: remap_pfn_range_notrack.cold (STB_LOCAL)
ffffffff8141e210-ffffffff8141e78d: remap_pfn_range_notrack (STB_GLOBAL)
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
