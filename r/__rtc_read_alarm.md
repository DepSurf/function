# Function: <code>__rtc_read_alarm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __rtc_read_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81674aa0)
Location: drivers/rtc/interface.c:115
Inline: False
Direct callers:
  - drivers/rtc/class.c:rtc_device_register
```
**Symbols:**

```
ffffffff81674aa0-ffffffff81674efa: __rtc_read_alarm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __rtc_read_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff816d52b0)
Location: drivers/rtc/interface.c:125
Inline: False
Direct callers:
  - drivers/rtc/class.c:rtc_device_register
```
**Symbols:**

```
ffffffff816d52b0-ffffffff816d56ca: __rtc_read_alarm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __rtc_read_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81704f90)
Location: drivers/rtc/interface.c:125
Inline: False
Direct callers:
  - drivers/rtc/class.c:rtc_device_register
```
**Symbols:**

```
ffffffff81704f90-ffffffff817053aa: __rtc_read_alarm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __rtc_read_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff8171aa70)
Location: drivers/rtc/interface.c:125
Inline: False
Direct callers:
  - drivers/rtc/class.c:__rtc_register_device
  - drivers/rtc/class.c:rtc_device_register
```
**Symbols:**

```
ffffffff8171aa70-ffffffff8171ae44: __rtc_read_alarm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __rtc_read_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff8178bd10)
Location: drivers/rtc/interface.c:125
Inline: False
Direct callers:
  - drivers/rtc/class.c:__rtc_register_device
  - drivers/rtc/class.c:rtc_device_register
```
**Symbols:**

```
ffffffff8178bd10-ffffffff8178c0ea: __rtc_read_alarm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __rtc_read_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff817ce0a0)
Location: drivers/rtc/interface.c:203
Inline: False
Direct callers:
  - drivers/rtc/class.c:__rtc_register_device
  - drivers/rtc/class.c:rtc_device_register
```
**Symbols:**

```
ffffffff817ce0a0-ffffffff817ce514: __rtc_read_alarm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __rtc_read_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff817f5110)
Location: drivers/rtc/interface.c:203
Inline: False
Direct callers:
  - drivers/rtc/class.c:__rtc_register_device
  - drivers/rtc/class.c:__rtc_register_device
```
**Symbols:**

```
ffffffff817f5110-ffffffff817f5551: __rtc_read_alarm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __rtc_read_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/interface.c (0)
Location: drivers/rtc/interface.c:195
Inline: False
```
**Symbols:**

```
ffffffff81836a8c-ffffffff81836abd: __rtc_read_alarm.cold (STB_LOCAL)
ffffffff81835e20-ffffffff81836214: __rtc_read_alarm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int __rtc_read_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/interface.c (0)
Location: drivers/rtc/interface.c:212
Inline: False
```
**Symbols:**

```
ffffffff818683fc-ffffffff8186842d: __rtc_read_alarm.cold (STB_LOCAL)
ffffffff81867790-ffffffff81867b84: __rtc_read_alarm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __rtc_read_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/interface.c (0)
Location: drivers/rtc/interface.c:212
Inline: False
```
**Symbols:**

```
ffffffff8193bfec-ffffffff8193c01d: __rtc_read_alarm.cold (STB_LOCAL)
ffffffff8193b1a0-ffffffff8193b594: __rtc_read_alarm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __rtc_read_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/interface.c (0)
Location: drivers/rtc/interface.c:212
Inline: False
```
**Symbols:**

```
ffffffff81c245e0-ffffffff81c24611: __rtc_read_alarm.cold (STB_LOCAL)
ffffffff81941530-ffffffff819418fe: __rtc_read_alarm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __rtc_read_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/interface.c (0)
Location: drivers/rtc/interface.c:212
Inline: False
Direct callers:
  - drivers/rtc/class.c:__devm_rtc_register_device
```
**Symbols:**

```
ffffffff81c1669d-ffffffff81c166ce: __rtc_read_alarm.cold (STB_LOCAL)
ffffffff81924cb0-ffffffff8192508b: __rtc_read_alarm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __rtc_read_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/interface.c (0)
Location: drivers/rtc/interface.c:212
Inline: False
Direct callers:
  - drivers/rtc/class.c:__devm_rtc_register_device
