# Function: <code>usb_hcd_pci_probe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int usb_hcd_pci_probe(struct pci_dev *dev, const struct pci_device_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff8161f830)
Location: drivers/usb/core/hcd-pci.c:177
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff8161f830-ffffffff8161fcf1: usb_hcd_pci_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int usb_hcd_pci_probe(struct pci_dev *dev, const struct pci_device_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff81680210)
Location: drivers/usb/core/hcd-pci.c:185
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff81680210-ffffffff816806a8: usb_hcd_pci_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int usb_hcd_pci_probe(struct pci_dev *dev, const struct pci_device_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff816adf40)
Location: drivers/usb/core/hcd-pci.c:185
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff816adf40-ffffffff816ae3d8: usb_hcd_pci_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int usb_hcd_pci_probe(struct pci_dev *dev, const struct pci_device_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff816c3950)
Location: drivers/usb/core/hcd-pci.c:185
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff816c3950-ffffffff816c3dce: usb_hcd_pci_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int usb_hcd_pci_probe(struct pci_dev *dev, const struct pci_device_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff8172f730)
Location: drivers/usb/core/hcd-pci.c:172
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff8172f730-ffffffff8172fbae: usb_hcd_pci_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int usb_hcd_pci_probe(struct pci_dev *dev, const struct pci_device_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff8176dfd0)
Location: drivers/usb/core/hcd-pci.c:172
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff8176dfd0-ffffffff8176e436: usb_hcd_pci_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int usb_hcd_pci_probe(struct pci_dev *dev, const struct pci_device_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff81792650)
Location: drivers/usb/core/hcd-pci.c:172
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff81792650-ffffffff81792ab6: usb_hcd_pci_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int usb_hcd_pci_probe(struct pci_dev *dev, const struct pci_device_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd-pci.c (0)
Location: drivers/usb/core/hcd-pci.c:172
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff817d1be4-ffffffff817d1c31: usb_hcd_pci_probe.cold (STB_LOCAL)
ffffffff817d17d0-ffffffff817d1b82: usb_hcd_pci_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int usb_hcd_pci_probe(struct pci_dev *dev, const struct pci_device_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd-pci.c (0)
Location: drivers/usb/core/hcd-pci.c:172
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff81802ab4-ffffffff81802b01: usb_hcd_pci_probe.cold (STB_LOCAL)
ffffffff818026a0-ffffffff81802a52: usb_hcd_pci_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int usb_hcd_pci_probe(struct pci_dev *dev, const struct pci_device_id *id, const struct hc_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd-pci.c (0)
Location: drivers/usb/core/hcd-pci.c:173
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_probe
  - drivers/usb/host/ohci-pci.c:ohci_pci_probe
  - drivers/usb/host/uhci-hcd.c:uhci_pci_probe
```
**Symbols:**

```
ffffffff818d31ca-ffffffff818d3217: usb_hcd_pci_probe.cold (STB_LOCAL)
ffffffff818d2630-ffffffff818d29e6: usb_hcd_pci_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int usb_hcd_pci_probe(struct pci_dev *dev, const struct pci_device_id *id, const struct hc_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd-pci.c (0)
Location: drivers/usb/core/hcd-pci.c:174
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_probe
  - drivers/usb/host/ohci-pci.c:ohci_pci_probe
  - drivers/usb/host/uhci-hcd.c:uhci_pci_probe
```
**Symbols:**

```
ffffffff81c1ea87-ffffffff81c1eadb: usb_hcd_pci_probe.cold (STB_LOCAL)
ffffffff818dc9e0-ffffffff818dcde3: usb_hcd_pci_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int usb_hcd_pci_probe(struct pci_dev *dev, const struct pci_device_id *id, const struct hc_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd-pci.c (0)
Location: drivers/usb/core/hcd-pci.c:174
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_probe
  - drivers/usb/host/ohci-pci.c:ohci_pci_probe
  - drivers/usb/host/uhci-hcd.c:uhci_pci_probe
```
**Symbols:**

```
ffffffff81c10918-ffffffff81c1096c: usb_hcd_pci_probe.cold (STB_LOCAL)
ffffffff818bfd50-ffffffff818c0153: usb_hcd_pci_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int usb_hcd_pci_probe(struct pci_dev *dev, const struct pci_device_id *id, const struct hc_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd-pci.c (0)
Location: drivers/usb/core/hcd-pci.c:174
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_probe
  - drivers/usb/host/ohci-pci.c:ohci_pci_probe
  - drivers/usb/host/uhci-hcd.c:uhci_pci_probe
```
**Symbols:**

```
ffffffff81d17c49-ffffffff81d17ca2: usb_hcd_pci_probe.cold (STB_LOCAL)
ffffffff819563c0-ffffffff819568a2: usb_hcd_pci_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int usb_hcd_pci_probe(struct pci_dev *dev, const struct pci_device_id *id, const struct hc_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd-pci.c (0)
Location: drivers/usb/core/hcd-pci.c:173
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_probe
  - drivers/usb/host/ohci-pci.c:ohci_pci_probe
  - drivers/usb/host/uhci-hcd.c:uhci_pci_probe
```
**Symbols:**

```
ffffffff81ee2aff-ffffffff81ee2b54: usb_hcd_pci_probe.cold (STB_LOCAL)
ffffffff81aaff90-ffffffff81ab049b: usb_hcd_pci_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int usb_hcd_pci_probe(struct pci_dev *dev, const struct hc_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff81c380a0)
Location: drivers/usb/core/hcd-pci.c:172
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_probe
  - drivers/usb/host/ohci-pci.c:ohci_pci_probe
  - drivers/usb/host/uhci-hcd.c:uhci_pci_probe
```
**Symbols:**

```
ffffffff81c380a0-ffffffff81c38615: usb_hcd_pci_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int usb_hcd_pci_probe(struct pci_dev *dev, const struct hc_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff81c9f460)
Location: drivers/usb/core/hcd-pci.c:172
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_probe
  - drivers/usb/host/ohci-pci.c:ohci_pci_probe
  - drivers/usb/host/uhci-hcd.c:uhci_pci_probe
```
**Symbols:**

```
ffffffff81c9f460-ffffffff81c9f997: usb_hcd_pci_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int usb_hcd_pci_probe(struct pci_dev *dev, const struct hc_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffff81d540b0)
Location: drivers/usb/core/hcd-pci.c:172
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_probe
  - drivers/usb/host/ohci-pci.c:ohci_pci_probe
  - drivers/usb/host/uhci-hcd.c:uhci_pci_probe
```
**Symbols:**

```
ffffffff81d540b0-ffffffff81d545ee: usb_hcd_pci_probe (STB_GLOBAL)
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
int usb_hcd_pci_probe(struct pci_dev *dev, const struct pci_device_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffff800010a36e90)
Location: drivers/usb/core/hcd-pci.c:172
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffff800010a36e90-ffff800010a3725c: usb_hcd_pci_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int usb_hcd_pci_probe(struct pci_dev *dev, const struct pci_device_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (c0b0a290)
Location: drivers/usb/core/hcd-pci.c:172
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
c0b0a290-c0b0a68c: usb_hcd_pci_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int usb_hcd_pci_probe(struct pci_dev *dev, const struct pci_device_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (c000000000af4830)
Location: drivers/usb/core/hcd-pci.c:172
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
c000000000af4830-c000000000af4d4c: usb_hcd_pci_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int usb_hcd_pci_probe(struct pci_dev *dev, const struct pci_device_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd-pci.c (ffffffe000653978)
Location: drivers/usb/core/hcd-pci.c:172
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffe000653978-ffffffe000653ce0: usb_hcd_pci_probe (STB_GLOBAL)
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
int usb_hcd_pci_probe(struct pci_dev *dev, const struct pci_device_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd-pci.c (0)
Location: drivers/usb/core/hcd-pci.c:172
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff817bae94-ffffffff817baee1: usb_hcd_pci_probe.cold (STB_LOCAL)
ffffffff817baa80-ffffffff817bae32: usb_hcd_pci_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int usb_hcd_pci_probe(struct pci_dev *dev, const struct pci_device_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd-pci.c (0)
Location: drivers/usb/core/hcd-pci.c:172
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff817ac8b4-ffffffff817ac901: usb_hcd_pci_probe.cold (STB_LOCAL)
ffffffff817ac4a0-ffffffff817ac852: usb_hcd_pci_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int usb_hcd_pci_probe(struct pci_dev *dev, const struct pci_device_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd-pci.c (0)
Location: drivers/usb/core/hcd-pci.c:172
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff817f7934-ffffffff817f7981: usb_hcd_pci_probe.cold (STB_LOCAL)
ffffffff817f7520-ffffffff817f78d2: usb_hcd_pci_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int usb_hcd_pci_probe(struct pci_dev *dev, const struct pci_device_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd-pci.c (0)
Location: drivers/usb/core/hcd-pci.c:172
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff81811b74-ffffffff81811bc1: usb_hcd_pci_probe.cold (STB_LOCAL)
ffffffff81811760-ffffffff81811b12: usb_hcd_pci_probe (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct hc_driver *driver</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>const struct pci_device_id *id</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, id, driver</code> ➡️ <code>dev, driver</code>
</li>
</ul>
</details>
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
