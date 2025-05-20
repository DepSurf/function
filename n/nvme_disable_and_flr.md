# Function: <code>nvme_disable_and_flr</code>

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
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int nvme_disable_and_flr(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81546460)
Location: drivers/pci/quirks.c:3740
Inline: True
```
**Symbols:**

```
ffffffff81546460-ffffffff815465ad: nvme_disable_and_flr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int nvme_disable_and_flr(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81575747)
Location: drivers/pci/quirks.c:3756
Inline: True
```
**Symbols:**

```
ffffffff815756d0-ffffffff81575807: nvme_disable_and_flr (STB_LOCAL)
ffffffff81577433-ffffffff8157744c: nvme_disable_and_flr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int nvme_disable_and_flr(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81596de7)
Location: drivers/pci/quirks.c:3821
Inline: True
```
**Symbols:**

```
ffffffff81596d70-ffffffff81596ea7: nvme_disable_and_flr (STB_LOCAL)
ffffffff81598b69-ffffffff81598b82: nvme_disable_and_flr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int nvme_disable_and_flr(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81645390)
Location: drivers/pci/quirks.c:3898
Inline: True
```
**Symbols:**

```
ffffffff81645290-ffffffff81645387: nvme_disable_and_flr.part.0 (STB_LOCAL)
ffffffff8164745c-ffffffff81647475: nvme_disable_and_flr.part.0.cold (STB_LOCAL)
ffffffff81645390-ffffffff816453e3: nvme_disable_and_flr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int nvme_disable_and_flr(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff8166b6d0)
Location: drivers/pci/quirks.c:3842
Inline: True
```
**Symbols:**

```
ffffffff8166b5d0-ffffffff8166b6c7: nvme_disable_and_flr.part.0 (STB_LOCAL)
ffffffff81bfafe2-ffffffff81bfaffb: nvme_disable_and_flr.part.0.cold (STB_LOCAL)
ffffffff8166b6d0-ffffffff8166b723: nvme_disable_and_flr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int nvme_disable_and_flr(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff8164da07)
Location: drivers/pci/quirks.c:3864
Inline: True
```
**Symbols:**

```
ffffffff8164d990-ffffffff8164dac9: nvme_disable_and_flr (STB_LOCAL)
ffffffff81bece4a-ffffffff81bece63: nvme_disable_and_flr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int nvme_disable_and_flr(struct pci_dev *dev, bool probe);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff816bf7d4)
Location: drivers/pci/quirks.c:3905
Inline: True
```
**Symbols:**

```
ffffffff816bf750-ffffffff816bf894: nvme_disable_and_flr (STB_LOCAL)
ffffffff81ce7b2d-ffffffff81ce7b46: nvme_disable_and_flr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int nvme_disable_and_flr(struct pci_dev *dev, bool probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (0)
Location: drivers/pci/quirks.c:3918
Inline: False
```
**Symbols:**

```
ffffffff817e3c00-ffffffff817e3d61: nvme_disable_and_flr (STB_LOCAL)
ffffffff81eae419-ffffffff81eae431: nvme_disable_and_flr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int nvme_disable_and_flr(struct pci_dev *dev, bool probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81907d40)
Location: drivers/pci/quirks.c:3929
Inline: False
```
**Symbols:**

```
ffffffff81907d40-ffffffff81907eb2: nvme_disable_and_flr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int nvme_disable_and_flr(struct pci_dev *dev, bool probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff8194b390)
Location: drivers/pci/quirks.c:4035
Inline: False
```
**Symbols:**

```
ffffffff8194b390-ffffffff8194b502: nvme_disable_and_flr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int nvme_disable_and_flr(struct pci_dev *dev, bool probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81994740)
Location: drivers/pci/quirks.c:4062
Inline: False
```
**Symbols:**

```
ffffffff81994740-ffffffff819948b2: nvme_disable_and_flr (STB_LOCAL)
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
int nvme_disable_and_flr(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffff8000106ff4e8)
Location: drivers/pci/quirks.c:3821
Inline: True
```
**Symbols:**

```
ffff8000106ff4e8-ffff8000106ff680: nvme_disable_and_flr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int nvme_disable_and_flr(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (c0896b7c)
Location: drivers/pci/quirks.c:3821
Inline: True
```
**Symbols:**

```
c0896b7c-c0896cf4: nvme_disable_and_flr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int nvme_disable_and_flr(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (c00000000087e6e0)
Location: drivers/pci/quirks.c:3821
Inline: True
```
**Symbols:**

```
c00000000087e6e0-c00000000087e9d0: nvme_disable_and_flr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int nvme_disable_and_flr(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffe0004cdeb0)
Location: drivers/pci/quirks.c:3821
Inline: True
```
**Symbols:**

```
ffffffe0004cdeb0-ffffffe0004ce002: nvme_disable_and_flr (STB_LOCAL)
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
int nvme_disable_and_flr(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff8158ac77)
Location: drivers/pci/quirks.c:3821
Inline: True
```
**Symbols:**

```
ffffffff8158ac00-ffffffff8158ad37: nvme_disable_and_flr (STB_LOCAL)
ffffffff8158c9f9-ffffffff8158ca12: nvme_disable_and_flr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int nvme_disable_and_flr(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff815797b7)
Location: drivers/pci/quirks.c:3821
Inline: True
```
**Symbols:**

```
ffffffff81579740-ffffffff81579877: nvme_disable_and_flr (STB_LOCAL)
ffffffff8157b539-ffffffff8157b552: nvme_disable_and_flr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int nvme_disable_and_flr(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff8158ab37)
Location: drivers/pci/quirks.c:3821
Inline: True
```
**Symbols:**

```
ffffffff8158aac0-ffffffff8158abf7: nvme_disable_and_flr (STB_LOCAL)
ffffffff8158c8b9-ffffffff8158c8d2: nvme_disable_and_flr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int nvme_disable_and_flr(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff815a4fe7)
Location: drivers/pci/quirks.c:3821
Inline: True
```
**Symbols:**

```
ffffffff815a4f70-ffffffff815a50a7: nvme_disable_and_flr (STB_LOCAL)
ffffffff815a6d69-ffffffff815a6d82: nvme_disable_and_flr.cold (STB_LOCAL)
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
