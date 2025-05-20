# Function: <code>make_lowmem_page_readwrite</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void make_lowmem_page_readwrite(void *vaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81022970)
Location: arch/x86/xen/mmu.c:173
Inline: True
Direct callers:
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_release_pmd_init
  - arch/x86/xen/mmu.c:xen_release_pte_init
  - arch/x86/xen/mmu.c:xen_free_ro_pages
```
**Symbols:**

```
ffffffff81022970-ffffffff810229ad: make_lowmem_page_readwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void make_lowmem_page_readwrite(void *vaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81021ca0)
Location: arch/x86/xen/mmu.c:174
Inline: True
Direct callers:
  - arch/x86/xen/mmu.c:xen_release_pmd_init
  - arch/x86/xen/mmu.c:xen_release_pte_init
  - arch/x86/xen/mmu.c:xen_free_ro_pages
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
**Symbols:**

```
ffffffff81021ca0-ffffffff81021cdd: make_lowmem_page_readwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void make_lowmem_page_readwrite(void *vaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff810223f0)
Location: arch/x86/xen/mmu.c:174
Inline: True
Direct callers:
  - arch/x86/xen/mmu.c:xen_release_pmd_init
  - arch/x86/xen/mmu.c:xen_release_pte_init
  - arch/x86/xen/mmu.c:xen_free_ro_pages
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
**Symbols:**

```
ffffffff810223f0-ffffffff8102242d: make_lowmem_page_readwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void make_lowmem_page_readwrite(void *vaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810243c0)
Location: arch/x86/xen/mmu_pv.c:141
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_release_pmd_init
  - arch/x86/xen/mmu_pv.c:xen_release_pte_init
  - arch/x86/xen/mmu_pv.c:xen_free_ro_pages
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
**Symbols:**

```
ffffffff810243c0-ffffffff810243fd: make_lowmem_page_readwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void make_lowmem_page_readwrite(void *vaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81024f60)
Location: arch/x86/xen/mmu_pv.c:141
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_release_pmd_init
  - arch/x86/xen/mmu_pv.c:xen_release_pte_init
  - arch/x86/xen/mmu_pv.c:xen_free_ro_pages
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
**Symbols:**

```
ffffffff81024f60-ffffffff81024f9d: make_lowmem_page_readwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void make_lowmem_page_readwrite(void *vaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81025c80)
Location: arch/x86/xen/mmu_pv.c:143
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_release_pmd_init
  - arch/x86/xen/mmu_pv.c:xen_release_pte_init
  - arch/x86/xen/mmu_pv.c:xen_free_ro_pages
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff81025c80-ffffffff81025cbd: make_lowmem_page_readwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void make_lowmem_page_readwrite(void *vaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81025830)
Location: arch/x86/xen/mmu_pv.c:152
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_release_pmd_init
  - arch/x86/xen/mmu_pv.c:xen_release_pte_init
  - arch/x86/xen/mmu_pv.c:xen_free_ro_pages
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff81025830-ffffffff8102586d: make_lowmem_page_readwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void make_lowmem_page_readwrite(void *vaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81027560)
Location: arch/x86/xen/mmu_pv.c:152
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_release_pmd_init
  - arch/x86/xen/mmu_pv.c:xen_release_pte_init
  - arch/x86/xen/mmu_pv.c:xen_free_ro_pages
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff81027560-ffffffff8102759f: make_lowmem_page_readwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void make_lowmem_page_readwrite(void *vaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81027b40)
Location: arch/x86/xen/mmu_pv.c:152
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_release_pmd_init
  - arch/x86/xen/mmu_pv.c:xen_release_pte_init
  - arch/x86/xen/mmu_pv.c:xen_free_ro_pages
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff81027b40-ffffffff81027b7f: make_lowmem_page_readwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void make_lowmem_page_readwrite(void *vaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81029a80)
Location: arch/x86/xen/mmu_pv.c:152
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_release_pmd_init
  - arch/x86/xen/mmu_pv.c:xen_release_pte_init
  - arch/x86/xen/mmu_pv.c:xen_free_ro_pages
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff81029a80-ffffffff81029abd: make_lowmem_page_readwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void make_lowmem_page_readwrite(void *vaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8102a460)
Location: arch/x86/xen/mmu_pv.c:141
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_release_pmd_init
  - arch/x86/xen/mmu_pv.c:xen_release_pte_init
  - arch/x86/xen/mmu_pv.c:xen_free_ro_pages
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff8102a460-ffffffff8102a49d: make_lowmem_page_readwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void make_lowmem_page_readwrite(void *vaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8102b100)
Location: arch/x86/xen/mmu_pv.c:141
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_release_pmd_init
  - arch/x86/xen/mmu_pv.c:xen_release_pte_init
  - arch/x86/xen/mmu_pv.c:xen_free_ro_pages
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff8102b100-ffffffff8102b13d: make_lowmem_page_readwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void make_lowmem_page_readwrite(void *vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8102fa10)
Location: arch/x86/xen/mmu_pv.c:141
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_release_pmd_init
  - arch/x86/xen/mmu_pv.c:xen_release_pte_init
  - arch/x86/xen/mmu_pv.c:xen_free_ro_pages
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff8102fa10-ffffffff8102fa4d: make_lowmem_page_readwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void make_lowmem_page_readwrite(void *vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81034dc0)
Location: arch/x86/xen/mmu_pv.c:143
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_release_pmd_init
  - arch/x86/xen/mmu_pv.c:xen_release_pte_init
  - arch/x86/xen/mmu_pv.c:xen_free_ro_pages
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff81034dc0-ffffffff81034e15: make_lowmem_page_readwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void make_lowmem_page_readwrite(void *vaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff83e6f570)
Location: arch/x86/xen/mmu_pv.c:143
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_release_pmd_init
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_release_pte_init
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff8103c930-ffffffff8103c985: make_lowmem_page_readwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void make_lowmem_page_readwrite(void *vaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff83690470)
Location: arch/x86/xen/mmu_pv.c:159
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_release_pmd_init
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_release_pte_init
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff8103c810-ffffffff8103c865: make_lowmem_page_readwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void make_lowmem_page_readwrite(void *vaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff838bffc0)
Location: arch/x86/xen/mmu_pv.c:159
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_release_pmd_init
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_release_pte_init
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff81042ce0-ffffffff81042d35: make_lowmem_page_readwrite (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void make_lowmem_page_readwrite(void *vaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81027ca0)
Location: arch/x86/xen/mmu_pv.c:152
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_release_pmd_init
  - arch/x86/xen/mmu_pv.c:xen_release_pte_init
  - arch/x86/xen/mmu_pv.c:xen_free_ro_pages
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff81027ca0-ffffffff81027cdf: make_lowmem_page_readwrite (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void make_lowmem_page_readwrite(void *vaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81027b00)
Location: arch/x86/xen/mmu_pv.c:152
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_release_pmd_init
  - arch/x86/xen/mmu_pv.c:xen_release_pte_init
  - arch/x86/xen/mmu_pv.c:xen_free_ro_pages
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff81027b00-ffffffff81027b3f: make_lowmem_page_readwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void make_lowmem_page_readwrite(void *vaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81028740)
Location: arch/x86/xen/mmu_pv.c:152
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_release_pmd_init
  - arch/x86/xen/mmu_pv.c:xen_release_pte_init
  - arch/x86/xen/mmu_pv.c:xen_free_ro_pages
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff81028740-ffffffff8102877f: make_lowmem_page_readwrite (STB_GLOBAL)
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
