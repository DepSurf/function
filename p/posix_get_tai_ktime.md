# Function: <code>posix_get_tai_ktime</code>

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
ktime_t posix_get_tai_ktime(clockid_t which_clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114f680)
Location: kernel/time/posix-timers.c:258
Inline: False
```
**Symbols:**

```
ffffffff8114f680-ffffffff8114f695: posix_get_tai_ktime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ktime_t posix_get_tai_ktime(clockid_t which_clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114b900)
Location: kernel/time/posix-timers.c:258
Inline: False
```
**Symbols:**

```
ffffffff8114b900-ffffffff8114b915: posix_get_tai_ktime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ktime_t posix_get_tai_ktime(clockid_t which_clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114cdb0)
Location: kernel/time/posix-timers.c:258
Inline: False
```
**Symbols:**

```
ffffffff8114cdb0-ffffffff8114cdc5: posix_get_tai_ktime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ktime_t posix_get_tai_ktime(clockid_t which_clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81170df0)
Location: kernel/time/posix-timers.c:258
Inline: False
```
**Symbols:**

```
ffffffff81170df0-ffffffff81170e05: posix_get_tai_ktime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ktime_t posix_get_tai_ktime(clockid_t which_clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811a5480)
Location: kernel/time/posix-timers.c:258
Inline: False
```
**Symbols:**

```
ffffffff811a5480-ffffffff811a549b: posix_get_tai_ktime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ktime_t posix_get_tai_ktime(clockid_t which_clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811e4e50)
Location: kernel/time/posix-timers.c:258
Inline: False
```
**Symbols:**

```
ffffffff811e4e50-ffffffff811e4e6b: posix_get_tai_ktime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ktime_t posix_get_tai_ktime(clockid_t which_clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811f94b0)
Location: kernel/time/posix-timers.c:211
Inline: False
```
**Symbols:**

```
ffffffff811f94b0-ffffffff811f94cb: posix_get_tai_ktime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ktime_t posix_get_tai_ktime(clockid_t which_clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8120f6a0)
Location: kernel/time/posix-timers.c:211
Inline: False
```
**Symbols:**

```
ffffffff8120f6a0-ffffffff8120f6bb: posix_get_tai_ktime (STB_LOCAL)
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
