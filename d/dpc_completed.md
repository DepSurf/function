# Function: <code>dpc_completed</code>

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
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffffffff81646fc1)
Location: drivers/pci/pcie/dpc.c:77
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffffffff816b8871)
Location: drivers/pci/pcie/dpc.c:77
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffffffff817dccf7)
Location: drivers/pci/pcie/dpc.c:77
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool dpc_completed(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffffffff818fe830)
Location: drivers/pci/pcie/dpc.c:77
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
```
**Symbols:**

```
ffffffff818fe830-ffffffff818fe8af: dpc_completed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool dpc_completed(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffffffff81941c40)
Location: drivers/pci/pcie/dpc.c:77
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
```
**Symbols:**

```
ffffffff81941c40-ffffffff81941cbf: dpc_completed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool dpc_completed(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffffffff8198aed0)
Location: drivers/pci/pcie/dpc.c:81
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
```
**Symbols:**

```
ffffffff8198aed0-ffffffff8198af4f: dpc_completed (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
