# Function: <code>zap_vma_ptes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int zap_vma_ptes(struct vm_area_struct *vma, long unsigned int address, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811bdec0)
Location: mm/memory.c:1408
Inline: False
```
**Symbols:**

```
ffffffff811bdec0-ffffffff811bdef7: zap_vma_ptes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int zap_vma_ptes(struct vm_area_struct *vma, long unsigned int address, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811d96f0)
Location: mm/memory.c:1441
Inline: False
```
**Symbols:**

```
ffffffff811d96f0-ffffffff811d9727: zap_vma_ptes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int zap_vma_ptes(struct vm_area_struct *vma, long unsigned int address, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811e8b00)
Location: mm/memory.c:1437
Inline: False
```
**Symbols:**

```
ffffffff811e8b00-ffffffff811e8b37: zap_vma_ptes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int zap_vma_ptes(struct vm_area_struct *vma, long unsigned int address, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f3d70)
Location: mm/memory.c:1559
Inline: False
```
**Symbols:**

```
ffffffff811f3d70-ffffffff811f3d9f: zap_vma_ptes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int zap_vma_ptes(struct vm_area_struct *vma, long unsigned int address, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8120ba30)
Location: mm/memory.c:1662
Inline: False
```
**Symbols:**

```
ffffffff8120ba30-ffffffff8120ba5f: zap_vma_ptes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void zap_vma_ptes(struct vm_area_struct *vma, long unsigned int address, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8122c740)
Location: mm/memory.c:1673
Inline: False
```
**Symbols:**

```
ffffffff8122c740-ffffffff8122c768: zap_vma_ptes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void zap_vma_ptes(struct vm_area_struct *vma, long unsigned int address, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8123fdb0)
Location: mm/memory.c:1405
Inline: False
```
**Symbols:**

```
ffffffff8123fdb0-ffffffff8123fdd8: zap_vma_ptes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void zap_vma_ptes(struct vm_area_struct *vma, long unsigned int address, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81251ef0)
Location: mm/memory.c:1377
Inline: False
```
**Symbols:**

```
ffffffff81251ef0-ffffffff81251f18: zap_vma_ptes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void zap_vma_ptes(struct vm_area_struct *vma, long unsigned int address, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812604c0)
Location: mm/memory.c:1382
Inline: False
```
**Symbols:**

```
ffffffff812604c0-ffffffff812604e8: zap_vma_ptes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void zap_vma_ptes(struct vm_area_struct *vma, long unsigned int address, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81290a90)
Location: mm/memory.c:1410
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap_open
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
```
**Symbols:**

```
ffffffff81290a90-ffffffff81290ab8: zap_vma_ptes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void zap_vma_ptes(struct vm_area_struct *vma, long unsigned int address, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129b520)
Location: mm/memory.c:1584
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap_open
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
```
**Symbols:**

```
ffffffff8129b520-ffffffff8129b548: zap_vma_ptes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void zap_vma_ptes(struct vm_area_struct *vma, long unsigned int address, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a0820)
Location: mm/memory.c:1602
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap_fault
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap_fault
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap_open
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
```
**Symbols:**

```
ffffffff812a0820-ffffffff812a0848: zap_vma_ptes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void zap_vma_ptes(struct vm_area_struct *vma, long unsigned int address, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e17b0)
Location: mm/memory.c:1697
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_mmap_fault
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_mmap_fault
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_mmap_open
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock
```
**Symbols:**

```
ffffffff812e17b0-ffffffff812e17d8: zap_vma_ptes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void zap_vma_ptes(struct vm_area_struct *vma, long unsigned int address, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81342320)
Location: mm/memory.c:1791
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_mmap_fault
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_mmap_fault
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_mmap_open
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock
```
**Symbols:**

```
ffffffff81342320-ffffffff81342369: zap_vma_ptes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void zap_vma_ptes(struct vm_area_struct *vma, long unsigned int address, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813ba450)
Location: mm/memory.c:1762
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
```
**Symbols:**

```
ffffffff813ba450-ffffffff813ba499: zap_vma_ptes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void zap_vma_ptes(struct vm_area_struct *vma, long unsigned int address, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813eee10)
Location: mm/memory.c:1778
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
```
**Symbols:**

```
ffffffff813eee10-ffffffff813eee59: zap_vma_ptes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void zap_vma_ptes(struct vm_area_struct *vma, long unsigned int address, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8141a8e0)
Location: mm/memory.c:1811
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
```
**Symbols:**

```
ffffffff8141a8e0-ffffffff8141a929: zap_vma_ptes (STB_GLOBAL)
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
void zap_vma_ptes(struct vm_area_struct *vma, long unsigned int address, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102f77a8)
Location: mm/memory.c:1382
Inline: False
```
**Symbols:**

```
ffff8000102f77a8-ffff8000102f7814: zap_vma_ptes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void zap_vma_ptes(struct vm_area_struct *vma, long unsigned int address, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c05197a8)
Location: mm/memory.c:1382
Inline: False
```
**Symbols:**

```
c05197a8-c05197f4: zap_vma_ptes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void zap_vma_ptes(struct vm_area_struct *vma, long unsigned int address, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003c05e0)
Location: mm/memory.c:1382
Inline: False
```
**Symbols:**

```
c0000000003c05e0-c0000000003c0620: zap_vma_ptes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void zap_vma_ptes(struct vm_area_struct *vma, long unsigned int address, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe000207d8a)
Location: mm/memory.c:1382
Inline: False
```
**Symbols:**

```
ffffffe000207d8a-ffffffe000207dde: zap_vma_ptes (STB_GLOBAL)
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
void zap_vma_ptes(struct vm_area_struct *vma, long unsigned int address, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81258b10)
Location: mm/memory.c:1382
Inline: False
```
**Symbols:**

```
ffffffff81258b10-ffffffff81258b38: zap_vma_ptes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void zap_vma_ptes(struct vm_area_struct *vma, long unsigned int address, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124afd0)
Location: mm/memory.c:1382
Inline: False
```
**Symbols:**

```
ffffffff8124afd0-ffffffff8124aff8: zap_vma_ptes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void zap_vma_ptes(struct vm_area_struct *vma, long unsigned int address, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812568b0)
Location: mm/memory.c:1382
Inline: False
```
**Symbols:**

```
ffffffff812568b0-ffffffff812568d8: zap_vma_ptes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void zap_vma_ptes(struct vm_area_struct *vma, long unsigned int address, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81266330)
Location: mm/memory.c:1382
Inline: False
```
**Symbols:**

```
ffffffff81266330-ffffffff81266358: zap_vma_ptes (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
