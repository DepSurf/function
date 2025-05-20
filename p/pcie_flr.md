# Function: <code>pcie_flr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81438272)
Location: drivers/pci/pci.c:3417
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81483f12)
Location: drivers/pci/pci.c:3738
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a5672)
Location: drivers/pci/pci.c:3776
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pcie_flr(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ad370)
Location: drivers/pci/pci.c:3900
Inline: False
Direct callers:
  - drivers/pci/quirks.c:reset_intel_82599_sfp_virtfn
```
**Symbols:**

```
ffffffff814ad370-ffffffff814ad3cb: pcie_flr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pcie_flr(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ec740)
Location: drivers/pci/pci.c:3937
Inline: False
Direct callers:
  - drivers/pci/quirks.c:reset_intel_82599_sfp_virtfn
```
**Symbols:**

```
ffffffff814ec740-ffffffff814ec79b: pcie_flr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pcie_flr(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151c300)
Location: drivers/pci/pci.c:4138
Inline: False
Direct callers:
  - drivers/pci/quirks.c:reset_intel_82599_sfp_virtfn
```
**Symbols:**

```
ffffffff8151c300-ffffffff8151c36c: pcie_flr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int pcie_flr(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81531bd0)
Location: drivers/pci/pci.c:4404
Inline: True
Direct callers:
  - drivers/pci/quirks.c:reset_intel_82599_sfp_virtfn
```
**Symbols:**

```
ffffffff81531bd0-ffffffff81531c47: pcie_flr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pcie_flr(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff815612a8)
Location: drivers/pci/pci.c:4501
Inline: True
Direct callers:
  - drivers/pci/quirks.c:reset_intel_82599_sfp_virtfn
```
**Symbols:**

```
ffffffff81564acf-ffffffff81564ae8: pcie_flr.cold (STB_LOCAL)
ffffffff81561270-ffffffff815612dc: pcie_flr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pcie_flr(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff81582468)
Location: drivers/pci/pci.c:4497
Inline: True
Direct callers:
  - drivers/pci/quirks.c:reset_intel_82599_sfp_virtfn
```
**Symbols:**

```
ffffffff81585dea-ffffffff81585e03: pcie_flr.cold (STB_LOCAL)
ffffffff81582430-ffffffff8158249c: pcie_flr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pcie_flr(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff81627d2f)
Location: drivers/pci/pci.c:4527
Inline: True
Direct callers:
  - drivers/pci/quirks.c:reset_intel_82599_sfp_virtfn
```
**Symbols:**

```
ffffffff8162cc4c-ffffffff8162cc65: pcie_flr.cold (STB_LOCAL)
ffffffff81627ce0-ffffffff81627dcb: pcie_flr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pcie_flr(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff8164d9cf)
Location: drivers/pci/pci.c:4602
Inline: True
Direct callers:
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/quirks.c:reset_intel_82599_sfp_virtfn
```
**Symbols:**

```
ffffffff81bf7dd3-ffffffff81bf7dec: pcie_flr.cold (STB_LOCAL)
ffffffff8164d980-ffffffff8164da6b: pcie_flr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pcie_flr(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff8163055f)
Location: drivers/pci/pci.c:4651
Inline: True
Direct callers:
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/quirks.c:reset_intel_82599_sfp_virtfn
```
**Symbols:**

```
ffffffff81be9c7a-ffffffff81be9c93: pcie_flr.cold (STB_LOCAL)
ffffffff81630510-ffffffff816305fb: pcie_flr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pcie_flr(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff816a02df)
Location: drivers/pci/pci.c:4681
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcie_reset_flr
  - drivers/pci/quirks.c:reset_intel_82599_sfp_virtfn
```
**Symbols:**

```
ffffffff81ce4779-ffffffff81ce4792: pcie_flr.cold (STB_LOCAL)
ffffffff816a0290-ffffffff816a037b: pcie_flr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pcie_flr(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c22af)
Location: drivers/pci/pci.c:4777
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcie_reset_flr
  - drivers/pci/quirks.c:reset_hinic_vf_dev
  - drivers/pci/quirks.c:nvme_disable_and_flr
  - drivers/pci/quirks.c:reset_chelsio_generic_dev
  - drivers/pci/quirks.c:reset_intel_82599_sfp_virtfn
