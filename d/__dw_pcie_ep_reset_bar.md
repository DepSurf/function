# Function: <code>__dw_pcie_ep_reset_bar</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff81549a55)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:22
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
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
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff81560275)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:22
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
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
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff815906b5)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:22
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
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
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff815b23e5)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:22
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
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
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8165bf05)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:31
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __dw_pcie_ep_reset_bar(struct dw_pcie *pci, u8 func_no, enum pci_barno bar, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8167c9c0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:57
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
```
**Symbols:**

```
ffffffff8167c9c0-ffffffff8167cab0: __dw_pcie_ep_reset_bar (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __dw_pcie_ep_reset_bar(struct dw_pcie *pci, u8 func_no, enum pci_barno bar, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8165f830)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:57
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
```
**Symbols:**

```
ffffffff8165f830-ffffffff8165f920: __dw_pcie_ep_reset_bar (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __dw_pcie_ep_reset_bar(struct dw_pcie *pci, u8 func_no, enum pci_barno bar, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff816d2420)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:57
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
```
**Symbols:**

```
ffffffff816d2420-ffffffff816d2510: __dw_pcie_ep_reset_bar (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __dw_pcie_ep_reset_bar(struct dw_pcie *pci, u8 func_no, enum pci_barno bar, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff817fb800)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:57
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
```
**Symbols:**

```
ffffffff817fb800-ffffffff817fb900: __dw_pcie_ep_reset_bar (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __dw_pcie_ep_reset_bar(struct dw_pcie *pci, u8 func_no, enum pci_barno bar, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff81928580)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:55
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
```
**Symbols:**

```
ffffffff81928580-ffffffff81928680: __dw_pcie_ep_reset_bar (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __dw_pcie_ep_reset_bar(struct dw_pcie *pci, u8 func_no, enum pci_barno bar, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8196c7b0)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:55
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
```
**Symbols:**

```
ffffffff8196c7b0-ffffffff8196c8b0: __dw_pcie_ep_reset_bar (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff819b6e09)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:47
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
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
void __dw_pcie_ep_reset_bar(struct dw_pcie *pci, enum pci_barno bar, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffff80001072f888)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:22
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
```
**Symbols:**

```
ffff80001072f888-ffff80001072f968: __dw_pcie_ep_reset_bar (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __dw_pcie_ep_reset_bar(struct dw_pcie *pci, enum pci_barno bar, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (c08b8c0c)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:22
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
```
**Symbols:**

```
c08b8c0c-c08b8cd8: __dw_pcie_ep_reset_bar (STB_LOCAL)
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
void __dw_pcie_ep_reset_bar(struct dw_pcie *pci, enum pci_barno bar, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffe0004e992a)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:22
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
```
**Symbols:**

```
ffffffe0004e992a-ffffffe0004e9a02: __dw_pcie_ep_reset_bar (STB_LOCAL)
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
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff815a5ba5)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:22
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
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
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff81594d45)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:22
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
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
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff815a6135)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:22
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
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
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff815c0535)
Location: drivers/pci/controller/dwc/pcie-designware-ep.c:22
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_reset_bar
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
</ul>
<b>Arch</b>
<ul>
</ul>
