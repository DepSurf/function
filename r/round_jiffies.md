# Function: <code>round_jiffies</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int round_jiffies(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810eb680)
Location: kernel/time/timer.c:262
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:__restart_timer
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_start_timer
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/ipv6/ip6_fib.c:fib6_run_gc
```
**Symbols:**

```
ffffffff810eb680-ffffffff810eb6e7: round_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int round_jiffies(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810f23b0)
Location: kernel/time/timer.c:360
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_start_timer
  - arch/x86/kernel/cpu/mcheck/mce.c:__restart_timer
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv6/ip6_fib.c:fib6_run_gc
```
**Symbols:**

```
ffffffff810f23b0-ffffffff810f241f: round_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int round_jiffies(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810f9530)
Location: kernel/time/timer.c:360
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:__start_timer
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv6/ip6_fib.c:fib6_run_gc
```
**Symbols:**

```
ffffffff810f9530-ffffffff810f959f: round_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int round_jiffies(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810fba50)
Location: kernel/time/timer.c:363
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:__start_timer
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv6/ip6_fib.c:fib6_run_gc
```
**Symbols:**

```
ffffffff810fba50-ffffffff810fbabf: round_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int round_jiffies(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81106340)
Location: kernel/time/timer.c:363
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:__start_timer
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv6/ip6_fib.c:fib6_run_gc
```
**Symbols:**

```
ffffffff81106340-ffffffff811063af: round_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int round_jiffies(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81111950)
Location: kernel/time/timer.c:380
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:__start_timer
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv6/ip6_fib.c:fib6_run_gc
```
**Symbols:**

```
ffffffff81111950-ffffffff811119c8: round_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int round_jiffies(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8111cf90)
Location: kernel/time/timer.c:379
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:__start_timer
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv6/ip6_fib.c:fib6_run_gc
```
**Symbols:**

```
ffffffff8111cf90-ffffffff8111d008: round_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int round_jiffies(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81127c20)
Location: kernel/time/timer.c:379
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:__start_timer
  - drivers/ras/cec.c:cec_mod_work
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv6/ip6_fib.c:fib6_run_gc
```
**Symbols:**

```
ffffffff81127c20-ffffffff81127c8c: round_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int round_jiffies(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81133bc0)
Location: kernel/time/timer.c:383
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:__start_timer
  - drivers/ras/cec.c:cec_mod_work
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv6/ip6_fib.c:fib6_run_gc
```
**Symbols:**

```
ffffffff81133bc0-ffffffff81133c2c: round_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int round_jiffies(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81144ba0)
Location: kernel/time/timer.c:383
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:__start_timer
  - drivers/ras/cec.c:decay_interval_set
  - drivers/ras/cec.c:cec_work_fn
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv6/ip6_fib.c:fib6_run_gc
```
**Symbols:**

```
ffffffff81144ba0-ffffffff81144c0b: round_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int round_jiffies(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81140ca0)
Location: kernel/time/timer.c:384
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:__start_timer
  - lib/random32.c:prandom_reseed
  - drivers/ras/cec.c:decay_interval_set
  - drivers/ras/cec.c:cec_work_fn
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv6/ip6_fib.c:fib6_run_gc
```
**Symbols:**

```
ffffffff81140ca0-ffffffff81140d0b: round_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int round_jiffies(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81141ea0)
Location: kernel/time/timer.c:385
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:__start_timer
  - lib/random32.c:prandom_reseed
  - drivers/thermal/thermal_helpers.c:thermal_set_delay_jiffies
  - drivers/ras/cec.c:decay_interval_set
  - drivers/ras/cec.c:cec_work_fn
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv6/ip6_fib.c:fib6_run_gc
```
**Symbols:**

```
ffffffff81141ea0-ffffffff81141f0c: round_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int round_jiffies(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81165390)
Location: kernel/time/timer.c:385
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:__start_timer
  - lib/random32.c:prandom_reseed
  - drivers/thermal/thermal_helpers.c:thermal_set_delay_jiffies
  - drivers/ras/cec.c:decay_interval_set
  - drivers/ras/cec.c:cec_work_fn
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv6/ip6_fib.c:fib6_run_gc
```
**Symbols:**

```
ffffffff81165390-ffffffff811653fc: round_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int round_jiffies(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811995c0)
Location: kernel/time/timer.c:408
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:__start_timer
  - drivers/thermal/thermal_helpers.c:thermal_set_delay_jiffies
  - drivers/ras/cec.c:decay_interval_set
  - drivers/ras/cec.c:cec_work_fn
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv6/ip6_fib.c:fib6_run_gc
```
**Symbols:**

```
ffffffff811995c0-ffffffff81199647: round_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int round_jiffies(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811d7bc0)
Location: kernel/time/timer.c:408
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:__start_timer
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/ras/cec.c:decay_interval_set
  - drivers/ras/cec.c:cec_work_fn
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv6/ip6_fib.c:fib6_run_gc
```
**Symbols:**

```
ffffffff811d7bc0-ffffffff811d7c47: round_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int round_jiffies(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811ec030)
Location: kernel/time/timer.c:408
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:__start_timer
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/ras/cec.c:decay_interval_set
  - drivers/ras/cec.c:cec_work_fn
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv6/ip6_fib.c:fib6_run_gc
```
**Symbols:**

```
ffffffff811ec030-ffffffff811ec0b7: round_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int round_jiffies(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81201fb0)
Location: kernel/time/timer.c:408
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:__start_timer
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/ras/cec.c:decay_interval_set
  - drivers/ras/cec.c:cec_work_fn
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv6/ip6_fib.c:fib6_run_gc
```
**Symbols:**

```
ffffffff81201fb0-ffffffff8120203b: round_jiffies (STB_GLOBAL)
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
long unsigned int round_jiffies(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffff80001019d730)
Location: kernel/time/timer.c:383
Inline: False
Direct callers:
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv6/ip6_fib.c:fib6_run_gc
```
**Symbols:**

```
ffff80001019d730-ffff80001019d7c8: round_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int round_jiffies(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c03e5f44)
Location: kernel/time/timer.c:383
Inline: False
Direct callers:
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv6/ip6_fib.c:fib6_run_gc
```
**Symbols:**

```
c03e5f44-c03e5fb4: round_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int round_jiffies(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c0000000001fbdd0)
Location: kernel/time/timer.c:383
Inline: False
Direct callers:
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv6/ip6_fib.c:fib6_run_gc
```
**Symbols:**

```
c0000000001fbdd0-c0000000001fbe4c: round_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int round_jiffies(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffe00012adc0)
Location: kernel/time/timer.c:383
Inline: False
Direct callers:
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv6/ip6_fib.c:fib6_run_gc
```
**Symbols:**

```
ffffffe00012adc0-ffffffe00012ae1c: round_jiffies (STB_GLOBAL)
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
long unsigned int round_jiffies(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112c370)
Location: kernel/time/timer.c:383
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:__start_timer
  - drivers/ras/cec.c:cec_mod_work
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv6/ip6_fib.c:fib6_run_gc
```
**Symbols:**

```
ffffffff8112c370-ffffffff8112c3dc: round_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int round_jiffies(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8111ebe0)
Location: kernel/time/timer.c:383
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:__start_timer
  - drivers/ras/cec.c:cec_mod_work
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv6/ip6_fib.c:fib6_run_gc
```
**Symbols:**

```
ffffffff8111ebe0-ffffffff8111ec4c: round_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int round_jiffies(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112a090)
Location: kernel/time/timer.c:383
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:__start_timer
  - drivers/ras/cec.c:cec_mod_work
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv6/ip6_fib.c:fib6_run_gc
```
**Symbols:**

```
ffffffff8112a090-ffffffff8112a0fc: round_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int round_jiffies(long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811366e0)
Location: kernel/time/timer.c:383
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:__start_timer
  - drivers/ras/cec.c:cec_mod_work
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv6/ip6_fib.c:fib6_run_gc
```
**Symbols:**

```
ffffffff811366e0-ffffffff81136750: round_jiffies (STB_GLOBAL)
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
