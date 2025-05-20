# Function: <code>pci_ioremap_bar</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *pci_ioremap_bar(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814338f0)
Location: drivers/pci/pci.c:128
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:setup_port
  - drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
```
**Symbols:**

```
ffffffff814338f0-ffffffff81433964: pci_ioremap_bar (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *pci_ioremap_bar(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8147f1b0)
Location: drivers/pci/pci.c:149
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
```
**Symbols:**

```
ffffffff8147f1b0-ffffffff8147f206: pci_ioremap_bar (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *pci_ioremap_bar(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a0890)
Location: drivers/pci/pci.c:149
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
```
**Symbols:**

```
ffffffff814a0890-ffffffff814a08eb: pci_ioremap_bar (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *pci_ioremap_bar(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814aa540)
Location: drivers/pci/pci.c:151
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
```
**Symbols:**

```
ffffffff814aa540-ffffffff814aa599: pci_ioremap_bar (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *pci_ioremap_bar(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814e9730)
Location: drivers/pci/pci.c:152
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
```
**Symbols:**

```
ffffffff814e9730-ffffffff814e9786: pci_ioremap_bar (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *pci_ioremap_bar(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81518f70)
Location: drivers/pci/pci.c:164
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
```
**Symbols:**

```
ffffffff81518f70-ffffffff81518fc6: pci_ioremap_bar (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *pci_ioremap_bar(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8152e9e0)
Location: drivers/pci/pci.c:168
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
```
**Symbols:**

```
ffffffff8152e9e0-ffffffff8152ea3b: pci_ioremap_bar (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void *pci_ioremap_bar(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:168
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_exit
```
**Symbols:**

```
ffffffff81564910-ffffffff8156492c: pci_ioremap_bar.cold (STB_LOCAL)
ffffffff8155e180-ffffffff8155e1c6: pci_ioremap_bar (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void *pci_ioremap_bar(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:168
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_exit
```
**Symbols:**

```
ffffffff81585c10-ffffffff81585c2c: pci_ioremap_bar.cold (STB_LOCAL)
ffffffff8157f1f0-ffffffff8157f234: pci_ioremap_bar (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void *pci_ioremap_bar(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:200
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_exit
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_ohci
```
**Symbols:**

```
ffffffff8162c8b0-ffffffff8162c8d4: pci_ioremap_bar.cold (STB_LOCAL)
ffffffff81624850-ffffffff8162489a: pci_ioremap_bar (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void *pci_ioremap_bar(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:209
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_exit
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_ohci
```
**Symbols:**

```
ffffffff81bf7a8b-ffffffff81bf7aaf: pci_ioremap_bar.cold (STB_LOCAL)
ffffffff8164a4a0-ffffffff8164a4ea: pci_ioremap_bar (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void *pci_ioremap_bar(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:209
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_exit
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_ohci
```
**Symbols:**

```
ffffffff81be9932-ffffffff81be9956: pci_ioremap_bar.cold (STB_LOCAL)
ffffffff8162d090-ffffffff8162d0da: pci_ioremap_bar (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *pci_ioremap_bar(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:236
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_exit
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_ohci
```
**Symbols:**

```
ffffffff81ce46da-ffffffff81ce46f7: pci_ioremap_bar.cold (STB_LOCAL)
ffffffff8169f380-ffffffff8169f405: pci_ioremap_bar (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *pci_ioremap_bar(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:253
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_ohci
```
**Symbols:**

```
ffffffff81eab018-ffffffff81eab035: pci_ioremap_bar.cold (STB_LOCAL)
ffffffff817c0a00-ffffffff817c0a91: pci_ioremap_bar (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *pci_ioremap_bar(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818da030)
Location: drivers/pci/pci.c:237
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_ohci
```
**Symbols:**

```
ffffffff818da030-ffffffff818da0e8: pci_ioremap_bar (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *pci_ioremap_bar(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81920820)
Location: drivers/pci/pci.c:252
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_ohci
```
**Symbols:**

```
ffffffff81920820-ffffffff819208d8: pci_ioremap_bar (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *pci_ioremap_bar(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff819689b0)
Location: drivers/pci/pci.c:252
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_ohci
```
**Symbols:**

```
ffffffff819689b0-ffffffff81968a6f: pci_ioremap_bar (STB_GLOBAL)
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
void *pci_ioremap_bar(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e5918)
Location: drivers/pci/pci.c:168
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_exit
```
**Symbols:**

```
ffff8000106e5918-ffff8000106e5a38: pci_ioremap_bar (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *pci_ioremap_bar(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c087d834)
Location: drivers/pci/pci.c:168
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_exit
  - drivers/mfd/sm501.c:sm501_pci_probe
```
**Symbols:**

```
c087d834-c087d8a4: pci_ioremap_bar (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *pci_ioremap_bar(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c00000000085b190)
Location: drivers/pci/pci.c:168
Inline: False
Direct callers:
  - drivers/video/fbdev/gxt4500.c:gxt4500_probe
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_exit
```
**Symbols:**

```
c00000000085b190-c00000000085b218: pci_ioremap_bar (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *pci_ioremap_bar(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004b97a2)
Location: drivers/pci/pci.c:168
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_exit
```
**Symbols:**

```
ffffffe0004b97a2-ffffffe0004b981a: pci_ioremap_bar (STB_GLOBAL)
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
void *pci_ioremap_bar(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:168
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_exit
```
**Symbols:**

```
ffffffff8157a130-ffffffff8157a14c: pci_ioremap_bar.cold (STB_LOCAL)
ffffffff81573710-ffffffff81573756: pci_ioremap_bar (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void *pci_ioremap_bar(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:168
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_exit
```
**Symbols:**

```
ffffffff81568870-ffffffff8156888c: pci_ioremap_bar.cold (STB_LOCAL)
ffffffff81561e70-ffffffff81561eb4: pci_ioremap_bar (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void *pci_ioremap_bar(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:168
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_exit
```
**Symbols:**

```
ffffffff81579960-ffffffff8157997c: pci_ioremap_bar.cold (STB_LOCAL)
ffffffff81572f40-ffffffff81572f84: pci_ioremap_bar (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void *pci_ioremap_bar(struct pci_dev *pdev, int bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:168
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_init
  - drivers/tty/serial/8250/8250_pci.c:sbs_exit
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_exit
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8420_exit
```
**Symbols:**

```
ffffffff81593e10-ffffffff81593e2c: pci_ioremap_bar.cold (STB_LOCAL)
ffffffff8158d420-ffffffff8158d464: pci_ioremap_bar (STB_GLOBAL)
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
