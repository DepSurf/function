# Function: <code>add_timer_on</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void add_timer_on(struct timer_list *timer, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810ec940)
Location: kernel/time/timer.c:978
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:__restart_timer
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_start_timer
  - kernel/workqueue.c:__queue_delayed_work
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_watchdog
```
**Symbols:**

```
ffffffff810ec940-ffffffff810ecabc: add_timer_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void add_timer_on(struct timer_list *timer, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810f3dc0)
Location: kernel/time/timer.c:1118
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_start_timer
  - arch/x86/kernel/cpu/mcheck/mce.c:__restart_timer
  - kernel/workqueue.c:__queue_delayed_work
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
**Symbols:**

```
ffffffff810f3dc0-ffffffff810f3f79: add_timer_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void add_timer_on(struct timer_list *timer, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810faf70)
Location: kernel/time/timer.c:1128
Inline: False
Direct callers:
  - kernel/workqueue.c:__queue_delayed_work
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
**Symbols:**

```
ffffffff810faf70-ffffffff810fb11a: add_timer_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void add_timer_on(struct timer_list *timer, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810fd2f0)
Location: kernel/time/timer.c:1103
Inline: False
Direct callers:
  - kernel/workqueue.c:__queue_delayed_work
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
**Symbols:**

```
ffffffff810fd2f0-ffffffff810fd480: add_timer_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void add_timer_on(struct timer_list *timer, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81108410)
Location: kernel/time/timer.c:1141
Inline: False
Direct callers:
  - kernel/workqueue.c:__queue_delayed_work
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
**Symbols:**

```
ffffffff81108410-ffffffff81108593: add_timer_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void add_timer_on(struct timer_list *timer, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81113940)
Location: kernel/time/timer.c:1149
Inline: False
Direct callers:
  - kernel/workqueue.c:__queue_delayed_work
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
**Symbols:**

```
ffffffff81113940-ffffffff81113ac3: add_timer_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void add_timer_on(struct timer_list *timer, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8111e950)
Location: kernel/time/timer.c:1148
Inline: False
Direct callers:
  - kernel/workqueue.c:__queue_delayed_work
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
**Symbols:**

```
ffffffff8111e950-ffffffff8111ead3: add_timer_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void add_timer_on(struct timer_list *timer, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811298f0)
Location: kernel/time/timer.c:1143
Inline: False
Direct callers:
  - kernel/workqueue.c:__queue_delayed_work
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
**Symbols:**

```
ffffffff811298f0-ffffffff81129a0b: add_timer_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void add_timer_on(struct timer_list *timer, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81135890)
Location: kernel/time/timer.c:1147
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat_enable
  - kernel/workqueue.c:__queue_delayed_work
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
**Symbols:**

```
ffffffff81135890-ffffffff811359ab: add_timer_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void add_timer_on(struct timer_list *timer, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81145770)
Location: kernel/time/timer.c:1159
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat_enable
  - kernel/workqueue.c:__queue_delayed_work
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
**Symbols:**

```
ffffffff81145770-ffffffff811458ab: add_timer_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void add_timer_on(struct timer_list *timer, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81141840)
Location: kernel/time/timer.c:1153
Inline: False
Direct callers:
  - kernel/workqueue.c:__queue_delayed_work
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
**Symbols:**

```
ffffffff81141840-ffffffff8114195f: add_timer_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void add_timer_on(struct timer_list *timer, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81142c90)
Location: kernel/time/timer.c:1155
Inline: False
Direct callers:
  - kernel/workqueue.c:__queue_delayed_work
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
**Symbols:**

```
ffffffff81142c90-ffffffff81142dae: add_timer_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void add_timer_on(struct timer_list *timer, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811661d0)
Location: kernel/time/timer.c:1155
Inline: False
Direct callers:
  - arch/x86/kernel/tsc_sync.c:tsc_sync_check_timer_fn
  - kernel/workqueue.c:__queue_delayed_work
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
**Symbols:**

```
ffffffff811661d0-ffffffff81166340: add_timer_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void add_timer_on(struct timer_list *timer, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81199290)
Location: kernel/time/timer.c:1208
Inline: False
Direct callers:
  - arch/x86/kernel/tsc_sync.c:tsc_sync_check_timer_fn
  - kernel/workqueue.c:__queue_delayed_work
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
**Symbols:**

