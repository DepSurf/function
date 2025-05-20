# Function: <code>timer_shutdown</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int timer_shutdown(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811d6ed0)
Location: kernel/time/timer.c:1380
Inline: False
```
**Symbols:**

```
ffffffff811d6ed0-ffffffff811d6f5f: timer_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int timer_shutdown(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811eb360)
Location: kernel/time/timer.c:1380
Inline: False
```
**Symbols:**

```
ffffffff811eb360-ffffffff811eb3e5: timer_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int timer_shutdown(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81201390)
Location: kernel/time/timer.c:1380
Inline: False
```
**Symbols:**

```
ffffffff81201390-ffffffff81201415: timer_shutdown (STB_GLOBAL)
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
In drivers/clocksource/arm_arch_timer.c (ffff800010b67420)
Location: drivers/clocksource/arm_arch_timer.c:667
Inline: True
Inline callers:
  - drivers/clocksource/arm_arch_timer.c:arch_timer_shutdown_phys_mem
  - drivers/clocksource/arm_arch_timer.c:arch_timer_shutdown_virt_mem
  - drivers/clocksource/arm_arch_timer.c:arch_timer_shutdown_phys
  - drivers/clocksource/arm_arch_timer.c:arch_timer_shutdown_virt
```
```
In drivers/clocksource/timer-sp804.c (ffff800010b68060)
Location: drivers/clocksource/timer-sp804.c:125
Inline: True
Inline callers:
  - drivers/clocksource/timer-sp804.c:sp804_set_periodic
  - drivers/clocksource/timer-sp804.c:sp804_shutdown
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
In drivers/clocksource/arm_arch_timer.c (c0c4b1cc)
Location: drivers/clocksource/arm_arch_timer.c:667
Inline: True
Inline callers:
  - drivers/clocksource/arm_arch_timer.c:arch_timer_shutdown_phys_mem
  - drivers/clocksource/arm_arch_timer.c:arch_timer_shutdown_virt_mem
  - drivers/clocksource/arm_arch_timer.c:arch_timer_shutdown_phys
  - drivers/clocksource/arm_arch_timer.c:arch_timer_shutdown_virt
```
```
In drivers/clocksource/timer-sp804.c (c0c4bc10)
Location: drivers/clocksource/timer-sp804.c:125
Inline: True
Inline callers:
  - drivers/clocksource/timer-sp804.c:sp804_set_periodic
  - drivers/clocksource/timer-sp804.c:sp804_shutdown
```
</details>
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
