# Function: <code>hpet_unregister_irq_handler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void hpet_unregister_irq_handler(rtc_irq_handler handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81062030)
Location: arch/x86/kernel/hpet.c:1069
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
```
**Symbols:**

```
ffffffff81062030-ffffffff8106206d: hpet_unregister_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void hpet_unregister_irq_handler(rtc_irq_handler handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81061e60)
Location: arch/x86/kernel/hpet.c:1066
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
```
**Symbols:**

```
ffffffff81061e60-ffffffff81061e9d: hpet_unregister_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void hpet_unregister_irq_handler(rtc_irq_handler handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81064ef0)
Location: arch/x86/kernel/hpet.c:1161
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
```
**Symbols:**

```
ffffffff81064ef0-ffffffff81064f2d: hpet_unregister_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void hpet_unregister_irq_handler(rtc_irq_handler handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810647b0)
Location: arch/x86/kernel/hpet.c:1156
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
```
**Symbols:**

```
ffffffff810647b0-ffffffff810647ed: hpet_unregister_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void hpet_unregister_irq_handler(rtc_irq_handler handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81068940)
Location: arch/x86/kernel/hpet.c:1156
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
```
**Symbols:**

```
ffffffff81068940-ffffffff8106897d: hpet_unregister_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void hpet_unregister_irq_handler(rtc_irq_handler handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8106ac60)
Location: arch/x86/kernel/hpet.c:1156
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
```
**Symbols:**

```
ffffffff8106ac60-ffffffff8106ac9d: hpet_unregister_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void hpet_unregister_irq_handler(rtc_irq_handler handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810709f0)
Location: arch/x86/kernel/hpet.c:1152
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
```
**Symbols:**

```
ffffffff810709f0-ffffffff81070a2d: hpet_unregister_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void hpet_unregister_irq_handler(rtc_irq_handler handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81074980)
Location: arch/x86/kernel/hpet.c:1066
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
```
**Symbols:**

```
ffffffff81074980-ffffffff810749bd: hpet_unregister_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void hpet_unregister_irq_handler(rtc_irq_handler handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81075950)
Location: arch/x86/kernel/hpet.c:1066
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
```
**Symbols:**

```
ffffffff81075950-ffffffff8107598d: hpet_unregister_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void hpet_unregister_irq_handler(rtc_irq_handler handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8107d560)
Location: arch/x86/kernel/hpet.c:1066
Inline: False
```
**Symbols:**

```
ffffffff8107d560-ffffffff8107d59d: hpet_unregister_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void hpet_unregister_irq_handler(rtc_irq_handler handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8107d500)
Location: arch/x86/kernel/hpet.c:1176
Inline: False
```
**Symbols:**

```
ffffffff8107d500-ffffffff8107d53d: hpet_unregister_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void hpet_unregister_irq_handler(rtc_irq_handler handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8107e440)
Location: arch/x86/kernel/hpet.c:1176
Inline: False
```
**Symbols:**

```
ffffffff8107e440-ffffffff8107e47d: hpet_unregister_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void hpet_unregister_irq_handler(rtc_irq_handler handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/hpet.c (0)
Location: arch/x86/kernel/hpet.c:1257
Inline: False
```
**Symbols:**

```
ffffffff81c9ee1c-ffffffff81c9ee44: hpet_unregister_irq_handler.cold (STB_LOCAL)
ffffffff8108cfa0-ffffffff8108cffa: hpet_unregister_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hpet_unregister_irq_handler(rtc_irq_handler handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8109dc4e)
Location: arch/x86/kernel/hpet.c:1257
Inline: True
```
**Symbols:**

```
ffffffff81e4e26a-ffffffff81e4e292: hpet_unregister_irq_handler.cold (STB_LOCAL)
ffffffff8109dc10-ffffffff8109dc72: hpet_unregister_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hpet_unregister_irq_handler(rtc_irq_handler handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810b4e3e)
Location: arch/x86/kernel/hpet.c:1257
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
```
**Symbols:**

```
ffffffff8205425f-ffffffff82054287: hpet_unregister_irq_handler.cold (STB_LOCAL)
ffffffff810b4e00-ffffffff810b4e62: hpet_unregister_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hpet_unregister_irq_handler(rtc_irq_handler handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810b7f0e)
Location: arch/x86/kernel/hpet.c:1259
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
```
**Symbols:**

```
ffffffff820d2820-ffffffff820d2848: hpet_unregister_irq_handler.cold (STB_LOCAL)
ffffffff810b7ed0-ffffffff810b7f32: hpet_unregister_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hpet_unregister_irq_handler(rtc_irq_handler handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810bf34e)
Location: arch/x86/kernel/hpet.c:1259
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
```
**Symbols:**

```
ffffffff821ad686-ffffffff821ad6ae: hpet_unregister_irq_handler.cold (STB_LOCAL)
ffffffff810bf310-ffffffff810bf372: hpet_unregister_irq_handler (STB_GLOBAL)
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
void hpet_unregister_irq_handler(rtc_irq_handler handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81074950)
Location: arch/x86/kernel/hpet.c:1066
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
```
**Symbols:**

```
ffffffff81074950-ffffffff8107498d: hpet_unregister_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void hpet_unregister_irq_handler(rtc_irq_handler handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81064980)
Location: arch/x86/kernel/hpet.c:1066
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
```
**Symbols:**

```
ffffffff81064980-ffffffff810649bd: hpet_unregister_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void hpet_unregister_irq_handler(rtc_irq_handler handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81074900)
Location: arch/x86/kernel/hpet.c:1066
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
```
**Symbols:**

```
ffffffff81074900-ffffffff8107493d: hpet_unregister_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void hpet_unregister_irq_handler(rtc_irq_handler handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81076960)
Location: arch/x86/kernel/hpet.c:1066
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
```
**Symbols:**

```
ffffffff81076960-ffffffff8107699d: hpet_unregister_irq_handler (STB_GLOBAL)
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
