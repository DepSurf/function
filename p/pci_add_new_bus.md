# Function: <code>pci_add_new_bus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct pci_bus *pci_add_new_bus(struct pci_bus *parent, struct pci_dev *dev, int busnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81431930)
Location: drivers/pci/probe.c:782
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/iov.c:pci_enable_sriov
```
**Symbols:**

```
ffffffff81431930-ffffffff81431d25: pci_add_new_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct pci_bus *pci_add_new_bus(struct pci_bus *parent, struct pci_dev *dev, int busnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8147d120)
Location: drivers/pci/probe.c:791
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff8147d120-ffffffff8147d552: pci_add_new_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct pci_bus *pci_add_new_bus(struct pci_bus *parent, struct pci_dev *dev, int busnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8149e690)
Location: drivers/pci/probe.c:910
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff8149e690-ffffffff8149eac2: pci_add_new_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct pci_bus *pci_add_new_bus(struct pci_bus *parent, struct pci_dev *dev, int busnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814a8520)
Location: drivers/pci/probe.c:936
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff814a8520-ffffffff814a891c: pci_add_new_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct pci_bus *pci_add_new_bus(struct pci_bus *parent, struct pci_dev *dev, int busnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814e7550)
Location: drivers/pci/probe.c:936
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff814e7550-ffffffff814e794f: pci_add_new_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct pci_bus *pci_add_new_bus(struct pci_bus *parent, struct pci_dev *dev, int busnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81516b90)
Location: drivers/pci/probe.c:1005
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff81516b90-ffffffff81516ffd: pci_add_new_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct pci_bus *pci_add_new_bus(struct pci_bus *parent, struct pci_dev *dev, int busnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8152c5f0)
Location: drivers/pci/probe.c:1005
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff8152c5f0-ffffffff8152ca7b: pci_add_new_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct pci_bus *pci_add_new_bus(struct pci_bus *parent, struct pci_dev *dev, int busnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1062
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff8155d425-ffffffff8155d47b: pci_add_new_bus.cold (STB_LOCAL)
ffffffff8155af90-ffffffff8155b3d2: pci_add_new_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct pci_bus *pci_add_new_bus(struct pci_bus *parent, struct pci_dev *dev, int busnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1058
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff8157e4b9-ffffffff8157e4ef: pci_add_new_bus.cold (STB_LOCAL)
ffffffff8157c040-ffffffff8157c486: pci_add_new_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct pci_bus *pci_add_new_bus(struct pci_bus *parent, struct pci_dev *dev, int busnr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff816225b2)
Location: drivers/pci/probe.c:1106
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
Direct callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff81621960-ffffffff816219b4: pci_add_new_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct pci_bus *pci_add_new_bus(struct pci_bus *parent, struct pci_dev *dev, int busnr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8164919d)
Location: drivers/pci/probe.c:1125
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
Direct callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff81648520-ffffffff81648574: pci_add_new_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct pci_bus *pci_add_new_bus(struct pci_bus *parent, struct pci_dev *dev, int busnr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8162bd61)
Location: drivers/pci/probe.c:1168
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
Direct callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff8162b130-ffffffff8162b184: pci_add_new_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct pci_bus *pci_add_new_bus(struct pci_bus *parent, struct pci_dev *dev, int busnr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8169b231)
Location: drivers/pci/probe.c:1177
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
Direct callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff8169a600-ffffffff8169a654: pci_add_new_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct pci_bus *pci_add_new_bus(struct pci_bus *parent, struct pci_dev *dev, int busnr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff817bc9e6)
Location: drivers/pci/probe.c:1158
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
Direct callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff817bbd70-ffffffff817bbdce: pci_add_new_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct pci_bus *pci_add_new_bus(struct pci_bus *parent, struct pci_dev *dev, int busnr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff818d8936)
Location: drivers/pci/probe.c:1163
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
Direct callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff818d7910-ffffffff818d796e: pci_add_new_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct pci_bus *pci_add_new_bus(struct pci_bus *parent, struct pci_dev *dev, int busnr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8191bc74)
Location: drivers/pci/probe.c:1166
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
Direct callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff8191aba0-ffffffff8191abfe: pci_add_new_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct pci_bus *pci_add_new_bus(struct pci_bus *parent, struct pci_dev *dev, int busnr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff819640a4)
Location: drivers/pci/probe.c:1177
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
Direct callers:
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff81962fa0-ffffffff81962ffe: pci_add_new_bus (STB_GLOBAL)
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
struct pci_bus *pci_add_new_bus(struct pci_bus *parent, struct pci_dev *dev, int busnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffff8000106df688)
Location: drivers/pci/probe.c:1058
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffff8000106df688-ffff8000106dfad4: pci_add_new_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct pci_bus *pci_add_new_bus(struct pci_bus *parent, struct pci_dev *dev, int busnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c087b300)
Location: drivers/pci/probe.c:1058
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
c087b300-c087b778: pci_add_new_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct pci_bus *pci_add_new_bus(struct pci_bus *parent, struct pci_dev *dev, int busnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c0000000008580d0)
Location: drivers/pci/probe.c:1058
Inline: False
Direct callers:
  - arch/powerpc/kernel/pci_of_scan.c:of_scan_pci_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
c0000000008580d0-c000000000858638: pci_add_new_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct pci_bus *pci_add_new_bus(struct pci_bus *parent, struct pci_dev *dev, int busnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffe0004b7676)
Location: drivers/pci/probe.c:1058
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffe0004b7676-ffffffe0004b7a4c: pci_add_new_bus (STB_GLOBAL)
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
struct pci_bus *pci_add_new_bus(struct pci_bus *parent, struct pci_dev *dev, int busnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1058
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff815729d9-ffffffff81572a0f: pci_add_new_bus.cold (STB_LOCAL)
ffffffff81570560-ffffffff815709a6: pci_add_new_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct pci_bus *pci_add_new_bus(struct pci_bus *parent, struct pci_dev *dev, int busnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1058
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff81561139-ffffffff8156116f: pci_add_new_bus.cold (STB_LOCAL)
ffffffff8155ecc0-ffffffff8155f106: pci_add_new_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct pci_bus *pci_add_new_bus(struct pci_bus *parent, struct pci_dev *dev, int busnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1058
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff81572209-ffffffff8157223f: pci_add_new_bus.cold (STB_LOCAL)
ffffffff8156fd90-ffffffff815701d6: pci_add_new_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct pci_bus *pci_add_new_bus(struct pci_bus *parent, struct pci_dev *dev, int busnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1058
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff8158c6e9-ffffffff8158c71f: pci_add_new_bus.cold (STB_LOCAL)
ffffffff8158a270-ffffffff8158a6b6: pci_add_new_bus (STB_GLOBAL)
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
