# Function: <code>housekeeping_any_cpu</code>

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
In kernel/sched/core.c (0)
Location: include/linux/tick.h:160
Inline: True
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
In kernel/sched/core.c (0)
Location: include/linux/tick.h:239
Inline: True
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
In kernel/sched/core.c (0)
Location: include/linux/tick.h:237
Inline: True
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
In kernel/sched/core.c (0)
Location: include/linux/tick.h:238
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int housekeeping_any_cpu(enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff810dc010)
Location: kernel/sched/isolation.c:21
Inline: True
Direct callers:
  - kernel/sched/core.c:get_nohz_timer_target
```
**Symbols:**

```
ffffffff810dc010-ffffffff810dc049: housekeeping_any_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int housekeeping_any_cpu(enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff810e4650)
Location: kernel/sched/isolation.c:16
Inline: True
Direct callers:
  - kernel/sched/core.c:get_nohz_timer_target
```
**Symbols:**

```
ffffffff810e4650-ffffffff810e4689: housekeeping_any_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int housekeeping_any_cpu(enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff810eedd0)
Location: kernel/sched/isolation.c:16
Inline: True
Direct callers:
  - kernel/sched/core.c:get_nohz_timer_target
```
**Symbols:**

```
ffffffff810eedd0-ffffffff810eee09: housekeeping_any_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int housekeeping_any_cpu(enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff810f5c00)
Location: kernel/sched/isolation.c:23
Inline: True
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/sched/core.c:get_nohz_timer_target
```
**Symbols:**

```
ffffffff810f5c00-ffffffff810f5c38: housekeeping_any_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int housekeeping_any_cpu(enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff81101970)
Location: kernel/sched/isolation.c:23
Inline: True
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/sched/core.c:get_nohz_timer_target
```
**Symbols:**

```
ffffffff81101970-ffffffff811019c5: housekeeping_any_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int housekeeping_any_cpu(enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff8110c200)
Location: kernel/sched/isolation.c:23
Inline: True
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/sched/core.c:get_nohz_timer_target
```
**Symbols:**

```
ffffffff8110c200-ffffffff8110c255: housekeeping_any_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int housekeeping_any_cpu(enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff81109420)
Location: kernel/sched/isolation.c:23
Inline: True
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/sched/core.c:get_nohz_timer_target
```
**Symbols:**

```
ffffffff81109420-ffffffff81109475: housekeeping_any_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int housekeeping_any_cpu(enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff8110b2c0)
Location: kernel/sched/isolation.c:23
Inline: True
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/sched/core.c:get_nohz_timer_target
```
**Symbols:**

```
ffffffff8110b2c0-ffffffff8110b313: housekeeping_any_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int housekeeping_any_cpu(enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff81129b20)
Location: kernel/sched/isolation.c:23
Inline: True
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/sched/core.c:get_nohz_timer_target
```
**Symbols:**

```
ffffffff81129b20-ffffffff81129b70: housekeeping_any_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int housekeeping_any_cpu(enum hk_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/isolation.c:39
Inline: False
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/sched/core.c:get_nohz_timer_target
```
**Symbols:**

```
ffffffff81e594c7-ffffffff81e594df: housekeeping_any_cpu.cold (STB_LOCAL)
ffffffff8114ac50-ffffffff8114acfb: housekeeping_any_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int housekeeping_any_cpu(enum hk_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/isolation.c:39
Inline: False
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/sched/core.c:get_nohz_timer_target
```
**Symbols:**

```
ffffffff82058172-ffffffff8205818a: housekeeping_any_cpu.cold (STB_LOCAL)
ffffffff81179600-ffffffff811796aa: housekeeping_any_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int housekeeping_any_cpu(enum hk_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118a232)
Location: kernel/sched/isolation.c:39
Inline: True
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/sched/core.c:get_nohz_timer_target
```
**Symbols:**

```
ffffffff820d6a54-ffffffff820d6a6c: housekeeping_any_cpu.cold (STB_LOCAL)
ffffffff8118a1f0-ffffffff8118a29f: housekeeping_any_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int housekeeping_any_cpu(enum hk_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81198b32)
Location: kernel/sched/isolation.c:39
Inline: True
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/sched/core.c:get_nohz_timer_target
```
**Symbols:**

```
ffffffff821b1cea-ffffffff821b1d02: housekeeping_any_cpu.cold (STB_LOCAL)
ffffffff81198af0-ffffffff81198b9f: housekeeping_any_cpu (STB_GLOBAL)
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
int housekeeping_any_cpu(enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffff8000101665e8)
Location: kernel/sched/isolation.c:23
Inline: True
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/sched/core.c:get_nohz_timer_target
```
**Symbols:**

```
ffff8000101665e8-ffff800010166684: housekeeping_any_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int housekeeping_any_cpu(enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (c03b29d8)
Location: kernel/sched/isolation.c:23
Inline: True
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/sched/core.c:get_nohz_timer_target
```
**Symbols:**

```
c03b29d8-c03b2a38: housekeeping_any_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int housekeeping_any_cpu(enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (c0000000001bdcc0)
Location: kernel/sched/isolation.c:23
Inline: True
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/sched/core.c:get_nohz_timer_target
```
**Symbols:**

```
c0000000001bdcc0-c0000000001bdd84: housekeeping_any_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int housekeeping_any_cpu(enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffe000108864)
Location: kernel/sched/isolation.c:23
Inline: True
Direct callers:
  - kernel/sched/core.c:get_nohz_timer_target
```
**Symbols:**

```
ffffffe000108864-ffffffe0001088bc: housekeeping_any_cpu (STB_GLOBAL)
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
int housekeeping_any_cpu(enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff810fac80)
Location: kernel/sched/isolation.c:23
Inline: True
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/sched/core.c:get_nohz_timer_target
```
**Symbols:**

```
ffffffff810fac80-ffffffff810facd5: housekeeping_any_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int housekeeping_any_cpu(enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff810eaea0)
Location: kernel/sched/isolation.c:23
Inline: True
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/sched/core.c:get_nohz_timer_target
```
**Symbols:**

```
ffffffff810eaea0-ffffffff810eaef5: housekeeping_any_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int housekeeping_any_cpu(enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff810f7e40)
Location: kernel/sched/isolation.c:23
Inline: True
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/sched/core.c:get_nohz_timer_target
```
**Symbols:**

```
ffffffff810f7e40-ffffffff810f7e95: housekeeping_any_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int housekeeping_any_cpu(enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff81102f80)
Location: kernel/sched/isolation.c:23
Inline: True
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/sched/core.c:get_nohz_timer_target
```
**Symbols:**

```
ffffffff81102f80-ffffffff81102fd5: housekeeping_any_cpu (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum hk_type type</code>
</li>
<li>
<b>Param removed. </b>
<code>enum hk_flags flags</code>
</li>
</ul>
</details>
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
