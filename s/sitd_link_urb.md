# Function: <code>sitd_link_urb</code>

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
In drivers/usb/host/ehci-hcd.c (ffffffff8163c63a)
Location: drivers/usb/host/ehci-sched.c:2167
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
In drivers/usb/host/ehci-hcd.c (ffffffff8169cf20)
Location: drivers/usb/host/ehci-sched.c:2166
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
In drivers/usb/host/ehci-hcd.c (ffffffff816cb040)
Location: drivers/usb/host/ehci-sched.c:2165
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
In drivers/usb/host/ehci-hcd.c (ffffffff816df720)
Location: drivers/usb/host/ehci-sched.c:2165
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
In drivers/usb/host/ehci-hcd.c (ffffffff8174c2ce)
Location: drivers/usb/host/ehci-sched.c:2152
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
In drivers/usb/host/ehci-hcd.c (ffffffff8178c6d4)
Location: drivers/usb/host/ehci-sched.c:2153
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
In drivers/usb/host/ehci-hcd.c (ffffffff817b2ed4)
Location: drivers/usb/host/ehci-sched.c:2151
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
In drivers/usb/host/ehci-hcd.c (ffffffff817efa7b)
Location: drivers/usb/host/ehci-sched.c:2151
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_submit
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
In drivers/usb/host/ehci-hcd.c (ffffffff8182096b)
Location: drivers/usb/host/ehci-sched.c:2151
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_submit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sitd_link_urb(struct ehci_hcd *ehci, struct urb *urb, unsigned int mod, struct ehci_iso_stream *stream);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818f01f0)
Location: drivers/usb/host/ehci-sched.c:2151
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:sitd_submit
```
**Symbols:**

```
ffffffff818f01f0-ffffffff818f043c: sitd_link_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sitd_link_urb(struct ehci_hcd *ehci, struct urb *urb, unsigned int mod, struct ehci_iso_stream *stream);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818f9510)
Location: drivers/usb/host/ehci-sched.c:2143
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:sitd_submit
```
**Symbols:**

```
ffffffff818f9510-ffffffff818f975c: sitd_link_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sitd_link_urb(struct ehci_hcd *ehci, struct urb *urb, unsigned int mod, struct ehci_iso_stream *stream);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818dc2f0)
Location: drivers/usb/host/ehci-sched.c:2143
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:sitd_submit
```
**Symbols:**

```
ffffffff818dc2f0-ffffffff818dc53b: sitd_link_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sitd_link_urb(struct ehci_hcd *ehci, struct urb *urb, unsigned int mod, struct ehci_iso_stream *stream);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81977d00)
Location: drivers/usb/host/ehci-sched.c:2143
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:sitd_submit
```
**Symbols:**

```
ffffffff81977d00-ffffffff81977f4b: sitd_link_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sitd_link_urb(struct ehci_hcd *ehci, struct urb *urb, unsigned int mod, struct ehci_iso_stream *stream);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81ad5550)
Location: drivers/usb/host/ehci-sched.c:2141
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:sitd_submit
```
**Symbols:**

```
ffffffff81ad5550-ffffffff81ad57b5: sitd_link_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sitd_link_urb(struct ehci_hcd *ehci, struct urb *urb, unsigned int mod, struct ehci_iso_stream *stream);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81c60540)
Location: drivers/usb/host/ehci-sched.c:2141
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:sitd_submit
```
**Symbols:**

```
ffffffff81c60540-ffffffff81c607a5: sitd_link_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sitd_link_urb(struct ehci_hcd *ehci, struct urb *urb, unsigned int mod, struct ehci_iso_stream *stream);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81cc7900)
Location: drivers/usb/host/ehci-sched.c:2141
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:sitd_submit
```
**Symbols:**

```
ffffffff81cc7900-ffffffff81cc7b65: sitd_link_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sitd_link_urb(struct ehci_hcd *ehci, struct urb *urb, unsigned int mod, struct ehci_iso_stream *stream);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81d7ce80)
Location: drivers/usb/host/ehci-sched.c:2142
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:sitd_submit
```
**Symbols:**

```
ffffffff81d7ce80-ffffffff81d7d0b0: sitd_link_urb (STB_LOCAL)
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
In drivers/usb/host/ehci-hcd.c (ffff800010a5bb2c)
Location: drivers/usb/host/ehci-sched.c:2151
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_submit
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
In drivers/usb/host/ehci-hcd.c (c0b2de04)
Location: drivers/usb/host/ehci-sched.c:2151
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_submit
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
In drivers/usb/host/ehci-hcd.c (c000000000b27234)
Location: drivers/usb/host/ehci-sched.c:2151
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_submit
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
In drivers/usb/host/ehci-hcd.c (ffffffe000673df4)
Location: drivers/usb/host/ehci-sched.c:2151
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_submit
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
In drivers/usb/host/ehci-hcd.c (ffffffff817d8d4b)
Location: drivers/usb/host/ehci-sched.c:2151
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_submit
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
In drivers/usb/host/ehci-hcd.c (ffffffff818157eb)
Location: drivers/usb/host/ehci-sched.c:2151
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_submit
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
In drivers/usb/host/ehci-hcd.c (ffffffff8182f83b)
Location: drivers/usb/host/ehci-sched.c:2151
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_submit
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
