# Function: <code>pcie_get_speed_cap</code>

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
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
enum pci_bus_speed pcie_get_speed_cap(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151ed90)
Location: drivers/pci/pci.c:5266
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcie_bandwidth_capable
  - drivers/pci/pci-sysfs.c:max_link_speed_show
  - drivers/pci/pci-sysfs.c:max_link_speed_show
  - drivers/pci/pci-sysfs.c:max_link_speed_show
  - drivers/pci/pci-sysfs.c:max_link_speed_show
```
**Symbols:**

```
ffffffff8151ed90-ffffffff8151ee5b: pcie_get_speed_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
enum pci_bus_speed pcie_get_speed_cap(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81530f40)
Location: drivers/pci/pci.c:5554
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcie_bandwidth_capable
  - drivers/pci/pci-sysfs.c:max_link_speed_show
  - drivers/pci/pci-sysfs.c:max_link_speed_show
  - drivers/pci/pci-sysfs.c:max_link_speed_show
  - drivers/pci/pci-sysfs.c:max_link_speed_show
```
**Symbols:**

```
ffffffff81530f40-ffffffff81530ff1: pcie_get_speed_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
enum pci_bus_speed pcie_get_speed_cap(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81560880)
Location: drivers/pci/pci.c:5648
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcie_bandwidth_capable
  - drivers/pci/pci-sysfs.c:max_link_speed_show
  - drivers/pci/pci-sysfs.c:max_link_speed_show
  - drivers/pci/pci-sysfs.c:max_link_speed_show
  - drivers/pci/pci-sysfs.c:max_link_speed_show
```
**Symbols:**

```
ffffffff81560880-ffffffff8156093d: pcie_get_speed_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
enum pci_bus_speed pcie_get_speed_cap(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815819a0)
Location: drivers/pci/pci.c:5778
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcie_bandwidth_capable
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci-sysfs.c:max_link_speed_show
  - drivers/pci/pci-sysfs.c:max_link_speed_show
  - drivers/pci/pci-sysfs.c:max_link_speed_show
  - drivers/pci/pci-sysfs.c:max_link_speed_show
