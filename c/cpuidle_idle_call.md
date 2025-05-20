# Function: <code>cpuidle_idle_call</code>

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
In kernel/sched/idle.c (ffffffff810c3e02)
Location: kernel/sched/idle.c:133
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_startup_entry
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
In kernel/sched/idle.c (ffffffff810c7afd)
Location: kernel/sched/idle.c:128
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_startup_entry
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
In kernel/sched/idle.c (ffffffff810cd92e)
Location: kernel/sched/idle.c:131
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
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
In kernel/sched/idle.c (ffffffff810ca352)
Location: kernel/sched/idle.c:133
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
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
In kernel/sched/idle.c (ffffffff810d1bbe)
Location: kernel/sched/idle.c:133
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
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
In kernel/sched/idle.c (ffffffff810c42d7)
Location: kernel/sched/idle.c:128
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
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
In kernel/sched/idle.c (ffffffff810cd597)
Location: kernel/sched/idle.c:128
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
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
In kernel/sched/idle.c (ffffffff810d5982)
Location: kernel/sched/idle.c:129
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
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
In kernel/sched/idle.c (ffffffff810dff92)
Location: kernel/sched/idle.c:129
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cpuidle_idle_call();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810e81f0)
Location: kernel/sched/idle.c:138
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff810e81f0-ffffffff810e83e9: cpuidle_idle_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cpuidle_idle_call();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810e5e10)
Location: kernel/sched/idle.c:170
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff810e5e10-ffffffff810e5fdb: cpuidle_idle_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cpuidle_idle_call();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810e7dd0)
Location: kernel/sched/idle.c:170
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff810e7dd0-ffffffff810e7f9b: cpuidle_idle_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void cpuidle_idle_call();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/idle.c (0)
Location: kernel/sched/idle.c:170
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff810ff480-ffffffff810ff657: cpuidle_idle_call (STB_LOCAL)
ffffffff81ca61e3-ffffffff81ca61f7: cpuidle_idle_call.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void cpuidle_idle_call();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/idle.c:167
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:do_idle
```
**Symbols:**

```
ffffffff811334e0-ffffffff81133669: cpuidle_idle_call (STB_LOCAL)
ffffffff81e5644d-ffffffff81e56462: cpuidle_idle_call.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void cpuidle_idle_call();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/idle.c:167
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:do_idle
```
**Symbols:**

```
ffffffff8115d8a0-ffffffff8115da7a: cpuidle_idle_call (STB_LOCAL)
ffffffff82057677-ffffffff8205768c: cpuidle_idle_call.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void cpuidle_idle_call();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/idle.c:146
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:do_idle
```
**Symbols:**

```
ffffffff8116dfe0-ffffffff8116e16b: cpuidle_idle_call (STB_LOCAL)
ffffffff820d5e9d-ffffffff820d5eb2: cpuidle_idle_call.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void cpuidle_idle_call();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/idle.c:146
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:do_idle
```
**Symbols:**

```
ffffffff8117b5a0-ffffffff8117b72b: cpuidle_idle_call (STB_LOCAL)
ffffffff821b0fac-ffffffff821b0fc1: cpuidle_idle_call.cold (STB_LOCAL)
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
In kernel/sched/idle.c (ffff80001013fcc8)
Location: kernel/sched/idle.c:129
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
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
In kernel/sched/idle.c (c038fc08)
Location: kernel/sched/idle.c:129
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
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
In kernel/sched/idle.c (c00000000018ed7c)
Location: kernel/sched/idle.c:129
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
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
In kernel/sched/idle.c (ffffffe0000edfd8)
Location: kernel/sched/idle.c:129
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
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
In kernel/sched/idle.c (ffffffff810da182)
Location: kernel/sched/idle.c:129
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
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
In kernel/sched/idle.c (ffffffff810c916c)
Location: kernel/sched/idle.c:129
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
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
In kernel/sched/idle.c (ffffffff810d64c2)
Location: kernel/sched/idle.c:129
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
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
In kernel/sched/idle.c (ffffffff810e1dc2)
Location: kernel/sched/idle.c:129
Inline: True
Inline callers:
  - kernel/sched/idle.c:do_idle
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
