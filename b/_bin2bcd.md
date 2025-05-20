# Function: <code>_bin2bcd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned char _bin2bcd(unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (ffffffff813f7e00)
Location: lib/bcd.c:10
Inline: False
Direct callers:
  - arch/x86/kernel/rtc.c:mach_set_rtc_mmss
  - arch/x86/kernel/rtc.c:mach_set_rtc_mmss
  - arch/x86/kernel/rtc.c:mach_set_rtc_mmss
  - arch/x86/kernel/rtc.c:mach_set_rtc_mmss
  - arch/x86/kernel/rtc.c:mach_set_rtc_mmss
  - arch/x86/kernel/rtc.c:mach_set_rtc_mmss
  - arch/x86/kernel/rtc.c:mach_set_rtc_mmss
  - drivers/base/power/trace.c:generate_pm_trace
  - drivers/base/power/trace.c:generate_pm_trace
  - drivers/base/power/trace.c:generate_pm_trace
  - drivers/base/power/trace.c:generate_pm_trace
  - drivers/base/power/trace.c:generate_pm_trace
  - drivers/base/power/trace.c:generate_pm_trace
  - drivers/base/power/trace.c:generate_pm_trace
  - drivers/rtc/rtc-cmos.c:cmos_set_time
  - drivers/rtc/rtc-cmos.c:cmos_set_time
  - drivers/rtc/rtc-cmos.c:cmos_set_time
  - drivers/rtc/rtc-cmos.c:cmos_set_time
  - drivers/rtc/rtc-cmos.c:cmos_set_time
  - drivers/rtc/rtc-cmos.c:cmos_set_time
  - drivers/rtc/rtc-cmos.c:cmos_set_time
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff813f7e00-ffffffff813f7e20: _bin2bcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned char _bin2bcd(unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (ffffffff8143ecc0)
Location: lib/bcd.c:10
Inline: False
Direct callers:
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff8143ecc0-ffffffff8143ece0: _bin2bcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned char _bin2bcd(unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (ffffffff8145bd10)
Location: lib/bcd.c:10
Inline: False
Direct callers:
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff8145bd10-ffffffff8145bd30: _bin2bcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned char _bin2bcd(unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (ffffffff814611f0)
Location: lib/bcd.c:10
Inline: False
Direct callers:
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff814611f0-ffffffff81461210: _bin2bcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned char _bin2bcd(unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (ffffffff8148d0c0)
Location: lib/bcd.c:11
Inline: False
Direct callers:
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff8148d0c0-ffffffff8148d0e0: _bin2bcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned char _bin2bcd(unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (ffffffff814c1e40)
Location: lib/bcd.c:11
Inline: False
Direct callers:
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff814c1e40-ffffffff814c1e5b: _bin2bcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned char _bin2bcd(unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (ffffffff814d6530)
Location: lib/bcd.c:11
Inline: False
Direct callers:
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff814d6530-ffffffff814d654b: _bin2bcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned char _bin2bcd(unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (ffffffff815023e0)
Location: lib/bcd.c:11
Inline: False
Direct callers:
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff815023e0-ffffffff815023fe: _bin2bcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned char _bin2bcd(unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (ffffffff815202f0)
Location: lib/bcd.c:11
Inline: False
Direct callers:
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff815202f0-ffffffff8152030e: _bin2bcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned char _bin2bcd(unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (ffffffff815834a0)
Location: lib/bcd.c:11
Inline: False
Direct callers:
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff815834a0-ffffffff815834bf: _bin2bcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned char _bin2bcd(unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (ffffffff815a0320)
Location: lib/bcd.c:11
Inline: False
Direct callers:
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff815a0320-ffffffff815a033f: _bin2bcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned char _bin2bcd(unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (ffffffff815a7110)
Location: lib/bcd.c:11
Inline: False
Direct callers:
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff815a7110-ffffffff815a712e: _bin2bcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned char _bin2bcd(unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (ffffffff81610050)
Location: lib/bcd.c:11
Inline: False
Direct callers:
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff81610050-ffffffff8161006e: _bin2bcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned char _bin2bcd(unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (ffffffff816dc3b0)
Location: lib/bcd.c:11
Inline: False
Direct callers:
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff816dc3b0-ffffffff816dc3d6: _bin2bcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned char _bin2bcd(unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (ffffffff817cc0a0)
Location: lib/bcd.c:11
Inline: False
Direct callers:
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff817cc0a0-ffffffff817cc0c6: _bin2bcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned char _bin2bcd(unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (ffffffff8180a4e0)
Location: lib/bcd.c:11
Inline: False
Direct callers:
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff8180a4e0-ffffffff8180a506: _bin2bcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned char _bin2bcd(unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (ffffffff81850cc0)
Location: lib/bcd.c:11
Inline: False
Direct callers:
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff81850cc0-ffffffff81850ce6: _bin2bcd (STB_GLOBAL)
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
unsigned char _bin2bcd(unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (ffff8000106297f8)
Location: lib/bcd.c:11
Inline: False
Direct callers:
  - drivers/rtc/rtc-mv.c:mv_rtc_set_alarm
  - drivers/rtc/rtc-mv.c:mv_rtc_set_alarm
  - drivers/rtc/rtc-mv.c:mv_rtc_set_alarm
  - drivers/rtc/rtc-mv.c:mv_rtc_set_alarm
  - drivers/rtc/rtc-mv.c:mv_rtc_set_alarm
  - drivers/rtc/rtc-mv.c:mv_rtc_set_alarm
  - drivers/rtc/rtc-mv.c:mv_rtc_set_time
  - drivers/rtc/rtc-mv.c:mv_rtc_set_time
  - drivers/rtc/rtc-mv.c:mv_rtc_set_time
  - drivers/rtc/rtc-mv.c:mv_rtc_set_time
  - drivers/rtc/rtc-mv.c:mv_rtc_set_time
  - drivers/rtc/rtc-mv.c:mv_rtc_set_time
  - drivers/rtc/rtc-mv.c:mv_rtc_set_time
```
**Symbols:**

```
ffff8000106297f8-ffff800010629818: _bin2bcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned char _bin2bcd(unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (c07d0a50)
Location: lib/bcd.c:11
Inline: False
Direct callers:
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mv.c:mv_rtc_set_alarm
  - drivers/rtc/rtc-mv.c:mv_rtc_set_alarm
  - drivers/rtc/rtc-mv.c:mv_rtc_set_alarm
  - drivers/rtc/rtc-mv.c:mv_rtc_set_alarm
  - drivers/rtc/rtc-mv.c:mv_rtc_set_alarm
  - drivers/rtc/rtc-mv.c:mv_rtc_set_alarm
  - drivers/rtc/rtc-mv.c:mv_rtc_set_time
  - drivers/rtc/rtc-mv.c:mv_rtc_set_time
  - drivers/rtc/rtc-mv.c:mv_rtc_set_time
  - drivers/rtc/rtc-mv.c:mv_rtc_set_time
  - drivers/rtc/rtc-mv.c:mv_rtc_set_time
  - drivers/rtc/rtc-mv.c:mv_rtc_set_time
  - drivers/rtc/rtc-mv.c:mv_rtc_set_time
  - drivers/rtc/rtc-omap.c:tm2bcd
  - drivers/rtc/rtc-omap.c:tm2bcd
  - drivers/rtc/rtc-omap.c:tm2bcd
  - drivers/rtc/rtc-omap.c:tm2bcd
  - drivers/rtc/rtc-omap.c:tm2bcd
  - drivers/rtc/rtc-omap.c:tm2bcd
  - drivers/rtc/rtc-pcf8523.c:pcf8523_rtc_set_time
  - drivers/rtc/rtc-pcf8523.c:pcf8523_rtc_set_time
  - drivers/rtc/rtc-pcf8523.c:pcf8523_rtc_set_time
  - drivers/rtc/rtc-pcf8523.c:pcf8523_rtc_set_time
  - drivers/rtc/rtc-pcf8523.c:pcf8523_rtc_set_time
  - drivers/rtc/rtc-pcf8523.c:pcf8523_rtc_set_time
  - drivers/rtc/rtc-pl031.c:pl031_stv2_tm_to_time
  - drivers/rtc/rtc-pl031.c:pl031_stv2_tm_to_time
  - drivers/rtc/rtc-s3c.c:s3c_rtc_setalarm
  - drivers/rtc/rtc-s3c.c:s3c_rtc_setalarm
  - drivers/rtc/rtc-s3c.c:s3c_rtc_setalarm
  - drivers/rtc/rtc-s3c.c:s3c_rtc_setalarm
  - drivers/rtc/rtc-s3c.c:s3c_rtc_setalarm
  - drivers/rtc/rtc-s3c.c:s3c_rtc_settime
  - drivers/rtc/rtc-s3c.c:s3c_rtc_settime
  - drivers/rtc/rtc-s3c.c:s3c_rtc_settime
  - drivers/rtc/rtc-s3c.c:s3c_rtc_settime
  - drivers/rtc/rtc-s3c.c:s3c_rtc_settime
  - drivers/rtc/rtc-s3c.c:s3c_rtc_settime
  - drivers/rtc/rtc-twl.c:twl_rtc_set_alarm
  - drivers/rtc/rtc-twl.c:twl_rtc_set_alarm
  - drivers/rtc/rtc-twl.c:twl_rtc_set_alarm
  - drivers/rtc/rtc-twl.c:twl_rtc_set_alarm
  - drivers/rtc/rtc-twl.c:twl_rtc_set_alarm
  - drivers/rtc/rtc-twl.c:twl_rtc_set_alarm
  - drivers/rtc/rtc-twl.c:twl_rtc_set_time
  - drivers/rtc/rtc-twl.c:twl_rtc_set_time
  - drivers/rtc/rtc-twl.c:twl_rtc_set_time
  - drivers/rtc/rtc-twl.c:twl_rtc_set_time
  - drivers/rtc/rtc-twl.c:twl_rtc_set_time
  - drivers/rtc/rtc-twl.c:twl_rtc_set_time
```
**Symbols:**

```
c07d0a50-c07d0a80: _bin2bcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned char _bin2bcd(unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (c0000000007cb110)
Location: lib/bcd.c:11
Inline: False
Direct callers:
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-opal.c:tm_to_opal
  - drivers/rtc/rtc-opal.c:tm_to_opal
  - drivers/rtc/rtc-opal.c:tm_to_opal
  - drivers/rtc/rtc-opal.c:tm_to_opal
  - drivers/rtc/rtc-opal.c:tm_to_opal
  - drivers/rtc/rtc-opal.c:tm_to_opal
  - drivers/rtc/rtc-opal.c:tm_to_opal
```
**Symbols:**

```
c0000000007cb110-c0000000007cb138: _bin2bcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned char _bin2bcd(unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (ffffffe00045a44a)
Location: lib/bcd.c:11
Inline: False
```
**Symbols:**

```
ffffffe00045a44a-ffffffe00045a46a: _bin2bcd (STB_GLOBAL)
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
unsigned char _bin2bcd(unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (ffffffff815188d0)
Location: lib/bcd.c:11
Inline: False
Direct callers:
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff815188d0-ffffffff815188ee: _bin2bcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned char _bin2bcd(unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (ffffffff81508bd0)
Location: lib/bcd.c:11
Inline: False
Direct callers:
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff81508bd0-ffffffff81508bee: _bin2bcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned char _bin2bcd(unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (ffffffff81514960)
Location: lib/bcd.c:11
Inline: False
Direct callers:
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff81514960-ffffffff8151497e: _bin2bcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned char _bin2bcd(unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bcd.c (ffffffff8152e0d0)
Location: lib/bcd.c:11
Inline: False
Direct callers:
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff8152e0d0-ffffffff8152e0ee: _bin2bcd (STB_GLOBAL)
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
