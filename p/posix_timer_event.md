# Function: <code>posix_timer_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int posix_timer_event(struct k_itimer *timr, int si_private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff810f0d90)
Location: kernel/time/posix-timers.c:406
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_timer_fn
  - kernel/time/alarmtimer.c:alarm_handle_timer
```
**Symbols:**

```
ffffffff810f0d90-ffffffff810f0dd6: posix_timer_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int posix_timer_event(struct k_itimer *timr, int si_private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff810f7d90)
Location: kernel/time/posix-timers.c:406
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_timer_fn
  - kernel/time/alarmtimer.c:alarm_handle_timer
```
**Symbols:**

```
ffffffff810f7d90-ffffffff810f7dd6: posix_timer_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int posix_timer_event(struct k_itimer *timr, int si_private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81105730)
Location: kernel/time/posix-timers.c:406
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarm_handle_timer
  - kernel/time/posix-timers.c:posix_timer_fn
```
**Symbols:**

```
ffffffff81105730-ffffffff81105776: posix_timer_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int posix_timer_event(struct k_itimer *timr, int si_private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811083a0)
Location: kernel/time/posix-timers.c:332
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarm_handle_timer
  - kernel/time/posix-timers.c:posix_timer_fn
```
**Symbols:**

```
ffffffff811083a0-ffffffff811083e7: posix_timer_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int posix_timer_event(struct k_itimer *timr, int si_private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81113550)
Location: kernel/time/posix-timers.c:333
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarm_handle_timer
  - kernel/time/posix-timers.c:posix_timer_fn
```
**Symbols:**

```
ffffffff81113550-ffffffff81113597: posix_timer_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int posix_timer_event(struct k_itimer *timr, int si_private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811208d0)
Location: kernel/time/posix-timers.c:343
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarm_handle_timer
  - kernel/time/posix-timers.c:posix_timer_fn
```
**Symbols:**

```
ffffffff811208d0-ffffffff81120917: posix_timer_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int posix_timer_event(struct k_itimer *timr, int si_private);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8112982b)
Location: kernel/time/posix-timers.c:310
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_timer_fn
Direct callers:
  - kernel/time/alarmtimer.c:alarm_handle_timer
```
**Symbols:**

```
ffffffff8112c0b0-ffffffff8112c0e0: posix_timer_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int posix_timer_event(struct k_itimer *timr, int si_private);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811342ab)
Location: kernel/time/posix-timers.c:310
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_timer_fn
Direct callers:
  - kernel/time/alarmtimer.c:alarm_handle_timer
```
**Symbols:**

```
ffffffff81136880-ffffffff811368b0: posix_timer_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int posix_timer_event(struct k_itimer *timr, int si_private);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811402bb)
Location: kernel/time/posix-timers.c:310
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_timer_fn
Direct callers:
  - kernel/time/alarmtimer.c:alarm_handle_timer
```
**Symbols:**

```
ffffffff81142930-ffffffff81142960: posix_timer_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int posix_timer_event(struct k_itimer *timr, int si_private);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8115063b)
Location: kernel/time/posix-timers.c:336
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_timer_fn
Direct callers:
  - kernel/time/alarmtimer.c:alarm_handle_timer
```
**Symbols:**

```
ffffffff81152390-ffffffff811523c0: posix_timer_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int posix_timer_event(struct k_itimer *timr, int si_private);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114c8bb)
Location: kernel/time/posix-timers.c:336
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_timer_fn
Direct callers:
  - kernel/time/alarmtimer.c:alarm_handle_timer
```
**Symbols:**

```
ffffffff8114e610-ffffffff8114e640: posix_timer_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int posix_timer_event(struct k_itimer *timr, int si_private);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114dd7b)
Location: kernel/time/posix-timers.c:336
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_timer_fn
Direct callers:
  - kernel/time/alarmtimer.c:alarm_handle_timer
```
**Symbols:**

```
ffffffff8114fab0-ffffffff8114fae0: posix_timer_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int posix_timer_event(struct k_itimer *timr, int si_private);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81171c0b)
Location: kernel/time/posix-timers.c:336
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_timer_fn
Direct callers:
  - kernel/time/alarmtimer.c:alarm_handle_timer
