# Function: <code>xen_xlate_remap_gfn_array</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xen_xlate_remap_gfn_array(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t *gfn, int nr, int *err_ptr, pgprot_t prot, unsigned int domid, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xlate_mmu.c (ffffffff814d71a0)
Location: drivers/xen/xlate_mmu.c:140
Inline: True
Direct callers:
  - arch/x86/xen/mmu.c:do_remap_gfn
```
**Symbols:**

```
ffffffff814d71a0-ffffffff814d71ab: xen_xlate_remap_gfn_array.part.0 (STB_LOCAL)
ffffffff814d71b0-ffffffff814d7250: xen_xlate_remap_gfn_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xen_xlate_remap_gfn_array(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t *gfn, int nr, int *err_ptr, pgprot_t prot, unsigned int domid, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xlate_mmu.c (ffffffff81527f60)
Location: drivers/xen/xlate_mmu.c:143
Inline: True
Direct callers:
  - arch/x86/xen/mmu.c:do_remap_gfn
```
**Symbols:**

```
ffffffff81527f60-ffffffff81527f6b: xen_xlate_remap_gfn_array.part.0 (STB_LOCAL)
ffffffff81527f70-ffffffff8152800f: xen_xlate_remap_gfn_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xen_xlate_remap_gfn_array(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t *gfn, int nr, int *err_ptr, pgprot_t prot, unsigned int domid, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xlate_mmu.c (ffffffff815544d0)
Location: drivers/xen/xlate_mmu.c:143
Inline: True
Direct callers:
  - arch/x86/xen/mmu.c:do_remap_gfn
```
**Symbols:**

```
ffffffff815544d0-ffffffff815544db: xen_xlate_remap_gfn_array.part.0 (STB_LOCAL)
ffffffff815544e0-ffffffff8155457f: xen_xlate_remap_gfn_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xen_xlate_remap_gfn_array(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t *gfn, int nr, int *err_ptr, pgprot_t prot, unsigned int domid, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xlate_mmu.c (ffffffff81569010)
Location: drivers/xen/xlate_mmu.c:143
Inline: True
```
**Symbols:**

```
ffffffff81569010-ffffffff8156901b: xen_xlate_remap_gfn_array.part.0 (STB_LOCAL)
ffffffff81569020-ffffffff815690c0: xen_xlate_remap_gfn_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xen_xlate_remap_gfn_array(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t *gfn, int nr, int *err_ptr, pgprot_t prot, unsigned int domid, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xlate_mmu.c (ffffffff815cd1c0)
Location: drivers/xen/xlate_mmu.c:143
Inline: True
```
**Symbols:**

```
ffffffff815cd1c0-ffffffff815cd1cb: xen_xlate_remap_gfn_array.part.0 (STB_LOCAL)
ffffffff815cd1d0-ffffffff815cd270: xen_xlate_remap_gfn_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xen_xlate_remap_gfn_array(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t *gfn, int nr, int *err_ptr, pgprot_t prot, unsigned int domid, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xlate_mmu.c (ffffffff81605910)
Location: drivers/xen/xlate_mmu.c:143
Inline: True
```
**Symbols:**

```
ffffffff81605910-ffffffff8160591b: xen_xlate_remap_gfn_array.part.0 (STB_LOCAL)
ffffffff81605920-ffffffff816059c0: xen_xlate_remap_gfn_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xen_xlate_remap_gfn_array(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t *gfn, int nr, int *err_ptr, pgprot_t prot, unsigned int domid, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xlate_mmu.c (ffffffff816209f0)
Location: drivers/xen/xlate_mmu.c:144
Inline: True
```
**Symbols:**

```
ffffffff816209f0-ffffffff816209fb: xen_xlate_remap_gfn_array.part.0 (STB_LOCAL)
ffffffff81620a00-ffffffff81620aa0: xen_xlate_remap_gfn_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xen_xlate_remap_gfn_array(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t *gfn, int nr, int *err_ptr, pgprot_t prot, unsigned int domid, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xlate_mmu.c (ffffffff81653f50)
Location: drivers/xen/xlate_mmu.c:143
Inline: True
```
**Symbols:**

```
ffffffff81653f50-ffffffff81653f5b: xen_xlate_remap_gfn_array.part.0 (STB_LOCAL)
ffffffff81653f60-ffffffff81653ffc: xen_xlate_remap_gfn_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xen_xlate_remap_gfn_array(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t *gfn, int nr, int *err_ptr, pgprot_t prot, unsigned int domid, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xlate_mmu.c (ffffffff816764f0)
Location: drivers/xen/xlate_mmu.c:143
Inline: True
```
**Symbols:**

```
ffffffff816764f0-ffffffff816764fb: xen_xlate_remap_gfn_array.part.0 (STB_LOCAL)
ffffffff81676500-ffffffff8167659c: xen_xlate_remap_gfn_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xen_xlate_remap_gfn_array(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t *gfn, int nr, int *err_ptr, pgprot_t prot, unsigned int domid, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xlate_mmu.c (ffffffff81726cb0)
Location: drivers/xen/xlate_mmu.c:143
Inline: False
```
**Symbols:**

```
ffffffff81726cb0-ffffffff81726d49: xen_xlate_remap_gfn_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xen_xlate_remap_gfn_array(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t *gfn, int nr, int *err_ptr, pgprot_t prot, unsigned int domid, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xlate_mmu.c (ffffffff81743210)
Location: drivers/xen/xlate_mmu.c:143
Inline: False
```
**Symbols:**

```
ffffffff81743210-ffffffff817432a9: xen_xlate_remap_gfn_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xen_xlate_remap_gfn_array(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t *gfn, int nr, int *err_ptr, pgprot_t prot, unsigned int domid, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xlate_mmu.c (ffffffff81726c00)
Location: drivers/xen/xlate_mmu.c:143
Inline: False
```
**Symbols:**

```
ffffffff81726c00-ffffffff81726ca4: xen_xlate_remap_gfn_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xen_xlate_remap_gfn_array(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t *gfn, int nr, int *err_ptr, pgprot_t prot, unsigned int domid, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xlate_mmu.c (ffffffff817a5c30)
Location: drivers/xen/xlate_mmu.c:143
Inline: False
```
**Symbols:**

```
ffffffff817a5c30-ffffffff817a5cd4: xen_xlate_remap_gfn_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xen_xlate_remap_gfn_array(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t *gfn, int nr, int *err_ptr, pgprot_t prot, unsigned int domid, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xlate_mmu.c (ffffffff818dfb70)
Location: drivers/xen/xlate_mmu.c:143
Inline: False
```
**Symbols:**

```
ffffffff818dfb70-ffffffff818dfc50: xen_xlate_remap_gfn_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xen_xlate_remap_gfn_array(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t *gfn, int nr, int *err_ptr, pgprot_t prot, unsigned int domid, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xlate_mmu.c (ffffffff81a33fc0)
Location: drivers/xen/xlate_mmu.c:143
Inline: False
```
**Symbols:**

```
ffffffff81a33fc0-ffffffff81a340a0: xen_xlate_remap_gfn_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xen_xlate_remap_gfn_array(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t *gfn, int nr, int *err_ptr, pgprot_t prot, unsigned int domid, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xlate_mmu.c (ffffffff81a7d9e0)
Location: drivers/xen/xlate_mmu.c:143
Inline: False
```
**Symbols:**

```
ffffffff81a7d9e0-ffffffff81a7dabb: xen_xlate_remap_gfn_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xen_xlate_remap_gfn_array(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t *gfn, int nr, int *err_ptr, pgprot_t prot, unsigned int domid, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xlate_mmu.c (ffffffff81acfe80)
Location: drivers/xen/xlate_mmu.c:143
Inline: False
```
**Symbols:**

```
ffffffff81acfe80-ffffffff81acff5b: xen_xlate_remap_gfn_array (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xen_xlate_remap_gfn_array(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t *gfn, int nr, int *err_ptr, pgprot_t prot, unsigned int domid, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xlate_mmu.c (ffff80001083eed8)
Location: drivers/xen/xlate_mmu.c:143
Inline: True
```
**Symbols:**

```
ffff80001083eed8-ffff80001083eeec: xen_xlate_remap_gfn_array.part.0 (STB_LOCAL)
ffff80001083eef0-ffff80001083efd8: xen_xlate_remap_gfn_array (STB_GLOBAL)
```
</details>
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xen_xlate_remap_gfn_array(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t *gfn, int nr, int *err_ptr, pgprot_t prot, unsigned int domid, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xlate_mmu.c (ffffffff8163c1e0)
Location: drivers/xen/xlate_mmu.c:143
Inline: True
```
**Symbols:**

```
ffffffff8163c1e0-ffffffff8163c1eb: xen_xlate_remap_gfn_array.part.0 (STB_LOCAL)
ffffffff8163c1f0-ffffffff8163c28c: xen_xlate_remap_gfn_array (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xen_xlate_remap_gfn_array(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t *gfn, int nr, int *err_ptr, pgprot_t prot, unsigned int domid, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xlate_mmu.c (ffffffff8166a330)
Location: drivers/xen/xlate_mmu.c:143
Inline: True
```
**Symbols:**

```
ffffffff8166a330-ffffffff8166a33b: xen_xlate_remap_gfn_array.part.0 (STB_LOCAL)
ffffffff8166a340-ffffffff8166a3dc: xen_xlate_remap_gfn_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xen_xlate_remap_gfn_array(struct vm_area_struct *vma, long unsigned int addr, xen_pfn_t *gfn, int nr, int *err_ptr, pgprot_t prot, unsigned int domid, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xlate_mmu.c (ffffffff816848f0)
Location: drivers/xen/xlate_mmu.c:143
Inline: True
```
**Symbols:**

```
ffffffff816848f0-ffffffff816848fb: xen_xlate_remap_gfn_array.part.0 (STB_LOCAL)
ffffffff81684900-ffffffff8168499c: xen_xlate_remap_gfn_array (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
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
