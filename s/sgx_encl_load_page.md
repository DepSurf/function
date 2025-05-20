# Function: <code>sgx_encl_load_page</code>

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
struct sgx_encl_page *sgx_encl_load_page(struct sgx_encl *encl, long unsigned int addr, long unsigned int vm_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81066480)
Location: arch/x86/kernel/cpu/sgx/encl.c:93
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_access
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault
```
**Symbols:**

```
ffffffff81066480-ffffffff81066539: sgx_encl_load_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sgx_encl_page *sgx_encl_load_page(struct sgx_encl *encl, long unsigned int addr, long unsigned int vm_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81066b40)
Location: arch/x86/kernel/cpu/sgx/encl.c:93
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_access
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault
```
**Symbols:**

```
ffffffff81066b40-ffffffff81066bf9: sgx_encl_load_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sgx_encl_page *sgx_encl_load_page(struct sgx_encl *encl, long unsigned int addr, long unsigned int vm_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81070e00)
Location: arch/x86/kernel/cpu/sgx/encl.c:134
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_access
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault
```
**Symbols:**

```
ffffffff81070e00-ffffffff81070eb9: sgx_encl_load_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sgx_encl_page *sgx_encl_load_page(struct sgx_encl *encl, long unsigned int addr, long unsigned int vm_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107ede0)
Location: arch/x86/kernel/cpu/sgx/encl.c:235
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_access
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault
```
**Symbols:**

```
ffffffff8107ede0-ffffffff8107eeb6: sgx_encl_load_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sgx_encl_page *sgx_encl_load_page(struct sgx_encl *encl, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81090720)
Location: arch/x86/kernel/cpu/sgx/encl.c:289
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_remove_pages
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_modify_types
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_restrict_permissions
```
**Symbols:**

```
ffffffff81090720-ffffffff8109075f: sgx_encl_load_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sgx_encl_page *sgx_encl_load_page(struct sgx_encl *encl, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81093630)
Location: arch/x86/kernel/cpu/sgx/encl.c:289
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_remove_pages
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_modify_types
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_restrict_permissions
```
**Symbols:**

```
ffffffff81093630-ffffffff8109366f: sgx_encl_load_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sgx_encl_page *sgx_encl_load_page(struct sgx_encl *encl, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109aaa0)
Location: arch/x86/kernel/cpu/sgx/encl.c:302
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_remove_pages
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_modify_types
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_restrict_permissions
```
**Symbols:**

```
ffffffff8109aaa0-ffffffff8109aadf: sgx_encl_load_page (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int vm_flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
