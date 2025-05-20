# Function: <code>start_unlink_intr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void start_unlink_intr(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81639450)
Location: drivers/usb/host/ehci-sched.c:673
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
```
**Symbols:**

```
ffffffff81639450-ffffffff8163974d: start_unlink_intr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void start_unlink_intr(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff8169a100)
Location: drivers/usb/host/ehci-sched.c:674
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
```
**Symbols:**

```
ffffffff8169a100-ffffffff8169a40b: start_unlink_intr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void start_unlink_intr(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff816c81e0)
Location: drivers/usb/host/ehci-sched.c:674
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
```
**Symbols:**

```
ffffffff816c81e0-ffffffff816c84eb: start_unlink_intr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void start_unlink_intr(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff816dcc50)
Location: drivers/usb/host/ehci-sched.c:674
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
```
**Symbols:**

```
ffffffff816dcc50-ffffffff816dcf43: start_unlink_intr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void start_unlink_intr(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81749380)
Location: drivers/usb/host/ehci-sched.c:661
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
```
**Symbols:**

```
ffffffff81749380-ffffffff8174968c: start_unlink_intr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void start_unlink_intr(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817893d0)
Location: drivers/usb/host/ehci-sched.c:662
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
```
**Symbols:**

```
ffffffff817893d0-ffffffff817896e0: start_unlink_intr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void start_unlink_intr(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817abf20)
Location: drivers/usb/host/ehci-sched.c:662
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
```
**Symbols:**

```
ffffffff817abf20-ffffffff817ac230: start_unlink_intr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void start_unlink_intr(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817eb130)
Location: drivers/usb/host/ehci-sched.c:662
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
```
**Symbols:**

```
ffffffff817eb130-ffffffff817eb43f: start_unlink_intr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void start_unlink_intr(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff8181c000)
Location: drivers/usb/host/ehci-sched.c:662
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
```
**Symbols:**

```
ffffffff8181c000-ffffffff8181c30f: start_unlink_intr (STB_LOCAL)
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
In drivers/usb/host/ehci-hcd.c (ffffffff818f2d9a)
Location: drivers/usb/host/ehci-sched.c:662
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
```
**Symbols:**

```
ffffffff818f09a0-ffffffff818f0a91: start_unlink_intr.part.0 (STB_LOCAL)
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
In drivers/usb/host/ehci-hcd.c (ffffffff818fbcba)
Location: drivers/usb/host/ehci-sched.c:648
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
```
**Symbols:**

```
ffffffff818f9cc0-ffffffff818f9db1: start_unlink_intr.part.0 (STB_LOCAL)
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
In drivers/usb/host/ehci-hcd.c (ffffffff818de96a)
Location: drivers/usb/host/ehci-sched.c:648
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
```
**Symbols:**

```
ffffffff818dcab0-ffffffff818dcba1: start_unlink_intr.part.0 (STB_LOCAL)
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
In drivers/usb/host/ehci-hcd.c (ffffffff8197a5ee)
Location: drivers/usb/host/ehci-sched.c:648
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
```
**Symbols:**

```
ffffffff819784a0-ffffffff81978591: start_unlink_intr.part.0 (STB_LOCAL)
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
In drivers/usb/host/ehci-hcd.c (ffffffff81ad7de6)
Location: drivers/usb/host/ehci-sched.c:648
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
```
**Symbols:**

```
ffffffff81ad5d40-ffffffff81ad5e4d: start_unlink_intr.part.0 (STB_LOCAL)
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
In drivers/usb/host/ehci-hcd.c (ffffffff81c62dd6)
Location: drivers/usb/host/ehci-sched.c:648
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
```
**Symbols:**

```
ffffffff81c60d70-ffffffff81c60e7d: start_unlink_intr.part.0 (STB_LOCAL)
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
In drivers/usb/host/ehci-hcd.c (ffffffff81cca1d6)
Location: drivers/usb/host/ehci-sched.c:648
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
```
**Symbols:**

```
ffffffff81cc8130-ffffffff81cc823d: start_unlink_intr.part.0 (STB_LOCAL)
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
In drivers/usb/host/ehci-hcd.c (ffffffff81d7f0b6)
Location: drivers/usb/host/ehci-sched.c:649
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
```
**Symbols:**

```
ffffffff81d7db40-ffffffff81d7dc4d: start_unlink_intr.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void start_unlink_intr(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffff800010a55950)
Location: drivers/usb/host/ehci-sched.c:662
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
```
**Symbols:**

```
ffff800010a55950-ffff800010a55c68: start_unlink_intr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (c0b28b5c)
Location: drivers/usb/host/ehci-sched.c:662
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
```
**Symbols:**

```
c0b2869c-c0b289d4: start_unlink_intr.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void start_unlink_intr(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (c000000000b22480)
Location: drivers/usb/host/ehci-sched.c:662
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
```
**Symbols:**

```
c000000000b22480-c000000000b228a0: start_unlink_intr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void start_unlink_intr(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffe0006732e2)
Location: drivers/usb/host/ehci-sched.c:662
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
```
**Symbols:**

```
ffffffe0006732e2-ffffffe000673536: start_unlink_intr (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void start_unlink_intr(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817d43e0)
Location: drivers/usb/host/ehci-sched.c:662
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
```
**Symbols:**

```
ffffffff817d43e0-ffffffff817d46ef: start_unlink_intr (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void start_unlink_intr(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81810e80)
Location: drivers/usb/host/ehci-sched.c:662
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
```
**Symbols:**

```
ffffffff81810e80-ffffffff8181118f: start_unlink_intr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void start_unlink_intr(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff8182b950)
Location: drivers/usb/host/ehci-sched.c:662
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_reset
  - drivers/usb/host/ehci-hcd.c:ehci_endpoint_disable
  - drivers/usb/host/ehci-hcd.c:ehci_urb_dequeue
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
```
**Symbols:**

```
ffffffff8182b950-ffffffff8182bc5f: start_unlink_intr (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
