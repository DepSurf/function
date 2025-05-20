# Function: <code>dw_pcie_prog_outbound_atu</code>

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
In drivers/pci/host/pcie-designware.c (ffffffff814a5958)
Location: drivers/pci/host/pcie-designware.c:152
Inline: True
Inline callers:
  - drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dw_pcie_prog_outbound_atu(struct pcie_port *pp, int index, int type, u64 cpu_addr, u64 pci_addr, u32 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host/pcie-designware.c (ffffffff814c6fb0)
Location: drivers/pci/host/pcie-designware.c:193
Inline: False
Direct callers:
  - drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc
  - drivers/pci/host/pcie-designware.c:dw_pcie_setup_rc
```
**Symbols:**

```
ffffffff814c6fb0-ffffffff814c7399: dw_pcie_prog_outbound_atu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dw_pcie_prog_outbound_atu(struct dw_pcie *pci, int index, int type, u64 cpu_addr, u64 pci_addr, u32 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/dwc/pcie-designware.c (ffffffff814d3140)
Location: drivers/pci/dwc/pcie-designware.c:145
Inline: False
Direct callers:
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
**Symbols:**

```
ffffffff814d3140-ffffffff814d32e4: dw_pcie_prog_outbound_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dw_pcie_prog_outbound_atu(struct dw_pcie *pci, int index, int type, u64 cpu_addr, u64 pci_addr, u32 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/dwc/pcie-designware.c (ffffffff815134a0)
Location: drivers/pci/dwc/pcie-designware.c:146
Inline: False
Direct callers:
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
**Symbols:**

```
ffffffff815134a0-ffffffff81513711: dw_pcie_prog_outbound_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dw_pcie_prog_outbound_atu(struct dw_pcie *pci, int index, int type, u64 cpu_addr, u64 pci_addr, u32 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81548880)
Location: drivers/pci/controller/dwc/pcie-designware.c:143
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
```
**Symbols:**

```
ffffffff81548880-ffffffff81548af1: dw_pcie_prog_outbound_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dw_pcie_prog_outbound_atu(struct dw_pcie *pci, int index, int type, u64 cpu_addr, u64 pci_addr, u32 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8155ef40)
Location: drivers/pci/controller/dwc/pcie-designware.c:143
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_outbound_atu
```
**Symbols:**

```
ffffffff8155ef40-ffffffff8155f1ce: dw_pcie_prog_outbound_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void dw_pcie_prog_outbound_atu(struct dw_pcie *pci, int index, int type, u64 cpu_addr, u64 pci_addr, u32 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (0)
Location: drivers/pci/controller/dwc/pcie-designware.c:197
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_outbound_atu
```
**Symbols:**

```
ffffffff8158fbc6-ffffffff8158fbee: dw_pcie_prog_outbound_atu.cold (STB_LOCAL)
ffffffff8158f5b0-ffffffff8158f7ee: dw_pcie_prog_outbound_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void dw_pcie_prog_outbound_atu(struct dw_pcie *pci, int index, int type, u64 cpu_addr, u64 pci_addr, u32 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (0)
Location: drivers/pci/controller/dwc/pcie-designware.c:277
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_outbound_atu
```
**Symbols:**

```
ffffffff815b192e-ffffffff815b1956: dw_pcie_prog_outbound_atu.cold (STB_LOCAL)
ffffffff815b1320-ffffffff815b155e: dw_pcie_prog_outbound_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void dw_pcie_prog_outbound_atu(struct dw_pcie *pci, int index, int type, u64 cpu_addr, u64 pci_addr, u32 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (0)
Location: drivers/pci/controller/dwc/pcie-designware.c:281
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_outbound_atu
```
**Symbols:**

```
ffffffff8165b1d0-ffffffff8165b1e5: dw_pcie_prog_outbound_atu.cold (STB_LOCAL)
ffffffff8165ac60-ffffffff8165adca: dw_pcie_prog_outbound_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dw_pcie_prog_outbound_atu(struct dw_pcie *pci, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8167b030)
Location: drivers/pci/controller/dwc/pcie-designware.c:315
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_wr_other_conf
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_rd_other_conf
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_other_conf_map_bus
```
**Symbols:**

```
ffffffff8167b030-ffffffff8167b04f: dw_pcie_prog_outbound_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dw_pcie_prog_outbound_atu(struct dw_pcie *pci, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8165da90)
Location: drivers/pci/controller/dwc/pcie-designware.c:365
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_wr_other_conf
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_rd_other_conf
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_other_conf_map_bus
```
**Symbols:**

```
ffffffff8165da90-ffffffff8165daaf: dw_pcie_prog_outbound_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dw_pcie_prog_outbound_atu(struct dw_pcie *pci, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff816d0500)
Location: drivers/pci/controller/dwc/pcie-designware.c:365
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_wr_other_conf
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_rd_other_conf
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_other_conf_map_bus
```
**Symbols:**

```
ffffffff816d0500-ffffffff816d051f: dw_pcie_prog_outbound_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dw_pcie_prog_outbound_atu(struct dw_pcie *pci, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff817f93d0)
Location: drivers/pci/controller/dwc/pcie-designware.c:369
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_wr_other_conf
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_rd_other_conf
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_other_conf_map_bus
```
**Symbols:**

```
ffffffff817f93d0-ffffffff817f9403: dw_pcie_prog_outbound_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dw_pcie_prog_outbound_atu(struct dw_pcie *pci, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81925750)
Location: drivers/pci/controller/dwc/pcie-designware.c:515
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_iatu_setup
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_iatu_setup
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_wr_other_conf
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_rd_other_conf
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_other_conf_map_bus
```
**Symbols:**

```
ffffffff81925750-ffffffff81925780: dw_pcie_prog_outbound_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dw_pcie_prog_outbound_atu(struct dw_pcie *pci, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81969500)
Location: drivers/pci/controller/dwc/pcie-designware.c:528
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_iatu_setup
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_iatu_setup
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_wr_other_conf
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_rd_other_conf
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_other_conf_map_bus
```
**Symbols:**

```
ffffffff81969500-ffffffff81969530: dw_pcie_prog_outbound_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dw_pcie_prog_outbound_atu(struct dw_pcie *pci, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff819b2cb0)
Location: drivers/pci/controller/dwc/pcie-designware.c:529
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_iatu_setup
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_iatu_setup
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_wr_other_conf
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_rd_other_conf
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_other_conf_map_bus
```
**Symbols:**

```
ffffffff819b2cb0-ffffffff819b2ce0: dw_pcie_prog_outbound_atu (STB_GLOBAL)
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
void dw_pcie_prog_outbound_atu(struct dw_pcie *pci, int index, int type, u64 cpu_addr, u64 pci_addr, u32 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffff80001072d438)
Location: drivers/pci/controller/dwc/pcie-designware.c:277
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr
```
**Symbols:**

```
ffff80001072d438-ffff80001072d68c: dw_pcie_prog_outbound_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dw_pcie_prog_outbound_atu(struct dw_pcie *pci, int index, int type, u64 cpu_addr, u64 pci_addr, u32 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (c08b6ba4)
Location: drivers/pci/controller/dwc/pcie-designware.c:277
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_access_other_conf
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_access_other_conf
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr
```
**Symbols:**

```
c08b6ba4-c08b6dfc: dw_pcie_prog_outbound_atu (STB_GLOBAL)
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
void dw_pcie_prog_outbound_atu(struct dw_pcie *pci, int index, int type, u64 cpu_addr, u64 pci_addr, u32 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffe0004e7b4e)
Location: drivers/pci/controller/dwc/pcie-designware.c:277
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_access_other_conf
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_access_other_conf
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr
```
**Symbols:**

```
ffffffe0004e7b4e-ffffffe0004e7d5a: dw_pcie_prog_outbound_atu (STB_GLOBAL)
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
void dw_pcie_prog_outbound_atu(struct dw_pcie *pci, int index, int type, u64 cpu_addr, u64 pci_addr, u32 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (0)
Location: drivers/pci/controller/dwc/pcie-designware.c:277
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_outbound_atu
```
**Symbols:**

```
ffffffff815a50ee-ffffffff815a5116: dw_pcie_prog_outbound_atu.cold (STB_LOCAL)
ffffffff815a4ae0-ffffffff815a4d1e: dw_pcie_prog_outbound_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void dw_pcie_prog_outbound_atu(struct dw_pcie *pci, int index, int type, u64 cpu_addr, u64 pci_addr, u32 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (0)
Location: drivers/pci/controller/dwc/pcie-designware.c:277
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_outbound_atu
```
**Symbols:**

```
ffffffff8159428e-ffffffff815942b6: dw_pcie_prog_outbound_atu.cold (STB_LOCAL)
ffffffff81593c80-ffffffff81593ebe: dw_pcie_prog_outbound_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void dw_pcie_prog_outbound_atu(struct dw_pcie *pci, int index, int type, u64 cpu_addr, u64 pci_addr, u32 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (0)
Location: drivers/pci/controller/dwc/pcie-designware.c:277
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_outbound_atu
```
**Symbols:**

```
ffffffff815a567e-ffffffff815a56a6: dw_pcie_prog_outbound_atu.cold (STB_LOCAL)
ffffffff815a5070-ffffffff815a52ae: dw_pcie_prog_outbound_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void dw_pcie_prog_outbound_atu(struct dw_pcie *pci, int index, int type, u64 cpu_addr, u64 pci_addr, u32 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (0)
Location: drivers/pci/controller/dwc/pcie-designware.c:277
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_outbound_atu
```
**Symbols:**

```
ffffffff815bfa7e-ffffffff815bfaa6: dw_pcie_prog_outbound_atu.cold (STB_LOCAL)
ffffffff815bf470-ffffffff815bf6ae: dw_pcie_prog_outbound_atu (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u32 size</code> ➡️ <code>u64 size</code>
</li>
</ul>
</details>
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
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
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
