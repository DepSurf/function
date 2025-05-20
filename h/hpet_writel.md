# Function: <code>hpet_writel</code>

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
In arch/x86/kernel/hpet.c (ffffffff81061df3)
Location: arch/x86/kernel/hpet.c:67
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_legacy_shutdown
  - arch/x86/kernel/hpet.c:hpet_legacy_set_oneshot
  - arch/x86/kernel/hpet.c:hpet_legacy_next_event
  - arch/x86/kernel/hpet.c:hpet_msi_shutdown
  - arch/x86/kernel/hpet.c:hpet_msi_set_oneshot
  - arch/x86/kernel/hpet.c:hpet_msi_next_event
  - arch/x86/kernel/hpet.c:hpet_resume
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_msi_unmask
  - arch/x86/kernel/hpet.c:hpet_msi_mask
  - arch/x86/kernel/hpet.c:hpet_msi_write
  - arch/x86/kernel/hpet.c:hpet_msi_write
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
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
In arch/x86/kernel/hpet.c (ffffffff8106252b)
Location: arch/x86/kernel/hpet.c:67
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_msi_next_event
  - arch/x86/kernel/hpet.c:hpet_msi_set_oneshot
  - arch/x86/kernel/hpet.c:hpet_msi_shutdown
  - arch/x86/kernel/hpet.c:hpet_msi_write
  - arch/x86/kernel/hpet.c:hpet_msi_write
  - arch/x86/kernel/hpet.c:hpet_msi_mask
  - arch/x86/kernel/hpet.c:hpet_msi_unmask
  - arch/x86/kernel/hpet.c:hpet_legacy_next_event
  - arch/x86/kernel/hpet.c:hpet_legacy_set_oneshot
  - arch/x86/kernel/hpet.c:hpet_legacy_shutdown
  - arch/x86/kernel/hpet.c:hpet_resume
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
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
In arch/x86/kernel/hpet.c (ffffffff8106559b)
Location: arch/x86/kernel/hpet.c:67
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_msi_next_event
  - arch/x86/kernel/hpet.c:hpet_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_set_oneshot
  - arch/x86/kernel/hpet.c:hpet_msi_shutdown
  - arch/x86/kernel/hpet.c:hpet_msi_write
  - arch/x86/kernel/hpet.c:hpet_msi_write
  - arch/x86/kernel/hpet.c:hpet_msi_mask
  - arch/x86/kernel/hpet.c:hpet_msi_unmask
  - arch/x86/kernel/hpet.c:hpet_legacy_next_event
  - arch/x86/kernel/hpet.c:hpet_legacy_resume
  - arch/x86/kernel/hpet.c:hpet_legacy_set_oneshot
  - arch/x86/kernel/hpet.c:hpet_legacy_shutdown
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
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
In arch/x86/kernel/hpet.c (ffffffff810644e1)
Location: arch/x86/kernel/hpet.c:67
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_msi_next_event
  - arch/x86/kernel/hpet.c:hpet_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_set_oneshot
  - arch/x86/kernel/hpet.c:hpet_msi_shutdown
  - arch/x86/kernel/hpet.c:hpet_msi_mask
  - arch/x86/kernel/hpet.c:hpet_legacy_next_event
  - arch/x86/kernel/hpet.c:hpet_legacy_resume
  - arch/x86/kernel/hpet.c:hpet_legacy_set_oneshot
  - arch/x86/kernel/hpet.c:hpet_legacy_shutdown
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
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
In arch/x86/kernel/hpet.c (ffffffff81068661)
Location: arch/x86/kernel/hpet.c:67
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_msi_next_event
  - arch/x86/kernel/hpet.c:hpet_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_set_oneshot
  - arch/x86/kernel/hpet.c:hpet_msi_shutdown
  - arch/x86/kernel/hpet.c:hpet_msi_mask
  - arch/x86/kernel/hpet.c:hpet_legacy_next_event
  - arch/x86/kernel/hpet.c:hpet_legacy_resume
  - arch/x86/kernel/hpet.c:hpet_legacy_set_oneshot
  - arch/x86/kernel/hpet.c:hpet_legacy_shutdown
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
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
In arch/x86/kernel/hpet.c (ffffffff8106b1b1)
Location: arch/x86/kernel/hpet.c:68
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_msi_next_event
  - arch/x86/kernel/hpet.c:hpet_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_set_oneshot
  - arch/x86/kernel/hpet.c:hpet_msi_shutdown
  - arch/x86/kernel/hpet.c:hpet_msi_mask
  - arch/x86/kernel/hpet.c:hpet_legacy_next_event
  - arch/x86/kernel/hpet.c:hpet_legacy_resume
  - arch/x86/kernel/hpet.c:hpet_legacy_set_oneshot
  - arch/x86/kernel/hpet.c:hpet_legacy_shutdown
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
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
In arch/x86/kernel/hpet.c (ffffffff81070f41)
Location: arch/x86/kernel/hpet.c:64
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_msi_next_event
  - arch/x86/kernel/hpet.c:hpet_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_set_oneshot
  - arch/x86/kernel/hpet.c:hpet_msi_shutdown
  - arch/x86/kernel/hpet.c:hpet_msi_mask
  - arch/x86/kernel/hpet.c:hpet_legacy_next_event
  - arch/x86/kernel/hpet.c:hpet_legacy_resume
  - arch/x86/kernel/hpet.c:hpet_legacy_set_oneshot
  - arch/x86/kernel/hpet.c:hpet_legacy_shutdown
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
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
In arch/x86/kernel/hpet.c (ffffffff81074ec3)
Location: arch/x86/kernel/hpet.c:80
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_mask
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_shutdown
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_oneshot
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
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
In arch/x86/kernel/hpet.c (ffffffff81075e93)
Location: arch/x86/kernel/hpet.c:80
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_mask
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_shutdown
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_oneshot
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
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
In arch/x86/kernel/hpet.c (ffffffff8107ce00)
Location: arch/x86/kernel/hpet.c:80
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_timer_reinit
  - arch/x86/kernel/hpet.c:hpet_rtc_timer_reinit
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_mask
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_shutdown
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_oneshot
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
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
In arch/x86/kernel/hpet.c (ffffffff8107ccba)
Location: arch/x86/kernel/hpet.c:81
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_timer_reinit
  - arch/x86/kernel/hpet.c:hpet_rtc_timer_reinit
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_write_msg
  - arch/x86/kernel/hpet.c:hpet_msi_write_msg
  - arch/x86/kernel/hpet.c:hpet_msi_mask
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_shutdown
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_oneshot
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
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
In arch/x86/kernel/hpet.c (ffffffff8107ddd8)
Location: arch/x86/kernel/hpet.c:81
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_write_msg
  - arch/x86/kernel/hpet.c:hpet_msi_write_msg
  - arch/x86/kernel/hpet.c:hpet_msi_mask
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_shutdown
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_oneshot
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
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
In arch/x86/kernel/hpet.c (ffffffff8108c748)
Location: arch/x86/kernel/hpet.c:82
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_write_msg
  - arch/x86/kernel/hpet.c:hpet_msi_write_msg
  - arch/x86/kernel/hpet.c:hpet_msi_mask
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_shutdown
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_oneshot
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
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
In arch/x86/kernel/hpet.c (ffffffff8109d130)
Location: arch/x86/kernel/hpet.c:82
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_write_msg
  - arch/x86/kernel/hpet.c:hpet_msi_write_msg
  - arch/x86/kernel/hpet.c:hpet_msi_mask
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_shutdown
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_oneshot
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
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
In arch/x86/kernel/hpet.c (ffffffff810b41d0)
Location: arch/x86/kernel/hpet.c:82
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_write_msg
  - arch/x86/kernel/hpet.c:hpet_msi_write_msg
  - arch/x86/kernel/hpet.c:hpet_msi_mask
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_shutdown
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_oneshot
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
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
In arch/x86/kernel/hpet.c (ffffffff810b72d0)
Location: arch/x86/kernel/hpet.c:82
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_write_msg
  - arch/x86/kernel/hpet.c:hpet_msi_write_msg
  - arch/x86/kernel/hpet.c:hpet_msi_mask
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_shutdown
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_oneshot
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
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
In arch/x86/kernel/hpet.c (ffffffff810be710)
Location: arch/x86/kernel/hpet.c:82
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_write_msg
  - arch/x86/kernel/hpet.c:hpet_msi_write_msg
  - arch/x86/kernel/hpet.c:hpet_msi_mask
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_shutdown
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_oneshot
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In arch/x86/kernel/hpet.c (ffffffff81074e93)
Location: arch/x86/kernel/hpet.c:80
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_mask
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_shutdown
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_oneshot
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
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
In arch/x86/kernel/hpet.c (ffffffff81064ec3)
Location: arch/x86/kernel/hpet.c:80
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_mask
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_shutdown
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_oneshot
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
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
In arch/x86/kernel/hpet.c (ffffffff81074e43)
Location: arch/x86/kernel/hpet.c:80
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_mask
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_shutdown
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_oneshot
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
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
In arch/x86/kernel/hpet.c (ffffffff81076ea3)
Location: arch/x86/kernel/hpet.c:80
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_disable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_mask
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_next_event
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_shutdown
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_oneshot
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
  - arch/x86/kernel/hpet.c:hpet_restart_counter
```
</details>
</li>
</ul>

## Differences
