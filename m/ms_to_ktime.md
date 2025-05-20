# Function: <code>ms_to_ktime</code>

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
In arch/x86/events/intel/cqm.c (0)
Location: include/linux/ktime.h:290
Inline: True
```
```
In arch/x86/events/intel/rapl.c (0)
Location: include/linux/ktime.h:290
Inline: True
```
```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/ktime.h:290
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
In arch/x86/events/intel/cqm.c (0)
Location: include/linux/ktime.h:290
Inline: True
```
```
In drivers/mailbox/mailbox.c (ffffffff817503b0)
Location: include/linux/ktime.h:290
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
In arch/x86/events/intel/cqm.c (0)
Location: include/linux/ktime.h:267
Inline: True
```
```
In kernel/sched/idle.c (ffffffff810cdbac)
Location: include/linux/ktime.h:267
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
```
```
In drivers/acpi/button.c (ffffffff8151cf44)
Location: include/linux/ktime.h:267
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_notify_state
```
```
In drivers/mailbox/mailbox.c (ffffffff8177bf70)
Location: include/linux/ktime.h:267
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
In kernel/sched/idle.c (ffffffff810ca5bc)
Location: include/linux/ktime.h:267
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
```
```
In drivers/acpi/button.c (0)
Location: include/linux/ktime.h:267
Inline: True
```
```
In drivers/mailbox/mailbox.c (ffffffff8179aad9)
Location: include/linux/ktime.h:267
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
In kernel/sched/idle.c (ffffffff810d1dcc)
Location: include/linux/ktime.h:267
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
```
```
In drivers/acpi/button.c (0)
Location: include/linux/ktime.h:267
Inline: True
```
```
In drivers/mailbox/mailbox.c (ffffffff81810ea0)
Location: include/linux/ktime.h:267
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
In kernel/sched/idle.c (ffffffff810c4576)
Location: include/linux/ktime.h:267
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
```
```
In drivers/acpi/button.c (0)
Location: include/linux/ktime.h:267
Inline: True
```
```
In drivers/char/tpm/tpm_crb.c (0)
Location: include/linux/ktime.h:267
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff817ee9d5)
Location: include/linux/ktime.h:267
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
```
```
In drivers/mailbox/mailbox.c (ffffffff8185ad24)
Location: include/linux/ktime.h:267
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
In kernel/sched/idle.c (ffffffff810cd836)
Location: include/linux/ktime.h:270
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
```
```
In drivers/acpi/button.c (0)
Location: include/linux/ktime.h:270
Inline: True
```
```
In drivers/char/tpm/tpm_crb.c (0)
Location: include/linux/ktime.h:270
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8181a8a5)
Location: include/linux/ktime.h:270
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
```
```
In drivers/mailbox/mailbox.c (ffffffff8187a124)
Location: include/linux/ktime.h:270
Inline: True
```
```
In drivers/powercap/idle_inject.c (ffffffff81883df0)
Location: include/linux/ktime.h:270
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_start
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
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
In kernel/sched/idle.c (ffffffff810d5c26)
Location: include/linux/ktime.h:270
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
```
```
In drivers/acpi/button.c (0)
Location: include/linux/ktime.h:270
Inline: True
```
```
In drivers/char/tpm/tpm_crb.c (0)
Location: include/linux/ktime.h:270
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8185ca98)
Location: include/linux/ktime.h:270
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
```
```
In drivers/mailbox/mailbox.c (ffffffff818bf6d4)
Location: include/linux/ktime.h:270
Inline: True
```
```
In drivers/powercap/idle_inject.c (ffffffff818ce4fe)
Location: include/linux/ktime.h:270
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_start
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
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
In drivers/acpi/button.c (0)
Location: include/linux/ktime.h:270
Inline: True
```
```
In drivers/char/tpm/tpm_crb.c (0)
Location: include/linux/ktime.h:270
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8188e8a8)
Location: include/linux/ktime.h:270
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
```
```
In drivers/mailbox/mailbox.c (ffffffff818f2224)
Location: include/linux/ktime.h:270
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
In drivers/acpi/button.c (ffffffff816def20)
Location: include/linux/ktime.h:226
Inline: True
```
```
In drivers/char/tpm/tpm_crb.c (0)
Location: include/linux/ktime.h:226
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8195d548)
Location: include/linux/ktime.h:226
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
```
```
In drivers/mailbox/mailbox.c (ffffffff819c7bb4)
Location: include/linux/ktime.h:226
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:txdone_hrtimer
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
In drivers/acpi/button.c (ffffffff816fcf40)
Location: include/linux/ktime.h:227
Inline: True
```
```
In drivers/char/tpm/tpm_crb.c (0)
Location: include/linux/ktime.h:227
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff819641c4)
Location: include/linux/ktime.h:227
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_set_last_hw_keepalive
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
```
```
In drivers/mailbox/mailbox.c (ffffffff819c7b07)
Location: include/linux/ktime.h:227
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:txdone_hrtimer
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
In drivers/acpi/button.c (ffffffff816ded0a)
Location: include/linux/ktime.h:227
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8175ec90)
Location: include/linux/ktime.h:227
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:__stop_tx_rs485
```
```
In drivers/char/tpm/tpm_crb.c (0)
Location: include/linux/ktime.h:227
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff819485e4)
Location: include/linux/ktime.h:227
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_set_last_hw_keepalive
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
```
```
In drivers/mailbox/mailbox.c (ffffffff819aca47)
Location: include/linux/ktime.h:227
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:txdone_hrtimer
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
In drivers/acpi/button.c (ffffffff81756eaa)
Location: include/linux/ktime.h:227
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff817e30f0)
Location: include/linux/ktime.h:227
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:__stop_tx_rs485
```
```
In drivers/char/tpm/tpm_crb.c (0)
Location: include/linux/ktime.h:227
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff819ed308)
Location: include/linux/ktime.h:227
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
```
```
In drivers/mailbox/mailbox.c (ffffffff81a5af57)
Location: include/linux/ktime.h:227
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:txdone_hrtimer
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
In drivers/acpi/button.c (ffffffff81889fea)
Location: include/linux/ktime.h:227
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81923f1e)
Location: include/linux/ktime.h:227
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
```
In drivers/char/tpm/tpm_crb.c (0)
Location: include/linux/ktime.h:227
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81b53ea4)
Location: include/linux/ktime.h:227
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_set_last_hw_keepalive
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
```
```
In drivers/mailbox/mailbox.c (ffffffff81bca7f9)
Location: include/linux/ktime.h:227
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:txdone_hrtimer
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
In drivers/acpi/button.c (ffffffff819d0a1a)
Location: include/linux/ktime.h:227
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81a809f6)
Location: include/linux/ktime.h:227
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
```
In drivers/char/tpm/tpm_crb.c (0)
Location: include/linux/ktime.h:227
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81cecf54)
Location: include/linux/ktime.h:227
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_set_last_hw_keepalive
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_update_worker
  - drivers/watchdog/watchdog_dev.c:watchdog_update_worker
  - drivers/watchdog/watchdog_dev.c:watchdog_update_worker
