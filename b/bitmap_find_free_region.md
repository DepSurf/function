# Function: <code>bitmap_find_free_region</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int bitmap_find_free_region(long unsigned int *bitmap, unsigned int bits, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff813f9250)
Location: lib/bitmap.c:1012
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff813f9250-ffffffff813f92c6: bitmap_find_free_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int bitmap_find_free_region(long unsigned int *bitmap, unsigned int bits, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81440130)
Location: lib/bitmap.c:1014
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff81440130-ffffffff814401a6: bitmap_find_free_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bitmap_find_free_region(long unsigned int *bitmap, unsigned int bits, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8145d230)
Location: lib/bitmap.c:1056
Inline: False
Direct callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff8145d230-ffffffff8145d2a6: bitmap_find_free_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bitmap_find_free_region(long unsigned int *bitmap, unsigned int bits, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff814624c0)
Location: lib/bitmap.c:1062
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff814624c0-ffffffff81462535: bitmap_find_free_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bitmap_find_free_region(long unsigned int *bitmap, unsigned int bits, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8148e3a0)
Location: lib/bitmap.c:1058
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff8148e3a0-ffffffff8148e415: bitmap_find_free_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int bitmap_find_free_region(long unsigned int *bitmap, unsigned int bits, int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff814c3450)
Location: lib/bitmap.c:1055
Inline: True
Direct callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff814c3450-ffffffff814c34c5: bitmap_find_free_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int bitmap_find_free_region(long unsigned int *bitmap, unsigned int bits, int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff814d7f20)
Location: lib/bitmap.c:1050
Inline: True
Direct callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff814d7f20-ffffffff814d7f95: bitmap_find_free_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bitmap_find_free_region(long unsigned int *bitmap, unsigned int bits, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81503590)
Location: lib/bitmap.c:1078
Inline: False
Direct callers:
  - kernel/dma/coherent.c:__dma_alloc_from_coherent
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff81503590-ffffffff81503618: bitmap_find_free_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bitmap_find_free_region(long unsigned int *bitmap, unsigned int bits, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81521530)
Location: lib/bitmap.c:1098
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff81521530-ffffffff815215b8: bitmap_find_free_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bitmap_find_free_region(long unsigned int *bitmap, unsigned int bits, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81584d70)
Location: lib/bitmap.c:1173
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/iommu/intel/irq_remapping.c:alloc_irte
```
**Symbols:**

```
ffffffff81584d70-ffffffff81584e1d: bitmap_find_free_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bitmap_find_free_region(long unsigned int *bitmap, unsigned int bits, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815a1e70)
Location: lib/bitmap.c:1173
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff815a1e70-ffffffff815a1f1d: bitmap_find_free_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bitmap_find_free_region(long unsigned int *bitmap, unsigned int bits, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815a8d80)
Location: lib/bitmap.c:1184
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff815a8d80-ffffffff815a8e24: bitmap_find_free_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int bitmap_find_free_region(long unsigned int *bitmap, unsigned int bits, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/bitmap.c (0)
Location: lib/bitmap.c:1315
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff81cda796-ffffffff81cda7b0: bitmap_find_free_region.cold (STB_LOCAL)
ffffffff81611850-ffffffff816118e2: bitmap_find_free_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int bitmap_find_free_region(long unsigned int *bitmap, unsigned int bits, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/bitmap.c (0)
Location: lib/bitmap.c:1332
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff81e92ddb-ffffffff81e92df4: bitmap_find_free_region.cold (STB_LOCAL)
ffffffff816dda30-ffffffff816ddad2: bitmap_find_free_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int bitmap_find_free_region(long unsigned int *bitmap, unsigned int bits, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/bitmap.c (0)
Location: lib/bitmap.c:1313
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff82077fbe-ffffffff82077fd7: bitmap_find_free_region.cold (STB_LOCAL)
ffffffff817cd9b0-ffffffff817cda52: bitmap_find_free_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int bitmap_find_free_region(long unsigned int *bitmap, unsigned int bits, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/bitmap.c (0)
Location: lib/bitmap.c:1313
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff820f82ef-ffffffff820f8308: bitmap_find_free_region.cold (STB_LOCAL)
ffffffff8180be30-ffffffff8180bed2: bitmap_find_free_region (STB_GLOBAL)
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
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff819b1774)
Location: include/linux/bitmap.h:547
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff819b47af)
Location: include/linux/bitmap.h:547
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b6e84f)
Location: include/linux/bitmap.h:547
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:alloc_irte
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
int bitmap_find_free_region(long unsigned int *bitmap, unsigned int bits, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffff80001062ac58)
Location: lib/bitmap.c:1098
Inline: False
Direct callers:
  - kernel/dma/coherent.c:__dma_alloc_from_coherent
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_irq_domain_alloc
  - drivers/irqchip/irq-gic-v3-mbi.c:mbi_irq_domain_alloc
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_alloc
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/controller/pcie-rcar.c:rcar_msi_setup_irqs
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_irq_domain_alloc
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__event_add
```
**Symbols:**

```
ffff80001062ac58-ffff80001062ace0: bitmap_find_free_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bitmap_find_free_region(long unsigned int *bitmap, unsigned int bits, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (c07d1e94)
Location: lib/bitmap.c:1098
Inline: False
Direct callers:
  - kernel/dma/coherent.c:__dma_alloc_from_coherent
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_irq_domain_alloc
  - drivers/irqchip/irq-gic-v3-mbi.c:mbi_irq_domain_alloc
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_alloc
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_alloc
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/controller/pcie-rcar.c:rcar_msi_setup_irqs
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
```
**Symbols:**

```
c07d1e94-c07d1f0c: bitmap_find_free_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bitmap_find_free_region(long unsigned int *bitmap, unsigned int bits, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (c0000000007cce80)
Location: lib/bitmap.c:1098
Inline: False
Direct callers:
  - kernel/dma/coherent.c:__dma_alloc_from_coherent
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
```
**Symbols:**

```
c0000000007cce80-c0000000007ccf80: bitmap_find_free_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bitmap_find_free_region(long unsigned int *bitmap, unsigned int bits, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffe00045b556)
Location: lib/bitmap.c:1098
Inline: False
Direct callers:
  - kernel/dma/coherent.c:__dma_alloc_from_coherent
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
```
**Symbols:**

```
ffffffe00045b556-ffffffe00045b5d4: bitmap_find_free_region (STB_GLOBAL)
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
int bitmap_find_free_region(long unsigned int *bitmap, unsigned int bits, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81519b10)
Location: lib/bitmap.c:1098
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff81519b10-ffffffff81519b98: bitmap_find_free_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bitmap_find_free_region(long unsigned int *bitmap, unsigned int bits, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81509e00)
Location: lib/bitmap.c:1098
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff81509e00-ffffffff81509e88: bitmap_find_free_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bitmap_find_free_region(long unsigned int *bitmap, unsigned int bits, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81515ba0)
Location: lib/bitmap.c:1098
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff81515ba0-ffffffff81515c28: bitmap_find_free_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bitmap_find_free_region(long unsigned int *bitmap, unsigned int bits, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8152f330)
Location: lib/bitmap.c:1098
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff8152f330-ffffffff8152f3b8: bitmap_find_free_region (STB_GLOBAL)
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
