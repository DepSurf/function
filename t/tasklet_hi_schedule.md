# Function: <code>tasklet_hi_schedule</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81085535)
Location: include/linux/interrupt.h:541
Inline: True
Inline callers:
  - kernel/softirq.c:__hrtimer_tasklet_trampoline
```
```
In drivers/usb/core/hcd.c (ffffffff8160cfc6)
Location: include/linux/interrupt.h:541
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81088615)
Location: include/linux/interrupt.h:560
Inline: True
Inline callers:
  - kernel/softirq.c:__hrtimer_tasklet_trampoline
```
```
In drivers/usb/core/hcd.c (ffffffff8166cb18)
Location: include/linux/interrupt.h:560
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff8108d645)
Location: include/linux/interrupt.h:580
Inline: True
Inline callers:
  - kernel/softirq.c:__hrtimer_tasklet_trampoline
```
```
In drivers/usb/core/hcd.c (ffffffff8169a818)
Location: include/linux/interrupt.h:580
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff8108a5b5)
Location: include/linux/interrupt.h:589
Inline: True
Inline callers:
  - kernel/softirq.c:__hrtimer_tasklet_trampoline
```
```
In drivers/usb/core/hcd.c (ffffffff816afab8)
Location: include/linux/interrupt.h:589
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81091149)
Location: include/linux/interrupt.h:591
Inline: True
Inline callers:
  - kernel/softirq.c:__hrtimer_tasklet_trampoline
```
```
In drivers/usb/core/hcd.c (ffffffff8171b128)
Location: include/linux/interrupt.h:591
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81094d35)
Location: include/linux/interrupt.h:596
Inline: True
Inline callers:
  - kernel/softirq.c:__hrtimer_tasklet_trampoline
```
```
In drivers/usb/core/hcd.c (ffffffff81759ec1)
Location: include/linux/interrupt.h:596
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff8109d145)
Location: include/linux/interrupt.h:612
Inline: True
Inline callers:
  - kernel/softirq.c:__hrtimer_tasklet_trampoline
```
```
In drivers/usb/core/hcd.c (ffffffff8177e441)
Location: include/linux/interrupt.h:612
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
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
In drivers/usb/core/hcd.c (ffffffff817bc9c1)
Location: include/linux/interrupt.h:641
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
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
In drivers/usb/core/hcd.c (ffffffff817ed1e1)
Location: include/linux/interrupt.h:646
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff818bca01)
Location: include/linux/interrupt.h:660
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff818c9711)
Location: include/linux/interrupt.h:698
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff818ad041)
Location: include/linux/interrupt.h:688
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff819420e1)
Location: include/linux/interrupt.h:662
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81a99fb3)
Location: include/linux/interrupt.h:713
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81c1e513)
Location: include/linux/interrupt.h:713
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81c853fb)
Location: include/linux/interrupt.h:713
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81d39dfb)
Location: include/linux/interrupt.h:717
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/smsc/smc91x.c (ffff8000109fd74c)
Location: include/linux/interrupt.h:646
Inline: True
Inline callers:
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
```
```
In drivers/usb/core/hcd.c (ffff800010a1cc44)
Location: include/linux/interrupt.h:646
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
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
In drivers/usb/core/hcd.c (c0af4100)
Location: include/linux/interrupt.h:646
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
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
In drivers/usb/core/hcd.c (c000000000ad60a0)
Location: include/linux/interrupt.h:646
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
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
In drivers/usb/core/hcd.c (ffffffe0006409a4)
Location: include/linux/interrupt.h:646
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
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
In drivers/usb/core/hcd.c (ffffffff817a55c1)
Location: include/linux/interrupt.h:646
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81797081)
Location: include/linux/interrupt.h:646
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817e2061)
Location: include/linux/interrupt.h:646
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
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
In drivers/usb/core/hcd.c (ffffffff817fc490)
Location: include/linux/interrupt.h:646
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
</details>
</li>
</ul>

## Differences
