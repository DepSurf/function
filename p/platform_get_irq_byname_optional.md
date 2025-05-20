# Function: <code>platform_get_irq_byname_optional</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int platform_get_irq_byname_optional(struct platform_device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81701ce0)
Location: drivers/base/platform.c:296
Inline: False
```
**Symbols:**

```
ffffffff81701ce0-ffffffff81701d06: platform_get_irq_byname_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int platform_get_irq_byname_optional(struct platform_device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817bc780)
Location: drivers/base/platform.c:355
Inline: False
```
**Symbols:**

```
ffffffff817bc780-ffffffff817bc81c: platform_get_irq_byname_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int platform_get_irq_byname_optional(struct platform_device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817d1480)
Location: drivers/base/platform.c:507
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
**Symbols:**

```
ffffffff817d1480-ffffffff817d151c: platform_get_irq_byname_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int platform_get_irq_byname_optional(struct platform_device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817b4eb0)
Location: drivers/base/platform.c:506
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
**Symbols:**

```
ffffffff817b4eb0-ffffffff817b4f4c: platform_get_irq_byname_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int platform_get_irq_byname_optional(struct platform_device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8183e3a0)
Location: drivers/base/platform.c:486
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
**Symbols:**

```
ffffffff8183e3a0-ffffffff8183e43c: platform_get_irq_byname_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int platform_get_irq_byname_optional(struct platform_device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff819811e0)
Location: drivers/base/platform.c:491
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
**Symbols:**

```
ffffffff819811e0-ffffffff81981281: platform_get_irq_byname_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int platform_get_irq_byname_optional(struct platform_device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81aef5d0)
Location: drivers/base/platform.c:491
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_host_init
```
**Symbols:**

```
ffffffff81aef5d0-ffffffff81aef5e8: platform_get_irq_byname_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int platform_get_irq_byname_optional(struct platform_device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81b3d9b0)
Location: drivers/base/platform.c:489
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_edma_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_edma_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_edma_irq_vector
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_edma_irq_vector
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_host_init
```
**Symbols:**

```
ffffffff81b3d9b0-ffffffff81b3d9c8: platform_get_irq_byname_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int platform_get_irq_byname_optional(struct platform_device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81b954f0)
Location: drivers/base/platform.c:490
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_edma_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_edma_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_edma_irq_vector
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_edma_irq_vector
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_host_init
```
**Symbols:**

```
ffffffff81b954f0-ffffffff81b95508: platform_get_irq_byname_optional (STB_GLOBAL)
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
int platform_get_irq_byname_optional(struct platform_device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffff8000108ed1a0)
Location: drivers/base/platform.c:296
Inline: False
Direct callers:
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_probe
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_probe
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_probe
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_init
```
**Symbols:**

```
ffff8000108ed1a0-ffff8000108ed1d4: platform_get_irq_byname_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int platform_get_irq_byname_optional(struct platform_device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (c09db118)
Location: drivers/base/platform.c:296
Inline: False
Direct callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_init
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_probe
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_probe
```
**Symbols:**

```
c09db118-c09db134: platform_get_irq_byname_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int platform_get_irq_byname_optional(struct platform_device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (c0000000009864e0)
Location: drivers/base/platform.c:296
Inline: False
```
**Symbols:**

```
c0000000009864e0-c0000000009864f4: platform_get_irq_byname_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int platform_get_irq_byname_optional(struct platform_device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffe000581042)
Location: drivers/base/platform.c:296
Inline: False
```
**Symbols:**

```
ffffffe000581042-ffffffe000581074: platform_get_irq_byname_optional (STB_GLOBAL)
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
int platform_get_irq_byname_optional(struct platform_device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816c7430)
Location: drivers/base/platform.c:296
Inline: False
```
**Symbols:**

```
ffffffff816c7430-ffffffff816c7456: platform_get_irq_byname_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int platform_get_irq_byname_optional(struct platform_device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816a2730)
Location: drivers/base/platform.c:296
Inline: False
```
**Symbols:**

```
ffffffff816a2730-ffffffff816a2756: platform_get_irq_byname_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int platform_get_irq_byname_optional(struct platform_device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816f59a0)
Location: drivers/base/platform.c:296
Inline: False
```
**Symbols:**

```
ffffffff816f59a0-ffffffff816f59c6: platform_get_irq_byname_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int platform_get_irq_byname_optional(struct platform_device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81710230)
Location: drivers/base/platform.c:296
Inline: False
```
**Symbols:**

```
ffffffff81710230-ffffffff81710256: platform_get_irq_byname_optional (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
