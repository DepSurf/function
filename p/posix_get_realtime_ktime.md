# Function: <code>posix_get_realtime_ktime</code>

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
ktime_t posix_get_realtime_ktime(clockid_t which_clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114f6c0)
Location: kernel/time/posix-timers.c:176
Inline: False
```
**Symbols:**

```
ffffffff8114f6c0-ffffffff8114f6d2: posix_get_realtime_ktime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ktime_t posix_get_realtime_ktime(clockid_t which_clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114b940)
Location: kernel/time/posix-timers.c:176
Inline: False
```
**Symbols:**

```
ffffffff8114b940-ffffffff8114b952: posix_get_realtime_ktime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ktime_t posix_get_realtime_ktime(clockid_t which_clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114cdf0)
Location: kernel/time/posix-timers.c:176
Inline: False
```
**Symbols:**

```
ffffffff8114cdf0-ffffffff8114ce02: posix_get_realtime_ktime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ktime_t posix_get_realtime_ktime(clockid_t which_clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81170e30)
Location: kernel/time/posix-timers.c:176
Inline: False
```
**Symbols:**

```
ffffffff81170e30-ffffffff81170e42: posix_get_realtime_ktime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ktime_t posix_get_realtime_ktime(clockid_t which_clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811a54c0)
Location: kernel/time/posix-timers.c:176
Inline: False
```
**Symbols:**

```
ffffffff811a54c0-ffffffff811a54d8: posix_get_realtime_ktime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ktime_t posix_get_realtime_ktime(clockid_t which_clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811e4eb0)
Location: kernel/time/posix-timers.c:176
Inline: False
```
**Symbols:**

```
ffffffff811e4eb0-ffffffff811e4ec8: posix_get_realtime_ktime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ktime_t posix_get_realtime_ktime(clockid_t which_clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811f9510)
Location: kernel/time/posix-timers.c:137
Inline: False
```
**Symbols:**

```
ffffffff811f9510-ffffffff811f9528: posix_get_realtime_ktime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ktime_t posix_get_realtime_ktime(clockid_t which_clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8120f700)
Location: kernel/time/posix-timers.c:137
Inline: False
```
**Symbols:**

```
ffffffff8120f700-ffffffff8120f718: posix_get_realtime_ktime (STB_LOCAL)
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
