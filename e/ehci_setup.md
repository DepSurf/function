# Function: <code>ehci_setup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
int ehci_setup(struct usb_hcd *hcd);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff816377f0)
Location: drivers/usb/host/ehci-hcd.c:657
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-platform.c:ehci_platform_reset
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff81fb0db3)
Location: drivers/usb/early/ehci-dbgp.c:757
Inline: True
```
**Symbols:**

```
ffffffff816377f0-ffffffff8163806d: ehci_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int ehci_setup(struct usb_hcd *hcd);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81698530)
Location: drivers/usb/host/ehci-hcd.c:669
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-platform.c:ehci_platform_reset
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff81fdd8d1)
Location: drivers/usb/early/ehci-dbgp.c:757
Inline: True
```
**Symbols:**

```
ffffffff81698530-ffffffff81698d8b: ehci_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
int ehci_setup(struct usb_hcd *hcd);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff816c6a60)
Location: drivers/usb/host/ehci-hcd.c:669
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-platform.c:ehci_platform_reset
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff8201b4e8)
Location: drivers/usb/early/ehci-dbgp.c:756
Inline: True
```
**Symbols:**

```
ffffffff816c6a60-ffffffff816c72bb: ehci_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
int ehci_setup(struct usb_hcd *hcd);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff816db220)
Location: drivers/usb/host/ehci-hcd.c:669
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-platform.c:ehci_platform_reset
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff820fdd83)
Location: drivers/usb/early/ehci-dbgp.c:755
Inline: True
```
**Symbols:**

```
ffffffff816db220-ffffffff816dba69: ehci_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
int ehci_setup(struct usb_hcd *hcd);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81747950)
Location: drivers/usb/host/ehci-hcd.c:656
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-platform.c:ehci_platform_reset
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff82707672)
Location: drivers/usb/early/ehci-dbgp.c:756
Inline: True
```
**Symbols:**

```
ffffffff81747950-ffffffff8174819c: ehci_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int ehci_setup(struct usb_hcd *hcd);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci-hcd.c:656
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-platform.c:ehci_platform_reset
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff82731566)
Location: drivers/usb/early/ehci-dbgp.c:756
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
```
**Symbols:**

```
ffffffff8178ceb6-ffffffff8178cec2: ehci_setup.cold.87 (STB_LOCAL)
ffffffff81788150-ffffffff8178898d: ehci_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int ehci_setup(struct usb_hcd *hcd);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci-hcd.c:656
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-platform.c:ehci_platform_reset
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff828ea227)
Location: drivers/usb/early/ehci-dbgp.c:756
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
```
**Symbols:**

```
ffffffff817b36b6-ffffffff817b36c2: ehci_setup.cold.82 (STB_LOCAL)
ffffffff817b1330-ffffffff817b1ae4: ehci_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int ehci_setup(struct usb_hcd *hcd);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci-hcd.c:656
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-platform.c:ehci_platform_reset
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff82904c4c)
Location: drivers/usb/early/ehci-dbgp.c:756
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
```
**Symbols:**

```
ffffffff817f2cdf-ffffffff817f2ceb: ehci_setup.cold (STB_LOCAL)
ffffffff817f1fc0-ffffffff817f258b: ehci_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int ehci_setup(struct usb_hcd *hcd);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci-hcd.c:656
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-platform.c:ehci_platform_reset
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff8290e687)
Location: drivers/usb/early/ehci-dbgp.c:756
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
```
**Symbols:**

```
ffffffff81823aff-ffffffff81823b0b: ehci_setup.cold (STB_LOCAL)
ffffffff81822eb0-ffffffff8182347b: ehci_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision ⚠️</summary>

```c
int ehci_setup(struct usb_hcd *hcd);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818f1b40)
Location: drivers/usb/host/ehci-hcd.c:657
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-platform.c:ehci_platform_reset
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff82d22526)
Location: drivers/usb/early/ehci-dbgp.c:756
Inline: False
Direct callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
```
**Symbols:**

```
ffffffff82d22526-ffffffff82d22646: ehci_setup (STB_LOCAL)
ffffffff818f1b40-ffffffff818f1bdf: ehci_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
int ehci_setup(struct usb_hcd *hcd);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818faa60)
Location: drivers/usb/host/ehci-hcd.c:669
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-platform.c:ehci_platform_reset
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff8301031f)
Location: drivers/usb/early/ehci-dbgp.c:751
Inline: False
Direct callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
```
**Symbols:**

```
ffffffff8301031f-ffffffff8301043f: ehci_setup (STB_LOCAL)
ffffffff818faa60-ffffffff818faaff: ehci_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
int ehci_setup(struct usb_hcd *hcd);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818df340)
Location: drivers/usb/host/ehci-hcd.c:669
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-platform.c:ehci_platform_reset
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff8321b4e7)
Location: drivers/usb/early/ehci-dbgp.c:751
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
```
**Symbols:**

