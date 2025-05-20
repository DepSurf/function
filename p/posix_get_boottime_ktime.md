# Function: <code>posix_get_boottime_ktime</code>

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
ktime_t posix_get_boottime_ktime(const clockid_t which_clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114f6a0)
Location: kernel/time/posix-timers.c:247
Inline: False
```
**Symbols:**

```
ffffffff8114f6a0-ffffffff8114f6b5: posix_get_boottime_ktime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ktime_t posix_get_boottime_ktime(const clockid_t which_clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114b920)
Location: kernel/time/posix-timers.c:247
Inline: False
```
**Symbols:**

```
ffffffff8114b920-ffffffff8114b935: posix_get_boottime_ktime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ktime_t posix_get_boottime_ktime(const clockid_t which_clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114cdd0)
Location: kernel/time/posix-timers.c:247
Inline: False
```
**Symbols:**

```
ffffffff8114cdd0-ffffffff8114cde5: posix_get_boottime_ktime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ktime_t posix_get_boottime_ktime(const clockid_t which_clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81170e10)
Location: kernel/time/posix-timers.c:247
Inline: False
```
**Symbols:**

```
ffffffff81170e10-ffffffff81170e25: posix_get_boottime_ktime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ktime_t posix_get_boottime_ktime(const clockid_t which_clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811a54a0)
Location: kernel/time/posix-timers.c:247
Inline: False
```
**Symbols:**

```
ffffffff811a54a0-ffffffff811a54bb: posix_get_boottime_ktime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ktime_t posix_get_boottime_ktime(const clockid_t which_clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811e4e80)
Location: kernel/time/posix-timers.c:247
Inline: False
```
**Symbols:**

```
ffffffff811e4e80-ffffffff811e4e9b: posix_get_boottime_ktime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ktime_t posix_get_boottime_ktime(const clockid_t which_clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811f94e0)
Location: kernel/time/posix-timers.c:200
Inline: False
```
**Symbols:**

```
ffffffff811f94e0-ffffffff811f94fb: posix_get_boottime_ktime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ktime_t posix_get_boottime_ktime(const clockid_t which_clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8120f6d0)
Location: kernel/time/posix-timers.c:200
Inline: False
```
**Symbols:**

```
ffffffff8120f6d0-ffffffff8120f6eb: posix_get_boottime_ktime (STB_LOCAL)
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
