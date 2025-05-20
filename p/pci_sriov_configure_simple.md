# Function: <code>pci_sriov_configure_simple</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int pci_sriov_configure_simple(struct pci_dev *dev, int nr_virtfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff815447d0)
Location: drivers/pci/iov.c:860
Inline: True
```
**Symbols:**

```
ffffffff815447d0-ffffffff81544848: pci_sriov_configure_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int pci_sriov_configure_simple(struct pci_dev *dev, int nr_virtfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff8155bba0)
Location: drivers/pci/iov.c:885
Inline: True
```
**Symbols:**

```
ffffffff8155bba0-ffffffff8155bc18: pci_sriov_configure_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_sriov_configure_simple(struct pci_dev *dev, int nr_virtfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (ffffffff8158be77)
Location: drivers/pci/iov.c:883
Inline: True
```
**Symbols:**

```
ffffffff8158c77a-ffffffff8158c796: pci_sriov_configure_simple.cold (STB_LOCAL)
ffffffff8158be40-ffffffff8158beaa: pci_sriov_configure_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_sriov_configure_simple(struct pci_dev *dev, int nr_virtfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (ffffffff815ada27)
Location: drivers/pci/iov.c:1049
Inline: True
```
**Symbols:**

```
ffffffff815ae399-ffffffff815ae3b5: pci_sriov_configure_simple.cold (STB_LOCAL)
ffffffff815ad9f0-ffffffff815ada5a: pci_sriov_configure_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_sriov_configure_simple(struct pci_dev *dev, int nr_virtfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (ffffffff81657247)
Location: drivers/pci/iov.c:1065
Inline: True
```
**Symbols:**

```
ffffffff81657685-ffffffff816576a1: pci_sriov_configure_simple.cold (STB_LOCAL)
ffffffff81657210-ffffffff8165727a: pci_sriov_configure_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_sriov_configure_simple(struct pci_dev *dev, int nr_virtfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (ffffffff81677807)
Location: drivers/pci/iov.c:1066
Inline: True
```
**Symbols:**

```
ffffffff81bfdcb6-ffffffff81bfdcd2: pci_sriov_configure_simple.cold (STB_LOCAL)
ffffffff816777d0-ffffffff8167783a: pci_sriov_configure_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_sriov_configure_simple(struct pci_dev *dev, int nr_virtfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (ffffffff81659db7)
Location: drivers/pci/iov.c:1156
Inline: True
```
**Symbols:**

```
ffffffff81befbbf-ffffffff81befbdb: pci_sriov_configure_simple.cold (STB_LOCAL)
ffffffff81659d80-ffffffff81659dea: pci_sriov_configure_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_sriov_configure_simple(struct pci_dev *dev, int nr_virtfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (ffffffff816cc0e7)
Location: drivers/pci/iov.c:1163
Inline: True
```
**Symbols:**

```
ffffffff81ceafe0-ffffffff81ceaffc: pci_sriov_configure_simple.cold (STB_LOCAL)
ffffffff816cc0b0-ffffffff816cc11a: pci_sriov_configure_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_sriov_configure_simple(struct pci_dev *dev, int nr_virtfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (ffffffff817f27d5)
Location: drivers/pci/iov.c:1204
Inline: True
```
**Symbols:**

```
ffffffff81eb2006-ffffffff81eb2022: pci_sriov_configure_simple.cold (STB_LOCAL)
ffffffff817f27a0-ffffffff817f2811: pci_sriov_configure_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int pci_sriov_configure_simple(struct pci_dev *dev, int nr_virtfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff8191adf0)
Location: drivers/pci/iov.c:1204
Inline: True
```
**Symbols:**

```
ffffffff8191adf0-ffffffff8191ae78: pci_sriov_configure_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int pci_sriov_configure_simple(struct pci_dev *dev, int nr_virtfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff8195e400)
Location: drivers/pci/iov.c:1204
Inline: True
```
**Symbols:**

```
ffffffff8195e400-ffffffff8195e487: pci_sriov_configure_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int pci_sriov_configure_simple(struct pci_dev *dev, int nr_virtfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff819a7a60)
Location: drivers/pci/iov.c:1206
Inline: True
```
**Symbols:**

```
ffffffff819a7a60-ffffffff819a7ae7: pci_sriov_configure_simple (STB_GLOBAL)
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
int pci_sriov_configure_simple(struct pci_dev *dev, int nr_virtfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffff800010717910)
Location: drivers/pci/iov.c:1049
Inline: True
```
**Symbols:**

```
ffff800010717910-ffff8000107179a0: pci_sriov_configure_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int pci_sriov_configure_simple(struct pci_dev *dev, int nr_virtfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (c08a2048)
Location: drivers/pci/iov.c:1049
Inline: True
```
**Symbols:**

```
c08a2048-c08a20d4: pci_sriov_configure_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int pci_sriov_configure_simple(struct pci_dev *dev, int nr_virtfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (c0000000008886d0)
Location: drivers/pci/iov.c:1049
Inline: True
```
**Symbols:**

```
c0000000008886d0-c0000000008887c4: pci_sriov_configure_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int pci_sriov_configure_simple(struct pci_dev *dev, int nr_virtfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffe0004e0b62)
Location: drivers/pci/iov.c:1049
Inline: True
```
**Symbols:**

```
ffffffe0004e0b62-ffffffe0004e0c02: pci_sriov_configure_simple (STB_GLOBAL)
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
int pci_sriov_configure_simple(struct pci_dev *dev, int nr_virtfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (ffffffff815a11f7)
Location: drivers/pci/iov.c:1049
Inline: True
```
**Symbols:**

```
ffffffff815a1b59-ffffffff815a1b75: pci_sriov_configure_simple.cold (STB_LOCAL)
ffffffff815a11c0-ffffffff815a122a: pci_sriov_configure_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_sriov_configure_simple(struct pci_dev *dev, int nr_virtfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (ffffffff81590387)
Location: drivers/pci/iov.c:1049
Inline: True
```
**Symbols:**

```
ffffffff81590cf9-ffffffff81590d15: pci_sriov_configure_simple.cold (STB_LOCAL)
ffffffff81590350-ffffffff815903ba: pci_sriov_configure_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_sriov_configure_simple(struct pci_dev *dev, int nr_virtfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (ffffffff815a1777)
Location: drivers/pci/iov.c:1049
Inline: True
```
**Symbols:**

```
ffffffff815a20e9-ffffffff815a2105: pci_sriov_configure_simple.cold (STB_LOCAL)
ffffffff815a1740-ffffffff815a17aa: pci_sriov_configure_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_sriov_configure_simple(struct pci_dev *dev, int nr_virtfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (ffffffff815bbb6e)
Location: drivers/pci/iov.c:1049
Inline: True
```
**Symbols:**

```
ffffffff815bc4e9-ffffffff815bc505: pci_sriov_configure_simple.cold (STB_LOCAL)
ffffffff815bbb40-ffffffff815bbba1: pci_sriov_configure_simple (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
