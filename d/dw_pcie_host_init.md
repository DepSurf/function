# Function: <code>dw_pcie_host_init</code>

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
int dw_pcie_host_init(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host/pcie-designware.c (ffffffff814a5450)
Location: drivers/pci/host/pcie-designware.c:431
Inline: False
Direct callers:
  - drivers/pci/host/pcie-designware-plat.c:dw_plat_pcie_probe
```
**Symbols:**

```
ffffffff814a5450-ffffffff814a5503: dw_pcie_host_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dw_pcie_host_init(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host/pcie-designware.c (ffffffff814c7730)
Location: drivers/pci/host/pcie-designware.c:517
Inline: False
Direct callers:
  - drivers/pci/host/pcie-designware-plat.c:dw_plat_pcie_probe
```
**Symbols:**

```
ffffffff814c7730-ffffffff814c77e3: dw_pcie_host_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dw_pcie_host_init(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/dwc/pcie-designware-host.c (ffffffff814d3890)
Location: drivers/pci/dwc/pcie-designware-host.c:276
Inline: False
Direct callers:
  - drivers/pci/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
```
**Symbols:**

```
ffffffff814d3890-ffffffff814d3920: dw_pcie_host_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dw_pcie_host_init(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/dwc/pcie-designware-host.c (ffffffff81513c60)
Location: drivers/pci/dwc/pcie-designware-host.c:276
Inline: False
Direct callers:
  - drivers/pci/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
```
**Symbols:**

```
ffffffff81513c60-ffffffff81513cf0: dw_pcie_host_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dw_pcie_host_init(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff81549640)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:325
Inline: False
```
**Symbols:**

```
ffffffff81549640-ffffffff815496da: dw_pcie_host_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dw_pcie_host_init(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8155fcf0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:331
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
```
**Symbols:**

```
ffffffff8155fcf0-ffffffff8155fd8a: dw_pcie_host_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dw_pcie_host_init(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:316
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
```
**Symbols:**

```
ffffffff8159052d-ffffffff81590541: dw_pcie_host_init.cold (STB_LOCAL)
ffffffff8158fca0-ffffffff8158fd32: dw_pcie_host_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int dw_pcie_host_init(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:317
Inline: False
```
**Symbols:**

```
ffffffff815b225d-ffffffff815b2271: dw_pcie_host_init.cold (STB_LOCAL)
ffffffff815b1a10-ffffffff815b1aa2: dw_pcie_host_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dw_pcie_host_init(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:320
Inline: False
```
**Symbols:**

```
ffffffff8165bc2f-ffffffff8165bc43: dw_pcie_host_init.cold (STB_LOCAL)
ffffffff8165b290-ffffffff8165b325: dw_pcie_host_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dw_pcie_host_init(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:291
Inline: False
```
**Symbols:**

```
ffffffff81bfe1cf-ffffffff81bfe29e: dw_pcie_host_init.cold (STB_LOCAL)
ffffffff8167bf80-ffffffff8167c3e7: dw_pcie_host_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dw_pcie_host_init(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:289
Inline: False
```
**Symbols:**

```
ffffffff81befe38-ffffffff81befe81: dw_pcie_host_init.cold (STB_LOCAL)
ffffffff8165ee40-ffffffff8165f24b: dw_pcie_host_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dw_pcie_host_init(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:288
Inline: False
```
**Symbols:**

```
ffffffff81ceb48d-ffffffff81ceb4eb: dw_pcie_host_init.cold (STB_LOCAL)
ffffffff816d19f0-ffffffff816d1e0a: dw_pcie_host_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dw_pcie_host_init(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:288
Inline: False
```
**Symbols:**

```
ffffffff81eb2878-ffffffff81eb28db: dw_pcie_host_init.cold (STB_LOCAL)
ffffffff817faae0-ffffffff817faf48: dw_pcie_host_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dw_pcie_host_init(struct dw_pcie_rp *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff81927700)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:384
Inline: False
```
**Symbols:**

```
ffffffff81927700-ffffffff81927a5f: dw_pcie_host_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dw_pcie_host_init(struct dw_pcie_rp *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8196b8d0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:394
Inline: False
```
**Symbols:**

```
ffffffff8196b8d0-ffffffff8196bc5b: dw_pcie_host_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dw_pcie_host_init(struct dw_pcie_rp *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff819b53b0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:396
Inline: False
```
**Symbols:**

```
ffffffff819b53b0-ffffffff819b5755: dw_pcie_host_init (STB_GLOBAL)
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
int dw_pcie_host_init(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffff80001072ed00)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:317
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe
  - drivers/pci/controller/dwc/pci-layerscape.c:ls_pcie_probe
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-al.c:al_pcie_probe
  - drivers/pci/controller/dwc/pcie-hisi.c:hisi_pcie_probe
```
**Symbols:**

```
ffff80001072ed00-ffff80001072f2d4: dw_pcie_host_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dw_pcie_host_init(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (c08b81b4)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:317
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe
```
**Symbols:**

```
c08b81b4-c08b87a8: dw_pcie_host_init (STB_GLOBAL)
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
int dw_pcie_host_init(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffe0004e8fce)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:317
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
```
**Symbols:**

```
ffffffe0004e8fce-ffffffe0004e947a: dw_pcie_host_init (STB_GLOBAL)
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
int dw_pcie_host_init(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:317
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
```
**Symbols:**

```
ffffffff815a5a1d-ffffffff815a5a31: dw_pcie_host_init.cold (STB_LOCAL)
ffffffff815a51d0-ffffffff815a5262: dw_pcie_host_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int dw_pcie_host_init(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:317
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
```
**Symbols:**

```
ffffffff81594bbd-ffffffff81594bd1: dw_pcie_host_init.cold (STB_LOCAL)
ffffffff81594370-ffffffff81594402: dw_pcie_host_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int dw_pcie_host_init(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:317
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
```
**Symbols:**

```
ffffffff815a5fad-ffffffff815a5fc1: dw_pcie_host_init.cold (STB_LOCAL)
ffffffff815a5760-ffffffff815a57f2: dw_pcie_host_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int dw_pcie_host_init(struct pcie_port *pp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:317
Inline: False
```
**Symbols:**

```
ffffffff815c03ad-ffffffff815c03c1: dw_pcie_host_init.cold (STB_LOCAL)
ffffffff815bfb60-ffffffff815bfbf2: dw_pcie_host_init (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct pcie_port *pp</code> ➡️ <code>struct dw_pcie_rp *pp</code>
</li>
</ul>
</details>
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
