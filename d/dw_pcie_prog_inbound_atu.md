# Function: <code>dw_pcie_prog_inbound_atu</code>

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
int dw_pcie_prog_inbound_atu(struct dw_pcie *pci, int index, int bar, u64 cpu_addr, enum dw_pcie_as_type as_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/dwc/pcie-designware.c (ffffffff814d3420)
Location: drivers/pci/dwc/pcie-designware.c:247
Inline: False
```
**Symbols:**

```
ffffffff814d3420-ffffffff814d3566: dw_pcie_prog_inbound_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dw_pcie_prog_inbound_atu(struct dw_pcie *pci, int index, int bar, u64 cpu_addr, enum dw_pcie_as_type as_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/dwc/pcie-designware.c (ffffffff81513720)
Location: drivers/pci/dwc/pcie-designware.c:249
Inline: False
```
**Symbols:**

```
ffffffff81513720-ffffffff81513945: dw_pcie_prog_inbound_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dw_pcie_prog_inbound_atu(struct dw_pcie *pci, int index, int bar, u64 cpu_addr, enum dw_pcie_as_type as_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81548b00)
Location: drivers/pci/controller/dwc/pcie-designware.c:246
Inline: False
```
**Symbols:**

```
ffffffff81548b00-ffffffff81548d2a: dw_pcie_prog_inbound_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dw_pcie_prog_inbound_atu(struct dw_pcie *pci, int index, int bar, u64 cpu_addr, enum dw_pcie_as_type as_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8155f1d0)
Location: drivers/pci/controller/dwc/pcie-designware.c:246
Inline: False
```
**Symbols:**

```
ffffffff8155f1d0-ffffffff8155f403: dw_pcie_prog_inbound_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dw_pcie_prog_inbound_atu(struct dw_pcie *pci, int index, int bar, u64 cpu_addr, enum dw_pcie_as_type as_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (0)
Location: drivers/pci/controller/dwc/pcie-designware.c:300
Inline: False
```
**Symbols:**

```
ffffffff8158fbee-ffffffff8158fc22: dw_pcie_prog_inbound_atu.cold (STB_LOCAL)
ffffffff8158f7f0-ffffffff8158f9c2: dw_pcie_prog_inbound_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int dw_pcie_prog_inbound_atu(struct dw_pcie *pci, int index, int bar, u64 cpu_addr, enum dw_pcie_as_type as_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (0)
Location: drivers/pci/controller/dwc/pcie-designware.c:380
Inline: False
```
**Symbols:**

```
ffffffff815b1956-ffffffff815b198a: dw_pcie_prog_inbound_atu.cold (STB_LOCAL)
ffffffff815b1560-ffffffff815b1732: dw_pcie_prog_inbound_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dw_pcie_prog_inbound_atu(struct dw_pcie *pci, int index, int bar, u64 cpu_addr, enum dw_pcie_as_type as_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (0)
Location: drivers/pci/controller/dwc/pcie-designware.c:384
Inline: False
```
**Symbols:**

```
ffffffff8165b1e5-ffffffff8165b219: dw_pcie_prog_inbound_atu.cold (STB_LOCAL)
ffffffff8165add0-ffffffff8165afa2: dw_pcie_prog_inbound_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dw_pcie_prog_inbound_atu(struct dw_pcie *pci, u8 func_no, int index, int bar, u64 cpu_addr, enum dw_pcie_as_type as_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (0)
Location: drivers/pci/controller/dwc/pcie-designware.c:392
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
```
**Symbols:**

```
ffffffff81bfdf20-ffffffff81bfdf54: dw_pcie_prog_inbound_atu.cold (STB_LOCAL)
ffffffff8167b070-ffffffff8167b253: dw_pcie_prog_inbound_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dw_pcie_prog_inbound_atu(struct dw_pcie *pci, u8 func_no, int index, int bar, u64 cpu_addr, enum dw_pcie_as_type as_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (0)
Location: drivers/pci/controller/dwc/pcie-designware.c:442
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
```
**Symbols:**

```
ffffffff81befd7f-ffffffff81befdb3: dw_pcie_prog_inbound_atu.cold (STB_LOCAL)
ffffffff8165dad0-ffffffff8165dcaf: dw_pcie_prog_inbound_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dw_pcie_prog_inbound_atu(struct dw_pcie *pci, u8 func_no, int index, int bar, u64 cpu_addr, enum dw_pcie_as_type as_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (0)
Location: drivers/pci/controller/dwc/pcie-designware.c:442
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
```
**Symbols:**

```
ffffffff81ceb3d4-ffffffff81ceb408: dw_pcie_prog_inbound_atu.cold (STB_LOCAL)
ffffffff816d0540-ffffffff816d071f: dw_pcie_prog_inbound_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dw_pcie_prog_inbound_atu(struct dw_pcie *pci, u8 func_no, int index, int bar, u64 cpu_addr, enum dw_pcie_as_type as_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (0)
Location: drivers/pci/controller/dwc/pcie-designware.c:446
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
```
**Symbols:**

```
ffffffff81eb27ee-ffffffff81eb2808: dw_pcie_prog_inbound_atu.cold (STB_LOCAL)
ffffffff817f9440-ffffffff817f964a: dw_pcie_prog_inbound_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dw_pcie_prog_inbound_atu(struct dw_pcie *pci, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff819257d0)
Location: drivers/pci/controller/dwc/pcie-designware.c:541
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_iatu_setup
```
**Symbols:**

```
ffffffff819257d0-ffffffff819259d0: dw_pcie_prog_inbound_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dw_pcie_prog_inbound_atu(struct dw_pcie *pci, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81969580)
Location: drivers/pci/controller/dwc/pcie-designware.c:554
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_iatu_setup
```
**Symbols:**

```
ffffffff81969580-ffffffff81969780: dw_pcie_prog_inbound_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dw_pcie_prog_inbound_atu(struct dw_pcie *pci, int index, int type, u64 cpu_addr, u64 pci_addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff819b2d30)
Location: drivers/pci/controller/dwc/pcie-designware.c:555
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_iatu_setup
```
**Symbols:**

```
ffffffff819b2d30-ffffffff819b2f30: dw_pcie_prog_inbound_atu (STB_GLOBAL)
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
int dw_pcie_prog_inbound_atu(struct dw_pcie *pci, int index, int bar, u64 cpu_addr, enum dw_pcie_as_type as_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffff80001072d690)
Location: drivers/pci/controller/dwc/pcie-designware.c:380
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
```
**Symbols:**

```
ffff80001072d690-ffff80001072d884: dw_pcie_prog_inbound_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dw_pcie_prog_inbound_atu(struct dw_pcie *pci, int index, int bar, u64 cpu_addr, enum dw_pcie_as_type as_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (c08b6dfc)
Location: drivers/pci/controller/dwc/pcie-designware.c:380
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
```
**Symbols:**

```
c08b6dfc-c08b6fe0: dw_pcie_prog_inbound_atu (STB_GLOBAL)
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
int dw_pcie_prog_inbound_atu(struct dw_pcie *pci, int index, int bar, u64 cpu_addr, enum dw_pcie_as_type as_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffe0004e7d5a)
Location: drivers/pci/controller/dwc/pcie-designware.c:380
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
```
**Symbols:**

```
ffffffe0004e7d5a-ffffffe0004e7f12: dw_pcie_prog_inbound_atu (STB_GLOBAL)
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
int dw_pcie_prog_inbound_atu(struct dw_pcie *pci, int index, int bar, u64 cpu_addr, enum dw_pcie_as_type as_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (0)
Location: drivers/pci/controller/dwc/pcie-designware.c:380
Inline: False
```
**Symbols:**

```
ffffffff815a5116-ffffffff815a514a: dw_pcie_prog_inbound_atu.cold (STB_LOCAL)
ffffffff815a4d20-ffffffff815a4ef2: dw_pcie_prog_inbound_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int dw_pcie_prog_inbound_atu(struct dw_pcie *pci, int index, int bar, u64 cpu_addr, enum dw_pcie_as_type as_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (0)
Location: drivers/pci/controller/dwc/pcie-designware.c:380
Inline: False
```
**Symbols:**

```
ffffffff815942b6-ffffffff815942ea: dw_pcie_prog_inbound_atu.cold (STB_LOCAL)
ffffffff81593ec0-ffffffff81594092: dw_pcie_prog_inbound_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int dw_pcie_prog_inbound_atu(struct dw_pcie *pci, int index, int bar, u64 cpu_addr, enum dw_pcie_as_type as_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (0)
Location: drivers/pci/controller/dwc/pcie-designware.c:380
Inline: False
```
**Symbols:**

```
ffffffff815a56a6-ffffffff815a56da: dw_pcie_prog_inbound_atu.cold (STB_LOCAL)
ffffffff815a52b0-ffffffff815a5482: dw_pcie_prog_inbound_atu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int dw_pcie_prog_inbound_atu(struct dw_pcie *pci, int index, int bar, u64 cpu_addr, enum dw_pcie_as_type as_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (0)
Location: drivers/pci/controller/dwc/pcie-designware.c:380
Inline: False
```
**Symbols:**

```
ffffffff815bfaa6-ffffffff815bfada: dw_pcie_prog_inbound_atu.cold (STB_LOCAL)
ffffffff815bf6b0-ffffffff815bf882: dw_pcie_prog_inbound_atu (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 func_no</code>
</li>
<li>
<b>Param reordered. </b>
<code>pci, index, bar, cpu_addr, as_type</code> ➡️ <code>pci, func_no, index, bar, cpu_addr, as_type</code>
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
<b>Param added. </b>
<code>int type</code>
</li>
<li>
<b>Param added. </b>
<code>u64 pci_addr</code>
</li>
<li>
<b>Param added. </b>
<code>u64 size</code>
</li>
<li>
<b>Param removed. </b>
<code>u8 func_no</code>
</li>
<li>
<b>Param removed. </b>
<code>int bar</code>
</li>
<li>
<b>Param removed. </b>
<code>enum dw_pcie_as_type as_type</code>
</li>
<li>
<b>Param reordered. </b>
<code>pci, func_no, index, bar, cpu_addr, as_type</code> ➡️ <code>pci, index, type, cpu_addr, pci_addr, size</code>
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
