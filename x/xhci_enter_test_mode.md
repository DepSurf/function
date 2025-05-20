# Function: <code>xhci_enter_test_mode</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff81701793)
Location: drivers/usb/host/xhci-hub.c:615
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
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
In drivers/usb/host/xhci-hub.c (ffffffff8176e4b6)
Location: drivers/usb/host/xhci-hub.c:616
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
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
In drivers/usb/host/xhci-hub.c (ffffffff817aecfd)
Location: drivers/usb/host/xhci-hub.c:605
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
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
In drivers/usb/host/xhci-hub.c (ffffffff817d53f4)
Location: drivers/usb/host/xhci-hub.c:605
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff818157d4)
Location: drivers/usb/host/xhci-hub.c:609
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff81846a8e)
Location: drivers/usb/host/xhci-hub.c:618
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int xhci_enter_test_mode(struct xhci_hcd *xhci, u16 test_mode, u16 wIndex, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-hub.c (0)
Location: drivers/usb/host/xhci-hub.c:619
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff819180f0-ffffffff819182ec: xhci_enter_test_mode (STB_LOCAL)
ffffffff8191a950-ffffffff8191a972: xhci_enter_test_mode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int xhci_enter_test_mode(struct xhci_hcd *xhci, u16 test_mode, u16 wIndex, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-hub.c (0)
Location: drivers/usb/host/xhci-hub.c:619
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff8191ea10-ffffffff8191ec0c: xhci_enter_test_mode (STB_LOCAL)
ffffffff81c2255b-ffffffff81c2257d: xhci_enter_test_mode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int xhci_enter_test_mode(struct xhci_hcd *xhci, u16 test_mode, u16 wIndex, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-hub.c (0)
Location: drivers/usb/host/xhci-hub.c:705
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff81902120-ffffffff81902321: xhci_enter_test_mode (STB_LOCAL)
ffffffff81c14757-ffffffff81c14779: xhci_enter_test_mode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xhci_enter_test_mode(struct xhci_hcd *xhci, u16 test_mode, u16 wIndex, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-hub.c (0)
Location: drivers/usb/host/xhci-hub.c:706
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff819a1b00-ffffffff819a1d2b: xhci_enter_test_mode (STB_LOCAL)
ffffffff81d219c7-ffffffff81d219e5: xhci_enter_test_mode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xhci_enter_test_mode(struct xhci_hcd *xhci, u16 test_mode, u16 wIndex, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-hub.c (0)
Location: drivers/usb/host/xhci-hub.c:706
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff81aff890-ffffffff81affaf0: xhci_enter_test_mode (STB_LOCAL)
ffffffff81eed62a-ffffffff81eed647: xhci_enter_test_mode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xhci_enter_test_mode(struct xhci_hcd *xhci, u16 test_mode, u16 wIndex, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff81c8e5f0)
Location: drivers/usb/host/xhci-hub.c:720
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff81c8e5f0-ffffffff81c8e874: xhci_enter_test_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xhci_enter_test_mode(struct xhci_hcd *xhci, u16 test_mode, u16 wIndex, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff81cf4b60)
Location: drivers/usb/host/xhci-hub.c:725
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff81cf4b60-ffffffff81cf4dc2: xhci_enter_test_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xhci_enter_test_mode(struct xhci_hcd *xhci, u16 test_mode, u16 wIndex, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff81daa450)
Location: drivers/usb/host/xhci-hub.c:725
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff81daa450-ffffffff81daa6b2: xhci_enter_test_mode (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffff800010a857b8)
Location: drivers/usb/host/xhci-hub.c:618
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (c0b58488)
Location: drivers/usb/host/xhci-hub.c:618
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (c000000000b5ee20)
Location: drivers/usb/host/xhci-hub.c:618
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffe00069ae52)
Location: drivers/usb/host/xhci-hub.c:618
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff817fee3e)
Location: drivers/usb/host/xhci-hub.c:618
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
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
In drivers/usb/host/xhci-hub.c (ffffffff817c3fde)
Location: drivers/usb/host/xhci-hub.c:618
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff8183b90e)
Location: drivers/usb/host/xhci-hub.c:618
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff81855db7)
Location: drivers/usb/host/xhci-hub.c:618
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
</details>
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
