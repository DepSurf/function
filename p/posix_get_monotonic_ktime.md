# Function: <code>posix_get_monotonic_ktime</code>

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
ktime_t posix_get_monotonic_ktime(clockid_t which_clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114fad0)
Location: kernel/time/posix-timers.c:204
Inline: False
```
**Symbols:**

```
ffffffff8114fad0-ffffffff8114fae0: posix_get_monotonic_ktime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ktime_t posix_get_monotonic_ktime(clockid_t which_clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114bd50)
Location: kernel/time/posix-timers.c:204
Inline: False
```
**Symbols:**

```
ffffffff8114bd50-ffffffff8114bd60: posix_get_monotonic_ktime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ktime_t posix_get_monotonic_ktime(clockid_t which_clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114d200)
Location: kernel/time/posix-timers.c:204
Inline: False
```
**Symbols:**

```
ffffffff8114d200-ffffffff8114d210: posix_get_monotonic_ktime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ktime_t posix_get_monotonic_ktime(clockid_t which_clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81171240)
Location: kernel/time/posix-timers.c:204
Inline: False
```
**Symbols:**

```
ffffffff81171240-ffffffff81171250: posix_get_monotonic_ktime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ktime_t posix_get_monotonic_ktime(clockid_t which_clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811a5950)
Location: kernel/time/posix-timers.c:204
Inline: False
```
**Symbols:**

```
ffffffff811a5950-ffffffff811a5964: posix_get_monotonic_ktime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ktime_t posix_get_monotonic_ktime(clockid_t which_clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811e53c0)
Location: kernel/time/posix-timers.c:204
Inline: False
```
**Symbols:**

```
ffffffff811e53c0-ffffffff811e53d4: posix_get_monotonic_ktime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ktime_t posix_get_monotonic_ktime(clockid_t which_clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811f9a20)
Location: kernel/time/posix-timers.c:161
Inline: False
```
**Symbols:**

```
ffffffff811f9a20-ffffffff811f9a34: posix_get_monotonic_ktime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ktime_t posix_get_monotonic_ktime(clockid_t which_clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8120fc10)
Location: kernel/time/posix-timers.c:161
Inline: False
```
**Symbols:**

```
ffffffff8120fc10-ffffffff8120fc24: posix_get_monotonic_ktime (STB_LOCAL)
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
