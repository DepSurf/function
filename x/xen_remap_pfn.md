# Function: <code>xen_remap_pfn</code>

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
int xen_remap_pfn(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t *pfn, int nr, int *err_ptr, pgprot_t prot, unsigned int domid, bool no_translate, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81022630)
Location: arch/x86/xen/mmu_pv.c:2730
Inline: False
```
**Symbols:**

```
ffffffff81022630-ffffffff81022818: xen_remap_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xen_remap_pfn(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t *pfn, int nr, int *err_ptr, pgprot_t prot, unsigned int domid, bool no_translate, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810235e0)
Location: arch/x86/xen/mmu_pv.c:2717
Inline: False
```
**Symbols:**

```
ffffffff810235e0-ffffffff810237c7: xen_remap_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xen_remap_pfn(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t *pfn, int nr, int *err_ptr, pgprot_t prot, unsigned int domid, bool no_translate, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810240a0)
Location: arch/x86/xen/mmu_pv.c:2715
Inline: False
```
**Symbols:**

```
ffffffff810240a0-ffffffff81024287: xen_remap_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xen_remap_pfn(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t *pfn, int nr, int *err_ptr, pgprot_t prot, unsigned int domid, bool no_translate, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81026a00)
Location: arch/x86/xen/mmu_pv.c:2715
Inline: False
```
**Symbols:**

```
ffffffff81026a00-ffffffff81026c79: xen_remap_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xen_remap_pfn(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t *pfn, int nr, int *err_ptr, pgprot_t prot, unsigned int domid, bool no_translate, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81027210)
Location: arch/x86/xen/mmu_pv.c:2397
Inline: False
```
**Symbols:**

```
ffffffff81027210-ffffffff81027489: xen_remap_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xen_remap_pfn(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t *pfn, int nr, int *err_ptr, pgprot_t prot, unsigned int domid, bool no_translate, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810290e0)
Location: arch/x86/xen/mmu_pv.c:2396
Inline: False
```
**Symbols:**

```
ffffffff810290e0-ffffffff810292fb: xen_remap_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xen_remap_pfn(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t *pfn, int nr, int *err_ptr, pgprot_t prot, unsigned int domid, bool no_translate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8102d830)
Location: arch/x86/xen/mmu_pv.c:2399
Inline: False
```
**Symbols:**

```
ffffffff8102d830-ffffffff8102da87: xen_remap_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xen_remap_pfn(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t *pfn, int nr, int *err_ptr, pgprot_t prot, unsigned int domid, bool no_translate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81032640)
Location: arch/x86/xen/mmu_pv.c:2425
Inline: False
```
**Symbols:**

```
ffffffff81032640-ffffffff810328e7: xen_remap_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xen_remap_pfn(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t *pfn, int nr, int *err_ptr, pgprot_t prot, unsigned int domid, bool no_translate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8103a050)
Location: arch/x86/xen/mmu_pv.c:2425
Inline: False
```
**Symbols:**

```
ffffffff8103a050-ffffffff8103a2f7: xen_remap_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xen_remap_pfn(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t *pfn, int nr, int *err_ptr, pgprot_t prot, unsigned int domid, bool no_translate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8103a0e0)
Location: arch/x86/xen/mmu_pv.c:2433
Inline: False
```
**Symbols:**

```
ffffffff8103a0e0-ffffffff8103a353: xen_remap_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xen_remap_pfn(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t *pfn, int nr, int *err_ptr, pgprot_t prot, unsigned int domid, bool no_translate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810405a0)
Location: arch/x86/xen/mmu_pv.c:2444
Inline: False
```
**Symbols:**

```
ffffffff810405a0-ffffffff81040813: xen_remap_pfn (STB_GLOBAL)
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
int xen_remap_pfn(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t *pfn, int nr, int *err_ptr, pgprot_t prot, unsigned int domid, bool no_translate, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81024200)
Location: arch/x86/xen/mmu_pv.c:2715
Inline: False
```
**Symbols:**

```
ffffffff81024200-ffffffff810243e7: xen_remap_pfn (STB_GLOBAL)
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
int xen_remap_pfn(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t *pfn, int nr, int *err_ptr, pgprot_t prot, unsigned int domid, bool no_translate, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81024060)
Location: arch/x86/xen/mmu_pv.c:2715
Inline: False
```
**Symbols:**

```
ffffffff81024060-ffffffff81024247: xen_remap_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xen_remap_pfn(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t *pfn, int nr, int *err_ptr, pgprot_t prot, unsigned int domid, bool no_translate, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810245b0)
Location: arch/x86/xen/mmu_pv.c:2715
Inline: False
```
**Symbols:**

```
ffffffff810245b0-ffffffff8102477d: xen_remap_pfn (STB_GLOBAL)
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
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct page **pages</code>
</li>
</ul>
</details>
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