```
**Symbols:**

```
ffffffff81173c90-ffffffff81173cc0: posix_timer_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int posix_timer_event(struct k_itimer *timr, int si_private);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811a703b)
Location: kernel/time/posix-timers.c:336
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_timer_fn
Direct callers:
  - kernel/time/alarmtimer.c:alarm_handle_timer
```
**Symbols:**

```
ffffffff811a8860-ffffffff811a889a: posix_timer_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int posix_timer_event(struct k_itimer *timr, int si_private);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811e6c5b)
Location: kernel/time/posix-timers.c:336
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_timer_fn
Direct callers:
  - kernel/time/alarmtimer.c:alarm_handle_timer
```
**Symbols:**

```
ffffffff811e8650-ffffffff811e868a: posix_timer_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int posix_timer_event(struct k_itimer *timr, int si_private);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811fb25b)
Location: kernel/time/posix-timers.c:280
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_timer_fn
Direct callers:
  - kernel/time/alarmtimer.c:alarm_handle_timer
```
**Symbols:**

```
ffffffff811fcc40-ffffffff811fcc7a: posix_timer_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int posix_timer_event(struct k_itimer *timr, int si_private);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8121144b)
Location: kernel/time/posix-timers.c:280
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_timer_fn
Direct callers:
  - kernel/time/alarmtimer.c:alarm_handle_timer
```
**Symbols:**

```
ffffffff81212e30-ffffffff81212e6a: posix_timer_event (STB_GLOBAL)
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
int posix_timer_event(struct k_itimer *timr, int si_private);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffff8000101ab580)
Location: kernel/time/posix-timers.c:310
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_timer_fn
Direct callers:
  - kernel/time/alarmtimer.c:alarm_handle_timer
```
**Symbols:**

```
ffff8000101ac9b8-ffff8000101aca04: posix_timer_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int posix_timer_event(struct k_itimer *timr, int si_private);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (c03f5b00)
Location: kernel/time/posix-timers.c:310
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_timer_fn
Direct callers:
  - kernel/time/alarmtimer.c:alarm_handle_timer
```
**Symbols:**

```
c03f6aec-c03f6b34: posix_timer_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int posix_timer_event(struct k_itimer *timr, int si_private);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (c00000000020dfa0)
Location: kernel/time/posix-timers.c:310
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_timer_fn
Direct callers:
  - kernel/time/alarmtimer.c:alarm_handle_timer
```
**Symbols:**

```
c000000000210800-c00000000021085c: posix_timer_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int posix_timer_event(struct k_itimer *timr, int si_private);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffe000135a2e)
Location: kernel/time/posix-timers.c:310
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_timer_fn
Direct callers:
  - kernel/time/alarmtimer.c:alarm_handle_timer
```
**Symbols:**

```
ffffffe000136544-ffffffe00013658c: posix_timer_event (STB_GLOBAL)
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
int posix_timer_event(struct k_itimer *timr, int si_private);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81138a6b)
Location: kernel/time/posix-timers.c:310
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_timer_fn
Direct callers:
  - kernel/time/alarmtimer.c:alarm_handle_timer
```
**Symbols:**

```
ffffffff8113b0e0-ffffffff8113b110: posix_timer_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int posix_timer_event(struct k_itimer *timr, int si_private);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8112b4bb)
Location: kernel/time/posix-timers.c:310
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_timer_fn
Direct callers:
  - kernel/time/alarmtimer.c:alarm_handle_timer
```
**Symbols:**

```
ffffffff8112db30-ffffffff8112db60: posix_timer_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int posix_timer_event(struct k_itimer *timr, int si_private);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8113678b)
Location: kernel/time/posix-timers.c:310
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_timer_fn
Direct callers:
  - kernel/time/alarmtimer.c:alarm_handle_timer
```
**Symbols:**

```
ffffffff81138e00-ffffffff81138e30: posix_timer_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int posix_timer_event(struct k_itimer *timr, int si_private);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114321b)
Location: kernel/time/posix-timers.c:310
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_timer_fn
Direct callers:
  - kernel/time/alarmtimer.c:alarm_handle_timer
```
**Symbols:**

```
ffffffff811458b0-ffffffff811458e0: posix_timer_event (STB_GLOBAL)
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
