# Function: <code>dw_pcie_wr_other_conf</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/host/pcie-designware.c (0)
Location: drivers/pci/host/pcie-designware.c:623
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/host/pcie-designware.c (0)
Location: drivers/pci/host/pcie-designware.c:717
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/dwc/pcie-designware-host.c (0)
Location: drivers/pci/dwc/pcie-designware-host.c:482
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/dwc/pcie-designware-host.c (0)
Location: drivers/pci/dwc/pcie-designware-host.c:485
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:548
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:554
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:562
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:579
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:571
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dw_pcie_wr_other_conf(struct pci_bus *bus, unsigned int devfn, int where, int size, u32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8167b550)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:508
Inline: False
```
**Symbols:**

```
ffffffff8167b550-ffffffff8167b5a5: dw_pcie_wr_other_conf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dw_pcie_wr_other_conf(struct pci_bus *bus, unsigned int devfn, int where, int size, u32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8165e3e0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:485
Inline: False
```
**Symbols:**

```
ffffffff8165e3e0-ffffffff8165e435: dw_pcie_wr_other_conf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dw_pcie_wr_other_conf(struct pci_bus *bus, unsigned int devfn, int where, int size, u32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff816d0eb0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:484
Inline: False
```
**Symbols:**

```
ffffffff816d0eb0-ffffffff816d0f05: dw_pcie_wr_other_conf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dw_pcie_wr_other_conf(struct pci_bus *bus, unsigned int devfn, int where, int size, u32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff817fa0e0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:504
Inline: False
```
**Symbols:**

```
ffffffff817fa0e0-ffffffff817fa159: dw_pcie_wr_other_conf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dw_pcie_wr_other_conf(struct pci_bus *bus, unsigned int devfn, int where, int size, u32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff81926310)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:580
Inline: False
```
**Symbols:**

```
ffffffff81926310-ffffffff81926391: dw_pcie_wr_other_conf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dw_pcie_wr_other_conf(struct pci_bus *bus, unsigned int devfn, int where, int size, u32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8196a4f0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:599
Inline: False
```
**Symbols:**

```
ffffffff8196a4f0-ffffffff8196a571: dw_pcie_wr_other_conf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dw_pcie_wr_other_conf(struct pci_bus *bus, unsigned int devfn, int where, int size, u32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff819b3cb0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:604
Inline: False
```
**Symbols:**

```
ffffffff819b3cb0-ffffffff819b3d31: dw_pcie_wr_other_conf (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffff80001072e6e0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:579
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_wr_conf
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (c08b7e38)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:579
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_wr_conf
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffe0004e8cb2)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:579
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_wr_conf
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:579
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:579
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:579
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:579
Inline: False
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
