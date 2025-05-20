# Function: <code>reset_hinic_vf_dev</code>

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
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int reset_hinic_vf_dev(struct pci_dev *pdev, int probe);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff8164d779)
Location: drivers/pci/quirks.c:3961
Inline: True
```
**Symbols:**

```
ffffffff8164d760-ffffffff8164d84e: reset_hinic_vf_dev (STB_LOCAL)
ffffffff81bece30-ffffffff81bece4a: reset_hinic_vf_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int reset_hinic_vf_dev(struct pci_dev *pdev, bool probe);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff816bf54c)
Location: drivers/pci/quirks.c:3999
Inline: True
```
**Symbols:**

```
ffffffff816bf530-ffffffff816bf621: reset_hinic_vf_dev (STB_LOCAL)
ffffffff81ce7b13-ffffffff81ce7b2d: reset_hinic_vf_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int reset_hinic_vf_dev(struct pci_dev *pdev, bool probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (0)
Location: drivers/pci/quirks.c:4012
Inline: False
```
**Symbols:**

```
ffffffff817e39c0-ffffffff817e3ace: reset_hinic_vf_dev (STB_LOCAL)
ffffffff81eae3ff-ffffffff81eae419: reset_hinic_vf_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int reset_hinic_vf_dev(struct pci_dev *pdev, bool probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81907ac0)
Location: drivers/pci/quirks.c:4023
Inline: False
```
**Symbols:**

```
ffffffff81907ac0-ffffffff81907be0: reset_hinic_vf_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int reset_hinic_vf_dev(struct pci_dev *pdev, bool probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff8194b110)
Location: drivers/pci/quirks.c:4130
Inline: False
```
**Symbols:**

```
ffffffff8194b110-ffffffff8194b230: reset_hinic_vf_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int reset_hinic_vf_dev(struct pci_dev *pdev, bool probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff819944c0)
Location: drivers/pci/quirks.c:4157
Inline: False
```
**Symbols:**

```
ffffffff819944c0-ffffffff819945e0: reset_hinic_vf_dev (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int probe</code> ➡️ <code>bool probe</code>
</li>
</ul>
</details>
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
