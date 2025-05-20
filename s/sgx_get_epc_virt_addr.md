# Function: <code>sgx_get_epc_virt_addr</code>

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
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81066b33)
Location: arch/x86/kernel/cpu/sgx/sgx.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_alloc_va_page
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_access
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_access
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8106706e)
Location: arch/x86/kernel/cpu/sgx/sgx.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_extend
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_extend
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8106873b)
Location: arch/x86/kernel/cpu/sgx/sgx.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_free_epc_page
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
  - arch/x86/kernel/cpu/sgx/main.c:sgx_sanitize_section
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81066a0f)
Location: arch/x86/kernel/cpu/sgx/sgx.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_free_epc_page
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_alloc_va_page
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_access
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_access
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff810675ff)
Location: arch/x86/kernel/cpu/sgx/sgx.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8106869c)
Location: arch/x86/kernel/cpu/sgx/sgx.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81069515)
Location: arch/x86/kernel/cpu/sgx/sgx.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_free_page
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81070c99)
Location: arch/x86/kernel/cpu/sgx/sgx.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_free_epc_page
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_alloc_va_page
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_access
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_access
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff810719af)
Location: arch/x86/kernel/cpu/sgx/sgx.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81072bc3)
Location: arch/x86/kernel/cpu/sgx/sgx.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81073c35)
Location: arch/x86/kernel/cpu/sgx/sgx.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_free_page
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107ec39)
Location: arch/x86/kernel/cpu/sgx/sgx.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_free_epc_page
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_alloc_va_page
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_access
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_access
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8107fa6b)
Location: arch/x86/kernel/cpu/sgx/sgx.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81081063)
Location: arch/x86/kernel/cpu/sgx/sgx.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff810826a5)
Location: arch/x86/kernel/cpu/sgx/sgx.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_free_page
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810904b9)
Location: arch/x86/kernel/cpu/sgx/sgx.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_free_epc_page
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_alloc_va_page
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_access
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_access
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff810915d2)
Location: arch/x86/kernel/cpu/sgx/sgx.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_remove_pages
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_modify_types
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_restrict_permissions
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_etrack
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810940a6)
Location: arch/x86/kernel/cpu/sgx/sgx.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81095125)
Location: arch/x86/kernel/cpu/sgx/sgx.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_free_page
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810933e9)
Location: arch/x86/kernel/cpu/sgx/sgx.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_free_epc_page
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_alloc_va_page
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_access
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_access
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81094512)
Location: arch/x86/kernel/cpu/sgx/sgx.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_remove_pages
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_modify_types
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_restrict_permissions
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_etrack
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81097030)
Location: arch/x86/kernel/cpu/sgx/sgx.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff810980a5)
Location: arch/x86/kernel/cpu/sgx/sgx.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_free_page
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109a859)
Location: arch/x86/kernel/cpu/sgx/sgx.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_free_epc_page
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_alloc_va_page
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_access
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_access
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8109b9f2)
Location: arch/x86/kernel/cpu/sgx/sgx.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_remove_pages
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_modify_types
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_restrict_permissions
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_etrack
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109e5a0)
Location: arch/x86/kernel/cpu/sgx/sgx.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff8109f645)
Location: arch/x86/kernel/cpu/sgx/sgx.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_free_page
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