```
ffffffff818df340-ffffffff818df3e2: ehci_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
int ehci_setup(struct usb_hcd *hcd);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff8197ad10)
Location: drivers/usb/host/ehci-hcd.c:679
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-platform.c:ehci_platform_reset
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff83304e61)
Location: drivers/usb/early/ehci-dbgp.c:751
Inline: False
Direct callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
```
**Symbols:**

```
ffffffff83304e61-ffffffff83304fd3: ehci_setup (STB_LOCAL)
ffffffff8197ad10-ffffffff8197adb2: ehci_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
int ehci_setup(struct usb_hcd *hcd);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81ad17f0)
Location: drivers/usb/host/ehci-hcd.c:679
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-platform.c:ehci_platform_reset
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff834bdf61)
Location: drivers/usb/early/ehci-dbgp.c:751
Inline: False
Direct callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
```
**Symbols:**

```
ffffffff834bdf61-ffffffff834be0d4: ehci_setup (STB_LOCAL)
ffffffff81ad17f0-ffffffff81ad189c: ehci_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
int ehci_setup(struct usb_hcd *hcd);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81c5c280)
Location: drivers/usb/host/ehci-hcd.c:679
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-platform.c:ehci_platform_reset
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff83efbdc0)
Location: drivers/usb/early/ehci-dbgp.c:751
Inline: False
Direct callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
```
**Symbols:**

```
ffffffff83efbdc0-ffffffff83efbf82: ehci_setup (STB_LOCAL)
ffffffff81c5c280-ffffffff81c5c32c: ehci_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
int ehci_setup(struct usb_hcd *hcd);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81cc3900)
Location: drivers/usb/host/ehci-hcd.c:679
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-platform.c:ehci_platform_reset
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff83721bd0)
Location: drivers/usb/early/ehci-dbgp.c:751
Inline: False
Direct callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
```
**Symbols:**

```
ffffffff83721bd0-ffffffff83721d92: ehci_setup (STB_LOCAL)
ffffffff81cc3900-ffffffff81cc39ac: ehci_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
int ehci_setup(struct usb_hcd *hcd);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81d78800)
Location: drivers/usb/host/ehci-hcd.c:679
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-platform.c:ehci_platform_reset
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff83955a00)
Location: drivers/usb/early/ehci-dbgp.c:751
Inline: False
Direct callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
```
**Symbols:**

```
ffffffff83955a00-ffffffff83955bc2: ehci_setup (STB_LOCAL)
ffffffff81d78800-ffffffff81d788ac: ehci_setup (STB_GLOBAL)
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
int ehci_setup(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffff800010a59128)
Location: drivers/usb/host/ehci-hcd.c:656
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_reset
```
**Symbols:**

```
ffff800010a59128-ffff800010a596fc: ehci_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ehci_setup(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (c0b2ed1c)
Location: drivers/usb/host/ehci-hcd.c:656
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_reset
```
**Symbols:**

```
c0b2ed1c-c0b2f2cc: ehci_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ehci_setup(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (c000000000b28fe0)
Location: drivers/usb/host/ehci-hcd.c:656
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
**Symbols:**

```
c000000000b28fe0-c000000000b2985c: ehci_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ehci_setup(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffe000676796)
Location: drivers/usb/host/ehci-hcd.c:656
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
**Symbols:**

```
ffffffe000676796-ffffffe000676d1a: ehci_setup (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int ehci_setup(struct usb_hcd *hcd);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci-hcd.c:656
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-platform.c:ehci_platform_reset
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff828f57e1)
Location: drivers/usb/early/ehci-dbgp.c:756
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
```
**Symbols:**

```
ffffffff817dbedf-ffffffff817dbeeb: ehci_setup.cold (STB_LOCAL)
ffffffff817db290-ffffffff817db85b: ehci_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/early/ehci-dbgp.c (ffffffff828ed0f1)
Location: drivers/usb/early/ehci-dbgp.c:756
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int ehci_setup(struct usb_hcd *hcd);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci-hcd.c:656
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-platform.c:ehci_platform_reset
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff82909a82)
Location: drivers/usb/early/ehci-dbgp.c:756
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
```
**Symbols:**

```
ffffffff8181897f-ffffffff8181898b: ehci_setup.cold (STB_LOCAL)
ffffffff81817d30-ffffffff818182fb: ehci_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int ehci_setup(struct usb_hcd *hcd);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci-hcd.c:656
Inline: False
Direct callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-platform.c:ehci_platform_reset
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff8290f6e9)
Location: drivers/usb/early/ehci-dbgp.c:756
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
```
**Symbols:**

```
ffffffff8183296f-ffffffff8183297b: ehci_setup.cold (STB_LOCAL)
ffffffff81831d20-ffffffff818322eb: ehci_setup (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
