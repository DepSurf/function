# Function: <code>getnstimeofday</code>

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
In kernel/trace/blktrace.c (ffffffff8115ccd3)
Location: include/linux/timekeeping.h:59
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_trace_startstop
```
```
In net/ipv4/ip_options.c (ffffffff8175ade4)
Location: include/linux/timekeeping.h:59
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/ip_options.c:ip_options_build
```
```
In net/ipv4/icmp.c (ffffffff8178ec1d)
Location: include/linux/timekeeping.h:59
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81802e40)
Location: include/linux/timekeeping.h:59
Inline: True
Inline callers:
  - net/packet/af_packet.c:prb_open_block
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:tpacket_rcv
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
In net/packet/af_packet.c (ffffffff81877b5d)
Location: include/linux/timekeeping.h:75
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_open_block
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
In net/packet/af_packet.c (ffffffff818ab3af)
Location: include/linux/timekeeping.h:75
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_open_block
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
In net/packet/af_packet.c (ffffffff818d47ad)
Location: include/linux/timekeeping.h:64
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_open_block
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
In net/packet/af_packet.c (ffffffff81959219)
Location: include/linux/timekeeping32.h:36
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_open_block
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
In net/packet/af_packet.c (ffffffff819b2f0a)
Location: include/linux/timekeeping32.h:32
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_open_block
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
In net/packet/af_packet.c (ffffffff819e9e5c)
Location: include/linux/timekeeping32.h:14
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_open_block
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
In net/packet/af_packet.c (ffffffff81a584fd)
Location: include/linux/timekeeping32.h:14
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_open_block
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
In net/packet/af_packet.c (ffffffff81a908e8)
Location: include/linux/timekeeping32.h:14
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_open_block
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In net/packet/af_packet.c (ffff800010d5e3ec)
Location: include/linux/timekeeping32.h:14
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_open_block
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
In sound/core/timer.c (c0c8cbbc)
Location: include/linux/timekeeping32.h:14
Inline: True
Inline callers:
  - sound/core/timer.c:snd_timer_user_tinterrupt
  - sound/core/timer.c:snd_timer_notify1
```
```
In sound/core/pcm_native.c (c0c93df0)
Location: include/linux/timekeeping32.h:14
Inline: True
Inline callers:
  - sound/core/pcm_native.c:snd_pcm_trigger_tstamp
  - sound/core/pcm_native.c:snd_pcm_status
```
```
In sound/core/pcm_lib.c (c0c99484)
Location: include/linux/timekeeping32.h:14
Inline: True
Inline callers:
  - sound/core/pcm_lib.c:update_audio_tstamp
  - sound/core/pcm_lib.c:__snd_pcm_xrun
```
```
In net/packet/af_packet.c (c0e5cb34)
Location: include/linux/timekeeping32.h:14
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_open_block
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
In net/packet/af_packet.c (c000000000e96db0)
Location: include/linux/timekeeping32.h:14
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_open_block
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
In net/packet/af_packet.c (ffffffe000893d6c)
Location: include/linux/timekeeping32.h:14
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_open_block
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
In net/packet/af_packet.c (ffffffff81a2ff78)
Location: include/linux/timekeeping32.h:14
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_open_block
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
In net/packet/af_packet.c (ffffffff819ed168)
Location: include/linux/timekeeping32.h:14
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_open_block
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
In net/packet/af_packet.c (ffffffff81a9bb28)
Location: include/linux/timekeeping32.h:14
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_open_block
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
In net/packet/af_packet.c (ffffffff81aa62fd)
Location: include/linux/timekeeping32.h:14
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_open_block
```
</details>
</li>
</ul>

## Differences
