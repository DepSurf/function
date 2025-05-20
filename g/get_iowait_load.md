# Function: <code>get_iowait_load</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void get_iowait_load(long unsigned int *nr_waiters, long unsigned int *load);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ad090)
Location: kernel/sched/core.c:2771
Inline: False
Direct callers:
  - drivers/cpuidle/governors/menu.c:menu_select
```
**Symbols:**

```
ffffffff810ad090-ffffffff810ad0bb: get_iowait_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void get_iowait_load(long unsigned int *nr_waiters, long unsigned int *load);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810afb00)
Location: kernel/sched/core.c:2954
Inline: False
Direct callers:
  - drivers/cpuidle/governors/menu.c:menu_select
```
**Symbols:**

```
ffffffff810afb00-ffffffff810afb2b: get_iowait_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void get_iowait_load(long unsigned int *nr_waiters, long unsigned int *load);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b5c40)
Location: kernel/sched/core.c:2968
Inline: False
Direct callers:
  - drivers/cpuidle/governors/menu.c:menu_select
```
**Symbols:**

```
ffffffff810b5c40-ffffffff810b5c6b: get_iowait_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void get_iowait_load(long unsigned int *nr_waiters, long unsigned int *load);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b1ed0)
Location: kernel/sched/core.c:2876
Inline: False
Direct callers:
  - drivers/cpuidle/governors/menu.c:menu_select
```
**Symbols:**

```
ffffffff810b1ed0-ffffffff810b1efb: get_iowait_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void get_iowait_load(long unsigned int *nr_waiters, long unsigned int *load);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b9280)
Location: kernel/sched/core.c:2905
Inline: False
Direct callers:
  - drivers/cpuidle/governors/menu.c:menu_select
```
**Symbols:**

```
ffffffff810b9280-ffffffff810b92ab: get_iowait_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void get_iowait_load(long unsigned int *nr_waiters, long unsigned int *load);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c0d70)
Location: kernel/sched/core.c:2958
Inline: False
Direct callers:
  - drivers/cpuidle/governors/menu.c:menu_select
```
**Symbols:**

```
ffffffff810c0d70-ffffffff810c0d9b: get_iowait_load (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.0</code>: Absent ⚠️
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
</ul>
