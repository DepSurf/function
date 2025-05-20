# Function: <code>xen_free_ro_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void xen_free_ro_pages(long unsigned int paddr, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81f62c0d)
Location: arch/x86/xen/mmu.c:1131
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_pagetable_init
```
**Symbols:**

```
ffffffff81f62c0d-ffffffff81f62c59: xen_free_ro_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xen_free_ro_pages(long unsigned int paddr, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81f8a7c6)
Location: arch/x86/xen/mmu.c:1132
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_cleanmfnmap_free_pgtbl
```
**Symbols:**

```
ffffffff81f8a7c6-ffffffff81f8a80f: xen_free_ro_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xen_free_ro_pages(long unsigned int paddr, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81fc5bc0)
Location: arch/x86/xen/mmu.c:1132
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_cleanmfnmap_free_pgtbl
```
**Symbols:**

```
ffffffff81fc5bc0-ffffffff81fc5c09: xen_free_ro_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xen_free_ro_pages(long unsigned int paddr, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff820a6a90)
Location: arch/x86/xen/mmu_pv.c:1104
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
```
**Symbols:**

```
ffffffff820a6a90-ffffffff820a6ade: xen_free_ro_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xen_free_ro_pages(long unsigned int paddr, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff826ad1ca)
Location: arch/x86/xen/mmu_pv.c:1077
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
```
**Symbols:**

```
ffffffff826ad1ca-ffffffff826ad218: xen_free_ro_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xen_free_ro_pages(long unsigned int paddr, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff826d6508)
Location: arch/x86/xen/mmu_pv.c:1106
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
```
**Symbols:**

```
ffffffff826d6508-ffffffff826d6556: xen_free_ro_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xen_free_ro_pages(long unsigned int paddr, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8288c451)
Location: arch/x86/xen/mmu_pv.c:1116
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
```
**Symbols:**

```
ffffffff8288c451-ffffffff8288c49f: xen_free_ro_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xen_free_ro_pages(long unsigned int paddr, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff828a38fa)
Location: arch/x86/xen/mmu_pv.c:1116
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
```
**Symbols:**

```
ffffffff828a38fa-ffffffff828a3948: xen_free_ro_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xen_free_ro_pages(long unsigned int paddr, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff828a6997)
Location: arch/x86/xen/mmu_pv.c:1116
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
```
**Symbols:**

```
ffffffff828a6997-ffffffff828a69e5: xen_free_ro_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xen_free_ro_pages(long unsigned int paddr, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff82cccd9c)
Location: arch/x86/xen/mmu_pv.c:1116
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pmd
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pmd
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
```
**Symbols:**

```
ffffffff82cccd9c-ffffffff82cccdea: xen_free_ro_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xen_free_ro_pages(long unsigned int paddr, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff82fb8bd8)
Location: arch/x86/xen/mmu_pv.c:1020
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pmd
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pmd
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
```
**Symbols:**

```
ffffffff82fb8bd8-ffffffff82fb8c26: xen_free_ro_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xen_free_ro_pages(long unsigned int paddr, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff831c3219)
Location: arch/x86/xen/mmu_pv.c:1020
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
```
**Symbols:**

```
ffffffff831c3219-ffffffff831c3267: xen_free_ro_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xen_free_ro_pages(long unsigned int paddr, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff832a3c53)
Location: arch/x86/xen/mmu_pv.c:1020
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
```
**Symbols:**

```
ffffffff832a3c53-ffffffff832a3ca1: xen_free_ro_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xen_free_ro_pages(long unsigned int paddr, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff83452ec6)
Location: arch/x86/xen/mmu_pv.c:1026
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
```
**Symbols:**

```
ffffffff83452ec6-ffffffff83452f1e: xen_free_ro_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff83e7060d)
Location: arch/x86/xen/mmu_pv.c:1026
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff83691487)
Location: arch/x86/xen/mmu_pv.c:1035
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff838c0f97)
Location: arch/x86/xen/mmu_pv.c:1035
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
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
void xen_free_ro_pages(long unsigned int paddr, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff828949a0)
Location: arch/x86/xen/mmu_pv.c:1116
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
```
**Symbols:**

```
ffffffff828949a0-ffffffff828949ee: xen_free_ro_pages (STB_LOCAL)
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
void xen_free_ro_pages(long unsigned int paddr, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff828a7997)
Location: arch/x86/xen/mmu_pv.c:1116
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
```
**Symbols:**

```
ffffffff828a7997-ffffffff828a79e5: xen_free_ro_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xen_free_ro_pages(long unsigned int paddr, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff828a799d)
Location: arch/x86/xen/mmu_pv.c:1116
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
```
**Symbols:**

```
ffffffff828a799d-ffffffff828a79eb: xen_free_ro_pages (STB_LOCAL)
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
