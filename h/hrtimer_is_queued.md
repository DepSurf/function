# Function: <code>hrtimer_is_queued</code>

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
In kernel/signal.c (0)
Location: include/linux/hrtimer.h:430
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/hrtimer.h:430
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/hrtimer.h:430
Inline: True
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
In kernel/signal.c (0)
Location: include/linux/hrtimer.h:430
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/hrtimer.h:430
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/hrtimer.h:430
Inline: True
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
In kernel/signal.c (0)
Location: include/linux/hrtimer.h:430
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/hrtimer.h:430
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/hrtimer.h:430
Inline: True
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
In kernel/signal.c (0)
Location: include/linux/hrtimer.h:414
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/hrtimer.h:414
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/hrtimer.h:414
Inline: True
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
In kernel/signal.c (0)
Location: include/linux/hrtimer.h:414
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/hrtimer.h:414
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/hrtimer.h:414
Inline: True
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
In kernel/signal.c (0)
Location: include/linux/hrtimer.h:436
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/hrtimer.h:436
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/hrtimer.h:436
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/hrtimer.h:436
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/hrtimer.h:436
Inline: True
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
In kernel/signal.c (0)
Location: include/linux/hrtimer.h:433
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/hrtimer.h:433
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/hrtimer.h:433
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/hrtimer.h:433
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/hrtimer.h:433
Inline: True
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
In kernel/signal.c (0)
Location: include/linux/hrtimer.h:419
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/hrtimer.h:419
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/hrtimer.h:419
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/hrtimer.h:419
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/hrtimer.h:419
Inline: True
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
In kernel/signal.c (ffffffff810b0cd0)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/sched/deadline.c (ffffffff810f12b9)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In block/blk-iocost.c (ffffffff8150fc4c)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In net/ipv4/tcp_input.c (ffffffff819c44a0)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff819cf6f6)
Location: include/linux/hrtimer.h:467
Inline: True
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
In kernel/signal.c (ffffffff810b9000)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/sched/deadline.c (ffffffff810fa729)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In block/blk-iocost.c (ffffffff81570d55)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In net/sched/sch_api.c (ffffffff81a680bc)
Location: include/linux/hrtimer.h:467
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81ab17ea)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81abf913)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
In kernel/signal.c (ffffffff810b42b0)
Location: include/linux/hrtimer.h:472
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/sched/deadline.c (ffffffff810f8bc9)
Location: include/linux/hrtimer.h:472
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In kernel/time/ntp.c (ffffffff811475de)
Location: include/linux/hrtimer.h:472
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_notify_cmos_timer
  - kernel/time/ntp.c:sync_hw_clock
```
```
In block/blk-iocost.c (ffffffff8158d2ef)
Location: include/linux/hrtimer.h:472
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In net/sched/sch_api.c (ffffffff81a707cc)
Location: include/linux/hrtimer.h:472
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81abc7aa)
Location: include/linux/hrtimer.h:472
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81acb37f)
Location: include/linux/hrtimer.h:472
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
In kernel/signal.c (ffffffff810b5ec0)
Location: include/linux/hrtimer.h:472
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/sched/deadline.c (ffffffff810fac6c)
Location: include/linux/hrtimer.h:472
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In kernel/time/ntp.c (ffffffff8114870e)
Location: include/linux/hrtimer.h:472
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_notify_cmos_timer
  - kernel/time/ntp.c:sync_hw_clock
```
```
In block/blk-iocost.c (ffffffff815946e0)
Location: include/linux/hrtimer.h:472
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In net/sched/sch_api.c (ffffffff81a590cc)
Location: include/linux/hrtimer.h:472
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81aa78b8)
Location: include/linux/hrtimer.h:472
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81ab63af)
Location: include/linux/hrtimer.h:472
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
In kernel/signal.c (ffffffff810c8d4f)
Location: include/linux/hrtimer.h:468
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/sched/deadline.c (ffffffff81116629)
Location: include/linux/hrtimer.h:468
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In kernel/time/ntp.c (ffffffff8116c2be)
Location: include/linux/hrtimer.h:468
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_notify_cmos_timer
  - kernel/time/ntp.c:sync_hw_clock
```
```
In block/blk-iocost.c (ffffffff815fbbf0)
Location: include/linux/hrtimer.h:468
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In net/sched/sch_api.c (ffffffff81b1226c)
Location: include/linux/hrtimer.h:468
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81b62fa1)
Location: include/linux/hrtimer.h:468
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81b733bb)
Location: include/linux/hrtimer.h:468
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
In kernel/signal.c (ffffffff810e02e5)
Location: include/linux/hrtimer.h:468
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/sched/build_policy.c (ffffffff8113054d)
Location: include/linux/hrtimer.h:468
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:start_dl_timer
```
```
In kernel/time/ntp.c (ffffffff811a02ae)
Location: include/linux/hrtimer.h:468
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_notify_cmos_timer
  - kernel/time/ntp.c:sync_hw_clock
```
```
In block/blk-iocost.c (ffffffff816af1c7)
Location: include/linux/hrtimer.h:468
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In drivers/mailbox/mailbox.c (ffffffff81bca7cd)
Location: include/linux/hrtimer.h:468
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:txdone_hrtimer
```
```
In net/sched/sch_api.c (ffffffff81c9954c)
Location: include/linux/hrtimer.h:468
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81cf1c67)
Location: include/linux/hrtimer.h:468
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81d02b36)
Location: include/linux/hrtimer.h:468
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
In kernel/signal.c (ffffffff81100975)
Location: include/linux/hrtimer.h:468
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/sched/build_policy.c (ffffffff8115a08d)
Location: include/linux/hrtimer.h:468
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:start_dl_timer
```
```
In kernel/time/ntp.c (ffffffff811df0ce)
Location: include/linux/hrtimer.h:468
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_notify_cmos_timer
  - kernel/time/ntp.c:sync_hw_clock
