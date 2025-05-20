# Function: <code>common_nsleep_timens</code>

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
int common_nsleep_timens(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81150220)
Location: kernel/time/posix-timers.c:1232
Inline: False
```
**Symbols:**

```
ffffffff81150220-ffffffff811502a4: common_nsleep_timens (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int common_nsleep_timens(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114c4a0)
Location: kernel/time/posix-timers.c:1232
Inline: False
```
**Symbols:**

```
ffffffff8114c4a0-ffffffff8114c524: common_nsleep_timens (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int common_nsleep_timens(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114d960)
Location: kernel/time/posix-timers.c:1232
Inline: False
```
**Symbols:**

```
ffffffff8114d960-ffffffff8114d9e4: common_nsleep_timens (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int common_nsleep_timens(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811717f0)
Location: kernel/time/posix-timers.c:1232
Inline: False
```
**Symbols:**

```
ffffffff811717f0-ffffffff81171874: common_nsleep_timens (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int common_nsleep_timens(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811a62c0)
Location: kernel/time/posix-timers.c:1241
Inline: False
```
**Symbols:**

```
ffffffff811a62c0-ffffffff811a6350: common_nsleep_timens (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int common_nsleep_timens(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811e5e20)
Location: kernel/time/posix-timers.c:1241
Inline: False
```
**Symbols:**

```
ffffffff811e5e20-ffffffff811e5eb0: common_nsleep_timens (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int common_nsleep_timens(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811fa2a0)
Location: kernel/time/posix-timers.c:1360
Inline: False
```
**Symbols:**

```
ffffffff811fa2a0-ffffffff811fa330: common_nsleep_timens (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int common_nsleep_timens(const clockid_t which_clock, int flags, const struct timespec64 *rqtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81210490)
Location: kernel/time/posix-timers.c:1360
Inline: False
```
**Symbols:**

```
ffffffff81210490-ffffffff81210520: common_nsleep_timens (STB_LOCAL)
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
