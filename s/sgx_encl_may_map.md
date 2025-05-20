# Function: <code>sgx_encl_may_map</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
int sgx_encl_may_map(struct sgx_encl *encl, long unsigned int start, long unsigned int end, long unsigned int vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81065aa0)
Location: arch/x86/kernel/cpu/sgx/encl.c:226
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_mmap
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_mprotect
```
**Symbols:**

```
ffffffff81065aa0-ffffffff81065cac: sgx_encl_may_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sgx_encl_may_map(struct sgx_encl *encl, long unsigned int start, long unsigned int end, long unsigned int vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81066050)
Location: arch/x86/kernel/cpu/sgx/encl.c:218
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_mmap
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_mprotect
```
**Symbols:**

```
ffffffff81066050-ffffffff8106625c: sgx_encl_may_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sgx_encl_may_map(struct sgx_encl *encl, long unsigned int start, long unsigned int end, long unsigned int vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81070170)
Location: arch/x86/kernel/cpu/sgx/encl.c:259
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_mmap
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_mprotect
```
**Symbols:**

```
ffffffff81070170-ffffffff81070380: sgx_encl_may_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sgx_encl_may_map(struct sgx_encl *encl, long unsigned int start, long unsigned int end, long unsigned int vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107e340)
Location: arch/x86/kernel/cpu/sgx/encl.c:360
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_mmap
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_mprotect
```
**Symbols:**

```
ffffffff8107e340-ffffffff8107e554: sgx_encl_may_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sgx_encl_may_map(struct sgx_encl *encl, long unsigned int start, long unsigned int end, long unsigned int vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8108f830)
Location: arch/x86/kernel/cpu/sgx/encl.c:502
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_mmap
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_mprotect
```
**Symbols:**

```
ffffffff8108f830-ffffffff8108fa6d: sgx_encl_may_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sgx_encl_may_map(struct sgx_encl *encl, long unsigned int start, long unsigned int end, long unsigned int vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81092730)
Location: arch/x86/kernel/cpu/sgx/encl.c:502
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_mmap
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_mprotect
```
**Symbols:**

```
ffffffff81092730-ffffffff81092972: sgx_encl_may_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sgx_encl_may_map(struct sgx_encl *encl, long unsigned int start, long unsigned int end, long unsigned int vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81099b40)
Location: arch/x86/kernel/cpu/sgx/encl.c:522
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_mmap
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_mprotect
```
**Symbols:**

```
ffffffff81099b40-ffffffff81099d82: sgx_encl_may_map (STB_GLOBAL)
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
