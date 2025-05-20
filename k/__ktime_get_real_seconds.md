# Function: <code>__ktime_get_real_seconds</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
time64_t __ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810f5a60)
Location: kernel/time/timekeeping.c:871
Inline: True
```
**Symbols:**

```
ffffffff810f5a60-ffffffff810f5a72: __ktime_get_real_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
time64_t __ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810fcc80)
Location: kernel/time/timekeeping.c:876
Inline: True
Direct callers:
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
```
**Symbols:**

```
ffffffff810fcc80-ffffffff810fcc92: __ktime_get_real_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
time64_t __ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810ffaa0)
Location: kernel/time/timekeeping.c:905
Inline: True
Direct callers:
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
```
**Symbols:**

```
ffffffff810ffaa0-ffffffff810ffab2: __ktime_get_real_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
time64_t __ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:937
Inline: False
Direct callers:
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
```
**Symbols:**

```
ffffffff81101d30-ffffffff81101d42: __ktime_get_real_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
time64_t __ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:941
Inline: False
Direct callers:
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
```
**Symbols:**

```
ffffffff8110cc30-ffffffff8110cc42: __ktime_get_real_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
time64_t __ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811187a0)
Location: kernel/time/timekeeping.c:942
Inline: False
Direct callers:
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/debug/kdb/kdb_main.c:kdb_summary
```
**Symbols:**

```
ffffffff811187a0-ffffffff811187b2: __ktime_get_real_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
time64_t __ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811242f0)
Location: kernel/time/timekeeping.c:949
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/debug/kdb/kdb_main.c:kdb_summary
```
**Symbols:**

```
ffffffff811242f0-ffffffff81124302: __ktime_get_real_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
time64_t __ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8112ec40)
Location: kernel/time/timekeeping.c:956
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/debug/kdb/kdb_main.c:kdb_summary
```
**Symbols:**

```
ffffffff8112ec40-ffffffff8112ec52: __ktime_get_real_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
time64_t __ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8113ac00)
Location: kernel/time/timekeeping.c:956
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/debug/kdb/kdb_main.c:kdb_summary
```
**Symbols:**

```
ffffffff8113ac00-ffffffff8113ac12: __ktime_get_real_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
time64_t __ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81bbfab0)
Location: kernel/time/timekeeping.c:956
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
  - kernel/time/ntp.c:process_adjtimex_modes
  - kernel/time/ntp.c:ntp_update_offset
  - kernel/time/ntp.c:ntp_update_offset
  - kernel/time/ntp.c:ntp_update_offset
  - kernel/debug/kdb/kdb_main.c:kdb_summary
```
**Symbols:**

```
ffffffff81bbfab0-ffffffff81bbfab8: __ktime_get_real_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
time64_t __ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81c38a70)
Location: kernel/time/timekeeping.c:1025
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
  - kernel/time/ntp.c:process_adjtimex_modes
  - kernel/time/ntp.c:ntp_update_offset
  - kernel/time/ntp.c:ntp_update_offset
  - kernel/time/ntp.c:ntp_update_offset
  - kernel/debug/kdb/kdb_main.c:kdb_summary
```
**Symbols:**

```
ffffffff81c38a70-ffffffff81c38a78: __ktime_get_real_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
time64_t __ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81c2ae70)
Location: kernel/time/timekeeping.c:1025
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
  - kernel/time/ntp.c:process_adjtimex_modes
  - kernel/time/ntp.c:process_adjtimex_modes
  - kernel/time/ntp.c:process_adjtimex_modes
  - kernel/time/ntp.c:process_adjtimex_modes
  - kernel/debug/kdb/kdb_main.c:kdb_summary
```
**Symbols:**

```
ffffffff81c2ae70-ffffffff81c2ae78: __ktime_get_real_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
time64_t __ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81d49400)
Location: kernel/time/timekeeping.c:1025
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
  - kernel/time/ntp.c:process_adjtimex_modes
  - kernel/time/ntp.c:ntp_update_offset
  - kernel/time/ntp.c:ntp_update_offset
  - kernel/time/ntp.c:ntp_update_offset
  - kernel/debug/kdb/kdb_main.c:kdb_summary
