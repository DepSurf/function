# Function: <code>itd_complete</code>

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
In drivers/usb/host/ehci-hcd.c (ffffffff816397ed)
Location: drivers/usb/host/ehci-sched.c:1845
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
In drivers/usb/host/ehci-hcd.c (ffffffff8169a4bd)
Location: drivers/usb/host/ehci-sched.c:1843
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
In drivers/usb/host/ehci-hcd.c (ffffffff816c859d)
Location: drivers/usb/host/ehci-sched.c:1842
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
In drivers/usb/host/ehci-hcd.c (ffffffff816dd225)
Location: drivers/usb/host/ehci-sched.c:1842
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
In drivers/usb/host/ehci-hcd.c (ffffffff81749965)
Location: drivers/usb/host/ehci-sched.c:1829
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
In drivers/usb/host/ehci-hcd.c (ffffffff81789be2)
Location: drivers/usb/host/ehci-sched.c:1830
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
In drivers/usb/host/ehci-hcd.c (ffffffff817ad832)
Location: drivers/usb/host/ehci-sched.c:1830
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
In drivers/usb/host/ehci-hcd.c (ffffffff817ec671)
Location: drivers/usb/host/ehci-sched.c:1830
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
In drivers/usb/host/ehci-hcd.c (ffffffff8181d541)
Location: drivers/usb/host/ehci-sched.c:1830
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
bool itd_complete(struct ehci_hcd *ehci, struct ehci_itd *itd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818f20e0)
Location: drivers/usb/host/ehci-sched.c:1830
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
```
**Symbols:**

```
ffffffff818f20e0-ffffffff818f23cc: itd_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool itd_complete(struct ehci_hcd *ehci, struct ehci_itd *itd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818fb000)
Location: drivers/usb/host/ehci-sched.c:1822
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
```
**Symbols:**

```
ffffffff818fb000-ffffffff818fb2ec: itd_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool itd_complete(struct ehci_hcd *ehci, struct ehci_itd *itd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818dddc0)
Location: drivers/usb/host/ehci-sched.c:1822
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
```
**Symbols:**

```
ffffffff818dddc0-ffffffff818de0ac: itd_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool itd_complete(struct ehci_hcd *ehci, struct ehci_itd *itd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff819798e0)
Location: drivers/usb/host/ehci-sched.c:1822
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
```
**Symbols:**

```
ffffffff819798e0-ffffffff81979c38: itd_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool itd_complete(struct ehci_hcd *ehci, struct ehci_itd *itd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81ad6fd0)
Location: drivers/usb/host/ehci-sched.c:1820
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
```
**Symbols:**

```
ffffffff81ad6fd0-ffffffff81ad7348: itd_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool itd_complete(struct ehci_hcd *ehci, struct ehci_itd *itd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81c61d60)
Location: drivers/usb/host/ehci-sched.c:1820
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
```
**Symbols:**

```
ffffffff81c61d60-ffffffff81c620d8: itd_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool itd_complete(struct ehci_hcd *ehci, struct ehci_itd *itd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81cc9100)
Location: drivers/usb/host/ehci-sched.c:1820
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
```
**Symbols:**

```
ffffffff81cc9100-ffffffff81cc94da: itd_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool itd_complete(struct ehci_hcd *ehci, struct ehci_itd *itd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81d7dfe0)
Location: drivers/usb/host/ehci-sched.c:1821
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
```
**Symbols:**

```
ffffffff81d7dfe0-ffffffff81d7e3ba: itd_complete (STB_LOCAL)
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
In drivers/usb/host/ehci-hcd.c (ffff800010a576cc)
Location: drivers/usb/host/ehci-sched.c:1830
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
In drivers/usb/host/ehci-hcd.c (c0b2a34c)
Location: drivers/usb/host/ehci-sched.c:1830
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
In drivers/usb/host/ehci-hcd.c (c000000000b252a4)
Location: drivers/usb/host/ehci-sched.c:1830
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
In drivers/usb/host/ehci-hcd.c (ffffffe000672a28)
Location: drivers/usb/host/ehci-sched.c:1830
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
In drivers/usb/host/ehci-hcd.c (ffffffff817d5921)
Location: drivers/usb/host/ehci-sched.c:1830
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
In drivers/usb/host/ehci-hcd.c (ffffffff818123c1)
Location: drivers/usb/host/ehci-sched.c:1830
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
In drivers/usb/host/ehci-hcd.c (ffffffff8182ce91)
Location: drivers/usb/host/ehci-sched.c:1830
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
