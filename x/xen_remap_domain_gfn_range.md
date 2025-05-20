# Function: <code>xen_remap_domain_gfn_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int xen_remap_domain_gfn_range(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t gfn, int nr, pgprot_t prot, unsigned int domid, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81023290)
Location: arch/x86/xen/mmu.c:2895
Inline: False
```
**Symbols:**

```
ffffffff81023290-ffffffff810232bf: xen_remap_domain_gfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xen_remap_domain_gfn_range(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t gfn, int nr, pgprot_t prot, unsigned int domid, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff810225a0)
Location: arch/x86/xen/mmu.c:2885
Inline: False
```
**Symbols:**

```
ffffffff810225a0-ffffffff810225cf: xen_remap_domain_gfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xen_remap_domain_gfn_range(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t gfn, int nr, pgprot_t prot, unsigned int domid, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81022cf0)
Location: arch/x86/xen/mmu.c:2885
Inline: False
```
**Symbols:**

```
ffffffff81022cf0-ffffffff81022d1f: xen_remap_domain_gfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xen_remap_domain_gfn_range(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t gfn, int nr, pgprot_t prot, unsigned int domid, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101a8e0)
Location: arch/x86/xen/mmu.c:169
Inline: False
```
**Symbols:**

```
ffffffff8101a8e0-ffffffff8101a914: xen_remap_domain_gfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xen_remap_domain_gfn_range(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t gfn, int nr, pgprot_t prot, unsigned int domid, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101b1b0)
Location: arch/x86/xen/mmu.c:169
Inline: False
```
**Symbols:**

```
ffffffff8101b1b0-ffffffff8101b1f5: xen_remap_domain_gfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xen_remap_domain_gfn_range(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t gfn, int nr, pgprot_t prot, unsigned int domid, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101bbe0)
Location: arch/x86/xen/mmu.c:177
Inline: False
```
**Symbols:**

```
ffffffff8101bbe0-ffffffff8101bc1a: xen_remap_domain_gfn_range (STB_GLOBAL)
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
