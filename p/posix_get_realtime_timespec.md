# Function: <code>posix_get_realtime_timespec</code>

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
int posix_get_realtime_timespec(clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114fb00)
Location: kernel/time/posix-timers.c:170
Inline: False
```
**Symbols:**

```
ffffffff8114fb00-ffffffff8114fb15: posix_get_realtime_timespec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int posix_get_realtime_timespec(clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114bd80)
Location: kernel/time/posix-timers.c:170
Inline: False
```
**Symbols:**

```
ffffffff8114bd80-ffffffff8114bd95: posix_get_realtime_timespec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int posix_get_realtime_timespec(clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114d230)
Location: kernel/time/posix-timers.c:170
Inline: False
```
**Symbols:**

```
ffffffff8114d230-ffffffff8114d245: posix_get_realtime_timespec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int posix_get_realtime_timespec(clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81171270)
Location: kernel/time/posix-timers.c:170
Inline: False
```
**Symbols:**

```
ffffffff81171270-ffffffff81171285: posix_get_realtime_timespec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int posix_get_realtime_timespec(clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811a5990)
Location: kernel/time/posix-timers.c:170
Inline: False
```
**Symbols:**

```
ffffffff811a5990-ffffffff811a59ad: posix_get_realtime_timespec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int posix_get_realtime_timespec(clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811e5420)
Location: kernel/time/posix-timers.c:170
Inline: False
```
**Symbols:**

```
ffffffff811e5420-ffffffff811e543d: posix_get_realtime_timespec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int posix_get_realtime_timespec(clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811f9a80)
Location: kernel/time/posix-timers.c:131
Inline: False
```
**Symbols:**

```
ffffffff811f9a80-ffffffff811f9a9d: posix_get_realtime_timespec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int posix_get_realtime_timespec(clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8120fc70)
Location: kernel/time/posix-timers.c:131
Inline: False
```
**Symbols:**

```
ffffffff8120fc70-ffffffff8120fc8d: posix_get_realtime_timespec (STB_LOCAL)
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
