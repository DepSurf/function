# Function: <code>get_boottime_timespec</code>

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
void get_boottime_timespec(struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8114e270)
Location: kernel/time/alarmtimer.c:889
Inline: False
```
**Symbols:**

```
ffffffff8114e270-ffffffff8114e300: get_boottime_timespec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void get_boottime_timespec(struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8114a500)
Location: kernel/time/alarmtimer.c:889
Inline: False
```
**Symbols:**

```
ffffffff8114a500-ffffffff8114a590: get_boottime_timespec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void get_boottime_timespec(struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8114b9c0)
Location: kernel/time/alarmtimer.c:895
Inline: False
```
**Symbols:**

```
ffffffff8114b9c0-ffffffff8114ba50: get_boottime_timespec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void get_boottime_timespec(struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8116f6d0)
Location: kernel/time/alarmtimer.c:895
Inline: False
```
**Symbols:**

```
ffffffff8116f6d0-ffffffff8116f760: get_boottime_timespec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void get_boottime_timespec(struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff811a3be0)
Location: kernel/time/alarmtimer.c:895
Inline: False
```
**Symbols:**

```
ffffffff811a3be0-ffffffff811a3c8d: get_boottime_timespec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void get_boottime_timespec(struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff811e3430)
Location: kernel/time/alarmtimer.c:920
Inline: False
```
**Symbols:**

```
ffffffff811e3430-ffffffff811e34dd: get_boottime_timespec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void get_boottime_timespec(struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff811f7a60)
Location: kernel/time/alarmtimer.c:919
Inline: False
```
**Symbols:**

```
ffffffff811f7a60-ffffffff811f7b0d: get_boottime_timespec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void get_boottime_timespec(struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8120dc00)
Location: kernel/time/alarmtimer.c:930
Inline: False
```
**Symbols:**

```
ffffffff8120dc00-ffffffff8120dcad: get_boottime_timespec (STB_LOCAL)
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
