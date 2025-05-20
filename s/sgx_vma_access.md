# Function: <code>sgx_vma_access</code>

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
int sgx_vma_access(struct vm_area_struct *vma, long unsigned int addr, void *buf, int len, int write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81066540)
Location: arch/x86/kernel/cpu/sgx/encl.c:327
Inline: False
```
**Symbols:**

```
ffffffff81066540-ffffffff8106686f: sgx_vma_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sgx_vma_access(struct vm_area_struct *vma, long unsigned int addr, void *buf, int len, int write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81066c00)
Location: arch/x86/kernel/cpu/sgx/encl.c:319
Inline: False
```
**Symbols:**

```
ffffffff81066c00-ffffffff81066f1e: sgx_vma_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sgx_vma_access(struct vm_area_struct *vma, long unsigned int addr, void *buf, int len, int write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81070ec0)
Location: arch/x86/kernel/cpu/sgx/encl.c:360
Inline: False
```
**Symbols:**

```
ffffffff81070ec0-ffffffff81071237: sgx_vma_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sgx_vma_access(struct vm_area_struct *vma, long unsigned int addr, void *buf, int len, int write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107eec0)
Location: arch/x86/kernel/cpu/sgx/encl.c:461
Inline: False
```
**Symbols:**

```
ffffffff8107eec0-ffffffff8107f18e: sgx_vma_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sgx_vma_access(struct vm_area_struct *vma, long unsigned int addr, void *buf, int len, int write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81090770)
Location: arch/x86/kernel/cpu/sgx/encl.c:608
Inline: False
```
**Symbols:**

```
ffffffff81090770-ffffffff81090a68: sgx_vma_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sgx_vma_access(struct vm_area_struct *vma, long unsigned int addr, void *buf, int len, int write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81093680)
Location: arch/x86/kernel/cpu/sgx/encl.c:608
Inline: False
```
**Symbols:**

```
ffffffff81093680-ffffffff81093994: sgx_vma_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sgx_vma_access(struct vm_area_struct *vma, long unsigned int addr, void *buf, int len, int write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109aaf0)
Location: arch/x86/kernel/cpu/sgx/encl.c:628
Inline: False
```
**Symbols:**

```
ffffffff8109aaf0-ffffffff8109ae04: sgx_vma_access (STB_LOCAL)
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
