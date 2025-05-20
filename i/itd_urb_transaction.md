# Function: <code>itd_urb_transaction</code>

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
In drivers/usb/host/ehci-hcd.c (ffffffff8163bf98)
Location: drivers/usb/host/ehci-sched.c:1263
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
In drivers/usb/host/ehci-hcd.c (ffffffff8169c9e8)
Location: drivers/usb/host/ehci-sched.c:1261
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
In drivers/usb/host/ehci-hcd.c (ffffffff816cab08)
Location: drivers/usb/host/ehci-sched.c:1260
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
In drivers/usb/host/ehci-hcd.c (ffffffff816df164)
Location: drivers/usb/host/ehci-sched.c:1260
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
In drivers/usb/host/ehci-hcd.c (ffffffff8174b8b9)
Location: drivers/usb/host/ehci-sched.c:1247
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
In drivers/usb/host/ehci-hcd.c (ffffffff8178c3ea)
Location: drivers/usb/host/ehci-sched.c:1248
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
In drivers/usb/host/ehci-hcd.c (ffffffff817b2bea)
Location: drivers/usb/host/ehci-sched.c:1248
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
In drivers/usb/host/ehci-hcd.c (ffffffff817efd93)
Location: drivers/usb/host/ehci-sched.c:1248
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
In drivers/usb/host/ehci-hcd.c (ffffffff81820c83)
Location: drivers/usb/host/ehci-sched.c:1248
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
int itd_urb_transaction(struct ehci_iso_stream *stream, struct ehci_hcd *ehci, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818eed10)
Location: drivers/usb/host/ehci-sched.c:1248
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:itd_submit
```
**Symbols:**

```
ffffffff818eed10-ffffffff818ef062: itd_urb_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int itd_urb_transaction(struct ehci_iso_stream *stream, struct ehci_hcd *ehci, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818f7d10)
Location: drivers/usb/host/ehci-sched.c:1234
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:itd_submit
```
**Symbols:**

```
ffffffff818f7d10-ffffffff818f8062: itd_urb_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int itd_urb_transaction(struct ehci_iso_stream *stream, struct ehci_hcd *ehci, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818db2e0)
Location: drivers/usb/host/ehci-sched.c:1234
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:itd_submit
```
**Symbols:**

```
ffffffff818db2e0-ffffffff818db635: itd_urb_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int itd_urb_transaction(struct ehci_iso_stream *stream, struct ehci_hcd *ehci, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81976900)
Location: drivers/usb/host/ehci-sched.c:1234
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:itd_submit
```
**Symbols:**

```
ffffffff81976900-ffffffff81976c55: itd_urb_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int itd_urb_transaction(struct ehci_iso_stream *stream, struct ehci_hcd *ehci, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81ad25b0)
Location: drivers/usb/host/ehci-sched.c:1232
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:itd_submit
```
**Symbols:**

```
ffffffff81ad25b0-ffffffff81ad2941: itd_urb_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int itd_urb_transaction(struct ehci_iso_stream *stream, struct ehci_hcd *ehci, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81c5d1d0)
Location: drivers/usb/host/ehci-sched.c:1232
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:itd_submit
```
**Symbols:**

```
ffffffff81c5d1d0-ffffffff81c5d561: itd_urb_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int itd_urb_transaction(struct ehci_iso_stream *stream, struct ehci_hcd *ehci, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81cc4850)
Location: drivers/usb/host/ehci-sched.c:1232
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:itd_submit
```
**Symbols:**

```
ffffffff81cc4850-ffffffff81cc4bd1: itd_urb_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int itd_urb_transaction(struct ehci_iso_stream *stream, struct ehci_hcd *ehci, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81d79740)
Location: drivers/usb/host/ehci-sched.c:1233
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:itd_submit
```
**Symbols:**

```
ffffffff81d79740-ffffffff81d79ac1: itd_urb_transaction (STB_LOCAL)
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
In drivers/usb/host/ehci-hcd.c (ffff800010a5b100)
Location: drivers/usb/host/ehci-sched.c:1248
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
In drivers/usb/host/ehci-hcd.c (c0b2e108)
Location: drivers/usb/host/ehci-sched.c:1248
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
In drivers/usb/host/ehci-hcd.c (c000000000b28118)
Location: drivers/usb/host/ehci-sched.c:1248
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
In drivers/usb/host/ehci-hcd.c (ffffffe000673620)
Location: drivers/usb/host/ehci-sched.c:1248
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
In drivers/usb/host/ehci-hcd.c (ffffffff817d9063)
Location: drivers/usb/host/ehci-sched.c:1248
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
In drivers/usb/host/ehci-hcd.c (ffffffff81815b03)
Location: drivers/usb/host/ehci-sched.c:1248
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
In drivers/usb/host/ehci-hcd.c (ffffffff8182fb53)
Location: drivers/usb/host/ehci-sched.c:1248
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
