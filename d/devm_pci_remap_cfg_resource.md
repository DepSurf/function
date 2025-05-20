# Function: <code>devm_pci_remap_cfg_resource</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void *devm_pci_remap_cfg_resource(struct device *dev, struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ac670)
Location: drivers/pci/pci.c:3509
Inline: True
```
**Symbols:**

```
ffffffff814ac670-ffffffff814ac760: devm_pci_remap_cfg_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void *devm_pci_remap_cfg_resource(struct device *dev, struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814eb760)
Location: drivers/pci/pci.c:3524
Inline: True
```
**Symbols:**

```
ffffffff814eb760-ffffffff814eb850: devm_pci_remap_cfg_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void *devm_pci_remap_cfg_resource(struct device *dev, struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151b150)
Location: drivers/pci/pci.c:3708
Inline: True
```
**Symbols:**

```
ffffffff8151b150-ffffffff8151b244: devm_pci_remap_cfg_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void *devm_pci_remap_cfg_resource(struct device *dev, struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81531000)
Location: drivers/pci/pci.c:3973
Inline: True
```
**Symbols:**

```
ffffffff81531000-ffffffff815310f4: devm_pci_remap_cfg_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void *devm_pci_remap_cfg_resource(struct device *dev, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4071
Inline: False
```
**Symbols:**

```
ffffffff81564985-ffffffff815649f2: devm_pci_remap_cfg_resource.cold (STB_LOCAL)
ffffffff8155f220-ffffffff8155f2be: devm_pci_remap_cfg_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void *devm_pci_remap_cfg_resource(struct device *dev, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4067
Inline: False
```
**Symbols:**

```
ffffffff81585cb5-ffffffff81585d22: devm_pci_remap_cfg_resource.cold (STB_LOCAL)
ffffffff81580360-ffffffff815803fe: devm_pci_remap_cfg_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void *devm_pci_remap_cfg_resource(struct device *dev, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4138
Inline: False
```
**Symbols:**

```
ffffffff8162ca32-ffffffff8162ca9f: devm_pci_remap_cfg_resource.cold (STB_LOCAL)
ffffffff81625890-ffffffff8162592e: devm_pci_remap_cfg_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void *devm_pci_remap_cfg_resource(struct device *dev, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4206
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
**Symbols:**

```
ffffffff81bf7c10-ffffffff81bf7c7d: devm_pci_remap_cfg_resource.cold (STB_LOCAL)
ffffffff8164b690-ffffffff8164b773: devm_pci_remap_cfg_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void *devm_pci_remap_cfg_resource(struct device *dev, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4238
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
**Symbols:**

```
ffffffff81be9ab7-ffffffff81be9b24: devm_pci_remap_cfg_resource.cold (STB_LOCAL)
ffffffff8162e270-ffffffff8162e353: devm_pci_remap_cfg_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *devm_pci_remap_cfg_resource(struct device *dev, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4288
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
**Symbols:**

```
ffffffff81ce4424-ffffffff81ce4491: devm_pci_remap_cfg_resource.cold (STB_LOCAL)
ffffffff8169d530-ffffffff8169d613: devm_pci_remap_cfg_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *devm_pci_remap_cfg_resource(struct device *dev, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4384
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
**Symbols:**

```
ffffffff81eaae58-ffffffff81eaaec4: devm_pci_remap_cfg_resource.cold (STB_LOCAL)
ffffffff817bf840-ffffffff817bf929: devm_pci_remap_cfg_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void *devm_pci_remap_cfg_resource(struct device *dev, struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818dca40)
Location: drivers/pci/pci.c:4327
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_get_resources
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_get_resources
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
**Symbols:**

```
ffffffff818dca40-ffffffff818dcb84: devm_pci_remap_cfg_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void *devm_pci_remap_cfg_resource(struct device *dev, struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8191fd20)
Location: drivers/pci/pci.c:4365
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_get_resources
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_get_resources
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
**Symbols:**

```
ffffffff8191fd20-ffffffff8191fe64: devm_pci_remap_cfg_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void *devm_pci_remap_cfg_resource(struct device *dev, struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81967f00)
Location: drivers/pci/pci.c:4475
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_get_resources
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_get_resources
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
**Symbols:**

```
ffffffff81967f00-ffffffff81968044: devm_pci_remap_cfg_resource (STB_GLOBAL)
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
void *devm_pci_remap_cfg_resource(struct device *dev, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e5b88)
Location: drivers/pci/pci.c:4067
Inline: False
Direct callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_probe
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_probe
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_probe
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_probe
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe
  - drivers/pci/controller/dwc/pci-layerscape.c:ls_pcie_probe
  - drivers/pci/controller/dwc/pci-layerscape-ep.c:ls_pcie_ep_probe
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
  - drivers/pci/controller/dwc/pcie-al.c:al_pcie_probe
  - drivers/pci/controller/dwc/pcie-al.c:al_pcie_init
  - drivers/pci/controller/dwc/pcie-hisi.c:hisi_pcie_probe
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_probe
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_ecam_init
```
**Symbols:**

```
ffff8000106e5b88-ffff8000106e5c8c: devm_pci_remap_cfg_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *devm_pci_remap_cfg_resource(struct device *dev, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c087ec10)
Location: drivers/pci/pci.c:4067
Inline: False
Direct callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_parse_dt
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
  - drivers/pci/controller/dwc/pci-layerscape-ep.c:ls_pcie_ep_probe
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe
```
**Symbols:**

```
c087ec10-c087ed20: devm_pci_remap_cfg_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *devm_pci_remap_cfg_resource(struct device *dev, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c00000000085c9f0)
Location: drivers/pci/pci.c:4067
Inline: False
Direct callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
```
**Symbols:**

```
c00000000085c9f0-c00000000085cb64: devm_pci_remap_cfg_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *devm_pci_remap_cfg_resource(struct device *dev, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004ba6ca)
Location: drivers/pci/pci.c:4067
Inline: False
Direct callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
```
**Symbols:**

```
ffffffe0004ba6ca-ffffffe0004ba7ac: devm_pci_remap_cfg_resource (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void *devm_pci_remap_cfg_resource(struct device *dev, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4067
Inline: False
```
**Symbols:**

```
ffffffff8157a1d5-ffffffff8157a242: devm_pci_remap_cfg_resource.cold (STB_LOCAL)
ffffffff81574880-ffffffff8157491e: devm_pci_remap_cfg_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void *devm_pci_remap_cfg_resource(struct device *dev, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4067
Inline: False
```
**Symbols:**

```
ffffffff81568915-ffffffff81568982: devm_pci_remap_cfg_resource.cold (STB_LOCAL)
ffffffff81562fe0-ffffffff8156307e: devm_pci_remap_cfg_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void *devm_pci_remap_cfg_resource(struct device *dev, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4067
Inline: False
```
**Symbols:**

```
ffffffff81579a05-ffffffff81579a72: devm_pci_remap_cfg_resource.cold (STB_LOCAL)
ffffffff815740b0-ffffffff8157414e: devm_pci_remap_cfg_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void *devm_pci_remap_cfg_resource(struct device *dev, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4067
Inline: False
```
**Symbols:**

```
ffffffff81593eb5-ffffffff81593f22: devm_pci_remap_cfg_resource.cold (STB_LOCAL)
ffffffff8158e590-ffffffff8158e62e: devm_pci_remap_cfg_resource (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
