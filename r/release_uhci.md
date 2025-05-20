# Function: <code>release_uhci</code>

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
In drivers/usb/host/uhci-hcd.c (ffffffff816496c5)
Location: drivers/usb/host/uhci-hcd.c:518
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
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
In drivers/usb/host/uhci-hcd.c (ffffffff816aa135)
Location: drivers/usb/host/uhci-hcd.c:518
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
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
In drivers/usb/host/uhci-hcd.c (ffffffff816d8285)
Location: drivers/usb/host/uhci-hcd.c:518
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
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
In drivers/usb/host/uhci-hcd.c (ffffffff816ec7a1)
Location: drivers/usb/host/uhci-hcd.c:529
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
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
In drivers/usb/host/uhci-hcd.c (ffffffff81758f91)
Location: drivers/usb/host/uhci-hcd.c:530
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
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
In drivers/usb/host/uhci-hcd.c (ffffffff817997d9)
Location: drivers/usb/host/uhci-hcd.c:530
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
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
In drivers/usb/host/uhci-hcd.c (ffffffff817bfa19)
Location: drivers/usb/host/uhci-hcd.c:530
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
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
In drivers/usb/host/uhci-hcd.c (ffffffff817ff2c9)
Location: drivers/usb/host/uhci-hcd.c:530
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
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
In drivers/usb/host/uhci-hcd.c (ffffffff81830129)
Location: drivers/usb/host/uhci-hcd.c:530
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void release_uhci(struct uhci_hcd *uhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81900590)
Location: drivers/usb/host/uhci-hcd.c:530
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
```
**Symbols:**

```
ffffffff81900590-ffffffff8190064e: release_uhci (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void release_uhci(struct uhci_hcd *uhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81908e60)
Location: drivers/usb/host/uhci-hcd.c:530
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
```
**Symbols:**

```
ffffffff81908e60-ffffffff81908f1e: release_uhci (STB_LOCAL)
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
In drivers/usb/host/uhci-hcd.c (ffffffff818ee6c0)
Location: drivers/usb/host/uhci-hcd.c:530
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
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
In drivers/usb/host/uhci-hcd.c (ffffffff8198ae90)
Location: drivers/usb/host/uhci-hcd.c:530
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
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
In drivers/usb/host/uhci-hcd.c (ffffffff81ae5be5)
Location: drivers/usb/host/uhci-hcd.c:530
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
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
In drivers/usb/host/uhci-hcd.c (ffffffff81c71935)
Location: drivers/usb/host/uhci-hcd.c:530
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
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
In drivers/usb/host/uhci-hcd.c (ffffffff81cd8f05)
Location: drivers/usb/host/uhci-hcd.c:530
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
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
In drivers/usb/host/uhci-hcd.c (ffffffff81d8df15)
Location: drivers/usb/host/uhci-hcd.c:530
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
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
In drivers/usb/host/uhci-hcd.c (ffff800010a6a644)
Location: drivers/usb/host/uhci-hcd.c:530
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
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
In drivers/usb/host/uhci-hcd.c (c0b3c394)
Location: drivers/usb/host/uhci-hcd.c:530
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
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
In drivers/usb/host/uhci-hcd.c (c000000000b3c5d8)
Location: drivers/usb/host/uhci-hcd.c:530
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
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
In drivers/usb/host/uhci-hcd.c (ffffffe00068566e)
Location: drivers/usb/host/uhci-hcd.c:530
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
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
In drivers/usb/host/uhci-hcd.c (ffffffff817e8509)
Location: drivers/usb/host/uhci-hcd.c:530
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
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
In drivers/usb/host/uhci-hcd.c (ffffffff81824fa9)
Location: drivers/usb/host/uhci-hcd.c:530
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
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
In drivers/usb/host/uhci-hcd.c (ffffffff8183dc77)
Location: drivers/usb/host/uhci-hcd.c:530
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
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
