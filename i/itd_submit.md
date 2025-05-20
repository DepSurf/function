# Function: <code>itd_submit</code>

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
In drivers/usb/host/ehci-hcd.c (ffffffff8163bb18)
Location: drivers/usb/host/ehci-sched.c:1939
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
In drivers/usb/host/ehci-hcd.c (ffffffff8169c7de)
Location: drivers/usb/host/ehci-sched.c:1938
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
In drivers/usb/host/ehci-hcd.c (ffffffff816ca8fe)
Location: drivers/usb/host/ehci-sched.c:1937
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
In drivers/usb/host/ehci-hcd.c (ffffffff816df00d)
Location: drivers/usb/host/ehci-sched.c:1937
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
In drivers/usb/host/ehci-hcd.c (ffffffff8174b75e)
Location: drivers/usb/host/ehci-sched.c:1924
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
In drivers/usb/host/ehci-hcd.c (ffffffff8178c3c4)
Location: drivers/usb/host/ehci-sched.c:1925
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
In drivers/usb/host/ehci-hcd.c (ffffffff817b2bc4)
Location: drivers/usb/host/ehci-sched.c:1923
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int itd_submit(struct ehci_hcd *ehci, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817efd40)
Location: drivers/usb/host/ehci-sched.c:1923
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
**Symbols:**

```
ffffffff817efd40-ffffffff817f0438: itd_submit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int itd_submit(struct ehci_hcd *ehci, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81820c30)
Location: drivers/usb/host/ehci-sched.c:1923
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
**Symbols:**

```
ffffffff81820c30-ffffffff81821328: itd_submit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int itd_submit(struct ehci_hcd *ehci, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818f10b0)
Location: drivers/usb/host/ehci-sched.c:1923
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
**Symbols:**

```
ffffffff818f10b0-ffffffff818f1251: itd_submit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int itd_submit(struct ehci_hcd *ehci, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818fa3d0)
Location: drivers/usb/host/ehci-sched.c:1915
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
**Symbols:**

```
ffffffff818fa3d0-ffffffff818fa571: itd_submit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int itd_submit(struct ehci_hcd *ehci, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818dd1b0)
Location: drivers/usb/host/ehci-sched.c:1915
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
**Symbols:**

```
ffffffff818dd1b0-ffffffff818dd351: itd_submit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int itd_submit(struct ehci_hcd *ehci, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81978d40)
Location: drivers/usb/host/ehci-sched.c:1915
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
**Symbols:**

```
ffffffff81978d40-ffffffff81978ed8: itd_submit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int itd_submit(struct ehci_hcd *ehci, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81ad6650)
Location: drivers/usb/host/ehci-sched.c:1913
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
**Symbols:**

```
ffffffff81ad6650-ffffffff81ad67e8: itd_submit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int itd_submit(struct ehci_hcd *ehci, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81c616c0)
Location: drivers/usb/host/ehci-sched.c:1913
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
**Symbols:**

```
ffffffff81c616c0-ffffffff81c61858: itd_submit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int itd_submit(struct ehci_hcd *ehci, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81cc8a60)
Location: drivers/usb/host/ehci-sched.c:1913
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
**Symbols:**

```
ffffffff81cc8a60-ffffffff81cc8bf8: itd_submit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int itd_submit(struct ehci_hcd *ehci, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81d7ccd0)
Location: drivers/usb/host/ehci-sched.c:1914
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
**Symbols:**

```
ffffffff81d7ccd0-ffffffff81d7ce68: itd_submit (STB_LOCAL)
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
int itd_submit(struct ehci_hcd *ehci, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffff800010a5b0a0)
Location: drivers/usb/host/ehci-sched.c:1923
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
**Symbols:**

```
ffff800010a5b0a0-ffff800010a5b7a0: itd_submit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int itd_submit(struct ehci_hcd *ehci, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (c0b2e0b4)
Location: drivers/usb/host/ehci-sched.c:1923
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
**Symbols:**

```
c0b2e0b4-c0b2e7e0: itd_submit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int itd_submit(struct ehci_hcd *ehci, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (c000000000b280b0)
Location: drivers/usb/host/ehci-sched.c:1923
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
**Symbols:**

```
c000000000b280b0-c000000000b2895c: itd_submit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int itd_submit(struct ehci_hcd *ehci, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffe0006735d4)
Location: drivers/usb/host/ehci-sched.c:1923
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
**Symbols:**

```
ffffffe0006735d4-ffffffe000673b66: itd_submit (STB_LOCAL)
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
int itd_submit(struct ehci_hcd *ehci, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817d9010)
Location: drivers/usb/host/ehci-sched.c:1923
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
**Symbols:**

```
ffffffff817d9010-ffffffff817d9708: itd_submit (STB_LOCAL)
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
int itd_submit(struct ehci_hcd *ehci, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81815ab0)
Location: drivers/usb/host/ehci-sched.c:1923
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
**Symbols:**

```
ffffffff81815ab0-ffffffff818161a8: itd_submit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int itd_submit(struct ehci_hcd *ehci, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff8182fb00)
Location: drivers/usb/host/ehci-sched.c:1923
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
**Symbols:**

```
ffffffff8182fb00-ffffffff818301f8: itd_submit (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
