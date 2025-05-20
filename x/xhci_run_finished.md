# Function: <code>xhci_run_finished</code>

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
In drivers/usb/host/xhci.c (ffffffff8164d34e)
Location: drivers/usb/host/xhci.c:568
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
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
In drivers/usb/host/xhci.c (ffffffff816adc73)
Location: drivers/usb/host/xhci.c:568
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
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
In drivers/usb/host/xhci.c (ffffffff816dbd6c)
Location: drivers/usb/host/xhci.c:572
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
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
In drivers/usb/host/xhci.c (ffffffff816f069a)
Location: drivers/usb/host/xhci.c:537
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
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
In drivers/usb/host/xhci.c (ffffffff8175c86a)
Location: drivers/usb/host/xhci.c:527
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
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
In drivers/usb/host/xhci.c (ffffffff8179d1a4)
Location: drivers/usb/host/xhci.c:606
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
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
In drivers/usb/host/xhci.c (ffffffff817c3584)
Location: drivers/usb/host/xhci.c:607
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
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
In drivers/usb/host/xhci.c (ffffffff81802fe7)
Location: drivers/usb/host/xhci.c:605
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
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
In drivers/usb/host/xhci.c (ffffffff81833ee7)
Location: drivers/usb/host/xhci.c:605
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81906db7)
Location: drivers/usb/host/xhci.c:605
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8190f557)
Location: drivers/usb/host/xhci.c:605
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
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
In drivers/usb/host/xhci.c (ffffffff818f2b25)
Location: drivers/usb/host/xhci.c:608
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
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
In drivers/usb/host/xhci.c (ffffffff8198fd95)
Location: drivers/usb/host/xhci.c:608
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xhci_run_finished(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81aec130)
Location: drivers/usb/host/xhci.c:612
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_run
```
**Symbols:**

```
ffffffff81aec130-ffffffff81aec207: xhci_run_finished (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xhci_run_finished(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81c78960)
Location: drivers/usb/host/xhci.c:614
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_run
```
**Symbols:**

```
ffffffff81c78960-ffffffff81c78a37: xhci_run_finished (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xhci_run_finished(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81cdf9e0)
Location: drivers/usb/host/xhci.c:457
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_run
```
**Symbols:**

```
ffffffff81cdf9e0-ffffffff81cdfac8: xhci_run_finished (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xhci_run_finished(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81d94ab0)
Location: drivers/usb/host/xhci.c:481
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_run
```
**Symbols:**

```
ffffffff81d94ab0-ffffffff81d94b9b: xhci_run_finished (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffff800010a713c4)
Location: drivers/usb/host/xhci.c:605
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
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
In drivers/usb/host/xhci.c (c0b45194)
Location: drivers/usb/host/xhci.c:605
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
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
In drivers/usb/host/xhci.c (c000000000b46230)
Location: drivers/usb/host/xhci.c:605
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
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
In drivers/usb/host/xhci.c (ffffffe000689a66)
Location: drivers/usb/host/xhci.c:605
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
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
In drivers/usb/host/xhci.c (ffffffff817ec2af)
Location: drivers/usb/host/xhci.c:605
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
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
In drivers/usb/host/xhci.c (ffffffff817b13c7)
Location: drivers/usb/host/xhci.c:605
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
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
In drivers/usb/host/xhci.c (ffffffff81828d67)
Location: drivers/usb/host/xhci.c:605
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
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
In drivers/usb/host/xhci.c (ffffffff81842d27)
Location: drivers/usb/host/xhci.c:605
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
