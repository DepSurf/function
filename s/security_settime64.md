# Function: <code>security_settime64</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_settime64(const struct timespec *ts, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81372580)
Location: security/security.c:212
Inline: False
Direct callers:
  - kernel/time/time.c:SyS_stime
  - kernel/compat.c:compat_SyS_stime
```
**Symbols:**

```
ffffffff81372580-ffffffff813725cf: security_settime64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_settime64(const struct timespec *ts, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81388eb0)
Location: security/security.c:212
Inline: False
Direct callers:
  - kernel/time/time.c:SyS_stime
  - kernel/compat.c:compat_SyS_stime
```
**Symbols:**

```
ffffffff81388eb0-ffffffff81388eff: security_settime64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_settime64(const struct timespec *ts, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139e220)
Location: security/security.c:783
Inline: False
Direct callers:
  - kernel/time/time.c:compat_SyS_stime
  - kernel/time/time.c:SyS_stime
```
**Symbols:**

```
ffffffff8139e220-ffffffff8139e26f: security_settime64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_settime64(const struct timespec *ts, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c3bd0)
Location: security/security.c:733
Inline: False
Direct callers:
  - kernel/time/time.c:compat_SyS_stime
  - kernel/time/time.c:SyS_stime
```
**Symbols:**

```
ffffffff813c3bd0-ffffffff813c3c25: security_settime64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_settime64(const struct timespec64 *ts, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f4240)
Location: security/security.c:310
Inline: False
Direct callers:
  - kernel/time/time.c:__x32_compat_sys_stime
  - kernel/time/time.c:__ia32_compat_sys_stime
  - kernel/time/time.c:__ia32_sys_stime
  - kernel/time/time.c:__x64_sys_stime
```
**Symbols:**

```
ffffffff813f4240-ffffffff813f4284: security_settime64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_settime64(const struct timespec64 *ts, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8140f620)
Location: security/security.c:792
Inline: False
Direct callers:
  - kernel/time/time.c:__x32_compat_sys_stime
  - kernel/time/time.c:__ia32_compat_sys_stime
  - kernel/time/time.c:__ia32_sys_stime
  - kernel/time/time.c:__x64_sys_stime
```
**Symbols:**

```
ffffffff8140f620-ffffffff8140f664: security_settime64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_settime64(const struct timespec64 *ts, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143cae0)
Location: security/security.c:791
Inline: False
Direct callers:
  - kernel/time/time.c:__ia32_sys_stime32
  - kernel/time/time.c:__x64_sys_stime32
  - kernel/time/time.c:__ia32_sys_stime
  - kernel/time/time.c:__x64_sys_stime
```
**Symbols:**

```
ffffffff8143cae0-ffffffff8143cb2d: security_settime64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_settime64(const struct timespec64 *ts, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814565e0)
Location: security/security.c:825
Inline: False
Direct callers:
  - kernel/time/time.c:__ia32_sys_stime32
  - kernel/time/time.c:__x64_sys_stime32
  - kernel/time/time.c:__ia32_sys_stime
  - kernel/time/time.c:__x64_sys_stime
```
**Symbols:**

```
ffffffff814565e0-ffffffff81456624: security_settime64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_settime64(const struct timespec64 *ts, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a93a0)
Location: security/security.c:968
Inline: False
Direct callers:
  - kernel/time/time.c:__ia32_sys_stime32
  - kernel/time/time.c:__x64_sys_stime32
  - kernel/time/time.c:__ia32_sys_stime
  - kernel/time/time.c:__x64_sys_stime
```
**Symbols:**

```
ffffffff814a93a0-ffffffff814a93e4: security_settime64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_settime64(const struct timespec64 *ts, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c69a0)
Location: security/security.c:970
Inline: False
Direct callers:
  - kernel/time/time.c:__ia32_sys_stime32
  - kernel/time/time.c:__x64_sys_stime32
  - kernel/time/time.c:__ia32_sys_stime
  - kernel/time/time.c:__x64_sys_stime
```
**Symbols:**

```
ffffffff814c69a0-ffffffff814c69e4: security_settime64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_settime64(const struct timespec64 *ts, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cca90)
Location: security/security.c:994
Inline: False
Direct callers:
  - kernel/time/time.c:__ia32_sys_stime32
  - kernel/time/time.c:__x64_sys_stime32
  - kernel/time/time.c:__ia32_sys_stime
  - kernel/time/time.c:__x64_sys_stime
```
**Symbols:**

```
ffffffff814cca90-ffffffff814ccad4: security_settime64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_settime64(const struct timespec64 *ts, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81525c10)
Location: security/security.c:994
Inline: False
Direct callers:
  - kernel/time/time.c:__ia32_sys_stime32
  - kernel/time/time.c:__x64_sys_stime32
  - kernel/time/time.c:__ia32_sys_stime
  - kernel/time/time.c:__x64_sys_stime
