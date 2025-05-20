# Function: <code>handshake</code>

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
In drivers/usb/host/pci-quirks.c (ffffffff81630dbb)
Location: drivers/usb/host/pci-quirks.c:833
Inline: True
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
In drivers/usb/host/pci-quirks.c (ffffffff816918f8)
Location: drivers/usb/host/pci-quirks.c:833
Inline: True
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
In drivers/usb/host/pci-quirks.c (ffffffff816bf9a8)
Location: drivers/usb/host/pci-quirks.c:832
Inline: True
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
In drivers/usb/host/pci-quirks.c (ffffffff816d432b)
Location: drivers/usb/host/pci-quirks.c:894
Inline: True
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
In drivers/usb/host/pci-quirks.c (ffffffff81740a1b)
Location: drivers/usb/host/pci-quirks.c:895
Inline: True
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
In drivers/usb/host/pci-quirks.c (ffffffff8178158d)
Location: drivers/usb/host/pci-quirks.c:1004
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff817a7db1)
Location: drivers/usb/host/pci-quirks.c:998
Inline: True
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff828eab03)
Location: drivers/usb/early/xhci-dbc.c:134
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff817e6f66)
Location: drivers/usb/host/pci-quirks.c:1007
Inline: True
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff82905542)
Location: drivers/usb/early/xhci-dbc.c:134
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff81817e26)
Location: drivers/usb/host/pci-quirks.c:1007
Inline: True
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff8290ef7d)
Location: drivers/usb/early/xhci-dbc.c:134
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int handshake(void *ptr, u32 mask, u32 done, int wait_usec, int delay_usec);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff818e8c3b)
Location: drivers/usb/host/pci-quirks.c:1010
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff81923abf)
Location: drivers/usb/early/xhci-dbc.c:133
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:xdbc_early_setup
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_bios_handoff
```
**Symbols:**

```
ffffffff81923020-ffffffff8192308a: handshake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline ⚠️</summary>

```c
int handshake(void *ptr, u32 mask, u32 done, int wait_usec, int delay_usec);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff818f1f18)
Location: drivers/usb/host/pci-quirks.c:1011
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff8192b233)
Location: drivers/usb/early/xhci-dbc.c:135
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_early_setup
  - drivers/usb/early/xhci-dbc.c:xdbc_bios_handoff
```
**Symbols:**

```
ffffffff8192a740-ffffffff8192a7b7: handshake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff818d5708)
Location: drivers/usb/host/pci-quirks.c:1011
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff8190e759)
Location: drivers/usb/early/xhci-dbc.c:135
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff81970373)
Location: drivers/usb/host/pci-quirks.c:1011
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff819af515)
Location: drivers/usb/early/xhci-dbc.c:134
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff81aca375)
Location: drivers/usb/host/pci-quirks.c:1011
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff81b0dca6)
Location: drivers/usb/early/xhci-dbc.c:134
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff81c54915)
Location: drivers/usb/host/pci-quirks.c:1011
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff81c9dd66)
Location: drivers/usb/early/xhci-dbc.c:134
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff81cbbe67)
Location: drivers/usb/host/pci-quirks.c:1009
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff81d050d6)
Location: drivers/usb/early/xhci-dbc.c:134
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff81d70bd7)
Location: drivers/usb/host/pci-quirks.c:1021
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff81dbac96)
Location: drivers/usb/early/xhci-dbc.c:134
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
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
In drivers/usb/host/pci-quirks.c (ffff800010a50e9c)
Location: drivers/usb/host/pci-quirks.c:1007
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
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
In drivers/usb/host/pci-quirks.c (c0b2331c)
Location: drivers/usb/host/pci-quirks.c:1007
Inline: True
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
In drivers/usb/host/pci-quirks.c (c000000000b1a000)
Location: drivers/usb/host/pci-quirks.c:1007
Inline: True
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
In drivers/usb/host/pci-quirks.c (ffffffe00066d94e)
Location: drivers/usb/host/pci-quirks.c:1007
Inline: True
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
In drivers/usb/host/pci-quirks.c (ffffffff817d0206)
Location: drivers/usb/host/pci-quirks.c:1007
Inline: True
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
In drivers/usb/host/pci-quirks.c (ffffffff817ae136)
Location: drivers/usb/host/pci-quirks.c:1007
Inline: True
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
In drivers/usb/host/pci-quirks.c (ffffffff8180cca6)
Location: drivers/usb/host/pci-quirks.c:1007
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff81826db6)
Location: drivers/usb/host/pci-quirks.c:1007
Inline: True
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff8290ffdf)
Location: drivers/usb/early/xhci-dbc.c:134
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
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
</ul>
