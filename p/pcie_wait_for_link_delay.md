# Function: <code>pcie_wait_for_link_delay</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
bool pcie_wait_for_link_delay(struct pci_dev *pdev, bool active, int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4615
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pcie_wait_for_link
```
**Symbols:**

```
ffffffff8157f7b0-ffffffff8157f898: pcie_wait_for_link_delay (STB_LOCAL)
ffffffff81585c85-ffffffff81585cb5: pcie_wait_for_link_delay.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
bool pcie_wait_for_link_delay(struct pci_dev *pdev, bool active, int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4645
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pcie_wait_for_link
```
**Symbols:**

```
ffffffff81624e60-ffffffff81624f49: pcie_wait_for_link_delay (STB_LOCAL)
ffffffff8162ca02-ffffffff8162ca32: pcie_wait_for_link_delay.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool pcie_wait_for_link_delay(struct pci_dev *pdev, bool active, int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8164aa90)
Location: drivers/pci/pci.c:4720
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pcie_wait_for_link
```
**Symbols:**

```
ffffffff8164aa90-ffffffff8164ab78: pcie_wait_for_link_delay (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool pcie_wait_for_link_delay(struct pci_dev *pdev, bool active, int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162d670)
Location: drivers/pci/pci.c:4769
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pcie_wait_for_link
```
**Symbols:**

```
ffffffff8162d670-ffffffff8162d758: pcie_wait_for_link_delay (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool pcie_wait_for_link_delay(struct pci_dev *pdev, bool active, int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8169cd40)
Location: drivers/pci/pci.c:4821
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pcie_wait_for_link
```
**Symbols:**

```
ffffffff8169cd40-ffffffff8169ce28: pcie_wait_for_link_delay (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool pcie_wait_for_link_delay(struct pci_dev *pdev, bool active, int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817bece0)
Location: drivers/pci/pci.c:4917
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pcie_wait_for_link
```
**Symbols:**

```
ffffffff817bece0-ffffffff817bedd9: pcie_wait_for_link_delay (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool pcie_wait_for_link_delay(struct pci_dev *pdev, bool active, int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818db110)
Location: drivers/pci/pci.c:4860
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pcie_wait_for_link
```
**Symbols:**

```
ffffffff818db110-ffffffff818db209: pcie_wait_for_link_delay (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool pcie_wait_for_link_delay(struct pci_dev *pdev, bool active, int delay);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81926d35)
Location: drivers/pci/pci.c:4967
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_wait_for_link
Direct callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
```
**Symbols:**

```
ffffffff8191f2c0-ffffffff8191f360: pcie_wait_for_link_delay (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool pcie_wait_for_link_delay(struct pci_dev *pdev, bool active, int delay);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8196f4d5)
Location: drivers/pci/pci.c:5077
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_wait_for_link
Direct callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
```
**Symbols:**

```
ffffffff81967430-ffffffff819674d0: pcie_wait_for_link_delay (STB_LOCAL)
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
bool pcie_wait_for_link_delay(struct pci_dev *pdev, bool active, int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e2248)
Location: drivers/pci/pci.c:4615
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pcie_wait_for_link
```
**Symbols:**

```
ffff8000106e2248-ffff8000106e2368: pcie_wait_for_link_delay (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool pcie_wait_for_link_delay(struct pci_dev *pdev, bool active, int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c087dedc)
Location: drivers/pci/pci.c:4615
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pcie_wait_for_link
```
**Symbols:**

```
c087dedc-c087e000: pcie_wait_for_link_delay (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool pcie_wait_for_link_delay(struct pci_dev *pdev, bool active, int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c00000000085b9a0)
Location: drivers/pci/pci.c:4615
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pcie_wait_for_link
```
**Symbols:**

```
c00000000085b9a0-c00000000085bb50: pcie_wait_for_link_delay (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool pcie_wait_for_link_delay(struct pci_dev *pdev, bool active, int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004b9d0e)
Location: drivers/pci/pci.c:4615
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pcie_wait_for_link
```
**Symbols:**

```
ffffffe0004b9d0e-ffffffe0004b9dfc: pcie_wait_for_link_delay (STB_LOCAL)
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
bool pcie_wait_for_link_delay(struct pci_dev *pdev, bool active, int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4615
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pcie_wait_for_link
```
**Symbols:**

```
ffffffff81573cd0-ffffffff81573db8: pcie_wait_for_link_delay (STB_LOCAL)
ffffffff8157a1a5-ffffffff8157a1d5: pcie_wait_for_link_delay.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
bool pcie_wait_for_link_delay(struct pci_dev *pdev, bool active, int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4615
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pcie_wait_for_link
```
**Symbols:**

```
ffffffff81562430-ffffffff81562518: pcie_wait_for_link_delay (STB_LOCAL)
ffffffff815688e5-ffffffff81568915: pcie_wait_for_link_delay.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
bool pcie_wait_for_link_delay(struct pci_dev *pdev, bool active, int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4615
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pcie_wait_for_link
```
**Symbols:**

```
ffffffff81573500-ffffffff815735e8: pcie_wait_for_link_delay (STB_LOCAL)
ffffffff815799d5-ffffffff81579a05: pcie_wait_for_link_delay.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
bool pcie_wait_for_link_delay(struct pci_dev *pdev, bool active, int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4615
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pcie_wait_for_link
```
**Symbols:**

```
ffffffff8158d9e0-ffffffff8158dac8: pcie_wait_for_link_delay (STB_LOCAL)
ffffffff81593e85-ffffffff81593eb5: pcie_wait_for_link_delay.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