```
**Symbols:**

```
ffffffff81525c10-ffffffff81525c54: security_settime64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_settime64(const struct timespec64 *ts, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815b9ee0)
Location: security/security.c:993
Inline: False
Direct callers:
  - kernel/time/time.c:do_sys_settimeofday64
  - kernel/time/time.c:__ia32_sys_stime32
  - kernel/time/time.c:__x64_sys_stime32
  - kernel/time/time.c:__ia32_sys_stime
  - kernel/time/time.c:__x64_sys_stime
```
**Symbols:**

```
ffffffff815b9ee0-ffffffff815b9f3d: security_settime64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_settime64(const struct timespec64 *ts, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81665760)
Location: security/security.c:991
Inline: False
Direct callers:
  - kernel/time/time.c:do_sys_settimeofday64
  - kernel/time/time.c:__ia32_sys_stime32
  - kernel/time/time.c:__x64_sys_stime32
  - kernel/time/time.c:__ia32_sys_stime
  - kernel/time/time.c:__x64_sys_stime
```
**Symbols:**

```
ffffffff81665760-ffffffff816657bd: security_settime64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_settime64(const struct timespec64 *ts, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169dce0)
Location: security/security.c:1138
Inline: False
Direct callers:
  - kernel/time/time.c:do_sys_settimeofday64
  - kernel/time/time.c:__ia32_sys_stime32
  - kernel/time/time.c:__x64_sys_stime32
  - kernel/time/time.c:__ia32_sys_stime
  - kernel/time/time.c:__x64_sys_stime
```
**Symbols:**

```
ffffffff8169dce0-ffffffff8169dd3d: security_settime64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_settime64(const struct timespec64 *ts, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816da610)
Location: security/security.c:1181
Inline: False
Direct callers:
  - kernel/time/time.c:do_sys_settimeofday64
  - kernel/time/time.c:__ia32_sys_stime32
  - kernel/time/time.c:__x64_sys_stime32
  - kernel/time/time.c:__ia32_sys_stime
  - kernel/time/time.c:__x64_sys_stime
```
**Symbols:**

```
ffffffff816da610-ffffffff816da66d: security_settime64 (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int security_settime64(const struct timespec64 *ts, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010541e80)
Location: security/security.c:825
Inline: False
```
**Symbols:**

```
ffff800010541e80-ffff800010541ee0: security_settime64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_settime64(const struct timespec64 *ts, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f7e4c)
Location: security/security.c:825
Inline: False
```
**Symbols:**

```
c06f7e4c-c06f7ea8: security_settime64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_settime64(const struct timespec64 *ts, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000694be0)
Location: security/security.c:825
Inline: False
Direct callers:
  - kernel/time/time.c:__se_sys_stime32
  - kernel/time/time.c:__se_sys_stime
```
**Symbols:**

```
c000000000694be0-c000000000694c9c: security_settime64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_settime64(const struct timespec64 *ts, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039e974)
Location: security/security.c:825
Inline: False
```
**Symbols:**

```
ffffffe00039e974-ffffffe00039e9b8: security_settime64 (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int security_settime64(const struct timespec64 *ts, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144ebc0)
Location: security/security.c:825
Inline: False
Direct callers:
  - kernel/time/time.c:__ia32_sys_stime32
  - kernel/time/time.c:__x64_sys_stime32
  - kernel/time/time.c:__ia32_sys_stime
  - kernel/time/time.c:__x64_sys_stime
```
**Symbols:**

```
ffffffff8144ebc0-ffffffff8144ec04: security_settime64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_settime64(const struct timespec64 *ts, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143f610)
Location: security/security.c:825
Inline: False
Direct callers:
  - kernel/time/time.c:__ia32_sys_stime32
  - kernel/time/time.c:__x64_sys_stime32
  - kernel/time/time.c:__ia32_sys_stime
  - kernel/time/time.c:__x64_sys_stime
```
**Symbols:**

```
ffffffff8143f610-ffffffff8143f654: security_settime64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_settime64(const struct timespec64 *ts, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144ac60)
Location: security/security.c:825
Inline: False
Direct callers:
  - kernel/time/time.c:__ia32_sys_stime32
  - kernel/time/time.c:__x64_sys_stime32
  - kernel/time/time.c:__ia32_sys_stime
  - kernel/time/time.c:__x64_sys_stime
```
**Symbols:**

```
ffffffff8144ac60-ffffffff8144aca4: security_settime64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_settime64(const struct timespec64 *ts, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81462030)
Location: security/security.c:825
Inline: False
Direct callers:
  - kernel/time/time.c:__ia32_sys_stime32
  - kernel/time/time.c:__x64_sys_stime32
  - kernel/time/time.c:__ia32_sys_stime
  - kernel/time/time.c:__x64_sys_stime
```
**Symbols:**

```
ffffffff81462030-ffffffff81462074: security_settime64 (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct timespec *ts</code> ➡️ <code>const struct timespec64 *ts</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
