# Function: <code>xhci_dbc_tty_register_driver</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xhci_dbc_tty_register_driver(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81774c70)
Location: drivers/usb/host/xhci-dbgtty.c:281
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
**Symbols:**

```
ffffffff81774c70-ffffffff81774d8d: xhci_dbc_tty_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xhci_dbc_tty_register_driver(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff817b5270)
Location: drivers/usb/host/xhci-dbgtty.c:284
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
**Symbols:**

```
ffffffff817b5270-ffffffff817b538d: xhci_dbc_tty_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xhci_dbc_tty_register_driver(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff817db7c0)
Location: drivers/usb/host/xhci-dbgtty.c:284
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
**Symbols:**

```
ffffffff817db7c0-ffffffff817db8dd: xhci_dbc_tty_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int xhci_dbc_tty_register_driver(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (0)
Location: drivers/usb/host/xhci-dbgtty.c:284
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
**Symbols:**

```
ffffffff8181c5e7-ffffffff8181c61d: xhci_dbc_tty_register_driver.cold (STB_LOCAL)
ffffffff8181c1d0-ffffffff8181c2bf: xhci_dbc_tty_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int xhci_dbc_tty_register_driver(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (0)
Location: drivers/usb/host/xhci-dbgtty.c:284
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
**Symbols:**

```
ffffffff8184d9a7-ffffffff8184d9dd: xhci_dbc_tty_register_driver.cold (STB_LOCAL)
ffffffff8184d590-ffffffff8184d67f: xhci_dbc_tty_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int xhci_dbc_tty_register_driver(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (0)
Location: drivers/usb/host/xhci-dbgtty.c:284
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
**Symbols:**

```
ffffffff81920579-ffffffff819205af: xhci_dbc_tty_register_driver.cold (STB_LOCAL)
ffffffff81920030-ffffffff8192011f: xhci_dbc_tty_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
int xhci_dbc_tty_register_driver(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffff800010a8d0e0)
Location: drivers/usb/host/xhci-dbgtty.c:284
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
**Symbols:**

```
ffff800010a8d0e0-ffff800010a8d1f8: xhci_dbc_tty_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xhci_dbc_tty_register_driver(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (c0b5f700)
Location: drivers/usb/host/xhci-dbgtty.c:284
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
**Symbols:**

```
c0b5f700-c0b5f808: xhci_dbc_tty_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xhci_dbc_tty_register_driver(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (c000000000b692c0)
Location: drivers/usb/host/xhci-dbgtty.c:284
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
**Symbols:**

```
c000000000b692c0-c000000000b69448: xhci_dbc_tty_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xhci_dbc_tty_register_driver(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffe0006a16da)
Location: drivers/usb/host/xhci-dbgtty.c:284
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
**Symbols:**

```
ffffffe0006a16da-ffffffe0006a180a: xhci_dbc_tty_register_driver (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int xhci_dbc_tty_register_driver(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (0)
Location: drivers/usb/host/xhci-dbgtty.c:284
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
**Symbols:**

```
ffffffff817caef7-ffffffff817caf2d: xhci_dbc_tty_register_driver.cold (STB_LOCAL)
ffffffff817caae0-ffffffff817cabcf: xhci_dbc_tty_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int xhci_dbc_tty_register_driver(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (0)
Location: drivers/usb/host/xhci-dbgtty.c:284
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
**Symbols:**

```
ffffffff81842827-ffffffff8184285d: xhci_dbc_tty_register_driver.cold (STB_LOCAL)
ffffffff81842410-ffffffff818424ff: xhci_dbc_tty_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int xhci_dbc_tty_register_driver(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (0)
Location: drivers/usb/host/xhci-dbgtty.c:284
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
**Symbols:**

```
ffffffff8185cd87-ffffffff8185cdbd: xhci_dbc_tty_register_driver.cold (STB_LOCAL)
ffffffff8185c970-ffffffff8185ca5f: xhci_dbc_tty_register_driver (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