```
```
In drivers/mailbox/mailbox.c (ffffffff81d73e99)
Location: include/linux/ktime.h:227
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:txdone_hrtimer
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
In drivers/acpi/button.c (ffffffff81a1807a)
Location: include/linux/ktime.h:227
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81acc016)
Location: include/linux/ktime.h:227
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
```
In drivers/char/tpm/tpm_crb.c (0)
Location: include/linux/ktime.h:227
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81d55c74)
Location: include/linux/ktime.h:227
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_set_last_hw_keepalive
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_update_worker
  - drivers/watchdog/watchdog_dev.c:watchdog_update_worker
  - drivers/watchdog/watchdog_dev.c:watchdog_update_worker
```
```
In drivers/mailbox/mailbox.c (ffffffff81de1b33)
Location: include/linux/ktime.h:227
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:txdone_hrtimer
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
In kernel/time/alarmtimer.c (ffffffff8120f227)
Location: include/linux/ktime.h:225
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_suspend
```
```
In drivers/acpi/button.c (ffffffff81a632ea)
Location: include/linux/ktime.h:225
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81b1e7b6)
Location: include/linux/ktime.h:225
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
```
In drivers/char/tpm/tpm_crb.c (0)
Location: include/linux/ktime.h:225
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81e0cb84)
Location: include/linux/ktime.h:225
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_set_last_hw_keepalive
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_update_worker
  - drivers/watchdog/watchdog_dev.c:watchdog_update_worker
  - drivers/watchdog/watchdog_dev.c:watchdog_update_worker
