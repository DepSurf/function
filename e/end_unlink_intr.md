# Function: <code>end_unlink_intr</code>

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
In drivers/usb/host/ehci-hcd.c (ffffffff81639363)
Location: drivers/usb/host/ehci-sched.c:728
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
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
In drivers/usb/host/ehci-hcd.c (ffffffff81699ffb)
Location: drivers/usb/host/ehci-sched.c:729
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
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
In drivers/usb/host/ehci-hcd.c (ffffffff816c80db)
Location: drivers/usb/host/ehci-sched.c:729
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
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
In drivers/usb/host/ehci-hcd.c (ffffffff816dcb4b)
Location: drivers/usb/host/ehci-sched.c:729
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
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
In drivers/usb/host/ehci-hcd.c (ffffffff8174927b)
Location: drivers/usb/host/ehci-sched.c:716
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
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
In drivers/usb/host/ehci-hcd.c (ffffffff817892e1)
Location: drivers/usb/host/ehci-sched.c:717
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
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
In drivers/usb/host/ehci-hcd.c (ffffffff817abe31)
Location: drivers/usb/host/ehci-sched.c:717
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
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
In drivers/usb/host/ehci-hcd.c (ffffffff817eb051)
Location: drivers/usb/host/ehci-sched.c:717
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
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
In drivers/usb/host/ehci-hcd.c (ffffffff8181bf21)
Location: drivers/usb/host/ehci-sched.c:717
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void end_unlink_intr(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci-sched.c:717
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
```
**Symbols:**

```
ffffffff818f0820-ffffffff818f08ca: end_unlink_intr (STB_LOCAL)
ffffffff818f555d-ffffffff818f557b: end_unlink_intr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void end_unlink_intr(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci-sched.c:703
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
```
**Symbols:**

```
ffffffff818f9b40-ffffffff818f9bea: end_unlink_intr (STB_LOCAL)
ffffffff81c2025e-ffffffff81c2027c: end_unlink_intr.cold (STB_LOCAL)
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
In drivers/usb/host/ehci-hcd.c (ffffffff818dc9d9)
Location: drivers/usb/host/ehci-sched.c:703
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
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
In drivers/usb/host/ehci-hcd.c (ffffffff819783c9)
Location: drivers/usb/host/ehci-sched.c:703
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
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
In drivers/usb/host/ehci-hcd.c (ffffffff81ad5c5d)
Location: drivers/usb/host/ehci-sched.c:703
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
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
In drivers/usb/host/ehci-hcd.c (ffffffff81c60c6d)
Location: drivers/usb/host/ehci-sched.c:703
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
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
In drivers/usb/host/ehci-hcd.c (ffffffff81cc802d)
Location: drivers/usb/host/ehci-sched.c:703
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
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
In drivers/usb/host/ehci-hcd.c (ffffffff81d7d56d)
Location: drivers/usb/host/ehci-sched.c:704
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
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
In drivers/usb/host/ehci-hcd.c (ffff800010a55880)
Location: drivers/usb/host/ehci-sched.c:717
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
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
In drivers/usb/host/ehci-hcd.c (c0b285ac)
Location: drivers/usb/host/ehci-sched.c:717
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
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
In drivers/usb/host/ehci-hcd.c (c000000000b22350)
Location: drivers/usb/host/ehci-sched.c:717
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
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
In drivers/usb/host/ehci-hcd.c (ffffffe0006731c6)
Location: drivers/usb/host/ehci-sched.c:717
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
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
In drivers/usb/host/ehci-hcd.c (ffffffff817d4301)
Location: drivers/usb/host/ehci-sched.c:717
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
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
In drivers/usb/host/ehci-hcd.c (ffffffff81810da1)
Location: drivers/usb/host/ehci-sched.c:717
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
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
In drivers/usb/host/ehci-hcd.c (ffffffff8182b871)
Location: drivers/usb/host/ehci-sched.c:717
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
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
