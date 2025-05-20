# Function: <code>vm_insert_pfn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int vm_insert_pfn(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811c1bb0)
Location: mm/memory.c:1564
Inline: False
```
**Symbols:**

```
ffffffff811c1bb0-ffffffff811c1cb0: vm_insert_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int vm_insert_pfn(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811dd7c0)
Location: mm/memory.c:1600
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
**Symbols:**

```
ffffffff811dd7c0-ffffffff811dd7d4: vm_insert_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int vm_insert_pfn(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811ed2a0)
Location: mm/memory.c:1596
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
**Symbols:**

```
ffffffff811ed2a0-ffffffff811ed2b4: vm_insert_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vm_insert_pfn(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f8260)
Location: mm/memory.c:1747
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
**Symbols:**

```
ffffffff811f8260-ffffffff811f8274: vm_insert_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vm_insert_pfn(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812103e0)
Location: mm/memory.c:1850
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
**Symbols:**

```
ffffffff812103e0-ffffffff812103f4: vm_insert_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int vm_insert_pfn(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8122fb40)
Location: mm/memory.c:1861
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
**Symbols:**

```
ffffffff8122fb40-ffffffff8122fb54: vm_insert_pfn (STB_GLOBAL)
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
