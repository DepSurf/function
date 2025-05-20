# Function: <code>posix_get_boottime_timespec</code>

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
int posix_get_boottime_timespec(const clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114f990)
Location: kernel/time/posix-timers.c:240
Inline: False
```
**Symbols:**

```
ffffffff8114f990-ffffffff8114fa22: posix_get_boottime_timespec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int posix_get_boottime_timespec(const clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114bc10)
Location: kernel/time/posix-timers.c:240
Inline: False
```
**Symbols:**

```
ffffffff8114bc10-ffffffff8114bca2: posix_get_boottime_timespec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int posix_get_boottime_timespec(const clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114d0c0)
Location: kernel/time/posix-timers.c:240
Inline: False
```
**Symbols:**

```
ffffffff8114d0c0-ffffffff8114d152: posix_get_boottime_timespec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int posix_get_boottime_timespec(const clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81171100)
Location: kernel/time/posix-timers.c:240
Inline: False
```
**Symbols:**

```
ffffffff81171100-ffffffff81171192: posix_get_boottime_timespec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int posix_get_boottime_timespec(const clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811a57e0)
Location: kernel/time/posix-timers.c:240
Inline: False
```
**Symbols:**

```
ffffffff811a57e0-ffffffff811a588d: posix_get_boottime_timespec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int posix_get_boottime_timespec(const clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811e5220)
Location: kernel/time/posix-timers.c:240
Inline: False
```
**Symbols:**

```
ffffffff811e5220-ffffffff811e52cd: posix_get_boottime_timespec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int posix_get_boottime_timespec(const clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811f9880)
Location: kernel/time/posix-timers.c:193
Inline: False
```
**Symbols:**

```
ffffffff811f9880-ffffffff811f992d: posix_get_boottime_timespec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int posix_get_boottime_timespec(const clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8120fa70)
Location: kernel/time/posix-timers.c:193
Inline: False
```
**Symbols:**

```
ffffffff8120fa70-ffffffff8120fb1d: posix_get_boottime_timespec (STB_LOCAL)
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
