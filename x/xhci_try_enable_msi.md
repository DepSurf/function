# Function: <code>xhci_try_enable_msi</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8164cf06)
Location: drivers/usb/host/xhci.c:367
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816ad836)
Location: drivers/usb/host/xhci.c:369
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816dbb16)
Location: drivers/usb/host/xhci.c:373
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816f0271)
Location: drivers/usb/host/xhci.c:337
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8175c431)
Location: drivers/usb/host/xhci.c:327
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8179ce14)
Location: drivers/usb/host/xhci.c:404
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817c31f4)
Location: drivers/usb/host/xhci.c:405
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int xhci_try_enable_msi(struct usb_hcd *hcd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:403
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_run
```
**Symbols:**

```
ffffffff81802430-ffffffff8180273b: xhci_try_enable_msi (STB_LOCAL)
ffffffff81807b7c-ffffffff81807bc4: xhci_try_enable_msi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int xhci_try_enable_msi(struct usb_hcd *hcd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:403
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_run
```
**Symbols:**

```
ffffffff818312a0-ffffffff818315a3: xhci_try_enable_msi (STB_LOCAL)
ffffffff8183885c-ffffffff818388a7: xhci_try_enable_msi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int xhci_try_enable_msi(struct usb_hcd *hcd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:403
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_run
```
**Symbols:**

```
ffffffff81903760-ffffffff81903930: xhci_try_enable_msi (STB_LOCAL)
ffffffff8190afcc-ffffffff8190b015: xhci_try_enable_msi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int xhci_try_enable_msi(struct usb_hcd *hcd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:403
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_run
```
**Symbols:**

```
ffffffff8190bcd0-ffffffff8190bea0: xhci_try_enable_msi (STB_LOCAL)
ffffffff81c209f9-ffffffff81c20a42: xhci_try_enable_msi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int xhci_try_enable_msi(struct usb_hcd *hcd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:406
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_run
```
**Symbols:**

```
ffffffff818ef280-ffffffff818ef58c: xhci_try_enable_msi (STB_LOCAL)
ffffffff81c12a7d-ffffffff81c12ac8: xhci_try_enable_msi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xhci_try_enable_msi(struct usb_hcd *hcd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:406
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_run
```
**Symbols:**

```
ffffffff8198be40-ffffffff8198c14c: xhci_try_enable_msi (STB_LOCAL)
ffffffff81d1f6fc-ffffffff81d1f747: xhci_try_enable_msi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xhci_try_enable_msi(struct usb_hcd *hcd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:407
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_run
```
**Symbols:**

```
ffffffff81ae8030-ffffffff81ae8353: xhci_try_enable_msi (STB_LOCAL)
ffffffff81eeb1d4-ffffffff81eeb237: xhci_try_enable_msi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xhci_try_enable_msi(struct usb_hcd *hcd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81c73ff0)
Location: drivers/usb/host/xhci.c:409
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_run
```
**Symbols:**

```
ffffffff81c73ff0-ffffffff81c74369: xhci_try_enable_msi (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int xhci_try_enable_msi(struct usb_hcd *hcd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffff800010a6d7d0)
Location: drivers/usb/host/xhci.c:403
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_run
```
**Symbols:**

```
ffff800010a6d7d0-ffff800010a6db04: xhci_try_enable_msi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xhci_try_enable_msi(struct usb_hcd *hcd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c0b41e3c)
Location: drivers/usb/host/xhci.c:403
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_run
```
**Symbols:**

```
c0b41e3c-c0b42178: xhci_try_enable_msi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xhci_try_enable_msi(struct usb_hcd *hcd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c000000000b41840)
Location: drivers/usb/host/xhci.c:403
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_run
```
**Symbols:**

```
c000000000b41840-c000000000b41c80: xhci_try_enable_msi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xhci_try_enable_msi(struct usb_hcd *hcd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffe000686c54)
Location: drivers/usb/host/xhci.c:403
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_run
```
**Symbols:**

```
ffffffe000686c54-ffffffe000686f24: xhci_try_enable_msi (STB_LOCAL)
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
int xhci_try_enable_msi(struct usb_hcd *hcd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:403
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_run
```
**Symbols:**

```
ffffffff817e9680-ffffffff817e9983: xhci_try_enable_msi (STB_LOCAL)
ffffffff817f0c0c-ffffffff817f0c57: xhci_try_enable_msi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int xhci_try_enable_msi(struct usb_hcd *hcd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:403
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_run
```
**Symbols:**

```
ffffffff817ae790-ffffffff817aea93: xhci_try_enable_msi (STB_LOCAL)
ffffffff817b5da2-ffffffff817b5ded: xhci_try_enable_msi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int xhci_try_enable_msi(struct usb_hcd *hcd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:403
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_run
```
**Symbols:**

```
ffffffff81826120-ffffffff81826423: xhci_try_enable_msi (STB_LOCAL)
ffffffff8182d6dc-ffffffff8182d727: xhci_try_enable_msi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int xhci_try_enable_msi(struct usb_hcd *hcd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:403
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_run
```
**Symbols:**

```
ffffffff81840000-ffffffff81840303: xhci_try_enable_msi (STB_LOCAL)
ffffffff818477c5-ffffffff81847810: xhci_try_enable_msi.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
