# Function: <code>__dw_pcie_write_dbi</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __dw_pcie_write_dbi(struct dw_pcie *pci, void *base, u32 reg, size_t size, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/dwc/pcie-designware.c (ffffffff814d2fa0)
Location: drivers/pci/dwc/pcie-designware.c:80
Inline: True
Direct callers:
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_disable_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_disable_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu_unroll
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu_unroll
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu_unroll
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu_unroll
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu_unroll
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu_unroll
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu_unroll
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu_unroll
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu_unroll
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu_unroll
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu_unroll
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
**Symbols:**

```
ffffffff814d2fa0-ffffffff814d2ffc: __dw_pcie_write_dbi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __dw_pcie_write_dbi(struct dw_pcie *pci, void *base, u32 reg, size_t size, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/dwc/pcie-designware.c (ffffffff81513440)
Location: drivers/pci/dwc/pcie-designware.c:80
Inline: True
Direct callers:
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_disable_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_disable_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
**Symbols:**

```
ffffffff81513440-ffffffff8151349f: __dw_pcie_write_dbi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __dw_pcie_write_dbi(struct dw_pcie *pci, void *base, u32 reg, size_t size, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81548820)
Location: drivers/pci/controller/dwc/pcie-designware.c:77
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
```
**Symbols:**

```
ffffffff81548820-ffffffff8154887f: __dw_pcie_write_dbi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __dw_pcie_write_dbi(struct dw_pcie *pci, void *base, u32 reg, size_t size, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8155eee0)
Location: drivers/pci/controller/dwc/pcie-designware.c:77
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_disable_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
```
**Symbols:**

```
ffffffff8155eee0-ffffffff8155ef3f: __dw_pcie_write_dbi (STB_GLOBAL)
```
</details>
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
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
</ul>