```
**Symbols:**

```
ffffffff81eab1a4-ffffffff81eab1bc: pcie_flr.cold (STB_LOCAL)
ffffffff817c2260-ffffffff817c234e: pcie_flr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int pcie_flr(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818deb10)
Location: drivers/pci/pci.c:4720
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcie_reset_flr
  - drivers/pci/quirks.c:reset_hinic_vf_dev
  - drivers/pci/quirks.c:nvme_disable_and_flr
  - drivers/pci/quirks.c:reset_chelsio_generic_dev
  - drivers/pci/quirks.c:reset_intel_82599_sfp_virtfn
```
**Symbols:**

```
ffffffff818deb10-ffffffff818dec1b: pcie_flr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int pcie_flr(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81921f70)
Location: drivers/pci/pci.c:4758
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcie_reset_flr
  - drivers/pci/quirks.c:reset_hinic_vf_dev
  - drivers/pci/quirks.c:nvme_disable_and_flr
  - drivers/pci/quirks.c:reset_chelsio_generic_dev
  - drivers/pci/quirks.c:reset_intel_82599_sfp_virtfn
```
**Symbols:**

```
ffffffff81921f70-ffffffff8192207b: pcie_flr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int pcie_flr(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8196a4d0)
Location: drivers/pci/pci.c:4868
Inline: True
Direct callers:
  - drivers/pci/pci.c:pcie_reset_flr
  - drivers/pci/quirks.c:reset_hinic_vf_dev
  - drivers/pci/quirks.c:nvme_disable_and_flr
  - drivers/pci/quirks.c:reset_chelsio_generic_dev
  - drivers/pci/quirks.c:reset_intel_82599_sfp_virtfn
```
**Symbols:**

```
ffffffff8196a4d0-ffffffff8196a5db: pcie_flr (STB_GLOBAL)
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
int pcie_flr(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e5f70)
Location: drivers/pci/pci.c:4497
Inline: True
Direct callers:
  - drivers/pci/quirks.c:reset_intel_82599_sfp_virtfn
```
**Symbols:**

```
ffff8000106e5f70-ffff8000106e5ffc: pcie_flr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int pcie_flr(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c0881294)
Location: drivers/pci/pci.c:4497
Inline: True
Direct callers:
  - drivers/pci/quirks.c:reset_intel_82599_sfp_virtfn
```
**Symbols:**

```
c0881294-c0881324: pcie_flr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int pcie_flr(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c000000000860020)
Location: drivers/pci/pci.c:4497
Inline: True
Direct callers:
  - drivers/pci/quirks.c:reset_intel_82599_sfp_virtfn
```
**Symbols:**

```
c000000000860020-c0000000008600ec: pcie_flr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int pcie_flr(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bcaf6)
Location: drivers/pci/pci.c:4497
Inline: True
Direct callers:
  - drivers/pci/quirks.c:reset_intel_82599_sfp_virtfn
```
**Symbols:**

```
ffffffe0004bcaf6-ffffffe0004bcb7c: pcie_flr (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pcie_flr(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff81576988)
Location: drivers/pci/pci.c:4497
Inline: True
Direct callers:
  - drivers/pci/quirks.c:reset_intel_82599_sfp_virtfn
```
**Symbols:**

```
ffffffff8157a30a-ffffffff8157a323: pcie_flr.cold (STB_LOCAL)
ffffffff81576950-ffffffff815769bc: pcie_flr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pcie_flr(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff815650e8)
Location: drivers/pci/pci.c:4497
Inline: True
Direct callers:
  - drivers/pci/quirks.c:reset_intel_82599_sfp_virtfn
```
**Symbols:**

```
ffffffff81568a4a-ffffffff81568a63: pcie_flr.cold (STB_LOCAL)
ffffffff815650b0-ffffffff8156511c: pcie_flr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pcie_flr(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff815761b8)
Location: drivers/pci/pci.c:4497
Inline: True
Direct callers:
  - drivers/pci/quirks.c:reset_intel_82599_sfp_virtfn
```
**Symbols:**

```
ffffffff81579b3a-ffffffff81579b53: pcie_flr.cold (STB_LOCAL)
ffffffff81576180-ffffffff815761ec: pcie_flr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pcie_flr(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff81590698)
Location: drivers/pci/pci.c:4497
Inline: True
Direct callers:
  - drivers/pci/quirks.c:reset_intel_82599_sfp_virtfn
```
**Symbols:**

```
ffffffff81593fea-ffffffff81594003: pcie_flr.cold (STB_LOCAL)
ffffffff81590660-ffffffff815906cc: pcie_flr (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
