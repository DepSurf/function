# Function: <code>dw_pcie_disable_atu</code>

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
void dw_pcie_disable_atu(struct dw_pcie *pci, int index, enum dw_pcie_region_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/dwc/pcie-designware.c (ffffffff814d3570)
Location: drivers/pci/dwc/pcie-designware.c:293
Inline: False
```
**Symbols:**

```
ffffffff814d3570-ffffffff814d35c7: dw_pcie_disable_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dw_pcie_disable_atu(struct dw_pcie *pci, int index, enum dw_pcie_region_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/dwc/pcie-designware.c (ffffffff81513950)
Location: drivers/pci/dwc/pcie-designware.c:295
Inline: False
```
**Symbols:**

```
ffffffff81513950-ffffffff815139a7: dw_pcie_disable_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dw_pcie_disable_atu(struct dw_pcie *pci, int index, enum dw_pcie_region_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81548d30)
Location: drivers/pci/controller/dwc/pcie-designware.c:292
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq
```
**Symbols:**

```
ffffffff81548d30-ffffffff81548d87: dw_pcie_disable_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dw_pcie_disable_atu(struct dw_pcie *pci, int index, enum dw_pcie_region_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8155f410)
Location: drivers/pci/controller/dwc/pcie-designware.c:292
Inline: False
```
**Symbols:**

```
ffffffff8155f410-ffffffff8155f467: dw_pcie_disable_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dw_pcie_disable_atu(struct dw_pcie *pci, int index, enum dw_pcie_region_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8158f9d0)
Location: drivers/pci/controller/dwc/pcie-designware.c:346
Inline: False
```
**Symbols:**

```
ffffffff8158f9d0-ffffffff8158fa1f: dw_pcie_disable_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dw_pcie_disable_atu(struct dw_pcie *pci, int index, enum dw_pcie_region_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815b1740)
Location: drivers/pci/controller/dwc/pcie-designware.c:426
Inline: False
```
**Symbols:**

```
ffffffff815b1740-ffffffff815b178f: dw_pcie_disable_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dw_pcie_disable_atu(struct dw_pcie *pci, int index, enum dw_pcie_region_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8165afb0)
Location: drivers/pci/controller/dwc/pcie-designware.c:430
Inline: False
```
**Symbols:**

```
ffffffff8165afb0-ffffffff8165b001: dw_pcie_disable_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dw_pcie_disable_atu(struct dw_pcie *pci, int index, enum dw_pcie_region_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8167b260)
Location: drivers/pci/controller/dwc/pcie-designware.c:441
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_unmap_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar
```
**Symbols:**

```
ffffffff8167b260-ffffffff8167b2b1: dw_pcie_disable_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dw_pcie_disable_atu(struct dw_pcie *pci, int index, enum dw_pcie_region_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8165dcb0)
Location: drivers/pci/controller/dwc/pcie-designware.c:491
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_unmap_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar
```
**Symbols:**

```
ffffffff8165dcb0-ffffffff8165dd01: dw_pcie_disable_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dw_pcie_disable_atu(struct dw_pcie *pci, int index, enum dw_pcie_region_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff816d0720)
Location: drivers/pci/controller/dwc/pcie-designware.c:491
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_unmap_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar
```
**Symbols:**

```
ffffffff816d0720-ffffffff816d0771: dw_pcie_disable_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dw_pcie_disable_atu(struct dw_pcie *pci, int index, enum dw_pcie_region_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff817f9650)
Location: drivers/pci/controller/dwc/pcie-designware.c:495
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_unmap_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar
```
**Symbols:**

```
ffffffff817f9650-ffffffff817f9702: dw_pcie_disable_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dw_pcie_disable_atu(struct dw_pcie *pci, u32 dir, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81925b40)
Location: drivers/pci/controller/dwc/pcie-designware.c:629
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_iatu_setup
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_iatu_setup
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_unmap_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar
```
**Symbols:**

```
ffffffff81925b40-ffffffff81925b67: dw_pcie_disable_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dw_pcie_disable_atu(struct dw_pcie *pci, u32 dir, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff819698f0)
Location: drivers/pci/controller/dwc/pcie-designware.c:642
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_iatu_setup
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_iatu_setup
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_unmap_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar
```
**Symbols:**

```
ffffffff819698f0-ffffffff81969917: dw_pcie_disable_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dw_pcie_disable_atu(struct dw_pcie *pci, u32 dir, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff819b30a0)
Location: drivers/pci/controller/dwc/pcie-designware.c:643
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_iatu_setup
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_iatu_setup
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_unmap_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar
```
**Symbols:**

```
ffffffff819b30a0-ffffffff819b30c7: dw_pcie_disable_atu (STB_GLOBAL)
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
void dw_pcie_disable_atu(struct dw_pcie *pci, int index, enum dw_pcie_region_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffff80001072d888)
Location: drivers/pci/controller/dwc/pcie-designware.c:426
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_unmap_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar
  - drivers/pci/controller/dwc/pci-layerscape.c:ls_pcie_host_init
```
**Symbols:**

```
ffff80001072d888-ffff80001072d8fc: dw_pcie_disable_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dw_pcie_disable_atu(struct dw_pcie *pci, int index, enum dw_pcie_region_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (c08b6fe0)
Location: drivers/pci/controller/dwc/pcie-designware.c:426
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_unmap_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar
```
**Symbols:**

```
c08b6fe0-c08b703c: dw_pcie_disable_atu (STB_GLOBAL)
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
void dw_pcie_disable_atu(struct dw_pcie *pci, int index, enum dw_pcie_region_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffe0004e7f12)
Location: drivers/pci/controller/dwc/pcie-designware.c:426
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_unmap_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar
```
**Symbols:**

```
ffffffe0004e7f12-ffffffe0004e7f80: dw_pcie_disable_atu (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void dw_pcie_disable_atu(struct dw_pcie *pci, int index, enum dw_pcie_region_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815a4f00)
Location: drivers/pci/controller/dwc/pcie-designware.c:426
Inline: False
```
**Symbols:**

```
ffffffff815a4f00-ffffffff815a4f4f: dw_pcie_disable_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dw_pcie_disable_atu(struct dw_pcie *pci, int index, enum dw_pcie_region_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815940a0)
Location: drivers/pci/controller/dwc/pcie-designware.c:426
Inline: False
```
**Symbols:**

```
ffffffff815940a0-ffffffff815940ef: dw_pcie_disable_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dw_pcie_disable_atu(struct dw_pcie *pci, int index, enum dw_pcie_region_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815a5490)
Location: drivers/pci/controller/dwc/pcie-designware.c:426
Inline: False
```
**Symbols:**

```
ffffffff815a5490-ffffffff815a54df: dw_pcie_disable_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dw_pcie_disable_atu(struct dw_pcie *pci, int index, enum dw_pcie_region_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815bf890)
Location: drivers/pci/controller/dwc/pcie-designware.c:426
Inline: False
```
**Symbols:**

```
ffffffff815bf890-ffffffff815bf8df: dw_pcie_disable_atu (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 dir</code>
</li>
<li>
<b>Param removed. </b>
<code>enum dw_pcie_region_type type</code>
</li>
<li>
<b>Param reordered. </b>
<code>pci, index, type</code> ➡️ <code>pci, dir, index</code>
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
