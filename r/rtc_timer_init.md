# Function: <code>rtc_timer_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void rtc_timer_init(struct rtc_timer *timer, void (*f)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81675280)
Location: drivers/rtc/interface.c:909
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
  - drivers/rtc/class.c:rtc_device_register
  - drivers/rtc/class.c:rtc_device_register
```
**Symbols:**

```
ffffffff81675280-ffffffff816752a1: rtc_timer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void rtc_timer_init(struct rtc_timer *timer, void (*f)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff816d5a50)
Location: drivers/rtc/interface.c:917
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
  - drivers/rtc/class.c:rtc_device_register
  - drivers/rtc/class.c:rtc_device_register
```
**Symbols:**

```
ffffffff816d5a50-ffffffff816d5a71: rtc_timer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void rtc_timer_init(struct rtc_timer *timer, void (*f)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81705730)
Location: drivers/rtc/interface.c:917
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
  - drivers/rtc/class.c:rtc_device_register
  - drivers/rtc/class.c:rtc_device_register
```
**Symbols:**

```
ffffffff81705730-ffffffff81705751: rtc_timer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rtc_timer_init(struct rtc_timer *timer, void (*f)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff8171b1d0)
Location: drivers/rtc/interface.c:924
Inline: False
Direct callers:
  - drivers/rtc/class.c:rtc_allocate_device
  - drivers/rtc/class.c:rtc_allocate_device
```
**Symbols:**

```
ffffffff8171b1d0-ffffffff8171b1f1: rtc_timer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rtc_timer_init(struct rtc_timer *timer, void (*f)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff8178c470)
Location: drivers/rtc/interface.c:924
Inline: False
Direct callers:
  - drivers/rtc/class.c:rtc_allocate_device
  - drivers/rtc/class.c:rtc_allocate_device
```
**Symbols:**

```
ffffffff8178c470-ffffffff8178c491: rtc_timer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rtc_timer_init(struct rtc_timer *timer, void (*f)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff817ce9f0)
Location: drivers/rtc/interface.c:1034
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
  - drivers/rtc/class.c:rtc_allocate_device
  - drivers/rtc/class.c:rtc_allocate_device
```
**Symbols:**

```
ffffffff817ce9f0-ffffffff817cea11: rtc_timer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rtc_timer_init(struct rtc_timer *timer, void (*f)(struct rtc_device *), struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff817f5b30)
Location: drivers/rtc/interface.c:960
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
**Symbols:**

```
ffffffff817f5b30-ffffffff817f5b4d: rtc_timer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rtc_timer_init(struct rtc_timer *timer, void (*f)(struct rtc_device *), struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff818367f0)
Location: drivers/rtc/interface.c:954
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
**Symbols:**

```
ffffffff818367f0-ffffffff8183680d: rtc_timer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rtc_timer_init(struct rtc_timer *timer, void (*f)(struct rtc_device *), struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81868160)
Location: drivers/rtc/interface.c:962
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
**Symbols:**

```
ffffffff81868160-ffffffff8186817d: rtc_timer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rtc_timer_init(struct rtc_timer *timer, void (*f)(struct rtc_device *), struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff8193bc80)
Location: drivers/rtc/interface.c:975
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
  - drivers/rtc/class.c:rtc_allocate_device
  - drivers/rtc/class.c:rtc_allocate_device
```
**Symbols:**

```
ffffffff8193bc80-ffffffff8193bc9d: rtc_timer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rtc_timer_init(struct rtc_timer *timer, void (*f)(struct rtc_device *), struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81941f50)
Location: drivers/rtc/interface.c:975
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
  - drivers/rtc/class.c:rtc_allocate_device
  - drivers/rtc/class.c:rtc_allocate_device
```
**Symbols:**

```
ffffffff81941f50-ffffffff81941f6d: rtc_timer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rtc_timer_init(struct rtc_timer *timer, void (*f)(struct rtc_device *), struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff819256e0)
Location: drivers/rtc/interface.c:961
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
**Symbols:**

```
ffffffff819256e0-ffffffff819256fd: rtc_timer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rtc_timer_init(struct rtc_timer *timer, void (*f)(struct rtc_device *), struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff819c8660)
Location: drivers/rtc/interface.c:961
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
**Symbols:**

