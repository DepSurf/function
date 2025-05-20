# Function: <code>rtc_timer_remove</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void rtc_timer_remove(struct rtc_device *rtc, struct rtc_timer *timer);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81674480)
Location: drivers/rtc/interface.c:805
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_timer_start
  - drivers/rtc/interface.c:rtc_timer_cancel
```
**Symbols:**

```
ffffffff81674480-ffffffff816745a4: rtc_timer_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void rtc_timer_remove(struct rtc_device *rtc, struct rtc_timer *timer);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff816d4c30)
Location: drivers/rtc/interface.c:813
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
```
**Symbols:**

```
ffffffff816d4c30-ffffffff816d4d54: rtc_timer_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void rtc_timer_remove(struct rtc_device *rtc, struct rtc_timer *timer);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81704910)
Location: drivers/rtc/interface.c:813
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
```
**Symbols:**

```
ffffffff81704910-ffffffff81704a34: rtc_timer_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void rtc_timer_remove(struct rtc_device *rtc, struct rtc_timer *timer);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff8171a3b0)
Location: drivers/rtc/interface.c:820
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
```
**Symbols:**

```
ffffffff8171a3b0-ffffffff8171a4e6: rtc_timer_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void rtc_timer_remove(struct rtc_device *rtc, struct rtc_timer *timer);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff8178b650)
Location: drivers/rtc/interface.c:820
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
```
**Symbols:**

```
ffffffff8178b650-ffffffff8178b789: rtc_timer_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void rtc_timer_remove(struct rtc_device *rtc, struct rtc_timer *timer);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff817cd4b0)
Location: drivers/rtc/interface.c:925
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
```
**Symbols:**

```
ffffffff817cd4b0-ffffffff817cd617: rtc_timer_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void rtc_timer_remove(struct rtc_device *rtc, struct rtc_timer *timer);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff817f4930)
Location: drivers/rtc/interface.c:851
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
```
**Symbols:**

```
ffffffff817f4930-ffffffff817f4a8c: rtc_timer_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void rtc_timer_remove(struct rtc_device *rtc, struct rtc_timer *timer);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81835960)
Location: drivers/rtc/interface.c:843
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
```
**Symbols:**

```
ffffffff81835960-ffffffff81835abf: rtc_timer_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void rtc_timer_remove(struct rtc_device *rtc, struct rtc_timer *timer);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81867130)
Location: drivers/rtc/interface.c:851
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
```
**Symbols:**

```
ffffffff81867130-ffffffff8186728f: rtc_timer_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rtc_timer_remove(struct rtc_device *rtc, struct rtc_timer *timer);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rtc/interface.c (ffffffff8193bdd1)
Location: drivers/rtc/interface.c:865
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:rtc_set_alarm
```
**Symbols:**

```
ffffffff8193a3f0-ffffffff8193a4c1: rtc_timer_remove.part.0 (STB_LOCAL)
ffffffff8193a4d0-ffffffff8193a56b: rtc_timer_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void rtc_timer_remove(struct rtc_device *rtc, struct rtc_timer *timer);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81940820)
Location: drivers/rtc/interface.c:865
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:rtc_set_alarm
```
**Symbols:**

```
ffffffff81940820-ffffffff8194096a: rtc_timer_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rtc_timer_remove(struct rtc_device *rtc, struct rtc_timer *timer);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rtc/interface.c (ffffffff8192581d)
Location: drivers/rtc/interface.c:851
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:rtc_set_alarm
```
**Symbols:**

```
ffffffff81923da0-ffffffff81923e69: rtc_timer_remove.part.0 (STB_LOCAL)
ffffffff819242d0-ffffffff81924352: rtc_timer_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rtc_timer_remove(struct rtc_device *rtc, struct rtc_timer *timer);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rtc/interface.c (ffffffff819c878d)
Location: drivers/rtc/interface.c:851
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:rtc_set_alarm
```
**Symbols:**

```
ffffffff819c6dd0-ffffffff819c6e99: rtc_timer_remove.part.0 (STB_LOCAL)
ffffffff819c7300-ffffffff819c737f: rtc_timer_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rtc_timer_remove(struct rtc_device *rtc, struct rtc_timer *timer);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81b296d7)
Location: drivers/rtc/interface.c:865
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
```
**Symbols:**

```
ffffffff81b27f50-ffffffff81b28051: rtc_timer_remove.part.0 (STB_LOCAL)
ffffffff81b28060-ffffffff81b280fe: rtc_timer_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rtc_timer_remove(struct rtc_device *rtc, struct rtc_timer *timer);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81cbd2a7)
Location: drivers/rtc/interface.c:865
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:rtc_set_alarm
```
**Symbols:**

```
ffffffff81cbb830-ffffffff81cbb931: rtc_timer_remove.part.0 (STB_LOCAL)
ffffffff81cbbad0-ffffffff81cbbb6e: rtc_timer_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rtc_timer_remove(struct rtc_device *rtc, struct rtc_timer *timer);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81d24bb7)
Location: drivers/rtc/interface.c:865
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
  - drivers/rtc/interface.c:rtc_update_irq_enable
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:rtc_set_alarm
```
**Symbols:**

```
ffffffff81d22fb0-ffffffff81d230b1: rtc_timer_remove.part.0 (STB_LOCAL)
ffffffff81d23380-ffffffff81d2341e: rtc_timer_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rtc_timer_remove(struct rtc_device *rtc, struct rtc_timer *timer);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81dda917)
Location: drivers/rtc/interface.c:865
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
  - drivers/rtc/interface.c:rtc_update_irq_enable
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:rtc_set_alarm
```
**Symbols:**

```
ffffffff81dd8d10-ffffffff81dd8e11: rtc_timer_remove.part.0 (STB_LOCAL)
ffffffff81dd90e0-ffffffff81dd917e: rtc_timer_remove (STB_LOCAL)
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
void rtc_timer_remove(struct rtc_device *rtc, struct rtc_timer *timer);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffff800010aa8580)
Location: drivers/rtc/interface.c:851
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
```
**Symbols:**

```
ffff800010aa8580-ffff800010aa86e8: rtc_timer_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void rtc_timer_remove(struct rtc_device *rtc, struct rtc_timer *timer);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (c0b8736c)
Location: drivers/rtc/interface.c:851
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
```
**Symbols:**

```
c0b8736c-c0b874e0: rtc_timer_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void rtc_timer_remove(struct rtc_device *rtc, struct rtc_timer *timer);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (c000000000b8a990)
Location: drivers/rtc/interface.c:851
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
```
**Symbols:**

```
c000000000b8a990-c000000000b8ab58: rtc_timer_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void rtc_timer_remove(struct rtc_device *rtc, struct rtc_timer *timer);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffe0006b402e)
Location: drivers/rtc/interface.c:851
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
```
**Symbols:**

```
ffffffe0006b402e-ffffffe0006b4168: rtc_timer_remove (STB_LOCAL)
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
void rtc_timer_remove(struct rtc_device *rtc, struct rtc_timer *timer);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81819de0)
Location: drivers/rtc/interface.c:851
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
```
**Symbols:**

```
ffffffff81819de0-ffffffff81819f3f: rtc_timer_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void rtc_timer_remove(struct rtc_device *rtc, struct rtc_timer *timer);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff817e14d0)
Location: drivers/rtc/interface.c:851
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
```
**Symbols:**

```
ffffffff817e14d0-ffffffff817e162f: rtc_timer_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void rtc_timer_remove(struct rtc_device *rtc, struct rtc_timer *timer);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff8185b2c0)
Location: drivers/rtc/interface.c:851
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
```
**Symbols:**

```
ffffffff8185b2c0-ffffffff8185b41f: rtc_timer_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void rtc_timer_remove(struct rtc_device *rtc, struct rtc_timer *timer);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81876450)
Location: drivers/rtc/interface.c:851
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
```
**Symbols:**

```
ffffffff81876450-ffffffff818765ba: rtc_timer_remove (STB_LOCAL)
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
