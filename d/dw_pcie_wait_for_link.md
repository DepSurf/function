# Function: <code>dw_pcie_wait_for_link</code>

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
int dw_pcie_wait_for_link(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host/pcie-designware.c (ffffffff814a53e0)
Location: drivers/pci/host/pcie-designware.c:389
Inline: False
Direct callers:
  - drivers/pci/host/pcie-designware-plat.c:dw_plat_pcie_host_init
```
**Symbols:**

```
ffffffff814a53e0-ffffffff814a5445: dw_pcie_wait_for_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dw_pcie_wait_for_link(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host/pcie-designware.c (ffffffff814c76c0)
Location: drivers/pci/host/pcie-designware.c:463
Inline: False
Direct callers:
  - drivers/pci/host/pcie-designware-plat.c:dw_plat_pcie_host_init
```
**Symbols:**

```
ffffffff814c76c0-ffffffff814c7725: dw_pcie_wait_for_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dw_pcie_wait_for_link(struct dw_pcie *pci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/dwc/pcie-designware.c (ffffffff814d3610)
Location: drivers/pci/dwc/pcie-designware.c:313
Inline: False
Direct callers:
  - drivers/pci/dwc/pcie-designware-plat.c:dw_plat_pcie_host_init
```
**Symbols:**

```
ffffffff814d3610-ffffffff814d3675: dw_pcie_wait_for_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dw_pcie_wait_for_link(struct dw_pcie *pci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/dwc/pcie-designware.c (ffffffff815139f0)
Location: drivers/pci/dwc/pcie-designware.c:315
Inline: False
Direct callers:
  - drivers/pci/dwc/pcie-designware-plat.c:dw_plat_pcie_host_init
```
**Symbols:**

```
ffffffff815139f0-ffffffff81513a55: dw_pcie_wait_for_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dw_pcie_wait_for_link(struct dw_pcie *pci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81548dd0)
Location: drivers/pci/controller/dwc/pcie-designware.c:312
Inline: False
```
**Symbols:**

```
ffffffff81548dd0-ffffffff81548e35: dw_pcie_wait_for_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dw_pcie_wait_for_link(struct dw_pcie *pci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8155f4b0)
Location: drivers/pci/controller/dwc/pcie-designware.c:312
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_host_init
```
**Symbols:**

```
ffffffff8155f4b0-ffffffff8155f515: dw_pcie_wait_for_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dw_pcie_wait_for_link(struct dw_pcie *pci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (0)
Location: drivers/pci/controller/dwc/pcie-designware.c:366
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_host_init
```
**Symbols:**

```
ffffffff8158fc22-ffffffff8158fc50: dw_pcie_wait_for_link.cold (STB_LOCAL)
ffffffff8158fa60-ffffffff8158faa0: dw_pcie_wait_for_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dw_pcie_wait_for_link(struct dw_pcie *pci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815b198a)
Location: drivers/pci/controller/dwc/pcie-designware.c:446
Inline: True
```
**Symbols:**

```
ffffffff815b198a-ffffffff815b19b8: dw_pcie_wait_for_link.cold (STB_LOCAL)
ffffffff815b17d0-ffffffff815b1810: dw_pcie_wait_for_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dw_pcie_wait_for_link(struct dw_pcie *pci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8165b0fa)
Location: drivers/pci/controller/dwc/pcie-designware.c:450
Inline: True
```
**Symbols:**

```
ffffffff8165b0fa-ffffffff8165b128: dw_pcie_wait_for_link.cold (STB_LOCAL)
ffffffff8165a430-ffffffff8165a49a: dw_pcie_wait_for_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dw_pcie_wait_for_link(struct dw_pcie *pci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81bfddbc)
Location: drivers/pci/controller/dwc/pcie-designware.c:461
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
**Symbols:**

```
ffffffff81bfddbc-ffffffff81bfddea: dw_pcie_wait_for_link.cold (STB_LOCAL)
ffffffff8167a980-ffffffff8167a9ea: dw_pcie_wait_for_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dw_pcie_wait_for_link(struct dw_pcie *pci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81befcd6)
Location: drivers/pci/controller/dwc/pcie-designware.c:511
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
**Symbols:**

```
ffffffff81befcd6-ffffffff81befd04: dw_pcie_wait_for_link.cold (STB_LOCAL)
ffffffff8165d370-ffffffff8165d3e1: dw_pcie_wait_for_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dw_pcie_wait_for_link(struct dw_pcie *pci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81ceb32b)
Location: drivers/pci/controller/dwc/pcie-designware.c:511
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
**Symbols:**

```
ffffffff81ceb32b-ffffffff81ceb359: dw_pcie_wait_for_link.cold (STB_LOCAL)
ffffffff816cfde0-ffffffff816cfe56: dw_pcie_wait_for_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dw_pcie_wait_for_link(struct dw_pcie *pci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81eb273c)
Location: drivers/pci/controller/dwc/pcie-designware.c:525
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
**Symbols:**

```
ffffffff81eb273c-ffffffff81eb2774: dw_pcie_wait_for_link.cold (STB_LOCAL)
ffffffff817f8bb0-ffffffff817f8c26: dw_pcie_wait_for_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dw_pcie_wait_for_link(struct dw_pcie *pci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81925160)
Location: drivers/pci/controller/dwc/pcie-designware.c:634
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
**Symbols:**

```
ffffffff81925160-ffffffff8192528f: dw_pcie_wait_for_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dw_pcie_wait_for_link(struct dw_pcie *pci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81968eb0)
Location: drivers/pci/controller/dwc/pcie-designware.c:647
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
**Symbols:**

```
ffffffff81968eb0-ffffffff81968fdf: dw_pcie_wait_for_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dw_pcie_wait_for_link(struct dw_pcie *pci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff819b27e0)
Location: drivers/pci/controller/dwc/pcie-designware.c:648
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_resume_noirq
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
**Symbols:**

```
ffffffff819b27e0-ffffffff819b2880: dw_pcie_wait_for_link (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_wait_for_link(struct dw_pcie *pci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffff80001072d970)
Location: drivers/pci/controller/dwc/pcie-designware.c:446
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_host_init
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_host_init
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_host_init
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_host_init
```
**Symbols:**

```
ffff80001072d970-ffff80001072da04: dw_pcie_wait_for_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_wait_for_link(struct dw_pcie *pci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (c08b7090)
Location: drivers/pci/controller/dwc/pcie-designware.c:446
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_host_init
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_host_init
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_host_init
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_host_init
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_host_init
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_establish_link
```
**Symbols:**

```
c08b7090-c08b7118: dw_pcie_wait_for_link (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_wait_for_link(struct dw_pcie *pci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffe0004e7fd0)
Location: drivers/pci/controller/dwc/pcie-designware.c:446
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_host_init
```
**Symbols:**

```
ffffffe0004e7fd0-ffffffe0004e805a: dw_pcie_wait_for_link (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dw_pcie_wait_for_link(struct dw_pcie *pci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815a514a)
Location: drivers/pci/controller/dwc/pcie-designware.c:446
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_host_init
```
**Symbols:**

```
ffffffff815a514a-ffffffff815a5178: dw_pcie_wait_for_link.cold (STB_LOCAL)
ffffffff815a4f90-ffffffff815a4fd0: dw_pcie_wait_for_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dw_pcie_wait_for_link(struct dw_pcie *pci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815942ea)
Location: drivers/pci/controller/dwc/pcie-designware.c:446
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_host_init
```
**Symbols:**

```
ffffffff815942ea-ffffffff81594318: dw_pcie_wait_for_link.cold (STB_LOCAL)
ffffffff81594130-ffffffff81594170: dw_pcie_wait_for_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dw_pcie_wait_for_link(struct dw_pcie *pci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815a56da)
Location: drivers/pci/controller/dwc/pcie-designware.c:446
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_host_init
```
**Symbols:**

```
ffffffff815a56da-ffffffff815a5708: dw_pcie_wait_for_link.cold (STB_LOCAL)
ffffffff815a5520-ffffffff815a5560: dw_pcie_wait_for_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dw_pcie_wait_for_link(struct dw_pcie *pci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815bfada)
Location: drivers/pci/controller/dwc/pcie-designware.c:446
Inline: True
```
**Symbols:**

```
ffffffff815bfada-ffffffff815bfb08: dw_pcie_wait_for_link.cold (STB_LOCAL)
ffffffff815bf920-ffffffff815bf960: dw_pcie_wait_for_link (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct dw_pcie *pci</code>
</li>
<li>
<b>Param removed. </b>
<code>struct pcie_port *pp</code>
</li>
</ul>
</details>
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
