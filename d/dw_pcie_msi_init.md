# Function: <code>dw_pcie_msi_init</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dw_pcie_msi_init(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host/pcie-designware.c (ffffffff814a5330)
Location: drivers/pci/host/pcie-designware.c:211
Inline: False
Direct callers:
  - drivers/pci/host/pcie-designware-plat.c:dw_plat_pcie_host_init
```
**Symbols:**

```
ffffffff814a5330-ffffffff814a53a9: dw_pcie_msi_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dw_pcie_msi_init(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host/pcie-designware.c (ffffffff814c7600)
Location: drivers/pci/host/pcie-designware.c:285
Inline: False
Direct callers:
  - drivers/pci/host/pcie-designware-plat.c:dw_plat_pcie_host_init
```
**Symbols:**

```
ffffffff814c7600-ffffffff814c7679: dw_pcie_msi_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dw_pcie_msi_init(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/dwc/pcie-designware-host.c (ffffffff814d3810)
Location: drivers/pci/dwc/pcie-designware-host.c:84
Inline: False
Direct callers:
  - drivers/pci/dwc/pcie-designware-plat.c:dw_plat_pcie_host_init
```
**Symbols:**

```
ffffffff814d3810-ffffffff814d3889: dw_pcie_msi_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dw_pcie_msi_init(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/dwc/pcie-designware-host.c (ffffffff81513be0)
Location: drivers/pci/dwc/pcie-designware-host.c:84
Inline: False
Direct callers:
  - drivers/pci/dwc/pcie-designware-plat.c:dw_plat_pcie_host_init
```
**Symbols:**

```
ffffffff81513be0-ffffffff81513c59: dw_pcie_msi_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dw_pcie_msi_init(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff81549500)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:302
Inline: False
```
**Symbols:**

```
ffffffff81549500-ffffffff81549636: dw_pcie_msi_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dw_pcie_msi_init(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8155fc00)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:308
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_host_init
```
**Symbols:**

```
ffffffff8155fc00-ffffffff8155fce4: dw_pcie_msi_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void dw_pcie_msi_init(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:291
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_host_init
```
**Symbols:**

```
ffffffff81590541-ffffffff81590570: dw_pcie_msi_init.cold (STB_LOCAL)
ffffffff8158fec0-ffffffff8158ff86: dw_pcie_msi_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void dw_pcie_msi_init(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:292
Inline: False
```
**Symbols:**

```
ffffffff815b2271-ffffffff815b22a0: dw_pcie_msi_init.cold (STB_LOCAL)
ffffffff815b1ee0-ffffffff815b1fa6: dw_pcie_msi_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void dw_pcie_msi_init(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:295
Inline: False
```
**Symbols:**

```
ffffffff8165bc43-ffffffff8165bc72: dw_pcie_msi_init.cold (STB_LOCAL)
ffffffff8165b4c0-ffffffff8165b5eb: dw_pcie_msi_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8167c123)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:278
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8165e83a)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:276
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff816d13d3)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:275
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff817fa45c)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:275
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff81926ba1)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:271
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8196ad71)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:271
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff819b4531)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:273
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
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
void dw_pcie_msi_init(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffff80001072e3f0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:292
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_host_init
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_host_init
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_host_init
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_host_init
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_host_init
```
**Symbols:**

```
ffff80001072e3f0-ffff80001072e4d4: dw_pcie_msi_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dw_pcie_msi_init(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (c08b7c6c)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:292
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_host_init
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_host_init
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_host_init
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_host_init
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_host_init
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_host_init
```
**Symbols:**

```
c08b7c6c-c08b7d70: dw_pcie_msi_init (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dw_pcie_msi_init(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffe0004e8b60)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:292
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_host_init
```
**Symbols:**

```
ffffffe0004e8b60-ffffffe0004e8c2e: dw_pcie_msi_init (STB_GLOBAL)
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
void dw_pcie_msi_init(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:292
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_host_init
```
**Symbols:**

```
ffffffff815a5a31-ffffffff815a5a60: dw_pcie_msi_init.cold (STB_LOCAL)
ffffffff815a56a0-ffffffff815a5766: dw_pcie_msi_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void dw_pcie_msi_init(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:292
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_host_init
```
**Symbols:**

```
ffffffff81594bd1-ffffffff81594c00: dw_pcie_msi_init.cold (STB_LOCAL)
ffffffff81594840-ffffffff81594906: dw_pcie_msi_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void dw_pcie_msi_init(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:292
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_host_init
```
**Symbols:**

```
ffffffff815a5fc1-ffffffff815a5ff0: dw_pcie_msi_init.cold (STB_LOCAL)
ffffffff815a5c30-ffffffff815a5cf6: dw_pcie_msi_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void dw_pcie_msi_init(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:292
Inline: False
```
**Symbols:**

```
ffffffff815c03c1-ffffffff815c03f0: dw_pcie_msi_init.cold (STB_LOCAL)
ffffffff815c0030-ffffffff815c00f6: dw_pcie_msi_init (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
