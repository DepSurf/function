# Function: <code>__rtc_read_time</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int __rtc_read_time(struct rtc_device *rtc, struct rtc_time *tm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81673fa0)
Location: drivers/rtc/interface.c:23
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_read_time
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_timer_do_work
```
**Symbols:**

```
ffffffff81673fa0-ffffffff81674079: __rtc_read_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int __rtc_read_time(struct rtc_device *rtc, struct rtc_time *tm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff816d4780)
Location: drivers/rtc/interface.c:23
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_read_time
```
**Symbols:**

```
ffffffff816d4780-ffffffff816d4863: __rtc_read_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int __rtc_read_time(struct rtc_device *rtc, struct rtc_time *tm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81704460)
Location: drivers/rtc/interface.c:23
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_read_time
```
**Symbols:**

```
ffffffff81704460-ffffffff81704543: __rtc_read_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __rtc_read_time(struct rtc_device *rtc, struct rtc_time *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81719c40)
Location: drivers/rtc/interface.c:23
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_read_time
```
**Symbols:**

```
ffffffff81719c40-ffffffff81719d1a: __rtc_read_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __rtc_read_time(struct rtc_device *rtc, struct rtc_time *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff8178aeb0)
Location: drivers/rtc/interface.c:23
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_read_time
```
**Symbols:**

```
ffffffff8178aeb0-ffffffff8178af90: __rtc_read_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __rtc_read_time(struct rtc_device *rtc, struct rtc_time *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff817ccbe0)
Location: drivers/rtc/interface.c:87
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_time
```
**Symbols:**

```
ffffffff817ccbe0-ffffffff817cccf2: __rtc_read_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __rtc_read_time(struct rtc_device *rtc, struct rtc_time *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff817f3f50)
Location: drivers/rtc/interface.c:87
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_time
```
**Symbols:**

```
ffffffff817f3f50-ffffffff817f4062: __rtc_read_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __rtc_read_time(struct rtc_device *rtc, struct rtc_time *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81834c90)
Location: drivers/rtc/interface.c:84
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_time
```
**Symbols:**

```
ffffffff81834c90-ffffffff81834da7: __rtc_read_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __rtc_read_time(struct rtc_device *rtc, struct rtc_time *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff818665b0)
Location: drivers/rtc/interface.c:84
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_time
```
**Symbols:**

```
ffffffff818665b0-ffffffff818666c7: __rtc_read_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __rtc_read_time(struct rtc_device *rtc, struct rtc_time *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81939d00)
Location: drivers/rtc/interface.c:84
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_time
```
**Symbols:**

```
ffffffff81939d00-ffffffff81939e17: __rtc_read_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __rtc_read_time(struct rtc_device *rtc, struct rtc_time *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81940160)
Location: drivers/rtc/interface.c:84
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_time
```
**Symbols:**

```
ffffffff81940160-ffffffff81940277: __rtc_read_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __rtc_read_time(struct rtc_device *rtc, struct rtc_time *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff819238d0)
Location: drivers/rtc/interface.c:84
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_time
```
**Symbols:**

```
ffffffff819238d0-ffffffff819239e7: __rtc_read_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __rtc_read_time(struct rtc_device *rtc, struct rtc_time *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff819c6880)
Location: drivers/rtc/interface.c:84
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_time
```
**Symbols:**

```
ffffffff819c6880-ffffffff819c6991: __rtc_read_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __rtc_read_time(struct rtc_device *rtc, struct rtc_time *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81b276d0)
Location: drivers/rtc/interface.c:84
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_time
```
**Symbols:**

```
ffffffff81b276d0-ffffffff81b27826: __rtc_read_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __rtc_read_time(struct rtc_device *rtc, struct rtc_time *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81cbb0b0)
Location: drivers/rtc/interface.c:84
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_time
```
**Symbols:**

```
ffffffff81cbb0b0-ffffffff81cbb219: __rtc_read_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __rtc_read_time(struct rtc_device *rtc, struct rtc_time *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81d22860)
Location: drivers/rtc/interface.c:84
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_time
```
**Symbols:**

```
ffffffff81d22860-ffffffff81d229c9: __rtc_read_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __rtc_read_time(struct rtc_device *rtc, struct rtc_time *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81dd85c0)
Location: drivers/rtc/interface.c:84
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_time
```
**Symbols:**

```
ffffffff81dd85c0-ffffffff81dd8729: __rtc_read_time (STB_LOCAL)
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
int __rtc_read_time(struct rtc_device *rtc, struct rtc_time *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffff800010aa78c8)
Location: drivers/rtc/interface.c:84
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_time
```
**Symbols:**

```
ffff800010aa78c8-ffff800010aa79f8: __rtc_read_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __rtc_read_time(struct rtc_device *rtc, struct rtc_time *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (c0b86b28)
Location: drivers/rtc/interface.c:84
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_time
```
**Symbols:**

```
c0b86b28-c0b86c34: __rtc_read_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __rtc_read_time(struct rtc_device *rtc, struct rtc_time *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (c000000000b89880)
Location: drivers/rtc/interface.c:84
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_time
```
**Symbols:**

```
c000000000b89880-c000000000b89a50: __rtc_read_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __rtc_read_time(struct rtc_device *rtc, struct rtc_time *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffe0006b3aec)
Location: drivers/rtc/interface.c:84
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_time
```
**Symbols:**

```
ffffffe0006b3aec-ffffffe0006b3bd4: __rtc_read_time (STB_LOCAL)
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
int __rtc_read_time(struct rtc_device *rtc, struct rtc_time *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81819260)
Location: drivers/rtc/interface.c:84
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_time
```
**Symbols:**

```
ffffffff81819260-ffffffff81819377: __rtc_read_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __rtc_read_time(struct rtc_device *rtc, struct rtc_time *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff817e0950)
Location: drivers/rtc/interface.c:84
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_time
```
**Symbols:**

```
ffffffff817e0950-ffffffff817e0a67: __rtc_read_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __rtc_read_time(struct rtc_device *rtc, struct rtc_time *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff8185a740)
Location: drivers/rtc/interface.c:84
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_time
```
**Symbols:**

```
ffffffff8185a740-ffffffff8185a857: __rtc_read_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __rtc_read_time(struct rtc_device *rtc, struct rtc_time *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81875840)
Location: drivers/rtc/interface.c:84
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_time
```
**Symbols:**

```
ffffffff81875840-ffffffff81875957: __rtc_read_time (STB_LOCAL)
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
