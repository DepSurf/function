# Function: <code>posix_cpu_timers_work</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void posix_cpu_timers_work(struct callback_head *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8114fa80)
Location: kernel/time/posix-cpu-timers.c:1098
Inline: False
```
**Symbols:**

```
ffffffff8114fa80-ffffffff8114fa99: posix_cpu_timers_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void posix_cpu_timers_work(struct callback_head *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/posix-cpu-timers.c (0)
Location: kernel/time/posix-cpu-timers.c:1098
Inline: False
```
**Symbols:**

```
ffffffff81150c60-ffffffff81150ed3: posix_cpu_timers_work (STB_LOCAL)
ffffffff81bd5a06-ffffffff81bd5a72: posix_cpu_timers_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void posix_cpu_timers_work(struct callback_head *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/posix-cpu-timers.c (0)
Location: kernel/time/posix-cpu-timers.c:1156
Inline: False
```
**Symbols:**

```
ffffffff81175030-ffffffff811752a3: posix_cpu_timers_work (STB_LOCAL)
ffffffff81cb1cda-ffffffff81cb1d46: posix_cpu_timers_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void posix_cpu_timers_work(struct callback_head *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/posix-cpu-timers.c (0)
Location: kernel/time/posix-cpu-timers.c:1163
Inline: False
```
**Symbols:**

```
ffffffff811aa2e0-ffffffff811aa58a: posix_cpu_timers_work (STB_LOCAL)
ffffffff81e63286-ffffffff81e632f2: posix_cpu_timers_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void posix_cpu_timers_work(struct callback_head *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811ea300)
Location: kernel/time/posix-cpu-timers.c:1163
Inline: False
```
**Symbols:**

```
ffffffff811ea300-ffffffff811ea604: posix_cpu_timers_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void posix_cpu_timers_work(struct callback_head *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811fea10)
Location: kernel/time/posix-cpu-timers.c:1164
Inline: False
```
**Symbols:**

```
ffffffff811fea10-ffffffff811fed3f: posix_cpu_timers_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void posix_cpu_timers_work(struct callback_head *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81214f10)
Location: kernel/time/posix-cpu-timers.c:1164
Inline: False
```
**Symbols:**

```
ffffffff81214f10-ffffffff8121508a: posix_cpu_timers_work (STB_LOCAL)
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
