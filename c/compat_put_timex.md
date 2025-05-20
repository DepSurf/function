# Function: <code>compat_put_timex</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int compat_put_timex(struct compat_timex *utp, struct timex *txc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8110f850)
Location: kernel/compat.c:63
Inline: False
Direct callers:
  - kernel/compat.c:C_SYSC_clock_adjtime
  - kernel/compat.c:C_SYSC_adjtimex
```
**Symbols:**

```
ffffffff8110f850-ffffffff8110fa35: compat_put_timex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int compat_put_timex(struct compat_timex *utp, struct timex *txc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81116fc0)
Location: kernel/compat.c:63
Inline: False
Direct callers:
  - kernel/compat.c:C_SYSC_adjtimex
  - kernel/compat.c:C_SYSC_clock_adjtime
```
**Symbols:**

```
ffffffff81116fc0-ffffffff81117197: compat_put_timex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int compat_put_timex(struct compat_timex *utp, struct timex *txc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8111e700)
Location: kernel/compat.c:63
Inline: False
Direct callers:
  - kernel/compat.c:C_SYSC_adjtimex
  - kernel/compat.c:C_SYSC_clock_adjtime
```
**Symbols:**

```
ffffffff8111e700-ffffffff8111e8d7: compat_put_timex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int compat_put_timex(struct compat_timex *utp, const struct timex *txc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811208e0)
Location: kernel/compat.c:64
Inline: False
Direct callers:
  - kernel/time/time.c:C_SYSC_adjtimex
  - kernel/time/posix-timers.c:C_SYSC_clock_adjtime
```
**Symbols:**

```
ffffffff811208e0-ffffffff811209f6: compat_put_timex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int compat_put_timex(struct compat_timex *utp, const struct timex *txc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8112c080)
Location: kernel/compat.c:64
Inline: False
Direct callers:
  - kernel/time/time.c:C_SYSC_adjtimex
  - kernel/time/posix-timers.c:C_SYSC_clock_adjtime
```
**Symbols:**

```
ffffffff8112c080-ffffffff8112c196: compat_put_timex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int compat_put_timex(struct compat_timex *utp, const struct timex *txc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8113a940)
Location: kernel/compat.c:65
Inline: False
Direct callers:
  - kernel/time/time.c:__do_compat_sys_adjtimex
  - kernel/time/posix-timers.c:__do_compat_sys_clock_adjtime
```
**Symbols:**

```
ffffffff8113a940-ffffffff8113aa56: compat_put_timex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int compat_put_timex(struct compat_timex *utp, const struct timex *txc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811461b0)
Location: kernel/compat.c:65
Inline: False
Direct callers:
  - kernel/time/time.c:__do_compat_sys_adjtimex
  - kernel/time/posix-timers.c:__do_compat_sys_clock_adjtime
```
**Symbols:**

```
ffffffff811461b0-ffffffff811462c6: compat_put_timex (STB_GLOBAL)
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
<code>struct timex *txc</code> ➡️ <code>const struct timex *txc</code>
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
