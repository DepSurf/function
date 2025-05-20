# Function: <code>sitd_urb_transaction</code>

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
In drivers/usb/host/ehci-hcd.c (ffffffff8163bcb5)
Location: drivers/usb/host/ehci-sched.c:2057
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
In drivers/usb/host/ehci-hcd.c (ffffffff8169cf92)
Location: drivers/usb/host/ehci-sched.c:2056
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
In drivers/usb/host/ehci-hcd.c (ffffffff816cb0b2)
Location: drivers/usb/host/ehci-sched.c:2055
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
In drivers/usb/host/ehci-hcd.c (ffffffff816df7d6)
Location: drivers/usb/host/ehci-sched.c:2055
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
In drivers/usb/host/ehci-hcd.c (ffffffff8174bf77)
Location: drivers/usb/host/ehci-sched.c:2042
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
In drivers/usb/host/ehci-hcd.c (ffffffff8178c03d)
Location: drivers/usb/host/ehci-sched.c:2043
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
In drivers/usb/host/ehci-hcd.c (ffffffff817b283d)
Location: drivers/usb/host/ehci-sched.c:2041
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
In drivers/usb/host/ehci-hcd.c (ffffffff817ef763)
Location: drivers/usb/host/ehci-sched.c:2041
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
In drivers/usb/host/ehci-hcd.c (ffffffff81820653)
Location: drivers/usb/host/ehci-sched.c:2041
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
int sitd_urb_transaction(struct ehci_iso_stream *stream, struct ehci_hcd *ehci, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818eea00)
Location: drivers/usb/host/ehci-sched.c:2041
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:sitd_submit
```
**Symbols:**

```
ffffffff818eea00-ffffffff818eed0a: sitd_urb_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sitd_urb_transaction(struct ehci_iso_stream *stream, struct ehci_hcd *ehci, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818f7920)
Location: drivers/usb/host/ehci-sched.c:2033
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:sitd_submit
```
**Symbols:**

```
ffffffff818f7920-ffffffff818f7c2a: sitd_urb_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sitd_urb_transaction(struct ehci_iso_stream *stream, struct ehci_hcd *ehci, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818dafd0)
Location: drivers/usb/host/ehci-sched.c:2033
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:sitd_submit
```
**Symbols:**

```
ffffffff818dafd0-ffffffff818db2da: sitd_urb_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sitd_urb_transaction(struct ehci_iso_stream *stream, struct ehci_hcd *ehci, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff819765f0)
Location: drivers/usb/host/ehci-sched.c:2033
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:sitd_submit
```
**Symbols:**

```
ffffffff819765f0-ffffffff819768fa: sitd_urb_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sitd_urb_transaction(struct ehci_iso_stream *stream, struct ehci_hcd *ehci, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81ad2290)
Location: drivers/usb/host/ehci-sched.c:2031
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:sitd_submit
```
**Symbols:**

```
ffffffff81ad2290-ffffffff81ad25ae: sitd_urb_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sitd_urb_transaction(struct ehci_iso_stream *stream, struct ehci_hcd *ehci, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81c5ce90)
Location: drivers/usb/host/ehci-sched.c:2031
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:sitd_submit
```
**Symbols:**

```
ffffffff81c5ce90-ffffffff81c5d1bb: sitd_urb_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sitd_urb_transaction(struct ehci_iso_stream *stream, struct ehci_hcd *ehci, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81cc4510)
Location: drivers/usb/host/ehci-sched.c:2031
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:sitd_submit
```
**Symbols:**

```
ffffffff81cc4510-ffffffff81cc4831: sitd_urb_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sitd_urb_transaction(struct ehci_iso_stream *stream, struct ehci_hcd *ehci, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81d79400)
Location: drivers/usb/host/ehci-sched.c:2032
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:sitd_submit
```
**Symbols:**

```
ffffffff81d79400-ffffffff81d79721: sitd_urb_transaction (STB_LOCAL)
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
In drivers/usb/host/ehci-hcd.c (ffff800010a5b800)
Location: drivers/usb/host/ehci-sched.c:2041
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
In drivers/usb/host/ehci-hcd.c (c0b2da9c)
Location: drivers/usb/host/ehci-sched.c:2041
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
In drivers/usb/host/ehci-hcd.c (c000000000b26ec8)
Location: drivers/usb/host/ehci-sched.c:2041
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
In drivers/usb/host/ehci-hcd.c (ffffffe000673bb2)
Location: drivers/usb/host/ehci-sched.c:2041
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
In drivers/usb/host/ehci-hcd.c (ffffffff817d8a33)
Location: drivers/usb/host/ehci-sched.c:2041
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
In drivers/usb/host/ehci-hcd.c (ffffffff818154d3)
Location: drivers/usb/host/ehci-sched.c:2041
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
In drivers/usb/host/ehci-hcd.c (ffffffff8182f523)
Location: drivers/usb/host/ehci-sched.c:2041
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