```
```
In block/blk-iocost.c (ffffffff8176e6e7)
Location: include/linux/hrtimer.h:468
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In drivers/mailbox/mailbox.c (ffffffff81d73e6d)
Location: include/linux/hrtimer.h:468
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:txdone_hrtimer
```
```
In net/sched/sch_api.c (ffffffff81e5583c)
Location: include/linux/hrtimer.h:468
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81eb64c7)
Location: include/linux/hrtimer.h:468
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81ec7c76)
Location: include/linux/hrtimer.h:468
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
In kernel/signal.c (ffffffff8110ca78)
Location: include/linux/hrtimer.h:468
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/sched/build_policy.c (ffffffff8116a29d)
Location: include/linux/hrtimer.h:468
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:start_dl_timer
```
```
In kernel/time/ntp.c (ffffffff811f35ae)
Location: include/linux/hrtimer.h:468
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_notify_cmos_timer
  - kernel/time/ntp.c:sync_hw_clock
```
```
In block/blk-iocost.c (ffffffff817ae267)
Location: include/linux/hrtimer.h:468
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In drivers/mailbox/mailbox.c (ffffffff81de1b05)
Location: include/linux/hrtimer.h:468
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:txdone_hrtimer
```
```
In net/sched/sch_api.c (ffffffff81eb10ec)
Location: include/linux/hrtimer.h:468
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81f148e7)
Location: include/linux/hrtimer.h:468
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81f26543)
Location: include/linux/hrtimer.h:468
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
In kernel/signal.c (ffffffff81116458)
Location: include/linux/hrtimer.h:430
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/sched/build_policy.c (ffffffff8117795f)
Location: include/linux/hrtimer.h:430
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:start_dl_timer
```
```
In kernel/time/ntp.c (ffffffff812096ee)
Location: include/linux/hrtimer.h:430
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_notify_cmos_timer
  - kernel/time/ntp.c:sync_hw_clock
```
```
In block/blk-iocost.c (ffffffff817f2077)
Location: include/linux/hrtimer.h:430
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In drivers/mailbox/mailbox.c (ffffffff81e97ac5)
Location: include/linux/hrtimer.h:430
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:txdone_hrtimer
```
```
In net/sched/sch_api.c (ffffffff81f73b8c)
Location: include/linux/hrtimer.h:430
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81fd8e16)
Location: include/linux/hrtimer.h:430
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81feaf23)
Location: include/linux/hrtimer.h:430
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
In kernel/signal.c (ffff80001010b8cc)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/sched/deadline.c (ffff800010153eb8)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In block/blk-iocost.c (ffff800010615454)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In net/ipv4/tcp_input.c (ffff800010c7b73c)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffff800010c81e58)
Location: include/linux/hrtimer.h:467
Inline: True
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
In kernel/signal.c (c0364ac8)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/sched/deadline.c (c03a0a7c)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In block/blk-iocost.c (c07be5bc)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In net/ipv4/tcp_input.c (c0d8791c)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (c0d9115c)
Location: include/linux/hrtimer.h:467
Inline: True
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
In kernel/signal.c (c000000000153594)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/sched/deadline.c (c0000000001a7538)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In block/blk-iocost.c (c0000000007b22ac)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In net/ipv4/tcp_input.c (c000000000d7f0c4)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (c000000000d8d548)
Location: include/linux/hrtimer.h:467
Inline: True
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
In kernel/signal.c (ffffffe0000cdeb4)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/sched/deadline.c (ffffffe0000fb726)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In block/blk-iocost.c (ffffffe00044add8)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In net/ipv4/tcp_input.c (ffffffe0007da140)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffe0007e4132)
Location: include/linux/hrtimer.h:467
Inline: True
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
In kernel/signal.c (ffffffff810ab040)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/sched/deadline.c (ffffffff810ea6b9)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In block/blk-iocost.c (ffffffff8150822c)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In net/ipv4/tcp_input.c (ffffffff81964310)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff8196f566)
Location: include/linux/hrtimer.h:467
Inline: True
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
In kernel/signal.c (ffffffff810999e0)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/sched/deadline.c (ffffffff810da6e9)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In block/blk-iocost.c (ffffffff814f86dc)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In net/ipv4/tcp_input.c (ffffffff8191de00)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81929036)
Location: include/linux/hrtimer.h:467
Inline: True
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
In kernel/signal.c (ffffffff810aa5a0)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/sched/deadline.c (ffffffff810e77e9)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In block/blk-iocost.c (ffffffff815042bc)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In net/ipv4/tcp_input.c (ffffffff819ceae0)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff819d9d36)
Location: include/linux/hrtimer.h:467
Inline: True
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
In kernel/signal.c (ffffffff810b267e)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/sched/deadline.c (ffffffff810f2de9)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In block/blk-iocost.c (ffffffff8151d86c)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In net/ipv4/tcp_input.c (ffffffff819d8670)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff819e3996)
Location: include/linux/hrtimer.h:467
Inline: True
```
</details>
</li>
</ul>

## Differences
