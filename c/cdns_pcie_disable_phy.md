# Function: <code>cdns_pcie_disable_phy</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void cdns_pcie_disable_phy(struct cdns_pcie *pcie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pcie-cadence.c (ffff80001071d2b0)
Location: drivers/pci/controller/pcie-cadence.c:128
Inline: False
Direct callers:
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_suspend_noirq
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_shutdown
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_shutdown
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_shutdown
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_shutdown
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_shutdown
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_shutdown
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
```
**Symbols:**

```
ffff80001071d2b0-ffff80001071d310: cdns_pcie_disable_phy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cdns_pcie_disable_phy(struct cdns_pcie *pcie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pcie-cadence.c (c08a6374)
Location: drivers/pci/controller/pcie-cadence.c:128
Inline: False
Direct callers:
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_suspend_noirq
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_shutdown
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_shutdown
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
```
**Symbols:**

```
c08a6374-c08a63c4: cdns_pcie_disable_phy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cdns_pcie_disable_phy(struct cdns_pcie *pcie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pcie-cadence.c (c00000000088dfb0)
Location: drivers/pci/controller/pcie-cadence.c:128
Inline: False
Direct callers:
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_suspend_noirq
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_shutdown
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_shutdown
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_shutdown
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_shutdown
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_shutdown
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_shutdown
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
```
**Symbols:**

```
c00000000088dfb0-c00000000088e040: cdns_pcie_disable_phy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cdns_pcie_disable_phy(struct cdns_pcie *pcie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pcie-cadence.c (ffffffe0004e4118)
Location: drivers/pci/controller/pcie-cadence.c:128
Inline: False
Direct callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_shutdown
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_shutdown
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
```
**Symbols:**

```
ffffffe0004e4118-ffffffe0004e417a: cdns_pcie_disable_phy (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
