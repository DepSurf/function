# Function: <code>xhci_disable_port_wake_on_bits</code>

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
In drivers/usb/host/xhci.c (ffffffff8164c967)
Location: drivers/usb/host/xhci.c:852
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
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
In drivers/usb/host/xhci.c (ffffffff816ad2a7)
Location: drivers/usb/host/xhci.c:859
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
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
In drivers/usb/host/xhci.c (ffffffff816db587)
Location: drivers/usb/host/xhci.c:862
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
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
In drivers/usb/host/xhci.c (ffffffff816eff38)
Location: drivers/usb/host/xhci.c:825
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
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
In drivers/usb/host/xhci.c (ffffffff8175c0f9)
Location: drivers/usb/host/xhci.c:823
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
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
In drivers/usb/host/xhci.c (ffffffff8179c938)
Location: drivers/usb/host/xhci.c:892
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
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
In drivers/usb/host/xhci.c (ffffffff817c2e77)
Location: drivers/usb/host/xhci.c:891
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
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
In drivers/usb/host/xhci.c (ffffffff81802b01)
Location: drivers/usb/host/xhci.c:889
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
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
In drivers/usb/host/xhci.c (ffffffff81833a01)
Location: drivers/usb/host/xhci.c:886
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xhci_disable_port_wake_on_bits(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81903ab0)
Location: drivers/usb/host/xhci.c:886
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_suspend
```
**Symbols:**

```
ffffffff81903ab0-ffffffff81903c1b: xhci_disable_port_wake_on_bits (STB_LOCAL)
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffff800010a70b6c)
Location: drivers/usb/host/xhci.c:886
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
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
In drivers/usb/host/xhci.c (c0b449e8)
Location: drivers/usb/host/xhci.c:886
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
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
In drivers/usb/host/xhci.c (c000000000b45330)
Location: drivers/usb/host/xhci.c:886
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
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
In drivers/usb/host/xhci.c (ffffffe00068923a)
Location: drivers/usb/host/xhci.c:886
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
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
In drivers/usb/host/xhci.c (ffffffff817ebdd9)
Location: drivers/usb/host/xhci.c:886
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
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
In drivers/usb/host/xhci.c (ffffffff817b0eeb)
Location: drivers/usb/host/xhci.c:886
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
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
In drivers/usb/host/xhci.c (ffffffff81828881)
Location: drivers/usb/host/xhci.c:886
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
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
In drivers/usb/host/xhci.c (ffffffff81842848)
Location: drivers/usb/host/xhci.c:886
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_suspend
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
