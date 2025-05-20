# Function: <code>iso_stream_init</code>

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
In drivers/usb/host/ehci-hcd.c (ffffffff816383d6)
Location: drivers/usb/host/ehci-sched.c:1040
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
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
In drivers/usb/host/ehci-hcd.c (ffffffff816990f7)
Location: drivers/usb/host/ehci-sched.c:1042
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
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
In drivers/usb/host/ehci-hcd.c (ffffffff816c5017)
Location: drivers/usb/host/ehci-sched.c:1042
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
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
In drivers/usb/host/ehci-hcd.c (ffffffff816d979a)
Location: drivers/usb/host/ehci-sched.c:1042
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
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
In drivers/usb/host/ehci-hcd.c (ffffffff81745dea)
Location: drivers/usb/host/ehci-sched.c:1029
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
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
In drivers/usb/host/ehci-hcd.c (ffffffff8178663d)
Location: drivers/usb/host/ehci-sched.c:1030
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
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
In drivers/usb/host/ehci-hcd.c (ffffffff817af412)
Location: drivers/usb/host/ehci-sched.c:1030
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
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
In drivers/usb/host/ehci-hcd.c (ffffffff817edba7)
Location: drivers/usb/host/ehci-sched.c:1030
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
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
In drivers/usb/host/ehci-hcd.c (ffffffff8181ea87)
Location: drivers/usb/host/ehci-sched.c:1030
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void iso_stream_init(struct ehci_hcd *ehci, struct ehci_iso_stream *stream, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818ea290)
Location: drivers/usb/host/ehci-sched.c:1030
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
```
**Symbols:**

```
ffffffff818ea290-ffffffff818ea5b1: iso_stream_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void iso_stream_init(struct ehci_hcd *ehci, struct ehci_iso_stream *stream, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818f3180)
Location: drivers/usb/host/ehci-sched.c:1016
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
```
**Symbols:**

```
ffffffff818f3180-ffffffff818f34a1: iso_stream_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void iso_stream_init(struct ehci_hcd *ehci, struct ehci_iso_stream *stream, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818d6940)
Location: drivers/usb/host/ehci-sched.c:1016
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
```
**Symbols:**

```
ffffffff818d6940-ffffffff818d6c5c: iso_stream_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void iso_stream_init(struct ehci_hcd *ehci, struct ehci_iso_stream *stream, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci-sched.c:1016
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
```
**Symbols:**

```
ffffffff819716b0-ffffffff81971a18: iso_stream_init (STB_LOCAL)
ffffffff81d1e8c4-ffffffff81d1e92e: iso_stream_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void iso_stream_init(struct ehci_hcd *ehci, struct ehci_iso_stream *stream, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci-sched.c:1016
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
```
**Symbols:**

```
ffffffff81acc550-ffffffff81acc8d4: iso_stream_init (STB_LOCAL)
ffffffff81eea366-ffffffff81eea3d0: iso_stream_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void iso_stream_init(struct ehci_hcd *ehci, struct ehci_iso_stream *stream, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci-sched.c:1016
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
```
**Symbols:**

```
ffffffff81c56ce0-ffffffff81c57064: iso_stream_init (STB_LOCAL)
ffffffff820a5297-ffffffff820a5301: iso_stream_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void iso_stream_init(struct ehci_hcd *ehci, struct ehci_iso_stream *stream, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci-sched.c:1016
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
```
**Symbols:**

```
ffffffff81cbe380-ffffffff81cbe702: iso_stream_init (STB_LOCAL)
ffffffff821267bc-ffffffff82126826: iso_stream_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void iso_stream_init(struct ehci_hcd *ehci, struct ehci_iso_stream *stream, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci-sched.c:1017
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
```
**Symbols:**

```
ffffffff81d730f0-ffffffff81d73472: iso_stream_init (STB_LOCAL)
ffffffff82207fc5-ffffffff8220802f: iso_stream_init.cold (STB_LOCAL)
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
In drivers/usb/host/ehci-hcd.c (ffff800010a5a5ac)
Location: drivers/usb/host/ehci-sched.c:1030
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
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
In drivers/usb/host/ehci-hcd.c (c0b2bff0)
Location: drivers/usb/host/ehci-sched.c:1030
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
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
In drivers/usb/host/ehci-hcd.c (c000000000b1d414)
Location: drivers/usb/host/ehci-sched.c:1030
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
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
In drivers/usb/host/ehci-hcd.c (ffffffe000671e02)
Location: drivers/usb/host/ehci-sched.c:1030
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
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
In drivers/usb/host/ehci-hcd.c (ffffffff817d6e67)
Location: drivers/usb/host/ehci-sched.c:1030
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
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
In drivers/usb/host/ehci-hcd.c (ffffffff81813907)
Location: drivers/usb/host/ehci-sched.c:1030
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
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
In drivers/usb/host/ehci-hcd.c (ffffffff8182e7a7)
Location: drivers/usb/host/ehci-sched.c:1030
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
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
