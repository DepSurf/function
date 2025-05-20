# Function: <code>xhci_dbc_do_handle_events</code>

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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81773591)
Location: drivers/usb/host/xhci-dbgcap.c:641
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
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
In drivers/usb/host/xhci-dbgcap.c (ffffffff817b3bb4)
Location: drivers/usb/host/xhci-dbgcap.c:649
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
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
In drivers/usb/host/xhci-dbgcap.c (ffffffff817da0f4)
Location: drivers/usb/host/xhci-dbgcap.c:650
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
enum evtreturn xhci_dbc_do_handle_events(struct xhci_dbc *dbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: drivers/usb/host/xhci-dbgcap.c:648
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
```
**Symbols:**

```
ffffffff8181a9e0-ffffffff8181ad58: xhci_dbc_do_handle_events (STB_LOCAL)
ffffffff8181b586-ffffffff8181b75c: xhci_dbc_do_handle_events.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
enum evtreturn xhci_dbc_do_handle_events(struct xhci_dbc *dbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: drivers/usb/host/xhci-dbgcap.c:647
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
```
**Symbols:**

```
ffffffff8184c060-ffffffff8184c3d8: xhci_dbc_do_handle_events (STB_LOCAL)
ffffffff8184c9c7-ffffffff8184cb9d: xhci_dbc_do_handle_events.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
enum evtreturn xhci_dbc_do_handle_events(struct xhci_dbc *dbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: drivers/usb/host/xhci-dbgcap.c:647
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
```
**Symbols:**

```
ffffffff8191eda0-ffffffff8191ef6e: xhci_dbc_do_handle_events (STB_LOCAL)
ffffffff8191f510-ffffffff8191f656: xhci_dbc_do_handle_events.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
enum evtreturn xhci_dbc_do_handle_events(struct xhci_dbc *dbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: drivers/usb/host/xhci-dbgcap.c:750
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
```
**Symbols:**

```
ffffffff819264d0-ffffffff819266ec: xhci_dbc_do_handle_events (STB_LOCAL)
ffffffff81c22740-ffffffff81c2288f: xhci_dbc_do_handle_events.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
enum evtreturn xhci_dbc_do_handle_events(struct xhci_dbc *dbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: drivers/usb/host/xhci-dbgcap.c:750
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
```
**Symbols:**

```
ffffffff81909ba0-ffffffff81909dc4: xhci_dbc_do_handle_events (STB_LOCAL)
ffffffff81c1493f-ffffffff81c14a8e: xhci_dbc_do_handle_events.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
enum evtreturn xhci_dbc_do_handle_events(struct xhci_dbc *dbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: drivers/usb/host/xhci-dbgcap.c:750
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
```
**Symbols:**

```
ffffffff819aa410-ffffffff819aa631: xhci_dbc_do_handle_events (STB_LOCAL)
ffffffff81d21e31-ffffffff81d21f80: xhci_dbc_do_handle_events.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
enum evtreturn xhci_dbc_do_handle_events(struct xhci_dbc *dbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: drivers/usb/host/xhci-dbgcap.c:750
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
```
**Symbols:**

```
ffffffff81b080c0-ffffffff81b0831a: xhci_dbc_do_handle_events (STB_LOCAL)
ffffffff81eed9ad-ffffffff81eedaf8: xhci_dbc_do_handle_events.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum evtreturn xhci_dbc_do_handle_events(struct xhci_dbc *dbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81c97ef0)
Location: drivers/usb/host/xhci-dbgcap.c:750
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
```
**Symbols:**

```
ffffffff81c97ef0-ffffffff81c9824e: xhci_dbc_do_handle_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum evtreturn xhci_dbc_do_handle_events(struct xhci_dbc *dbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81cff220)
Location: drivers/usb/host/xhci-dbgcap.c:750
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
```
**Symbols:**

```
ffffffff81cff220-ffffffff81cff5a6: xhci_dbc_do_handle_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
enum evtreturn xhci_dbc_do_handle_events(struct xhci_dbc *dbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81db4320)
Location: drivers/usb/host/xhci-dbgcap.c:761
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
```
**Symbols:**

```
ffffffff81db4320-ffffffff81db46a6: xhci_dbc_do_handle_events (STB_LOCAL)
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
enum evtreturn xhci_dbc_do_handle_events(struct xhci_dbc *dbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffff800010a8b018)
Location: drivers/usb/host/xhci-dbgcap.c:647
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
```
**Symbols:**

```
ffff800010a8b018-ffff800010a8b5f8: xhci_dbc_do_handle_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
enum evtreturn xhci_dbc_do_handle_events(struct xhci_dbc *dbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (c0b5e224)
Location: drivers/usb/host/xhci-dbgcap.c:647
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
```
**Symbols:**

```
c0b5e224-c0b5e7f4: xhci_dbc_do_handle_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
enum evtreturn xhci_dbc_do_handle_events(struct xhci_dbc *dbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (c000000000b66b20)
Location: drivers/usb/host/xhci-dbgcap.c:647
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
```
**Symbols:**

```
c000000000b66b20-c000000000b674e8: xhci_dbc_do_handle_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
enum evtreturn xhci_dbc_do_handle_events(struct xhci_dbc *dbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffe00069f7d4)
Location: drivers/usb/host/xhci-dbgcap.c:647
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
```
**Symbols:**

```
ffffffe00069f7d4-ffffffe00069fdf2: xhci_dbc_do_handle_events (STB_LOCAL)
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
enum evtreturn xhci_dbc_do_handle_events(struct xhci_dbc *dbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: drivers/usb/host/xhci-dbgcap.c:647
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
```
**Symbols:**

```
ffffffff817c95b0-ffffffff817c9928: xhci_dbc_do_handle_events (STB_LOCAL)
ffffffff817c9f17-ffffffff817ca0ed: xhci_dbc_do_handle_events.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
enum evtreturn xhci_dbc_do_handle_events(struct xhci_dbc *dbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: drivers/usb/host/xhci-dbgcap.c:647
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
```
**Symbols:**

```
ffffffff81840ee0-ffffffff81841258: xhci_dbc_do_handle_events (STB_LOCAL)
ffffffff81841847-ffffffff81841a1d: xhci_dbc_do_handle_events.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
enum evtreturn xhci_dbc_do_handle_events(struct xhci_dbc *dbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: drivers/usb/host/xhci-dbgcap.c:647
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
```
**Symbols:**

```
ffffffff8185b3e0-ffffffff8185b78a: xhci_dbc_do_handle_events (STB_LOCAL)
ffffffff8185bda7-ffffffff8185bf7d: xhci_dbc_do_handle_events.cold (STB_LOCAL)
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