```
ffffffff819c8660-ffffffff819c867d: rtc_timer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rtc_timer_init(struct rtc_timer *timer, void (*f)(struct rtc_device *), struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81b29570)
Location: drivers/rtc/interface.c:975
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
  - drivers/rtc/class.c:rtc_allocate_device
  - drivers/rtc/class.c:rtc_allocate_device
```
**Symbols:**

```
ffffffff81b29570-ffffffff81b29597: rtc_timer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rtc_timer_init(struct rtc_timer *timer, void (*f)(struct rtc_device *), struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81cbd120)
Location: drivers/rtc/interface.c:975
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
  - drivers/rtc/class.c:rtc_allocate_device
  - drivers/rtc/class.c:rtc_allocate_device
```
**Symbols:**

```
ffffffff81cbd120-ffffffff81cbd147: rtc_timer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rtc_timer_init(struct rtc_timer *timer, void (*f)(struct rtc_device *), struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81d24a30)
Location: drivers/rtc/interface.c:975
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
  - drivers/rtc/class.c:rtc_allocate_device
  - drivers/rtc/class.c:rtc_allocate_device
```
**Symbols:**

```
ffffffff81d24a30-ffffffff81d24a57: rtc_timer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rtc_timer_init(struct rtc_timer *timer, void (*f)(struct rtc_device *), struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81dda790)
Location: drivers/rtc/interface.c:975
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
  - drivers/rtc/class.c:rtc_allocate_device
  - drivers/rtc/class.c:rtc_allocate_device
```
**Symbols:**

```
ffffffff81dda790-ffffffff81dda7b7: rtc_timer_init (STB_GLOBAL)
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
void rtc_timer_init(struct rtc_timer *timer, void (*f)(struct rtc_device *), struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffff800010aa9de8)
Location: drivers/rtc/interface.c:962
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
**Symbols:**

```
ffff800010aa9de8-ffff800010aa9e28: rtc_timer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rtc_timer_init(struct rtc_timer *timer, void (*f)(struct rtc_device *), struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (c0b88c4c)
Location: drivers/rtc/interface.c:962
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
**Symbols:**

```
c0b88c4c-c0b88c74: rtc_timer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rtc_timer_init(struct rtc_timer *timer, void (*f)(struct rtc_device *), struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (c000000000b8bfe0)
Location: drivers/rtc/interface.c:962
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
**Symbols:**

```
c000000000b8bfe0-c000000000b8c000: rtc_timer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rtc_timer_init(struct rtc_timer *timer, void (*f)(struct rtc_device *), struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffe0006b53e6)
Location: drivers/rtc/interface.c:962
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
**Symbols:**

```
ffffffe0006b53e6-ffffffe0006b5420: rtc_timer_init (STB_GLOBAL)
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
void rtc_timer_init(struct rtc_timer *timer, void (*f)(struct rtc_device *), struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff8181ae10)
Location: drivers/rtc/interface.c:962
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
**Symbols:**

```
ffffffff8181ae10-ffffffff8181ae2d: rtc_timer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rtc_timer_init(struct rtc_timer *timer, void (*f)(struct rtc_device *), struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff817e2500)
Location: drivers/rtc/interface.c:962
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
**Symbols:**

```
ffffffff817e2500-ffffffff817e251d: rtc_timer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rtc_timer_init(struct rtc_timer *timer, void (*f)(struct rtc_device *), struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff8185c2f0)
Location: drivers/rtc/interface.c:962
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
**Symbols:**

```
ffffffff8185c2f0-ffffffff8185c30d: rtc_timer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rtc_timer_init(struct rtc_timer *timer, void (*f)(struct rtc_device *), struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81877550)
Location: drivers/rtc/interface.c:962
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
**Symbols:**

```
ffffffff81877550-ffffffff8187756d: rtc_timer_init (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct rtc_device *rtc</code>
</li>
<li>
<b>Param removed. </b>
<code>void *data</code>
</li>
<li>
<b>Param type changed. </b>
<code>void (*f)(void *)</code> ➡️ <code>void (*f)(struct rtc_device *)</code>
</li>
</ul>
</details>
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
