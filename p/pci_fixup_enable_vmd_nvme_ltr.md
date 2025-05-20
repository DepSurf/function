# Function: <code>pci_fixup_enable_vmd_nvme_ltr</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pci_fixup_enable_vmd_nvme_ltr(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81643e80)
Location: drivers/pci/quirks.c:5695
Inline: False
```
**Symbols:**

```
ffffffff81643e80-ffffffff81643f67: pci_fixup_enable_vmd_nvme_ltr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pci_fixup_enable_vmd_nvme_ltr(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff8166a410)
Location: drivers/pci/quirks.c:5674
Inline: False
```
**Symbols:**

```
ffffffff8166a410-ffffffff8166a4f9: pci_fixup_enable_vmd_nvme_ltr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pci_fixup_enable_vmd_nvme_ltr(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff8164e380)
Location: drivers/pci/quirks.c:5758
Inline: False
```
**Symbols:**

```
ffffffff8164e380-ffffffff8164e47e: pci_fixup_enable_vmd_nvme_ltr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pci_fixup_enable_vmd_nvme_ltr(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff816be1a0)
Location: drivers/pci/quirks.c:5844
Inline: False
```
**Symbols:**

```
ffffffff816be1a0-ffffffff816be289: pci_fixup_enable_vmd_nvme_ltr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pci_fixup_enable_vmd_nvme_ltr(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff817e5780)
Location: drivers/pci/quirks.c:6031
Inline: False
```
**Symbols:**

```
ffffffff817e5780-ffffffff817e5890: pci_fixup_enable_vmd_nvme_ltr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_fixup_enable_vmd_nvme_ltr(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff8190a640)
Location: drivers/pci/quirks.c:6069
Inline: False
```
**Symbols:**

```
ffffffff8190a640-ffffffff8190a750: pci_fixup_enable_vmd_nvme_ltr (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
