# Function: <code>xen_flush_tlb_all</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void xen_flush_tlb_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81022ee0)
Location: arch/x86/xen/mmu.c:1314
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:do_remap_gfn
  - arch/x86/xen/mmu.c:do_remap_gfn
```
**Symbols:**

```
ffffffff81022ee0-ffffffff8102309f: xen_flush_tlb_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xen_flush_tlb_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81022200)
Location: arch/x86/xen/mmu.c:1315
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:do_remap_gfn
  - arch/x86/xen/mmu.c:do_remap_gfn
```
**Symbols:**

```
ffffffff81022200-ffffffff8102239f: xen_flush_tlb_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xen_flush_tlb_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81022950)
Location: arch/x86/xen/mmu.c:1315
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:do_remap_gfn
  - arch/x86/xen/mmu.c:do_remap_gfn
```
**Symbols:**

```
ffffffff81022950-ffffffff81022aef: xen_flush_tlb_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101a6cb)
Location: arch/x86/xen/mmu.c:45
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101af9b)
Location: arch/x86/xen/mmu.c:45
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xen_flush_tlb_all();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101b7d0)
Location: arch/x86/xen/mmu.c:45
Inline: False
```
**Symbols:**

```
ffffffff8101b7d0-ffffffff8101b945: xen_flush_tlb_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xen_flush_tlb_all();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810224b0)
Location: arch/x86/xen/mmu_pv.c:2677
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
```
**Symbols:**

```
ffffffff810224b0-ffffffff81022625: xen_flush_tlb_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xen_flush_tlb_all();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81023460)
Location: arch/x86/xen/mmu_pv.c:2665
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
```
**Symbols:**

```
ffffffff81023460-ffffffff810235d1: xen_flush_tlb_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xen_flush_tlb_all();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81023f20)
Location: arch/x86/xen/mmu_pv.c:2663
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
```
**Symbols:**

```
ffffffff81023f20-ffffffff81024091: xen_flush_tlb_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xen_flush_tlb_all();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810268f0)
Location: arch/x86/xen/mmu_pv.c:2663
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
```
**Symbols:**

```
ffffffff810268f0-ffffffff810269f9: xen_flush_tlb_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xen_flush_tlb_all();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810270e0)
Location: arch/x86/xen/mmu_pv.c:2345
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
```
**Symbols:**

```
ffffffff810270e0-ffffffff81027210: xen_flush_tlb_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xen_flush_tlb_all();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81029050)
Location: arch/x86/xen/mmu_pv.c:2344
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
```
**Symbols:**

```
ffffffff81029050-ffffffff810290de: xen_flush_tlb_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xen_flush_tlb_all();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8102d7a0)
Location: arch/x86/xen/mmu_pv.c:2347
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
```
**Symbols:**

```
ffffffff8102d7a0-ffffffff8102d82b: xen_flush_tlb_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xen_flush_tlb_all();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81032570)
Location: arch/x86/xen/mmu_pv.c:2373
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
```
**Symbols:**

```
ffffffff81032570-ffffffff81032635: xen_flush_tlb_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xen_flush_tlb_all();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81039f70)
Location: arch/x86/xen/mmu_pv.c:2373
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
```
**Symbols:**

```
ffffffff81039f70-ffffffff8103a035: xen_flush_tlb_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xen_flush_tlb_all();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8103a000)
Location: arch/x86/xen/mmu_pv.c:2381
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
```
**Symbols:**

```
ffffffff8103a000-ffffffff8103a0c5: xen_flush_tlb_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xen_flush_tlb_all();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810404c0)
Location: arch/x86/xen/mmu_pv.c:2392
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
```
**Symbols:**

```
ffffffff810404c0-ffffffff81040585: xen_flush_tlb_all (STB_LOCAL)
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
void xen_flush_tlb_all();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81024080)
Location: arch/x86/xen/mmu_pv.c:2663
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
```
**Symbols:**

```
ffffffff81024080-ffffffff810241f1: xen_flush_tlb_all (STB_LOCAL)
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
void xen_flush_tlb_all();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81023ee0)
Location: arch/x86/xen/mmu_pv.c:2663
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
```
**Symbols:**

```
ffffffff81023ee0-ffffffff81024051: xen_flush_tlb_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xen_flush_tlb_all();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810243d0)
Location: arch/x86/xen/mmu_pv.c:2663
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
  - arch/x86/xen/mmu_pv.c:xen_remap_pfn
```
**Symbols:**

```
ffffffff810243d0-ffffffff810245ab: xen_flush_tlb_all (STB_LOCAL)
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
