# Function: <code>pcie_bandwidth_capable</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
u32 pcie_bandwidth_capable(struct pci_dev *dev, enum pci_bus_speed *speed, enum pcie_link_width *width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151eec0)
Location: drivers/pci/pci.c:5331
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcie_print_link_status
```
**Symbols:**

```
ffffffff8151eec0-ffffffff8151ef80: pcie_bandwidth_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u32 pcie_bandwidth_capable(struct pci_dev *dev, enum pci_bus_speed *speed, enum pcie_link_width *width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81534e40)
Location: drivers/pci/pci.c:5619
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pcie_print_link_status
```
**Symbols:**

```
ffffffff81534e40-ffffffff81534f00: pcie_bandwidth_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u32 pcie_bandwidth_capable(struct pci_dev *dev, enum pci_bus_speed *speed, enum pcie_link_width *width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81564300)
Location: drivers/pci/pci.c:5715
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pcie_print_link_status
```
**Symbols:**

```
ffffffff81564300-ffffffff815643bc: pcie_bandwidth_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u32 pcie_bandwidth_capable(struct pci_dev *dev, enum pci_bus_speed *speed, enum pcie_link_width *width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815855e0)
Location: drivers/pci/pci.c:5845
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pcie_print_link_status
```
**Symbols:**

```
ffffffff815855e0-ffffffff8158569c: pcie_bandwidth_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u32 pcie_bandwidth_capable(struct pci_dev *dev, enum pci_bus_speed *speed, enum pcie_link_width *width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162c140)
Location: drivers/pci/pci.c:5866
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pcie_print_link_status
```
**Symbols:**

```
ffffffff8162c140-ffffffff8162c209: pcie_bandwidth_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u32 pcie_bandwidth_capable(struct pci_dev *dev, enum pci_bus_speed *speed, enum pcie_link_width *width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81651e90)
Location: drivers/pci/pci.c:5940
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pcie_print_link_status
```
**Symbols:**

```
ffffffff81651e90-ffffffff81651f66: pcie_bandwidth_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u32 pcie_bandwidth_capable(struct pci_dev *dev, enum pci_bus_speed *speed, enum pcie_link_width *width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81634980)
Location: drivers/pci/pci.c:5989
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pcie_print_link_status
```
**Symbols:**

```
ffffffff81634980-ffffffff81634a1c: pcie_bandwidth_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u32 pcie_bandwidth_capable(struct pci_dev *dev, enum pci_bus_speed *speed, enum pcie_link_width *width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816a4a70)
Location: drivers/pci/pci.c:6179
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pcie_print_link_status
```
**Symbols:**

```
ffffffff816a4a70-ffffffff816a4b0c: pcie_bandwidth_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u32 pcie_bandwidth_capable(struct pci_dev *dev, enum pci_bus_speed *speed, enum pcie_link_width *width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c6ee0)
Location: drivers/pci/pci.c:6275
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pcie_print_link_status
```
**Symbols:**

```
ffffffff817c6ee0-ffffffff817c6f95: pcie_bandwidth_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 pcie_bandwidth_capable(struct pci_dev *dev, enum pci_bus_speed *speed, enum pcie_link_width *width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818e4390)
Location: drivers/pci/pci.c:6222
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pcie_print_link_status
```
**Symbols:**

```
ffffffff818e4390-ffffffff818e4445: pcie_bandwidth_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 pcie_bandwidth_capable(struct pci_dev *dev, enum pci_bus_speed *speed, enum pcie_link_width *width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff819279e0)
Location: drivers/pci/pci.c:6344
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pcie_print_link_status
```
**Symbols:**

```
ffffffff819279e0-ffffffff81927a95: pcie_bandwidth_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 pcie_bandwidth_capable(struct pci_dev *dev, enum pci_bus_speed *speed, enum pcie_link_width *width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81970180)
Location: drivers/pci/pci.c:6488
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pcie_print_link_status
```
**Symbols:**

```
ffffffff81970180-ffffffff81970235: pcie_bandwidth_capable (STB_GLOBAL)
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
u32 pcie_bandwidth_capable(struct pci_dev *dev, enum pci_bus_speed *speed, enum pcie_link_width *width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e9d30)
Location: drivers/pci/pci.c:5845
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pcie_print_link_status
```
**Symbols:**

```
ffff8000106e9d30-ffff8000106e9e20: pcie_bandwidth_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u32 pcie_bandwidth_capable(struct pci_dev *dev, enum pci_bus_speed *speed, enum pcie_link_width *width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c0884cac)
Location: drivers/pci/pci.c:5845
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pcie_print_link_status
```
**Symbols:**

```
c0884cac-c0884d90: pcie_bandwidth_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u32 pcie_bandwidth_capable(struct pci_dev *dev, enum pci_bus_speed *speed, enum pcie_link_width *width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c000000000864e90)
Location: drivers/pci/pci.c:5845
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pcie_print_link_status
```
**Symbols:**

```
c000000000864e90-c000000000864fc4: pcie_bandwidth_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u32 pcie_bandwidth_capable(struct pci_dev *dev, enum pci_bus_speed *speed, enum pcie_link_width *width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bffb8)
Location: drivers/pci/pci.c:5845
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pcie_print_link_status
```
**Symbols:**

```
ffffffe0004bffb8-ffffffe0004c0088: pcie_bandwidth_capable (STB_GLOBAL)
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
u32 pcie_bandwidth_capable(struct pci_dev *dev, enum pci_bus_speed *speed, enum pcie_link_width *width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81579b00)
Location: drivers/pci/pci.c:5845
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pcie_print_link_status
```
**Symbols:**

```
ffffffff81579b00-ffffffff81579bbc: pcie_bandwidth_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u32 pcie_bandwidth_capable(struct pci_dev *dev, enum pci_bus_speed *speed, enum pcie_link_width *width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81568240)
Location: drivers/pci/pci.c:5845
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pcie_print_link_status
```
**Symbols:**

```
ffffffff81568240-ffffffff815682fc: pcie_bandwidth_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 pcie_bandwidth_capable(struct pci_dev *dev, enum pci_bus_speed *speed, enum pcie_link_width *width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81579330)
Location: drivers/pci/pci.c:5845
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pcie_print_link_status
```
**Symbols:**

```
ffffffff81579330-ffffffff815793ec: pcie_bandwidth_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 pcie_bandwidth_capable(struct pci_dev *dev, enum pci_bus_speed *speed, enum pcie_link_width *width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815937c0)
Location: drivers/pci/pci.c:5845
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pcie_print_link_status
```
**Symbols:**

```
ffffffff815937c0-ffffffff8159387c: pcie_bandwidth_capable (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
