# Function: <code>vmalloc_to_pfn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int vmalloc_to_pfn(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811cc680)
Location: mm/vmalloc.c:268
Inline: False
```
**Symbols:**

```
ffffffff811cc680-ffffffff811cc6a1: vmalloc_to_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int vmalloc_to_pfn(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811e96f0)
Location: mm/vmalloc.c:269
Inline: False
```
**Symbols:**

```
ffffffff811e96f0-ffffffff811e9711: vmalloc_to_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int vmalloc_to_pfn(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811faa40)
Location: mm/vmalloc.c:269
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
**Symbols:**

```
ffffffff811faa40-ffffffff811faa5b: vmalloc_to_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int vmalloc_to_pfn(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81205850)
Location: mm/vmalloc.c:319
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
**Symbols:**

```
ffffffff81205850-ffffffff8120586b: vmalloc_to_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int vmalloc_to_pfn(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8121f8d0)
Location: mm/vmalloc.c:317
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
**Symbols:**

```
ffffffff8121f8d0-ffffffff8121f8eb: vmalloc_to_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int vmalloc_to_pfn(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81241010)
Location: mm/vmalloc.c:317
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
**Symbols:**

```
ffffffff81241010-ffffffff8124102b: vmalloc_to_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int vmalloc_to_pfn(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81254d20)
Location: mm/vmalloc.c:317
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
**Symbols:**

```
ffffffff81254d20-ffffffff81254d3b: vmalloc_to_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int vmalloc_to_pfn(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812670d0)
Location: mm/vmalloc.c:320
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
**Symbols:**

```
ffffffff812670d0-ffffffff812670eb: vmalloc_to_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int vmalloc_to_pfn(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812759d0)
Location: mm/vmalloc.c:320
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
**Symbols:**

```
ffffffff812759d0-ffffffff812759eb: vmalloc_to_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int vmalloc_to_pfn(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812a73e0)
Location: mm/vmalloc.c:401
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_resume
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
**Symbols:**

```
ffffffff812a73e0-ffffffff812a73fb: vmalloc_to_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int vmalloc_to_pfn(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812b2660)
Location: mm/vmalloc.c:400
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_resume
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
**Symbols:**

```
ffffffff812b2660-ffffffff812b267b: vmalloc_to_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int vmalloc_to_pfn(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812b8e80)
Location: mm/vmalloc.c:677
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_resume
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
**Symbols:**

```
ffffffff812b8e80-ffffffff812b8e9b: vmalloc_to_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int vmalloc_to_pfn(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812fb420)
Location: mm/vmalloc.c:705
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_resume
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
**Symbols:**

```
ffffffff812fb420-ffffffff812fb43b: vmalloc_to_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int vmalloc_to_pfn(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81362910)
Location: mm/vmalloc.c:706
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_resume
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/ivm.c:hv_map_memory
  - arch/x86/kernel/ldt.c:map_ldt_struct
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
```
**Symbols:**

```
ffffffff81362910-ffffffff81362931: vmalloc_to_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int vmalloc_to_pfn(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff813de2c0)
Location: mm/vmalloc.c:725
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_resume
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/ivm.c:hv_map_memory
  - arch/x86/kernel/ldt.c:map_ldt_struct
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
```
**Symbols:**

```
ffffffff813de2c0-ffffffff813de2e1: vmalloc_to_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int vmalloc_to_pfn(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81412b30)
Location: mm/vmalloc.c:718
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_resume
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/ldt.c:map_ldt_struct
  - arch/x86/kernel/sev.c:__set_pages_state
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
```
**Symbols:**

```
ffffffff81412b30-ffffffff81412b51: vmalloc_to_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int vmalloc_to_pfn(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8143f5a0)
Location: mm/vmalloc.c:718
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_resume
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/ldt.c:map_ldt_struct
  - arch/x86/kernel/sev.c:__set_pages_state
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
```
**Symbols:**

```
ffffffff8143f5a0-ffffffff8143f5c1: vmalloc_to_pfn (STB_GLOBAL)
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
long unsigned int vmalloc_to_pfn(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffff80001030bdb8)
Location: mm/vmalloc.c:320
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
```
**Symbols:**

```
ffff80001030bdb8-ffff80001030bdf4: vmalloc_to_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int vmalloc_to_pfn(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0527dc0)
Location: mm/vmalloc.c:320
Inline: False
```
**Symbols:**

```
c0527dc0-c0527e08: vmalloc_to_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int vmalloc_to_pfn(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0000000003dbd30)
Location: mm/vmalloc.c:320
Inline: False
Direct callers:
  - arch/powerpc/mm/pgtable.c:vmalloc_to_phys
  - arch/powerpc/platforms/powernv/opal.c:opal_vmalloc_to_sg_list
  - arch/powerpc/platforms/powernv/opal.c:opal_vmalloc_to_sg_list
```
**Symbols:**

```
c0000000003dbd30-c0000000003dbd74: vmalloc_to_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int vmalloc_to_pfn(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffe000215266)
Location: mm/vmalloc.c:320
Inline: False
```
**Symbols:**

```
ffffffe000215266-ffffffe00021529a: vmalloc_to_pfn (STB_GLOBAL)
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
long unsigned int vmalloc_to_pfn(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126e020)
Location: mm/vmalloc.c:320
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
**Symbols:**

```
ffffffff8126e020-ffffffff8126e03b: vmalloc_to_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int vmalloc_to_pfn(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8125ffd0)
Location: mm/vmalloc.c:320
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
**Symbols:**

```
ffffffff8125ffd0-ffffffff8125ffeb: vmalloc_to_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int vmalloc_to_pfn(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126bdc0)
Location: mm/vmalloc.c:320
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
**Symbols:**

```
ffffffff8126bdc0-ffffffff8126bddb: vmalloc_to_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int vmalloc_to_pfn(const void *vmalloc_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8127b7d0)
Location: mm/vmalloc.c:320
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
**Symbols:**

```
ffffffff8127b7d0-ffffffff8127b7eb: vmalloc_to_pfn (STB_GLOBAL)
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
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
