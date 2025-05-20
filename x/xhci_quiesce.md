# Function: <code>xhci_quiesce</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void xhci_quiesce(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8164cdb0)
Location: drivers/usb/host/xhci.c:83
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
**Symbols:**

```
ffffffff8164cdb0-ffffffff8164cdde: xhci_quiesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void xhci_quiesce(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816ad6e0)
Location: drivers/usb/host/xhci.c:84
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
```
**Symbols:**

```
ffffffff816ad6e0-ffffffff816ad708: xhci_quiesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void xhci_quiesce(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816dba14)
Location: drivers/usb/host/xhci.c:84
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_halt
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
```
**Symbols:**

```
ffffffff816db9c0-ffffffff816db9e8: xhci_quiesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void xhci_quiesce(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816f00c4)
Location: drivers/usb/host/xhci.c:84
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_halt
```
**Symbols:**

```
ffffffff816f0070-ffffffff816f0098: xhci_quiesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void xhci_quiesce(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8175c284)
Location: drivers/usb/host/xhci.c:74
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_halt
```
**Symbols:**

```
ffffffff8175c230-ffffffff8175c258: xhci_quiesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void xhci_quiesce(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8179cc58)
Location: drivers/usb/host/xhci.c:89
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_halt
```
**Symbols:**

```
ffffffff8179cc00-ffffffff8179cc28: xhci_quiesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void xhci_quiesce(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817c3038)
Location: drivers/usb/host/xhci.c:89
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_halt
```
**Symbols:**

```
ffffffff817c2fe0-ffffffff817c3008: xhci_quiesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void xhci_quiesce(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81802d34)
Location: drivers/usb/host/xhci.c:87
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_halt
```
**Symbols:**

```
ffffffff81802ce0-ffffffff81802d08: xhci_quiesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void xhci_quiesce(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81833c34)
Location: drivers/usb/host/xhci.c:87
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_halt
```
**Symbols:**

```
ffffffff81833be0-ffffffff81833c08: xhci_quiesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void xhci_quiesce(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81906b04)
Location: drivers/usb/host/xhci.c:87
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_halt
```
**Symbols:**

```
ffffffff81906ab0-ffffffff81906ad8: xhci_quiesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void xhci_quiesce(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8190f2a4)
Location: drivers/usb/host/xhci.c:87
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_halt
```
**Symbols:**

```
ffffffff8190f250-ffffffff8190f278: xhci_quiesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void xhci_quiesce(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff818f2874)
Location: drivers/usb/host/xhci.c:86
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_halt
```
**Symbols:**

```
ffffffff818f2820-ffffffff818f284b: xhci_quiesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void xhci_quiesce(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8198fae4)
Location: drivers/usb/host/xhci.c:86
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_halt
```
**Symbols:**

```
ffffffff8198fa90-ffffffff8198fabb: xhci_quiesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void xhci_quiesce(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81aec044)
Location: drivers/usb/host/xhci.c:86
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_halt
```
**Symbols:**

```
ffffffff81aebfe0-ffffffff81aec015: xhci_quiesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void xhci_quiesce(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81c787e4)
Location: drivers/usb/host/xhci.c:86
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_halt
```
**Symbols:**

```
ffffffff81c78770-ffffffff81c787a5: xhci_quiesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void xhci_quiesce(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81cdf864)
Location: drivers/usb/host/xhci.c:87
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_halt
```
**Symbols:**

```
ffffffff81cdf7f0-ffffffff81cdf825: xhci_quiesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void xhci_quiesce(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81d94924)
Location: drivers/usb/host/xhci.c:110
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_halt
```
**Symbols:**

```
ffffffff81d948b0-ffffffff81d948e5: xhci_quiesce (STB_GLOBAL)
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
void xhci_quiesce(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffff800010a70fc8)
Location: drivers/usb/host/xhci.c:87
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_halt
```
**Symbols:**

```
ffff800010a70fc8-ffff800010a71038: xhci_quiesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void xhci_quiesce(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c0b44dfc)
Location: drivers/usb/host/xhci.c:87
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_halt
```
**Symbols:**

```
c0b44dfc-c0b44e50: xhci_quiesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void xhci_quiesce(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c000000000b45bf0)
Location: drivers/usb/host/xhci.c:87
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_halt
```
**Symbols:**

```
c000000000b45bf0-c000000000b45d40: xhci_quiesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void xhci_quiesce(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffe000689648)
Location: drivers/usb/host/xhci.c:87
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_halt
```
**Symbols:**

```
ffffffe000689648-ffffffe0006896b0: xhci_quiesce (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void xhci_quiesce(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817ec004)
Location: drivers/usb/host/xhci.c:87
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_halt
```
**Symbols:**

```
ffffffff817ebfb0-ffffffff817ebfd8: xhci_quiesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void xhci_quiesce(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817b1114)
Location: drivers/usb/host/xhci.c:87
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_halt
```
**Symbols:**

```
ffffffff817b10c0-ffffffff817b10e8: xhci_quiesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void xhci_quiesce(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81828ab4)
Location: drivers/usb/host/xhci.c:87
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_halt
```
**Symbols:**

```
ffffffff81828a60-ffffffff81828a88: xhci_quiesce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void xhci_quiesce(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81842a74)
Location: drivers/usb/host/xhci.c:87
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_halt
```
**Symbols:**

```
ffffffff81842a20-ffffffff81842a48: xhci_quiesce (STB_GLOBAL)
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
