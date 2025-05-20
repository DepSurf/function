# Function: <code>pci_bus_error_reset</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_bus_error_reset(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81534d10)
Location: drivers/pci/pci.c:5223
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/aer.c:aer_root_reset
```
**Symbols:**

```
ffffffff81534d10-ffffffff81534e35: pci_bus_error_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pci_bus_error_reset(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815641d0)
Location: drivers/pci/pci.c:5321
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/aer.c:aer_root_reset
```
**Symbols:**

```
ffffffff815641d0-ffffffff815642f7: pci_bus_error_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_bus_error_reset(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815854b0)
Location: drivers/pci/pci.c:5451
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/aer.c:aer_root_reset
```
**Symbols:**

```
ffffffff815854b0-ffffffff815855d7: pci_bus_error_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_bus_error_reset(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162bfb0)
Location: drivers/pci/pci.c:5481
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_root_reset
```
**Symbols:**

```
ffffffff8162bfb0-ffffffff8162c133: pci_bus_error_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_bus_error_reset(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81651d00)
Location: drivers/pci/pci.c:5549
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_root_reset
```
**Symbols:**

```
ffffffff81651d00-ffffffff81651e83: pci_bus_error_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_bus_error_reset(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816347f0)
Location: drivers/pci/pci.c:5598
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_root_reset
```
**Symbols:**

```
ffffffff816347f0-ffffffff81634973: pci_bus_error_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_bus_error_reset(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816a48e0)
Location: drivers/pci/pci.c:5788
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_root_reset
```
**Symbols:**

```
ffffffff816a48e0-ffffffff816a4a63: pci_bus_error_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_bus_error_reset(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c6d40)
Location: drivers/pci/pci.c:5884
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_root_reset
```
**Symbols:**

```
ffffffff817c6d40-ffffffff817c6ed3: pci_bus_error_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_bus_error_reset(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818e41e0)
Location: drivers/pci/pci.c:5821
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_root_reset
```
**Symbols:**

```
ffffffff818e41e0-ffffffff818e437c: pci_bus_error_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_bus_error_reset(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff819278f0)
Location: drivers/pci/pci.c:5943
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_root_reset
```
**Symbols:**

```
ffffffff819278f0-ffffffff819279d0: pci_bus_error_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_bus_error_reset(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81970090)
Location: drivers/pci/pci.c:6053
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_root_reset
```
**Symbols:**

```
ffffffff81970090-ffffffff81970170: pci_bus_error_reset (STB_GLOBAL)
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
int pci_bus_error_reset(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e9bd8)
Location: drivers/pci/pci.c:5451
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/aer.c:aer_root_reset
```
**Symbols:**

```
ffff8000106e9bd8-ffff8000106e9d2c: pci_bus_error_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_bus_error_reset(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c0884b74)
Location: drivers/pci/pci.c:5451
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/aer.c:aer_root_reset
```
**Symbols:**

```
c0884b74-c0884cac: pci_bus_error_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_bus_error_reset(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c000000000864cd0)
Location: drivers/pci/pci.c:5451
Inline: False
Direct callers:
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_reset
```
**Symbols:**

```
c000000000864cd0-c000000000864e90: pci_bus_error_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_bus_error_reset(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bfe9c)
Location: drivers/pci/pci.c:5451
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/aer.c:aer_root_reset
```
**Symbols:**

```
ffffffe0004bfe9c-ffffffe0004bffb8: pci_bus_error_reset (STB_GLOBAL)
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
int pci_bus_error_reset(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815799d0)
Location: drivers/pci/pci.c:5451
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/aer.c:aer_root_reset
```
**Symbols:**

```
ffffffff815799d0-ffffffff81579af7: pci_bus_error_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_bus_error_reset(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81568110)
Location: drivers/pci/pci.c:5451
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/aer.c:aer_root_reset
```
**Symbols:**

```
ffffffff81568110-ffffffff81568237: pci_bus_error_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_bus_error_reset(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81579200)
Location: drivers/pci/pci.c:5451
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/aer.c:aer_root_reset
```
**Symbols:**

```
ffffffff81579200-ffffffff81579327: pci_bus_error_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_bus_error_reset(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81593690)
Location: drivers/pci/pci.c:5451
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/aer.c:aer_root_reset
```
**Symbols:**

```
ffffffff81593690-ffffffff815937b2: pci_bus_error_reset (STB_GLOBAL)
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
