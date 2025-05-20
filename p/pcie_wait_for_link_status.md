# Function: <code>pcie_wait_for_link_status</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pcie_wait_for_link_status(struct pci_dev *pdev, bool use_lt, bool active);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8191e340)
Location: drivers/pci/pci.c:4899
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcie_wait_for_link
  - drivers/pci/pci.c:pcie_wait_for_link
  - drivers/pci/pci.c:pcie_retrain_link
  - drivers/pci/pci.c:pcie_retrain_link
```
**Symbols:**

```
ffffffff8191e340-ffffffff8191e404: pcie_wait_for_link_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pcie_wait_for_link_status(struct pci_dev *pdev, bool use_lt, bool active);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff819663c0)
Location: drivers/pci/pci.c:5009
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcie_wait_for_link
  - drivers/pci/pci.c:pcie_wait_for_link
  - drivers/pci/pci.c:pcie_retrain_link
  - drivers/pci/pci.c:pcie_retrain_link
```
**Symbols:**

```
ffffffff819663c0-ffffffff81966484: pcie_wait_for_link_status (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
