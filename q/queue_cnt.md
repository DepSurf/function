# Function: <code>queue_cnt</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff817df046)
Location: drivers/ptp/ptp_private.h:71
Inline: True
```
```
In drivers/ptp/ptp_chardev.c (ffffffff817dfe21)
Location: drivers/ptp/ptp_private.h:71
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_poll
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff817e0452)
Location: drivers/ptp/ptp_private.h:71
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:extts_fifo_show
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
In drivers/ptp/ptp_clock.c (ffffffff8180a486)
Location: drivers/ptp/ptp_private.h:71
Inline: True
```
```
In drivers/ptp/ptp_chardev.c (ffffffff8180b3f1)
Location: drivers/ptp/ptp_private.h:71
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_poll
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff8180ba22)
Location: drivers/ptp/ptp_private.h:71
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:extts_fifo_show
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
In drivers/ptp/ptp_clock.c (ffffffff8184c166)
Location: drivers/ptp/ptp_private.h:58
Inline: True
```
```
In drivers/ptp/ptp_chardev.c (ffffffff8184d0e1)
Location: drivers/ptp/ptp_private.h:58
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_poll
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff8184d6f7)
Location: drivers/ptp/ptp_private.h:58
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:extts_fifo_show
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
In drivers/ptp/ptp_clock.c (ffffffff8187d966)
Location: drivers/ptp/ptp_private.h:58
Inline: True
```
```
In drivers/ptp/ptp_chardev.c (ffffffff8187eb21)
Location: drivers/ptp/ptp_private.h:58
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_poll
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff8187f137)
Location: drivers/ptp/ptp_private.h:58
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:extts_fifo_show
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
In drivers/ptp/ptp_clock.c (ffffffff8194bd2a)
Location: drivers/ptp/ptp_private.h:58
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_event
```
```
In drivers/ptp/ptp_chardev.c (ffffffff8194d01c)
Location: drivers/ptp/ptp_private.h:58
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_poll
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff8194d639)
Location: drivers/ptp/ptp_private.h:58
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:extts_fifo_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff8195173a)
Location: drivers/ptp/ptp_private.h:58
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_event
```
```
In drivers/ptp/ptp_chardev.c (ffffffff81952a4c)
Location: drivers/ptp/ptp_private.h:58
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_poll
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff81953029)
Location: drivers/ptp/ptp_private.h:58
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:extts_fifo_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff819355be)
Location: drivers/ptp/ptp_private.h:58
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_event
```
```
In drivers/ptp/ptp_chardev.c (ffffffff819368ba)
Location: drivers/ptp/ptp_private.h:58
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_poll
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff81936eb1)
Location: drivers/ptp/ptp_private.h:58
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:extts_fifo_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff819d881d)
Location: drivers/ptp/ptp_private.h:77
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_event
```
```
In drivers/ptp/ptp_chardev.c (ffffffff819d9ffd)
Location: drivers/ptp/ptp_private.h:77
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_poll
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff819da7a7)
Location: drivers/ptp/ptp_private.h:77
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:extts_fifo_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff81b3bd23)
Location: drivers/ptp/ptp_private.h:79
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_event
```
```
In drivers/ptp/ptp_chardev.c (ffffffff81b3d6a1)
Location: drivers/ptp/ptp_private.h:79
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_poll
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff81b3dd47)
Location: drivers/ptp/ptp_private.h:79
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:extts_fifo_show
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff81cd1c53)
Location: drivers/ptp/ptp_private.h:79
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_event
```
```
In drivers/ptp/ptp_chardev.c (ffffffff81cd36f1)
Location: drivers/ptp/ptp_private.h:79
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_poll
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff81cd3ec7)
Location: drivers/ptp/ptp_private.h:79
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:extts_fifo_show
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff81d395fb)
Location: drivers/ptp/ptp_private.h:79
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_event
```
```
In drivers/ptp/ptp_chardev.c (ffffffff81d3b2a4)
Location: drivers/ptp/ptp_private.h:79
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_poll
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff81d3bad7)
Location: drivers/ptp/ptp_private.h:79
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:extts_fifo_show
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff81def975)
Location: drivers/ptp/ptp_private.h:88
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_event
```
```
In drivers/ptp/ptp_chardev.c (ffffffff81df1c34)
Location: drivers/ptp/ptp_private.h:88
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_poll
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff81df2437)
Location: drivers/ptp/ptp_private.h:88
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:extts_fifo_show
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
In drivers/ptp/ptp_clock.c (ffff800010ac75d8)
Location: drivers/ptp/ptp_private.h:58
Inline: True
```
```
In drivers/ptp/ptp_chardev.c (ffff800010ac8778)
Location: drivers/ptp/ptp_private.h:58
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_poll
```
```
In drivers/ptp/ptp_sysfs.c (ffff800010ac9020)
Location: drivers/ptp/ptp_private.h:58
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:extts_fifo_show
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (c0ba7058)
Location: drivers/ptp/ptp_private.h:58
Inline: True
```
```
In drivers/ptp/ptp_chardev.c (c0ba80f0)
Location: drivers/ptp/ptp_private.h:58
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_poll
```
```
In drivers/ptp/ptp_sysfs.c (c0ba8760)
Location: drivers/ptp/ptp_private.h:58
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:extts_fifo_show
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
In drivers/ptp/ptp_clock.c (c000000000ba8a9c)
Location: drivers/ptp/ptp_private.h:58
Inline: True
```
```
In drivers/ptp/ptp_chardev.c (c000000000baa0e0)
Location: drivers/ptp/ptp_private.h:58
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_poll
```
```
In drivers/ptp/ptp_sysfs.c (c000000000baa988)
Location: drivers/ptp/ptp_private.h:58
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:extts_fifo_show
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffe0006c5c32)
Location: drivers/ptp/ptp_private.h:58
Inline: True
```
```
In drivers/ptp/ptp_chardev.c (ffffffe0006c6b3a)
Location: drivers/ptp/ptp_private.h:58
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_poll
```
```
In drivers/ptp/ptp_sysfs.c (ffffffe0006c70e2)
Location: drivers/ptp/ptp_private.h:58
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:extts_fifo_show
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
In drivers/ptp/ptp_clock.c (ffffffff81825ed6)
Location: drivers/ptp/ptp_private.h:58
Inline: True
```
```
In drivers/ptp/ptp_chardev.c (ffffffff81827091)
Location: drivers/ptp/ptp_private.h:58
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_poll
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff818276a7)
Location: drivers/ptp/ptp_private.h:58
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:extts_fifo_show
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
In drivers/ptp/ptp_clock.c (ffffffff817ed566)
Location: drivers/ptp/ptp_private.h:58
Inline: True
```
```
In drivers/ptp/ptp_chardev.c (ffffffff817ee721)
Location: drivers/ptp/ptp_private.h:58
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_poll
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff817eed37)
Location: drivers/ptp/ptp_private.h:58
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:extts_fifo_show
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
In drivers/ptp/ptp_clock.c (ffffffff81872e16)
Location: drivers/ptp/ptp_private.h:58
Inline: True
```
```
In drivers/ptp/ptp_chardev.c (ffffffff81873fd1)
Location: drivers/ptp/ptp_private.h:58
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_poll
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff818745e7)
Location: drivers/ptp/ptp_private.h:58
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:extts_fifo_show
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
In drivers/ptp/ptp_clock.c (ffffffff8188e7c6)
Location: drivers/ptp/ptp_private.h:58
Inline: True
```
```
In drivers/ptp/ptp_chardev.c (ffffffff8188f97c)
Location: drivers/ptp/ptp_private.h:58
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_poll
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff8188ff97)
Location: drivers/ptp/ptp_private.h:58
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:extts_fifo_show
```
</details>
</li>
</ul>

## Differences
