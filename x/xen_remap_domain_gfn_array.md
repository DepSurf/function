# Function: <code>xen_remap_domain_gfn_array</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int xen_remap_domain_gfn_array(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t *gfn, int nr, int *err_ptr, pgprot_t prot, unsigned int domid, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff810232c0)
Location: arch/x86/xen/mmu.c:2905
Inline: True
```
**Symbols:**

```
ffffffff810232c0-ffffffff810232ea: xen_remap_domain_gfn_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int xen_remap_domain_gfn_array(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t *gfn, int nr, int *err_ptr, pgprot_t prot, unsigned int domid, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff810225d0)
Location: arch/x86/xen/mmu.c:2895
Inline: True
```
**Symbols:**

```
ffffffff810225d0-ffffffff810225fa: xen_remap_domain_gfn_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int xen_remap_domain_gfn_array(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t *gfn, int nr, int *err_ptr, pgprot_t prot, unsigned int domid, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81022d20)
Location: arch/x86/xen/mmu.c:2895
Inline: True
```
**Symbols:**

```
ffffffff81022d20-ffffffff81022d4a: xen_remap_domain_gfn_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int xen_remap_domain_gfn_array(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t *gfn, int nr, int *err_ptr, pgprot_t prot, unsigned int domid, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101a920)
Location: arch/x86/xen/mmu.c:179
Inline: True
```
**Symbols:**

```
ffffffff8101a920-ffffffff8101a955: xen_remap_domain_gfn_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int xen_remap_domain_gfn_array(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t *gfn, int nr, int *err_ptr, pgprot_t prot, unsigned int domid, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101b200)
Location: arch/x86/xen/mmu.c:182
Inline: True
```
**Symbols:**

```
ffffffff8101b200-ffffffff8101b251: xen_remap_domain_gfn_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int xen_remap_domain_gfn_array(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t *gfn, int nr, int *err_ptr, pgprot_t prot, unsigned int domid, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101bb70)
Location: arch/x86/xen/mmu.c:191
Inline: True
```
**Symbols:**

```
ffffffff8101bb70-ffffffff8101bba8: xen_remap_domain_gfn_array (STB_GLOBAL)
```
</details>
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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
