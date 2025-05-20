# Function: <code>ehci_urb_done</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ehci_urb_done(struct ehci_hcd *ehci, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff816315b0)
Location: drivers/usb/host/ehci-q.c:249
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
**Symbols:**

```
ffffffff816315b0-ffffffff81631632: ehci_urb_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ehci_urb_done(struct ehci_hcd *ehci, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81692180)
Location: drivers/usb/host/ehci-q.c:253
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
**Symbols:**

```
ffffffff81692180-ffffffff81692202: ehci_urb_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ehci_urb_done(struct ehci_hcd *ehci, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff816c0260)
Location: drivers/usb/host/ehci-q.c:253
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
**Symbols:**

```
ffffffff816c0260-ffffffff816c02e2: ehci_urb_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ehci_urb_done(struct ehci_hcd *ehci, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff816d4c30)
Location: drivers/usb/host/ehci-q.c:253
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
**Symbols:**

```
ffffffff816d4c30-ffffffff816d4ca9: ehci_urb_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ehci_urb_done(struct ehci_hcd *ehci, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81741320)
Location: drivers/usb/host/ehci-q.c:240
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
**Symbols:**

```
ffffffff81741320-ffffffff81741399: ehci_urb_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ehci_urb_done(struct ehci_hcd *ehci, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81781fa0)
Location: drivers/usb/host/ehci-q.c:240
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
**Symbols:**

```
ffffffff81781fa0-ffffffff81782019: ehci_urb_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ehci_urb_done(struct ehci_hcd *ehci, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817a87c0)
Location: drivers/usb/host/ehci-q.c:240
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
**Symbols:**

```
ffffffff817a87c0-ffffffff817a8839: ehci_urb_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ehci_urb_done(struct ehci_hcd *ehci, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817e7a20)
Location: drivers/usb/host/ehci-q.c:240
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
**Symbols:**

```
ffffffff817e7a20-ffffffff817e7a9a: ehci_urb_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ehci_urb_done(struct ehci_hcd *ehci, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818188e0)
Location: drivers/usb/host/ehci-q.c:251
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
**Symbols:**

```
ffffffff818188e0-ffffffff8181895a: ehci_urb_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ehci_urb_done(struct ehci_hcd *ehci, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818e9a40)
Location: drivers/usb/host/ehci-q.c:251
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
**Symbols:**

```
ffffffff818e9a40-ffffffff818e9aba: ehci_urb_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ehci_urb_done(struct ehci_hcd *ehci, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818f2930)
Location: drivers/usb/host/ehci-q.c:251
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
**Symbols:**

```
ffffffff818f2930-ffffffff818f29aa: ehci_urb_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ehci_urb_done(struct ehci_hcd *ehci, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818d60f0)
Location: drivers/usb/host/ehci-q.c:251
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
**Symbols:**

```
ffffffff818d60f0-ffffffff818d616a: ehci_urb_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ehci_urb_done(struct ehci_hcd *ehci, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81970d90)
Location: drivers/usb/host/ehci-q.c:251
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
**Symbols:**

```
ffffffff81970d90-ffffffff81970e0a: ehci_urb_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ehci_urb_done(struct ehci_hcd *ehci, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81acbba0)
Location: drivers/usb/host/ehci-q.c:252
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
**Symbols:**

```
ffffffff81acbba0-ffffffff81acbc25: ehci_urb_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ehci_urb_done(struct ehci_hcd *ehci, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81c56310)
Location: drivers/usb/host/ehci-q.c:252
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
**Symbols:**

```
ffffffff81c56310-ffffffff81c56395: ehci_urb_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ehci_urb_done(struct ehci_hcd *ehci, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81cbd940)
Location: drivers/usb/host/ehci-q.c:252
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
**Symbols:**

```
ffffffff81cbd940-ffffffff81cbd9c5: ehci_urb_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ehci_urb_done(struct ehci_hcd *ehci, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81d726b0)
Location: drivers/usb/host/ehci-q.c:252
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
**Symbols:**

```
ffffffff81d726b0-ffffffff81d72735: ehci_urb_done (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void ehci_urb_done(struct ehci_hcd *ehci, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffff800010a51c38)
Location: drivers/usb/host/ehci-q.c:251
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
**Symbols:**

```
ffff800010a51c38-ffff800010a51ce0: ehci_urb_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ehci_urb_done(struct ehci_hcd *ehci, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (c0b24978)
Location: drivers/usb/host/ehci-q.c:251
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
**Symbols:**

```
c0b24978-c0b24a04: ehci_urb_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ehci_urb_done(struct ehci_hcd *ehci, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (c000000000b1b0a0)
Location: drivers/usb/host/ehci-q.c:251
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
**Symbols:**

```
c000000000b1b0a0-c000000000b1b19c: ehci_urb_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ehci_urb_done(struct ehci_hcd *ehci, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffe00066e396)
Location: drivers/usb/host/ehci-q.c:251
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
**Symbols:**

```
ffffffe00066e396-ffffffe00066e42e: ehci_urb_done (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void ehci_urb_done(struct ehci_hcd *ehci, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817d0cc0)
Location: drivers/usb/host/ehci-q.c:251
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
**Symbols:**

```
ffffffff817d0cc0-ffffffff817d0d3a: ehci_urb_done (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ehci_urb_done(struct ehci_hcd *ehci, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff8180d760)
Location: drivers/usb/host/ehci-q.c:251
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
**Symbols:**

```
ffffffff8180d760-ffffffff8180d7da: ehci_urb_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ehci_urb_done(struct ehci_hcd *ehci, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81827df0)
Location: drivers/usb/host/ehci-q.c:251
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:qh_completions
  - drivers/usb/host/ehci-hcd.c:qh_completions
```
**Symbols:**

```
ffffffff81827df0-ffffffff81827e6a: ehci_urb_done (STB_LOCAL)
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
