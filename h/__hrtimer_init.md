# Function: <code>__hrtimer_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810eeca0)
Location: kernel/time/hrtimer.c:1125
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
**Symbols:**

```
ffffffff810eeca0-ffffffff810eed2d: __hrtimer_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810f5d50)
Location: kernel/time/hrtimer.c:1115
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
```
**Symbols:**

```
ffffffff810f5d50-ffffffff810f5de1: __hrtimer_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810fce80)
Location: kernel/time/hrtimer.c:1115
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
```
**Symbols:**

```
ffffffff810fce80-ffffffff810fcf11: __hrtimer_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810ff290)
Location: kernel/time/hrtimer.c:1097
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
```
**Symbols:**

```
ffffffff810ff290-ffffffff810ff340: __hrtimer_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8110a070)
Location: kernel/time/hrtimer.c:1097
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
```
**Symbols:**

```
ffffffff8110a070-ffffffff8110a12c: __hrtimer_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81115860)
Location: kernel/time/hrtimer.c:1268
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
```
**Symbols:**

```
ffffffff81115860-ffffffff81115916: __hrtimer_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81120f30)
Location: kernel/time/hrtimer.c:1259
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
```
**Symbols:**

```
ffffffff81120f30-ffffffff81120fe6: __hrtimer_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112b760)
Location: kernel/time/hrtimer.c:1259
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
```
**Symbols:**

```
ffffffff8112b760-ffffffff8112b80f: __hrtimer_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81137830)
Location: kernel/time/hrtimer.c:1376
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_init_sleeper
  - kernel/time/hrtimer.c:hrtimer_init
```
**Symbols:**

```
ffffffff81137830-ffffffff811378e9: __hrtimer_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81146230)
Location: kernel/time/hrtimer.c:1376
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
  - kernel/time/hrtimer.c:hrtimer_init
```
**Symbols:**

```
ffffffff81146230-ffffffff811462ff: __hrtimer_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81142750)
Location: kernel/time/hrtimer.c:1393
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_init_sleeper
  - kernel/time/hrtimer.c:hrtimer_init
```
**Symbols:**

```
ffffffff81142750-ffffffff8114281f: __hrtimer_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81143920)
Location: kernel/time/hrtimer.c:1393
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_init_sleeper
  - kernel/time/hrtimer.c:hrtimer_init
```
**Symbols:**

```
ffffffff81143920-ffffffff811439e3: __hrtimer_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81166d10)
Location: kernel/time/hrtimer.c:1541
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
  - kernel/time/hrtimer.c:hrtimer_init
```
**Symbols:**

```
ffffffff81166d10-ffffffff81166e15: __hrtimer_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81f286c0)
Location: kernel/time/hrtimer.c:1541
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_init
```
**Symbols:**

```
ffffffff8119a4f0-ffffffff8119a617: __hrtimer_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff820d4300)
Location: kernel/time/hrtimer.c:1541
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_init
```
**Symbols:**

```
ffffffff811d8c60-ffffffff811d8d87: __hrtimer_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811ed090)
Location: kernel/time/hrtimer.c:1544
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
  - kernel/time/hrtimer.c:hrtimer_init
```
**Symbols:**

```
ffffffff811ed090-ffffffff811ed1d9: __hrtimer_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff812032c0)
Location: kernel/time/hrtimer.c:1545
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
  - kernel/time/hrtimer.c:hrtimer_init
```
**Symbols:**

```
ffffffff812032c0-ffffffff81203409: __hrtimer_init (STB_LOCAL)
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
void __hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffff8000101a0d58)
Location: kernel/time/hrtimer.c:1376
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_init_sleeper
  - kernel/time/hrtimer.c:hrtimer_init
  - kernel/time/hrtimer.c:hrtimer_init
```
**Symbols:**

```
ffff8000101a0d58-ffff8000101a0e28: __hrtimer_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c03ea948)
Location: kernel/time/hrtimer.c:1376
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_init_sleeper
  - kernel/time/hrtimer.c:hrtimer_init
```
**Symbols:**

```
c03ea948-c03eaa14: __hrtimer_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c0000000002020e0)
Location: kernel/time/hrtimer.c:1376
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_init_sleeper
  - kernel/time/hrtimer.c:hrtimer_init_sleeper
  - kernel/time/hrtimer.c:hrtimer_init
  - kernel/time/hrtimer.c:hrtimer_init
```
**Symbols:**

```
c0000000002020e0-c000000000202244: __hrtimer_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffe00012e48c)
Location: kernel/time/hrtimer.c:1376
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_init_sleeper
  - kernel/time/hrtimer.c:hrtimer_init
```
**Symbols:**

```
ffffffe00012e48c-ffffffe00012e562: __hrtimer_init (STB_LOCAL)
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
void __hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112ffe0)
Location: kernel/time/hrtimer.c:1376
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_init_sleeper
  - kernel/time/hrtimer.c:hrtimer_init
```
**Symbols:**

```
ffffffff8112ffe0-ffffffff81130099: __hrtimer_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81122a50)
Location: kernel/time/hrtimer.c:1376
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_init_sleeper
  - kernel/time/hrtimer.c:hrtimer_init
```
**Symbols:**

```
ffffffff81122a50-ffffffff81122b09: __hrtimer_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112dd00)
Location: kernel/time/hrtimer.c:1376
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_init_sleeper
  - kernel/time/hrtimer.c:hrtimer_init
```
**Symbols:**

```
ffffffff8112dd00-ffffffff8112ddb9: __hrtimer_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8113a650)
Location: kernel/time/hrtimer.c:1376
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_init_sleeper
  - kernel/time/hrtimer.c:hrtimer_init
```
**Symbols:**

```
ffffffff8113a650-ffffffff8113a709: __hrtimer_init (STB_LOCAL)
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
