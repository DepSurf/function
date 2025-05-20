# Function: <code>uhci_unlink_isochronous_tds</code>

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
In drivers/usb/host/uhci-hcd.c (ffffffff81646044)
Location: drivers/usb/host/uhci-q.c:236
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
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
In drivers/usb/host/uhci-hcd.c (ffffffff816a6b64)
Location: drivers/usb/host/uhci-q.c:236
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
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
In drivers/usb/host/uhci-hcd.c (ffffffff816d4c84)
Location: drivers/usb/host/uhci-q.c:236
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
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
In drivers/usb/host/uhci-hcd.c (ffffffff816eb590)
Location: drivers/usb/host/uhci-q.c:236
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
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
In drivers/usb/host/uhci-hcd.c (ffffffff81757d80)
Location: drivers/usb/host/uhci-q.c:237
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
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
In drivers/usb/host/uhci-hcd.c (ffffffff81797291)
Location: drivers/usb/host/uhci-q.c:236
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
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
In drivers/usb/host/uhci-hcd.c (ffffffff817bc371)
Location: drivers/usb/host/uhci-q.c:236
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
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
In drivers/usb/host/uhci-hcd.c (ffffffff817fb543)
Location: drivers/usb/host/uhci-q.c:236
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
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
In drivers/usb/host/uhci-hcd.c (ffffffff8182c3a2)
Location: drivers/usb/host/uhci-q.c:236
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void uhci_unlink_isochronous_tds(struct uhci_hcd *uhci, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff818fd480)
Location: drivers/usb/host/uhci-q.c:236
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
```
**Symbols:**

```
ffffffff818fd480-ffffffff818fd55d: uhci_unlink_isochronous_tds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void uhci_unlink_isochronous_tds(struct uhci_hcd *uhci, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81905d80)
Location: drivers/usb/host/uhci-q.c:236
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
```
**Symbols:**

```
ffffffff81905d80-ffffffff81905e5d: uhci_unlink_isochronous_tds (STB_LOCAL)
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
In drivers/usb/host/uhci-hcd.c (ffffffff818ebfc5)
Location: drivers/usb/host/uhci-q.c:236
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
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
In drivers/usb/host/uhci-hcd.c (ffffffff819886d5)
Location: drivers/usb/host/uhci-q.c:236
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
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
In drivers/usb/host/uhci-hcd.c (ffffffff81ae5d74)
Location: drivers/usb/host/uhci-q.c:236
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
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
In drivers/usb/host/uhci-hcd.c (ffffffff81c71ac4)
Location: drivers/usb/host/uhci-q.c:236
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
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
In drivers/usb/host/uhci-hcd.c (ffffffff81cd9094)
Location: drivers/usb/host/uhci-q.c:236
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
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
In drivers/usb/host/uhci-hcd.c (ffffffff81d8e0a4)
Location: drivers/usb/host/uhci-q.c:236
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
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
In drivers/usb/host/uhci-hcd.c (ffff800010a6b440)
Location: drivers/usb/host/uhci-q.c:236
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
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
In drivers/usb/host/uhci-hcd.c (c0b3c4dc)
Location: drivers/usb/host/uhci-q.c:236
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
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
In drivers/usb/host/uhci-hcd.c (c000000000b3b770)
Location: drivers/usb/host/uhci-q.c:236
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
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
In drivers/usb/host/uhci-hcd.c (ffffffe000682644)
Location: drivers/usb/host/uhci-q.c:236
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
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
In drivers/usb/host/uhci-hcd.c (ffffffff817e4782)
Location: drivers/usb/host/uhci-q.c:236
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
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
In drivers/usb/host/uhci-hcd.c (ffffffff81821222)
Location: drivers/usb/host/uhci-q.c:236
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
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
In drivers/usb/host/uhci-hcd.c (ffffffff8183b8f2)
Location: drivers/usb/host/uhci-q.c:236
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
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
