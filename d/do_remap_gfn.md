# Function: <code>do_remap_gfn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_remap_gfn(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t *gfn, int nr, int *err_ptr, pgprot_t prot, unsigned int domid, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff810230a0)
Location: arch/x86/xen/mmu.c:2810
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:xen_remap_domain_gfn_range
```
**Symbols:**

```
ffffffff810230a0-ffffffff81023290: do_remap_gfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_remap_gfn(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t *gfn, int nr, int *err_ptr, pgprot_t prot, unsigned int domid, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff810223a0)
Location: arch/x86/xen/mmu.c:2800
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:xen_remap_domain_gfn_range
```
**Symbols:**

```
ffffffff810223a0-ffffffff810225a0: do_remap_gfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_remap_gfn(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t *gfn, int nr, int *err_ptr, pgprot_t prot, unsigned int domid, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81022af0)
Location: arch/x86/xen/mmu.c:2800
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:xen_remap_domain_gfn_range
```
**Symbols:**

```
ffffffff81022af0-ffffffff81022cf0: do_remap_gfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101a4f0)
Location: arch/x86/xen/mmu.c:94
Inline: True
Direct callers:
  - arch/x86/xen/mmu.c:xen_remap_domain_gfn_range
```
**Symbols:**

```
ffffffff8101a4f0-ffffffff8101a8d2: do_remap_gfn.isra.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101adc0)
Location: arch/x86/xen/mmu.c:94
Inline: True
Direct callers:
  - arch/x86/xen/mmu.c:xen_remap_domain_gfn_range
```
**Symbols:**

```
ffffffff8101adc0-ffffffff8101b1ae: do_remap_gfn.isra.3 (STB_LOCAL)
```
</details>
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
</ul>
