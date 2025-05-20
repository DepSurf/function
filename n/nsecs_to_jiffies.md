# Function: <code>nsecs_to_jiffies</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int nsecs_to_jiffies(u64 n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810eaf40)
Location: kernel/time/time.c:742
Inline: True
Direct callers:
  - kernel/sched/cputime.c:cputime_adjust
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810eaf40-ffffffff810eaf62: nsecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int nsecs_to_jiffies(u64 n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810f1c10)
Location: kernel/time/time.c:749
Inline: False
Direct callers:
  - kernel/sched/cputime.c:cputime_adjust
  - kernel/sched/cputime.c:account_idle_ticks
  - kernel/sched/cputime.c:account_process_tick
  - block/cfq-iosched.c:cfq_completed_request
```
**Symbols:**

```
ffffffff810f1c10-ffffffff810f1c32: nsecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int nsecs_to_jiffies(u64 n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810f8d90)
Location: kernel/time/time.c:749
Inline: False
Direct callers:
  - kernel/sched/cputime.c:cputime_adjust
  - kernel/sched/cputime.c:account_idle_ticks
  - kernel/sched/cputime.c:account_process_tick
  - block/cfq-iosched.c:cfq_completed_request
  - block/blk-wbt.c:rwb_arm_timer
```
**Symbols:**

```
ffffffff810f8d90-ffffffff810f8db2: nsecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int nsecs_to_jiffies(u64 n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810fadd0)
Location: kernel/time/time.c:849
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_completed_request
  - block/blk-wbt.c:rwb_arm_timer
```
**Symbols:**

```
ffffffff810fadd0-ffffffff810fadf2: nsecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int nsecs_to_jiffies(u64 n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81105760)
Location: kernel/time/time.c:816
Inline: False
Direct callers:
  - block/cfq-iosched.c:cfq_completed_request
  - block/blk-wbt.c:rwb_arm_timer
```
**Symbols:**

```
ffffffff81105760-ffffffff81105782: nsecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int nsecs_to_jiffies(u64 n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811105c0)
Location: kernel/time/time.c:828
Inline: False
Direct callers:
  - block/blk-wbt.c:rwb_arm_timer
```
**Symbols:**

```
ffffffff811105c0-ffffffff811105e2: nsecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int nsecs_to_jiffies(u64 n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111bbb0)
Location: kernel/time/time.c:766
Inline: False
Direct callers:
  - kernel/sched/psi.c:update_stats
  - block/blk-wbt.c:rwb_arm_timer
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
**Symbols:**

```
ffffffff8111bbb0-ffffffff8111bbd2: nsecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int nsecs_to_jiffies(u64 n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811265f0)
Location: kernel/time/time.c:844
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_poll_work
  - kernel/sched/psi.c:psi_avgs_work
  - kernel/sched/psi.c:collect_percpu_times
  - block/blk-wbt.c:rwb_arm_timer
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
**Symbols:**

```
ffffffff811265f0-ffffffff81126612: nsecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int nsecs_to_jiffies(u64 n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81132590)
Location: kernel/time/time.c:844
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_poll_work
  - kernel/sched/psi.c:psi_avgs_work
  - kernel/sched/psi.c:collect_percpu_times
  - block/blk-wbt.c:rwb_arm_timer
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
**Symbols:**

