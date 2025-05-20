# Function: <code>xen_remap_exchanged_ptes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void xen_remap_exchanged_ptes(long unsigned int vaddr, int order, long unsigned int *mfns, long unsigned int first_mfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101f380)
Location: arch/x86/xen/mmu.c:2539
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:xen_create_contiguous_region
  - arch/x86/xen/mmu.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff8101f380-ffffffff8101f5b0: xen_remap_exchanged_ptes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xen_remap_exchanged_ptes(long unsigned int vaddr, int order, long unsigned int *mfns, long unsigned int first_mfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101e7b0)
Location: arch/x86/xen/mmu.c:2529
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:xen_create_contiguous_region
  - arch/x86/xen/mmu.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff8101e7b0-ffffffff8101e9d5: xen_remap_exchanged_ptes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xen_remap_exchanged_ptes(long unsigned int vaddr, int order, long unsigned int *mfns, long unsigned int first_mfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101eea0)
Location: arch/x86/xen/mmu.c:2529
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:xen_create_contiguous_region
  - arch/x86/xen/mmu.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff8101eea0-ffffffff8101f0c5: xen_remap_exchanged_ptes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xen_remap_exchanged_ptes(long unsigned int vaddr, int order, long unsigned int *mfns, long unsigned int first_mfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81021a70)
Location: arch/x86/xen/mmu_pv.c:2530
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff81021a70-ffffffff81021cac: xen_remap_exchanged_ptes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xen_remap_exchanged_ptes(long unsigned int vaddr, int order, long unsigned int *mfns, long unsigned int first_mfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81022560)
Location: arch/x86/xen/mmu_pv.c:2471
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff81022560-ffffffff810227ab: xen_remap_exchanged_ptes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xen_remap_exchanged_ptes(long unsigned int vaddr, int order, long unsigned int *mfns, long unsigned int first_mfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81024d70)
Location: arch/x86/xen/mmu_pv.c:2507
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff81024d70-ffffffff81024fc5: xen_remap_exchanged_ptes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xen_remap_exchanged_ptes(long unsigned int vaddr, int order, long unsigned int *mfns, long unsigned int first_mfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81022f40)
Location: arch/x86/xen/mmu_pv.c:2515
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff81022f40-ffffffff81023195: xen_remap_exchanged_ptes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xen_remap_exchanged_ptes(long unsigned int vaddr, int order, long unsigned int *mfns, long unsigned int first_mfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81023b30)
Location: arch/x86/xen/mmu_pv.c:2503
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff81023b30-ffffffff81023d88: xen_remap_exchanged_ptes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xen_remap_exchanged_ptes(long unsigned int vaddr, int order, long unsigned int *mfns, long unsigned int first_mfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81024470)
Location: arch/x86/xen/mmu_pv.c:2503
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff81024470-ffffffff810246c8: xen_remap_exchanged_ptes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xen_remap_exchanged_ptes(long unsigned int vaddr, int order, long unsigned int *mfns, long unsigned int first_mfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81026d90)
Location: arch/x86/xen/mmu_pv.c:2503
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff81026d90-ffffffff81026f88: xen_remap_exchanged_ptes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xen_remap_exchanged_ptes(long unsigned int vaddr, int order, long unsigned int *mfns, long unsigned int first_mfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81027e70)
Location: arch/x86/xen/mmu_pv.c:2185
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff81027e70-ffffffff8102808d: xen_remap_exchanged_ptes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xen_remap_exchanged_ptes(long unsigned int vaddr, int order, long unsigned int *mfns, long unsigned int first_mfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81028860)
Location: arch/x86/xen/mmu_pv.c:2184
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff81028860-ffffffff810289d3: xen_remap_exchanged_ptes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void xen_remap_exchanged_ptes(long unsigned int vaddr, int order, long unsigned int *mfns, long unsigned int first_mfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/xen/mmu_pv.c:2187
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff8102cfa0-ffffffff8102d114: xen_remap_exchanged_ptes (STB_LOCAL)
ffffffff81c97877-ffffffff81c97890: xen_remap_exchanged_ptes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void xen_remap_exchanged_ptes(long unsigned int vaddr, int order, long unsigned int *mfns, long unsigned int first_mfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/xen/mmu_pv.c:2213
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff81031da0-ffffffff81031f32: xen_remap_exchanged_ptes (STB_LOCAL)
ffffffff81e46b9e-ffffffff81e46bbf: xen_remap_exchanged_ptes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void xen_remap_exchanged_ptes(long unsigned int vaddr, int order, long unsigned int *mfns, long unsigned int first_mfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/xen/mmu_pv.c:2213
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff81039680-ffffffff81039812: xen_remap_exchanged_ptes (STB_LOCAL)
ffffffff82051b4f-ffffffff82051b70: xen_remap_exchanged_ptes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xen_remap_exchanged_ptes(long unsigned int vaddr, int order, long unsigned int *mfns, long unsigned int first_mfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81039990)
Location: arch/x86/xen/mmu_pv.c:2221
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff81039990-ffffffff81039b20: xen_remap_exchanged_ptes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xen_remap_exchanged_ptes(long unsigned int vaddr, int order, long unsigned int *mfns, long unsigned int first_mfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8103fe40)
Location: arch/x86/xen/mmu_pv.c:2238
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff8103fe40-ffffffff8103ffd0: xen_remap_exchanged_ptes (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void xen_remap_exchanged_ptes(long unsigned int vaddr, int order, long unsigned int *mfns, long unsigned int first_mfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810245d0)
Location: arch/x86/xen/mmu_pv.c:2503
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff810245d0-ffffffff81024828: xen_remap_exchanged_ptes (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void xen_remap_exchanged_ptes(long unsigned int vaddr, int order, long unsigned int *mfns, long unsigned int first_mfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81024430)
Location: arch/x86/xen/mmu_pv.c:2503
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff81024430-ffffffff81024688: xen_remap_exchanged_ptes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xen_remap_exchanged_ptes(long unsigned int vaddr, int order, long unsigned int *mfns, long unsigned int first_mfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810249e0)
Location: arch/x86/xen/mmu_pv.c:2503
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff810249e0-ffffffff81024c83: xen_remap_exchanged_ptes (STB_LOCAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
