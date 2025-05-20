# Function: <code>rtc_tv_nsec_ok</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff8110e464)
Location: include/linux/rtc.h:242
Inline: True
```
```
In drivers/rtc/systohc.c (ffffffff8178a2d2)
Location: include/linux/rtc.h:242
Inline: True
Inline callers:
  - drivers/rtc/systohc.c:rtc_set_ntp_time
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
In kernel/time/ntp.c (ffffffff81119dcf)
Location: include/linux/rtc.h:247
Inline: True
```
```
In drivers/rtc/systohc.c (ffffffff817cb3e8)
Location: include/linux/rtc.h:247
Inline: True
Inline callers:
  - drivers/rtc/systohc.c:rtc_set_ntp_time
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
In kernel/time/ntp.c (ffffffff811252cf)
Location: include/linux/rtc.h:228
Inline: True
```
```
In drivers/rtc/systohc.c (ffffffff817f2a98)
Location: include/linux/rtc.h:228
Inline: True
Inline callers:
  - drivers/rtc/systohc.c:rtc_set_ntp_time
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff8112fd51)
Location: include/linux/rtc.h:227
Inline: True
```
```
In drivers/rtc/systohc.c (ffffffff81833775)
Location: include/linux/rtc.h:227
Inline: True
Inline callers:
  - drivers/rtc/systohc.c:rtc_set_ntp_time
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff8113bc91)
Location: include/linux/rtc.h:227
Inline: True
```
```
In drivers/rtc/systohc.c (ffffffff818650b5)
Location: include/linux/rtc.h:227
Inline: True
Inline callers:
  - drivers/rtc/systohc.c:rtc_set_ntp_time
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff8114b004)
Location: include/linux/rtc.h:221
Inline: True
Inline callers:
  - kernel/time/ntp.c:sync_cmos_clock
```
```
In drivers/rtc/systohc.c (ffffffff81938905)
Location: include/linux/rtc.h:221
Inline: True
Inline callers:
  - drivers/rtc/systohc.c:rtc_set_ntp_time
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
In kernel/time/ntp.c (ffffffff81147441)
Location: kernel/time/ntp.c:543
Inline: True
Inline callers:
  - kernel/time/ntp.c:sync_hw_clock
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
In kernel/time/ntp.c (ffffffff81148571)
Location: kernel/time/ntp.c:543
Inline: True
Inline callers:
  - kernel/time/ntp.c:sync_hw_clock
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
In kernel/time/ntp.c (ffffffff8116c121)
Location: kernel/time/ntp.c:543
Inline: True
Inline callers:
  - kernel/time/ntp.c:sync_hw_clock
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
In kernel/time/ntp.c (ffffffff811a00cc)
Location: kernel/time/ntp.c:543
Inline: True
Inline callers:
  - kernel/time/ntp.c:sync_hw_clock
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
In kernel/time/ntp.c (ffffffff811deedc)
Location: kernel/time/ntp.c:543
Inline: True
Inline callers:
  - kernel/time/ntp.c:sync_hw_clock
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
In kernel/time/ntp.c (ffffffff811f33bc)
Location: kernel/time/ntp.c:543
Inline: True
Inline callers:
  - kernel/time/ntp.c:sync_hw_clock
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
In kernel/time/ntp.c (ffffffff812094fc)
Location: kernel/time/ntp.c:543
Inline: True
Inline callers:
  - kernel/time/ntp.c:sync_hw_clock
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
In drivers/rtc/systohc.c (ffff800010aa690c)
Location: include/linux/rtc.h:227
Inline: True
Inline callers:
  - drivers/rtc/systohc.c:rtc_set_ntp_time
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
In drivers/rtc/systohc.c (c0b85420)
Location: include/linux/rtc.h:227
Inline: True
Inline callers:
  - drivers/rtc/systohc.c:rtc_set_ntp_time
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (c0000000002081ac)
Location: include/linux/rtc.h:227
Inline: True
```
```
In drivers/rtc/systohc.c (c000000000b87544)
Location: include/linux/rtc.h:227
Inline: True
Inline callers:
  - drivers/rtc/systohc.c:rtc_set_ntp_time
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
In drivers/rtc/systohc.c (ffffffe0006b2c1e)
Location: include/linux/rtc.h:227
Inline: True
Inline callers:
  - drivers/rtc/systohc.c:rtc_set_ntp_time
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff81134441)
Location: include/linux/rtc.h:227
Inline: True
```
```
In drivers/rtc/systohc.c (ffffffff81817d65)
Location: include/linux/rtc.h:227
Inline: True
Inline callers:
  - drivers/rtc/systohc.c:rtc_set_ntp_time
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff81126ea1)
Location: include/linux/rtc.h:227
Inline: True
```
```
In drivers/rtc/systohc.c (ffffffff817df455)
Location: include/linux/rtc.h:227
Inline: True
Inline callers:
  - drivers/rtc/systohc.c:rtc_set_ntp_time
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff81132161)
Location: include/linux/rtc.h:227
Inline: True
```
```
In drivers/rtc/systohc.c (ffffffff81859245)
Location: include/linux/rtc.h:227
Inline: True
Inline callers:
  - drivers/rtc/systohc.c:rtc_set_ntp_time
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff8113eb81)
Location: include/linux/rtc.h:227
Inline: True
```
```
In drivers/rtc/systohc.c (ffffffff81874325)
Location: include/linux/rtc.h:227
Inline: True
Inline callers:
  - drivers/rtc/systohc.c:rtc_set_ntp_time
```
</details>
</li>
</ul>

## Differences
