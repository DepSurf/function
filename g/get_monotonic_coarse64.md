# Function: <code>get_monotonic_coarse64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct timespec get_monotonic_coarse64();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810f6990)
Location: kernel/time/timekeeping.c:2171
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_coarse
```
**Symbols:**

```
ffffffff810f6990-ffffffff810f6a24: get_monotonic_coarse64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct timespec get_monotonic_coarse64();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810fbc70)
Location: kernel/time/timekeeping.c:2176
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_coarse
```
**Symbols:**

```
ffffffff810fbc70-ffffffff810fbd05: get_monotonic_coarse64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct timespec get_monotonic_coarse64();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810feb70)
Location: kernel/time/timekeeping.c:2188
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_coarse
```
**Symbols:**

```
ffffffff810feb70-ffffffff810fec05: get_monotonic_coarse64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct timespec get_monotonic_coarse64();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81100e50)
Location: kernel/time/timekeeping.c:2177
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_coarse
```
**Symbols:**

```
ffffffff81100e50-ffffffff81100ee9: get_monotonic_coarse64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct timespec get_monotonic_coarse64();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8110bc60)
Location: kernel/time/timekeeping.c:2206
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_coarse
```
**Symbols:**

```
ffffffff8110bc60-ffffffff8110bcf9: get_monotonic_coarse64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8111e524)
Location: include/linux/timekeeping.h:266
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_coarse
```
</details>
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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