```
**Symbols:**

```
ffffffff81d49400-ffffffff81d49408: __ktime_get_real_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
time64_t __ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81f188b0)
Location: kernel/time/timekeeping.c:1044
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
  - kernel/time/ntp.c:process_adjtimex_modes
  - kernel/time/ntp.c:ntp_update_offset
  - kernel/time/ntp.c:ntp_update_offset
  - kernel/time/ntp.c:ntp_update_offset
  - kernel/debug/kdb/kdb_main.c:kdb_summary
```
**Symbols:**

```
ffffffff81f188b0-ffffffff81f188bc: __ktime_get_real_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
time64_t __ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff820bff10)
Location: kernel/time/timekeeping.c:1044
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
  - kernel/time/ntp.c:process_adjtimex_modes
  - kernel/time/ntp.c:ntp_update_offset
  - kernel/time/ntp.c:ntp_update_offset
  - kernel/time/ntp.c:ntp_update_offset
  - kernel/debug/kdb/kdb_main.c:kdb_summary
```
**Symbols:**

```
ffffffff820bff10-ffffffff820bff1c: __ktime_get_real_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
time64_t __ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff82141d50)
Location: kernel/time/timekeeping.c:1044
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
  - kernel/time/ntp.c:process_adjtimex_modes
  - kernel/time/ntp.c:ntp_update_offset
  - kernel/time/ntp.c:ntp_update_offset
  - kernel/time/ntp.c:ntp_update_offset
  - kernel/debug/kdb/kdb_main.c:kdb_summary
```
**Symbols:**

```
ffffffff82141d50-ffffffff82141d5c: __ktime_get_real_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
time64_t __ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff822240d0)
Location: kernel/time/timekeeping.c:1044
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
  - kernel/time/ntp.c:process_adjtimex_modes
  - kernel/time/ntp.c:ntp_update_offset
  - kernel/time/ntp.c:ntp_update_offset
  - kernel/time/ntp.c:ntp_update_offset
  - kernel/debug/kdb/kdb_main.c:kdb_summary
```
**Symbols:**

```
ffffffff822240d0-ffffffff822240dc: __ktime_get_real_seconds (STB_GLOBAL)
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
time64_t __ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffff8000101a4ce8)
Location: kernel/time/timekeeping.c:956
Inline: False
Direct callers:
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/debug/kdb/kdb_main.c:kdb_summary
```
**Symbols:**

```
ffff8000101a4ce8-ffff8000101a4d08: __ktime_get_real_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
time64_t __ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c03efbec)
Location: kernel/time/timekeeping.c:956
Inline: False
Direct callers:
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/debug/kdb/kdb_main.c:kdb_summary
```
**Symbols:**

```
c03efbec-c03efc10: __ktime_get_real_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
time64_t __ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c000000000206940)
Location: kernel/time/timekeeping.c:956
Inline: False
Direct callers:
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/debug/kdb/kdb_main.c:kdb_summary
```
**Symbols:**

```
c000000000206940-c00000000020695c: __ktime_get_real_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
time64_t __ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffe0001312e6)
Location: kernel/time/timekeeping.c:956
Inline: False
Direct callers:
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
```
**Symbols:**

```
ffffffe0001312e6-ffffffe000131308: __ktime_get_real_seconds (STB_GLOBAL)
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
time64_t __ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811333b0)
Location: kernel/time/timekeeping.c:956
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/debug/kdb/kdb_main.c:kdb_summary
```
**Symbols:**

```
ffffffff811333b0-ffffffff811333c2: __ktime_get_real_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
time64_t __ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81125e10)
Location: kernel/time/timekeeping.c:956
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/debug/kdb/kdb_main.c:kdb_summary
```
**Symbols:**

```
ffffffff81125e10-ffffffff81125e22: __ktime_get_real_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
time64_t __ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811310d0)
Location: kernel/time/timekeeping.c:956
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/debug/kdb/kdb_main.c:kdb_summary
```
**Symbols:**

```
ffffffff811310d0-ffffffff811310e2: __ktime_get_real_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
time64_t __ktime_get_real_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8113daf0)
Location: kernel/time/timekeeping.c:956
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/time/ntp.c:__do_adjtimex
  - kernel/debug/kdb/kdb_main.c:kdb_summary
```
**Symbols:**

```
ffffffff8113daf0-ffffffff8113db02: __ktime_get_real_seconds (STB_GLOBAL)
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