```
**Symbols:**

```
ffffffff815819a0-ffffffff81581a5d: pcie_get_speed_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
enum pci_bus_speed pcie_get_speed_cap(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81625240)
Location: drivers/pci/pci.c:5808
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcie_bandwidth_capable
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci-sysfs.c:max_link_speed_show
```
**Symbols:**

```
ffffffff81625240-ffffffff816252f2: pcie_get_speed_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
enum pci_bus_speed pcie_get_speed_cap(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8164b370)
Location: drivers/pci/pci.c:5882
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcie_bandwidth_capable
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci-sysfs.c:max_link_speed_show
```
**Symbols:**

```
ffffffff8164b370-ffffffff8164b42c: pcie_get_speed_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum pci_bus_speed pcie_get_speed_cap(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162df50)
Location: drivers/pci/pci.c:5931
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcie_bandwidth_capable
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci-sysfs.c:max_link_speed_show
```
**Symbols:**

```
ffffffff8162df50-ffffffff8162e00c: pcie_get_speed_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
enum pci_bus_speed pcie_get_speed_cap(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8169c9d0)
Location: drivers/pci/pci.c:6121
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcie_bandwidth_capable
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci-sysfs.c:max_link_speed_show
```
**Symbols:**

```
ffffffff8169c9d0-ffffffff8169ca8c: pcie_get_speed_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
enum pci_bus_speed pcie_get_speed_cap(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817be9d0)
Location: drivers/pci/pci.c:6217
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcie_bandwidth_capable
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci-sysfs.c:max_link_speed_show
```
**Symbols:**

```
ffffffff817be9d0-ffffffff817bea9b: pcie_get_speed_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum pci_bus_speed pcie_get_speed_cap(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818dae80)
Location: drivers/pci/pci.c:6164
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcie_bandwidth_capable
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci-sysfs.c:max_link_speed_show
```
**Symbols:**

```
ffffffff818dae80-ffffffff818daf4b: pcie_get_speed_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum pci_bus_speed pcie_get_speed_cap(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8191e1e0)
Location: drivers/pci/pci.c:6286
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcie_bandwidth_capable
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci-sysfs.c:max_link_speed_show
```
**Symbols:**

```
ffffffff8191e1e0-ffffffff8191e2ab: pcie_get_speed_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
enum pci_bus_speed pcie_get_speed_cap(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81966260)
Location: drivers/pci/pci.c:6430
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcie_bandwidth_capable
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci-sysfs.c:max_link_speed_show
```
**Symbols:**

```
ffffffff81966260-ffffffff8196632b: pcie_get_speed_cap (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
enum pci_bus_speed pcie_get_speed_cap(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e4b28)
Location: drivers/pci/pci.c:5778
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcie_bandwidth_capable
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci-sysfs.c:max_link_speed_show
  - drivers/pci/pci-sysfs.c:max_link_speed_show
  - drivers/pci/pci-sysfs.c:max_link_speed_show
  - drivers/pci/pci-sysfs.c:max_link_speed_show
```
**Symbols:**

```
ffff8000106e4b28-ffff8000106e4bf4: pcie_get_speed_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
enum pci_bus_speed pcie_get_speed_cap(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c0880838)
Location: drivers/pci/pci.c:5778
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcie_bandwidth_capable
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci-sysfs.c:max_link_speed_show
  - drivers/pci/pci-sysfs.c:max_link_speed_show
  - drivers/pci/pci-sysfs.c:max_link_speed_show
  - drivers/pci/pci-sysfs.c:max_link_speed_show
```
**Symbols:**

```
c0880838-c0880914: pcie_get_speed_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
enum pci_bus_speed pcie_get_speed_cap(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c00000000085f320)
Location: drivers/pci/pci.c:5778
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcie_bandwidth_capable
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci-sysfs.c:max_link_speed_show
  - drivers/pci/pci-sysfs.c:max_link_speed_show
  - drivers/pci/pci-sysfs.c:max_link_speed_show
  - drivers/pci/pci-sysfs.c:max_link_speed_show
```
**Symbols:**

```
c00000000085f320-c00000000085f424: pcie_get_speed_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
enum pci_bus_speed pcie_get_speed_cap(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bbf02)
Location: drivers/pci/pci.c:5778
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcie_bandwidth_capable
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci-sysfs.c:max_link_speed_show
  - drivers/pci/pci-sysfs.c:max_link_speed_show
  - drivers/pci/pci-sysfs.c:max_link_speed_show
  - drivers/pci/pci-sysfs.c:max_link_speed_show
```
**Symbols:**

```
ffffffe0004bbf02-ffffffe0004bbf90: pcie_get_speed_cap (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
enum pci_bus_speed pcie_get_speed_cap(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81575ec0)
Location: drivers/pci/pci.c:5778
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcie_bandwidth_capable
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci-sysfs.c:max_link_speed_show
  - drivers/pci/pci-sysfs.c:max_link_speed_show
  - drivers/pci/pci-sysfs.c:max_link_speed_show
  - drivers/pci/pci-sysfs.c:max_link_speed_show
```
**Symbols:**

```
ffffffff81575ec0-ffffffff81575f7d: pcie_get_speed_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
enum pci_bus_speed pcie_get_speed_cap(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81564620)
Location: drivers/pci/pci.c:5778
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcie_bandwidth_capable
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci-sysfs.c:max_link_speed_show
  - drivers/pci/pci-sysfs.c:max_link_speed_show
  - drivers/pci/pci-sysfs.c:max_link_speed_show
  - drivers/pci/pci-sysfs.c:max_link_speed_show
```
**Symbols:**

```
ffffffff81564620-ffffffff815646dd: pcie_get_speed_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
enum pci_bus_speed pcie_get_speed_cap(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815756f0)
Location: drivers/pci/pci.c:5778
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcie_bandwidth_capable
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci-sysfs.c:max_link_speed_show
  - drivers/pci/pci-sysfs.c:max_link_speed_show
  - drivers/pci/pci-sysfs.c:max_link_speed_show
  - drivers/pci/pci-sysfs.c:max_link_speed_show
```
**Symbols:**

```
ffffffff815756f0-ffffffff815757ad: pcie_get_speed_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
enum pci_bus_speed pcie_get_speed_cap(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8158fcc0)
Location: drivers/pci/pci.c:5778
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcie_bandwidth_capable
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci-sysfs.c:max_link_speed_show
  - drivers/pci/pci-sysfs.c:max_link_speed_show
  - drivers/pci/pci-sysfs.c:max_link_speed_show
  - drivers/pci/pci-sysfs.c:max_link_speed_show
```
**Symbols:**

```
ffffffff8158fcc0-ffffffff8158fd7d: pcie_get_speed_cap (STB_GLOBAL)
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
