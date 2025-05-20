# Function: <code>find_tt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct ehci_tt *find_tt(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81638e50)
Location: drivers/usb/host/ehci-sched.c:114
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:reserve_release_intr_bandwidth
  - drivers/usb/host/ehci-hcd.c:qh_schedule
  - drivers/usb/host/ehci-hcd.c:reserve_release_iso_bandwidth
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
```
**Symbols:**

```
ffffffff81638e50-ffffffff81638f79: find_tt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct ehci_tt *find_tt(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81699b10)
Location: drivers/usb/host/ehci-sched.c:114
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:reserve_release_iso_bandwidth
  - drivers/usb/host/ehci-hcd.c:qh_schedule
  - drivers/usb/host/ehci-hcd.c:reserve_release_intr_bandwidth
```
**Symbols:**

```
ffffffff81699b10-ffffffff81699c39: find_tt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct ehci_tt *find_tt(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff816c7bf0)
Location: drivers/usb/host/ehci-sched.c:114
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:reserve_release_iso_bandwidth
  - drivers/usb/host/ehci-hcd.c:qh_schedule
  - drivers/usb/host/ehci-hcd.c:reserve_release_intr_bandwidth
```
**Symbols:**

```
ffffffff816c7bf0-ffffffff816c7d19: find_tt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct ehci_tt *find_tt(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff816dc470)
Location: drivers/usb/host/ehci-sched.c:114
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:reserve_release_iso_bandwidth
  - drivers/usb/host/ehci-hcd.c:qh_schedule
  - drivers/usb/host/ehci-hcd.c:reserve_release_intr_bandwidth
```
**Symbols:**

```
ffffffff816dc470-ffffffff816dc5ac: find_tt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct ehci_tt *find_tt(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81748ba0)
Location: drivers/usb/host/ehci-sched.c:101
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:reserve_release_iso_bandwidth
  - drivers/usb/host/ehci-hcd.c:qh_schedule
  - drivers/usb/host/ehci-hcd.c:reserve_release_intr_bandwidth
```
**Symbols:**

```
ffffffff81748ba0-ffffffff81748cdc: find_tt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct ehci_tt *find_tt(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81788c00)
Location: drivers/usb/host/ehci-sched.c:101
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:reserve_release_iso_bandwidth
  - drivers/usb/host/ehci-hcd.c:qh_schedule
  - drivers/usb/host/ehci-hcd.c:reserve_release_intr_bandwidth
```
**Symbols:**

```
ffffffff81788c00-ffffffff81788d4a: find_tt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct ehci_tt *find_tt(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817ab5c0)
Location: drivers/usb/host/ehci-sched.c:101
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:reserve_release_iso_bandwidth
  - drivers/usb/host/ehci-hcd.c:qh_schedule
  - drivers/usb/host/ehci-hcd.c:reserve_release_intr_bandwidth
```
**Symbols:**

```
ffffffff817ab5c0-ffffffff817ab70a: find_tt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct ehci_tt *find_tt(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817ea7c0)
Location: drivers/usb/host/ehci-sched.c:101
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:reserve_release_iso_bandwidth
  - drivers/usb/host/ehci-hcd.c:qh_schedule
  - drivers/usb/host/ehci-hcd.c:reserve_release_intr_bandwidth
```
**Symbols:**

```
ffffffff817ea7c0-ffffffff817ea90d: find_tt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct ehci_tt *find_tt(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff8181b690)
Location: drivers/usb/host/ehci-sched.c:101
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:reserve_release_iso_bandwidth
  - drivers/usb/host/ehci-hcd.c:qh_schedule
  - drivers/usb/host/ehci-hcd.c:reserve_release_intr_bandwidth
```
**Symbols:**

```
ffffffff8181b690-ffffffff8181b7dd: find_tt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct ehci_tt *find_tt(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818ecba0)
Location: drivers/usb/host/ehci-sched.c:101
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:reserve_release_iso_bandwidth
  - drivers/usb/host/ehci-hcd.c:qh_schedule
  - drivers/usb/host/ehci-hcd.c:reserve_release_intr_bandwidth
```
**Symbols:**

```
ffffffff818ecba0-ffffffff818ecced: find_tt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct ehci_tt *find_tt(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818f5a30)
Location: drivers/usb/host/ehci-sched.c:101
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:reserve_release_iso_bandwidth
  - drivers/usb/host/ehci-hcd.c:qh_schedule
  - drivers/usb/host/ehci-hcd.c:reserve_release_intr_bandwidth
```
**Symbols:**

```
ffffffff818f5a30-ffffffff818f5b77: find_tt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct ehci_tt *find_tt(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818d92d0)
Location: drivers/usb/host/ehci-sched.c:101
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:reserve_release_iso_bandwidth
  - drivers/usb/host/ehci-hcd.c:qh_schedule
  - drivers/usb/host/ehci-hcd.c:reserve_release_intr_bandwidth
```
**Symbols:**

```
ffffffff818d92d0-ffffffff818d9417: find_tt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct ehci_tt *find_tt(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81974580)
Location: drivers/usb/host/ehci-sched.c:101
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:reserve_release_iso_bandwidth
  - drivers/usb/host/ehci-hcd.c:qh_schedule
  - drivers/usb/host/ehci-hcd.c:reserve_release_intr_bandwidth
