# Function: <code>pin_pagetable_pfn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void pin_pagetable_pfn(unsigned int cmd, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81f623b0)
Location: arch/x86/xen/mmu.c:1097
Inline: True
Direct callers:
  - arch/x86/xen/mmu.c:xen_alloc_pte_init
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_release_pte_init
  - arch/x86/xen/mmu.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
```
**Symbols:**

```
ffffffff81f623b0-ffffffff81f62436: pin_pagetable_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void pin_pagetable_pfn(unsigned int cmd, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81f89fcc)
Location: arch/x86/xen/mmu.c:1098
Inline: True
Direct callers:
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu.c:xen_release_pte_init
  - arch/x86/xen/mmu.c:xen_alloc_pte_init
  - arch/x86/xen/mmu.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
**Symbols:**

```
ffffffff81f89fcc-ffffffff81f8a052: pin_pagetable_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void pin_pagetable_pfn(unsigned int cmd, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81fc53c6)
Location: arch/x86/xen/mmu.c:1098
Inline: True
Direct callers:
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu.c:xen_release_pte_init
  - arch/x86/xen/mmu.c:xen_alloc_pte_init
  - arch/x86/xen/mmu.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
**Symbols:**

```
ffffffff81fc53c6-ffffffff81fc544c: pin_pagetable_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void pin_pagetable_pfn(unsigned int cmd, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff820a6213)
Location: arch/x86/xen/mmu_pv.c:1070
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_release_pte_init
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte_init
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
**Symbols:**

```
ffffffff820a6213-ffffffff820a629e: pin_pagetable_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void pin_pagetable_pfn(unsigned int cmd, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff826ac8dd)
Location: arch/x86/xen/mmu_pv.c:1043
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_release_pte_init
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte_init
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
**Symbols:**

```
ffffffff826ac8dd-ffffffff826ac968: pin_pagetable_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pin_pagetable_pfn(unsigned int cmd, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff826d5a10)
Location: arch/x86/xen/mmu_pv.c:1072
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_release_pte_init
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte_init
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
**Symbols:**

```
ffffffff826d5a10-ffffffff826d5a93: pin_pagetable_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pin_pagetable_pfn(unsigned int cmd, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8288bb28)
Location: arch/x86/xen/mmu_pv.c:1082
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_release_pte_init
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte_init
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
**Symbols:**

```
ffffffff8288bb28-ffffffff8288bbab: pin_pagetable_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pin_pagetable_pfn(unsigned int cmd, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff828a2f5b)
Location: arch/x86/xen/mmu_pv.c:1082
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_release_pte_init
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte_init
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
**Symbols:**

```
ffffffff828a2f5b-ffffffff828a2fde: pin_pagetable_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pin_pagetable_pfn(unsigned int cmd, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff828a600e)
Location: arch/x86/xen/mmu_pv.c:1082
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_release_pte_init
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte_init
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
**Symbols:**

```
ffffffff828a600e-ffffffff828a6091: pin_pagetable_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pin_pagetable_pfn(unsigned int cmd, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff82ccc4ec)
Location: arch/x86/xen/mmu_pv.c:1082
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_release_pte_init
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte_init
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
**Symbols:**

```
ffffffff82ccc4ec-ffffffff82ccc56f: pin_pagetable_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pin_pagetable_pfn(unsigned int cmd, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff82fb8328)
Location: arch/x86/xen/mmu_pv.c:987
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_release_pte_init
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte_init
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
**Symbols:**

```
ffffffff82fb8328-ffffffff82fb83ab: pin_pagetable_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pin_pagetable_pfn(unsigned int cmd, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff831c2993)
Location: arch/x86/xen/mmu_pv.c:987
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_release_pte_init
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte_init
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
**Symbols:**

```
ffffffff831c2993-ffffffff831c2a16: pin_pagetable_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pin_pagetable_pfn(unsigned int cmd, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff832a339f)
Location: arch/x86/xen/mmu_pv.c:987
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_release_pte_init
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte_init
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
**Symbols:**

```
ffffffff832a339f-ffffffff832a3422: pin_pagetable_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pin_pagetable_pfn(unsigned int cmd, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8345260f)
Location: arch/x86/xen/mmu_pv.c:993
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_release_pte_init
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte_init
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
**Symbols:**

```
ffffffff8345260f-ffffffff834526ba: pin_pagetable_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pin_pagetable_pfn(unsigned int cmd, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff83e6f480)
Location: arch/x86/xen/mmu_pv.c:993
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_release_pte_init
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte_init
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
**Symbols:**

```
ffffffff83e6f480-ffffffff83e6f534: pin_pagetable_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pin_pagetable_pfn(unsigned int cmd, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff83690380)
Location: arch/x86/xen/mmu_pv.c:1002
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_release_pte_init
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte_init
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
**Symbols:**

```
ffffffff83690380-ffffffff83690434: pin_pagetable_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pin_pagetable_pfn(unsigned int cmd, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff838bfed0)
Location: arch/x86/xen/mmu_pv.c:1002
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_release_pte_init
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte_init
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
**Symbols:**

```
ffffffff838bfed0-ffffffff838bff84: pin_pagetable_pfn (STB_LOCAL)
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
void pin_pagetable_pfn(unsigned int cmd, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff82894017)
Location: arch/x86/xen/mmu_pv.c:1082
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_release_pte_init
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte_init
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
**Symbols:**

```
ffffffff82894017-ffffffff8289409a: pin_pagetable_pfn (STB_LOCAL)
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
void pin_pagetable_pfn(unsigned int cmd, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff828a700e)
Location: arch/x86/xen/mmu_pv.c:1082
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_release_pte_init
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte_init
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
**Symbols:**

```
ffffffff828a700e-ffffffff828a7091: pin_pagetable_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pin_pagetable_pfn(unsigned int cmd, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff828a6fe2)
Location: arch/x86/xen/mmu_pv.c:1082
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_release_pte_init
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte_init
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
**Symbols:**

```
ffffffff828a6fe2-ffffffff828a7065: pin_pagetable_pfn (STB_LOCAL)
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
