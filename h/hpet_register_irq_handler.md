# Function: <code>hpet_register_irq_handler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int hpet_register_irq_handler(rtc_irq_handler handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81061fe0)
Location: arch/x86/kernel/hpet.c:1052
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff81061fe0-ffffffff81062024: hpet_register_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int hpet_register_irq_handler(rtc_irq_handler handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81061e10)
Location: arch/x86/kernel/hpet.c:1049
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff81061e10-ffffffff81061e54: hpet_register_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int hpet_register_irq_handler(rtc_irq_handler handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81064ea0)
Location: arch/x86/kernel/hpet.c:1144
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff81064ea0-ffffffff81064ee4: hpet_register_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int hpet_register_irq_handler(rtc_irq_handler handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81063e90)
Location: arch/x86/kernel/hpet.c:1139
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff81063e90-ffffffff81063ed6: hpet_register_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int hpet_register_irq_handler(rtc_irq_handler handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81068010)
Location: arch/x86/kernel/hpet.c:1139
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff81068010-ffffffff81068056: hpet_register_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int hpet_register_irq_handler(rtc_irq_handler handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8106b460)
Location: arch/x86/kernel/hpet.c:1139
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff8106b460-ffffffff8106b4a6: hpet_register_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int hpet_register_irq_handler(rtc_irq_handler handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810711f0)
Location: arch/x86/kernel/hpet.c:1135
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff810711f0-ffffffff81071236: hpet_register_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int hpet_register_irq_handler(rtc_irq_handler handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81075160)
Location: arch/x86/kernel/hpet.c:1049
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff81075160-ffffffff810751a6: hpet_register_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int hpet_register_irq_handler(rtc_irq_handler handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81076130)
Location: arch/x86/kernel/hpet.c:1049
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff81076130-ffffffff81076176: hpet_register_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int hpet_register_irq_handler(rtc_irq_handler handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8107d620)
Location: arch/x86/kernel/hpet.c:1049
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff8107d620-ffffffff8107d666: hpet_register_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int hpet_register_irq_handler(rtc_irq_handler handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8107d590)
Location: arch/x86/kernel/hpet.c:1159
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff8107d590-ffffffff8107d5d6: hpet_register_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int hpet_register_irq_handler(rtc_irq_handler handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8107e4d0)
Location: arch/x86/kernel/hpet.c:1159
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff8107e4d0-ffffffff8107e516: hpet_register_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int hpet_register_irq_handler(rtc_irq_handler handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/hpet.c (0)
Location: arch/x86/kernel/hpet.c:1240
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff81c9ee7a-ffffffff81c9eea4: hpet_register_irq_handler.cold (STB_LOCAL)
ffffffff8108d090-ffffffff8108d102: hpet_register_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int hpet_register_irq_handler(rtc_irq_handler handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/hpet.c (0)
Location: arch/x86/kernel/hpet.c:1240
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff81e4e2f0-ffffffff81e4e31a: hpet_register_irq_handler.cold (STB_LOCAL)
ffffffff8109dd90-ffffffff8109de12: hpet_register_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int hpet_register_irq_handler(rtc_irq_handler handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/hpet.c (0)
Location: arch/x86/kernel/hpet.c:1240
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff820542e5-ffffffff8205430f: hpet_register_irq_handler.cold (STB_LOCAL)
ffffffff810b4fb0-ffffffff810b5032: hpet_register_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int hpet_register_irq_handler(rtc_irq_handler handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/hpet.c (0)
Location: arch/x86/kernel/hpet.c:1242
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff820d28a6-ffffffff820d28d0: hpet_register_irq_handler.cold (STB_LOCAL)
ffffffff810b8080-ffffffff810b8102: hpet_register_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int hpet_register_irq_handler(rtc_irq_handler handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/hpet.c (0)
Location: arch/x86/kernel/hpet.c:1242
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff821ad70c-ffffffff821ad736: hpet_register_irq_handler.cold (STB_LOCAL)
ffffffff810bf4c0-ffffffff810bf542: hpet_register_irq_handler (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int hpet_register_irq_handler(rtc_irq_handler handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81075130)
Location: arch/x86/kernel/hpet.c:1049
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff81075130-ffffffff81075176: hpet_register_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int hpet_register_irq_handler(rtc_irq_handler handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81065160)
Location: arch/x86/kernel/hpet.c:1049
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff81065160-ffffffff810651a6: hpet_register_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int hpet_register_irq_handler(rtc_irq_handler handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810750e0)
Location: arch/x86/kernel/hpet.c:1049
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff810750e0-ffffffff81075126: hpet_register_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int hpet_register_irq_handler(rtc_irq_handler handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81077140)
Location: arch/x86/kernel/hpet.c:1049
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff81077140-ffffffff81077186: hpet_register_irq_handler (STB_GLOBAL)
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
