# Function: <code>bitmap_release_region</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void bitmap_release_region(long unsigned int *bitmap, unsigned int pos, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff813f92d0)
Location: lib/bitmap.c:1037
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff813f92d0-ffffffff813f92e0: bitmap_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void bitmap_release_region(long unsigned int *bitmap, unsigned int pos, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff814401b0)
Location: lib/bitmap.c:1039
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff814401b0-ffffffff814401c0: bitmap_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void bitmap_release_region(long unsigned int *bitmap, unsigned int pos, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8145d2b0)
Location: lib/bitmap.c:1081
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff8145d2b0-ffffffff8145d2c0: bitmap_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void bitmap_release_region(long unsigned int *bitmap, unsigned int pos, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81462540)
Location: lib/bitmap.c:1087
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff81462540-ffffffff81462550: bitmap_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void bitmap_release_region(long unsigned int *bitmap, unsigned int pos, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8148e420)
Location: lib/bitmap.c:1083
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff8148e420-ffffffff8148e430: bitmap_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void bitmap_release_region(long unsigned int *bitmap, unsigned int pos, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff814c30a0)
Location: lib/bitmap.c:1080
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff814c30a0-ffffffff814c30b0: bitmap_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bitmap_release_region(long unsigned int *bitmap, unsigned int pos, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff814d7750)
Location: lib/bitmap.c:1075
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff814d7750-ffffffff814d7760: bitmap_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bitmap_release_region(long unsigned int *bitmap, unsigned int pos, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81503620)
Location: lib/bitmap.c:1103
Inline: False
Direct callers:
  - kernel/dma/coherent.c:__dma_release_from_coherent
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff81503620-ffffffff81503630: bitmap_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bitmap_release_region(long unsigned int *bitmap, unsigned int pos, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815215c0)
Location: lib/bitmap.c:1123
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff815215c0-ffffffff815215d0: bitmap_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bitmap_release_region(long unsigned int *bitmap, unsigned int pos, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81584e20)
Location: lib/bitmap.c:1198
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/iommu/intel/irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff81584e20-ffffffff81584e79: bitmap_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bitmap_release_region(long unsigned int *bitmap, unsigned int pos, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815a1f20)
Location: lib/bitmap.c:1198
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/iommu/intel/irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff815a1f20-ffffffff815a1f79: bitmap_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bitmap_release_region(long unsigned int *bitmap, unsigned int pos, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815a8e30)
Location: lib/bitmap.c:1209
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/iommu/intel/irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff815a8e30-ffffffff815a8e88: bitmap_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bitmap_release_region(long unsigned int *bitmap, unsigned int pos, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81611800)
Location: lib/bitmap.c:1340
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/iommu/intel/irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff81611800-ffffffff81611810: bitmap_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bitmap_release_region(long unsigned int *bitmap, unsigned int pos, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff816dd9c0)
Location: lib/bitmap.c:1357
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/iommu/intel/irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff816dd9c0-ffffffff816dd9de: bitmap_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bitmap_release_region(long unsigned int *bitmap, unsigned int pos, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff817cd920)
Location: lib/bitmap.c:1338
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/iommu/intel/irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff817cd920-ffffffff817cd93e: bitmap_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bitmap_release_region(long unsigned int *bitmap, unsigned int pos, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8180bda0)
Location: lib/bitmap.c:1338
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/iommu/intel/irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff8180bda0-ffffffff8180bdbe: bitmap_release_region (STB_GLOBAL)
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
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff819b1bf6)
Location: include/linux/bitmap.h:507
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff819b4929)
Location: include/linux/bitmap.h:507
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b6e9e8)
Location: include/linux/bitmap.h:507
Inline: True
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
void bitmap_release_region(long unsigned int *bitmap, unsigned int pos, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffff80001062ace0)
Location: lib/bitmap.c:1123
Inline: False
Direct callers:
  - kernel/dma/coherent.c:__dma_release_from_coherent
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_free
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_free
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_irq_domain_free
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__event_del
```
**Symbols:**

```
ffff80001062ace0-ffff80001062acf8: bitmap_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bitmap_release_region(long unsigned int *bitmap, unsigned int pos, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (c07d1f0c)
Location: lib/bitmap.c:1123
Inline: False
Direct callers:
  - kernel/dma/coherent.c:__dma_release_from_coherent
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_unalloc_msi
  - drivers/irqchip/irq-gic-v3-mbi.c:mbi_free_msi
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_free
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_free
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
```
**Symbols:**

```
c07d1f0c-c07d1f24: bitmap_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bitmap_release_region(long unsigned int *bitmap, unsigned int pos, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (c0000000007ccf80)
Location: lib/bitmap.c:1123
Inline: False
Direct callers:
  - arch/powerpc/sysdev/msi_bitmap.c:msi_bitmap_reserve_dt_hwirqs
  - kernel/dma/coherent.c:__dma_release_from_coherent
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
```
**Symbols:**

```
c0000000007ccf80-c0000000007ccf90: bitmap_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bitmap_release_region(long unsigned int *bitmap, unsigned int pos, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffe00045b5d4)
Location: lib/bitmap.c:1123
Inline: False
Direct callers:
  - kernel/dma/coherent.c:__dma_release_from_coherent
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
```
**Symbols:**

```
ffffffe00045b5d4-ffffffe00045b5ee: bitmap_release_region (STB_GLOBAL)
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
void bitmap_release_region(long unsigned int *bitmap, unsigned int pos, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81519ba0)
Location: lib/bitmap.c:1123
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff81519ba0-ffffffff81519bb0: bitmap_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bitmap_release_region(long unsigned int *bitmap, unsigned int pos, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81509e90)
Location: lib/bitmap.c:1123
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff81509e90-ffffffff81509ea0: bitmap_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bitmap_release_region(long unsigned int *bitmap, unsigned int pos, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81515c30)
Location: lib/bitmap.c:1123
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff81515c30-ffffffff81515c40: bitmap_release_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bitmap_release_region(long unsigned int *bitmap, unsigned int pos, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8152f3c0)
Location: lib/bitmap.c:1123
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff8152f3c0-ffffffff8152f3d0: bitmap_release_region (STB_GLOBAL)
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
