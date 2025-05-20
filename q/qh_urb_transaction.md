# Function: <code>qh_urb_transaction</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct list_head *qh_urb_transaction(struct ehci_hcd *ehci, struct urb *urb, struct list_head *head, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81634f10)
Location: drivers/usb/host/ehci-q.c:573
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
**Symbols:**

```
ffffffff81634f10-ffffffff816353bb: qh_urb_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct list_head *qh_urb_transaction(struct ehci_hcd *ehci, struct urb *urb, struct list_head *head, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81695780)
Location: drivers/usb/host/ehci-q.c:582
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
**Symbols:**

```
ffffffff81695780-ffffffff81695c2b: qh_urb_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct list_head *qh_urb_transaction(struct ehci_hcd *ehci, struct urb *urb, struct list_head *head, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff816c2650)
Location: drivers/usb/host/ehci-q.c:577
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
**Symbols:**

```
ffffffff816c2650-ffffffff816c2afb: qh_urb_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct list_head *qh_urb_transaction(struct ehci_hcd *ehci, struct urb *urb, struct list_head *head, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff816d8040)
Location: drivers/usb/host/ehci-q.c:577
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
**Symbols:**

```
ffffffff816d8040-ffffffff816d84a5: qh_urb_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct list_head *qh_urb_transaction(struct ehci_hcd *ehci, struct urb *urb, struct list_head *head, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81744770)
Location: drivers/usb/host/ehci-q.c:564
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
**Symbols:**

```
ffffffff81744770-ffffffff81744bd5: qh_urb_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct list_head *qh_urb_transaction(struct ehci_hcd *ehci, struct urb *urb, struct list_head *head, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81784910)
Location: drivers/usb/host/ehci-q.c:564
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
**Symbols:**

```
ffffffff81784910-ffffffff81784d75: qh_urb_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct list_head *qh_urb_transaction(struct ehci_hcd *ehci, struct urb *urb, struct list_head *head, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817acf70)
Location: drivers/usb/host/ehci-q.c:564
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
**Symbols:**

```
ffffffff817acf70-ffffffff817ad3c7: qh_urb_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct list_head *qh_urb_transaction(struct ehci_hcd *ehci, struct urb *urb, struct list_head *head, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci-q.c:564
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
**Symbols:**

```
ffffffff817ec110-ffffffff817ec557: qh_urb_transaction (STB_LOCAL)
ffffffff817f2adb-ffffffff817f2b1d: qh_urb_transaction.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct list_head *qh_urb_transaction(struct ehci_hcd *ehci, struct urb *urb, struct list_head *head, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff8181cfe0)
Location: drivers/usb/host/ehci-q.c:575
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
**Symbols:**

```
ffffffff8181cfe0-ffffffff8181d42b: qh_urb_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct list_head *qh_urb_transaction(struct ehci_hcd *ehci, struct urb *urb, struct list_head *head, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818ee560)
Location: drivers/usb/host/ehci-q.c:575
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
**Symbols:**

```
ffffffff818ee560-ffffffff818ee9f1: qh_urb_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct list_head *qh_urb_transaction(struct ehci_hcd *ehci, struct urb *urb, struct list_head *head, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818f7480)
Location: drivers/usb/host/ehci-q.c:575
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
**Symbols:**

```
ffffffff818f7480-ffffffff818f7911: qh_urb_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct list_head *qh_urb_transaction(struct ehci_hcd *ehci, struct urb *urb, struct list_head *head, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818dab40)
Location: drivers/usb/host/ehci-q.c:575
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
**Symbols:**

```
ffffffff818dab40-ffffffff818dafcf: qh_urb_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct list_head *qh_urb_transaction(struct ehci_hcd *ehci, struct urb *urb, struct list_head *head, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81976160)
Location: drivers/usb/host/ehci-q.c:575
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
**Symbols:**

```
ffffffff81976160-ffffffff819765ef: qh_urb_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct list_head *qh_urb_transaction(struct ehci_hcd *ehci, struct urb *urb, struct list_head *head, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81ad1e30)
Location: drivers/usb/host/ehci-q.c:576
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
**Symbols:**

```
ffffffff81ad1e30-ffffffff81ad2288: qh_urb_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct list_head *qh_urb_transaction(struct ehci_hcd *ehci, struct urb *urb, struct list_head *head, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81c5ca80)
Location: drivers/usb/host/ehci-q.c:576
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
**Symbols:**

```
ffffffff81c5ca80-ffffffff81c5ce71: qh_urb_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct list_head *qh_urb_transaction(struct ehci_hcd *ehci, struct urb *urb, struct list_head *head, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81cc4100)
Location: drivers/usb/host/ehci-q.c:576
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
**Symbols:**

```
ffffffff81cc4100-ffffffff81cc44ff: qh_urb_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct list_head *qh_urb_transaction(struct ehci_hcd *ehci, struct urb *urb, struct list_head *head, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81d78ff0)
Location: drivers/usb/host/ehci-q.c:576
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
**Symbols:**

```
ffffffff81d78ff0-ffffffff81d793ef: qh_urb_transaction (STB_LOCAL)
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
struct list_head *qh_urb_transaction(struct ehci_hcd *ehci, struct urb *urb, struct list_head *head, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffff800010a548b8)
Location: drivers/usb/host/ehci-q.c:575
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
**Symbols:**

```
ffff800010a548b8-ffff800010a54ca0: qh_urb_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct list_head *qh_urb_transaction(struct ehci_hcd *ehci, struct urb *urb, struct list_head *head, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (c0b29644)
Location: drivers/usb/host/ehci-q.c:575
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
**Symbols:**

```
c0b29644-c0b29a94: qh_urb_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct list_head *qh_urb_transaction(struct ehci_hcd *ehci, struct urb *urb, struct list_head *head, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (c000000000b1e220)
Location: drivers/usb/host/ehci-q.c:575
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
**Symbols:**

```
c000000000b1e220-c000000000b1e6e0: qh_urb_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct list_head *qh_urb_transaction(struct ehci_hcd *ehci, struct urb *urb, struct list_head *head, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffe00066f660)
Location: drivers/usb/host/ehci-q.c:575
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
**Symbols:**

```
ffffffe00066f660-ffffffe00066f998: qh_urb_transaction (STB_LOCAL)
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
struct list_head *qh_urb_transaction(struct ehci_hcd *ehci, struct urb *urb, struct list_head *head, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817d53c0)
Location: drivers/usb/host/ehci-q.c:575
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
**Symbols:**

```
ffffffff817d53c0-ffffffff817d580b: qh_urb_transaction (STB_LOCAL)
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
struct list_head *qh_urb_transaction(struct ehci_hcd *ehci, struct urb *urb, struct list_head *head, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81811e60)
Location: drivers/usb/host/ehci-q.c:575
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
**Symbols:**

```
ffffffff81811e60-ffffffff818122ab: qh_urb_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct list_head *qh_urb_transaction(struct ehci_hcd *ehci, struct urb *urb, struct list_head *head, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff8182c930)
Location: drivers/usb/host/ehci-q.c:575
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
**Symbols:**

```
ffffffff8182c930-ffffffff8182cd7b: qh_urb_transaction (STB_LOCAL)
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
