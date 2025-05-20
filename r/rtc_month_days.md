# Function: <code>rtc_month_days</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int rtc_month_days(unsigned int month, unsigned int year);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-lib.c (ffffffff81672f60)
Location: drivers/rtc/rtc-lib.c:33
Inline: True
Inline callers:
  - drivers/rtc/rtc-lib.c:rtc_time64_to_tm
  - drivers/rtc/rtc-lib.c:rtc_valid_tm
Direct callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
```
**Symbols:**

```
ffffffff81672f60-ffffffff81672fb3: rtc_month_days (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int rtc_month_days(unsigned int month, unsigned int year);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-lib.c (ffffffff816d3a38)
Location: drivers/rtc/rtc-lib.c:33
Inline: True
Inline callers:
  - drivers/rtc/rtc-lib.c:rtc_valid_tm
  - drivers/rtc/rtc-lib.c:rtc_time64_to_tm
Direct callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
```
**Symbols:**

```
ffffffff816d3750-ffffffff816d37a3: rtc_month_days (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int rtc_month_days(unsigned int month, unsigned int year);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-lib.c (ffffffff81703718)
Location: drivers/rtc/rtc-lib.c:33
Inline: True
Inline callers:
  - drivers/rtc/rtc-lib.c:rtc_valid_tm
  - drivers/rtc/rtc-lib.c:rtc_time64_to_tm
Direct callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff81703430-ffffffff81703483: rtc_month_days (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int rtc_month_days(unsigned int month, unsigned int year);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-lib.c (ffffffff81718efc)
Location: drivers/rtc/rtc-lib.c:33
Inline: True
Inline callers:
  - drivers/rtc/rtc-lib.c:rtc_valid_tm
  - drivers/rtc/rtc-lib.c:rtc_time64_to_tm
Direct callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff81718c20-ffffffff81718c7b: rtc_month_days (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int rtc_month_days(unsigned int month, unsigned int year);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-lib.c (ffffffff8178a0dc)
Location: drivers/rtc/rtc-lib.c:33
Inline: True
Inline callers:
  - drivers/rtc/rtc-lib.c:rtc_valid_tm
  - drivers/rtc/rtc-lib.c:rtc_time64_to_tm
Direct callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff81789e00-ffffffff81789e5b: rtc_month_days (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int rtc_month_days(unsigned int month, unsigned int year);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-lib.c (ffffffff817cb1ea)
Location: drivers/rtc/rtc-lib.c:33
Inline: True
Inline callers:
  - drivers/rtc/rtc-lib.c:rtc_valid_tm
  - drivers/rtc/rtc-lib.c:rtc_time64_to_tm
Direct callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff817caf10-ffffffff817caf6b: rtc_month_days (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int rtc_month_days(unsigned int month, unsigned int year);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffffffff817f289a)
Location: drivers/rtc/lib.c:33
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_valid_tm
  - drivers/rtc/lib.c:rtc_time64_to_tm
Direct callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff817f25c0-ffffffff817f261b: rtc_month_days (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int rtc_month_days(unsigned int month, unsigned int year);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffffffff8183358b)
Location: drivers/rtc/lib.c:30
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_valid_tm
  - drivers/rtc/lib.c:rtc_time64_to_tm
Direct callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff818332a0-ffffffff818332f2: rtc_month_days (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int rtc_month_days(unsigned int month, unsigned int year);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffffffff81864ecb)
Location: drivers/rtc/lib.c:30
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_valid_tm
  - drivers/rtc/lib.c:rtc_time64_to_tm
Direct callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff81864be0-ffffffff81864c32: rtc_month_days (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int rtc_month_days(unsigned int month, unsigned int year);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffffffff8193881b)
Location: drivers/rtc/lib.c:30
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_valid_tm
  - drivers/rtc/lib.c:rtc_time64_to_tm
Direct callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff81938420-ffffffff81938472: rtc_month_days (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int rtc_month_days(unsigned int month, unsigned int year);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffffffff8193eb4b)
Location: drivers/rtc/lib.c:30
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_valid_tm
  - drivers/rtc/lib.c:rtc_time64_to_tm
Direct callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff8193e750-ffffffff8193e7a2: rtc_month_days (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int rtc_month_days(unsigned int month, unsigned int year);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffffffff8192233b)
Location: drivers/rtc/lib.c:30
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_valid_tm
  - drivers/rtc/lib.c:rtc_time64_to_tm
Direct callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff81921f50-ffffffff81921fa2: rtc_month_days (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int rtc_month_days(unsigned int month, unsigned int year);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffffffff819c52bf)
Location: drivers/rtc/lib.c:30
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_valid_tm
Direct callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff819c4f00-ffffffff819c4f7b: rtc_month_days (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int rtc_month_days(unsigned int month, unsigned int year);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffffffff81b258c7)
Location: drivers/rtc/lib.c:30
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_valid_tm
Direct callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff81b25460-ffffffff81b254e5: rtc_month_days (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int rtc_month_days(unsigned int month, unsigned int year);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffffffff81cb8e87)
Location: drivers/rtc/lib.c:30
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_valid_tm
Direct callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff81cb89c0-ffffffff81cb8a45: rtc_month_days (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int rtc_month_days(unsigned int month, unsigned int year);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffffffff81d205b7)
Location: drivers/rtc/lib.c:30
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_valid_tm
Direct callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff81d20120-ffffffff81d201a5: rtc_month_days (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int rtc_month_days(unsigned int month, unsigned int year);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffffffff81dd62e7)
Location: drivers/rtc/lib.c:30
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_valid_tm
Direct callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff81dd5e50-ffffffff81dd5ed5: rtc_month_days (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int rtc_month_days(unsigned int month, unsigned int year);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffff800010aa66d0)
Location: drivers/rtc/lib.c:30
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_valid_tm
  - drivers/rtc/lib.c:rtc_time64_to_tm
Direct callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_read_time
  - drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_read_time
```
**Symbols:**

```
ffff800010aa6320-ffff800010aa63b0: rtc_month_days (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int rtc_month_days(unsigned int month, unsigned int year);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (c0b84f68)
Location: drivers/rtc/lib.c:30
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_valid_tm
  - drivers/rtc/lib.c:rtc_time64_to_tm
Direct callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
```
**Symbols:**

```
c0b84e18-c0b84e8c: rtc_month_days (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int rtc_month_days(unsigned int month, unsigned int year);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (c000000000b8724c)
Location: drivers/rtc/lib.c:30
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_valid_tm
  - drivers/rtc/lib.c:rtc_time64_to_tm
Direct callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
```
**Symbols:**

```
c000000000b86e10-c000000000b86eb8: rtc_month_days (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int rtc_month_days(unsigned int month, unsigned int year);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffffffe0006b2a50)
Location: drivers/rtc/lib.c:30
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_valid_tm
  - drivers/rtc/lib.c:rtc_time64_to_tm
Direct callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
```
**Symbols:**

```
ffffffe0006b27ca-ffffffe0006b2836: rtc_month_days (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int rtc_month_days(unsigned int month, unsigned int year);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffffffff81817b7b)
Location: drivers/rtc/lib.c:30
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_valid_tm
  - drivers/rtc/lib.c:rtc_time64_to_tm
Direct callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff81817890-ffffffff818178e2: rtc_month_days (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int rtc_month_days(unsigned int month, unsigned int year);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffffffff817df26b)
Location: drivers/rtc/lib.c:30
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_valid_tm
  - drivers/rtc/lib.c:rtc_time64_to_tm
Direct callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff817def80-ffffffff817defd2: rtc_month_days (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int rtc_month_days(unsigned int month, unsigned int year);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffffffff8185905b)
Location: drivers/rtc/lib.c:30
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_valid_tm
  - drivers/rtc/lib.c:rtc_time64_to_tm
Direct callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff81858d70-ffffffff81858dc2: rtc_month_days (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int rtc_month_days(unsigned int month, unsigned int year);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffffffff8187413b)
Location: drivers/rtc/lib.c:30
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_valid_tm
  - drivers/rtc/lib.c:rtc_time64_to_tm
Direct callers:
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff81873e50-ffffffff81873ea2: rtc_month_days (STB_GLOBAL)
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
