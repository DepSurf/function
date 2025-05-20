# Function: <code>uhci_reset_hc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void uhci_reset_hc(struct pci_dev *pdev, long unsigned int base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff816303e0)
Location: drivers/usb/host/pci-quirks.c:457
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_reset_hc
```
**Symbols:**

```
ffffffff816303e0-ffffffff8163044a: uhci_reset_hc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void uhci_reset_hc(struct pci_dev *pdev, long unsigned int base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff81691040)
Location: drivers/usb/host/pci-quirks.c:457
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_reset_hc
```
**Symbols:**

```
ffffffff81691040-ffffffff816910aa: uhci_reset_hc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void uhci_reset_hc(struct pci_dev *pdev, long unsigned int base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff816bf0f0)
Location: drivers/usb/host/pci-quirks.c:456
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_reset_hc
```
**Symbols:**

```
ffffffff816bf0f0-ffffffff816bf15a: uhci_reset_hc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void uhci_reset_hc(struct pci_dev *pdev, long unsigned int base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff816d39a0)
Location: drivers/usb/host/pci-quirks.c:518
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_reset_hc
```
**Symbols:**

```
ffffffff816d39a0-ffffffff816d3a03: uhci_reset_hc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void uhci_reset_hc(struct pci_dev *pdev, long unsigned int base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff81740090)
Location: drivers/usb/host/pci-quirks.c:519
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_reset_hc
```
**Symbols:**

```
ffffffff81740090-ffffffff817400f3: uhci_reset_hc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void uhci_reset_hc(struct pci_dev *pdev, long unsigned int base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff81780c00)
Location: drivers/usb/host/pci-quirks.c:628
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_reset_hc
```
**Symbols:**

```
ffffffff81780c00-ffffffff81780c65: uhci_reset_hc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void uhci_reset_hc(struct pci_dev *pdev, long unsigned int base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff817a7420)
Location: drivers/usb/host/pci-quirks.c:628
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_reset_hc
```
**Symbols:**

```
ffffffff817a7420-ffffffff817a7485: uhci_reset_hc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void uhci_reset_hc(struct pci_dev *pdev, long unsigned int base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/pci-quirks.c (0)
Location: drivers/usb/host/pci-quirks.c:637
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_reset_hc
```
**Symbols:**

```
ffffffff817e71cc-ffffffff817e71e5: uhci_reset_hc.cold (STB_LOCAL)
ffffffff817e6630-ffffffff817e6683: uhci_reset_hc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void uhci_reset_hc(struct pci_dev *pdev, long unsigned int base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/pci-quirks.c (0)
Location: drivers/usb/host/pci-quirks.c:637
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_reset_hc
```
**Symbols:**

```
ffffffff8181808c-ffffffff818180a5: uhci_reset_hc.cold (STB_LOCAL)
ffffffff818174f0-ffffffff81817543: uhci_reset_hc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void uhci_reset_hc(struct pci_dev *pdev, long unsigned int base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/pci-quirks.c (0)
Location: drivers/usb/host/pci-quirks.c:640
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_reset_hc
```
**Symbols:**

```
ffffffff818e920e-ffffffff818e9227: uhci_reset_hc.cold (STB_LOCAL)
ffffffff818e8570-ffffffff818e85c3: uhci_reset_hc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void uhci_reset_hc(struct pci_dev *pdev, long unsigned int base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/pci-quirks.c (0)
Location: drivers/usb/host/pci-quirks.c:640
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_reset_hc
```
**Symbols:**

```
ffffffff81c1ff94-ffffffff81c1ffad: uhci_reset_hc.cold (STB_LOCAL)
ffffffff818f1550-ffffffff818f15a3: uhci_reset_hc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void uhci_reset_hc(struct pci_dev *pdev, long unsigned int base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/pci-quirks.c (0)
Location: drivers/usb/host/pci-quirks.c:640
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_reset_hc
```
**Symbols:**

```
ffffffff81c11f7d-ffffffff81c11f96: uhci_reset_hc.cold (STB_LOCAL)
ffffffff818d4d50-ffffffff818d4dab: uhci_reset_hc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void uhci_reset_hc(struct pci_dev *pdev, long unsigned int base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/pci-quirks.c (0)
Location: drivers/usb/host/pci-quirks.c:640
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_reset_hc
```
**Symbols:**

```
ffffffff81d1e736-ffffffff81d1e74f: uhci_reset_hc.cold (STB_LOCAL)
ffffffff8196f470-ffffffff8196f4cb: uhci_reset_hc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void uhci_reset_hc(struct pci_dev *pdev, long unsigned int base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/pci-quirks.c (0)
Location: drivers/usb/host/pci-quirks.c:640
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_reset_hc
```
**Symbols:**

```
ffffffff81eea1f9-ffffffff81eea212: uhci_reset_hc.cold (STB_LOCAL)
ffffffff81ac9950-ffffffff81ac99b7: uhci_reset_hc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void uhci_reset_hc(struct pci_dev *pdev, long unsigned int base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff81c53dd0)
Location: drivers/usb/host/pci-quirks.c:640
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_reset_hc
```
**Symbols:**

```
ffffffff81c53dd0-ffffffff81c53e49: uhci_reset_hc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void uhci_reset_hc(struct pci_dev *pdev, long unsigned int base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff81cbb2c0)
Location: drivers/usb/host/pci-quirks.c:638
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_reset_hc
```
**Symbols:**

```
ffffffff81cbb2c0-ffffffff81cbb339: uhci_reset_hc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void uhci_reset_hc(struct pci_dev *pdev, long unsigned int base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff81d702f0)
Location: drivers/usb/host/pci-quirks.c:651
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_reset_hc
```
**Symbols:**

```
ffffffff81d702f0-ffffffff81d70369: uhci_reset_hc (STB_GLOBAL)
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
void uhci_reset_hc(struct pci_dev *pdev, long unsigned int base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffff800010a4fd40)
Location: drivers/usb/host/pci-quirks.c:637
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_reset_hc
```
**Symbols:**

```
ffff800010a4fd40-ffff800010a4fdc8: uhci_reset_hc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void uhci_reset_hc(struct pci_dev *pdev, long unsigned int base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (c0b22808)
Location: drivers/usb/host/pci-quirks.c:637
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_reset_hc
```
**Symbols:**

```
c0b22808-c0b228bc: uhci_reset_hc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void uhci_reset_hc(struct pci_dev *pdev, long unsigned int base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (c000000000b18a50)
Location: drivers/usb/host/pci-quirks.c:637
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_reset_hc
```
**Symbols:**

```
c000000000b18a50-c000000000b18c78: uhci_reset_hc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void uhci_reset_hc(struct pci_dev *pdev, long unsigned int base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffe00066ce66)
Location: drivers/usb/host/pci-quirks.c:637
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_reset_hc
```
**Symbols:**

```
ffffffe00066ce66-ffffffe00066cf16: uhci_reset_hc (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void uhci_reset_hc(struct pci_dev *pdev, long unsigned int base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/pci-quirks.c (0)
Location: drivers/usb/host/pci-quirks.c:637
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_reset_hc
```
**Symbols:**

```
ffffffff817d046c-ffffffff817d0485: uhci_reset_hc.cold (STB_LOCAL)
ffffffff817cf8d0-ffffffff817cf923: uhci_reset_hc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void uhci_reset_hc(struct pci_dev *pdev, long unsigned int base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/pci-quirks.c (0)
Location: drivers/usb/host/pci-quirks.c:637
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
```
**Symbols:**

```
ffffffff817ae39c-ffffffff817ae3b5: uhci_reset_hc.cold (STB_LOCAL)
ffffffff817ad800-ffffffff817ad853: uhci_reset_hc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void uhci_reset_hc(struct pci_dev *pdev, long unsigned int base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/pci-quirks.c (0)
Location: drivers/usb/host/pci-quirks.c:637
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_reset_hc
```
**Symbols:**

```
ffffffff8180cf0c-ffffffff8180cf25: uhci_reset_hc.cold (STB_LOCAL)
ffffffff8180c370-ffffffff8180c3c3: uhci_reset_hc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void uhci_reset_hc(struct pci_dev *pdev, long unsigned int base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/pci-quirks.c (0)
Location: drivers/usb/host/pci-quirks.c:637
Inline: False
Direct callers:
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/uhci-hcd.c:uhci_pci_reset_hc
```
**Symbols:**

```
ffffffff8182701c-ffffffff81827035: uhci_reset_hc.cold (STB_LOCAL)
ffffffff81826480-ffffffff818264d3: uhci_reset_hc (STB_GLOBAL)
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
