# Function: <code>pci_fixup_enable_aspm</code>

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
void pci_fixup_enable_aspm(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81643dc0)
Location: drivers/pci/quirks.c:5685
Inline: False
```
**Symbols:**

```
ffffffff81643dc0-ffffffff81643df0: pci_fixup_enable_aspm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pci_fixup_enable_aspm(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff8166a220)
Location: drivers/pci/quirks.c:5664
Inline: False
```
**Symbols:**

```
ffffffff8166a220-ffffffff8166a250: pci_fixup_enable_aspm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_fixup_enable_aspm(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81bed0ac)
Location: drivers/pci/quirks.c:5747
Inline: True
```
**Symbols:**

```
ffffffff8164eab0-ffffffff8164eb08: pci_fixup_enable_aspm (STB_LOCAL)
ffffffff81bed0ac-ffffffff81bed0cd: pci_fixup_enable_aspm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pci_fixup_enable_aspm(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff816bdfc0)
Location: drivers/pci/quirks.c:5834
Inline: False
```
**Symbols:**

```
ffffffff816bdfc0-ffffffff816bdff0: pci_fixup_enable_aspm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_fixup_enable_aspm(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81eaeecc)
Location: drivers/pci/quirks.c:6020
Inline: True
```
**Symbols:**

```
ffffffff817e5d00-ffffffff817e5d6c: pci_fixup_enable_aspm (STB_LOCAL)
ffffffff81eaeecc-ffffffff81eaeeed: pci_fixup_enable_aspm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pci_fixup_enable_aspm(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff8190ad20)
Location: drivers/pci/quirks.c:6058
Inline: True
```
**Symbols:**

```
ffffffff8190ad20-ffffffff8190ada4: pci_fixup_enable_aspm (STB_LOCAL)
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
