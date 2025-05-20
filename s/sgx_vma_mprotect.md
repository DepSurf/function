# Function: <code>sgx_vma_mprotect</code>

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
int sgx_vma_mprotect(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long unsigned int newflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81065cb0)
Location: arch/x86/kernel/cpu/sgx/encl.c:269
Inline: False
```
**Symbols:**

```
ffffffff81065cb0-ffffffff81065cc7: sgx_vma_mprotect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sgx_vma_mprotect(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long unsigned int newflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81066260)
Location: arch/x86/kernel/cpu/sgx/encl.c:261
Inline: False
```
**Symbols:**

```
ffffffff81066260-ffffffff81066277: sgx_vma_mprotect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sgx_vma_mprotect(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long unsigned int newflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81070380)
Location: arch/x86/kernel/cpu/sgx/encl.c:302
Inline: False
```
**Symbols:**

```
ffffffff81070380-ffffffff81070397: sgx_vma_mprotect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sgx_vma_mprotect(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long unsigned int newflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107e560)
Location: arch/x86/kernel/cpu/sgx/encl.c:403
Inline: False
```
**Symbols:**

```
ffffffff8107e560-ffffffff8107e583: sgx_vma_mprotect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sgx_vma_mprotect(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long unsigned int newflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8108fa80)
Location: arch/x86/kernel/cpu/sgx/encl.c:550
Inline: False
```
**Symbols:**

```
ffffffff8108fa80-ffffffff8108faa3: sgx_vma_mprotect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sgx_vma_mprotect(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long unsigned int newflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81092990)
Location: arch/x86/kernel/cpu/sgx/encl.c:550
Inline: False
```
**Symbols:**

```
ffffffff81092990-ffffffff810929b3: sgx_vma_mprotect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sgx_vma_mprotect(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long unsigned int newflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81099da0)
Location: arch/x86/kernel/cpu/sgx/encl.c:570
Inline: False
```
**Symbols:**

```
ffffffff81099da0-ffffffff81099dc3: sgx_vma_mprotect (STB_LOCAL)
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
