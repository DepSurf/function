# Function: <code>vmf_insert_pfn_prot</code>

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
vm_fault_t vmf_insert_pfn_prot(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, pgprot_t pgprot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81244470)
Location: mm/memory.c:1595
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - mm/memory.c:vmf_insert_pfn
```
**Symbols:**

```
ffffffff81244470-ffffffff81244576: vmf_insert_pfn_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn_prot(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, pgprot_t pgprot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81256410)
Location: mm/memory.c:1648
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - mm/memory.c:vmf_insert_pfn
```
**Symbols:**

```
ffffffff81256410-ffffffff8125653b: vmf_insert_pfn_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn_prot(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, pgprot_t pgprot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812649a0)
Location: mm/memory.c:1653
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - mm/memory.c:vmf_insert_pfn
```
**Symbols:**

```
ffffffff812649a0-ffffffff81264acb: vmf_insert_pfn_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn_prot(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, pgprot_t pgprot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81292c00)
Location: mm/memory.c:1819
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - mm/memory.c:vmf_insert_pfn
```
**Symbols:**

```
ffffffff81292c00-ffffffff81292d42: vmf_insert_pfn_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn_prot(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, pgprot_t pgprot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129d520)
Location: mm/memory.c:1993
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - mm/memory.c:vmf_insert_pfn
```
**Symbols:**

```
ffffffff8129d520-ffffffff8129d5eb: vmf_insert_pfn_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn_prot(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, pgprot_t pgprot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a2b50)
Location: mm/memory.c:2011
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - mm/memory.c:vmf_insert_pfn
```
**Symbols:**

```
ffffffff812a2b50-ffffffff812a2c1b: vmf_insert_pfn_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn_prot(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, pgprot_t pgprot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e5fa0)
Location: mm/memory.c:2106
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - mm/memory.c:vmf_insert_pfn
```
**Symbols:**

```
ffffffff812e5fa0-ffffffff812e6081: vmf_insert_pfn_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn_prot(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, pgprot_t pgprot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81345590)
Location: mm/memory.c:2199
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - mm/memory.c:vmf_insert_pfn
```
**Symbols:**

```
ffffffff81345590-ffffffff81345688: vmf_insert_pfn_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn_prot(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, pgprot_t pgprot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813bd830)
Location: mm/memory.c:2170
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - mm/memory.c:vmf_insert_pfn
```
**Symbols:**

```
ffffffff813bd830-ffffffff813bd9b9: vmf_insert_pfn_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn_prot(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, pgprot_t pgprot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813f2530)
Location: mm/memory.c:2203
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - mm/memory.c:vmf_insert_pfn
```
**Symbols:**

```
ffffffff813f2530-ffffffff813f26b9: vmf_insert_pfn_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn_prot(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, pgprot_t pgprot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8141d230)
Location: mm/memory.c:2226
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - mm/memory.c:vmf_insert_pfn
```
**Symbols:**

```
ffffffff8141d230-ffffffff8141d3f5: vmf_insert_pfn_prot (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn_prot(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, pgprot_t pgprot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102fb6a0)
Location: mm/memory.c:1653
Inline: False
Direct callers:
  - mm/memory.c:vmf_insert_pfn
```
**Symbols:**

```
ffff8000102fb6a0-ffff8000102fb75c: vmf_insert_pfn_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn_prot(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, pgprot_t pgprot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0519ebc)
Location: mm/memory.c:1653
Inline: False
Direct callers:
  - mm/memory.c:vmf_insert_pfn
```
**Symbols:**

```
c0519ebc-c0519f8c: vmf_insert_pfn_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn_prot(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, pgprot_t pgprot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003c66b0)
Location: mm/memory.c:1653
Inline: False
Direct callers:
  - mm/memory.c:vmf_insert_pfn
```
**Symbols:**

```
c0000000003c66b0-c0000000003c67d4: vmf_insert_pfn_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn_prot(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, pgprot_t pgprot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe00020ad4a)
Location: mm/memory.c:1653
Inline: False
Direct callers:
  - mm/memory.c:vmf_insert_pfn
```
**Symbols:**

```
ffffffe00020ad4a-ffffffe00020ae22: vmf_insert_pfn_prot (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn_prot(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, pgprot_t pgprot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125cff0)
Location: mm/memory.c:1653
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - mm/memory.c:vmf_insert_pfn
```
**Symbols:**

```
ffffffff8125cff0-ffffffff8125d11b: vmf_insert_pfn_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn_prot(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, pgprot_t pgprot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124f450)
Location: mm/memory.c:1653
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - mm/memory.c:vmf_insert_pfn
```
**Symbols:**

```
ffffffff8124f450-ffffffff8124f57b: vmf_insert_pfn_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn_prot(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, pgprot_t pgprot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125ad90)
Location: mm/memory.c:1653
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - mm/memory.c:vmf_insert_pfn
```
**Symbols:**

```
ffffffff8125ad90-ffffffff8125aebb: vmf_insert_pfn_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn_prot(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, pgprot_t pgprot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8126a760)
Location: mm/memory.c:1653
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - mm/memory.c:vmf_insert_pfn
```
**Symbols:**

```
ffffffff8126a760-ffffffff8126a88b: vmf_insert_pfn_prot (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
