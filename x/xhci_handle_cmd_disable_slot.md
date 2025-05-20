# Function: <code>xhci_handle_cmd_disable_slot</code>

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
In drivers/usb/host/xhci-ring.c (ffffffff8165a531)
Location: drivers/usb/host/xhci-ring.c:1091
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
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
In drivers/usb/host/xhci-ring.c (ffffffff816bad32)
Location: drivers/usb/host/xhci-ring.c:1107
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
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
In drivers/usb/host/xhci-ring.c (ffffffff816e9258)
Location: drivers/usb/host/xhci-ring.c:1158
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
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
In drivers/usb/host/xhci-ring.c (ffffffff816fd2c3)
Location: drivers/usb/host/xhci-ring.c:1183
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
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
In drivers/usb/host/xhci-ring.c (ffffffff81769e4a)
Location: drivers/usb/host/xhci-ring.c:1169
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
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
In drivers/usb/host/xhci-ring.c (ffffffff817ab043)
Location: drivers/usb/host/xhci-ring.c:1169
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
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
In drivers/usb/host/xhci-ring.c (ffffffff817d0ea3)
Location: drivers/usb/host/xhci-ring.c:1173
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
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
In drivers/usb/host/xhci-ring.c (ffffffff81810fb1)
Location: drivers/usb/host/xhci-ring.c:1184
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
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
In drivers/usb/host/xhci-ring.c (ffffffff81842193)
Location: drivers/usb/host/xhci-ring.c:1184
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xhci_handle_cmd_disable_slot(struct xhci_hcd *xhci, int slot_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81911570)
Location: drivers/usb/host/xhci-ring.c:1210
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff81911570-ffffffff81911621: xhci_handle_cmd_disable_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xhci_handle_cmd_disable_slot(struct xhci_hcd *xhci, int slot_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81918fd0)
Location: drivers/usb/host/xhci-ring.c:1215
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff81918fd0-ffffffff81919069: xhci_handle_cmd_disable_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff8190017c)
Location: drivers/usb/host/xhci-ring.c:1448
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff8199f91c)
Location: drivers/usb/host/xhci-ring.c:1513
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81afce17)
Location: drivers/usb/host/xhci-ring.c:1448
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81c8b986)
Location: drivers/usb/host/xhci-ring.c:1450
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81cf2502)
Location: drivers/usb/host/xhci-ring.c:1472
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81da7e78)
Location: drivers/usb/host/xhci-ring.c:1480
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
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
In drivers/usb/host/xhci-ring.c (ffff800010a8108c)
Location: drivers/usb/host/xhci-ring.c:1184
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
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
In drivers/usb/host/xhci-ring.c (c0b545c4)
Location: drivers/usb/host/xhci-ring.c:1184
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
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
In drivers/usb/host/xhci-ring.c (c000000000b5a480)
Location: drivers/usb/host/xhci-ring.c:1184
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
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
In drivers/usb/host/xhci-ring.c (ffffffe000697992)
Location: drivers/usb/host/xhci-ring.c:1184
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
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
In drivers/usb/host/xhci-ring.c (ffffffff817fa543)
Location: drivers/usb/host/xhci-ring.c:1184
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
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
In drivers/usb/host/xhci-ring.c (ffffffff817bf6e3)
Location: drivers/usb/host/xhci-ring.c:1184
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
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
In drivers/usb/host/xhci-ring.c (ffffffff81837013)
Location: drivers/usb/host/xhci-ring.c:1184
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
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
In drivers/usb/host/xhci-ring.c (ffffffff818513b2)
Location: drivers/usb/host/xhci-ring.c:1184
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
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
