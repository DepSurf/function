# Function: <code>__tick_nohz_idle_restart_tick</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __tick_nohz_idle_restart_tick(struct tick_sched *ts, ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81126ff0)
Location: kernel/time/tick-sched.c:1113
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
```
**Symbols:**

```
ffffffff81126ff0-ffffffff811270c5: __tick_nohz_idle_restart_tick (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __tick_nohz_idle_restart_tick(struct tick_sched *ts, ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811326e0)
Location: kernel/time/tick-sched.c:1110
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
```
**Symbols:**

```
ffffffff811326e0-ffffffff811327b5: __tick_nohz_idle_restart_tick (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __tick_nohz_idle_restart_tick(struct tick_sched *ts, ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8113d260)
Location: kernel/time/tick-sched.c:1135
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
```
**Symbols:**

```
ffffffff8113d260-ffffffff8113d330: __tick_nohz_idle_restart_tick (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __tick_nohz_idle_restart_tick(struct tick_sched *ts, ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81148df0)
Location: kernel/time/tick-sched.c:1142
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
```
**Symbols:**

```
ffffffff81148df0-ffffffff81148ec3: __tick_nohz_idle_restart_tick (STB_LOCAL)
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
In kernel/time/tick-sched.c (ffffffff81159484)
Location: kernel/time/tick-sched.c:1167
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
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
In kernel/time/tick-sched.c (ffffffff81155450)
Location: kernel/time/tick-sched.c:1208
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
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
In kernel/time/tick-sched.c (ffffffff811567c0)
Location: kernel/time/tick-sched.c:1213
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __tick_nohz_idle_restart_tick(struct tick_sched *ts, ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffff8000101b4d90)
Location: kernel/time/tick-sched.c:1142
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
```
**Symbols:**

```
ffff8000101b4d90-ffff8000101b4e8c: __tick_nohz_idle_restart_tick (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __tick_nohz_idle_restart_tick(struct tick_sched *ts, ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (c03fecc0)
Location: kernel/time/tick-sched.c:1142
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
```
**Symbols:**

```
c03fecc0-c03fedfc: __tick_nohz_idle_restart_tick (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __tick_nohz_idle_restart_tick(struct tick_sched *ts, ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (c00000000021a880)
Location: kernel/time/tick-sched.c:1142
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
```
**Symbols:**

```
c00000000021a880-c00000000021aa1c: __tick_nohz_idle_restart_tick (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __tick_nohz_idle_restart_tick(struct tick_sched *ts, ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffe00013b490)
Location: kernel/time/tick-sched.c:1142
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
```
**Symbols:**

```
ffffffe00013b490-ffffffe00013b580: __tick_nohz_idle_restart_tick (STB_LOCAL)
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
void __tick_nohz_idle_restart_tick(struct tick_sched *ts, ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff81141410)
Location: kernel/time/tick-sched.c:1142
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
```
**Symbols:**

```
ffffffff81141410-ffffffff811414e3: __tick_nohz_idle_restart_tick (STB_LOCAL)
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
In kernel/time/tick-sched.c (ffffffff81134e65)
Location: kernel/time/tick-sched.c:1142
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __tick_nohz_idle_restart_tick(struct tick_sched *ts, ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8113f2c0)
Location: kernel/time/tick-sched.c:1142
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
```
**Symbols:**

```
ffffffff8113f2c0-ffffffff8113f393: __tick_nohz_idle_restart_tick (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __tick_nohz_idle_restart_tick(struct tick_sched *ts, ktime_t now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff8114bd20)
Location: kernel/time/tick-sched.c:1142
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_idle_restart_tick
```
**Symbols:**

```
ffffffff8114bd20-ffffffff8114bdf3: __tick_nohz_idle_restart_tick (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
