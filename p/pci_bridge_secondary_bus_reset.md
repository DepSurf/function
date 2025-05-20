# Function: <code>pci_bridge_secondary_bus_reset</code>

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
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int pci_bridge_secondary_bus_reset(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81534db5)
Location: drivers/pci/pci.c:4603
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_parent_bus_reset
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
```
**Symbols:**

```
ffffffff81534630-ffffffff81534654: pci_bridge_secondary_bus_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int pci_bridge_secondary_bus_reset(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81564277)
Location: drivers/pci/pci.c:4700
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_parent_bus_reset
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
```
**Symbols:**

```
ffffffff81563ae0-ffffffff81563b06: pci_bridge_secondary_bus_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int pci_bridge_secondary_bus_reset(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81585557)
Location: drivers/pci/pci.c:4830
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_parent_bus_reset
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
```
**Symbols:**

```
ffffffff81584dc0-ffffffff81584de6: pci_bridge_secondary_bus_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int pci_bridge_secondary_bus_reset(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162c088)
Location: drivers/pci/pci.c:4860
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_parent_bus_reset
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
```
**Symbols:**

```
ffffffff8162ba20-ffffffff8162ba48: pci_bridge_secondary_bus_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int pci_bridge_secondary_bus_reset(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81651dd8)
Location: drivers/pci/pci.c:4934
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_parent_bus_reset
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
```
**Symbols:**

```
ffffffff81651720-ffffffff81651748: pci_bridge_secondary_bus_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int pci_bridge_secondary_bus_reset(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816348c8)
Location: drivers/pci/pci.c:4983
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_parent_bus_reset
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
```
**Symbols:**

```
ffffffff81634190-ffffffff816341b8: pci_bridge_secondary_bus_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int pci_bridge_secondary_bus_reset(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816a49b8)
Location: drivers/pci/pci.c:5035
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_reset_bus_function
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
```
**Symbols:**

```
ffffffff816a4370-ffffffff816a4398: pci_bridge_secondary_bus_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int pci_bridge_secondary_bus_reset(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c6e18)
Location: drivers/pci/pci.c:5131
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_reset_bus_function
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
```
**Symbols:**

```
ffffffff817c6790-ffffffff817c67bf: pci_bridge_secondary_bus_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int pci_bridge_secondary_bus_reset(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818e42b8)
Location: drivers/pci/pci.c:5067
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_reset_bus_function
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
```
**Symbols:**

```
ffffffff818e3b40-ffffffff818e3b76: pci_bridge_secondary_bus_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int pci_bridge_secondary_bus_reset(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff819274d3)
Location: drivers/pci/pci.c:5190
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reset_bus_function
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
```
**Symbols:**

```
ffffffff81927140-ffffffff8192716f: pci_bridge_secondary_bus_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int pci_bridge_secondary_bus_reset(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8196fc73)
Location: drivers/pci/pci.c:5300
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reset_bus_function
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
```
**Symbols:**

```
ffffffff8196f8e0-ffffffff8196f90f: pci_bridge_secondary_bus_reset (STB_GLOBAL)
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
int pci_bridge_secondary_bus_reset(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e9c88)
Location: drivers/pci/pci.c:4830
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_parent_bus_reset
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
```
**Symbols:**

```
ffff8000106e9460-ffff8000106e949c: pci_bridge_secondary_bus_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int pci_bridge_secondary_bus_reset(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c0884c20)
Location: drivers/pci/pci.c:4830
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_parent_bus_reset
```
**Symbols:**

```
c08843f0-c0884420: pci_bridge_secondary_bus_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int pci_bridge_secondary_bus_reset(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c000000000864db4)
Location: drivers/pci/pci.c:4830
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_parent_bus_reset
```
**Symbols:**

```
c000000000864330-c00000000086437c: pci_bridge_secondary_bus_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int pci_bridge_secondary_bus_reset(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bff3c)
Location: drivers/pci/pci.c:4830
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_parent_bus_reset
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
```
**Symbols:**

```
ffffffe0004bf82a-ffffffe0004bf866: pci_bridge_secondary_bus_reset (STB_GLOBAL)
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
int pci_bridge_secondary_bus_reset(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81579a77)
Location: drivers/pci/pci.c:4830
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_parent_bus_reset
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
```
**Symbols:**

```
ffffffff815792e0-ffffffff81579306: pci_bridge_secondary_bus_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int pci_bridge_secondary_bus_reset(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815681b7)
Location: drivers/pci/pci.c:4830
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_parent_bus_reset
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
```
**Symbols:**

```
ffffffff81567a20-ffffffff81567a46: pci_bridge_secondary_bus_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int pci_bridge_secondary_bus_reset(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815792a7)
Location: drivers/pci/pci.c:4830
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_parent_bus_reset
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
```
**Symbols:**

```
ffffffff81578b10-ffffffff81578b36: pci_bridge_secondary_bus_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int pci_bridge_secondary_bus_reset(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81593732)
Location: drivers/pci/pci.c:4830
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_parent_bus_reset
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
```
**Symbols:**

```
ffffffff81592fd0-ffffffff81592ff6: pci_bridge_secondary_bus_reset (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
