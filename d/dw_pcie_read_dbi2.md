# Function: <code>dw_pcie_read_dbi2</code>

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
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
u32 dw_pcie_read_dbi2(struct dw_pcie *pci, u32 reg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (0)
Location: drivers/pci/controller/dwc/pcie-designware.c:88
Inline: False
```
**Symbols:**

```
ffffffff8158fb74-ffffffff8158fb89: dw_pcie_read_dbi2.cold (STB_LOCAL)
ffffffff8158f3d0-ffffffff8158f44b: dw_pcie_read_dbi2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
u32 dw_pcie_read_dbi2(struct dw_pcie *pci, u32 reg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (0)
Location: drivers/pci/controller/dwc/pcie-designware.c:168
Inline: False
```
**Symbols:**

```
ffffffff815b18dc-ffffffff815b18f1: dw_pcie_read_dbi2.cold (STB_LOCAL)
ffffffff815b1140-ffffffff815b11bb: dw_pcie_read_dbi2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
u32 dw_pcie_read_dbi2(struct dw_pcie *pci, u32 reg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (0)
Location: drivers/pci/controller/dwc/pcie-designware.c:169
Inline: False
```
**Symbols:**

```
ffffffff8165b167-ffffffff8165b17d: dw_pcie_read_dbi2.cold (STB_LOCAL)
ffffffff8165a980-ffffffff8165a9e7: dw_pcie_read_dbi2 (STB_GLOBAL)
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
<summary>In <code>arm64</code>: ✅</summary>

```c
u32 dw_pcie_read_dbi2(struct dw_pcie *pci, u32 reg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffff80001072d1b8)
Location: drivers/pci/controller/dwc/pcie-designware.c:168
Inline: False
```
**Symbols:**

```
ffff80001072d1b8-ffff80001072d26c: dw_pcie_read_dbi2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u32 dw_pcie_read_dbi2(struct dw_pcie *pci, u32 reg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (c08b694c)
Location: drivers/pci/controller/dwc/pcie-designware.c:168
Inline: False
```
**Symbols:**

```
c08b694c-c08b69fc: dw_pcie_read_dbi2 (STB_GLOBAL)
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
u32 dw_pcie_read_dbi2(struct dw_pcie *pci, u32 reg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffe0004e795a)
Location: drivers/pci/controller/dwc/pcie-designware.c:168
Inline: False
```
**Symbols:**

```
ffffffe0004e795a-ffffffe0004e79e0: dw_pcie_read_dbi2 (STB_GLOBAL)
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
u32 dw_pcie_read_dbi2(struct dw_pcie *pci, u32 reg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (0)
Location: drivers/pci/controller/dwc/pcie-designware.c:168
Inline: False
```
**Symbols:**

```
ffffffff815a509c-ffffffff815a50b1: dw_pcie_read_dbi2.cold (STB_LOCAL)
ffffffff815a4900-ffffffff815a497b: dw_pcie_read_dbi2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
u32 dw_pcie_read_dbi2(struct dw_pcie *pci, u32 reg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (0)
Location: drivers/pci/controller/dwc/pcie-designware.c:168
Inline: False
```
**Symbols:**

```
ffffffff8159423c-ffffffff81594251: dw_pcie_read_dbi2.cold (STB_LOCAL)
ffffffff81593aa0-ffffffff81593b1b: dw_pcie_read_dbi2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
u32 dw_pcie_read_dbi2(struct dw_pcie *pci, u32 reg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (0)
Location: drivers/pci/controller/dwc/pcie-designware.c:168
Inline: False
```
**Symbols:**

```
ffffffff815a562c-ffffffff815a5641: dw_pcie_read_dbi2.cold (STB_LOCAL)
ffffffff815a4e90-ffffffff815a4f0b: dw_pcie_read_dbi2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
u32 dw_pcie_read_dbi2(struct dw_pcie *pci, u32 reg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (0)
Location: drivers/pci/controller/dwc/pcie-designware.c:168
Inline: False
```
**Symbols:**

```
ffffffff815bfa2c-ffffffff815bfa41: dw_pcie_read_dbi2.cold (STB_LOCAL)
ffffffff815bf290-ffffffff815bf30b: dw_pcie_read_dbi2 (STB_GLOBAL)
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
