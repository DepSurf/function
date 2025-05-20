# Function: <code>device_link_add</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct device_link *device_link_add(struct device *consumer, struct device *supplier, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815c7e60)
Location: drivers/base/core.c:177
Inline: False
```
**Symbols:**

```
ffffffff815c7e60-ffffffff815c80fa: device_link_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct device_link *device_link_add(struct device *consumer, struct device *supplier, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815dcae0)
Location: drivers/base/core.c:178
Inline: False
```
**Symbols:**

```
ffffffff815dcae0-ffffffff815dcd82: device_link_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct device_link *device_link_add(struct device *consumer, struct device *supplier, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81643ae0)
Location: drivers/base/core.c:178
Inline: False
```
**Symbols:**

```
ffffffff81643ae0-ffffffff81643d82: device_link_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct device_link *device_link_add(struct device *consumer, struct device *supplier, u32 flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8167eee0)
Location: drivers/base/core.c:195
Inline: True
Direct callers:
  - drivers/pci/quirks.c:quirk_gpu_hda
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
**Symbols:**

```
ffffffff8167eee0-ffffffff8167f195: device_link_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct device_link *device_link_add(struct device *consumer, struct device *supplier, u32 flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169f320)
Location: drivers/base/core.c:196
Inline: True
Direct callers:
  - drivers/pci/quirks.c:quirk_gpu_hda
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/regulator/core.c:_regulator_get
```
**Symbols:**

```
ffffffff8169f320-ffffffff8169f5df: device_link_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct device_link *device_link_add(struct device *consumer, struct device *supplier, u32 flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (ffffffff816d7cd0)
Location: drivers/base/core.c:217
Inline: True
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pwm/core.c:pwm_get
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/regulator/core.c:_regulator_get
```
**Symbols:**

```
ffffffff816d7970-ffffffff816d7ccc: device_link_add.part.0 (STB_LOCAL)
ffffffff816d9185-ffffffff816d91b3: device_link_add.part.0.cold (STB_LOCAL)
ffffffff816d7cd0-ffffffff816d7d67: device_link_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct device_link *device_link_add(struct device *consumer, struct device *supplier, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816fba90)
Location: drivers/base/core.c:288
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pwm/core.c:pwm_get
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/regulator/core.c:_regulator_get
```
**Symbols:**

```
ffffffff816fba90-ffffffff816fbe62: device_link_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct device_link *device_link_add(struct device *consumer, struct device *supplier, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b52b0)
Location: drivers/base/core.c:303
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_get
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pwm/core.c:pwm_get
  - drivers/acpi/acpi_lpss.c:acpi_lpss_link_supplier
  - drivers/acpi/acpi_lpss.c:acpi_lpss_link_consumer
  - drivers/regulator/core.c:_regulator_get
```
**Symbols:**

```
ffffffff817b52b0-ffffffff817b57dc: device_link_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct device_link *device_link_add(struct device *consumer, struct device *supplier, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817c99a0)
Location: drivers/base/core.c:629
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_get
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pwm/core.c:pwm_get
  - drivers/acpi/acpi_lpss.c:acpi_lpss_link_supplier
  - drivers/acpi/acpi_lpss.c:acpi_lpss_link_consumer
  - drivers/regulator/core.c:_regulator_get
  - drivers/base/core.c:fw_devlink_create_devlink
```
**Symbols:**

```
ffffffff817c99a0-ffffffff817ca02d: device_link_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct device_link *device_link_add(struct device *consumer, struct device *supplier, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817ad190)
Location: drivers/base/core.c:673
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_get
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pwm/core.c:pwm_get
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/regulator/core.c:_regulator_get
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:fw_devlink_create_devlink
```
**Symbols:**

```
ffffffff817ad190-ffffffff817ad84d: device_link_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct device_link *device_link_add(struct device *consumer, struct device *supplier, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81836480)
Location: drivers/base/core.c:684
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_get
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pwm/core.c:pwm_get
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/regulator/core.c:_regulator_get
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:fw_devlink_create_devlink
```
**Symbols:**

```
ffffffff81836480-ffffffff81836b34: device_link_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct device_link *device_link_add(struct device *consumer, struct device *supplier, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81978480)
Location: drivers/base/core.c:696
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_get
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pwm/core.c:pwm_get
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/regulator/core.c:_regulator_get
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:fw_devlink_create_devlink
```
**Symbols:**

