# Function: <code>dw_pcie_wr_own_conf</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_wr_own_conf(struct pcie_port *pp, int where, int size, u32 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/host/pcie-designware.c (ffffffff814a5130)
Location: drivers/pci/host/pcie-designware.c:143
Inline: True
Direct callers:
  - drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc
  - drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc
  - drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc
  - drivers/pci/host/pcie-designware.c:dw_pcie_msi_init
  - drivers/pci/host/pcie-designware.c:dw_pcie_msi_init
  - drivers/pci/host/pcie-designware.c:dw_handle_msi_irq
```
**Symbols:**

```
ffffffff814a5130-ffffffff814a5184: dw_pcie_wr_own_conf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_wr_own_conf(struct pcie_port *pp, int where, int size, u32 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/host/pcie-designware.c (ffffffff814c73a0)
Location: drivers/pci/host/pcie-designware.c:184
Inline: True
Direct callers:
  - drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc
  - drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc
  - drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc
  - drivers/pci/host/pcie-designware.c:dw_pcie_msi_init
  - drivers/pci/host/pcie-designware.c:dw_pcie_msi_init
  - drivers/pci/host/pcie-designware.c:dw_handle_msi_irq
```
**Symbols:**

```
ffffffff814c73a0-ffffffff814c73f4: dw_pcie_wr_own_conf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_wr_own_conf(struct pcie_port *pp, int where, int size, u32 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/dwc/pcie-designware-host.c (ffffffff814d36c0)
Location: drivers/pci/dwc/pcie-designware-host.c:36
Inline: True
Direct callers:
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/pci/dwc/pcie-designware-host.c:dw_handle_msi_irq
```
**Symbols:**

```
ffffffff814d36c0-ffffffff814d36f6: dw_pcie_wr_own_conf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_wr_own_conf(struct pcie_port *pp, int where, int size, u32 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/dwc/pcie-designware-host.c (ffffffff81513aa0)
Location: drivers/pci/dwc/pcie-designware-host.c:36
Inline: True
Direct callers:
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/pci/dwc/pcie-designware-host.c:dw_handle_msi_irq
```
**Symbols:**

```
ffffffff81513aa0-ffffffff81513ad9: dw_pcie_wr_own_conf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_wr_own_conf(struct pcie_port *pp, int where, int size, u32 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff81548fc0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:35
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_unmask
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_mask
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
```
**Symbols:**

```
ffffffff81548fc0-ffffffff81548ff9: dw_pcie_wr_own_conf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_wr_own_conf(struct pcie_port *pp, int where, int size, u32 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8155f730)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:35
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_ack
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_unmask
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_mask
```
**Symbols:**

```
ffffffff8155f730-ffffffff8155f769: dw_pcie_wr_own_conf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_wr_own_conf(struct pcie_port *pp, int where, int size, u32 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8158fe40)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:35
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
**Symbols:**

```
ffffffff8158fe40-ffffffff8158fe79: dw_pcie_wr_own_conf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_wr_own_conf(struct pcie_port *pp, int where, int size, u32 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815b1bb0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:35
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
**Symbols:**

```
ffffffff815b1bb0-ffffffff815b1be9: dw_pcie_wr_own_conf (STB_LOCAL)
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
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8165b732)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:36
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
</details>
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_wr_own_conf(struct pcie_port *pp, int where, int size, u32 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffff80001072de20)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:35
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_wr_conf
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_ack
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_unmask
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_mask
```
**Symbols:**

```
ffff80001072de20-ffff80001072de9c: dw_pcie_wr_own_conf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_wr_own_conf(struct pcie_port *pp, int where, int size, u32 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (c08b7850)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:35
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_wr_conf
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_ack
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_unmask
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_mask
```
**Symbols:**

```
c08b7850-c08b78a0: dw_pcie_wr_own_conf (STB_LOCAL)
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
int dw_pcie_wr_own_conf(struct pcie_port *pp, int where, int size, u32 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffe0004e8752)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:35
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_wr_conf
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_ack
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_unmask
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_mask
```
**Symbols:**

```
ffffffe0004e8752-ffffffe0004e87b6: dw_pcie_wr_own_conf (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_wr_own_conf(struct pcie_port *pp, int where, int size, u32 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815a5370)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:35
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
**Symbols:**

```
ffffffff815a5370-ffffffff815a53a9: dw_pcie_wr_own_conf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_wr_own_conf(struct pcie_port *pp, int where, int size, u32 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff81594510)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:35
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
**Symbols:**

```
ffffffff81594510-ffffffff81594549: dw_pcie_wr_own_conf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_wr_own_conf(struct pcie_port *pp, int where, int size, u32 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815a5900)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:35
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
**Symbols:**

```
ffffffff815a5900-ffffffff815a5939: dw_pcie_wr_own_conf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_wr_own_conf(struct pcie_port *pp, int where, int size, u32 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815bfd00)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:35
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
**Symbols:**

```
ffffffff815bfd00-ffffffff815bfd39: dw_pcie_wr_own_conf (STB_LOCAL)
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
