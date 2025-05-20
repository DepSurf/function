# Function: <code>early_set_mem_enc_dec_hypercall</code>

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
void early_set_mem_enc_dec_hypercall(long unsigned int vaddr, int npages, bool enc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff83476dd3)
Location: arch/x86/mm/mem_encrypt_amd.c:482
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_init_platform
```
**Symbols:**

```
ffffffff83477046-ffffffff8347705e: early_set_mem_enc_dec_hypercall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void early_set_mem_enc_dec_hypercall(long unsigned int vaddr, int npages, bool enc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff83ea003e)
Location: arch/x86/mm/mem_encrypt_amd.c:483
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_init_platform
```
**Symbols:**

```
ffffffff83ea0480-ffffffff83ea0498: early_set_mem_enc_dec_hypercall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void early_set_mem_enc_dec_hypercall(long unsigned int vaddr, long unsigned int size, bool enc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff836c41c1)
Location: arch/x86/mm/mem_encrypt_amd.c:484
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_init_platform
```
**Symbols:**

```
ffffffff836c4600-ffffffff836c4618: early_set_mem_enc_dec_hypercall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void early_set_mem_enc_dec_hypercall(long unsigned int vaddr, long unsigned int size, bool enc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff838f4e41)
Location: arch/x86/mm/mem_encrypt_amd.c:449
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_init_platform
```
**Symbols:**

```
ffffffff838f5200-ffffffff838f5218: early_set_mem_enc_dec_hypercall (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int size</code>
</li>
<li>
<b>Param removed. </b>
<code>int npages</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
