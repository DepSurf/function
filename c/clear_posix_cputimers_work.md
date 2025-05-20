# Function: <code>clear_posix_cputimers_work</code>

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
In <code>4.18</code>: Absent ⚠️
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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void clear_posix_cputimers_work(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81175920)
Location: kernel/time/posix-cpu-timers.c:1164
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/time/posix-cpu-timers.c:posix_cputimers_init_work
```
**Symbols:**

```
ffffffff81175920-ffffffff8117594b: clear_posix_cputimers_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void clear_posix_cputimers_work(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811aa8b0)
Location: kernel/time/posix-cpu-timers.c:1171
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/time/posix-cpu-timers.c:posix_cputimers_init_work
```
**Symbols:**

```
ffffffff811aa8b0-ffffffff811aa8e1: clear_posix_cputimers_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void clear_posix_cputimers_work(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff83eae6cf)
Location: kernel/time/posix-cpu-timers.c:1171
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cputimers_init_work
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff811ea990-ffffffff811ea9c1: clear_posix_cputimers_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void clear_posix_cputimers_work(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811ff0c0)
Location: kernel/time/posix-cpu-timers.c:1214
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/time/posix-cpu-timers.c:posix_cputimers_init_work
```
**Symbols:**

```
ffffffff811ff0c0-ffffffff811ff111: clear_posix_cputimers_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void clear_posix_cputimers_work(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81215440)
Location: kernel/time/posix-cpu-timers.c:1214
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/time/posix-cpu-timers.c:posix_cputimers_init_work
```
**Symbols:**

```
ffffffff81215440-ffffffff81215491: clear_posix_cputimers_work (STB_GLOBAL)
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
