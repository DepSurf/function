# Function: <code>rtc_update_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void rtc_update_irq(struct rtc_device *rtc, long unsigned int num, long unsigned int events);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81674440)
Location: drivers/rtc/interface.c:564
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
**Symbols:**

```
ffffffff81674440-ffffffff8167447f: rtc_update_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void rtc_update_irq(struct rtc_device *rtc, long unsigned int num, long unsigned int events);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff816d4f10)
Location: drivers/rtc/interface.c:572
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
```
**Symbols:**

```
ffffffff816d4f10-ffffffff816d4f4f: rtc_update_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void rtc_update_irq(struct rtc_device *rtc, long unsigned int num, long unsigned int events);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81704e20)
Location: drivers/rtc/interface.c:572
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
```
**Symbols:**

```
ffffffff81704e20-ffffffff81704e5f: rtc_update_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void rtc_update_irq(struct rtc_device *rtc, long unsigned int num, long unsigned int events);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff8171a900)
Location: drivers/rtc/interface.c:579
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
```
**Symbols:**

```
ffffffff8171a900-ffffffff8171a940: rtc_update_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void rtc_update_irq(struct rtc_device *rtc, long unsigned int num, long unsigned int events);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff8178bba0)
Location: drivers/rtc/interface.c:579
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
```
**Symbols:**

```
ffffffff8178bba0-ffffffff8178bbe0: rtc_update_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void rtc_update_irq(struct rtc_device *rtc, long unsigned int num, long unsigned int events);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff817cd120)
Location: drivers/rtc/interface.c:677
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
```
**Symbols:**

```
ffffffff817cd120-ffffffff817cd15f: rtc_update_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void rtc_update_irq(struct rtc_device *rtc, long unsigned int num, long unsigned int events);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff817f4490)
Location: drivers/rtc/interface.c:664
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
```
**Symbols:**

```
ffffffff817f4490-ffffffff817f44cf: rtc_update_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void rtc_update_irq(struct rtc_device *rtc, long unsigned int num, long unsigned int events);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81835160)
Location: drivers/rtc/interface.c:655
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
```
**Symbols:**

```
ffffffff81835160-ffffffff818351a0: rtc_update_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void rtc_update_irq(struct rtc_device *rtc, long unsigned int num, long unsigned int events);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81866930)
Location: drivers/rtc/interface.c:672
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
```
**Symbols:**

```
ffffffff81866930-ffffffff81866970: rtc_update_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void rtc_update_irq(struct rtc_device *rtc, long unsigned int num, long unsigned int events);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81939fc0)
Location: drivers/rtc/interface.c:686
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
```
**Symbols:**

```
ffffffff81939fc0-ffffffff8193a003: rtc_update_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void rtc_update_irq(struct rtc_device *rtc, long unsigned int num, long unsigned int events);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81940400)
Location: drivers/rtc/interface.c:686
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
```
**Symbols:**

```
ffffffff81940400-ffffffff81940443: rtc_update_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void rtc_update_irq(struct rtc_device *rtc, long unsigned int num, long unsigned int events);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81923b80)
Location: drivers/rtc/interface.c:672
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
```
**Symbols:**

```
ffffffff81923b80-ffffffff81923bc3: rtc_update_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void rtc_update_irq(struct rtc_device *rtc, long unsigned int num, long unsigned int events);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff819c6bb0)
Location: drivers/rtc/interface.c:672
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
```
**Symbols:**

```
ffffffff819c6bb0-ffffffff819c6bf3: rtc_update_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rtc_update_irq(struct rtc_device *rtc, long unsigned int num, long unsigned int events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81b27a20)
Location: drivers/rtc/interface.c:683
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
```
**Symbols:**

```
ffffffff81b27a20-ffffffff81b27a7b: rtc_update_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rtc_update_irq(struct rtc_device *rtc, long unsigned int num, long unsigned int events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81cbb450)
Location: drivers/rtc/interface.c:683
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
```
**Symbols:**

```
ffffffff81cbb450-ffffffff81cbb4ab: rtc_update_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rtc_update_irq(struct rtc_device *rtc, long unsigned int num, long unsigned int events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81d22d00)
Location: drivers/rtc/interface.c:683
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
```
**Symbols:**

```
ffffffff81d22d00-ffffffff81d22d5b: rtc_update_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rtc_update_irq(struct rtc_device *rtc, long unsigned int num, long unsigned int events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81dd8a60)
Location: drivers/rtc/interface.c:683
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
```
**Symbols:**

```
ffffffff81dd8a60-ffffffff81dd8abb: rtc_update_irq (STB_GLOBAL)
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
void rtc_update_irq(struct rtc_device *rtc, long unsigned int num, long unsigned int events);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffff800010aa7bc8)
Location: drivers/rtc/interface.c:672
Inline: True
Direct callers:
  - drivers/rtc/rtc-mv.c:mv_rtc_interrupt
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_alarmirq
```
**Symbols:**

```
ffff800010aa7bc8-ffff800010aa7c14: rtc_update_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void rtc_update_irq(struct rtc_device *rtc, long unsigned int num, long unsigned int events);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (c0b870bc)
Location: drivers/rtc/interface.c:672
Inline: True
Direct callers:
  - drivers/rtc/rtc-mv.c:mv_rtc_interrupt
  - drivers/rtc/rtc-omap.c:rtc_irq
  - drivers/rtc/rtc-s3c.c:s3c6410_rtc_irq
  - drivers/rtc/rtc-s3c.c:s3c24xx_rtc_irq
  - drivers/rtc/rtc-twl.c:twl_rtc_interrupt
```
**Symbols:**

```
c0b870bc-c0b87104: rtc_update_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void rtc_update_irq(struct rtc_device *rtc, long unsigned int num, long unsigned int events);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (c000000000b89e30)
Location: drivers/rtc/interface.c:672
Inline: True
```
**Symbols:**

```
c000000000b89e30-c000000000b89ea0: rtc_update_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void rtc_update_irq(struct rtc_device *rtc, long unsigned int num, long unsigned int events);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffe0006b3df4)
Location: drivers/rtc/interface.c:672
Inline: True
```
**Symbols:**

```
ffffffe0006b3df4-ffffffe0006b3e32: rtc_update_irq (STB_GLOBAL)
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
void rtc_update_irq(struct rtc_device *rtc, long unsigned int num, long unsigned int events);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff818195e0)
Location: drivers/rtc/interface.c:672
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
```
**Symbols:**

```
ffffffff818195e0-ffffffff81819620: rtc_update_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void rtc_update_irq(struct rtc_device *rtc, long unsigned int num, long unsigned int events);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff817e0cd0)
Location: drivers/rtc/interface.c:672
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
```
**Symbols:**

```
ffffffff817e0cd0-ffffffff817e0d10: rtc_update_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void rtc_update_irq(struct rtc_device *rtc, long unsigned int num, long unsigned int events);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff8185aac0)
Location: drivers/rtc/interface.c:672
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
```
**Symbols:**

```
ffffffff8185aac0-ffffffff8185ab00: rtc_update_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void rtc_update_irq(struct rtc_device *rtc, long unsigned int num, long unsigned int events);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81875bf0)
Location: drivers/rtc/interface.c:672
Inline: True
Direct callers:
  - drivers/rtc/rtc-cmos.c:rtc_handler
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
```
**Symbols:**

```
ffffffff81875bf0-ffffffff81875c30: rtc_update_irq (STB_GLOBAL)
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
