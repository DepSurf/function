# Function: <code>pcie_phy_write</code>

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
int pcie_phy_write(struct imx6_pcie *imx6_pcie, int addr, u16 data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pci-imx6.c (ffff800010731130)
Location: drivers/pci/controller/dwc/pci-imx6.c:226
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_host_init
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_host_init
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link
```
**Symbols:**

```
ffff800010731130-ffff80001073124c: pcie_phy_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pcie_phy_write(struct imx6_pcie *imx6_pcie, int addr, u16 data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pci-imx6.c (c08baef8)
Location: drivers/pci/controller/dwc/pci-imx6.c:226
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_host_init
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_host_init
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link
```
**Symbols:**

```
c08baef8-c08baff8: pcie_phy_write (STB_LOCAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
