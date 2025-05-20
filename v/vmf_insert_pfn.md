# Function: <code>vmf_insert_pfn</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81244580)
Location: mm/memory.c:1643
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
**Symbols:**

```
ffffffff81244580-ffffffff81244594: vmf_insert_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81256540)
Location: mm/memory.c:1696
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
**Symbols:**

```
ffffffff81256540-ffffffff81256554: vmf_insert_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81264ad0)
Location: mm/memory.c:1701
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
**Symbols:**

```
ffffffff81264ad0-ffffffff81264ae4: vmf_insert_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81292d50)
Location: mm/memory.c:1867
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
**Symbols:**

```
ffffffff81292d50-ffffffff81292d64: vmf_insert_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129d5f0)
Location: mm/memory.c:2041
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault
```
**Symbols:**

```
ffffffff8129d5f0-ffffffff8129d604: vmf_insert_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a2c20)
Location: mm/memory.c:2059
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
```
**Symbols:**

```
ffffffff812a2c20-ffffffff812a2c34: vmf_insert_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e6090)
Location: mm/memory.c:2154
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
```
**Symbols:**

```
ffffffff812e6090-ffffffff812e60a4: vmf_insert_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81345690)
Location: mm/memory.c:2247
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
```
**Symbols:**

```
ffffffff81345690-ffffffff813456b0: vmf_insert_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813bd9d0)
Location: mm/memory.c:2218
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
```
**Symbols:**

```
ffffffff813bd9d0-ffffffff813bd9f0: vmf_insert_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813f26d0)
Location: mm/memory.c:2251
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
```
**Symbols:**

```
ffffffff813f26d0-ffffffff813f26f0: vmf_insert_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8141d410)
Location: mm/memory.c:2274
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
  - drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_fault
```
**Symbols:**

```
ffffffff8141d410-ffffffff8141d430: vmf_insert_pfn (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102fb760)
Location: mm/memory.c:1701
Inline: False
```
**Symbols:**

```
ffff8000102fb760-ffff8000102fb7a8: vmf_insert_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0519f8c)
Location: mm/memory.c:1701
Inline: False
```
**Symbols:**

```
c0519f8c-c0519fac: vmf_insert_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003c67e0)
Location: mm/memory.c:1701
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_nvlink2.c:vfio_pci_nvgpu_mmap_fault
```
**Symbols:**

```
c0000000003c67e0-c0000000003c67f8: vmf_insert_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe00020ae22)
Location: mm/memory.c:1701
Inline: False
```
**Symbols:**

```
ffffffe00020ae22-ffffffe00020ae60: vmf_insert_pfn (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125d120)
Location: mm/memory.c:1701
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
**Symbols:**

```
ffffffff8125d120-ffffffff8125d134: vmf_insert_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124f580)
Location: mm/memory.c:1701
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
**Symbols:**

```
ffffffff8124f580-ffffffff8124f594: vmf_insert_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125aec0)
Location: mm/memory.c:1701
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
**Symbols:**

```
ffffffff8125aec0-ffffffff8125aed4: vmf_insert_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
vm_fault_t vmf_insert_pfn(struct vm_area_struct *vma, long unsigned int addr, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8126a890)
Location: mm/memory.c:1701
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
**Symbols:**

```
ffffffff8126a890-ffffffff8126a8a4: vmf_insert_pfn (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