```
```
In drivers/mailbox/mailbox.c (ffffffff81e97af3)
Location: include/linux/ktime.h:225
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:txdone_hrtimer
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
In drivers/acpi/button.c (0)
Location: include/linux/ktime.h:270
Inline: True
```
```
In drivers/char/tpm/tpm_crb.c (0)
Location: include/linux/ktime.h:270
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffff800010adf150)
Location: include/linux/ktime.h:270
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
```
```
In drivers/mailbox/mailbox.c (ffff800010b7a594)
Location: include/linux/ktime.h:270
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
In arch/arm/mm/cache-l2x0-pmu.c (0)
Location: include/linux/ktime.h:270
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (c0bc0c38)
Location: include/linux/ktime.h:270
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
```
```
In drivers/mailbox/mailbox.c (c0c600d0)
Location: include/linux/ktime.h:270
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
In arch/powerpc/kernel/watchdog.c (c000000000036e04)
Location: include/linux/ktime.h:270
Inline: True
Inline callers:
  - arch/powerpc/kernel/watchdog.c:start_watchdog
  - arch/powerpc/kernel/watchdog.c:watchdog_timer_fn
```
```
In drivers/watchdog/watchdog_dev.c (c000000000bc74b4)
Location: include/linux/ktime.h:270
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
```
```
In drivers/mailbox/mailbox.c (c000000000c59b20)
Location: include/linux/ktime.h:270
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
In drivers/watchdog/watchdog_dev.c (ffffffe0006d7326)
Location: include/linux/ktime.h:270
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
```
```
In drivers/mailbox/mailbox.c (ffffffe00072c44a)
Location: include/linux/ktime.h:270
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
In drivers/acpi/button.c (0)
Location: include/linux/ktime.h:270
Inline: True
```
```
In drivers/char/tpm/tpm_crb.c (0)
Location: include/linux/ktime.h:270
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81834728)
Location: include/linux/ktime.h:270
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
```
```
In drivers/mailbox/mailbox.c (ffffffff81893554)
Location: include/linux/ktime.h:270
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
In drivers/acpi/button.c (0)
Location: include/linux/ktime.h:270
Inline: True
```
```
In drivers/char/tpm/tpm_crb.c (0)
Location: include/linux/ktime.h:270
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff817fbdb8)
Location: include/linux/ktime.h:270
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
```
```
In drivers/mailbox/mailbox.c (ffffffff8184ba54)
Location: include/linux/ktime.h:270
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
In drivers/acpi/button.c (0)
Location: include/linux/ktime.h:270
Inline: True
```
```
In drivers/char/tpm/tpm_crb.c (0)
Location: include/linux/ktime.h:270
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81883d58)
Location: include/linux/ktime.h:270
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
```
```
In drivers/mailbox/mailbox.c (ffffffff818e7054)
Location: include/linux/ktime.h:270
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
In drivers/acpi/button.c (0)
Location: include/linux/ktime.h:270
Inline: True
```
```
In drivers/char/tpm/tpm_crb.c (0)
Location: include/linux/ktime.h:270
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8189f818)
Location: include/linux/ktime.h:270
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
```
```
In drivers/mailbox/mailbox.c (ffffffff81903cd4)
Location: include/linux/ktime.h:270
Inline: True
```
</details>
</li>
</ul>

## Differences
