# Function: <code>pci_host_probe</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_host_probe(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81518320)
Location: drivers/pci/probe.c:2845
Inline: False
```
**Symbols:**

```
ffffffff81518320-ffffffff815183b7: pci_host_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_host_probe(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8152dda0)
Location: drivers/pci/probe.c:2971
Inline: False
```
**Symbols:**

```
ffffffff8152dda0-ffffffff8152de37: pci_host_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pci_host_probe(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:3197
Inline: False
```
**Symbols:**

```
ffffffff8155d78d-ffffffff8155d7a8: pci_host_probe.cold (STB_LOCAL)
ffffffff8155c4d0-ffffffff8155c55b: pci_host_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pci_host_probe(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:2931
Inline: False
```
**Symbols:**

```
ffffffff8157e801-ffffffff8157e81c: pci_host_probe.cold (STB_LOCAL)
ffffffff8157d5a0-ffffffff8157d62b: pci_host_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pci_host_probe(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:2983
Inline: False
```
**Symbols:**

```
ffffffff81623d18-ffffffff81623d33: pci_host_probe.cold (STB_LOCAL)
ffffffff81622b90-ffffffff81622c1b: pci_host_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pci_host_probe(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:2990
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
**Symbols:**

```
ffffffff81bf7a30-ffffffff81bf7a4b: pci_host_probe.cold (STB_LOCAL)
ffffffff81649790-ffffffff8164981b: pci_host_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int pci_host_probe(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:3034
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
**Symbols:**

```
ffffffff81be98d7-ffffffff81be98f2: pci_host_probe.cold (STB_LOCAL)
ffffffff8162c350-ffffffff8162c3db: pci_host_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pci_host_probe(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:3076
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
**Symbols:**

```
ffffffff81ce427d-ffffffff81ce4298: pci_host_probe.cold (STB_LOCAL)
ffffffff8169b820-ffffffff8169b8ab: pci_host_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pci_host_probe(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:3047
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
**Symbols:**

```
ffffffff81eaac8f-ffffffff81eaacaa: pci_host_probe.cold (STB_LOCAL)
ffffffff817bd010-ffffffff817bd0a3: pci_host_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_host_probe(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff818d9010)
Location: drivers/pci/probe.c:3057
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
**Symbols:**

```
ffffffff818d9010-ffffffff818d90b8: pci_host_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_host_probe(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8191c350)
Location: drivers/pci/probe.c:3071
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
**Symbols:**

```
ffffffff8191c350-ffffffff8191c3f8: pci_host_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_host_probe(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81964780)
Location: drivers/pci/probe.c:3120
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
**Symbols:**

```
ffffffff81964780-ffffffff81964828: pci_host_probe (STB_GLOBAL)
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
int pci_host_probe(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffff8000106e0db0)
Location: drivers/pci/probe.c:2931
Inline: False
Direct callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_probe
  - drivers/pci/controller/pci-host-common.c:pci_host_common_probe
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe
```
**Symbols:**

```
ffff8000106e0db0-ffff8000106e0e78: pci_host_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_host_probe(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c087cb0c)
Location: drivers/pci/probe.c:2931
Inline: False
Direct callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pci-host-common.c:pci_host_common_probe
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe
```
**Symbols:**

```
c087cb0c-c087cbac: pci_host_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_host_probe(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c000000000859f30)
Location: drivers/pci/probe.c:2931
Inline: False
Direct callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pci-host-common.c:pci_host_common_probe
```
**Symbols:**

```
c000000000859f30-c00000000085a038: pci_host_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_host_probe(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffe0004b8acc)
Location: drivers/pci/probe.c:2931
Inline: False
Direct callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pci-host-common.c:pci_host_common_probe
```
**Symbols:**

```
ffffffe0004b8acc-ffffffe0004b8b82: pci_host_probe (STB_GLOBAL)
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
int pci_host_probe(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:2931
Inline: False
```
**Symbols:**

```
ffffffff81572d21-ffffffff81572d3c: pci_host_probe.cold (STB_LOCAL)
ffffffff81571ac0-ffffffff81571b4b: pci_host_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int pci_host_probe(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:2931
Inline: False
```
**Symbols:**

```
ffffffff81561481-ffffffff8156149c: pci_host_probe.cold (STB_LOCAL)
ffffffff81560220-ffffffff815602ab: pci_host_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pci_host_probe(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:2931
Inline: False
```
**Symbols:**

```
ffffffff81572551-ffffffff8157256c: pci_host_probe.cold (STB_LOCAL)
ffffffff815712f0-ffffffff8157137b: pci_host_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pci_host_probe(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:2931
Inline: False
```
**Symbols:**

```
ffffffff8158ca31-ffffffff8158ca4c: pci_host_probe.cold (STB_LOCAL)
ffffffff8158b7d0-ffffffff8158b85b: pci_host_probe (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
