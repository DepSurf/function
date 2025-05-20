# Function: <code>sitd_complete</code>

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
In drivers/usb/host/ehci-hcd.c (ffffffff81639816)
Location: drivers/usb/host/ehci-sched.c:2240
Inline: True
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
In drivers/usb/host/ehci-hcd.c (ffffffff8169a6ae)
Location: drivers/usb/host/ehci-sched.c:2239
Inline: True
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
In drivers/usb/host/ehci-hcd.c (ffffffff816c878e)
Location: drivers/usb/host/ehci-sched.c:2238
Inline: True
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
In drivers/usb/host/ehci-hcd.c (ffffffff816dd3bb)
Location: drivers/usb/host/ehci-sched.c:2238
Inline: True
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
In drivers/usb/host/ehci-hcd.c (ffffffff81749af8)
Location: drivers/usb/host/ehci-sched.c:2225
Inline: True
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
In drivers/usb/host/ehci-hcd.c (ffffffff817899e5)
Location: drivers/usb/host/ehci-sched.c:2226
Inline: True
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
In drivers/usb/host/ehci-hcd.c (ffffffff817ad635)
Location: drivers/usb/host/ehci-sched.c:2224
Inline: True
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
In drivers/usb/host/ehci-hcd.c (ffffffff817ec7c2)
Location: drivers/usb/host/ehci-sched.c:2224
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
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
In drivers/usb/host/ehci-hcd.c (ffffffff8181d692)
Location: drivers/usb/host/ehci-sched.c:2224
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool sitd_complete(struct ehci_hcd *ehci, struct ehci_sitd *sitd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818f1e60)
Location: drivers/usb/host/ehci-sched.c:2224
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
```
**Symbols:**

```
ffffffff818f1e60-ffffffff818f20d2: sitd_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool sitd_complete(struct ehci_hcd *ehci, struct ehci_sitd *sitd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818fad80)
Location: drivers/usb/host/ehci-sched.c:2216
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
```
**Symbols:**

```
ffffffff818fad80-ffffffff818faff2: sitd_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool sitd_complete(struct ehci_hcd *ehci, struct ehci_sitd *sitd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818ddb40)
Location: drivers/usb/host/ehci-sched.c:2216
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
```
**Symbols:**

```
ffffffff818ddb40-ffffffff818dddb2: sitd_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool sitd_complete(struct ehci_hcd *ehci, struct ehci_sitd *sitd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81979660)
Location: drivers/usb/host/ehci-sched.c:2216
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
```
**Symbols:**

```
ffffffff81979660-ffffffff819798d2: sitd_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool sitd_complete(struct ehci_hcd *ehci, struct ehci_sitd *sitd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81ad6d50)
Location: drivers/usb/host/ehci-sched.c:2214
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
```
**Symbols:**

```
ffffffff81ad6d50-ffffffff81ad6fcf: sitd_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool sitd_complete(struct ehci_hcd *ehci, struct ehci_sitd *sitd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81c61ad0)
Location: drivers/usb/host/ehci-sched.c:2214
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
```
**Symbols:**

```
ffffffff81c61ad0-ffffffff81c61d4f: sitd_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool sitd_complete(struct ehci_hcd *ehci, struct ehci_sitd *sitd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81cc8e70)
Location: drivers/usb/host/ehci-sched.c:2214
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
```
**Symbols:**

```
ffffffff81cc8e70-ffffffff81cc90f0: sitd_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool sitd_complete(struct ehci_hcd *ehci, struct ehci_sitd *sitd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81d7dd50)
Location: drivers/usb/host/ehci-sched.c:2215
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
```
**Symbols:**

```
ffffffff81d7dd50-ffffffff81d7dfd0: sitd_complete (STB_LOCAL)
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
In drivers/usb/host/ehci-hcd.c (ffff800010a57828)
Location: drivers/usb/host/ehci-sched.c:2224
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
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
In drivers/usb/host/ehci-hcd.c (c0b2a43c)
Location: drivers/usb/host/ehci-sched.c:2224
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
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
In drivers/usb/host/ehci-hcd.c (c000000000b254a0)
Location: drivers/usb/host/ehci-sched.c:2224
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
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
In drivers/usb/host/ehci-hcd.c (ffffffe000672a20)
Location: drivers/usb/host/ehci-sched.c:2224
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
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
In drivers/usb/host/ehci-hcd.c (ffffffff817d5a72)
Location: drivers/usb/host/ehci-sched.c:2224
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
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
In drivers/usb/host/ehci-hcd.c (ffffffff81812512)
Location: drivers/usb/host/ehci-sched.c:2224
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
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
In drivers/usb/host/ehci-hcd.c (ffffffff8182cfe2)
Location: drivers/usb/host/ehci-sched.c:2224
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
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
