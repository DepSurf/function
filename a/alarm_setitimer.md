# Function: <code>alarm_setitimer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int alarm_setitimer(unsigned int seconds);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff810f07e0)
Location: kernel/time/itimer.c:253
Inline: False
Direct callers:
  - kernel/time/timer.c:SyS_alarm
```
**Symbols:**

```
ffffffff810f07e0-ffffffff810f0872: alarm_setitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int alarm_setitimer(unsigned int seconds);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff810f7810)
Location: kernel/time/itimer.c:253
Inline: False
Direct callers:
  - kernel/time/timer.c:SyS_alarm
```
**Symbols:**

```
ffffffff810f7810-ffffffff810f789b: alarm_setitimer (STB_GLOBAL)
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
In kernel/time/itimer.c (ffffffff81109ed6)
Location: kernel/time/itimer.c:255
Inline: True
Inline callers:
  - kernel/time/itimer.c:SyS_alarm
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
In kernel/time/itimer.c (ffffffff8110bd6e)
Location: kernel/time/itimer.c:255
Inline: True
Inline callers:
  - kernel/time/itimer.c:SyS_alarm
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
In kernel/time/itimer.c (ffffffff81116fbe)
Location: kernel/time/itimer.c:256
Inline: True
Inline callers:
  - kernel/time/itimer.c:SyS_alarm
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int alarm_setitimer(unsigned int seconds);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff81123920)
Location: kernel/time/itimer.c:256
Inline: False
Direct callers:
  - kernel/time/itimer.c:__ia32_sys_alarm
  - kernel/time/itimer.c:__x64_sys_alarm
```
**Symbols:**

```
ffffffff81123920-ffffffff811239ab: alarm_setitimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int alarm_setitimer(unsigned int seconds);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff8112eff0)
Location: kernel/time/itimer.c:255
Inline: False
Direct callers:
  - kernel/time/itimer.c:__ia32_sys_alarm
  - kernel/time/itimer.c:__x64_sys_alarm
```
**Symbols:**

```
ffffffff8112eff0-ffffffff8112f080: alarm_setitimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int alarm_setitimer(unsigned int seconds);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff81139a60)
Location: kernel/time/itimer.c:255
Inline: False
Direct callers:
  - kernel/time/itimer.c:__ia32_sys_alarm
  - kernel/time/itimer.c:__x64_sys_alarm
```
**Symbols:**

```
ffffffff81139a60-ffffffff81139af0: alarm_setitimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int alarm_setitimer(unsigned int seconds);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff811456e0)
Location: kernel/time/itimer.c:251
Inline: False
Direct callers:
  - kernel/time/itimer.c:__ia32_sys_alarm
  - kernel/time/itimer.c:__x64_sys_alarm
```
**Symbols:**

```
ffffffff811456e0-ffffffff81145770: alarm_setitimer (STB_LOCAL)
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
In kernel/time/itimer.c (ffffffff81154d3c)
Location: kernel/time/itimer.c:281
Inline: True
Inline callers:
  - kernel/time/itimer.c:__ia32_sys_alarm
  - kernel/time/itimer.c:__x64_sys_alarm
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
In kernel/time/itimer.c (ffffffff81150fac)
Location: kernel/time/itimer.c:277
Inline: True
Inline callers:
  - kernel/time/itimer.c:__ia32_sys_alarm
  - kernel/time/itimer.c:__x64_sys_alarm
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
In kernel/time/itimer.c (ffffffff811523e1)
Location: kernel/time/itimer.c:277
Inline: True
Inline callers:
  - kernel/time/itimer.c:__ia32_sys_alarm
  - kernel/time/itimer.c:__x64_sys_alarm
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
In kernel/time/itimer.c (ffffffff811769b1)
Location: kernel/time/itimer.c:277
Inline: True
Inline callers:
  - kernel/time/itimer.c:__ia32_sys_alarm
  - kernel/time/itimer.c:__x64_sys_alarm
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
In kernel/time/itimer.c (ffffffff811abe41)
Location: kernel/time/itimer.c:277
Inline: True
Inline callers:
  - kernel/time/itimer.c:__ia32_sys_alarm
  - kernel/time/itimer.c:__x64_sys_alarm
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
In kernel/time/itimer.c (ffffffff811ec0f1)
Location: kernel/time/itimer.c:277
Inline: True
Inline callers:
  - kernel/time/itimer.c:__ia32_sys_alarm
  - kernel/time/itimer.c:__x64_sys_alarm
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
In kernel/time/itimer.c (ffffffff81200821)
Location: kernel/time/itimer.c:277
Inline: True
Inline callers:
  - kernel/time/itimer.c:__ia32_sys_alarm
  - kernel/time/itimer.c:__x64_sys_alarm
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
In kernel/time/itimer.c (ffffffff81216cc1)
Location: kernel/time/itimer.c:277
Inline: True
Inline callers:
  - kernel/time/itimer.c:__ia32_sys_alarm
  - kernel/time/itimer.c:__x64_sys_alarm
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
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (c000000000214a6c)
Location: kernel/time/itimer.c:251
Inline: True
Inline callers:
  - kernel/time/itimer.c:__se_sys_alarm
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
unsigned int alarm_setitimer(unsigned int seconds);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff8113de90)
Location: kernel/time/itimer.c:251
Inline: False
Direct callers:
  - kernel/time/itimer.c:__ia32_sys_alarm
  - kernel/time/itimer.c:__x64_sys_alarm
```
**Symbols:**

```
ffffffff8113de90-ffffffff8113df20: alarm_setitimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int alarm_setitimer(unsigned int seconds);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff811309b0)
Location: kernel/time/itimer.c:251
Inline: False
Direct callers:
  - kernel/time/itimer.c:__ia32_sys_alarm
  - kernel/time/itimer.c:__x64_sys_alarm
```
**Symbols:**

```
ffffffff811309b0-ffffffff81130a40: alarm_setitimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int alarm_setitimer(unsigned int seconds);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff8113bbb0)
Location: kernel/time/itimer.c:251
Inline: False
Direct callers:
  - kernel/time/itimer.c:__ia32_sys_alarm
  - kernel/time/itimer.c:__x64_sys_alarm
```
**Symbols:**

```
ffffffff8113bbb0-ffffffff8113bc40: alarm_setitimer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int alarm_setitimer(unsigned int seconds);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff81148690)
Location: kernel/time/itimer.c:251
Inline: False
Direct callers:
  - kernel/time/itimer.c:__ia32_sys_alarm
  - kernel/time/itimer.c:__x64_sys_alarm
```
**Symbols:**

```
ffffffff81148690-ffffffff81148720: alarm_setitimer (STB_LOCAL)
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
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
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
