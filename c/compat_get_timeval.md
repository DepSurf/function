# Function: <code>compat_get_timeval</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int compat_get_timeval(struct timeval *tv, const void *utv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811101b0)
Location: kernel/compat.c:157
Inline: True
Direct callers:
  - kernel/compat.c:compat_SyS_settimeofday
```
**Symbols:**

```
ffffffff811101b0-ffffffff81110233: compat_get_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int compat_get_timeval(struct timeval *tv, const void *utv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81117270)
Location: kernel/compat.c:157
Inline: False
Direct callers:
  - kernel/compat.c:compat_SyS_settimeofday
```
**Symbols:**

```
ffffffff81117270-ffffffff811172ea: compat_get_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int compat_get_timeval(struct timeval *tv, const void *utv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8111e9b0)
Location: kernel/compat.c:157
Inline: False
Direct callers:
  - kernel/compat.c:compat_SyS_settimeofday
```
**Symbols:**

```
ffffffff8111e9b0-ffffffff8111ea2a: compat_get_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int compat_get_timeval(struct timeval *tv, const void *utv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811205c0)
Location: kernel/compat.c:167
Inline: True
Direct callers:
  - kernel/time/time.c:compat_SyS_settimeofday
```
**Symbols:**

```
ffffffff811205c0-ffffffff8112063a: compat_get_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int compat_get_timeval(struct timeval *tv, const void *utv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8112bcf0)
Location: kernel/compat.c:167
Inline: True
Direct callers:
  - kernel/time/time.c:compat_SyS_settimeofday
```
**Symbols:**

```
ffffffff8112bcf0-ffffffff8112bd67: compat_get_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int compat_get_timeval(struct timeval *tv, const void *utv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8113a4b0)
Location: kernel/compat.c:124
Inline: True
Direct callers:
  - kernel/time/time.c:__x32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_compat_sys_settimeofday
```
**Symbols:**

```
ffffffff8113a4b0-ffffffff8113a527: compat_get_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int compat_get_timeval(struct timeval *tv, const void *utv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81145d00)
Location: kernel/compat.c:124
Inline: True
Direct callers:
  - kernel/time/time.c:__x32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_compat_sys_settimeofday
```
**Symbols:**

```
ffffffff81145d00-ffffffff81145d77: compat_get_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int compat_get_timeval(struct timeval *tv, const void *utv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811510d0)
Location: kernel/compat.c:57
Inline: True
Direct callers:
  - kernel/time/time.c:__x32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_compat_sys_settimeofday
```
**Symbols:**

```
ffffffff811510d0-ffffffff81151150: compat_get_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int compat_get_timeval(struct timeval *tv, const void *utv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8115cd40)
Location: kernel/compat.c:57
Inline: True
Direct callers:
  - kernel/time/time.c:__x32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_compat_sys_settimeofday
```
**Symbols:**

```
ffffffff8115cd40-ffffffff8115cdc0: compat_get_timeval (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int compat_get_timeval(struct timeval *tv, const void *utv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffff8000101cc110)
Location: kernel/compat.c:57
Inline: False
Direct callers:
  - kernel/time/time.c:__arm64_compat_sys_settimeofday
```
**Symbols:**

```
ffff8000101cc110-ffff8000101cc408: compat_get_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int compat_get_timeval(struct timeval *tv, const void *utv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (c000000000236860)
Location: kernel/compat.c:57
Inline: False
Direct callers:
  - kernel/time/time.c:__se_compat_sys_settimeofday
```
**Symbols:**

```
c000000000236860-c000000000236978: compat_get_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int compat_get_timeval(struct timeval *tv, const void *utv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81155360)
Location: kernel/compat.c:57
Inline: True
Direct callers:
  - kernel/time/time.c:__x32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_compat_sys_settimeofday
```
**Symbols:**

```
ffffffff81155360-ffffffff811553e0: compat_get_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int compat_get_timeval(struct timeval *tv, const void *utv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81148680)
Location: kernel/compat.c:57
Inline: True
Direct callers:
  - kernel/time/time.c:__x32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_compat_sys_settimeofday
```
**Symbols:**

```
ffffffff81148680-ffffffff81148700: compat_get_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int compat_get_timeval(struct timeval *tv, const void *utv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81153130)
Location: kernel/compat.c:57
Inline: True
Direct callers:
  - kernel/time/time.c:__x32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_compat_sys_settimeofday
```
**Symbols:**

```
ffffffff81153130-ffffffff811531b0: compat_get_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int compat_get_timeval(struct timeval *tv, const void *utv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81160030)
Location: kernel/compat.c:57
Inline: True
Direct callers:
  - kernel/time/time.c:__x32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_compat_sys_settimeofday
```
**Symbols:**

```
ffffffff81160030-ffffffff811600b0: compat_get_timeval (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
