# Function: <code>ed_schedule</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ed_schedule(struct ohci_hcd *ohci, struct ed *ed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff8163e170)
Location: drivers/usb/host/ohci-q.c:182
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
**Symbols:**

```
ffffffff8163e170-ffffffff8163e4ec: ed_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ed_schedule(struct ohci_hcd *ohci, struct ed *ed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff8169ed90)
Location: drivers/usb/host/ohci-q.c:182
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
**Symbols:**

```
ffffffff8169ed90-ffffffff8169f106: ed_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ed_schedule(struct ohci_hcd *ohci, struct ed *ed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff816ccee0)
Location: drivers/usb/host/ohci-q.c:182
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
**Symbols:**

```
ffffffff816ccee0-ffffffff816cd256: ed_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ed_schedule(struct ohci_hcd *ohci, struct ed *ed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff816e13a0)
Location: drivers/usb/host/ohci-q.c:182
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
**Symbols:**

```
ffffffff816e13a0-ffffffff816e16f4: ed_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ed_schedule(struct ohci_hcd *ohci, struct ed *ed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff8174dba0)
Location: drivers/usb/host/ohci-q.c:183
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
**Symbols:**

```
ffffffff8174dba0-ffffffff8174def4: ed_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ed_schedule(struct ohci_hcd *ohci, struct ed *ed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff8178e3e0)
Location: drivers/usb/host/ohci-q.c:183
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
**Symbols:**

```
ffffffff8178e3e0-ffffffff8178e71d: ed_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ed_schedule(struct ohci_hcd *ohci, struct ed *ed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff817b4a60)
Location: drivers/usb/host/ohci-q.c:183
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
**Symbols:**

```
ffffffff817b4a60-ffffffff817b4d9d: ed_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ed_schedule(struct ohci_hcd *ohci, struct ed *ed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (0)
Location: drivers/usb/host/ohci-q.c:183
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
**Symbols:**

```
ffffffff817f4210-ffffffff817f452a: ed_schedule (STB_LOCAL)
ffffffff817f9a2a-ffffffff817f9a50: ed_schedule.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ed_schedule(struct ohci_hcd *ohci, struct ed *ed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81824e70)
Location: drivers/usb/host/ohci-q.c:183
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
**Symbols:**

```
ffffffff81824e70-ffffffff818251a3: ed_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ed_schedule(struct ohci_hcd *ohci, struct ed *ed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff818f6e10)
Location: drivers/usb/host/ohci-q.c:183
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
```
**Symbols:**

```
ffffffff818f6e10-ffffffff818f6ffd: ed_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ed_schedule(struct ohci_hcd *ohci, struct ed *ed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff818ff960)
Location: drivers/usb/host/ohci-q.c:183
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
```
**Symbols:**

```
ffffffff818ff960-ffffffff818ffb4d: ed_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ed_schedule(struct ohci_hcd *ohci, struct ed *ed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff818e2db0)
Location: drivers/usb/host/ohci-q.c:183
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
```
**Symbols:**

```
ffffffff818e2db0-ffffffff818e30d6: ed_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ed_schedule(struct ohci_hcd *ohci, struct ed *ed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff8197ef00)
Location: drivers/usb/host/ohci-q.c:183
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
```
**Symbols:**

```
ffffffff8197ef00-ffffffff8197f386: ed_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ed_schedule(struct ohci_hcd *ohci, struct ed *ed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81ada6b0)
Location: drivers/usb/host/ohci-q.c:183
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
```
**Symbols:**

```
ffffffff81ada6b0-ffffffff81adab5e: ed_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ed_schedule(struct ohci_hcd *ohci, struct ed *ed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81c658b0)
Location: drivers/usb/host/ohci-q.c:183
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
```
**Symbols:**

```
ffffffff81c658b0-ffffffff81c65d54: ed_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ed_schedule(struct ohci_hcd *ohci, struct ed *ed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81cccb30)
Location: drivers/usb/host/ohci-q.c:183
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
```
**Symbols:**

```
ffffffff81cccb30-ffffffff81cccfd5: ed_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ed_schedule(struct ohci_hcd *ohci, struct ed *ed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81d81a30)
Location: drivers/usb/host/ohci-q.c:183
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
```
**Symbols:**

```
ffffffff81d81a30-ffffffff81d81ed5: ed_schedule (STB_LOCAL)
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
int ed_schedule(struct ohci_hcd *ohci, struct ed *ed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffff800010a5f608)
Location: drivers/usb/host/ohci-q.c:183
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
**Symbols:**

```
ffff800010a5f608-ffff800010a5f98c: ed_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ed_schedule(struct ohci_hcd *ohci, struct ed *ed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (c0b315ac)
Location: drivers/usb/host/ohci-q.c:183
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
**Symbols:**

```
c0b315ac-c0b31990: ed_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ed_schedule(struct ohci_hcd *ohci, struct ed *ed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (c000000000b2d470)
Location: drivers/usb/host/ohci-q.c:183
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
**Symbols:**

```
c000000000b2d470-c000000000b2d8d8: ed_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ed_schedule(struct ohci_hcd *ohci, struct ed *ed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffe000679fee)
Location: drivers/usb/host/ohci-q.c:183
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
**Symbols:**

```
ffffffe000679fee-ffffffe00067a3a2: ed_schedule (STB_LOCAL)
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
int ed_schedule(struct ohci_hcd *ohci, struct ed *ed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff817dd250)
Location: drivers/usb/host/ohci-q.c:183
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
**Symbols:**

```
ffffffff817dd250-ffffffff817dd583: ed_schedule (STB_LOCAL)
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
int ed_schedule(struct ohci_hcd *ohci, struct ed *ed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81819cf0)
Location: drivers/usb/host/ohci-q.c:183
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
**Symbols:**

```
ffffffff81819cf0-ffffffff8181a023: ed_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ed_schedule(struct ohci_hcd *ohci, struct ed *ed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81833ce0)
Location: drivers/usb/host/ohci-q.c:183
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
**Symbols:**

```
ffffffff81833ce0-ffffffff81834013: ed_schedule (STB_LOCAL)
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
