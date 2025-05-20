# Function: <code>posix_get_tai_timespec</code>

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
int posix_get_tai_timespec(clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114f6e0)
Location: kernel/time/posix-timers.c:252
Inline: False
```
**Symbols:**

```
ffffffff8114f6e0-ffffffff8114f70e: posix_get_tai_timespec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int posix_get_tai_timespec(clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114b960)
Location: kernel/time/posix-timers.c:252
Inline: False
```
**Symbols:**

```
ffffffff8114b960-ffffffff8114b98e: posix_get_tai_timespec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int posix_get_tai_timespec(clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114ce10)
Location: kernel/time/posix-timers.c:252
Inline: False
```
**Symbols:**

```
ffffffff8114ce10-ffffffff8114ce3e: posix_get_tai_timespec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int posix_get_tai_timespec(clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81170e50)
Location: kernel/time/posix-timers.c:252
Inline: False
```
**Symbols:**

```
ffffffff81170e50-ffffffff81170e7e: posix_get_tai_timespec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int posix_get_tai_timespec(clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811a54e0)
Location: kernel/time/posix-timers.c:252
Inline: False
```
**Symbols:**

```
ffffffff811a54e0-ffffffff811a5518: posix_get_tai_timespec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int posix_get_tai_timespec(clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811e4ee0)
Location: kernel/time/posix-timers.c:252
Inline: False
```
**Symbols:**

```
ffffffff811e4ee0-ffffffff811e4f18: posix_get_tai_timespec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int posix_get_tai_timespec(clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811f9540)
Location: kernel/time/posix-timers.c:205
Inline: False
```
**Symbols:**

```
ffffffff811f9540-ffffffff811f9578: posix_get_tai_timespec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int posix_get_tai_timespec(clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8120f730)
Location: kernel/time/posix-timers.c:205
Inline: False
```
**Symbols:**

```
ffffffff8120f730-ffffffff8120f768: posix_get_tai_timespec (STB_LOCAL)
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
