# Function: <code>flush_smp_call_function_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void flush_smp_call_function_queue(bool warn_cpu_offline);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81103600)
Location: kernel/smp.c:212
Inline: False
Direct callers:
  - kernel/smp.c:hotplug_cfd
  - kernel/smp.c:generic_smp_call_function_single_interrupt
```
**Symbols:**

```
ffffffff81103600-ffffffff81103757: flush_smp_call_function_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void flush_smp_call_function_queue(bool warn_cpu_offline);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8110aae0)
Location: kernel/smp.c:196
Inline: False
Direct callers:
  - kernel/smp.c:generic_smp_call_function_single_interrupt
  - kernel/smp.c:smpcfd_dying_cpu
```
**Symbols:**

```
ffffffff8110aae0-ffffffff8110ac32: flush_smp_call_function_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void flush_smp_call_function_queue(bool warn_cpu_offline);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81112300)
Location: kernel/smp.c:200
Inline: False
Direct callers:
  - kernel/smp.c:generic_smp_call_function_single_interrupt
  - kernel/smp.c:smpcfd_dying_cpu
```
**Symbols:**

```
ffffffff81112300-ffffffff81112452: flush_smp_call_function_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void flush_smp_call_function_queue(bool warn_cpu_offline);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81113940)
Location: kernel/smp.c:209
Inline: False
Direct callers:
  - kernel/smp.c:generic_smp_call_function_single_interrupt
  - kernel/smp.c:smpcfd_dying_cpu
```
**Symbols:**

```
ffffffff81113940-ffffffff81113a34: flush_smp_call_function_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void flush_smp_call_function_queue(bool warn_cpu_offline);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8111eed0)
Location: kernel/smp.c:209
Inline: False
Direct callers:
  - kernel/smp.c:generic_smp_call_function_single_interrupt
  - kernel/smp.c:smpcfd_dying_cpu
```
**Symbols:**

```
ffffffff8111eed0-ffffffff8111efb3: flush_smp_call_function_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void flush_smp_call_function_queue(bool warn_cpu_offline);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/smp.c (0)
Location: kernel/smp.c:209
Inline: False
Direct callers:
  - kernel/smp.c:generic_smp_call_function_single_interrupt
  - kernel/smp.c:smpcfd_dying_cpu
```
**Symbols:**

```
ffffffff8112c210-ffffffff8112c2e9: flush_smp_call_function_queue (STB_LOCAL)
ffffffff8112cd5b-ffffffff8112cd71: flush_smp_call_function_queue.cold.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void flush_smp_call_function_queue(bool warn_cpu_offline);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/smp.c (0)
Location: kernel/smp.c:209
Inline: False
Direct callers:
  - kernel/smp.c:generic_smp_call_function_single_interrupt
  - kernel/smp.c:smpcfd_dying_cpu
```
**Symbols:**

```
ffffffff81137ae0-ffffffff81137bc0: flush_smp_call_function_queue (STB_LOCAL)
ffffffff8113864b-ffffffff81138661: flush_smp_call_function_queue.cold.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void flush_smp_call_function_queue(bool warn_cpu_offline);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/smp.c (0)
Location: kernel/smp.c:210
Inline: False
Direct callers:
  - kernel/smp.c:generic_smp_call_function_single_interrupt
  - kernel/smp.c:smpcfd_dying_cpu
```
**Symbols:**

```
ffffffff81142c10-ffffffff81142cf9: flush_smp_call_function_queue (STB_LOCAL)
ffffffff811437fb-ffffffff81143839: flush_smp_call_function_queue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void flush_smp_call_function_queue(bool warn_cpu_offline);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/smp.c (0)
Location: kernel/smp.c:210
Inline: False
Direct callers:
  - kernel/smp.c:generic_smp_call_function_single_interrupt
  - kernel/smp.c:smpcfd_dying_cpu
```
**Symbols:**

```
ffffffff8114e780-ffffffff8114e85b: flush_smp_call_function_queue (STB_LOCAL)
ffffffff8114f33b-ffffffff8114f353: flush_smp_call_function_queue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void flush_smp_call_function_queue(bool warn_cpu_offline);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/smp.c (0)
Location: kernel/smp.c:211
Inline: False
Direct callers:
  - kernel/smp.c:flush_smp_call_function_from_idle
  - kernel/smp.c:generic_smp_call_function_single_interrupt
  - kernel/smp.c:smpcfd_dying_cpu
```
**Symbols:**

```
ffffffff8115f020-ffffffff8115f1ad: flush_smp_call_function_queue (STB_LOCAL)
ffffffff8115fcfb-ffffffff8115fd50: flush_smp_call_function_queue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void flush_smp_call_function_queue(bool warn_cpu_offline);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/smp.c (0)
Location: kernel/smp.c:334
Inline: False
Direct callers:
  - kernel/smp.c:flush_smp_call_function_from_idle
  - kernel/smp.c:generic_smp_call_function_single_interrupt
  - kernel/smp.c:smpcfd_dying_cpu
```
**Symbols:**

```
ffffffff8115afc0-ffffffff8115b14d: flush_smp_call_function_queue (STB_LOCAL)
ffffffff81be3de8-ffffffff81be3e3d: flush_smp_call_function_queue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void flush_smp_call_function_queue(bool warn_cpu_offline);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/smp.c (0)
Location: kernel/smp.c:561
Inline: False
Direct callers:
  - kernel/smp.c:flush_smp_call_function_from_idle
  - kernel/smp.c:generic_smp_call_function_single_interrupt
  - kernel/smp.c:smpcfd_dying_cpu
