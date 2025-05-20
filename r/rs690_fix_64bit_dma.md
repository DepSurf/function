# Function: <code>rs690_fix_64bit_dma</code>

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
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void rs690_fix_64bit_dma(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/fixup.c (0)
Location: arch/x86/pci/fixup.c:798
Inline: False
```
**Symbols:**

```
ffffffff81bbf930-ffffffff81bbf9ee: rs690_fix_64bit_dma (STB_LOCAL)
ffffffff81c2683b-ffffffff81c2689f: rs690_fix_64bit_dma.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void rs690_fix_64bit_dma(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/fixup.c (0)
Location: arch/x86/pci/fixup.c:798
Inline: False
```
**Symbols:**

```
ffffffff81c8f8a0-ffffffff81c8f95e: rs690_fix_64bit_dma (STB_LOCAL)
ffffffff81d44692-ffffffff81d446f6: rs690_fix_64bit_dma.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void rs690_fix_64bit_dma(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/fixup.c (0)
Location: arch/x86/pci/fixup.c:798
Inline: False
```
**Symbols:**

```
ffffffff81e3e8c0-ffffffff81e3e98b: rs690_fix_64bit_dma (STB_LOCAL)
ffffffff81f1158d-ffffffff81f115f0: rs690_fix_64bit_dma.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rs690_fix_64bit_dma(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/fixup.c (ffffffff82018430)
Location: arch/x86/pci/fixup.c:798
Inline: False
```
**Symbols:**

```
ffffffff82018430-ffffffff8201855d: rs690_fix_64bit_dma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rs690_fix_64bit_dma(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/fixup.c (ffffffff820988e0)
Location: arch/x86/pci/fixup.c:799
Inline: False
```
**Symbols:**

```
ffffffff820988e0-ffffffff82098a0d: rs690_fix_64bit_dma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rs690_fix_64bit_dma(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/fixup.c (ffffffff8216fdc0)
Location: arch/x86/pci/fixup.c:801
Inline: False
```
**Symbols:**

```
ffffffff8216fdc0-ffffffff8216feed: rs690_fix_64bit_dma (STB_LOCAL)
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
