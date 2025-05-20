# Function: <code>periodic_unlink</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff816394ad)
Location: drivers/usb/host/ehci-sched.c:76
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff8163dc32)
Location: drivers/usb/host/ohci-q.c:268
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff8169a165)
Location: drivers/usb/host/ehci-sched.c:76
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff8169e862)
Location: drivers/usb/host/ohci-q.c:269
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff816c8245)
Location: drivers/usb/host/ehci-sched.c:76
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff816cc9b2)
Location: drivers/usb/host/ohci-q.c:269
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff816dccad)
Location: drivers/usb/host/ehci-sched.c:76
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff816e1162)
Location: drivers/usb/host/ohci-q.c:269
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817493e1)
Location: drivers/usb/host/ehci-sched.c:63
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff8174d966)
Location: drivers/usb/host/ohci-q.c:270
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81789433)
Location: drivers/usb/host/ehci-sched.c:63
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff8178e1aa)
Location: drivers/usb/host/ohci-q.c:270
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817abf83)
Location: drivers/usb/host/ehci-sched.c:63
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff817b482a)
Location: drivers/usb/host/ohci-q.c:270
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817eb19c)
Location: drivers/usb/host/ehci-sched.c:63
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff817f3df9)
Location: drivers/usb/host/ohci-q.c:270
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff8181c06c)
Location: drivers/usb/host/ehci-sched.c:63
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81824c39)
Location: drivers/usb/host/ohci-q.c:270
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision ⚠️</summary>

```c
void periodic_unlink(struct ehci_hcd *ehci, unsigned int frame, void *ptr);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818e9410)
Location: drivers/usb/host/ehci-sched.c:63
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:qh_unlink_periodic
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff818f6b00)
Location: drivers/usb/host/ohci-q.c:270
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
```
**Symbols:**

```
ffffffff818e9410-ffffffff818e9531: periodic_unlink (STB_LOCAL)
ffffffff818f6b00-ffffffff818f6bf0: periodic_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
void periodic_unlink(struct ehci_hcd *ehci, unsigned int frame, void *ptr);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818f2320)
Location: drivers/usb/host/ehci-sched.c:63
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:qh_unlink_periodic
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff818ff650)
Location: drivers/usb/host/ohci-q.c:270
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
```
**Symbols:**

```
ffffffff818f2320-ffffffff818f2441: periodic_unlink (STB_LOCAL)
ffffffff818ff650-ffffffff818ff740: periodic_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818d5ce1)
Location: drivers/usb/host/ehci-sched.c:63
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_unlink_periodic
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff818e46bc)
Location: drivers/usb/host/ohci-q.c:270
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff819709a1)
Location: drivers/usb/host/ehci-sched.c:63
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_unlink_periodic
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff8198096d)
Location: drivers/usb/host/ohci-q.c:270
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81acb231)
Location: drivers/usb/host/ehci-sched.c:63
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_unlink_periodic
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81adc87d)
Location: drivers/usb/host/ohci-q.c:270
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81c55911)
Location: drivers/usb/host/ehci-sched.c:63
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_unlink_periodic
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81c67bad)
Location: drivers/usb/host/ohci-q.c:270
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81cbcea1)
Location: drivers/usb/host/ehci-sched.c:63
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_unlink_periodic
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81ccec99)
Location: drivers/usb/host/ohci-q.c:270
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81d71c11)
Location: drivers/usb/host/ehci-sched.c:63
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_unlink_periodic
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81d83b99)
Location: drivers/usb/host/ohci-q.c:270
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffff800010a559c0)
Location: drivers/usb/host/ehci-sched.c:63
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (ffff800010a5f3e0)
Location: drivers/usb/host/ohci-q.c:270
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (c0b286f8)
Location: drivers/usb/host/ehci-sched.c:63
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (c0b30e9c)
Location: drivers/usb/host/ohci-q.c:270
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (c000000000b22500)
Location: drivers/usb/host/ehci-sched.c:63
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (c000000000b2d1c0)
Location: drivers/usb/host/ohci-q.c:270
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffe000673334)
Location: drivers/usb/host/ehci-sched.c:63
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (ffffffe000679d4a)
Location: drivers/usb/host/ohci-q.c:270
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817d444c)
Location: drivers/usb/host/ehci-sched.c:63
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff817dd019)
Location: drivers/usb/host/ohci-q.c:270
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81810eec)
Location: drivers/usb/host/ehci-sched.c:63
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81819ab9)
Location: drivers/usb/host/ohci-q.c:270
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff8182b9bc)
Location: drivers/usb/host/ehci-sched.c:63
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81833aa9)
Location: drivers/usb/host/ohci-q.c:270
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ed_deschedule
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
</ul>
