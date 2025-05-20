# Function: <code>cpu_load_update_nohz_start</code>

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
void cpu_load_update_nohz_start();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bfc20)
Location: kernel/sched/fair.c:4814
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
**Symbols:**

```
ffffffff810bfc20-ffffffff810bfc58: cpu_load_update_nohz_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cpu_load_update_nohz_start();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c5b00)
Location: kernel/sched/fair.c:5044
Inline: False
```
**Symbols:**

```
ffffffff810c5b00-ffffffff810c5b38: cpu_load_update_nohz_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cpu_load_update_nohz_start();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bf6c0)
Location: kernel/sched/fair.c:5187
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
**Symbols:**

```
ffffffff810bf6c0-ffffffff810bf6f8: cpu_load_update_nohz_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cpu_load_update_nohz_start();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c6ee0)
Location: kernel/sched/fair.c:5526
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
**Symbols:**

```
ffffffff810c6ee0-ffffffff810c6f05: cpu_load_update_nohz_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cpu_load_update_nohz_start();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810cede0)
Location: kernel/sched/fair.c:5722
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff810cede0-ffffffff810cee05: cpu_load_update_nohz_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cpu_load_update_nohz_start();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d8350)
Location: kernel/sched/fair.c:5462
Inline: False
Direct callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
**Symbols:**

```
ffffffff810d8350-ffffffff810d8375: cpu_load_update_nohz_start (STB_GLOBAL)
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