```
**Symbols:**

```
ffffffff81d25142-ffffffff81d25173: __rtc_read_alarm.cold (STB_LOCAL)
ffffffff819c7c40-ffffffff819c8018: __rtc_read_alarm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __rtc_read_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/interface.c (0)
Location: drivers/rtc/interface.c:212
Inline: False
Direct callers:
  - drivers/rtc/class.c:__devm_rtc_register_device
```
**Symbols:**

```
ffffffff81ef0f27-ffffffff81ef0f58: __rtc_read_alarm.cold (STB_LOCAL)
ffffffff81b28980-ffffffff81b28dcc: __rtc_read_alarm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __rtc_read_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81cbc460)
Location: drivers/rtc/interface.c:212
Inline: False
Direct callers:
  - drivers/rtc/class.c:__devm_rtc_register_device
  - drivers/rtc/class.c:__devm_rtc_register_device
```
**Symbols:**

```
ffffffff81cbc460-ffffffff81cbc8e1: __rtc_read_alarm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __rtc_read_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81d23d70)
Location: drivers/rtc/interface.c:212
Inline: False
Direct callers:
  - drivers/rtc/class.c:__devm_rtc_register_device
  - drivers/rtc/class.c:__devm_rtc_register_device
```
**Symbols:**

```
ffffffff81d23d70-ffffffff81d241f1: __rtc_read_alarm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __rtc_read_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81dd9ad0)
Location: drivers/rtc/interface.c:212
Inline: False
Direct callers:
  - drivers/rtc/class.c:__devm_rtc_register_device
  - drivers/rtc/class.c:__devm_rtc_register_device
```
**Symbols:**

```
ffffffff81dd9ad0-ffffffff81dd9f5c: __rtc_read_alarm (STB_GLOBAL)
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
int __rtc_read_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffff800010aa9278)
Location: drivers/rtc/interface.c:212
Inline: False
```
**Symbols:**

```
ffff800010aa9278-ffff800010aa9710: __rtc_read_alarm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __rtc_read_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (c0b88084)
Location: drivers/rtc/interface.c:212
Inline: False
```
**Symbols:**

```
c0b88084-c0b8857c: __rtc_read_alarm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __rtc_read_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (c000000000b8b270)
Location: drivers/rtc/interface.c:212
Inline: False
```
**Symbols:**

```
c000000000b8b270-c000000000b8b804: __rtc_read_alarm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __rtc_read_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffe0006b4a92)
Location: drivers/rtc/interface.c:212
Inline: False
```
**Symbols:**

```
ffffffe0006b4a92-ffffffe0006b4e98: __rtc_read_alarm (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int __rtc_read_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/interface.c (0)
Location: drivers/rtc/interface.c:212
Inline: False
```
**Symbols:**

```
ffffffff8181b0ac-ffffffff8181b0dd: __rtc_read_alarm.cold (STB_LOCAL)
ffffffff8181a440-ffffffff8181a834: __rtc_read_alarm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int __rtc_read_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/interface.c (0)
Location: drivers/rtc/interface.c:212
Inline: False
```
**Symbols:**

```
ffffffff817e279c-ffffffff817e27cd: __rtc_read_alarm.cold (STB_LOCAL)
ffffffff817e1b30-ffffffff817e1f24: __rtc_read_alarm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int __rtc_read_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/interface.c (0)
Location: drivers/rtc/interface.c:212
Inline: False
```
**Symbols:**

```
ffffffff8185c58c-ffffffff8185c5bd: __rtc_read_alarm.cold (STB_LOCAL)
ffffffff8185b920-ffffffff8185bd14: __rtc_read_alarm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int __rtc_read_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/interface.c (0)
Location: drivers/rtc/interface.c:212
Inline: False
```
**Symbols:**

```
ffffffff81877807-ffffffff81877838: __rtc_read_alarm.cold (STB_LOCAL)
ffffffff81876af0-ffffffff81876efd: __rtc_read_alarm (STB_GLOBAL)
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
