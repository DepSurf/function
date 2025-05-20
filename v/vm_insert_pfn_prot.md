# Function: <code>vm_insert_pfn_prot</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int vm_insert_pfn_prot(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, pgprot_t pgprot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811dd6d0)
Location: mm/memory.c:1622
Inline: False
Direct callers:
  - mm/memory.c:vm_insert_pfn
```
**Symbols:**

```
ffffffff811dd6d0-ffffffff811dd7b6: vm_insert_pfn_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int vm_insert_pfn_prot(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, pgprot_t pgprot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811ed1c0)
Location: mm/memory.c:1618
Inline: False
Direct callers:
  - mm/memory.c:vm_insert_pfn
```
**Symbols:**

```
ffffffff811ed1c0-ffffffff811ed29b: vm_insert_pfn_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vm_insert_pfn_prot(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, pgprot_t pgprot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f8170)
Location: mm/memory.c:1769
Inline: False
Direct callers:
  - mm/memory.c:vm_insert_pfn
```
**Symbols:**

```
ffffffff811f8170-ffffffff811f8257: vm_insert_pfn_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vm_insert_pfn_prot(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, pgprot_t pgprot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812102f0)
Location: mm/memory.c:1872
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - mm/memory.c:vm_insert_pfn
```
**Symbols:**

```
ffffffff812102f0-ffffffff812103df: vm_insert_pfn_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int vm_insert_pfn_prot(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn, pgprot_t pgprot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8122fa30)
Location: mm/memory.c:1883
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - mm/memory.c:vm_insert_pfn
```
**Symbols:**

```
ffffffff8122fa30-ffffffff8122fb40: vm_insert_pfn_prot (STB_GLOBAL)
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
