# Function: <code>pcie_reset_flr</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pcie_reset_flr(struct pci_dev *dev, bool probe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816a0380)
Location: drivers/pci/pci.c:4709
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_root_reset
```
**Symbols:**

```
ffffffff816a0380-ffffffff816a03ad: pcie_reset_flr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pcie_reset_flr(struct pci_dev *dev, bool probe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c2350)
Location: drivers/pci/pci.c:4805
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/quirks.c:nvme_disable_and_flr
```
**Symbols:**

```
ffffffff817c2350-ffffffff817c2395: pcie_reset_flr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pcie_reset_flr(struct pci_dev *dev, bool probe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818dec30)
Location: drivers/pci/pci.c:4748
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/quirks.c:nvme_disable_and_flr
```
**Symbols:**

```
ffffffff818dec30-ffffffff818dec75: pcie_reset_flr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pcie_reset_flr(struct pci_dev *dev, bool probe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81922090)
Location: drivers/pci/pci.c:4786
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/quirks.c:nvme_disable_and_flr
```
**Symbols:**

```
ffffffff81922090-ffffffff819220d5: pcie_reset_flr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pcie_reset_flr(struct pci_dev *dev, bool probe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8196a5f0)
Location: drivers/pci/pci.c:4896
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/quirks.c:nvme_disable_and_flr
```
**Symbols:**

```
ffffffff8196a5f0-ffffffff8196a635: pcie_reset_flr (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