```
**Symbols:**

```
ffffffff81974580-ffffffff819746c7: find_tt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct ehci_tt *find_tt(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81acf5a0)
Location: drivers/usb/host/ehci-sched.c:101
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:reserve_release_iso_bandwidth
  - drivers/usb/host/ehci-hcd.c:qh_schedule
  - drivers/usb/host/ehci-hcd.c:reserve_release_intr_bandwidth
```
**Symbols:**

```
ffffffff81acf5a0-ffffffff81acf6ff: find_tt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct ehci_tt *find_tt(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81c59ed0)
Location: drivers/usb/host/ehci-sched.c:101
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:reserve_release_iso_bandwidth
  - drivers/usb/host/ehci-hcd.c:qh_schedule
  - drivers/usb/host/ehci-hcd.c:reserve_release_intr_bandwidth
```
**Symbols:**

```
ffffffff81c59ed0-ffffffff81c5a02f: find_tt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct ehci_tt *find_tt(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81cc1590)
Location: drivers/usb/host/ehci-sched.c:101
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:reserve_release_iso_bandwidth
  - drivers/usb/host/ehci-hcd.c:qh_schedule
  - drivers/usb/host/ehci-hcd.c:reserve_release_intr_bandwidth
```
**Symbols:**

```
ffffffff81cc1590-ffffffff81cc16ef: find_tt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct ehci_tt *find_tt(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81d761f0)
Location: drivers/usb/host/ehci-sched.c:101
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:reserve_release_iso_bandwidth
  - drivers/usb/host/ehci-hcd.c:qh_schedule
  - drivers/usb/host/ehci-hcd.c:reserve_release_intr_bandwidth
```
**Symbols:**

```
ffffffff81d761f0-ffffffff81d76385: find_tt (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline ⚠️</summary>

```c
struct ehci_tt *find_tt(struct usb_device *udev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffff800010a53800)
Location: drivers/usb/host/ehci-sched.c:101
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:reserve_release_iso_bandwidth
  - drivers/usb/host/ehci-hcd.c:qh_schedule
  - drivers/usb/host/ehci-hcd.c:reserve_release_intr_bandwidth
```
```
In drivers/usb/host/xhci-mtk-sch.c (ffff800010a8e0a0)
Location: drivers/usb/host/xhci-mtk-sch.c:84
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_add_ep_quirk
```
**Symbols:**

```
ffff800010a53800-ffff800010a53930: find_tt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
struct ehci_tt *find_tt(struct usb_device *udev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (c0b27c88)
Location: drivers/usb/host/ehci-sched.c:101
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:reserve_release_iso_bandwidth
  - drivers/usb/host/ehci-hcd.c:qh_schedule
  - drivers/usb/host/ehci-hcd.c:reserve_release_intr_bandwidth
```
```
In drivers/usb/host/xhci-mtk-sch.c (c0b607d0)
Location: drivers/usb/host/xhci-mtk-sch.c:84
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_add_ep_quirk
```
**Symbols:**

```
c0b27c88-c0b27db0: find_tt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct ehci_tt *find_tt(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (c000000000b21b30)
Location: drivers/usb/host/ehci-sched.c:101
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:reserve_release_iso_bandwidth
  - drivers/usb/host/ehci-hcd.c:qh_schedule
  - drivers/usb/host/ehci-hcd.c:reserve_release_intr_bandwidth
```
**Symbols:**

```
c000000000b21b30-c000000000b21d10: find_tt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct ehci_tt *find_tt(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffe000670f88)
Location: drivers/usb/host/ehci-sched.c:101
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:reserve_release_iso_bandwidth
  - drivers/usb/host/ehci-hcd.c:qh_schedule
  - drivers/usb/host/ehci-hcd.c:reserve_release_intr_bandwidth
```
**Symbols:**

```
ffffffe000670f88-ffffffe000671084: find_tt (STB_LOCAL)
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
struct ehci_tt *find_tt(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817d3a70)
Location: drivers/usb/host/ehci-sched.c:101
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:reserve_release_iso_bandwidth
  - drivers/usb/host/ehci-hcd.c:qh_schedule
  - drivers/usb/host/ehci-hcd.c:reserve_release_intr_bandwidth
```
**Symbols:**

```
ffffffff817d3a70-ffffffff817d3bbd: find_tt (STB_LOCAL)
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
struct ehci_tt *find_tt(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81810510)
Location: drivers/usb/host/ehci-sched.c:101
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:reserve_release_iso_bandwidth
  - drivers/usb/host/ehci-hcd.c:qh_schedule
  - drivers/usb/host/ehci-hcd.c:reserve_release_intr_bandwidth
```
**Symbols:**

```
ffffffff81810510-ffffffff8181065d: find_tt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct ehci_tt *find_tt(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff8182afe0)
Location: drivers/usb/host/ehci-sched.c:101
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:reserve_release_iso_bandwidth
  - drivers/usb/host/ehci-hcd.c:qh_schedule
  - drivers/usb/host/ehci-hcd.c:reserve_release_intr_bandwidth
```
**Symbols:**

```
ffffffff8182afe0-ffffffff8182b12d: find_tt (STB_LOCAL)
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