```
ffffffff81199290-ffffffff8119941e: add_timer_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void add_timer_on(struct timer_list *timer, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811d7960)
Location: kernel/time/timer.c:1257
Inline: False
Direct callers:
  - arch/x86/kernel/tsc_sync.c:tsc_sync_check_timer_fn
  - kernel/workqueue.c:__queue_delayed_work
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/random.c:add_interrupt_randomness
```
**Symbols:**

```
ffffffff811d7960-ffffffff811d7b08: add_timer_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void add_timer_on(struct timer_list *timer, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811ebcb0)
Location: kernel/time/timer.c:1257
Inline: False
Direct callers:
  - arch/x86/kernel/tsc_sync.c:tsc_sync_check_timer_fn
  - kernel/workqueue.c:__queue_delayed_work
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/random.c:add_interrupt_randomness
```
**Symbols:**

```
ffffffff811ebcb0-ffffffff811ebe45: add_timer_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void add_timer_on(struct timer_list *timer, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81201cd0)
Location: kernel/time/timer.c:1257
Inline: False
Direct callers:
  - arch/x86/kernel/tsc_sync.c:tsc_sync_check_timer_fn
  - arch/x86/kernel/apic/vector.c:__vector_schedule_cleanup
  - kernel/workqueue.c:__queue_delayed_work
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/random.c:add_interrupt_randomness
```
**Symbols:**

```
ffffffff81201cd0-ffffffff81201e5c: add_timer_on (STB_GLOBAL)
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
void add_timer_on(struct timer_list *timer, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffff80001019e3f8)
Location: kernel/time/timer.c:1147
Inline: False
Direct callers:
  - kernel/workqueue.c:__queue_delayed_work
```
**Symbols:**

```
ffff80001019e3f8-ffff80001019e578: add_timer_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void add_timer_on(struct timer_list *timer, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c03e7e70)
Location: kernel/time/timer.c:1147
Inline: False
Direct callers:
  - kernel/workqueue.c:__queue_delayed_work
```
**Symbols:**

```
c03e7e70-c03e7fd8: add_timer_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void add_timer_on(struct timer_list *timer, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c0000000001fef70)
Location: kernel/time/timer.c:1147
Inline: False
Direct callers:
  - kernel/workqueue.c:__queue_delayed_work
  - drivers/cpufreq/powernv-cpufreq.c:gpstate_timer_handler
```
**Symbols:**

```
c0000000001fef70-c0000000001ff140: add_timer_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void add_timer_on(struct timer_list *timer, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffe00012cd20)
Location: kernel/time/timer.c:1147
Inline: False
Direct callers:
  - kernel/workqueue.c:__queue_delayed_work
```
**Symbols:**

```
ffffffe00012cd20-ffffffe00012ce78: add_timer_on (STB_GLOBAL)
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
void add_timer_on(struct timer_list *timer, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112e040)
Location: kernel/time/timer.c:1147
Inline: False
Direct callers:
  - kernel/workqueue.c:__queue_delayed_work
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
**Symbols:**

```
ffffffff8112e040-ffffffff8112e15b: add_timer_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void add_timer_on(struct timer_list *timer, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81120ac0)
Location: kernel/time/timer.c:1147
Inline: False
Direct callers:
  - kernel/workqueue.c:__queue_delayed_work
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
**Symbols:**

```
ffffffff81120ac0-ffffffff81120bdb: add_timer_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void add_timer_on(struct timer_list *timer, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112bd60)
Location: kernel/time/timer.c:1147
Inline: False
Direct callers:
  - kernel/workqueue.c:__queue_delayed_work
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
**Symbols:**

```
ffffffff8112bd60-ffffffff8112be7b: add_timer_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void add_timer_on(struct timer_list *timer, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81138650)
Location: kernel/time/timer.c:1147
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat_enable
  - kernel/workqueue.c:__queue_delayed_work
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
**Symbols:**

```
ffffffff81138650-ffffffff81138769: add_timer_on (STB_GLOBAL)
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
