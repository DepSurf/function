# Function: <code>xhci_abort_cmd_ring</code>

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
In drivers/usb/host/xhci-ring.c (ffffffff81658260)
Location: drivers/usb/host/xhci-ring.c:283
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
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
In drivers/usb/host/xhci-ring.c (ffffffff816b8c68)
Location: drivers/usb/host/xhci-ring.c:263
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
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
In drivers/usb/host/xhci-ring.c (ffffffff816e6e02)
Location: drivers/usb/host/xhci-ring.c:342
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
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
In drivers/usb/host/xhci-ring.c (ffffffff816faf4c)
Location: drivers/usb/host/xhci-ring.c:351
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
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
In drivers/usb/host/xhci-ring.c (ffffffff81767a89)
Location: drivers/usb/host/xhci-ring.c:340
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
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
In drivers/usb/host/xhci-ring.c (ffffffff817a8dd3)
Location: drivers/usb/host/xhci-ring.c:340
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
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
In drivers/usb/host/xhci-ring.c (ffffffff817ced43)
Location: drivers/usb/host/xhci-ring.c:340
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
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
In drivers/usb/host/xhci-ring.c (ffffffff8180f136)
Location: drivers/usb/host/xhci-ring.c:340
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
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
In drivers/usb/host/xhci-ring.c (ffffffff81840246)
Location: drivers/usb/host/xhci-ring.c:340
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:343
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
**Symbols:**

```
ffffffff81913ed0-ffffffff81913ff0: xhci_abort_cmd_ring.isra.0 (STB_LOCAL)
ffffffff819171dc-ffffffff81917206: xhci_abort_cmd_ring.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:343
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
**Symbols:**

```
ffffffff8191b4f0-ffffffff8191b610: xhci_abort_cmd_ring.isra.0 (STB_LOCAL)
ffffffff81c22104-ffffffff81c2212e: xhci_abort_cmd_ring.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:367
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
**Symbols:**

```
ffffffff818feab0-ffffffff818febd0: xhci_abort_cmd_ring.isra.0 (STB_LOCAL)
ffffffff81c14321-ffffffff81c1434b: xhci_abort_cmd_ring.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:367
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
**Symbols:**

```
ffffffff8199dc10-ffffffff8199ddab: xhci_abort_cmd_ring.isra.0 (STB_LOCAL)
ffffffff81d2126a-ffffffff81d21294: xhci_abort_cmd_ring.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:367
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
**Symbols:**

```
ffffffff81afaec0-ffffffff81afb075: xhci_abort_cmd_ring.isra.0 (STB_LOCAL)
ffffffff81eecdf8-ffffffff81eece21: xhci_abort_cmd_ring.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81c895d0)
Location: drivers/usb/host/xhci-ring.c:367
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
**Symbols:**

```
ffffffff81c895d0-ffffffff81c897d4: xhci_abort_cmd_ring.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81cf07d0)
Location: drivers/usb/host/xhci-ring.c:421
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
**Symbols:**

```
ffffffff81cf07d0-ffffffff81cf09e3: xhci_abort_cmd_ring.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81da5ff0)
Location: drivers/usb/host/xhci-ring.c:428
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
**Symbols:**

```
ffffffff81da5ff0-ffffffff81da623f: xhci_abort_cmd_ring.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffff800010a7ee1c)
Location: drivers/usb/host/xhci-ring.c:340
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
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
In drivers/usb/host/xhci-ring.c (c0b522b0)
Location: drivers/usb/host/xhci-ring.c:340
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
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
In drivers/usb/host/xhci-ring.c (c000000000b5783c)
Location: drivers/usb/host/xhci-ring.c:340
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
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
In drivers/usb/host/xhci-ring.c (ffffffe000695ad0)
Location: drivers/usb/host/xhci-ring.c:340
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
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
In drivers/usb/host/xhci-ring.c (ffffffff817f85f6)
Location: drivers/usb/host/xhci-ring.c:340
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
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
In drivers/usb/host/xhci-ring.c (ffffffff817bd796)
Location: drivers/usb/host/xhci-ring.c:340
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
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
In drivers/usb/host/xhci-ring.c (ffffffff818350c6)
Location: drivers/usb/host/xhci-ring.c:340
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
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
In drivers/usb/host/xhci-ring.c (ffffffff8184f3e6)
Location: drivers/usb/host/xhci-ring.c:340
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
</details>
</li>
</ul>

## Differences
