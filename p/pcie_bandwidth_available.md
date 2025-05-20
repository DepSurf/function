# Function: <code>pcie_bandwidth_available</code>

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
u32 pcie_bandwidth_available(struct pci_dev *dev, struct pci_dev **limiting_dev, enum pci_bus_speed *speed, enum pcie_link_width *width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81519620)
Location: drivers/pci/pci.c:5215
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcie_print_link_status
```
**Symbols:**

```
ffffffff81519620-ffffffff8151975d: pcie_bandwidth_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u32 pcie_bandwidth_available(struct pci_dev *dev, struct pci_dev **limiting_dev, enum pci_bus_speed *speed, enum pcie_link_width *width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8152f080)
Location: drivers/pci/pci.c:5503
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pcie_print_link_status
```
**Symbols:**

```
ffffffff8152f080-ffffffff8152f1bd: pcie_bandwidth_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u32 pcie_bandwidth_available(struct pci_dev *dev, struct pci_dev **limiting_dev, enum pci_bus_speed *speed, enum pcie_link_width *width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8155e7f0)
Location: drivers/pci/pci.c:5597
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pcie_print_link_status
```
**Symbols:**

```
ffffffff8155e7f0-ffffffff8155e922: pcie_bandwidth_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u32 pcie_bandwidth_available(struct pci_dev *dev, struct pci_dev **limiting_dev, enum pci_bus_speed *speed, enum pcie_link_width *width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8157f950)
Location: drivers/pci/pci.c:5727
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pcie_print_link_status
```
**Symbols:**

```
ffffffff8157f950-ffffffff8157fa82: pcie_bandwidth_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u32 pcie_bandwidth_available(struct pci_dev *dev, struct pci_dev **limiting_dev, enum pci_bus_speed *speed, enum pcie_link_width *width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81625000)
Location: drivers/pci/pci.c:5757
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pcie_print_link_status
```
**Symbols:**

```
ffffffff81625000-ffffffff81625147: pcie_bandwidth_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u32 pcie_bandwidth_available(struct pci_dev *dev, struct pci_dev **limiting_dev, enum pci_bus_speed *speed, enum pcie_link_width *width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8164ac30)
Location: drivers/pci/pci.c:5831
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pcie_print_link_status
```
**Symbols:**

```
ffffffff8164ac30-ffffffff8164ad87: pcie_bandwidth_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u32 pcie_bandwidth_available(struct pci_dev *dev, struct pci_dev **limiting_dev, enum pci_bus_speed *speed, enum pcie_link_width *width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162d810)
Location: drivers/pci/pci.c:5880
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pcie_print_link_status
```
**Symbols:**

```
ffffffff8162d810-ffffffff8162d931: pcie_bandwidth_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u32 pcie_bandwidth_available(struct pci_dev *dev, struct pci_dev **limiting_dev, enum pci_bus_speed *speed, enum pcie_link_width *width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8169cee0)
Location: drivers/pci/pci.c:6070
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pcie_print_link_status
```
**Symbols:**

```
ffffffff8169cee0-ffffffff8169d003: pcie_bandwidth_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u32 pcie_bandwidth_available(struct pci_dev *dev, struct pci_dev **limiting_dev, enum pci_bus_speed *speed, enum pcie_link_width *width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817beeb0)
Location: drivers/pci/pci.c:6166
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pcie_print_link_status
```
**Symbols:**

```
ffffffff817beeb0-ffffffff817befe0: pcie_bandwidth_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 pcie_bandwidth_available(struct pci_dev *dev, struct pci_dev **limiting_dev, enum pci_bus_speed *speed, enum pcie_link_width *width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818db310)
Location: drivers/pci/pci.c:6113
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pcie_print_link_status
```
**Symbols:**

```
ffffffff818db310-ffffffff818db440: pcie_bandwidth_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 pcie_bandwidth_available(struct pci_dev *dev, struct pci_dev **limiting_dev, enum pci_bus_speed *speed, enum pcie_link_width *width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8191e510)
Location: drivers/pci/pci.c:6235
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pcie_print_link_status
```
**Symbols:**

```
ffffffff8191e510-ffffffff8191e634: pcie_bandwidth_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 pcie_bandwidth_available(struct pci_dev *dev, struct pci_dev **limiting_dev, enum pci_bus_speed *speed, enum pcie_link_width *width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81966620)
Location: drivers/pci/pci.c:6380
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pcie_print_link_status
```
**Symbols:**

```
ffffffff81966620-ffffffff81966744: pcie_bandwidth_available (STB_GLOBAL)
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
u32 pcie_bandwidth_available(struct pci_dev *dev, struct pci_dev **limiting_dev, enum pci_bus_speed *speed, enum pcie_link_width *width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e2438)
Location: drivers/pci/pci.c:5727
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pcie_print_link_status
```
**Symbols:**

```
ffff8000106e2438-ffff8000106e25a8: pcie_bandwidth_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u32 pcie_bandwidth_available(struct pci_dev *dev, struct pci_dev **limiting_dev, enum pci_bus_speed *speed, enum pcie_link_width *width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c087e0d8)
Location: drivers/pci/pci.c:5727
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pcie_print_link_status
```
**Symbols:**

```
c087e0d8-c087e220: pcie_bandwidth_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u32 pcie_bandwidth_available(struct pci_dev *dev, struct pci_dev **limiting_dev, enum pci_bus_speed *speed, enum pcie_link_width *width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c00000000085bc50)
Location: drivers/pci/pci.c:5727
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pcie_print_link_status
```
**Symbols:**

```
c00000000085bc50-c00000000085be34: pcie_bandwidth_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u32 pcie_bandwidth_available(struct pci_dev *dev, struct pci_dev **limiting_dev, enum pci_bus_speed *speed, enum pcie_link_width *width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004b9e80)
Location: drivers/pci/pci.c:5727
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pcie_print_link_status
```
**Symbols:**

```
ffffffe0004b9e80-ffffffe0004b9fa0: pcie_bandwidth_available (STB_GLOBAL)
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
u32 pcie_bandwidth_available(struct pci_dev *dev, struct pci_dev **limiting_dev, enum pci_bus_speed *speed, enum pcie_link_width *width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81573e70)
Location: drivers/pci/pci.c:5727
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pcie_print_link_status
```
**Symbols:**

```
ffffffff81573e70-ffffffff81573fa2: pcie_bandwidth_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u32 pcie_bandwidth_available(struct pci_dev *dev, struct pci_dev **limiting_dev, enum pci_bus_speed *speed, enum pcie_link_width *width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815625d0)
Location: drivers/pci/pci.c:5727
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pcie_print_link_status
```
**Symbols:**

```
ffffffff815625d0-ffffffff81562702: pcie_bandwidth_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 pcie_bandwidth_available(struct pci_dev *dev, struct pci_dev **limiting_dev, enum pci_bus_speed *speed, enum pcie_link_width *width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815736a0)
Location: drivers/pci/pci.c:5727
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pcie_print_link_status
```
**Symbols:**

```
ffffffff815736a0-ffffffff815737d2: pcie_bandwidth_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 pcie_bandwidth_available(struct pci_dev *dev, struct pci_dev **limiting_dev, enum pci_bus_speed *speed, enum pcie_link_width *width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8158db80)
Location: drivers/pci/pci.c:5727
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pcie_print_link_status
```
**Symbols:**

```
ffffffff8158db80-ffffffff8158dcb2: pcie_bandwidth_available (STB_GLOBAL)
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
