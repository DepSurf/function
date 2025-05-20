# Function: <code>debug_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810ebb74)
Location: kernel/time/timer.c:655
Inline: True
Inline callers:
  - kernel/time/timer.c:init_timer_key
```
```
In kernel/time/hrtimer.c (ffffffff810ef3b9)
Location: kernel/time/hrtimer.c:441
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810f3914)
Location: kernel/time/timer.c:763
Inline: True
Inline callers:
  - kernel/time/timer.c:init_timer_key
```
```
In kernel/time/hrtimer.c (ffffffff810f6c63)
Location: kernel/time/hrtimer.c:437
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810fac64)
Location: kernel/time/timer.c:763
Inline: True
Inline callers:
  - kernel/time/timer.c:init_timer_key
```
```
In kernel/time/hrtimer.c (ffffffff810fdd1a)
Location: kernel/time/hrtimer.c:437
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81909efa)
Location: kernel/time/timer.c:734
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
```
```
In kernel/time/hrtimer.c (ffffffff810fffd6)
Location: kernel/time/hrtimer.c:438
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81994238)
Location: kernel/time/timer.c:738
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
```
```
In kernel/time/hrtimer.c (ffffffff8110adc6)
Location: kernel/time/hrtimer.c:438
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff819f07b8)
Location: kernel/time/timer.c:755
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
```
```
In kernel/time/hrtimer.c (ffffffff819f0e25)
Location: kernel/time/hrtimer.c:455
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81a2bb38)
Location: kernel/time/timer.c:754
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
```
```
In kernel/time/hrtimer.c (ffffffff81a2c1a5)
Location: kernel/time/hrtimer.c:446
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81a9bd69)
Location: kernel/time/timer.c:756
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
```
```
In kernel/time/hrtimer.c (ffffffff81a9c345)
Location: kernel/time/hrtimer.c:445
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81ad36b9)
Location: kernel/time/timer.c:760
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
```
```
In kernel/time/hrtimer.c (ffffffff811378f5)
Location: kernel/time/hrtimer.c:466
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_init_sleeper
  - kernel/time/hrtimer.c:hrtimer_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81bcb7c3)
Location: kernel/time/timer.c:768
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
```
```
In kernel/time/hrtimer.c (ffffffff81147572)
Location: kernel/time/hrtimer.c:466
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
  - kernel/time/hrtimer.c:hrtimer_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81c44662)
Location: kernel/time/timer.c:768
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
```
```
In kernel/time/hrtimer.c (ffffffff81142a47)
Location: kernel/time/hrtimer.c:465
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_init_sleeper
  - kernel/time/hrtimer.c:hrtimer_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81c378d2)
Location: kernel/time/timer.c:770
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
```
```
In kernel/time/hrtimer.c (ffffffff81143a37)
Location: kernel/time/hrtimer.c:465
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_init_sleeper
  - kernel/time/hrtimer.c:hrtimer_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81d56192)
Location: kernel/time/timer.c:770
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
```
```
In kernel/time/hrtimer.c (ffffffff81d564a8)
Location: kernel/time/hrtimer.c:465
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
  - kernel/time/hrtimer.c:hrtimer_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81f281a4)
Location: kernel/time/timer.c:823
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
```
```
In kernel/time/hrtimer.c (ffffffff8119beb6)
Location: kernel/time/hrtimer.c:465
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
  - kernel/time/hrtimer.c:hrtimer_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff820d3d94)
Location: kernel/time/timer.c:823
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
```
```
In kernel/time/hrtimer.c (ffffffff811da826)
Location: kernel/time/hrtimer.c:465
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
  - kernel/time/hrtimer.c:hrtimer_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff82158014)
Location: kernel/time/timer.c:823
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
```
```
In kernel/time/hrtimer.c (ffffffff811eed4b)
Location: kernel/time/hrtimer.c:467
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
  - kernel/time/hrtimer.c:hrtimer_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8223ae84)
Location: kernel/time/timer.c:820
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
```
```
In kernel/time/hrtimer.c (ffffffff81204ecb)
Location: kernel/time/hrtimer.c:467
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
  - kernel/time/hrtimer.c:hrtimer_init
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffff800010da6374)
Location: kernel/time/timer.c:760
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
```
```
In kernel/time/hrtimer.c (ffff8000101a0f24)
Location: kernel/time/hrtimer.c:466
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_init_sleeper
  - kernel/time/hrtimer.c:hrtimer_init
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c0e9df88)
Location: kernel/time/timer.c:760
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
```
```
In kernel/time/hrtimer.c (c03eaa28)
Location: kernel/time/hrtimer.c:466
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_init_sleeper
  - kernel/time/hrtimer.c:hrtimer_init
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c000000000ee8960)
Location: kernel/time/timer.c:760
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
```
```
In kernel/time/hrtimer.c (c000000000202278)
Location: kernel/time/hrtimer.c:466
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_init_sleeper
  - kernel/time/hrtimer.c:hrtimer_init
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffe0008c86a4)
Location: kernel/time/timer.c:760
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
```
```
In kernel/time/hrtimer.c (ffffffe00012e582)
Location: kernel/time/hrtimer.c:466
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_init_sleeper
  - kernel/time/hrtimer.c:hrtimer_init
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81a72529)
Location: kernel/time/timer.c:760
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
```
```
In kernel/time/hrtimer.c (ffffffff811300a5)
Location: kernel/time/hrtimer.c:466
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_init_sleeper
  - kernel/time/hrtimer.c:hrtimer_init
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81a2e8f9)
Location: kernel/time/timer.c:760
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
```
```
In kernel/time/hrtimer.c (ffffffff81122b15)
Location: kernel/time/hrtimer.c:466
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_init_sleeper
  - kernel/time/hrtimer.c:hrtimer_init
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81ade939)
Location: kernel/time/timer.c:760
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
```
```
In kernel/time/hrtimer.c (ffffffff8112ddc5)
Location: kernel/time/hrtimer.c:466
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_init_sleeper
  - kernel/time/hrtimer.c:hrtimer_init
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81aeadb9)
Location: kernel/time/timer.c:760
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
```
```
In kernel/time/hrtimer.c (ffffffff8113a715)
Location: kernel/time/hrtimer.c:466
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_init_sleeper
  - kernel/time/hrtimer.c:hrtimer_init
```
</details>
</li>
</ul>

## Differences
