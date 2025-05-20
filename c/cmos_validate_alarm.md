# Function: <code>cmos_validate_alarm</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cmos_validate_alarm(struct device *dev, struct rtc_wkalrm *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-cmos.c (ffffffff81707350)
Location: drivers/rtc/rtc-cmos.c:335
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff81707350-ffffffff81707510: cmos_validate_alarm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cmos_validate_alarm(struct device *dev, struct rtc_wkalrm *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-cmos.c (ffffffff8171cf40)
Location: drivers/rtc/rtc-cmos.c:338
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff8171cf40-ffffffff8171d0ec: cmos_validate_alarm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cmos_validate_alarm(struct device *dev, struct rtc_wkalrm *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-cmos.c (ffffffff8178e1c0)
Location: drivers/rtc/rtc-cmos.c:338
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff8178e1c0-ffffffff8178e36c: cmos_validate_alarm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cmos_validate_alarm(struct device *dev, struct rtc_wkalrm *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-cmos.c (ffffffff817d06a0)
Location: drivers/rtc/rtc-cmos.c:369
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff817d06a0-ffffffff817d083e: cmos_validate_alarm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cmos_validate_alarm(struct device *dev, struct rtc_wkalrm *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-cmos.c (ffffffff817f76f0)
Location: drivers/rtc/rtc-cmos.c:383
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff817f76f0-ffffffff817f788e: cmos_validate_alarm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int cmos_validate_alarm(struct device *dev, struct rtc_wkalrm *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/rtc-cmos.c (0)
Location: drivers/rtc/rtc-cmos.c:379
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff81838410-ffffffff81838572: cmos_validate_alarm (STB_LOCAL)
ffffffff81839c18-ffffffff81839c63: cmos_validate_alarm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int cmos_validate_alarm(struct device *dev, struct rtc_wkalrm *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/rtc-cmos.c (0)
Location: drivers/rtc/rtc-cmos.c:379
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff81869d80-ffffffff81869ee2: cmos_validate_alarm (STB_LOCAL)
ffffffff8186b588-ffffffff8186b5d3: cmos_validate_alarm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int cmos_validate_alarm(struct device *dev, struct rtc_wkalrm *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/rtc-cmos.c (0)
Location: drivers/rtc/rtc-cmos.c:379
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff8193d9e0-ffffffff8193db5e: cmos_validate_alarm (STB_LOCAL)
ffffffff8193f2d9-ffffffff8193f324: cmos_validate_alarm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int cmos_validate_alarm(struct device *dev, struct rtc_wkalrm *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/rtc-cmos.c (0)
Location: drivers/rtc/rtc-cmos.c:379
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff81943a60-ffffffff81943bde: cmos_validate_alarm (STB_LOCAL)
ffffffff81c2462d-ffffffff81c24678: cmos_validate_alarm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int cmos_validate_alarm(struct device *dev, struct rtc_wkalrm *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/rtc-cmos.c (0)
Location: drivers/rtc/rtc-cmos.c:379
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff81927290-ffffffff8192740e: cmos_validate_alarm (STB_LOCAL)
ffffffff81c166ea-ffffffff81c16735: cmos_validate_alarm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int cmos_validate_alarm(struct device *dev, struct rtc_wkalrm *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/rtc-cmos.c (0)
Location: drivers/rtc/rtc-cmos.c:373
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff819ca350-ffffffff819ca4dd: cmos_validate_alarm (STB_LOCAL)
ffffffff81d251d2-ffffffff81d25232: cmos_validate_alarm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int cmos_validate_alarm(struct device *dev, struct rtc_wkalrm *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/rtc-cmos.c (0)
Location: drivers/rtc/rtc-cmos.c:406
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff81b2bac0-ffffffff81b2bc62: cmos_validate_alarm (STB_LOCAL)
ffffffff81ef0f9d-ffffffff81ef0fd8: cmos_validate_alarm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cmos_validate_alarm(struct device *dev, struct rtc_wkalrm *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-cmos.c (ffffffff81cbf940)
Location: drivers/rtc/rtc-cmos.c:406
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff81cbf940-ffffffff81cbfb13: cmos_validate_alarm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cmos_validate_alarm(struct device *dev, struct rtc_wkalrm *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-cmos.c (ffffffff81d272a0)
Location: drivers/rtc/rtc-cmos.c:406
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff81d272a0-ffffffff81d27471: cmos_validate_alarm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cmos_validate_alarm(struct device *dev, struct rtc_wkalrm *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-cmos.c (ffffffff81ddd0b0)
Location: drivers/rtc/rtc-cmos.c:406
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff81ddd0b0-ffffffff81ddd281: cmos_validate_alarm (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int cmos_validate_alarm(struct device *dev, struct rtc_wkalrm *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/rtc-cmos.c (0)
Location: drivers/rtc/rtc-cmos.c:379
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff8181ca30-ffffffff8181cb92: cmos_validate_alarm (STB_LOCAL)
ffffffff8181e238-ffffffff8181e283: cmos_validate_alarm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int cmos_validate_alarm(struct device *dev, struct rtc_wkalrm *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/rtc-cmos.c (0)
Location: drivers/rtc/rtc-cmos.c:379
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff817e4120-ffffffff817e4282: cmos_validate_alarm (STB_LOCAL)
ffffffff817e58d8-ffffffff817e5923: cmos_validate_alarm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int cmos_validate_alarm(struct device *dev, struct rtc_wkalrm *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/rtc-cmos.c (0)
Location: drivers/rtc/rtc-cmos.c:379
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff8185df10-ffffffff8185e072: cmos_validate_alarm (STB_LOCAL)
ffffffff8185f718-ffffffff8185f763: cmos_validate_alarm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int cmos_validate_alarm(struct device *dev, struct rtc_wkalrm *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/rtc-cmos.c (0)
Location: drivers/rtc/rtc-cmos.c:379
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff818792a0-ffffffff81879402: cmos_validate_alarm (STB_LOCAL)
ffffffff8187a925-ffffffff8187a970: cmos_validate_alarm.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
