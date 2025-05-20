# Function: <code>remap_area_pfn_pte_fn</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int remap_area_pfn_pte_fn(pte_t *ptep, pgtable_t token, long unsigned int addr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101bc20)
Location: arch/x86/xen/mmu.c:73
Inline: False
```
**Symbols:**

```
ffffffff8101bc20-ffffffff8101bd54: remap_area_pfn_pte_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int remap_area_pfn_pte_fn(pte_t *ptep, pgtable_t token, long unsigned int addr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81021600)
Location: arch/x86/xen/mmu_pv.c:2705
Inline: False
```
**Symbols:**

```
ffffffff81021600-ffffffff81021734: remap_area_pfn_pte_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int remap_area_pfn_pte_fn(pte_t *ptep, long unsigned int addr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81023210)
Location: arch/x86/xen/mmu_pv.c:2693
Inline: False
```
**Symbols:**

```
ffffffff81023210-ffffffff8102333a: remap_area_pfn_pte_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int remap_area_pfn_pte_fn(pte_t *ptep, long unsigned int addr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81023b50)
Location: arch/x86/xen/mmu_pv.c:2691
Inline: False
```
**Symbols:**

```
ffffffff81023b50-ffffffff81023c7a: remap_area_pfn_pte_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int remap_area_pfn_pte_fn(pte_t *ptep, long unsigned int addr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81026260)
Location: arch/x86/xen/mmu_pv.c:2691
Inline: False
```
**Symbols:**

```
ffffffff81026260-ffffffff81026388: remap_area_pfn_pte_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int remap_area_pfn_pte_fn(pte_t *ptep, long unsigned int addr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81026970)
Location: arch/x86/xen/mmu_pv.c:2373
Inline: False
```
**Symbols:**

```
ffffffff81026970-ffffffff81026a98: remap_area_pfn_pte_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int remap_area_pfn_pte_fn(pte_t *ptep, long unsigned int addr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810285e0)
Location: arch/x86/xen/mmu_pv.c:2372
Inline: False
```
**Symbols:**

```
ffffffff810285e0-ffffffff81028717: remap_area_pfn_pte_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int remap_area_pfn_pte_fn(pte_t *ptep, long unsigned int addr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/xen/mmu_pv.c:2375
Inline: False
```
**Symbols:**

```
ffffffff8102ccf0-ffffffff8102ce5a: remap_area_pfn_pte_fn (STB_LOCAL)
ffffffff81c97844-ffffffff81c97877: remap_area_pfn_pte_fn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int remap_area_pfn_pte_fn(pte_t *ptep, long unsigned int addr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/xen/mmu_pv.c:2401
Inline: False
```
**Symbols:**

```
ffffffff81031c40-ffffffff81031d99: remap_area_pfn_pte_fn (STB_LOCAL)
ffffffff81e46b6b-ffffffff81e46b9e: remap_area_pfn_pte_fn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int remap_area_pfn_pte_fn(pte_t *ptep, long unsigned int addr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/xen/mmu_pv.c:2401
Inline: False
```
**Symbols:**

```
ffffffff81039510-ffffffff81039669: remap_area_pfn_pte_fn (STB_LOCAL)
ffffffff82051b1c-ffffffff82051b4f: remap_area_pfn_pte_fn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int remap_area_pfn_pte_fn(pte_t *ptep, long unsigned int addr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/xen/mmu_pv.c:2409
Inline: False
```
**Symbols:**

```
ffffffff81039450-ffffffff810395a5: remap_area_pfn_pte_fn (STB_LOCAL)
ffffffff820d0007-ffffffff820d0039: remap_area_pfn_pte_fn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int remap_area_pfn_pte_fn(pte_t *ptep, long unsigned int addr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/xen/mmu_pv.c:2420
Inline: False
```
**Symbols:**

```
ffffffff8103f900-ffffffff8103fa55: remap_area_pfn_pte_fn (STB_LOCAL)
ffffffff821aa974-ffffffff821aa9a6: remap_area_pfn_pte_fn.cold (STB_LOCAL)
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
int remap_area_pfn_pte_fn(pte_t *ptep, long unsigned int addr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81023cb0)
Location: arch/x86/xen/mmu_pv.c:2691
Inline: False
```
**Symbols:**

```
ffffffff81023cb0-ffffffff81023dda: remap_area_pfn_pte_fn (STB_LOCAL)
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
int remap_area_pfn_pte_fn(pte_t *ptep, long unsigned int addr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81023b10)
Location: arch/x86/xen/mmu_pv.c:2691
Inline: False
```
**Symbols:**

```
ffffffff81023b10-ffffffff81023c3a: remap_area_pfn_pte_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int remap_area_pfn_pte_fn(pte_t *ptep, long unsigned int addr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81023fa0)
Location: arch/x86/xen/mmu_pv.c:2691
Inline: False
```
**Symbols:**

```
ffffffff81023fa0-ffffffff810240ca: remap_area_pfn_pte_fn (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>pgtable_t token</code>
</li>
<li>
<b>Param reordered. </b>
<code>ptep, token, addr, data</code> ➡️ <code>ptep, addr, data</code>
</li>
</ul>
</details>
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
