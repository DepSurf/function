# Function: <code>xhci_decode_usbsts</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const char *xhci_decode_usbsts(u32 usbsts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81910710)
Location: drivers/usb/host/xhci.h:2596
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
```
**Symbols:**

```
ffffffff81910710-ffffffff819108c9: xhci_decode_usbsts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const char *xhci_decode_usbsts(u32 usbsts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81917f90)
Location: drivers/usb/host/xhci.h:2611
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
```
**Symbols:**

```
ffffffff81917f90-ffffffff81918149: xhci_decode_usbsts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const char *xhci_decode_usbsts(u32 usbsts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff818fb3a0)
Location: drivers/usb/host/xhci.h:2617
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
```
**Symbols:**

```
ffffffff818fb3a0-ffffffff818fb559: xhci_decode_usbsts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const char *xhci_decode_usbsts(char *str, u32 usbsts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff8199a290)
Location: drivers/usb/host/xhci.h:2623
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
```
**Symbols:**

```
ffffffff8199a290-ffffffff8199a3e7: xhci_decode_usbsts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const char *xhci_decode_usbsts(char *str, u32 usbsts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81af72f0)
Location: drivers/usb/host/xhci.h:2652
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
**Symbols:**

```
ffffffff81af72f0-ffffffff81af7481: xhci_decode_usbsts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char *xhci_decode_usbsts(char *str, u32 usbsts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81c84e50)
Location: drivers/usb/host/xhci.h:2653
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
**Symbols:**

```
ffffffff81c84e50-ffffffff81c84fe1: xhci_decode_usbsts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char *xhci_decode_usbsts(char *str, u32 usbsts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81cebb10)
Location: drivers/usb/host/xhci.h:2663
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
**Symbols:**

```
ffffffff81cebb10-ffffffff81cebca1: xhci_decode_usbsts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const char *xhci_decode_usbsts(char *str, u32 usbsts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81da1130)
Location: drivers/usb/host/xhci.h:2640
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
**Symbols:**

```
ffffffff81da1130-ffffffff81da12c1: xhci_decode_usbsts (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<b>Param added. </b>
<code>char *str</code>
</li>
<li>
<b>Param reordered. </b>
<code>usbsts</code> ➡️ <code>str, usbsts</code>
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
