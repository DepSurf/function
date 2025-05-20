# Function: <code>itd_link_urb</code>

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
In drivers/usb/host/ehci-hcd.c (ffffffff8163c2cb)
Location: drivers/usb/host/ehci-sched.c:1765
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
In drivers/usb/host/ehci-hcd.c (ffffffff8169ccf7)
Location: drivers/usb/host/ehci-sched.c:1763
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
In drivers/usb/host/ehci-hcd.c (ffffffff816cae17)
Location: drivers/usb/host/ehci-sched.c:1762
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
In drivers/usb/host/ehci-hcd.c (ffffffff816df500)
Location: drivers/usb/host/ehci-sched.c:1762
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
In drivers/usb/host/ehci-hcd.c (ffffffff8174bc57)
Location: drivers/usb/host/ehci-sched.c:1749
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
In drivers/usb/host/ehci-hcd.c (ffffffff8178c9ba)
Location: drivers/usb/host/ehci-sched.c:1750
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
In drivers/usb/host/ehci-hcd.c (ffffffff817b31ba)
Location: drivers/usb/host/ehci-sched.c:1750
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
In drivers/usb/host/ehci-hcd.c (ffffffff817f005e)
Location: drivers/usb/host/ehci-sched.c:1750
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:itd_submit
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
In drivers/usb/host/ehci-hcd.c (ffffffff81820f4e)
Location: drivers/usb/host/ehci-sched.c:1750
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:itd_submit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void itd_link_urb(struct ehci_hcd *ehci, struct urb *urb, unsigned int mod, struct ehci_iso_stream *stream);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818f0da0)
Location: drivers/usb/host/ehci-sched.c:1750
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:itd_submit
```
**Symbols:**

```
ffffffff818f0da0-ffffffff818f10b0: itd_link_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void itd_link_urb(struct ehci_hcd *ehci, struct urb *urb, unsigned int mod, struct ehci_iso_stream *stream);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818fa0c0)
Location: drivers/usb/host/ehci-sched.c:1742
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:itd_submit
```
**Symbols:**

```
ffffffff818fa0c0-ffffffff818fa3d0: itd_link_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void itd_link_urb(struct ehci_hcd *ehci, struct urb *urb, unsigned int mod, struct ehci_iso_stream *stream);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818dcea0)
Location: drivers/usb/host/ehci-sched.c:1742
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:itd_submit
```
**Symbols:**

```
ffffffff818dcea0-ffffffff818dd1a3: itd_link_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void itd_link_urb(struct ehci_hcd *ehci, struct urb *urb, unsigned int mod, struct ehci_iso_stream *stream);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81978890)
Location: drivers/usb/host/ehci-sched.c:1742
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:itd_submit
```
**Symbols:**

```
ffffffff81978890-ffffffff81978d32: itd_link_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void itd_link_urb(struct ehci_hcd *ehci, struct urb *urb, unsigned int mod, struct ehci_iso_stream *stream);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81ad6190)
Location: drivers/usb/host/ehci-sched.c:1740
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:itd_submit
```
**Symbols:**

```
ffffffff81ad6190-ffffffff81ad664f: itd_link_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void itd_link_urb(struct ehci_hcd *ehci, struct urb *urb, unsigned int mod, struct ehci_iso_stream *stream);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81c611f0)
Location: drivers/usb/host/ehci-sched.c:1740
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:itd_submit
```
**Symbols:**

```
ffffffff81c611f0-ffffffff81c616af: itd_link_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void itd_link_urb(struct ehci_hcd *ehci, struct urb *urb, unsigned int mod, struct ehci_iso_stream *stream);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81cc85b0)
Location: drivers/usb/host/ehci-sched.c:1740
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:itd_submit
```
**Symbols:**

```
ffffffff81cc85b0-ffffffff81cc8a47: itd_link_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void itd_link_urb(struct ehci_hcd *ehci, struct urb *urb, unsigned int mod, struct ehci_iso_stream *stream);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81d7c860)
Location: drivers/usb/host/ehci-sched.c:1741
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:itd_submit
```
**Symbols:**

```
ffffffff81d7c860-ffffffff81d7ccb7: itd_link_urb (STB_LOCAL)
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
In drivers/usb/host/ehci-hcd.c (ffff800010a5b3c4)
Location: drivers/usb/host/ehci-sched.c:1750
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:itd_submit
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
In drivers/usb/host/ehci-hcd.c (c0b2e3f4)
Location: drivers/usb/host/ehci-sched.c:1750
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:itd_submit
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
In drivers/usb/host/ehci-hcd.c (c000000000b28458)
Location: drivers/usb/host/ehci-sched.c:1750
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:itd_submit
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
In drivers/usb/host/ehci-hcd.c (ffffffe00067384c)
Location: drivers/usb/host/ehci-sched.c:1750
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:itd_submit
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
In drivers/usb/host/ehci-hcd.c (ffffffff817d932e)
Location: drivers/usb/host/ehci-sched.c:1750
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:itd_submit
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
In drivers/usb/host/ehci-hcd.c (ffffffff81815dce)
Location: drivers/usb/host/ehci-sched.c:1750
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:itd_submit
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
In drivers/usb/host/ehci-hcd.c (ffffffff8182fe1e)
Location: drivers/usb/host/ehci-sched.c:1750
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:itd_submit
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
