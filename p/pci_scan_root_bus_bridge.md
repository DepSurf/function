# Function: <code>pci_scan_root_bus_bridge</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_scan_root_bus_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814a99c0)
Location: drivers/pci/probe.c:2497
Inline: False
```
**Symbols:**

```
ffffffff814a99c0-ffffffff814a9a7b: pci_scan_root_bus_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_scan_root_bus_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814e8c20)
Location: drivers/pci/probe.c:2724
Inline: False
```
**Symbols:**

```
ffffffff814e8c20-ffffffff814e8cdf: pci_scan_root_bus_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_scan_root_bus_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81518260)
Location: drivers/pci/probe.c:2941
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_host_probe
```
**Symbols:**

```
ffffffff81518260-ffffffff8151831f: pci_scan_root_bus_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_scan_root_bus_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8152dce0)
Location: drivers/pci/probe.c:3067
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_host_probe
```
**Symbols:**

```
ffffffff8152dce0-ffffffff8152dd9f: pci_scan_root_bus_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pci_scan_root_bus_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:3291
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_host_probe
```
**Symbols:**

```
ffffffff8155d73d-ffffffff8155d78d: pci_scan_root_bus_bridge.cold (STB_LOCAL)
ffffffff8155c450-ffffffff8155c4cd: pci_scan_root_bus_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pci_scan_root_bus_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:3025
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_host_probe
```
**Symbols:**

```
ffffffff8157e7b1-ffffffff8157e801: pci_scan_root_bus_bridge.cold (STB_LOCAL)
ffffffff8157d520-ffffffff8157d59d: pci_scan_root_bus_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pci_scan_root_bus_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:3077
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_host_probe
```
**Symbols:**

```
ffffffff81623cc8-ffffffff81623d18: pci_scan_root_bus_bridge.cold (STB_LOCAL)
ffffffff81622b10-ffffffff81622b8d: pci_scan_root_bus_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pci_scan_root_bus_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:3084
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_host_probe
```
**Symbols:**

```
ffffffff81bf79e0-ffffffff81bf7a30: pci_scan_root_bus_bridge.cold (STB_LOCAL)
ffffffff81649700-ffffffff81649781: pci_scan_root_bus_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int pci_scan_root_bus_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:3128
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_host_probe
```
**Symbols:**

```
ffffffff81be9887-ffffffff81be98d7: pci_scan_root_bus_bridge.cold (STB_LOCAL)
ffffffff8162c2c0-ffffffff8162c341: pci_scan_root_bus_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pci_scan_root_bus_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:3170
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_host_probe
```
**Symbols:**

```
ffffffff81ce422d-ffffffff81ce427d: pci_scan_root_bus_bridge.cold (STB_LOCAL)
ffffffff8169b790-ffffffff8169b811: pci_scan_root_bus_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pci_scan_root_bus_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:3141
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_host_probe
```
**Symbols:**

```
ffffffff81eaac44-ffffffff81eaac8f: pci_scan_root_bus_bridge.cold (STB_LOCAL)
ffffffff817bcf70-ffffffff817bd005: pci_scan_root_bus_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_scan_root_bus_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff818d8f20)
Location: drivers/pci/probe.c:3151
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_host_probe
```
**Symbols:**

```
ffffffff818d8f20-ffffffff818d8ffd: pci_scan_root_bus_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_scan_root_bus_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8191c260)
Location: drivers/pci/probe.c:3165
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_host_probe
```
**Symbols:**

```
ffffffff8191c260-ffffffff8191c33d: pci_scan_root_bus_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_scan_root_bus_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81964690)
Location: drivers/pci/probe.c:3214
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_host_probe
```
**Symbols:**

```
ffffffff81964690-ffffffff8196476d: pci_scan_root_bus_bridge (STB_GLOBAL)
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
int pci_scan_root_bus_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffff8000106e0cd0)
Location: drivers/pci/probe.c:3025
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_host_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_probe
  - drivers/pci/controller/pcie-altera.c:altera_pcie_probe
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_probe
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_probe
```
**Symbols:**

```
ffff8000106e0cd0-ffff8000106e0dac: pci_scan_root_bus_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_scan_root_bus_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c087ca38)
Location: drivers/pci/probe.c:3025
Inline: False
Direct callers:
  - arch/arm/kernel/bios32.c:pci_common_init_dev
  - drivers/pci/probe.c:pci_host_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_enable
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
  - drivers/pci/controller/pcie-altera.c:altera_pcie_probe
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
**Symbols:**

```
c087ca38-c087cb0c: pci_scan_root_bus_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_scan_root_bus_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c000000000859e10)
Location: drivers/pci/probe.c:3025
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_host_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
```
**Symbols:**

```
c000000000859e10-c000000000859f30: pci_scan_root_bus_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_scan_root_bus_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffe0004b89fe)
Location: drivers/pci/probe.c:3025
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_host_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
**Symbols:**

```
ffffffe0004b89fe-ffffffe0004b8acc: pci_scan_root_bus_bridge (STB_GLOBAL)
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
int pci_scan_root_bus_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:3025
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_host_probe
```
**Symbols:**

```
ffffffff81572cd1-ffffffff81572d21: pci_scan_root_bus_bridge.cold (STB_LOCAL)
ffffffff81571a40-ffffffff81571abd: pci_scan_root_bus_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int pci_scan_root_bus_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:3025
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_host_probe
```
**Symbols:**

```
ffffffff81561431-ffffffff81561481: pci_scan_root_bus_bridge.cold (STB_LOCAL)
ffffffff815601a0-ffffffff8156021d: pci_scan_root_bus_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pci_scan_root_bus_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:3025
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_host_probe
```
**Symbols:**

```
ffffffff81572501-ffffffff81572551: pci_scan_root_bus_bridge.cold (STB_LOCAL)
ffffffff81571270-ffffffff815712ed: pci_scan_root_bus_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pci_scan_root_bus_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:3025
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_host_probe
```
**Symbols:**

```
ffffffff8158c9e1-ffffffff8158ca31: pci_scan_root_bus_bridge.cold (STB_LOCAL)
ffffffff8158b750-ffffffff8158b7cd: pci_scan_root_bus_bridge (STB_GLOBAL)
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
