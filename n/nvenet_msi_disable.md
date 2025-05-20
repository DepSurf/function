# Function: <code>nvenet_msi_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void nvenet_msi_disable(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81444a40)
Location: drivers/pci/quirks.c:2389
Inline: False
```
**Symbols:**

```
ffffffff81444a40-ffffffff81444aaa: nvenet_msi_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void nvenet_msi_disable(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81490920)
Location: drivers/pci/quirks.c:2430
Inline: False
```
**Symbols:**

```
ffffffff81490920-ffffffff8149098a: nvenet_msi_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void nvenet_msi_disable(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff814b2170)
Location: drivers/pci/quirks.c:2442
Inline: False
```
**Symbols:**

```
ffffffff814b2170-ffffffff814b21da: nvenet_msi_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void nvenet_msi_disable(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff814be290)
Location: drivers/pci/quirks.c:2502
Inline: True
```
**Symbols:**

```
ffffffff814be290-ffffffff814be2fd: nvenet_msi_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void nvenet_msi_disable(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff814fe620)
Location: drivers/pci/quirks.c:2503
Inline: True
```
**Symbols:**

```
ffffffff814fe620-ffffffff814fe68d: nvenet_msi_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void nvenet_msi_disable(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff8152edf0)
Location: drivers/pci/quirks.c:2541
Inline: True
```
**Symbols:**

```
ffffffff8152edf0-ffffffff8152ee5d: nvenet_msi_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void nvenet_msi_disable(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81545c70)
Location: drivers/pci/quirks.c:2582
Inline: True
```
**Symbols:**

```
ffffffff81545c70-ffffffff81545cdd: nvenet_msi_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void nvenet_msi_disable(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff815772c7)
Location: drivers/pci/quirks.c:2597
Inline: True
```
**Symbols:**

```
ffffffff81575000-ffffffff81575056: nvenet_msi_disable (STB_LOCAL)
ffffffff815772c7-ffffffff815772e6: nvenet_msi_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void nvenet_msi_disable(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff815989fd)
Location: drivers/pci/quirks.c:2591
Inline: True
```
**Symbols:**

```
ffffffff815966a0-ffffffff815966f6: nvenet_msi_disable (STB_LOCAL)
ffffffff815989fd-ffffffff81598a1c: nvenet_msi_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void nvenet_msi_disable(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff8164733e)
Location: drivers/pci/quirks.c:2668
Inline: True
```
**Symbols:**

```
ffffffff81644d70-ffffffff81644dc6: nvenet_msi_disable (STB_LOCAL)
ffffffff8164733e-ffffffff8164735d: nvenet_msi_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void nvenet_msi_disable(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81bfaeee)
Location: drivers/pci/quirks.c:2669
Inline: True
```
**Symbols:**

```
ffffffff8166b180-ffffffff8166b1d6: nvenet_msi_disable (STB_LOCAL)
ffffffff81bfaeee-ffffffff81bfaf0d: nvenet_msi_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void nvenet_msi_disable(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81becd37)
Location: drivers/pci/quirks.c:2659
Inline: True
```
**Symbols:**

```
ffffffff8164d470-ffffffff8164d4c6: nvenet_msi_disable (STB_LOCAL)
ffffffff81becd37-ffffffff81becd56: nvenet_msi_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void nvenet_msi_disable(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81ce7a1f)
Location: drivers/pci/quirks.c:2698
Inline: True
```
**Symbols:**

```
ffffffff816bf230-ffffffff816bf286: nvenet_msi_disable (STB_LOCAL)
ffffffff81ce7a1f-ffffffff81ce7a3e: nvenet_msi_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void nvenet_msi_disable(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81eaeb79)
Location: drivers/pci/quirks.c:2711
Inline: True
```
**Symbols:**

```
ffffffff817e4cf0-ffffffff817e4d50: nvenet_msi_disable (STB_LOCAL)
ffffffff81eaeb79-ffffffff81eaeb9b: nvenet_msi_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void nvenet_msi_disable(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81909680)
Location: drivers/pci/quirks.c:2713
Inline: True
```
**Symbols:**

```
ffffffff81909680-ffffffff819096f7: nvenet_msi_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void nvenet_msi_disable(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff8194cd00)
Location: drivers/pci/quirks.c:2819
Inline: True
```
**Symbols:**

```
ffffffff8194cd00-ffffffff8194cd77: nvenet_msi_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void nvenet_msi_disable(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81995fc0)
Location: drivers/pci/quirks.c:2833
Inline: True
```
**Symbols:**

```
ffffffff81995fc0-ffffffff81996037: nvenet_msi_disable (STB_LOCAL)
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
void nvenet_msi_disable(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffff8000106fdd80)
Location: drivers/pci/quirks.c:2591
Inline: True
```
**Symbols:**

```
ffff8000106fdd80-ffff8000106fddf8: nvenet_msi_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void nvenet_msi_disable(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (c08963c4)
Location: drivers/pci/quirks.c:2591
Inline: True
```
**Symbols:**

```
c08963c4-c0896438: nvenet_msi_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void nvenet_msi_disable(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (c000000000877cc0)
Location: drivers/pci/quirks.c:2591
Inline: False
```
**Symbols:**

```
c000000000877cc0-c000000000877ccc: nvenet_msi_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void nvenet_msi_disable(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffe0004ca444)
Location: drivers/pci/quirks.c:2591
Inline: False
```
**Symbols:**

```
ffffffe0004ca444-ffffffe0004ca45e: nvenet_msi_disable (STB_LOCAL)
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
void nvenet_msi_disable(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff8158c88d)
Location: drivers/pci/quirks.c:2591
Inline: True
```
**Symbols:**

```
ffffffff8158a530-ffffffff8158a586: nvenet_msi_disable (STB_LOCAL)
ffffffff8158c88d-ffffffff8158c8ac: nvenet_msi_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void nvenet_msi_disable(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff8157b3cd)
Location: drivers/pci/quirks.c:2591
Inline: True
```
**Symbols:**

```
ffffffff81579070-ffffffff815790c6: nvenet_msi_disable (STB_LOCAL)
ffffffff8157b3cd-ffffffff8157b3ec: nvenet_msi_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void nvenet_msi_disable(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff8158c74d)
Location: drivers/pci/quirks.c:2591
Inline: True
```
**Symbols:**

```
ffffffff8158a3f0-ffffffff8158a446: nvenet_msi_disable (STB_LOCAL)
ffffffff8158c74d-ffffffff8158c76c: nvenet_msi_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void nvenet_msi_disable(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff815a6bfd)
Location: drivers/pci/quirks.c:2591
Inline: True
```
**Symbols:**

```
ffffffff815a48a0-ffffffff815a48f6: nvenet_msi_disable (STB_LOCAL)
ffffffff815a6bfd-ffffffff815a6c1c: nvenet_msi_disable.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
