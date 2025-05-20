# Function: <code>dw_pcie_rd_other_conf</code>

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
Location: drivers/pci/host/pcie-designware.c:586
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
Location: drivers/pci/host/pcie-designware.c:679
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
Location: drivers/pci/dwc/pcie-designware-host.c:443
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
Location: drivers/pci/dwc/pcie-designware-host.c:446
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
Location: drivers/pci/controller/dwc/pcie-designware-host.c:509
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
Location: drivers/pci/controller/dwc/pcie-designware-host.c:515
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
Location: drivers/pci/controller/dwc/pcie-designware-host.c:551
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
Location: drivers/pci/controller/dwc/pcie-designware-host.c:568
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
Location: drivers/pci/controller/dwc/pcie-designware-host.c:560
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dw_pcie_rd_other_conf(struct pci_bus *bus, unsigned int devfn, int where, int size, u32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8167b660)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:492
Inline: False
```
**Symbols:**

```
ffffffff8167b660-ffffffff8167b6b5: dw_pcie_rd_other_conf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dw_pcie_rd_other_conf(struct pci_bus *bus, unsigned int devfn, int where, int size, u32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8165e4f0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:469
Inline: False
```
**Symbols:**

```
ffffffff8165e4f0-ffffffff8165e545: dw_pcie_rd_other_conf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dw_pcie_rd_other_conf(struct pci_bus *bus, unsigned int devfn, int where, int size, u32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff816d0fc0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:468
Inline: False
```
**Symbols:**

```
ffffffff816d0fc0-ffffffff816d1015: dw_pcie_rd_other_conf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dw_pcie_rd_other_conf(struct pci_bus *bus, unsigned int devfn, int where, int size, u32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff817fa230)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:488
Inline: False
```
**Symbols:**

```
ffffffff817fa230-ffffffff817fa2a9: dw_pcie_rd_other_conf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dw_pcie_rd_other_conf(struct pci_bus *bus, unsigned int devfn, int where, int size, u32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff81926490)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:558
Inline: False
```
**Symbols:**

```
ffffffff81926490-ffffffff81926511: dw_pcie_rd_other_conf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dw_pcie_rd_other_conf(struct pci_bus *bus, unsigned int devfn, int where, int size, u32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8196a670)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:577
Inline: False
```
**Symbols:**

```
ffffffff8196a670-ffffffff8196a6f1: dw_pcie_rd_other_conf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dw_pcie_rd_other_conf(struct pci_bus *bus, unsigned int devfn, int where, int size, u32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff819b3e30)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:582
Inline: False
```
**Symbols:**

```
ffffffff819b3e30-ffffffff819b3eb1: dw_pcie_rd_other_conf (STB_LOCAL)
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
In drivers/pci/controller/dwc/pcie-designware-host.c (ffff80001072e34c)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:568
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_rd_conf
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
In drivers/pci/controller/dwc/pcie-designware-host.c (c08b76dc)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:568
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_rd_conf
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
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffe0004e85e0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:568
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_rd_conf
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
Location: drivers/pci/controller/dwc/pcie-designware-host.c:568
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
Location: drivers/pci/controller/dwc/pcie-designware-host.c:568
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
Location: drivers/pci/controller/dwc/pcie-designware-host.c:568
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
Location: drivers/pci/controller/dwc/pcie-designware-host.c:568
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
