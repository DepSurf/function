# Function: <code>sgx_vepc_remove_page</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int sgx_vepc_remove_page(struct sgx_epc_page *epc_page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff810826a5)
Location: arch/x86/kernel/cpu/sgx/virt.c:114
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_free_page
Direct callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_ioctl
```
**Symbols:**

```
ffffffff81082100-ffffffff81082164: sgx_vepc_remove_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int sgx_vepc_remove_page(struct sgx_epc_page *epc_page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81095125)
Location: arch/x86/kernel/cpu/sgx/virt.c:114
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_free_page
Direct callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_ioctl
```
**Symbols:**

```
ffffffff81094b20-ffffffff81094b84: sgx_vepc_remove_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int sgx_vepc_remove_page(struct sgx_epc_page *epc_page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff810980a5)
Location: arch/x86/kernel/cpu/sgx/virt.c:114
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_free_page
Direct callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_ioctl
```
**Symbols:**

```
ffffffff81097a60-ffffffff81097ac4: sgx_vepc_remove_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int sgx_vepc_remove_page(struct sgx_epc_page *epc_page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff8109f645)
Location: arch/x86/kernel/cpu/sgx/virt.c:114
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_free_page
Direct callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_ioctl
```
**Symbols:**

```
ffffffff8109efd0-ffffffff8109f034: sgx_vepc_remove_page (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
