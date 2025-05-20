# Function: <code>pci_scan_single_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_scan_single_device(struct pci_bus *bus, int devfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81431760)
Location: drivers/pci/probe.c:1772
Inline: True
```
**Symbols:**

```
ffffffff81431760-ffffffff8143182c: pci_scan_single_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_scan_single_device(struct pci_bus *bus, int devfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8147cf50)
Location: drivers/pci/probe.c:1794
Inline: True
```
**Symbols:**

```
ffffffff8147cf50-ffffffff8147d020: pci_scan_single_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_scan_single_device(struct pci_bus *bus, int devfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8149e4c0)
Location: drivers/pci/probe.c:1944
Inline: True
```
**Symbols:**

```
ffffffff8149e4c0-ffffffff8149e590: pci_scan_single_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_scan_single_device(struct pci_bus *bus, int devfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814a8340)
Location: drivers/pci/probe.c:2070
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffff814a8340-ffffffff814a8410: pci_scan_single_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_scan_single_device(struct pci_bus *bus, int devfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814e7380)
Location: drivers/pci/probe.c:2201
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffff814e7380-ffffffff814e7450: pci_scan_single_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_scan_single_device(struct pci_bus *bus, int devfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff815169c0)
Location: drivers/pci/probe.c:2352
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffff815169c0-ffffffff81516a87: pci_scan_single_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_scan_single_device(struct pci_bus *bus, int devfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8152c420)
Location: drivers/pci/probe.c:2478
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffff8152c420-ffffffff8152c4e7: pci_scan_single_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_scan_single_device(struct pci_bus *bus, int devfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8155adb0)
Location: drivers/pci/probe.c:2704
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffff8155adb0-ffffffff8155ae71: pci_scan_single_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_scan_single_device(struct pci_bus *bus, int devfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8157be50)
Location: drivers/pci/probe.c:2442
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffff8157be50-ffffffff8157bf11: pci_scan_single_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_scan_single_device(struct pci_bus *bus, int devfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81621520)
Location: drivers/pci/probe.c:2494
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffff81621520-ffffffff8162160b: pci_scan_single_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_scan_single_device(struct pci_bus *bus, int devfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff816480b0)
Location: drivers/pci/probe.c:2501
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffff816480b0-ffffffff8164819b: pci_scan_single_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_scan_single_device(struct pci_bus *bus, int devfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8162acd0)
Location: drivers/pci/probe.c:2545
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffff8162acd0-ffffffff8162adbb: pci_scan_single_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_scan_single_device(struct pci_bus *bus, int devfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8169a1a0)
Location: drivers/pci/probe.c:2587
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffff8169a1a0-ffffffff8169a28b: pci_scan_single_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_scan_single_device(struct pci_bus *bus, int devfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff817bb800)
Location: drivers/pci/probe.c:2562
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffff817bb800-ffffffff817bb902: pci_scan_single_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_scan_single_device(struct pci_bus *bus, int devfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff818d7310)
Location: drivers/pci/probe.c:2574
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/platform/x86/p2sb.c:p2sb_bar
  - drivers/platform/x86/p2sb.c:p2sb_bar
```
**Symbols:**

```
ffffffff818d7310-ffffffff818d7412: pci_scan_single_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_scan_single_device(struct pci_bus *bus, int devfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8191a5a0)
Location: drivers/pci/probe.c:2588
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/platform/x86/p2sb.c:p2sb_bar
  - drivers/platform/x86/p2sb.c:p2sb_bar
```
**Symbols:**

```
ffffffff8191a5a0-ffffffff8191a6a2: pci_scan_single_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_scan_single_device(struct pci_bus *bus, int devfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff819629a0)
Location: drivers/pci/probe.c:2637
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/platform/x86/p2sb.c:p2sb_scan_and_cache_devfn
```
**Symbols:**

```
ffffffff819629a0-ffffffff81962aa2: pci_scan_single_device (STB_GLOBAL)
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
struct pci_dev *pci_scan_single_device(struct pci_bus *bus, int devfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffff8000106df420)
Location: drivers/pci/probe.c:2442
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffff8000106df420-ffff8000106df518: pci_scan_single_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_scan_single_device(struct pci_bus *bus, int devfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c087b0bc)
Location: drivers/pci/probe.c:2442
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
c087b0bc-c087b19c: pci_scan_single_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_scan_single_device(struct pci_bus *bus, int devfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c000000000857df0)
Location: drivers/pci/probe.c:2442
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
c000000000857df0-c000000000857f24: pci_scan_single_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_scan_single_device(struct pci_bus *bus, int devfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffe0004b7474)
Location: drivers/pci/probe.c:2442
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffe0004b7474-ffffffe0004b752c: pci_scan_single_device (STB_GLOBAL)
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
struct pci_dev *pci_scan_single_device(struct pci_bus *bus, int devfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81570370)
Location: drivers/pci/probe.c:2442
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffff81570370-ffffffff81570431: pci_scan_single_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_scan_single_device(struct pci_bus *bus, int devfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8155ead0)
Location: drivers/pci/probe.c:2442
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffff8155ead0-ffffffff8155eb91: pci_scan_single_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_scan_single_device(struct pci_bus *bus, int devfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8156fba0)
Location: drivers/pci/probe.c:2442
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffff8156fba0-ffffffff8156fc61: pci_scan_single_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct pci_dev *pci_scan_single_device(struct pci_bus *bus, int devfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8158a080)
Location: drivers/pci/probe.c:2442
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_scan_slot
```
**Symbols:**

```
ffffffff8158a080-ffffffff8158a141: pci_scan_single_device (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
