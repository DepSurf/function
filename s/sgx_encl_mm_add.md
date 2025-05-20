# Function: <code>sgx_encl_mm_add</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sgx_encl_mm_add(struct sgx_encl *encl, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81065980)
Location: arch/x86/kernel/cpu/sgx/encl.c:516
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_mmap
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_open
```
**Symbols:**

```
ffffffff81065980-ffffffff81065a98: sgx_encl_mm_add.part.0 (STB_LOCAL)
ffffffff81065f00-ffffffff81065f9d: sgx_encl_mm_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int sgx_encl_mm_add(struct sgx_encl *encl, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81066280)
Location: arch/x86/kernel/cpu/sgx/encl.c:508
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_mmap
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_open
```
**Symbols:**

```
ffffffff81066280-ffffffff8106640b: sgx_encl_mm_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int sgx_encl_mm_add(struct sgx_encl *encl, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810703a0)
Location: arch/x86/kernel/cpu/sgx/encl.c:551
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_mmap
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_open
```
**Symbols:**

```
ffffffff810703a0-ffffffff81070530: sgx_encl_mm_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sgx_encl_mm_add(struct sgx_encl *encl, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107e590)
Location: arch/x86/kernel/cpu/sgx/encl.c:652
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_mmap
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_open
```
**Symbols:**

```
ffffffff8107e590-ffffffff8107e71b: sgx_encl_mm_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sgx_encl_mm_add(struct sgx_encl *encl, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8108fac0)
Location: arch/x86/kernel/cpu/sgx/encl.c:814
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_mmap
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_open
```
**Symbols:**

```
ffffffff8108fac0-ffffffff8108fc4b: sgx_encl_mm_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sgx_encl_mm_add(struct sgx_encl *encl, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810929d0)
Location: arch/x86/kernel/cpu/sgx/encl.c:816
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_mmap
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_open
```
**Symbols:**

```
ffffffff810929d0-ffffffff81092b5b: sgx_encl_mm_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sgx_encl_mm_add(struct sgx_encl *encl, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81099de0)
Location: arch/x86/kernel/cpu/sgx/encl.c:836
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_mmap
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_open
```
**Symbols:**

```
ffffffff81099de0-ffffffff81099f9a: sgx_encl_mm_add (STB_GLOBAL)
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
