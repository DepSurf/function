# Function: <code>sgx_get_epc_phys_addr</code>

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
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81066a3a)
Location: arch/x86/kernel/cpu/sgx/sgx.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81066f6d)
Location: arch/x86/kernel/cpu/sgx/sgx.h:60
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff8106994b)
Location: arch/x86/kernel/cpu/sgx/sgx.h:60
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81071293)
Location: arch/x86/kernel/cpu/sgx/sgx.h:60
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff8107402f)
Location: arch/x86/kernel/cpu/sgx/sgx.h:60
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107f1e7)
Location: arch/x86/kernel/cpu/sgx/sgx.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81082580)
Location: arch/x86/kernel/cpu/sgx/sgx.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81090f13)
Location: arch/x86/kernel/cpu/sgx/sgx.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81094ffd)
Location: arch/x86/kernel/cpu/sgx/sgx.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81093e44)
Location: arch/x86/kernel/cpu/sgx/sgx.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81097f80)
Location: arch/x86/kernel/cpu/sgx/sgx.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109b324)
Location: arch/x86/kernel/cpu/sgx/sgx.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff8109f520)
Location: arch/x86/kernel/cpu/sgx/sgx.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
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
