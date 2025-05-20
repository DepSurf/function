# Function: <code>alarm_clock_get_ktime</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ktime_t alarm_clock_get_ktime(clockid_t which_clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8114edd0)
Location: kernel/time/alarmtimer.c:684
Inline: False
```
**Symbols:**

```
ffffffff8114edd0-ffffffff8114ee38: alarm_clock_get_ktime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ktime_t alarm_clock_get_ktime(clockid_t which_clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8114b040)
Location: kernel/time/alarmtimer.c:684
Inline: False
```
**Symbols:**

```
ffffffff8114b040-ffffffff8114b0a8: alarm_clock_get_ktime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ktime_t alarm_clock_get_ktime(clockid_t which_clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8114c500)
Location: kernel/time/alarmtimer.c:687
Inline: False
```
**Symbols:**

```
ffffffff8114c500-ffffffff8114c568: alarm_clock_get_ktime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ktime_t alarm_clock_get_ktime(clockid_t which_clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff81170310)
Location: kernel/time/alarmtimer.c:687
Inline: False
```
**Symbols:**

```
ffffffff81170310-ffffffff81170390: alarm_clock_get_ktime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ktime_t alarm_clock_get_ktime(clockid_t which_clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff811a4870)
Location: kernel/time/alarmtimer.c:687
Inline: False
```
**Symbols:**

```
ffffffff811a4870-ffffffff811a48f8: alarm_clock_get_ktime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ktime_t alarm_clock_get_ktime(clockid_t which_clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff811e41d0)
Location: kernel/time/alarmtimer.c:712
Inline: False
```
**Symbols:**

```
ffffffff811e41d0-ffffffff811e4258: alarm_clock_get_ktime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ktime_t alarm_clock_get_ktime(clockid_t which_clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff811f8840)
Location: kernel/time/alarmtimer.c:711
Inline: False
```
**Symbols:**

```
ffffffff811f8840-ffffffff811f88c8: alarm_clock_get_ktime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ktime_t alarm_clock_get_ktime(clockid_t which_clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8120e9e0)
Location: kernel/time/alarmtimer.c:722
Inline: False
```
**Symbols:**

```
ffffffff8120e9e0-ffffffff8120ea68: alarm_clock_get_ktime (STB_LOCAL)
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
