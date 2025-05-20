# Function: <code>set_cpu_sd_state_idle</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void set_cpu_sd_state_idle();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810be510)
Location: kernel/sched/fair.c:7516
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_enter
```
**Symbols:**

```
ffffffff810be510-ffffffff810be556: set_cpu_sd_state_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void set_cpu_sd_state_idle();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c1d00)
Location: kernel/sched/fair.c:7978
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_enter
```
**Symbols:**

```
ffffffff810c1d00-ffffffff810c1d46: set_cpu_sd_state_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void set_cpu_sd_state_idle();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c7d10)
Location: kernel/sched/fair.c:8556
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_enter
```
**Symbols:**

```
ffffffff810c7d10-ffffffff810c7d55: set_cpu_sd_state_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void set_cpu_sd_state_idle();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c19b0)
Location: kernel/sched/fair.c:8572
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_enter
```
**Symbols:**

```
ffffffff810c19b0-ffffffff810c19f5: set_cpu_sd_state_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void set_cpu_sd_state_idle();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c9110)
Location: kernel/sched/fair.c:9045
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_enter
```
**Symbols:**

```
ffffffff810c9110-ffffffff810c9155: set_cpu_sd_state_idle (STB_GLOBAL)
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
In kernel/sched/fair.c (ffffffff810d13b2)
Location: kernel/sched/fair.c:9489
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
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
In kernel/sched/fair.c (ffffffff810dacd2)
Location: kernel/sched/fair.c:9592
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
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
In kernel/sched/fair.c (ffffffff810e209b)
Location: kernel/sched/fair.c:9533
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
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
In kernel/sched/fair.c (ffffffff810ebf9b)
Location: kernel/sched/fair.c:9517
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
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
In kernel/sched/fair.c (ffffffff810f67ab)
Location: kernel/sched/fair.c:10203
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
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
In kernel/sched/fair.c (ffffffff810f493b)
Location: kernel/sched/fair.c:10317
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
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
In kernel/sched/fair.c (ffffffff810f69ad)
Location: kernel/sched/fair.c:10356
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
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
In kernel/sched/fair.c (ffffffff811108d9)
Location: kernel/sched/fair.c:10598
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
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
In kernel/sched/fair.c (ffffffff8112ca76)
Location: kernel/sched/fair.c:10703
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
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
In kernel/sched/fair.c (ffffffff81156766)
Location: kernel/sched/fair.c:11231
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
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
In kernel/sched/fair.c (ffffffff811667e6)
Location: kernel/sched/fair.c:11535
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
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
In kernel/sched/fair.c (ffffffff81173526)
Location: kernel/sched/fair.c:11999
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
</details>
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
In kernel/sched/fair.c (ffff80001014c408)
Location: kernel/sched/fair.c:9517
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c039a014)
Location: kernel/sched/fair.c:9517
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
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
In kernel/sched/fair.c (c00000000019ed6c)
Location: kernel/sched/fair.c:9517
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
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
In kernel/sched/fair.c (ffffffe0000f5984)
Location: kernel/sched/fair.c:9517
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
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
In kernel/sched/fair.c (ffffffff810e60fb)
Location: kernel/sched/fair.c:9517
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
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
In kernel/sched/fair.c (ffffffff810d529b)
Location: kernel/sched/fair.c:9517
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
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
In kernel/sched/fair.c (ffffffff810e24cb)
Location: kernel/sched/fair.c:9517
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
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
In kernel/sched/fair.c (ffffffff810ee06b)
Location: kernel/sched/fair.c:9517
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
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
</ul>
