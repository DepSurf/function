# Function: <code>cdns_pcie_ep_assert_intx</code>

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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/pcie-cadence-ep.c (ffff80001071e7c0)
Location: drivers/pci/controller/pcie-cadence-ep.c:257
Inline: True
Direct callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq
```
**Symbols:**

```
ffff80001071e7c0-ffff80001071e8bc: cdns_pcie_ep_assert_intx.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/pcie-cadence-ep.c (c08a76d8)
Location: drivers/pci/controller/pcie-cadence-ep.c:257
Inline: True
Direct callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq
```
**Symbols:**

```
c08a76d8-c08a77d4: cdns_pcie_ep_assert_intx.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/pcie-cadence-ep.c (c00000000088fcd0)
Location: drivers/pci/controller/pcie-cadence-ep.c:257
Inline: True
Direct callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq
```
**Symbols:**

```
c00000000088fcd0-c00000000088fe8c: cdns_pcie_ep_assert_intx.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/pcie-cadence-ep.c (ffffffe0004e56ce)
Location: drivers/pci/controller/pcie-cadence-ep.c:257
Inline: True
Direct callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq
```
**Symbols:**

```
ffffffe0004e56ce-ffffffe0004e57d6: cdns_pcie_ep_assert_intx.constprop.0 (STB_LOCAL)
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
