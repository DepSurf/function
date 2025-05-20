# Function: <code>hpet_set_alarm_time</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int hpet_set_alarm_time(unsigned char hrs, unsigned char min, unsigned char sec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81062070)
Location: arch/x86/kernel/hpet.c:1167
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff81062070-ffffffff810620bb: hpet_set_alarm_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int hpet_set_alarm_time(unsigned char hrs, unsigned char min, unsigned char sec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81061ea0)
Location: arch/x86/kernel/hpet.c:1164
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff81061ea0-ffffffff81061eeb: hpet_set_alarm_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int hpet_set_alarm_time(unsigned char hrs, unsigned char min, unsigned char sec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81064f30)
Location: arch/x86/kernel/hpet.c:1259
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff81064f30-ffffffff81064f7b: hpet_set_alarm_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int hpet_set_alarm_time(unsigned char hrs, unsigned char min, unsigned char sec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810647f0)
Location: arch/x86/kernel/hpet.c:1254
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff810647f0-ffffffff8106483b: hpet_set_alarm_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int hpet_set_alarm_time(unsigned char hrs, unsigned char min, unsigned char sec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81068980)
Location: arch/x86/kernel/hpet.c:1254
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff81068980-ffffffff810689cb: hpet_set_alarm_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int hpet_set_alarm_time(unsigned char hrs, unsigned char min, unsigned char sec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8106aca0)
Location: arch/x86/kernel/hpet.c:1254
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff8106aca0-ffffffff8106aceb: hpet_set_alarm_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int hpet_set_alarm_time(unsigned char hrs, unsigned char min, unsigned char sec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81070a30)
Location: arch/x86/kernel/hpet.c:1250
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff81070a30-ffffffff81070a7b: hpet_set_alarm_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int hpet_set_alarm_time(unsigned char hrs, unsigned char min, unsigned char sec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810749c0)
Location: arch/x86/kernel/hpet.c:1166
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff810749c0-ffffffff81074a0b: hpet_set_alarm_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int hpet_set_alarm_time(unsigned char hrs, unsigned char min, unsigned char sec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81075990)
Location: arch/x86/kernel/hpet.c:1166
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff81075990-ffffffff810759db: hpet_set_alarm_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int hpet_set_alarm_time(unsigned char hrs, unsigned char min, unsigned char sec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8107d5d0)
Location: arch/x86/kernel/hpet.c:1166
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff8107d5d0-ffffffff8107d61b: hpet_set_alarm_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int hpet_set_alarm_time(unsigned char hrs, unsigned char min, unsigned char sec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8107d540)
Location: arch/x86/kernel/hpet.c:1276
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff8107d540-ffffffff8107d58b: hpet_set_alarm_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int hpet_set_alarm_time(unsigned char hrs, unsigned char min, unsigned char sec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8107e480)
Location: arch/x86/kernel/hpet.c:1276
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff8107e480-ffffffff8107e4cb: hpet_set_alarm_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int hpet_set_alarm_time(unsigned char hrs, unsigned char min, unsigned char sec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/hpet.c (0)
Location: arch/x86/kernel/hpet.c:1357
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff81c9ee44-ffffffff81c9ee7a: hpet_set_alarm_time.cold (STB_LOCAL)
ffffffff8108d000-ffffffff8108d08a: hpet_set_alarm_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int hpet_set_alarm_time(unsigned char hrs, unsigned char min, unsigned char sec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/hpet.c (0)
Location: arch/x86/kernel/hpet.c:1357
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm_callback
```
**Symbols:**

```
ffffffff81e4e2ba-ffffffff81e4e2f0: hpet_set_alarm_time.cold (STB_LOCAL)
ffffffff8109dcf0-ffffffff8109dd8e: hpet_set_alarm_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int hpet_set_alarm_time(unsigned char hrs, unsigned char min, unsigned char sec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/hpet.c (0)
Location: arch/x86/kernel/hpet.c:1357
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm_callback
```
**Symbols:**

```
ffffffff820542af-ffffffff820542e5: hpet_set_alarm_time.cold (STB_LOCAL)
ffffffff810b4f00-ffffffff810b4f9e: hpet_set_alarm_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int hpet_set_alarm_time(unsigned char hrs, unsigned char min, unsigned char sec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/hpet.c (0)
Location: arch/x86/kernel/hpet.c:1359
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm_callback
```
**Symbols:**

```
ffffffff820d2870-ffffffff820d28a6: hpet_set_alarm_time.cold (STB_LOCAL)
ffffffff810b7fd0-ffffffff810b806e: hpet_set_alarm_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int hpet_set_alarm_time(unsigned char hrs, unsigned char min, unsigned char sec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/hpet.c (0)
Location: arch/x86/kernel/hpet.c:1359
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm_callback
```
**Symbols:**

```
ffffffff821ad6d6-ffffffff821ad70c: hpet_set_alarm_time.cold (STB_LOCAL)
ffffffff810bf410-ffffffff810bf4ae: hpet_set_alarm_time (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int hpet_set_alarm_time(unsigned char hrs, unsigned char min, unsigned char sec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81074990)
Location: arch/x86/kernel/hpet.c:1166
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff81074990-ffffffff810749db: hpet_set_alarm_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int hpet_set_alarm_time(unsigned char hrs, unsigned char min, unsigned char sec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810649c0)
Location: arch/x86/kernel/hpet.c:1166
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff810649c0-ffffffff81064a0b: hpet_set_alarm_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int hpet_set_alarm_time(unsigned char hrs, unsigned char min, unsigned char sec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81074940)
Location: arch/x86/kernel/hpet.c:1166
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff81074940-ffffffff8107498b: hpet_set_alarm_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int hpet_set_alarm_time(unsigned char hrs, unsigned char min, unsigned char sec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810769a0)
Location: arch/x86/kernel/hpet.c:1166
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff810769a0-ffffffff810769eb: hpet_set_alarm_time (STB_GLOBAL)
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
