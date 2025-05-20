# Function: <code>pcie_capability_write_dword</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pcie_capability_write_dword(struct pci_dev *dev, int pos, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8142e390)
Location: drivers/pci/access.c:724
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
```
**Symbols:**

```
ffffffff8142e390-ffffffff8142e40c: pcie_capability_write_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pcie_capability_write_dword(struct pci_dev *dev, int pos, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81479960)
Location: drivers/pci/access.c:835
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
```
**Symbols:**

```
ffffffff81479960-ffffffff814799d0: pcie_capability_write_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pcie_capability_write_dword(struct pci_dev *dev, int pos, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8149adf0)
Location: drivers/pci/access.c:847
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
```
**Symbols:**

```
ffffffff8149adf0-ffffffff8149ae60: pcie_capability_write_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pcie_capability_write_dword(struct pci_dev *dev, int pos, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814a4b80)
Location: drivers/pci/access.c:857
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
```
**Symbols:**

```
ffffffff814a4b80-ffffffff814a4bf3: pcie_capability_write_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pcie_capability_write_dword(struct pci_dev *dev, int pos, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814e3960)
Location: drivers/pci/access.c:857
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
```
**Symbols:**

```
ffffffff814e3960-ffffffff814e39d3: pcie_capability_write_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pcie_capability_write_dword(struct pci_dev *dev, int pos, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81513370)
Location: drivers/pci/access.c:490
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
```
**Symbols:**

```
ffffffff81513370-ffffffff81513404: pcie_capability_write_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pcie_capability_write_dword(struct pci_dev *dev, int pos, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81528ab0)
Location: drivers/pci/access.c:490
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
```
**Symbols:**

```
ffffffff81528ab0-ffffffff81528b26: pcie_capability_write_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_write_dword(struct pci_dev *dev, int pos, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81557ed0)
Location: drivers/pci/access.c:490
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
```
**Symbols:**

```
ffffffff81557ed0-ffffffff81557f3d: pcie_capability_write_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_write_dword(struct pci_dev *dev, int pos, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff815794e0)
Location: drivers/pci/access.c:481
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
```
**Symbols:**

```
ffffffff815794e0-ffffffff8157954d: pcie_capability_write_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pcie_capability_write_dword(struct pci_dev *dev, int pos, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8161e5d0)
Location: drivers/pci/access.c:477
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
```
**Symbols:**

```
ffffffff8161e5d0-ffffffff8161e655: pcie_capability_write_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pcie_capability_write_dword(struct pci_dev *dev, int pos, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81644e00)
Location: drivers/pci/access.c:477
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
```
**Symbols:**

```
ffffffff81644e00-ffffffff81644e90: pcie_capability_write_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pcie_capability_write_dword(struct pci_dev *dev, int pos, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81627aa0)
Location: drivers/pci/access.c:477
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
```
**Symbols:**

```
ffffffff81627aa0-ffffffff81627b30: pcie_capability_write_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pcie_capability_write_dword(struct pci_dev *dev, int pos, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff816973a0)
Location: drivers/pci/access.c:477
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
```
**Symbols:**

```
ffffffff816973a0-ffffffff81697430: pcie_capability_write_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_write_dword(struct pci_dev *dev, int pos, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff817b8b70)
Location: drivers/pci/access.c:482
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
```
**Symbols:**

```
ffffffff817b8b70-ffffffff817b8c16: pcie_capability_write_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_write_dword(struct pci_dev *dev, int pos, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff818d3610)
Location: drivers/pci/access.c:488
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
```
**Symbols:**

```
ffffffff818d3610-ffffffff818d36b6: pcie_capability_write_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_write_dword(struct pci_dev *dev, int pos, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81916740)
Location: drivers/pci/access.c:488
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
```
**Symbols:**

```
ffffffff81916740-ffffffff819167e6: pcie_capability_write_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_write_dword(struct pci_dev *dev, int pos, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8195e760)
Location: drivers/pci/access.c:488
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
```
**Symbols:**

```
ffffffff8195e760-ffffffff8195e806: pcie_capability_write_dword (STB_GLOBAL)
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
int pcie_capability_write_dword(struct pci_dev *dev, int pos, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffff8000106dbb20)
Location: drivers/pci/access.c:481
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
```
**Symbols:**

```
ffff8000106dbb20-ffff8000106dbbcc: pcie_capability_write_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pcie_capability_write_dword(struct pci_dev *dev, int pos, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c0877e74)
Location: drivers/pci/access.c:481
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
```
**Symbols:**

```
c0877e74-c0877eec: pcie_capability_write_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_write_dword(struct pci_dev *dev, int pos, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c000000000853300)
Location: drivers/pci/access.c:481
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
```
**Symbols:**

```
c000000000853300-c0000000008533f8: pcie_capability_write_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pcie_capability_write_dword(struct pci_dev *dev, int pos, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffe0004b3fb2)
Location: drivers/pci/access.c:481
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
```
**Symbols:**

```
ffffffe0004b3fb2-ffffffe0004b402c: pcie_capability_write_dword (STB_GLOBAL)
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
int pcie_capability_write_dword(struct pci_dev *dev, int pos, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8156da00)
Location: drivers/pci/access.c:481
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
```
**Symbols:**

```
ffffffff8156da00-ffffffff8156da6d: pcie_capability_write_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_write_dword(struct pci_dev *dev, int pos, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8155c170)
Location: drivers/pci/access.c:481
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
```
**Symbols:**

```
ffffffff8155c170-ffffffff8155c1dd: pcie_capability_write_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_write_dword(struct pci_dev *dev, int pos, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8156d230)
Location: drivers/pci/access.c:481
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
```
**Symbols:**

```
ffffffff8156d230-ffffffff8156d29d: pcie_capability_write_dword (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_write_dword(struct pci_dev *dev, int pos, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81587d30)
Location: drivers/pci/access.c:481
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_dword
```
**Symbols:**

```
ffffffff81587d30-ffffffff81587d9d: pcie_capability_write_dword (STB_GLOBAL)
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
