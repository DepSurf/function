# Function: <code>xhci_dbc_tty_register_device</code>

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
int xhci_dbc_tty_register_device(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81774dc0)
Location: drivers/usb/host/xhci-dbgtty.c:436
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
```
**Symbols:**

```
ffffffff81774dc0-ffffffff81774fb1: xhci_dbc_tty_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xhci_dbc_tty_register_device(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff817b53d0)
Location: drivers/usb/host/xhci-dbgtty.c:443
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
```
**Symbols:**

```
ffffffff817b53d0-ffffffff817b55a7: xhci_dbc_tty_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xhci_dbc_tty_register_device(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff817db920)
Location: drivers/usb/host/xhci-dbgtty.c:443
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
```
**Symbols:**

```
ffffffff817db920-ffffffff817dbaf7: xhci_dbc_tty_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xhci_dbc_tty_register_device(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff8181c300)
Location: drivers/usb/host/xhci-dbgtty.c:443
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
```
**Symbols:**

```
ffffffff8181c300-ffffffff8181c4e5: xhci_dbc_tty_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xhci_dbc_tty_register_device(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff8184d6c0)
Location: drivers/usb/host/xhci-dbgtty.c:443
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
```
**Symbols:**

```
ffffffff8184d6c0-ffffffff8184d8a5: xhci_dbc_tty_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xhci_dbc_tty_register_device(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81920160)
Location: drivers/usb/host/xhci-dbgtty.c:443
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
```
**Symbols:**

```
ffffffff81920160-ffffffff81920345: xhci_dbc_tty_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xhci_dbc_tty_register_device(struct xhci_dbc *dbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81926ee0)
Location: drivers/usb/host/xhci-dbgtty.c:401
Inline: False
```
**Symbols:**

```
ffffffff81926ee0-ffffffff81927082: xhci_dbc_tty_register_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xhci_dbc_tty_register_device(struct xhci_dbc *dbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff8190a4f0)
Location: drivers/usb/host/xhci-dbgtty.c:401
Inline: False
```
**Symbols:**

```
ffffffff8190a4f0-ffffffff8190a690: xhci_dbc_tty_register_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xhci_dbc_tty_register_device(struct xhci_dbc *dbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (0)
Location: drivers/usb/host/xhci-dbgtty.c:401
Inline: False
```
**Symbols:**

```
ffffffff819ab560-ffffffff819ab7af: xhci_dbc_tty_register_device (STB_LOCAL)
ffffffff81d21ff2-ffffffff81d22007: xhci_dbc_tty_register_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xhci_dbc_tty_register_device(struct xhci_dbc *dbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (0)
Location: drivers/usb/host/xhci-dbgtty.c:408
Inline: False
```
**Symbols:**

```
ffffffff81b098a0-ffffffff81b09b65: xhci_dbc_tty_register_device (STB_LOCAL)
ffffffff81eedbc7-ffffffff81eedbdc: xhci_dbc_tty_register_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int xhci_dbc_tty_register_device(struct xhci_dbc *dbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (0)
Location: drivers/usb/host/xhci-dbgtty.c:408
Inline: False
```
**Symbols:**

```
ffffffff81c99680-ffffffff81c9993d: xhci_dbc_tty_register_device (STB_LOCAL)
ffffffff820a5df8-ffffffff820a5e0c: xhci_dbc_tty_register_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int xhci_dbc_tty_register_device(struct xhci_dbc *dbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (0)
Location: drivers/usb/host/xhci-dbgtty.c:408
Inline: False
```
**Symbols:**

```
ffffffff81d00a30-ffffffff81d00ced: xhci_dbc_tty_register_device (STB_LOCAL)
ffffffff8212719e-ffffffff821271b2: xhci_dbc_tty_register_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int xhci_dbc_tty_register_device(struct xhci_dbc *dbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (0)
Location: drivers/usb/host/xhci-dbgtty.c:407
Inline: False
```
**Symbols:**

```
ffffffff81db6530-ffffffff81db67ed: xhci_dbc_tty_register_device (STB_LOCAL)
ffffffff82208af5-ffffffff82208b09: xhci_dbc_tty_register_device.cold (STB_LOCAL)
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
int xhci_dbc_tty_register_device(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffff800010a8d238)
Location: drivers/usb/host/xhci-dbgtty.c:443
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
```
**Symbols:**

```
ffff800010a8d238-ffff800010a8d3e8: xhci_dbc_tty_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xhci_dbc_tty_register_device(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (c0b5f848)
Location: drivers/usb/host/xhci-dbgtty.c:443
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
```
**Symbols:**

```
c0b5f848-c0b5f9f8: xhci_dbc_tty_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xhci_dbc_tty_register_device(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (c000000000b694b0)
Location: drivers/usb/host/xhci-dbgtty.c:443
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
```
**Symbols:**

```
c000000000b694b0-c000000000b696d8: xhci_dbc_tty_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xhci_dbc_tty_register_device(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffe0006a184e)
Location: drivers/usb/host/xhci-dbgtty.c:443
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
```
**Symbols:**

```
ffffffe0006a184e-ffffffe0006a19ea: xhci_dbc_tty_register_device (STB_GLOBAL)
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
<summary>In <code>azure</code>: ✅</summary>

```c
int xhci_dbc_tty_register_device(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff817cac10)
Location: drivers/usb/host/xhci-dbgtty.c:443
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
```
**Symbols:**

```
ffffffff817cac10-ffffffff817cadf5: xhci_dbc_tty_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int xhci_dbc_tty_register_device(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81842540)
Location: drivers/usb/host/xhci-dbgtty.c:443
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
```
**Symbols:**

```
ffffffff81842540-ffffffff81842725: xhci_dbc_tty_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xhci_dbc_tty_register_device(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff8185caa0)
Location: drivers/usb/host/xhci-dbgtty.c:443
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
```
**Symbols:**

```
ffffffff8185caa0-ffffffff8185cc85: xhci_dbc_tty_register_device (STB_GLOBAL)
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
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct xhci_dbc *dbc</code>
</li>
<li>
<b>Param removed. </b>
<code>struct xhci_hcd *xhci</code>
</li>
</ul>
</details>
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
