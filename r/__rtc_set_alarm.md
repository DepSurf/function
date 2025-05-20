# Function: <code>__rtc_set_alarm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int __rtc_set_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff816740d0)
Location: drivers/rtc/interface.c:306
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_timer_do_work
```
**Symbols:**

```
ffffffff816740d0-ffffffff81674184: __rtc_set_alarm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int __rtc_set_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff816d48c0)
Location: drivers/rtc/interface.c:316
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff816d48c0-ffffffff816d4974: __rtc_set_alarm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int __rtc_set_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff817045a0)
Location: drivers/rtc/interface.c:316
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff817045a0-ffffffff81704654: __rtc_set_alarm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int __rtc_set_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff8171a040)
Location: drivers/rtc/interface.c:323
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff8171a040-ffffffff8171a0f4: __rtc_set_alarm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __rtc_set_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff8178b2b0)
Location: drivers/rtc/interface.c:323
Inline: True
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff8178b2b0-ffffffff8178b367: __rtc_set_alarm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __rtc_set_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff817cce10)
Location: drivers/rtc/interface.c:404
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff817cce10-ffffffff817ccf57: __rtc_set_alarm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __rtc_set_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff817f4180)
Location: drivers/rtc/interface.c:400
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff817f4180-ffffffff817f42c7: __rtc_set_alarm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __rtc_set_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81834ec0)
Location: drivers/rtc/interface.c:392
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_remove
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff81834ec0-ffffffff8183500e: __rtc_set_alarm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __rtc_set_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff818667e0)
Location: drivers/rtc/interface.c:409
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_remove
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff818667e0-ffffffff8186692e: __rtc_set_alarm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __rtc_set_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81939e20)
Location: drivers/rtc/interface.c:409
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff81939e20-ffffffff81939f91: __rtc_set_alarm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __rtc_set_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81940280)
Location: drivers/rtc/interface.c:409
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff81940280-ffffffff819403db: __rtc_set_alarm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __rtc_set_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff819239f0)
Location: drivers/rtc/interface.c:409
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff819239f0-ffffffff81923b56: __rtc_set_alarm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __rtc_set_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff819c6a30)
Location: drivers/rtc/interface.c:409
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff819c6a30-ffffffff819c6b8f: __rtc_set_alarm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __rtc_set_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81b27830)
Location: drivers/rtc/interface.c:409
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff81b27830-ffffffff81b279dc: __rtc_set_alarm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __rtc_set_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81cbb230)
Location: drivers/rtc/interface.c:409
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff81cbb230-ffffffff81cbb3dc: __rtc_set_alarm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __rtc_set_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81d229e0)
Location: drivers/rtc/interface.c:409
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff81d229e0-ffffffff81d22b8c: __rtc_set_alarm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __rtc_set_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81dd8740)
Location: drivers/rtc/interface.c:409
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff81dd8740-ffffffff81dd88ec: __rtc_set_alarm (STB_LOCAL)
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
int __rtc_set_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffff800010aa7a50)
Location: drivers/rtc/interface.c:409
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_remove
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffff800010aa7a50-ffff800010aa7bc4: __rtc_set_alarm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __rtc_set_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (c0b86d90)
Location: drivers/rtc/interface.c:409
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
c0b86d90-c0b86f38: __rtc_set_alarm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __rtc_set_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (c000000000b89c30)
Location: drivers/rtc/interface.c:409
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
c000000000b89c30-c000000000b89e28: __rtc_set_alarm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __rtc_set_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffe0006b3ce2)
Location: drivers/rtc/interface.c:409
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffe0006b3ce2-ffffffe0006b3df4: __rtc_set_alarm (STB_LOCAL)
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
int __rtc_set_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81819490)
Location: drivers/rtc/interface.c:409
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_remove
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff81819490-ffffffff818195de: __rtc_set_alarm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __rtc_set_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff817e0b80)
Location: drivers/rtc/interface.c:409
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_remove
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff817e0b80-ffffffff817e0cce: __rtc_set_alarm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __rtc_set_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff8185a970)
Location: drivers/rtc/interface.c:409
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_remove
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff8185a970-ffffffff8185aabe: __rtc_set_alarm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __rtc_set_alarm(struct rtc_device *rtc, struct rtc_wkalrm *alarm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81875a80)
Location: drivers/rtc/interface.c:409
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_remove
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
**Symbols:**

```
ffffffff81875a80-ffffffff81875be7: __rtc_set_alarm (STB_LOCAL)
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
