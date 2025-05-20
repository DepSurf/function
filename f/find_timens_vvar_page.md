# Function: <code>find_timens_vvar_page</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81005aa1)
Location: arch/x86/entry/vdso/vma.c:117
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004a51)
Location: arch/x86/entry/vdso/vma.c:101
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004a41)
Location: arch/x86/entry/vdso/vma.c:101
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81005071)
Location: arch/x86/entry/vdso/vma.c:101
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004074)
Location: arch/x86/entry/vdso/vma.c:101
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct page *find_timens_vvar_page(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff811f2670)
Location: kernel/time/namespace.c:195
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
**Symbols:**

```
ffffffff811f2670-ffffffff811f26c1: find_timens_vvar_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct page *find_timens_vvar_page(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff81206df0)
Location: kernel/time/namespace.c:195
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
**Symbols:**

```
ffffffff81206df0-ffffffff81206e41: find_timens_vvar_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct page *find_timens_vvar_page(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff8121e000)
Location: kernel/time/namespace.c:195
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
**Symbols:**

```
ffffffff8121e000-ffffffff8121e051: find_timens_vvar_page (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