```
ffffffff81978480-ffffffff81978b7e: device_link_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct device_link *device_link_add(struct device *consumer, struct device *supplier, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae4d00)
Location: drivers/base/core.c:769
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_get
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pwm/core.c:pwm_get
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/net/phy/phy_device.c:phy_attach_direct
```
**Symbols:**

```
ffffffff81ae4d00-ffffffff81ae5476: device_link_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct device_link *device_link_add(struct device *consumer, struct device *supplier, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b33090)
Location: drivers/base/core.c:711
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_get
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pwm/core.c:pwm_get
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/net/phy/phy_device.c:phy_attach_direct
```
**Symbols:**

```
ffffffff81b33090-ffffffff81b33838: device_link_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct device_link *device_link_add(struct device *consumer, struct device *supplier, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b8a9a0)
Location: drivers/base/core.c:714
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_get
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pwm/core.c:pwm_get
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/ata/libata-scsi.c:ata_scsi_slave_alloc
  - drivers/net/phy/phy_device.c:phy_attach_direct
```
**Symbols:**

```
ffffffff81b8a9a0-ffffffff81b8b177: device_link_add (STB_GLOBAL)
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
struct device_link *device_link_add(struct device *consumer, struct device *supplier, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffff8000108e63c8)
Location: drivers/base/core.c:288
Inline: False
Direct callers:
  - drivers/bus/fsl-mc/mc-io.c:fsl_mc_portal_allocate
  - drivers/bus/fsl-mc/fsl-mc-allocator.c:fsl_mc_object_allocate
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_init_phy
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe
  - drivers/regulator/core.c:_regulator_get
  - drivers/iommu/arm-smmu.c:arm_smmu_add_device
  - drivers/iommu/rockchip-iommu.c:rk_iommu_add_device
  - drivers/iommu/qcom_iommu.c:qcom_iommu_add_device
```
**Symbols:**

```
ffff8000108e63c8-ffff8000108e678c: device_link_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct device_link *device_link_add(struct device *consumer, struct device *supplier, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c09d4a08)
Location: drivers/base/core.c:288
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_init_phy
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
  - drivers/soc/imx/gpc.c:imx_pgc_power_domain_probe
  - drivers/regulator/core.c:_regulator_get
  - drivers/iommu/rockchip-iommu.c:rk_iommu_add_device
  - drivers/iommu/exynos-iommu.c:exynos_iommu_add_device
  - drivers/iommu/qcom_iommu.c:qcom_iommu_add_device
```
**Symbols:**

```
c09d4a08-c09d4dbc: device_link_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct device_link *device_link_add(struct device *consumer, struct device *supplier, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c00000000097c0a0)
Location: drivers/base/core.c:288
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_init_phy
  - drivers/regulator/core.c:_regulator_get
```
**Symbols:**

```
c00000000097c0a0-c00000000097c604: device_link_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct device_link *device_link_add(struct device *consumer, struct device *supplier, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffe00057ae42)
Location: drivers/base/core.c:288
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_init_phy
  - drivers/regulator/core.c:_regulator_get
```
**Symbols:**

```
ffffffe00057ae42-ffffffe00057b176: device_link_add (STB_GLOBAL)
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
struct device_link *device_link_add(struct device *consumer, struct device *supplier, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816c1280)
Location: drivers/base/core.c:288
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pwm/core.c:pwm_get
  - drivers/regulator/core.c:_regulator_get
```
**Symbols:**

```
ffffffff816c1280-ffffffff816c1652: device_link_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct device_link *device_link_add(struct device *consumer, struct device *supplier, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169c530)
Location: drivers/base/core.c:288
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/regulator/core.c:_regulator_get
```
**Symbols:**

```
ffffffff8169c530-ffffffff8169c902: device_link_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct device_link *device_link_add(struct device *consumer, struct device *supplier, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816ef750)
Location: drivers/base/core.c:288
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pwm/core.c:pwm_get
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/regulator/core.c:_regulator_get
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_probe
```
**Symbols:**

```
ffffffff816ef750-ffffffff816efb22: device_link_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct device_link *device_link_add(struct device *consumer, struct device *supplier, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81709f90)
Location: drivers/base/core.c:288
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pwm/core.c:pwm_get
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/regulator/core.c:_regulator_get
```
**Symbols:**

```
ffffffff81709f90-ffffffff8170a362: device_link_add (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
