# Function: <code>cpu_load_update_nohz_stop</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cpu_load_update_nohz_stop();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bfc60)
Location: kernel/sched/fair.c:4829
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
```
**Symbols:**

```
ffffffff810bfc60-ffffffff810bfd0a: cpu_load_update_nohz_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cpu_load_update_nohz_stop();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c5b40)
Location: kernel/sched/fair.c:5059
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
```
**Symbols:**

```
ffffffff810c5b40-ffffffff810c5bea: cpu_load_update_nohz_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cpu_load_update_nohz_stop();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bf700)
Location: kernel/sched/fair.c:5202
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
```
**Symbols:**

```
ffffffff810bf700-ffffffff810bf7b1: cpu_load_update_nohz_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cpu_load_update_nohz_stop();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c6f10)
Location: kernel/sched/fair.c:5541
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
```
**Symbols:**

```
ffffffff810c6f10-ffffffff810c6fae: cpu_load_update_nohz_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cpu_load_update_nohz_stop();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810cee10)
Location: kernel/sched/fair.c:5737
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
```
**Symbols:**

```
ffffffff810cee10-ffffffff810ceeae: cpu_load_update_nohz_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cpu_load_update_nohz_stop();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d8380)
Location: kernel/sched/fair.c:5477
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
```
**Symbols:**

```
ffffffff810d8380-ffffffff810d841e: cpu_load_update_nohz_stop (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