```
ffffffff81132590-ffffffff811325b2: nsecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int nsecs_to_jiffies(u64 n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (0)
Location: kernel/time/time.c:754
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_poll_work
  - kernel/sched/psi.c:psi_avgs_work
  - kernel/sched/psi.c:collect_percpu_times
  - block/blk-wbt.c:rwb_arm_timer
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
**Symbols:**

```
ffffffff81141fd0-ffffffff81141ff2: nsecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int nsecs_to_jiffies(u64 n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (0)
Location: kernel/time/time.c:754
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_poll_work
  - kernel/sched/psi.c:psi_avgs_work
  - kernel/sched/psi.c:collect_percpu_times
  - block/blk-wbt.c:rwb_arm_timer
  - net/ipv4/tcp_input.c:tcp_ack_probe
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
**Symbols:**

```
ffffffff8113e1e0-ffffffff8113e202: nsecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int nsecs_to_jiffies(u64 n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (0)
Location: kernel/time/time.c:754
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_poll_worker
  - kernel/sched/psi.c:psi_avgs_work
  - kernel/sched/psi.c:collect_percpu_times
  - block/blk-wbt.c:rwb_arm_timer
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
**Symbols:**

```
ffffffff8113f430-ffffffff8113f452: nsecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int nsecs_to_jiffies(u64 n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (0)
Location: kernel/time/time.c:754
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_poll_worker
  - kernel/sched/psi.c:psi_avgs_work
  - kernel/sched/psi.c:collect_percpu_times
  - fs/ext4/super.c:ext4_run_li_request
  - block/blk-wbt.c:rwb_arm_timer
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
**Symbols:**

```
ffffffff811628c0-ffffffff811628e2: nsecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int nsecs_to_jiffies(u64 n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (0)
Location: kernel/time/time.c:754
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:psi_poll_worker
  - kernel/sched/build_utility.c:psi_avgs_work
  - kernel/sched/build_utility.c:collect_percpu_times
  - fs/ext4/super.c:ext4_run_li_request
  - block/blk-wbt.c:rwb_arm_timer
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
**Symbols:**

```
ffffffff81195780-ffffffff811957a7: nsecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int nsecs_to_jiffies(u64 n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (0)
Location: kernel/time/time.c:754
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:psi_poll_worker
  - kernel/sched/build_utility.c:psi_avgs_work
  - kernel/sched/build_utility.c:collect_percpu_times
  - fs/ext4/super.c:ext4_run_li_request
  - block/blk-wbt.c:rwb_arm_timer
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_timer
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_timer
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_timeout
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
**Symbols:**

```
ffffffff811d3640-ffffffff811d3667: nsecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int nsecs_to_jiffies(u64 n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (0)
Location: kernel/time/time.c:754
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:psi_rtpoll_work
  - kernel/sched/build_utility.c:psi_avgs_work
  - kernel/sched/build_utility.c:collect_percpu_times
  - fs/ext4/super.c:ext4_run_li_request
  - block/blk-wbt.c:rwb_arm_timer
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_timer
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_timer
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_timeout
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
**Symbols:**

```
ffffffff811e7930-ffffffff811e7957: nsecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int nsecs_to_jiffies(u64 n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (0)
Location: kernel/time/time.c:829
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:psi_rtpoll_work
  - kernel/sched/build_utility.c:psi_avgs_work
  - kernel/sched/build_utility.c:collect_percpu_times
  - fs/ext4/super.c:ext4_run_li_request
  - block/blk-wbt.c:rwb_arm_timer
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_timer
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_timer
  - drivers/tty/serial/8250/8250_core.c:serial8250_backup_timeout
  - drivers/tty/serial/8250/8250_core.c:serial8250_timeout
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
**Symbols:**

```
ffffffff811fd660-ffffffff811fd687: nsecs_to_jiffies (STB_GLOBAL)
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
long unsigned int nsecs_to_jiffies(u64 n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffff80001019a0f8)
Location: kernel/time/time.c:844
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_poll_work
  - kernel/sched/psi.c:psi_avgs_work
  - kernel/sched/psi.c:collect_percpu_times
  - block/blk-wbt.c:rwb_arm_timer
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
**Symbols:**

```
ffff80001019a0f8-ffff80001019a134: nsecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int nsecs_to_jiffies(u64 n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c03e5300)
Location: kernel/time/time.c:844
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_poll_work
  - kernel/sched/psi.c:psi_avgs_work
  - kernel/sched/psi.c:collect_percpu_times
  - block/blk-wbt.c:rwb_arm_timer
  - drivers/mmc/host/sdhci.c:sdhci_send_command
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
**Symbols:**

```
c03e5300-c03e5360: nsecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int nsecs_to_jiffies(u64 n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c0000000001fa320)
Location: kernel/time/time.c:844
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_poll_work
  - kernel/sched/psi.c:psi_avgs_work
  - kernel/sched/psi.c:collect_percpu_times
  - block/blk-wbt.c:rwb_arm_timer
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
**Symbols:**

```
c0000000001fa320-c0000000001fa348: nsecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int nsecs_to_jiffies(u64 n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffe00012a526)
Location: kernel/time/time.c:844
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_poll_work
  - kernel/sched/psi.c:psi_avgs_work
  - kernel/sched/psi.c:collect_percpu_times
  - block/blk-wbt.c:rwb_arm_timer
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
**Symbols:**

```
ffffffe00012a526-ffffffe00012a552: nsecs_to_jiffies (STB_GLOBAL)
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
long unsigned int nsecs_to_jiffies(u64 n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8112ad40)
Location: kernel/time/time.c:844
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_poll_work
  - kernel/sched/psi.c:psi_avgs_work
  - kernel/sched/psi.c:collect_percpu_times
  - block/blk-wbt.c:rwb_arm_timer
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
**Symbols:**

```
ffffffff8112ad40-ffffffff8112ad62: nsecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int nsecs_to_jiffies(u64 n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111d5b0)
Location: kernel/time/time.c:844
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_poll_work
  - kernel/sched/psi.c:psi_avgs_work
  - kernel/sched/psi.c:collect_percpu_times
  - block/blk-wbt.c:rwb_arm_timer
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
**Symbols:**

```
ffffffff8111d5b0-ffffffff8111d5d2: nsecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int nsecs_to_jiffies(u64 n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81128a60)
Location: kernel/time/time.c:844
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_poll_work
  - kernel/sched/psi.c:psi_avgs_work
  - kernel/sched/psi.c:collect_percpu_times
  - block/blk-wbt.c:rwb_arm_timer
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
**Symbols:**

```
ffffffff81128a60-ffffffff81128a82: nsecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int nsecs_to_jiffies(u64 n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811350b0)
Location: kernel/time/time.c:844
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_poll_work
  - kernel/sched/psi.c:psi_avgs_work
  - kernel/sched/psi.c:collect_percpu_times
  - block/blk-wbt.c:rwb_arm_timer
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_output.c:tcp_send_probe0
  - net/ipv4/tcp_output.c:__tcp_push_pending_frames
```
**Symbols:**

```
ffffffff811350b0-ffffffff811350d2: nsecs_to_jiffies (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
