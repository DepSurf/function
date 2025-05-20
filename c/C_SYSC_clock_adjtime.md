# Function: <code>C_SYSC_clock_adjtime</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int C_SYSC_clock_adjtime(clockid_t which_clock, struct compat_timex *utp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8110fc50)
Location: kernel/compat.c:774
Inline: False
Direct callers:
  - kernel/compat.c:compat_SyS_clock_adjtime
```
**Symbols:**

```
ffffffff8110fc50-ffffffff8110fcff: C_SYSC_clock_adjtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int C_SYSC_clock_adjtime(clockid_t which_clock, struct compat_timex *utp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811175f0)
Location: kernel/compat.c:774
Inline: False
Direct callers:
  - kernel/compat.c:compat_SyS_clock_adjtime
```
**Symbols:**

```
ffffffff811175f0-ffffffff8111769f: C_SYSC_clock_adjtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int C_SYSC_clock_adjtime(clockid_t which_clock, struct compat_timex *utp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8111ed30)
Location: kernel/compat.c:782
Inline: False
Direct callers:
  - kernel/compat.c:compat_SyS_clock_adjtime
```
**Symbols:**

```
ffffffff8111ed30-ffffffff8111eddf: C_SYSC_clock_adjtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int C_SYSC_clock_adjtime(clockid_t which_clock, struct compat_timex *utp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81107db0)
Location: kernel/time/posix-timers.c:1145
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:compat_SyS_clock_adjtime
```
**Symbols:**

```
ffffffff81107db0-ffffffff81107e78: C_SYSC_clock_adjtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int C_SYSC_clock_adjtime(clockid_t which_clock, struct compat_timex *utp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81112f50)
Location: kernel/time/posix-timers.c:1151
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:compat_SyS_clock_adjtime
```
**Symbols:**

```
ffffffff81112f50-ffffffff81113021: C_SYSC_clock_adjtime (STB_LOCAL)
```
</details>
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
