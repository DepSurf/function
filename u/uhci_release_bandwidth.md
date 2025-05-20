# Function: <code>uhci_release_bandwidth</code>

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
In drivers/usb/host/uhci-hcd.c (ffffffff81645e46)
Location: drivers/usb/host/uhci-q.c:693
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
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
In drivers/usb/host/uhci-hcd.c (ffffffff816a697c)
Location: drivers/usb/host/uhci-q.c:692
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
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
In drivers/usb/host/uhci-hcd.c (ffffffff816d4a9c)
Location: drivers/usb/host/uhci-q.c:692
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
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
In drivers/usb/host/uhci-hcd.c (ffffffff816e8ef9)
Location: drivers/usb/host/uhci-q.c:692
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
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
In drivers/usb/host/uhci-hcd.c (ffffffff817556e9)
Location: drivers/usb/host/uhci-q.c:693
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
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
In drivers/usb/host/uhci-hcd.c (ffffffff817984c9)
Location: drivers/usb/host/uhci-q.c:692
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
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
In drivers/usb/host/uhci-hcd.c (ffffffff817be999)
Location: drivers/usb/host/uhci-q.c:692
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
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
In drivers/usb/host/uhci-hcd.c (ffffffff817fe301)
Location: drivers/usb/host/uhci-q.c:692
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
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
In drivers/usb/host/uhci-hcd.c (ffffffff8182f151)
Location: drivers/usb/host/uhci-q.c:692
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void uhci_release_bandwidth(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff818fd560)
Location: drivers/usb/host/uhci-q.c:692
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
```
**Symbols:**

```
ffffffff818fd560-ffffffff818fd637: uhci_release_bandwidth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void uhci_release_bandwidth(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81905e60)
Location: drivers/usb/host/uhci-q.c:692
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
```
**Symbols:**

```
ffffffff81905e60-ffffffff81905f37: uhci_release_bandwidth (STB_LOCAL)
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
In drivers/usb/host/uhci-hcd.c (ffffffff818ed90d)
Location: drivers/usb/host/uhci-q.c:692
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
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
In drivers/usb/host/uhci-hcd.c (ffffffff8198a021)
Location: drivers/usb/host/uhci-q.c:692
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
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
In drivers/usb/host/uhci-hcd.c (ffffffff81ae537b)
Location: drivers/usb/host/uhci-q.c:692
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
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
In drivers/usb/host/uhci-hcd.c (ffffffff81c70f9b)
Location: drivers/usb/host/uhci-q.c:692
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
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
In drivers/usb/host/uhci-hcd.c (ffffffff81cd857f)
Location: drivers/usb/host/uhci-q.c:692
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
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
In drivers/usb/host/uhci-hcd.c (ffffffff81d8d58f)
Location: drivers/usb/host/uhci-q.c:692
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
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
In drivers/usb/host/uhci-hcd.c (ffff800010a69a34)
Location: drivers/usb/host/uhci-q.c:692
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
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
In drivers/usb/host/uhci-hcd.c (c0b3b6c0)
Location: drivers/usb/host/uhci-q.c:692
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
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
In drivers/usb/host/uhci-hcd.c (c000000000b3a918)
Location: drivers/usb/host/uhci-q.c:692
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
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
In drivers/usb/host/uhci-hcd.c (ffffffe000684bd6)
Location: drivers/usb/host/uhci-q.c:692
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
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
In drivers/usb/host/uhci-hcd.c (ffffffff817e7531)
Location: drivers/usb/host/uhci-q.c:692
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
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
In drivers/usb/host/uhci-hcd.c (ffffffff81823fd1)
Location: drivers/usb/host/uhci-q.c:692
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
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
In drivers/usb/host/uhci-hcd.c (ffffffff8183b70f)
Location: drivers/usb/host/uhci-q.c:692
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
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
