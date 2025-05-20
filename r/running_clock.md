# Function: <code>running_clock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u64 running_clock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810b1530)
Location: kernel/sched/clock.c:432
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_enable
```
**Symbols:**

```
ffffffff810b1530-ffffffff810b153b: running_clock (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u64 running_clock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810b3fb0)
Location: kernel/sched/clock.c:391
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
```
**Symbols:**

```
ffffffff810b3fb0-ffffffff810b3fc2: running_clock (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 running_clock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810ba5f0)
Location: kernel/sched/clock.c:391
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
```
**Symbols:**

```
ffffffff810ba5f0-ffffffff810ba602: running_clock (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 running_clock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810b4e70)
Location: kernel/sched/clock.c:467
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
```
**Symbols:**

```
ffffffff810b4e70-ffffffff810b4e82: running_clock (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 running_clock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810bc160)
Location: kernel/sched/clock.c:467
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
```
**Symbols:**

```
ffffffff810bc160-ffffffff810bc172: running_clock (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 running_clock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810c37f0)
Location: kernel/sched/clock.c:455
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
```
**Symbols:**

```
ffffffff810c37f0-ffffffff810c3802: running_clock (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 running_clock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810ccab0)
Location: kernel/sched/clock.c:478
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:softlockup_fn
```
**Symbols:**

```
ffffffff810ccab0-ffffffff810ccac2: running_clock (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 running_clock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810d4ea0)
Location: kernel/sched/clock.c:479
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:softlockup_fn
```
**Symbols:**

```
ffffffff810d4ea0-ffffffff810d4eb2: running_clock (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 running_clock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810df460)
Location: kernel/sched/clock.c:479
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:softlockup_fn
```
**Symbols:**

```
ffffffff810df460-ffffffff810df472: running_clock (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 running_clock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810e77b0)
Location: kernel/sched/clock.c:479
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:softlockup_fn
```
**Symbols:**

```
ffffffff810e77b0-ffffffff810e77c2: running_clock (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 running_clock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810e53f0)
Location: kernel/sched/clock.c:479
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:softlockup_fn
```
**Symbols:**

```
ffffffff810e53f0-ffffffff810e5402: running_clock (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 running_clock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810e73a0)
Location: kernel/sched/clock.c:479
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:softlockup_fn
  - kernel/watchdog.c:softlockup_fn
```
**Symbols:**

```
ffffffff810e73a0-ffffffff810e73b2: running_clock (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 running_clock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810fe9b0)
Location: kernel/sched/clock.c:479
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:softlockup_fn
  - kernel/watchdog.c:softlockup_fn
```
**Symbols:**

```
ffffffff810fe9b0-ffffffff810fe9c2: running_clock (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 running_clock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81145460)
Location: kernel/sched/clock.c:477
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:softlockup_fn
  - kernel/watchdog.c:softlockup_fn
```
**Symbols:**

```
ffffffff81145460-ffffffff81145478: running_clock (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 running_clock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811725a0)
Location: kernel/sched/clock.c:477
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:softlockup_fn
  - kernel/watchdog.c:softlockup_fn
```
**Symbols:**

```
ffffffff811725a0-ffffffff811725b8: running_clock (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 running_clock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81183600)
Location: kernel/sched/clock.c:502
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:softlockup_fn
  - kernel/watchdog.c:softlockup_fn
```
**Symbols:**

```
ffffffff81183600-ffffffff8118362a: running_clock (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 running_clock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81191d40)
Location: kernel/sched/clock.c:502
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:softlockup_fn
  - kernel/watchdog.c:softlockup_fn
```
**Symbols:**

```
ffffffff81191d40-ffffffff81191d6a: running_clock (STB_WEAK)
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
u64 running_clock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffff80001013ed08)
Location: kernel/sched/clock.c:479
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:__touch_watchdog
```
**Symbols:**

```
ffff80001013ed08-ffff80001013ed1c: running_clock (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 running_clock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (c038ec04)
Location: kernel/sched/clock.c:479
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:__touch_watchdog
```
**Symbols:**

```
c038ec04-c038ec18: running_clock (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long long unsigned int running_clock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/time.c (c00000000002be20)
Location: arch/powerpc/kernel/time.c:737
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:softlockup_fn
```
**Symbols:**

```
c00000000002be20-c00000000002befc: running_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 running_clock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffe0000ed50c)
Location: kernel/sched/clock.c:479
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:__touch_watchdog
```
**Symbols:**

```
ffffffe0000ed50c-ffffffe0000ed524: running_clock (STB_WEAK)
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
u64 running_clock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810d9650)
Location: kernel/sched/clock.c:479
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:softlockup_fn
```
**Symbols:**

```
ffffffff810d9650-ffffffff810d9662: running_clock (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 running_clock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810c8030)
Location: kernel/sched/clock.c:479
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:softlockup_fn
```
**Symbols:**

```
ffffffff810c8030-ffffffff810c8042: running_clock (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 running_clock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810d5990)
Location: kernel/sched/clock.c:479
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:softlockup_fn
```
**Symbols:**

```
ffffffff810d5990-ffffffff810d59a2: running_clock (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 running_clock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810e1280)
Location: kernel/sched/clock.c:479
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:softlockup_fn
```
**Symbols:**

```
ffffffff810e1280-ffffffff810e1292: running_clock (STB_WEAK)
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
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>u64</code> ➡️ <code>long long unsigned int</code>
</li>
</ul>
</details>
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
