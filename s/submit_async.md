# Function: <code>submit_async</code>

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
In drivers/usb/host/ehci-hcd.c (ffffffff8163ba52)
Location: drivers/usb/host/ehci-q.c:1097
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
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
In drivers/usb/host/ehci-hcd.c (ffffffff8169c715)
Location: drivers/usb/host/ehci-q.c:1106
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
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
In drivers/usb/host/ehci-hcd.c (ffffffff816ca835)
Location: drivers/usb/host/ehci-q.c:1104
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
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
In drivers/usb/host/ehci-hcd.c (ffffffff816def45)
Location: drivers/usb/host/ehci-q.c:1104
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
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
In drivers/usb/host/ehci-hcd.c (ffffffff8174b695)
Location: drivers/usb/host/ehci-q.c:1091
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
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
In drivers/usb/host/ehci-hcd.c (ffffffff8178bf54)
Location: drivers/usb/host/ehci-q.c:1091
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
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
In drivers/usb/host/ehci-hcd.c (ffffffff817b2754)
Location: drivers/usb/host/ehci-q.c:1091
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
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
In drivers/usb/host/ehci-hcd.c (ffffffff817f04b7)
Location: drivers/usb/host/ehci-q.c:1091
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
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
In drivers/usb/host/ehci-hcd.c (ffffffff818213a7)
Location: drivers/usb/host/ehci-q.c:1102
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
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
In drivers/usb/host/ehci-hcd.c (ffffffff818f1500)
Location: drivers/usb/host/ehci-q.c:1102
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
**Symbols:**

```
ffffffff818f1500-ffffffff818f1651: submit_async.constprop.0 (STB_LOCAL)
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
In drivers/usb/host/ehci-hcd.c (ffffffff818f9260)
Location: drivers/usb/host/ehci-q.c:1102
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
**Symbols:**

```
ffffffff818f9260-ffffffff818f93b1: submit_async.constprop.0 (STB_LOCAL)
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
In drivers/usb/host/ehci-hcd.c (ffffffff818dd677)
Location: drivers/usb/host/ehci-q.c:1102
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
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
In drivers/usb/host/ehci-hcd.c (ffffffff819791f7)
Location: drivers/usb/host/ehci-q.c:1102
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
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
In drivers/usb/host/ehci-hcd.c (ffffffff81ad6b77)
Location: drivers/usb/host/ehci-q.c:1103
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
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
In drivers/usb/host/ehci-hcd.c (ffffffff81c618e7)
Location: drivers/usb/host/ehci-q.c:1103
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
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
In drivers/usb/host/ehci-hcd.c (ffffffff81cc8cad)
Location: drivers/usb/host/ehci-q.c:1103
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
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
In drivers/usb/host/ehci-hcd.c (ffffffff81d7d97d)
Location: drivers/usb/host/ehci-q.c:1103
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
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
In drivers/usb/host/ehci-hcd.c (ffff800010a5be64)
Location: drivers/usb/host/ehci-q.c:1102
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
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
In drivers/usb/host/ehci-hcd.c (c0b2e860)
Location: drivers/usb/host/ehci-q.c:1102
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
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
In drivers/usb/host/ehci-hcd.c (c000000000b289f4)
Location: drivers/usb/host/ehci-q.c:1102
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
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
In drivers/usb/host/ehci-hcd.c (ffffffe0006742ea)
Location: drivers/usb/host/ehci-q.c:1102
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
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
In drivers/usb/host/ehci-hcd.c (ffffffff817d9787)
Location: drivers/usb/host/ehci-q.c:1102
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81816227)
Location: drivers/usb/host/ehci-q.c:1102
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
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
In drivers/usb/host/ehci-hcd.c (ffffffff81830277)
Location: drivers/usb/host/ehci-q.c:1102
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
</details>
</li>
</ul>

## Differences
