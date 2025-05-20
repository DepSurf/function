# Function: <code>pci_clear_mwi</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pci_clear_mwi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81433c40)
Location: drivers/pci/pci.c:3230
Inline: False
```
**Symbols:**

```
ffffffff81433c40-ffffffff81433cb4: pci_clear_mwi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pci_clear_mwi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8147f5c0)
Location: drivers/pci/pci.c:3540
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_remove
```
**Symbols:**

```
ffffffff8147f5c0-ffffffff8147f634: pci_clear_mwi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pci_clear_mwi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a0c00)
Location: drivers/pci/pci.c:3578
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_remove
```
**Symbols:**

```
ffffffff814a0c00-ffffffff814a0c74: pci_clear_mwi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pci_clear_mwi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814aa7c0)
Location: drivers/pci/pci.c:3716
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_remove
```
**Symbols:**

```
ffffffff814aa7c0-ffffffff814aa829: pci_clear_mwi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_clear_mwi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814e99b0)
Location: drivers/pci/pci.c:3731
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_remove
```
**Symbols:**

```
ffffffff814e99b0-ffffffff814e9a19: pci_clear_mwi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_clear_mwi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815191f0)
Location: drivers/pci/pci.c:3936
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/usb/host/ehci-pci.c:ehci_pci_remove
```
**Symbols:**

```
ffffffff815191f0-ffffffff8151925b: pci_clear_mwi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_clear_mwi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8152ec60)
Location: drivers/pci/pci.c:4201
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/usb/host/ehci-pci.c:ehci_pci_remove
```
**Symbols:**

```
ffffffff8152ec60-ffffffff8152eccb: pci_clear_mwi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pci_clear_mwi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8155e3f0)
Location: drivers/pci/pci.c:4299
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/usb/host/ehci-pci.c:ehci_pci_remove
```
**Symbols:**

```
ffffffff8155e3f0-ffffffff8155e45d: pci_clear_mwi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pci_clear_mwi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8157f4a0)
Location: drivers/pci/pci.c:4295
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/usb/host/ehci-pci.c:ehci_pci_remove
```
**Symbols:**

```
ffffffff8157f4a0-ffffffff8157f50d: pci_clear_mwi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void pci_clear_mwi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81629acb)
Location: drivers/pci/pci.c:4366
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_release
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_remove
```
**Symbols:**

```
ffffffff816247e0-ffffffff8162484b: pci_clear_mwi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void pci_clear_mwi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8164fe9b)
Location: drivers/pci/pci.c:4441
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_release
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_remove
```
**Symbols:**

```
ffffffff8164a430-ffffffff8164a49b: pci_clear_mwi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void pci_clear_mwi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81632a5b)
Location: drivers/pci/pci.c:4473
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_release
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_remove
```
**Symbols:**

```
ffffffff8162d020-ffffffff8162d08b: pci_clear_mwi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void pci_clear_mwi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816a2bcb)
Location: drivers/pci/pci.c:4523
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_release
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_remove
```
**Symbols:**

```
ffffffff8169c2e0-ffffffff8169c34b: pci_clear_mwi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void pci_clear_mwi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c4cd7)
Location: drivers/pci/pci.c:4619
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_release
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_remove
```
**Symbols:**

```
ffffffff817bdd40-ffffffff817bddbc: pci_clear_mwi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pci_clear_mwi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818e1cc7)
Location: drivers/pci/pci.c:4562
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_release
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_remove
```
**Symbols:**

```
ffffffff818d9fa0-ffffffff818da01c: pci_clear_mwi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pci_clear_mwi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81925107)
Location: drivers/pci/pci.c:4600
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_release
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_remove
```
**Symbols:**

```
ffffffff8191d2f0-ffffffff8191d36c: pci_clear_mwi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pci_clear_mwi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8196d7d7)
Location: drivers/pci/pci.c:4710
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcim_release
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_remove
```
**Symbols:**

```
ffffffff81965720-ffffffff8196579c: pci_clear_mwi (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void pci_clear_mwi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e1ec8)
Location: drivers/pci/pci.c:4295
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/usb/host/ehci-pci.c:ehci_pci_remove
```
**Symbols:**

```
ffff8000106e1ec8-ffff8000106e1f4c: pci_clear_mwi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_clear_mwi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c087db48)
Location: drivers/pci/pci.c:4295
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/usb/host/ehci-pci.c:ehci_pci_remove
```
**Symbols:**

```
c087db48-c087dbd0: pci_clear_mwi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void pci_clear_mwi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c00000000085ae20)
Location: drivers/pci/pci.c:4295
Inline: True
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_remove
```
**Symbols:**

```
c00000000085ae20-c00000000085ae2c: pci_clear_mwi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_clear_mwi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004b9a3c)
Location: drivers/pci/pci.c:4295
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/usb/host/ehci-pci.c:ehci_pci_remove
```
**Symbols:**

```
ffffffe0004b9a3c-ffffffe0004b9a96: pci_clear_mwi (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void pci_clear_mwi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815739c0)
Location: drivers/pci/pci.c:4295
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/usb/host/ehci-pci.c:ehci_pci_remove
```
**Symbols:**

```
ffffffff815739c0-ffffffff81573a2d: pci_clear_mwi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pci_clear_mwi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81562120)
Location: drivers/pci/pci.c:4295
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcim_release
```
**Symbols:**

```
ffffffff81562120-ffffffff8156218d: pci_clear_mwi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pci_clear_mwi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815731f0)
Location: drivers/pci/pci.c:4295
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/usb/host/ehci-pci.c:ehci_pci_remove
```
**Symbols:**

```
ffffffff815731f0-ffffffff8157325d: pci_clear_mwi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pci_clear_mwi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8158d6d0)
Location: drivers/pci/pci.c:4295
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcim_release
  - drivers/usb/host/ehci-pci.c:ehci_pci_remove
```
**Symbols:**

```
ffffffff8158d6d0-ffffffff8158d73d: pci_clear_mwi (STB_GLOBAL)
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