```
**Symbols:**

```
ffffffff8115c350-ffffffff8115c4dd: flush_smp_call_function_queue (STB_LOCAL)
ffffffff81bd5d02-ffffffff81bd5d57: flush_smp_call_function_queue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void flush_smp_call_function_queue(bool warn_cpu_offline);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/smp.c (0)
Location: kernel/smp.c:561
Inline: False
Direct callers:
  - kernel/smp.c:flush_smp_call_function_from_idle
  - kernel/smp.c:generic_smp_call_function_single_interrupt
  - kernel/smp.c:smpcfd_dying_cpu
```
**Symbols:**

```
ffffffff81181510-ffffffff811816ac: flush_smp_call_function_queue (STB_LOCAL)
ffffffff81cb234d-ffffffff81cb23b7: flush_smp_call_function_queue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void flush_smp_call_function_queue();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff811b8920)
Location: kernel/smp.c:700
Inline: False
Direct callers:
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/build_policy.c:do_idle
```
**Symbols:**

```
ffffffff811b8920-ffffffff811b8995: flush_smp_call_function_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void flush_smp_call_function_queue();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff811f9cf0)
Location: kernel/smp.c:699
Inline: False
Direct callers:
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/build_policy.c:do_idle
```
**Symbols:**

```
ffffffff811f9cf0-ffffffff811f9d71: flush_smp_call_function_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void flush_smp_call_function_queue();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8120f0d0)
Location: kernel/smp.c:555
Inline: False
Direct callers:
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/build_policy.c:do_idle
```
**Symbols:**

```
ffffffff8120f0d0-ffffffff8120f151: flush_smp_call_function_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void flush_smp_call_function_queue();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81226870)
Location: kernel/smp.c:575
Inline: False
Direct callers:
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/build_policy.c:do_idle
```
**Symbols:**

```
ffffffff81226870-ffffffff812268f1: flush_smp_call_function_queue (STB_GLOBAL)
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
void flush_smp_call_function_queue(bool warn_cpu_offline);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffff8000101bd910)
Location: kernel/smp.c:210
Inline: False
Direct callers:
  - kernel/smp.c:generic_smp_call_function_single_interrupt
  - kernel/smp.c:smpcfd_dying_cpu
```
**Symbols:**

```
ffff8000101bd910-ffff8000101bda68: flush_smp_call_function_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void flush_smp_call_function_queue(bool warn_cpu_offline);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (c040588c)
Location: kernel/smp.c:210
Inline: False
Direct callers:
  - kernel/smp.c:generic_smp_call_function_single_interrupt
  - kernel/smp.c:smpcfd_dying_cpu
```
**Symbols:**

```
c040588c-c0405a44: flush_smp_call_function_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void flush_smp_call_function_queue(bool warn_cpu_offline);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (c000000000222ac0)
Location: kernel/smp.c:210
Inline: False
Direct callers:
  - kernel/smp.c:generic_smp_call_function_single_interrupt
  - kernel/smp.c:smpcfd_dying_cpu
```
**Symbols:**

```
c000000000222ac0-c000000000222c74: flush_smp_call_function_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void flush_smp_call_function_queue(bool warn_cpu_offline);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffe0001403cc)
Location: kernel/smp.c:210
Inline: False
Direct callers:
  - kernel/smp.c:generic_smp_call_function_single_interrupt
  - kernel/smp.c:smpcfd_dying_cpu
```
**Symbols:**

```
ffffffe0001403cc-ffffffe0001404e4: flush_smp_call_function_queue (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void flush_smp_call_function_queue(bool warn_cpu_offline);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/smp.c (0)
Location: kernel/smp.c:210
Inline: False
Direct callers:
  - kernel/smp.c:generic_smp_call_function_single_interrupt
  - kernel/smp.c:smpcfd_dying_cpu
```
**Symbols:**

```
ffffffff81146da0-ffffffff81146e7b: flush_smp_call_function_queue (STB_LOCAL)
ffffffff8114795b-ffffffff81147973: flush_smp_call_function_queue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void flush_smp_call_function_queue(bool warn_cpu_offline);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/smp.c (0)
Location: kernel/smp.c:210
Inline: False
Direct callers:
  - kernel/smp.c:generic_smp_call_function_single_interrupt
  - kernel/smp.c:smpcfd_dying_cpu
```
**Symbols:**

```
ffffffff8113a0a0-ffffffff8113a17b: flush_smp_call_function_queue (STB_LOCAL)
ffffffff8113ac0b-ffffffff8113ac23: flush_smp_call_function_queue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void flush_smp_call_function_queue(bool warn_cpu_offline);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/smp.c (0)
Location: kernel/smp.c:210
Inline: False
Direct callers:
  - kernel/smp.c:generic_smp_call_function_single_interrupt
  - kernel/smp.c:smpcfd_dying_cpu
```
**Symbols:**

```
ffffffff81144c50-ffffffff81144d2b: flush_smp_call_function_queue (STB_LOCAL)
ffffffff8114580b-ffffffff81145823: flush_smp_call_function_queue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void flush_smp_call_function_queue(bool warn_cpu_offline);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/smp.c (0)
Location: kernel/smp.c:210
Inline: False
Direct callers:
  - kernel/smp.c:generic_smp_call_function_single_interrupt
  - kernel/smp.c:smpcfd_dying_cpu
```
**Symbols:**

```
ffffffff811517d0-ffffffff811518ab: flush_smp_call_function_queue (STB_LOCAL)
ffffffff8115241b-ffffffff81152433: flush_smp_call_function_queue.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool warn_cpu_offline</code>
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
