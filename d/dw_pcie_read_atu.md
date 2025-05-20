# Function: <code>dw_pcie_read_atu</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 dw_pcie_read_atu(struct dw_pcie *pci, u32 reg, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8158f519)
Location: drivers/pci/controller/dwc/pcie-designware.c:117
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
```
**Symbols:**

```
ffffffff8158fb9d-ffffffff8158fbb2: dw_pcie_read_atu.cold (STB_LOCAL)
ffffffff8158f4c0-ffffffff8158f53b: dw_pcie_read_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 dw_pcie_read_atu(struct dw_pcie *pci, u32 reg, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815b1289)
Location: drivers/pci/controller/dwc/pcie-designware.c:197
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
```
**Symbols:**

```
ffffffff815b1905-ffffffff815b191a: dw_pcie_read_atu.cold (STB_LOCAL)
ffffffff815b1230-ffffffff815b12ab: dw_pcie_read_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 dw_pcie_read_atu(struct dw_pcie *pci, u32 reg, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8165aa8c)
Location: drivers/pci/controller/dwc/pcie-designware.c:198
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu_unroll
```
**Symbols:**

```
ffffffff8165b191-ffffffff8165b1a7: dw_pcie_read_atu.cold (STB_LOCAL)
ffffffff8165aa60-ffffffff8165aac7: dw_pcie_read_atu (STB_GLOBAL)
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
u32 dw_pcie_read_atu(struct dw_pcie *pci, u32 reg, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffff80001072d2f8)
Location: drivers/pci/controller/dwc/pcie-designware.c:197
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
```
**Symbols:**

```
ffff80001072d2f8-ffff80001072d3ac: dw_pcie_read_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
u32 dw_pcie_read_atu(struct dw_pcie *pci, u32 reg, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (c08b6a78)
Location: drivers/pci/controller/dwc/pcie-designware.c:197
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
```
**Symbols:**

```
c08b6a78-c08b6b28: dw_pcie_read_atu (STB_GLOBAL)
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
u32 dw_pcie_read_atu(struct dw_pcie *pci, u32 reg, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffe0004e7a54)
Location: drivers/pci/controller/dwc/pcie-designware.c:197
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
```
**Symbols:**

```
ffffffe0004e7a54-ffffffe0004e7ada: dw_pcie_read_atu (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 dw_pcie_read_atu(struct dw_pcie *pci, u32 reg, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815a4a49)
Location: drivers/pci/controller/dwc/pcie-designware.c:197
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
```
**Symbols:**

```
ffffffff815a50c5-ffffffff815a50da: dw_pcie_read_atu.cold (STB_LOCAL)
ffffffff815a49f0-ffffffff815a4a6b: dw_pcie_read_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 dw_pcie_read_atu(struct dw_pcie *pci, u32 reg, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81593be9)
Location: drivers/pci/controller/dwc/pcie-designware.c:197
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
```
**Symbols:**

```
ffffffff81594265-ffffffff8159427a: dw_pcie_read_atu.cold (STB_LOCAL)
ffffffff81593b90-ffffffff81593c0b: dw_pcie_read_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 dw_pcie_read_atu(struct dw_pcie *pci, u32 reg, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815a4fd9)
Location: drivers/pci/controller/dwc/pcie-designware.c:197
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
```
**Symbols:**

```
ffffffff815a5655-ffffffff815a566a: dw_pcie_read_atu.cold (STB_LOCAL)
ffffffff815a4f80-ffffffff815a4ffb: dw_pcie_read_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 dw_pcie_read_atu(struct dw_pcie *pci, u32 reg, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815bf3d9)
Location: drivers/pci/controller/dwc/pcie-designware.c:197
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
```
**Symbols:**

```
ffffffff815bfa55-ffffffff815bfa6a: dw_pcie_read_atu.cold (STB_LOCAL)
ffffffff815bf380-ffffffff815bf3fb: dw_pcie_read_atu (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
