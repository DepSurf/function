# Function: <code>xen_zap_pfn_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void xen_zap_pfn_range(long unsigned int vaddr, unsigned int order, long unsigned int *in_frames, long unsigned int *out_frames);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101f5b0)
Location: arch/x86/xen/mmu.c:2511
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff8101f5b0-ffffffff8101f887: xen_zap_pfn_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xen_zap_pfn_range(long unsigned int vaddr, unsigned int order, long unsigned int *in_frames, long unsigned int *out_frames);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101e9e0)
Location: arch/x86/xen/mmu.c:2501
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff8101e9e0-ffffffff8101ecb0: xen_zap_pfn_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xen_zap_pfn_range(long unsigned int vaddr, unsigned int order, long unsigned int *in_frames, long unsigned int *out_frames);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101f0d0)
Location: arch/x86/xen/mmu.c:2501
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff8101f0d0-ffffffff8101f3a0: xen_zap_pfn_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xen_zap_pfn_range(long unsigned int vaddr, unsigned int order, long unsigned int *in_frames, long unsigned int *out_frames);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810220e0)
Location: arch/x86/xen/mmu_pv.c:2502
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff810220e0-ffffffff810223b0: xen_zap_pfn_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xen_zap_pfn_range(long unsigned int vaddr, unsigned int order, long unsigned int *in_frames, long unsigned int *out_frames);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81022bb0)
Location: arch/x86/xen/mmu_pv.c:2443
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff81022bb0-ffffffff81022e88: xen_zap_pfn_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xen_zap_pfn_range(long unsigned int vaddr, unsigned int order, long unsigned int *in_frames, long unsigned int *out_frames);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81024fd0)
Location: arch/x86/xen/mmu_pv.c:2479
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff81024fd0-ffffffff810252e0: xen_zap_pfn_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xen_zap_pfn_range(long unsigned int vaddr, unsigned int order, long unsigned int *in_frames, long unsigned int *out_frames);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810231a0)
Location: arch/x86/xen/mmu_pv.c:2487
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff810231a0-ffffffff810234b0: xen_zap_pfn_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xen_zap_pfn_range(long unsigned int vaddr, unsigned int order, long unsigned int *in_frames, long unsigned int *out_frames);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81023d90)
Location: arch/x86/xen/mmu_pv.c:2475
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff81023d90-ffffffff8102409e: xen_zap_pfn_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xen_zap_pfn_range(long unsigned int vaddr, unsigned int order, long unsigned int *in_frames, long unsigned int *out_frames);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810246d0)
Location: arch/x86/xen/mmu_pv.c:2475
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff810246d0-ffffffff810249de: xen_zap_pfn_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xen_zap_pfn_range(long unsigned int vaddr, unsigned int order, long unsigned int *in_frames, long unsigned int *out_frames);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81027360)
Location: arch/x86/xen/mmu_pv.c:2475
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff81027360-ffffffff810275c7: xen_zap_pfn_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xen_zap_pfn_range(long unsigned int vaddr, unsigned int order, long unsigned int *in_frames, long unsigned int *out_frames);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81028470)
Location: arch/x86/xen/mmu_pv.c:2157
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff81028470-ffffffff8102873a: xen_zap_pfn_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xen_zap_pfn_range(long unsigned int vaddr, unsigned int order, long unsigned int *in_frames, long unsigned int *out_frames);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810289e0)
Location: arch/x86/xen/mmu_pv.c:2156
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff810289e0-ffffffff81028c16: xen_zap_pfn_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void xen_zap_pfn_range(long unsigned int vaddr, unsigned int order, long unsigned int *in_frames, long unsigned int *out_frames);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/xen/mmu_pv.c:2159
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff8102d120-ffffffff8102d35c: xen_zap_pfn_range (STB_LOCAL)
ffffffff81c97890-ffffffff81c978aa: xen_zap_pfn_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void xen_zap_pfn_range(long unsigned int vaddr, unsigned int order, long unsigned int *in_frames, long unsigned int *out_frames);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/xen/mmu_pv.c:2185
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff81031f40-ffffffff810321a9: xen_zap_pfn_range (STB_LOCAL)
ffffffff81e46bbf-ffffffff81e46bd9: xen_zap_pfn_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void xen_zap_pfn_range(long unsigned int vaddr, unsigned int order, long unsigned int *in_frames, long unsigned int *out_frames);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/xen/mmu_pv.c:2185
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff81039830-ffffffff81039a99: xen_zap_pfn_range (STB_LOCAL)
ffffffff82051b70-ffffffff82051b8a: xen_zap_pfn_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void xen_zap_pfn_range(long unsigned int vaddr, unsigned int order, long unsigned int *in_frames, long unsigned int *out_frames);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/xen/mmu_pv.c:2193
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff81039b30-ffffffff81039d99: xen_zap_pfn_range (STB_LOCAL)
ffffffff820d016d-ffffffff820d0187: xen_zap_pfn_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void xen_zap_pfn_range(long unsigned int vaddr, unsigned int order, long unsigned int *in_frames, long unsigned int *out_frames);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/xen/mmu_pv.c:2210
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff8103ffe0-ffffffff81040255: xen_zap_pfn_range (STB_LOCAL)
ffffffff821aaada-ffffffff821aaaf4: xen_zap_pfn_range.cold (STB_LOCAL)
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
void xen_zap_pfn_range(long unsigned int vaddr, unsigned int order, long unsigned int *in_frames, long unsigned int *out_frames);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81024830)
Location: arch/x86/xen/mmu_pv.c:2475
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff81024830-ffffffff81024b3e: xen_zap_pfn_range (STB_LOCAL)
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
void xen_zap_pfn_range(long unsigned int vaddr, unsigned int order, long unsigned int *in_frames, long unsigned int *out_frames);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81024690)
Location: arch/x86/xen/mmu_pv.c:2475
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff81024690-ffffffff8102499e: xen_zap_pfn_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xen_zap_pfn_range(long unsigned int vaddr, unsigned int order, long unsigned int *in_frames, long unsigned int *out_frames);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81024c90)
Location: arch/x86/xen/mmu_pv.c:2475
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
```
**Symbols:**

```
ffffffff81024c90-ffffffff81024fe9: xen_zap_pfn_range (STB_LOCAL)
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
