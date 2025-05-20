# Function: <code>compat_get_timex</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int compat_get_timex(struct timex *txc, struct compat_timex *utp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8110fa40)
Location: kernel/compat.c:33
Inline: False
Direct callers:
  - kernel/compat.c:C_SYSC_clock_adjtime
  - kernel/compat.c:C_SYSC_adjtimex
```
**Symbols:**

```
ffffffff8110fa40-ffffffff8110fc47: compat_get_timex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int compat_get_timex(struct timex *txc, struct compat_timex *utp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811173e0)
Location: kernel/compat.c:33
Inline: False
Direct callers:
  - kernel/compat.c:C_SYSC_adjtimex
  - kernel/compat.c:C_SYSC_clock_adjtime
```
**Symbols:**

```
ffffffff811173e0-ffffffff811175e4: compat_get_timex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int compat_get_timex(struct timex *txc, struct compat_timex *utp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8111eb20)
Location: kernel/compat.c:33
Inline: False
Direct callers:
  - kernel/compat.c:C_SYSC_adjtimex
  - kernel/compat.c:C_SYSC_clock_adjtime
```
**Symbols:**

```
ffffffff8111eb20-ffffffff8111ed24: compat_get_timex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int compat_get_timex(struct timex *txc, const struct compat_timex *utp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811207c0)
Location: kernel/compat.c:33
Inline: False
Direct callers:
  - kernel/time/time.c:C_SYSC_adjtimex
  - kernel/time/posix-timers.c:C_SYSC_clock_adjtime
```
**Symbols:**

```
ffffffff811207c0-ffffffff811208d5: compat_get_timex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int compat_get_timex(struct timex *txc, const struct compat_timex *utp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8112bf60)
Location: kernel/compat.c:33
Inline: False
Direct callers:
  - kernel/time/time.c:C_SYSC_adjtimex
  - kernel/time/posix-timers.c:C_SYSC_clock_adjtime
```
**Symbols:**

```
ffffffff8112bf60-ffffffff8112c075: compat_get_timex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int compat_get_timex(struct timex *txc, const struct compat_timex *utp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8113a7f0)
Location: kernel/compat.c:33
Inline: False
Direct callers:
  - kernel/time/time.c:__do_compat_sys_adjtimex
  - kernel/time/posix-timers.c:__do_compat_sys_clock_adjtime
```
**Symbols:**

```
ffffffff8113a7f0-ffffffff8113a932: compat_get_timex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int compat_get_timex(struct timex *txc, const struct compat_timex *utp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81146060)
Location: kernel/compat.c:33
Inline: False
Direct callers:
  - kernel/time/time.c:__do_compat_sys_adjtimex
  - kernel/time/posix-timers.c:__do_compat_sys_clock_adjtime
```
**Symbols:**

```
ffffffff81146060-ffffffff811461a2: compat_get_timex (STB_GLOBAL)
```
</details>
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct compat_timex *utp</code> ➡️ <code>const struct compat_timex *utp</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
