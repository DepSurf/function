# Function: <code>account_steal_time</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void account_steal_time(cputime_t cputime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810b1870)
Location: kernel/sched/cputime.c:235
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_process_tick
  - kernel/sched/cputime.c:account_steal_ticks
```
**Symbols:**

```
ffffffff810b1870-ffffffff810b188e: account_steal_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void account_steal_time(cputime_t cputime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810b46a9)
Location: kernel/sched/cputime.c:244
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_idle_ticks
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810b4320-ffffffff810b433e: account_steal_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void account_steal_time(cputime_t cputime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810bac89)
Location: kernel/sched/cputime.c:223
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_idle_ticks
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810ba930-ffffffff810ba94e: account_steal_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void account_steal_time(u64 cputime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810b5539)
Location: kernel/sched/cputime.c:210
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_idle_ticks
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810b5200-ffffffff810b521e: account_steal_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void account_steal_time(u64 cputime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810bc6e9)
Location: kernel/sched/cputime.c:210
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_idle_ticks
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810bc3b0-ffffffff810bc3ce: account_steal_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void account_steal_time(u64 cputime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810c3dc0)
Location: kernel/sched/cputime.c:206
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_idle_ticks
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810c3a80-ffffffff810c3a9e: account_steal_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void account_steal_time(u64 cputime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810cd080)
Location: kernel/sched/cputime.c:206
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_idle_ticks
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810ccd40-ffffffff810ccd5e: account_steal_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void account_steal_time(u64 cputime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810d5469)
Location: kernel/sched/cputime.c:207
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_idle_ticks
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810d5120-ffffffff810d513e: account_steal_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void account_steal_time(u64 cputime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810dfa29)
Location: kernel/sched/cputime.c:207
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_idle_ticks
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810df6e0-ffffffff810df6fe: account_steal_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void account_steal_time(u64 cputime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810e7d3d)
Location: kernel/sched/cputime.c:207
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_idle_ticks
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810e7a30-ffffffff810e7a4e: account_steal_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void account_steal_time(u64 cputime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810e5a2d)
Location: kernel/sched/cputime.c:208
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_idle_ticks
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810e5720-ffffffff810e573e: account_steal_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void account_steal_time(u64 cputime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810e79f8)
Location: kernel/sched/cputime.c:208
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_idle_ticks
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810e76f0-ffffffff810e770e: account_steal_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void account_steal_time(u64 cputime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810ff085)
Location: kernel/sched/cputime.c:208
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_idle_ticks
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810fed90-ffffffff810fedae: account_steal_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void account_steal_time(u64 cputime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81139995)
Location: kernel/sched/cputime.c:207
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:account_idle_ticks
  - kernel/sched/build_policy.c:account_process_tick
```
**Symbols:**

```
ffffffff81139640-ffffffff81139666: account_steal_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void account_steal_time(u64 cputime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81164175)
Location: kernel/sched/cputime.c:207
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:account_idle_ticks
  - kernel/sched/build_policy.c:account_process_tick
```
**Symbols:**

```
ffffffff81163d60-ffffffff81163d86: account_steal_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void account_steal_time(u64 cputime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81174955)
Location: kernel/sched/cputime.c:211
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:account_idle_ticks
  - kernel/sched/build_policy.c:account_process_tick
```
**Symbols:**

```
ffffffff81174540-ffffffff81174566: account_steal_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void account_steal_time(u64 cputime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff811762ef)
Location: kernel/sched/cputime.c:211
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:get_vtime_delta
  - kernel/sched/build_policy.c:account_idle_ticks
  - kernel/sched/build_policy.c:account_process_tick
```
**Symbols:**

```
ffffffff81181f80-ffffffff81181fa6: account_steal_time (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void account_steal_time(u64 cputime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffff80001013f450)
Location: kernel/sched/cputime.c:207
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_idle_ticks
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffff80001013f058-ffff80001013f098: account_steal_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void account_steal_time(u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (c038f020)
Location: kernel/sched/cputime.c:207
Inline: False
```
**Symbols:**

```
c038f020-c038f060: account_steal_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void account_steal_time(u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (c00000000018e200)
Location: kernel/sched/cputime.c:207
Inline: False
```
**Symbols:**

```
c00000000018e200-c00000000018e230: account_steal_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void account_steal_time(u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffe0000ed7b8)
Location: kernel/sched/cputime.c:207
Inline: False
```
**Symbols:**

```
ffffffe0000ed7b8-ffffffe0000ed7fe: account_steal_time (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void account_steal_time(u64 cputime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810d9c19)
Location: kernel/sched/cputime.c:207
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_idle_ticks
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810d98d0-ffffffff810d98ee: account_steal_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void account_steal_time(u64 cputime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810c8699)
Location: kernel/sched/cputime.c:207
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_idle_ticks
  - kernel/sched/cputime.c:account_process_tick
Direct callers:
  - kernel/sched/cputime.c:get_vtime_delta
```
**Symbols:**

```
ffffffff810c82b0-ffffffff810c82ce: account_steal_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void account_steal_time(u64 cputime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810d5f59)
Location: kernel/sched/cputime.c:207
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_idle_ticks
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810d5c10-ffffffff810d5c2e: account_steal_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void account_steal_time(u64 cputime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810e1869)
Location: kernel/sched/cputime.c:207
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_idle_ticks
  - kernel/sched/cputime.c:account_process_tick
```
**Symbols:**

```
ffffffff810e1520-ffffffff810e153e: account_steal_time (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>cputime_t cputime</code> ➡️ <code>u64 cputime</code>
</li>
</ul>
</details>
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
